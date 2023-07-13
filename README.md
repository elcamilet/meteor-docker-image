# meteor-docker-image
Custom docker image with Meteor 2.12, ready to deploy Meteor apps in GitLab Pipeline Editor
It's public in https://hub.docker.com/r/lacodificadora/meteorjs

Copy src/Dockerfile to a folder and run:
```
  docker build -t lacodificadora/meteorjs:latest -t lacodificadora/meteorjs:meteor-2.12 .
  docker push -a lacodificadora/meteorjs
```

You can use it in GitLab Pipeline Editor like this:
```
image: lacodificadora/meteorjs:meteor-2.12

stages:
  - build
  - deploy

...
```

Feel free to use and reuse my work!

[La Codificadora de Ideas](https://lacodificadora.com)