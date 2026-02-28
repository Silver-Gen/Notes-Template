Would be updated soon



File Structure that needs to be downloaded - 

```text
.
├── LaTeX Files
│   ├── alpha.tex
│   ├── dependencies.sty
│   ├── titlepage.sty
│   ├── parttoc.sty
│   ├── chaptertoc.sty
│   ├── general.sty
│   ├── questions.sty
│   └── file23.ext

```


Alpha.tex is a template of some sorts to establish how things can be implemented in your tex project. 

```tex
\usepackage{dependencies}
\usepackage{titlepage}
\usepackage{parttoc}
\usepackage{chaptertoc}
\usepackage{questions}
\usepackage{general}
```

Keep the margins as small as possible

```tex
\geometry{
  left=0.5cm,
  right=0.5cm,
  top=0.5cm,
  bottom=0.5cm,
}
```
