<!-- README.md is generated from README.Rmd. Please edit that file -->
Release summary
===============

The current version is 0.0.3.

Per suggestion by Kurt Hornik, the title was shortened. The package was re-uploaded as version 0.0.2.

Made some additional changes to the documentation and uploaded it as version 0.0.3.

Test environments
=================

-   Local OS X install, R 3.1.2 and R 3.2.2, using devtools::check()

-   win-builder (devel and release).

R CMD check results
===================

I got NOTE: "File README.md cannot be checked without ‘pandoc’ being installed."

I can't get rid of this unless I add the README.md file to .Rbuildignore, which does not seems like a good strategy. So I am ignorig this for now, hoping that the CRAN servers will have pandoc.

Devtools does throw the following message "Warning: Uncommited changes in git." I am not sure what git repo it is referring to and so I ignored this message.

Other than that, there were no WARNINGs or ERRORs.