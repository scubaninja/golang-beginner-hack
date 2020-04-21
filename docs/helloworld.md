# Hello World

> This exercise will ensure that you have all the tools you need to progress through the rest of the hack

Open your terminal (recommend using command prompt, not PowerShell)

Create a ```code``` directory under your %USERPROFILE%.
In there create a folder called ```hello-world-go```

In that folder type ```code .``` to open VS Code

Now create a file & enter the following text:

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

In VS Code press ```CTRL+SHIFT+D``` or click on the Run/Debug icon on the left.

Click the link to create ```launch.json``` and accept the defaults.

Now press ```F5``` or click the run icon to start run your code.
The put should be displayed below and should look something like this:

```bash
API server listening at: 127.0.0.1:29386
hello world
Process exiting with code: 0
```

Next, let's look at the [bookdata-api challenge 1](bookdata-01.md)