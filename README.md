# Domestic Containers

This project is a compendium of different services alternatives to deploy in your home.

## Where to look for containers

We can deploy almost any server in containers but unless you have a reasonable amount of expertise the best start is to take a look at the repos to be aware of ecosystem.

Docker containers are built by layers, usually it uses a linux flavour base image and on top of it, stacks the different dependencies and the app.

- [Docker's Official documentation][DockerDocs]
- [DockerHub], [Arm][DockerHub_Arm] The **Main** site.
- [LinuxServer.io] A reference team.

[DockerDocs]: https://docs.docker.com/
[DockerHub]: https://hub.docker.com/search/?q=&type=image&image_filter=official
[DockerHub_Arm]: https://hub.docker.com/search/?q=&type=image&architecture=arm&image_filter=official
[LinuxServer.io]: https://www.linuxserver.io/

## Doc in Dev

- [codex.md](codex.md)
- [build-template](build-template)
