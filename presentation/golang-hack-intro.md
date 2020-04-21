---
marp: true
theme: default
class: invert
---

# Go Hack

![bg right contain](https://blog.golang.org/gopher/gopher.png)

History of Go & Go on Azure

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
