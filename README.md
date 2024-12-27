```go
package main

import (
    "fmt"
)

type MyBio map[string]string

func main() {
    fmt.Println("Hi!, My name is Muhamad Firly Ramadan 😃. I am from Cirebon, West Java, Indonesia. I love to explore and learn about programming.")

    for k, v := range GetBiodata() {
        fmt.Printf("%+v: %+v\n", k, v)
    }
}

func GetBiodata() MyBio {
    return MyBio{
        "name":     "Muhamad Firly Ramadan",
        "pronous":  "He/Him",
        "role":     "Back End Developer",
        "skills":   "Javascript, Typescript, Next.js, Nest.js, Golang, PHP, Laravel, Git, Docker, MySQL/PostgreSQL, MongoDB",
    }
}
```
