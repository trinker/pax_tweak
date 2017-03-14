# pax_tweak

Materials, scripts, and files for tweaking the `pax` function in the [**pax**](https://github.com/trinker/pax) package.

The standard **pax** template looks like:

```
|   .gitignore
|   .Rbuildignore
|   DESCRIPTION
|   foo.rproj
|   NEWS
|   README.md
|   README.Rmd
|   travis.yml
|   
+---inst
|       maintenance.R
|       
+---R
|       sample.R
|       utils.R
|       
\---tests
    |   testthat.R
    |   
    \---testthat
            test-sample.R
```

With the `tweak = "http://goo.gl/oL7UXO"` option set:

```
|   .gitignore
|   .Rbuildignore
|   .Rprofile
|   bar.rproj
|   DESCRIPTION
|   NEWS
|   README.md
|   README.Rmd
|   travis.yml
|   
+---inst
|   |   build.R
|   |   maintenance.R
|   |       
|   +---extra_statdoc
|   |       readme.R
|   |       
|   \---staticdocs
|           index.R
|           
+---R
|       sample.R
|       utils.R
|       
+---tests
|   |   testthat.R
|   |   
|   \---testthat
|           test-sample.R
| 
\---tools
    |
    \---bar_logo
           r_bar.pptx            
```
