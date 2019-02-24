# From the top

I decided I should commit to building this site with a minimum of automation from the beginning. The idea is to use it as an exercise in TDD, documentation and webrelated F#. The goal is an appealing personal website with blogish features.

The first step is to state some sort of intent. A first goal and a basic architecture. So the first goal is this: render a very simple site with two or more blog posts.

### To do
* Put down a basic design.
* Write a document about the design and the intent.
* Document the steps taken to create the site in some detail.

## Design

The first iteration should be really simple. A framework to render the common stuff of the website (header, footer, navigation) and some way to take a directory with Markdown-files and render them as blog posts.

### Technical
* [F#](https://fsharp.org)  
A very nice functional language.  
* [ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core)  
To be more agnostic regarding where we run.  
* [FAKE](https://fake.build)  
Write the build script in F#!  
* [Paket](https://fsprojects.github.io/Paket/)  
Install packages from all over the place ...  
* [Expecto](https://github.com/haf/expecto)  
A test framework.

The testing will be done with Expecto

## The next few steps

1. [Init a git repo](https://github.com/oelrich/oelrich.se.git) and start commiting updates.
1. Create a document describing project set up.