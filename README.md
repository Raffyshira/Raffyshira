# Hi, I'm Rafi Ahsira Prayoga! 👋

> 🇮🇩 **Still learning to become Backend Explorer**  
> Building fast microservices, scalable web apps, and enjoying the journey one `go run` at a time. Always open to collaborate, learn, and discuss tech or space stuff! 🚀

---

```go
package main

import "fmt"

type Developer struct {
    Name     string
    Location string
    Role     string
    Bio      string
    Socials  map[string]string
    Stack    []string
}

func (d Developer) SayHello() {
    fmt.Printf("Hi there, I'm %s 👋\n", d.Name)
    fmt.Printf("%s\n", d.Bio)
    fmt.Println("\nLet's connect and build awesome things together! 🚀")
}

func main() {
    me := Developer{
        Name        : "Rafi Ahsira Prayoga",
        Location    : "Banyuwangi, Indonesia 🇮🇩"
        Role        : "Still Learning as Backend Developer",
        Bio         : "Passionate about building fast microservices, scalable web apps, & exploring the cosmos! 🌌",
        Socials     : map[string]string{
            "Instagram": "[https://www.instagram.com/raffyshira/](https://www.instagram.com/raffyshira/)",
            "Email":     "mailto:rafiahsiraprayoga@gmail.com",
        },
        Stack       : []string{
            "Go", "TypeScript", "Postman", "Redis", 
            "Docker", "Kubernetes", "Cloudflare", "AWS",
        },
    }

    me.SayHello()
}
```
