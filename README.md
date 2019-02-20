# Docker

![title slide](https://raw.githubusercontent.com/freyamade/netsoc-docker-talk/master/title.png)

Docker is probably the most used containerisation platforms in the market at the moment?

What's a container I hear you say, and by coming to this talk you'll hopefully end up learning about what they are and why you should use it.

It's more a tool used in industry for deployment of applications but with the soon coming NetSoc Containers-as-a-Service platform you will soon be able to host your own applications in containers, and then you'll never look back.

## Roadmap

The talk will go as follows;

1. Brief Introduction
    - What is a container
    - Containers vs VMs
2. Getting started with Docker
    - Images vs Containers
    - Let's make a basic image
    - Using Apache Docker image for development
3. Case Study of CIX
    - The dark ages of VMs
        - Issues regarding dependencies
            - Old deploy scripts didn't / don't properly update dependencies
        - Monolithic / Microservice
            - Old code all on single server
            - New stuff being deployed on multiple servers for load balancing / failover
        - Stupid issues
            - Server clock discrepencies causing issues with tokens >.>
    - The new age of Docker / Kubernetes
        - Dependencies are handled when building the image, not after deploying code
        - Once image is built, that's all that has to be deployed
        - Kubernetes clusters allow for load balancing, automatic rollout of upgrades to prevent downtime, failover etc
4. Conclusion
