## Why Docker is so important?

![Github Logo](/images/Docker.jpg)

The Docker goal is to ease the creation, deploy and the delivery of an application using the so called Containers. The Docker **Containers** allow the developer/sysadmin to bundle an application with all needed components (libraries and other resources) and to deliver it as an independent and single package.

**Thanks to the Container**, the system administrator is sure 100% that the application will run on _every_ Linux machine (or on other docker supported platforms) regardless of any customization, server settings or other customization that may be present on the target server.

**From a certain point of view** a container is not so much different from a **virtual machine**. But, instead of creating a full operating system, a Docker Container has just the minimum set of operating system software needed for the application to run and rely on the host Linux Kernel itself.

This allow a huge boost on performance (compared to a virtualized system you can save up to 8% processing power) and a reduced memory and disk footprint for your application.

Docker has also a complete configuration management system. You can easily use it to replace **Chef or Puppet** to build Containers automatically for your test, development and production environments.

Docker runs on pretty much every platform on the market and is very easy to port your application from your physical PC (Docker works also with OSX and Windows) to a cloud based server and vice-versa. Moreover the containers versioning system allow you to easily address disaster recovery and backup issues.

Is Docker the silver bullet for the System administrator? Maybe, for sure Docker solves a lot of problems that a system administrator encounters on the every day work. Moreover is a good candidate to replace very specific software like Hypervisors and configuration management tools.

Actually we are testing docker in production thus re-thinking all our cloud based systems in order to use this technology.

Last but not least, **Docker is Open Source:** everybody can contribute, customize and extend Docker.
