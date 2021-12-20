# all-about-cam


 <h2 align="center">I am not a robot, this is the proof <img src = "https://media0.giphy.com/media/KDDpcKigbfFpnejZs6/giphy.gif?cid=ecf05e47oy6f4zjs8g1qoiystc56cu7r9tb8a1fe76e05oty&rid=giphy.gif" width = 100px, align="center"></h2>

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
		"⚡  I'm passionate about coding and human languages",
		"🔭 I’m currently studying a Master's in Business Analytics",
		"🌱 I’m currently learning Python, R, C++ and Java",
		"👯 I’m looking to collaborate on Python/finance related projects",
		"🤔 I’m looking for help with anything related to what I am currently learning 😅",
		"💬 Ask me about finance ans statistical analysis",
		"📫 How to reach me at http://linkedin.com/in/cam-perez,
	}
}
```
  
