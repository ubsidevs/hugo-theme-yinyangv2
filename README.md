# 👋 YinYang V2 - Hugo Fast Theme

Name    : YinYang V2  
Based   : [YinYang Theme](https://github.com/joway/hugo-theme-yinyang)  
Demo V2 : [Demo](https://bucin-kode.github.io)  

## 🔎 Feature in V2 Version

- Minimalist dark colors, using the color palette from Github Dark Theme
- Now comment platform using [utteranc.es](https://utteranc.es/)
- Display optimization for smaller screens ( Responsive )
- Added FiraCode font for Syntax Highlighter

## 📷 Screenshots

![Screnshoot Home Page Yinyang V2 from Smartphone]()  

![Screnshoot Home Page Yinyang V2 from Tab]()

## ⚙ Installation

From the root of your site:

```shell
git clone https://github.com/bucin-kode/hugo-theme-yinyangv2.git themes/yinyang
```

Change `config.toml`:

```toml
theme = "yinyangv2"
```

## Configuration

### Head Title

```
[params]
headTitle = "Yinyang V2"
```

If there is no `headTitle` in params, use `.Site.Author.name`.

### Main section

Set your main section:

```
[params]
mainSections = ["posts"]
```

### Multi-Language

```
[languages]
  [languages.en]
    contentDir = "content/en"
    languageName = "English"
    weight = 1
  [languages.cn]
    contentDir = "content/cn"
    languageName = "Chinese"
    weight = 2
  [languages.id]
    contentDir = "content/id"
    languageName = "Indonesia"
    weight = 3
```

Then your posts files should be put into `content/en` , `content/cn` or `content/id` for Indonesian language.

---

> ### See a more complete configuration in the yinyang base repository [Here!](https://github.com/joway/hugo-theme-yinyang/blob/master/README.md)