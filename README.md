# SHWETA MAURYA
<h2 align="center">About me</h2>

```golang

package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}
func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of MusicLover-traveler-foodLover-coder-programmer-catLover",
		"- 🔭 I’m currently working on":      "frontEnd Developer",
		"- 🌱 I’m currently learning":        " php,Full Stack Developer)",
		"- 👯 I’m looking to collaborate on": "Website designing related project",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "HTML,CSS,JAVA,JAVA SCRIPT ,SQL, Software Design & Architecture",
		"- 📫 How to reach me:":              "",
	}
}
