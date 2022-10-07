# y-isa

Presentation for the 3rd Young-ISA Meeting - Limerick, IE

## To reproduce this slides

1. Install `renv`

```r
> install.packages("renv")
```

2. Clone this repository with git (this is in a Linux/Unix terminal)

```bash
$ git clone https://github.com/fernandomayer/y-isa.git
```

Or download a zip file from
[here](https://github.com/fernandomayer/y-isa/archive/refs/heads/main.zip).

3. Open R in this project and run

```r
> renv::restore()
```

to install all the packages needed.

4. Run

```r
> rmarkdown::render("slides-y-isa.Rmd")
```

and see the slides in `slides-y-isa.html` in your browser.
