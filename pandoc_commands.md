## Converting .md tabs to .pdf file

```bash
pandoc Throwing_Dough.md -o Throwing_Dough.pdf \
  --pdf-engine=xelatex \
  -V geometry:left=20pt,bottom=20pt,top=20pt
```

## TODO

- update macTex
- instll fvextra and remove codeblock splitting
- install framed for pandoc/latex syntax hilighting options

```
sudo tlmgr update --self
sudo tlmgr install fvextra
```

```
sudo tlmgr install framed
```
