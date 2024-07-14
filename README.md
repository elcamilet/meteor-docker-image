# meteor-docker-image
Custom docker image for Meteor 2.15 apps.
Ready to deploy Meteor apps in GitLab Pipeline Editor or as standalone custom image.
It's public in https://hub.docker.com/r/lacodificadora/meteorjs

Copy src/Dockerfile to a folder and run:
```
  docker build -t lacodificadora/meteorjs:latest -t lacodificadora/meteorjs:meteor-2.15 .
  docker push -a lacodificadora/meteorjs
```

You can use it in GitLab Pipeline Editor like this:
```
image: lacodificadora/meteorjs:meteor-2.15

stages:
  - build
  - deploy

...
```

Feel free to use and reuse my work!

[La Codificadora de Ideas](https://lacodificadora.com)
