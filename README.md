# OpenOceansScience.github.io
website


To create this website: 

```
library(blogdown)

# blogdown::install_hugo()
blogdown::new_site(theme = "digitalcraftsman/hugo-agency-theme", theme_example = TRUE)

blogdown::install_theme("digitalcraftsman/hugo-agency-theme", update_config = TRUE)

blogdown::serve_site()
```