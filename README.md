# doc-builder
This repo contains a GitLab CI job that takes all markdown files and turns them into PDF and DOCX. It's perfect for those that want to use Markdown to write and track changes to documentation.

## Installation
 - This is for GitLab. I'm sure it can be ported to something like travis-ci or another CI provider of your choice.
 - Make sure that you've got a runner already installed. How to do this is outside of the scope of this readme.
 - Download `.gitlab-ci.yml` from this repo and commit it to your own repo on the top level
 - Whenever a new commit is pushed, this job will automatically run, but **only on the master branch**. To make it run or a different branch, edit or remove the `only:` section of `.gitlab-ci.yml`
