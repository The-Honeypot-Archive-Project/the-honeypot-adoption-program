# The Honeypot Adoption Program

Many honeypots are no longer maintained and it has become hard to run and test them as libraries and packages evolve.

In an aim to preserve them, we have started adopting some honeypots. What does this mean? The adoption work involves forking or migrating the code to our GitHub organisation, improving the documentation when appropriate, creating a docker image or package that can be used to run the honeypot without having dependencies issues and providing LTS.

## Adopted Honeypots

The honeypots below have been adopted, are working and have a usable package or Docker image that can be used to run the honeypot without dependencies issues.

| Honeypot   | Adopter    | Docker Image | Last commit | DockerHub pulls |
| ---------- | :------------: |:------------: | ----------- | --------------- |
| Delilah    | @verovaleros | Yes          | ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/The-Honeypot-Archive-Project/delilah) | ![Docker Pulls](https://img.shields.io/docker/pulls/verovaleros/delilah?color=green) |
| Honeyprint | @verovaleros | Yes          | ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/The-Honeypot-Archive-Project/honeyprint) | ![Docker Pulls](https://img.shields.io/docker/pulls/verovaleros/honeyprint?color=green) |
| NoSQLpot   | @verovaleros | Yes          | ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/The-Honeypot-Archive-Project/nosqlpot) | ![Docker Pulls](https://img.shields.io/docker/pulls/verovaleros/nosqlpot?color=green)|
| wordpot    | @verovaleros | Yes          | ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/The-Honeypot-Archive-Project/wordpot) |  ![Docker Pulls](https://img.shields.io/docker/pulls/verovaleros/wordpot?color=green)|

## How to Contribute?

1. If you created a honeypot and do not wish to maintain it anymore, create an issue to get in contact with us to coordinate the adoption. Please include:
    - the honeypot name
    - the type of the honeypot (database honeypot, service honeypot, web honeypot, etc)
    - the interaction level (high, medium, low)
    - the language in which the honeypot is written
    - the link to the code

2. If you found an orphan honeypot, please create an issue with its details so we can take a look at it and investigate the possibility of adopting it.
