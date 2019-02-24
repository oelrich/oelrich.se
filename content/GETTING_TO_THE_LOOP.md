# Getting to the Loop

There are a few steps to perform before the actual coding can begin.

## Settign up Git

This might seem a bit trivial, but never the less ...

Create a working directory and issue the command `git init` then `git add .` followed by `git commit -S -m 'Initial Commitment'`. This imples that `git` is set up with a code signing key. And it's a good idea to do that.

To store the repo at GitHub, just follow the instructions on that site and add that as a remote. Also put in a README.md there to make the presentation there a bit prettier.

## Setting up FAKE

Not a lot of work. `dotnet new -i "fake-template::*"` followed by `dotnet new fake` and then `.\fake.cmd build`. This command takes a little while and pulls down a ton fo dependencies. So the next step, before committing the files we want, is to add a `.gitignore` file.