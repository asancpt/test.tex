
intro.tex
---------

<https://services.math.duke.edu/computing/tex/templates.html>

``` r
tinytex::xelatex('intro.tex')
system('convert intro.pdf intro.png')
```

![](intro-0.png) ![](intro-1.png)

test.tex
========

``` r
tinytex::xelatex('test.tex')
system('convert test.pdf test.png')
```

![](test.png)
