---
title: Tips
layout: page
---

## Linters 

The most complete linter/checking solution I’m aware of is [Vale](https://vale.sh/). 

If you’re running in Codespaces, VSCode, or another popular development environment, Vale's going to be a built-in plugin you can just select, install, and use. It can automatically check your content against the entire Microsoft Style Guide, for example. Or make sure your company name is capitalized correctly.

## Learn to script

If you can spend a little time with our API and ChatGPT, you can write scripts of your own. With AI help, I wrote up a script that pulled dates from two different sources, compared them, and if the date in the file was wrong, updated it. If the field was missing or the content was invalid, it wrote the filename to an errata file so I can capture and track the task of fixing things. I went from exactly zero knowledge of Python to a fully functional script -- without asking Eng for help! -- in three days.

The best book I'm aware of on Actions is [Automating Workflows with GitHub Actions](https://www.amazon.com/Automating-Workflows-GitHub-Actions-applications/dp/1800560400) Until very recently, the author was a senior manager in our Premium Support org.

## OpenAPI template repo

There's a complete [template repo](https://swagger.io/blog/api-development/generator-openapi-repo/) available to clone and poke around with. Build a complete OpenAPI-enabled site in 20 minutes with Swagger? No problem. If you're looking at getting started with documenting using OpenAPI this is a great place to start learning how the are written and how they work together.

_(Swagger donated the specification that they developed to the OpenAPI initiative in 2015, and have since focused on building tools to implement that specification.)_
