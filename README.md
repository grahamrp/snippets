# RStudio Snippets

My [RStudio code snippets](http://blog.rstudio.org/2015/04/13/rstudio-v0-99-preview-code-snippets/), which can be installed using the [snippr](https://github.com/dgrtwo/snippr) package as follows:

*Note that a .snippets file for a language may not yet exist. If it does not exist, go to Preferences->Code->Edit Snippets in RStudio, make a trivial change to the language of choice (for example, a new empty line), and click Save. This will create the language file in ~/.R/snippets/<language>.snippets with defaults included.*

```
devtools::install_github("dgrtwo/snippr")
library(snippr)
snippets_install_github("grahamrp/snippets")
```
