# in .Rprofile of the website project
if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}

options(blogdown.new_bundle = TRUE)

options(
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
options(blogdown.hugo.version = "0.65.0")
