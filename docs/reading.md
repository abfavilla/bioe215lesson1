# Project workflows
_Bryan (2017)_

What problems can setwd() cause in your scripts and how do RStudio projects address them?

*setwd() only works for the person who wrote it. The path is almost never going to work for a different user (or even the same user on a different computer).* 

When you call rm(list=ls()), what is removed from your environment? What’s left over that restarting your R session would remove? What’s the keyboard shortcut for restarting your R session?

*It removes user-created objects from the global workspace (e.g., variables), but it does not remove packages that were loaded and other changes/options that were set to something different than the default. The keyboard shortcut for restarting an R session is Ctrl+Shift+F10 for Windows.*  

# Version control
You either read Bryan (2018) or Braga et al. (2023). Answer the questions for the paper you read.

_Bryan (2018)_

The basic git commands are commit, push, and pull. Which commands change happen locally (i.e., on your computer)? Which happen remotely?

*Commit happens locally. Push and pull happen remotely.* 

Why do diffs work for source code (e.g., .R files) but not Word documents (i.e., .docx files)?

*Word documents are binary files, the diffs created are not human-readable.* 

Why is Markdown useful for GitHub repos?

*Files written in Markdown can be rendered in an HTML-like way on GitHub--"formatting and links 'just work'". They make it easy to create a website for your project.*

_Braga et al. (2023)_

Imagine you’re working with a few collaborators on an analysis. Come up with two examples of Issues you might open. How would using Issues differ from communicating over email?

*Examples of Issues would be resolving inconsistencies in a data set one of the co-authors provided. Or deciding which analytical method to use. Using Issues makes it easier to track progress over the project's lifespan compared to email.*

What are three ways GitHub features can promote open science practices?

*(1) Entire workflow is transparent. (2) It becomes easier to verify code written by collaborators. (3) Provide time-stamped preregistration of hypotheses. *