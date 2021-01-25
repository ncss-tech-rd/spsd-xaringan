# USDA-NRCS SPSD {xaringan} slide template

USDA-NRCS Soil and Plant Science Division {_xaringan_} slide template. See the demo in the _DemoSlides_ folder.

1. Install the R package containing templates from GitHub:

```
# install.packages('remotes')

remotes::install_github('ncss-tech-rd/spsdxaringan')
```

2. **File >> New File >> R Markdown... >> From Template >> _"USDA-NRCS SPSD xaringan Slide Deck"_**

3. Change the default values populated in the _.Rmd_ file that is created. Note that there are several different CSS classes. These are provided for basic slide styling that conforms with editorial standards.

4. Call `xaringan::inf_mr()` or use RStudio _AddIns >> Xaringan >> Infinite Moon Reader_ menu item to interact with your new [Remark.js](https://yihui.name/en/2017/08/why-xaringan-remark-js/) slide deck!

5. Read more on customizing your {_xaringan_} slides!

   - For a crash course on {_xaringan_} slides check out 2019 Advanced Markdown Workshop (ARM): http://arm.rbind.io/slides/xaringan.html
 
   - https://bookdown.org/yihui/rmarkdown/xaringan.html
 
   - https://slides.yihui.org/xaringan/incremental.html
  
   - https://yihui.org/en/2017/10/xaringan-themes/

6. A shell script is provided for using `decktape` to create PDF versions of these slide decks. Note that incremental reveals are challenging to render with standard e.g. print to PDF from Google Chrome, but simple slide sets should be exportable to PDF using standard tools. There may be somewhat different formatting compared to the HTML slides. 
