# **Introduction to DevOps\_\_Automate everything to Focus on what really matters**

## **LEARNINGS**

- Understand the value of automating tedious tasks
- Define a development lifecycle
- Automate shell-like tasks with Make, and/or shell script
- Be aware of tools dependencies and the value of reproducing environment
- Build static HTML website from Markdown code using Go-Hugo

## **Prerequisites**

- Install Go-Hugo to produce a valid Go-Hugo Website
- No Git Submodules allowed
- No directory `dist/` committed
- A Ubuntu system
- Usage of a Makefile to ease Lifecycle
- The website created has to use the theme 'ananke'

## **Lifecycle**

- build: Generate the website from the markdown and configuration files in the directory `dist/`.
- clean: Cleanup the content of the directory `dist/`
- post: Create a new blog post whose filename and title come from the
  environment variables `POST_TITLE` and `POST_NAME`.
- help: Display the documentation of all targets
