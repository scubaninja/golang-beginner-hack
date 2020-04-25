---
marp: true
theme: default
class: invert
---

# Go Hack

![bg right contain](https://blog.golang.org/gopher/gopher.png)

History of Go & Go on Azure

---

# In Preview

![bg right:60% contain](https://www.thesprucepets.com/thmb/BaQm4xIhuaJ3DPcx777bC1Ll7cM=/960x0/filters:no_upscale():max_bytes(150000):strip_icc()/dog-food-144564301-resized-1-56a26ad43df78cf7727563d1.jpg)

```golang
thisHack := !perfect
```

> Your feedback is critical to assessing value

---

# History of Go

Conceived in 2007 at Google
Released in 2009

> This is very new for a programming language

---

# Why Go

Static typing and runtime efficiency - fast! (like C++)
> No external runtime required like .NET and JAVA, compiles to a single binary
> Short compile times

Ease of programming, high readability (like Python/JavaScript)
> Much less repetitive than Java/C++

Modern, support for multi-core CPUs and distributed environments
> Native support for safely implementing concurrency and parallelism

---
<!-- _class: !invert -->

# Static Typing

Consider this in Python, this is dynamic typing:

```python
b = 1
b = "one" # This is ok
```

Whereas in Go, with static typing:

```go
b := 1    // Create new var of type int
b = "one" // Compiler error
```

---

# Positioning

Where is it a good fit?

- Enterprise Java/C++
- Python/JavaScript
- Organisations considering containerised applications
- Organisations considering distributed/micro-service applications
- Organisations that have an preference for open source

---

# Cloud Native Compute Foundation

The majority graduated projects at the CNCF are written in Go. Here are a selection of graduated and incubating projects at CNCF that use Go:

- Kubernetes (inc. etcd)
- Helm
- Prometheus
- CoreDNS
- containerd
- Vitess

And (not CNCF, but...):

- Terraform

---

# Enterprises using Go

Alright, so we aren't always dealing with organisations like Netflix, so who else uses go:

![height:100](https://consumer-component-library.roocdn.com/19.14.0/static/images/logo-white.ab7fec09c226528ad294a56a53bf5ea6.svg) ![height:100](https://images.metadata.sky.com/pd-image/f97e2aee-7363-47de-90ef-4a86bdc24e2e/16-9/900) ![height:100](https://assets.publishing.service.gov.uk/static/opengraph-image-a1f7d89ffd0782738b1aeb0da37842d8bd0addbd724b8e58c3edbc7287cc11de.png) ![height:100](https://monzo.com/static/images/blog/2016-08-25-monzo/monzo.png)

![height:100](https://www.sainsburys.co.uk/assets/images/logos_logoImage_5TrheyQtjk6OXYZV6GvC1R_sainsburys-logo.svg) ![height:100](https://airports.ie/wp-content/uploads/2016/03/ryanair-logo-2015-version.jpg)
![height:100](https://blueandgreentomorrow.com/wp-content/uploads/2013/11/new-lush-logo.jpg)

This has a UK focus, but loads more here:

> <https://github.com/golang/go/wiki/GoUsers>

---

# Challenges

Where might we see issues?

- Skills in the enterprise dev community
- SDK support, especially on Azure (though it is improving)

> OSS support is good, so we can often use Azure services with an OSS spin
> E.g. CosmosDB with Mongo API

---

# Aim of this Hack

We are not out to **force** people to use Go

Through education, we want to convince them to **consider** using Go if it's a good fit

---

# Go on Azure

How can we deploy Go on Azure:

- Azure Kubernetes Service
- Azure Container Instances
- App Service for Linux (again, containers)

> Are you seeing a pattern here?

---

# Go Resources at Microsoft

If my customer wants help using Go, where can I go?

- CSU - sporadic Go skills - but hopefully improving!
- CSE - extensive Go skills
- Golang Friends Team
