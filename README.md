# hugo-mock-landing-page
Assignment 1 Part 2 for CIS 3500 - Software Engineering


## Useful parts of this workflow

The workflow for continuous integration is pretty easy to set up, with the right yaml file to code for a github action. This is useful because we can see changes live on our site whenever we create a new push to the repository.

The workflow does the following:
It activates whenever there is a new push onto the main branch. It then check outs the current main branch onto the the runner. First it will initialize the hugo environment using peaceiris/actions-hugo@v2.6.0. Then it runs code to compile hugo into a static website. And finally it publishes the result onto github pages.
