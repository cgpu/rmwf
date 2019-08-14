# RMWF

Reproducilble Metabolomics WorkFlow(RMWF) is a R package for [xcmsrocker](https://hub.docker.com/r/yufree/xcmsrocker/). It will show the workflow templates and demo data for different R-based metabolomics software. User could use this package to make meta-analysis for different workflows.

If you directly use the docker image, the rmwf package is already installed.

However, if you wanted to install locally on your own computer, you could install it from [GitHub](https://github.com/yufree/rmwf):

In RStudio console, input this command to install it:

~~~
# You need remotes package and you could install it by this command
install.packages(‘remotes’)
remotes::install_github("yufree/rmwf")
~~~

Then you could find the workflow template from RStudio:

File-New file-R Markdown-from template

Then select 'MSSM metabolomics workflow’ to use template.
