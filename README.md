  <p align="center">
    <img title="" src="https://c.tenor.com/NzrqQHFBVz8AAAAj/kitty-transparent.gif" alt=""  width="301" >
  </p>
 <h1>Hello There, Fellow Developers👋🙌</h1>

[![Twitter Badge](https://img.shields.io/badge/-@mframadann-000000?style=for-the-badge&logo=x&logoColor=white&link=https://twitter.com/mframadann)](https://twitter.com/mframadann)
[![Hackerrank Badge](https://img.shields.io/badge/-dev.ramadann-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white&link=https://www.hackerrank.com/profile/dev_ramadann)](https://www.hackerrank.com/profile/dev_ramadann)
[![Linkedin Badge](https://img.shields.io/badge/-Muhamad%20Firly%20Ramadan-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/muhamad-firly-ramadan/)](https://www.linkedin.com/in/muhamad-firly-ramadan/)
[![Gmail Badge](https://img.shields.io/badge/-dev.ramadann@gmail.com-c14438?style=for-the-badge&logo=Gmail&logoColor=white&link=mailto:dev.ramadann@gmail.com)](mailto:dev.ramadann@gmail.com)

```go
package main

import (
    "fmt"
)

type MeowdevvBio map[string]string

func main() {
    fmt.Println("I am Muhamad Firly Ramadan 😃. I am from Cirebon, West Java, Indonesia. I love to explore and learn about technologies.")

    for k, v := range GetBio() {
        fmt.Printf("%+v: %+v\n", k, v)
    }
}

func GetBio() MeowdevvBio {
    return MeowdevvBio{
        "- ⚡ Quick bio:":                    "A kind of Programmer, Coder, Cat Lovers😺",
        "- 🔭 I’m currently working on":      "Kominfo as Junior Software Engineer",
        "- 🌱 I’m currently learning":        "Golang, Keycloack, Docker, Vue JS, Livewire, Filament, Next.js, MySQL",
        "- 👯 I’m looking to collaborate on": "Node.js, Javascript, Typescript ,Golang and Docker related projects",
        "- 🤔 I’m looking for help with":     "Anything related to what I am currently learning:D",
        "- 💬 Ask me about":                  "Node.js, React.JS, Next.js, Golang, PHP, Laravel, SQL, Software Design & Architecture, Web Development and SEO",
        "- 📫 How to reach me:":              "https://instagram.com/mframadann",
    }
}
```
