```go
package main

type Profile struct {
	Telegram     string
	Languages    []string
	Age          int
	CodeLang     map[string][]string
	Specialities []string
	Environment  []string
}

func NewProfile() *Profile {
	return &Profile{
		Telegram:  "t.me/qwwozzz",
		Languages: []string{"Russian", "English"},
		Age:       18,
		CodeLang: map[string][]string{
			"expert":       {"python", "django", "fastapi"},
			"intermediate": {"c++", "go", "bash", "postgresql"},
			"learning":     {"javascript", "rust"},
		},
		Specialities: []string{"back-end developer"},
		Environment:  []string{"vscode", "vs"},
	}
}

func (p *Profile) GetContact() (string, string, string) {
	return p.Telegram, "", ""
}

func (p *Profile) GetLife() ([]string, int) {
	return p.Languages, p.Age
}

func (p *Profile) GetCoding() (map[string][]string, []string, []string) {
	return p.CodeLang, p.Specialities, p.Environment
}
```
<h2 align="center">Skills </h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,javascript,fastapi,django,react,postgres,git,linux"/>
  </a>
</p>

---

<p align="center">
   <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=oonixxxxx&theme=tokyonight">
</p>


<p align="center">
</p>

---

<div align="center">

### LeetCode
[![LeetCode Stats](https://leetcard.jacoblin.cool/oonixxxxx?theme=dark&font=Karla&ext=heatmap)](https://leetcode.com/oonixxxxx/)

</div>

---
