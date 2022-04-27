## 03-control-document

This folder contains workflows based on using RMarkdown to control the output of code.

[Reference-external.Rmd](reference-external.Rmd) shows a usecase for rendering a document with other external RMarkdown portions from a .R file (penguins.R).

[use-child-adelie.Rmd](use-child-adelie.Rmd) shows a usecase for rendering a document with a child document that will fill in that section.

[use-conditional-child.Rmd](use-conditional-child.Rmd) shows a usecase for rendering a document with a _conditiona;_ child document that will fill in that section only if a specific logical criteria is met.

The [penguin-emailer.Rmd](penguin-emailer.Rmd) shows a workflow of generating an entire email with `blastula` package. Render it to see the output, try changing components in the [penguin-email.Rmd](penguin-email.Rmd) to see the change in the output email.