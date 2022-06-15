# An exercise in CI/CD

This repo exemplifies several possible workflows.


1. naive push - on every push to github, the image is built and pushed to DockerHub

2. naive push + cache

3. only tagged versions are pushed to Docker Hub. + a manually triggered job that pushes the image to Github Registry (cache included).


