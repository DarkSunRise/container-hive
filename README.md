# Docker GUI

![Screenshot](public/images/squares.gif)

## Why? 
Visualization helps provides intuition and understanding of even the most complex systems.
## What? 
Docker GUI's main goal is to give a user friendly display of everything that is running in your Docker daemon and, in the future, provide powerful CRUD capabilities. 
## How?
Docker GUI is a Node app built with React, Refetch, Dockerode, and a basic Express server.

## UI Concept

![Concept](public/images/ComponentConcept.png)

## Screenshots (WIP)

![Screenshot](public/images/ScreenShot2016-08-13-10.53.33AM.png)


## Known Issues

* Docker pull doesn't work as expected
* Running containers in detached mode is not possible unless the container has an entrypoint

## Contibuting

```bash
# Start React App with Hot Reloading
npm run start

# Start Backend App
npm run start-server
```