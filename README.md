# Microservices Blog Concept

Minimalist Blog with moderated comments, made for the sake of testing a basic microservices architecture with a custom and event bus.

No database, data are stored in memory, so cleared every restart.

## Requirements
Docker, Kubernetes and Skaffold have to be installed for local deployment.

## Local dev deployment
The domain `posts.com` is used as http route in this project as example. To access it locally, we can redirect this domain to localhost in our local machine, adding to the `hosts` file (`/etc/hosts` on MacOs/Linux):

`127.0.0.1 posts.com`

In the terminal, inside the project's root directory, run `skaffold dev`
