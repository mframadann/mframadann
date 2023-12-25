```go
package main

import (
	"fmt"
)

type MeowDevvBio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() MeowDevvBio {
	return MeowDevvBio{
		"- ⚡ Quick bio:":                     "A kind of Programmer, Coder, Cat Lovers😺",
		"- 🔭 I’m currently working on":      "Kominfo as Junior Software Engineer",
		"- 🌱 I’m currently learning":        "Golang, Keycloack, Docker, Vue JS",
		"- 👯 I’m looking to collaborate on": "Node.js, Javascript, Typescript ,Golang and Docker related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning:D",
		"- 💬 Ask me about":                  "Node.js, React.JS, Next.js, Golang, PHP, Laravel, SQL, Software Design & Architecture, Web Development and SEO",
		"- 📫 How to reach me:":              "https://github.com/meowdevv",
	}
}
```
