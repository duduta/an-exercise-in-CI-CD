An exercise in CI/CD

This repo exemplifies several possible workflows, starting from the naive to the optimal.

First, if you checkout branch naive-push-DH, the workflow is as follows:
Upon every push to github, the image is built and run and the resulting container is 
pushed to Docker Hub. 
That's suboptimal, but it's a start. (you will practice logging in to Docker Hub and pushing to it)

Right now, on main, the workflow is just a bit improved. Cache is added.

To be continued :)


