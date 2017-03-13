---
permalink: /work/showcase/gymcloud
title: GymCloud - Work Showcase
---

# Work Showcase: GymCloud

## Project Background

* Idea: Platform for fitness professionals and their clients to perform personally designed workouts and exercises
* Founders were solving the industry problem, being end users of the product
* MVP was in development during 1 year

## My Role

Initial intention to join the team was simply to become yet another developer.
But that was extended quickly to something even more valuable. CTO like position.

* Senior Software Engineer
* Code Quality Improver
* Team Lead
* Hiring Manager
* Scrum Master
* QA Establisher
* Design Critique

## The Problem

* Single monolithic application repository
* Multiple technologies and frameworks were used
* Architecture was hard to extend and support
* Abandoned features and pieces of codebase were present
* There were no specific code quality requirements
* Tasks assigned to developers lacked behavior details
* Development tasks were roughly estimated without enough planning

## Problem-Solving Approach

* To establish reliable workflows for the development team
* To set high level for the code quality
* To reduce the technical debt
* To build extendable architecture
* To establish Quality Assurance

## Improvement Actions

### In Workflows

* Development workflow was established based on pull requests with mandatory code reviews
* Writing user behavior scenarios in Gherkin language
* Performing manual QA after deploying to staging server before the task acceptance
* Daily routine was established for development team to deliver predictable output
* Developers started to give feedback to design team
* Strict tasks management workflow in Trello was established

### In Automatization

* Continuous Integration workflow was set up to deliver the code to staging and production servers
* Automated code linters were set up to check the syntax of JavaScript and Ruby code
* Deployment platform was changed from Heroku to Digital Ocean VPS to reduce costs and increase flexibility
* Notification for incidents on production server were set up

### In Technology

* Application codebase was reviewed to identify working features and code
* 4 new application codebases were built from the scratch: api server, web application, landing pages application and mobile application
* Previous code repository was totally replaced with the 4 new repositories
* Usage of Angular was totally dropped on web app, giving preference to Backbone.Marionette
* Plain HTML and CSS were converted to cleaner syntax of HAML, SASS, Jade, LESS

## Used Technology

* API server app: Ruby on Rails, Grape
* Web app: Backbone Marionette, Backbone StickIt, Jade, SASS, CoffeeScript, WebPack
* Mobile app: Ionic, Angular 1, Jade, LESS
* Landing pages app: Ruby on Rails, HAML, SASS
* Continuous Integration: CodeShip, Dokku, Digital Ocean

## The Results

* Increased Quality of development workflows, platform architecture, written code, prepared requirements, task estimates
* Increased platform stability
* Reduced technical debt
* Increased development flexibility and ease of extending the platform
* Development team became reliable, involved, and more organized
* New features were delivered
* Tons of bugs were fixed
* Project was prepared for launch

---

{% include works_footer.md %}
