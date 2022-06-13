# REMEMBER to restart R after you modify and save this file!

# First, execute the global .Rprofile if it exists. You may configure blogdown
# options there, too, so they apply to any blogdown projects. Feel free to
# ignore this part if it sounds too complicated to you.

# in .Rprofile of the website project
if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}

options(blogdown.new_bundle = TRUE)

# Now set options to customize the behavior of blogdown for this project. Below
# are a few sample options; for more options, see 
# https://bookdown.org/yihui/blogdown/global-options.html

options(
  # to automoatically serve the site on RStudio startup, set this option to TRUE
  blogdown.serve_site.startup = FALSE,
  # to disable knitting Rmd files on save, set this option to FALSE
  blogdown.knit.on_save = TRUE,
  # build .Rmd to .html (via Pandoc); to build to Markdown, set this option to 'markdown'
  blogdown.ext = ".Rmarkdown",
  blogdown.method = "markdown",
  blogdown.author = "Desirée De Leon",
  blogdown.ext = ".Rmd",
  blogdown.subdir = "post",
  blogdown.yaml.empty = TRUE,
  blogdown.new_bundle = TRUE,
  blogdown.title_case = TRUE
)

rprofile <- Sys.getenv("R_PROFILE_USER", "~/.Rprofile") # This line and below added in from Blogdown Day 3 slides for bundling 

if (file.exists(rprofile)) {
  source(file = rprofile)
}


# fix Hugo version
options(blogdown.hugo.version = "0.80.0")
