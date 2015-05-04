![Travis build](https://travis-ci.org/timlegrand/ci.svg)

# Cloudinuous Integration

This is a minimalistic, sample repository to test Travis' Continuous Integration and study then link and integration between Travis and GitHub.


## What is does

This repository contains the bare needs to integrate a cloud-based, continuous integration system called Travis.
Travis provides a picture [https://api.travis-ci.org/timlegrand/ci.svg](https://api.travis-ci.org/timlegrand/ci.svg) that changes according to the *build status* of the projet. Of course, what you put in *build status* can be customizable and may go from compiling to testing, packaging or deployment testing...


## How it works

I linked my Travis account to this repository. Basically, that means that every push to this repository tells Travis to launch the build process described in the `.travis.yml` file, without which no build or test can be performed. At the end of the "build", the picture that represents the current project status is updated on Travis servers. That's it. You can have a look on how I integrated this picture to this page at the very top of the README.md file.


## What to do with this repo

You can use it as a base for your projects that need for continuous integration with Travis without any restriction.
I actively encourage to use continuous integration with your projects since it brings quality, safety and sustainability to applications.

