---
layout: default
title: The Story of Container Tools
nav_order: 3
parent: Story
---

# ContainerTools

This is a story provided by the lead maintainer of the [singularityhub](https://singularityhub.github.io/) set of
tools and deployments for Singularity containers.

---------------------

I'm @vsoch on GitHub. I created [Singularity Hub](https://www.singularity-hub.org), a platform for building
containers from GitHub repositories, and having the containers be easily pulled to a research cluster
in 2016. While Singularity Hub itself is private, I felt a compelling need to provide an open source version
of Singularity Hub, with no aim but to empower institutions to deploy their own container registries for 
Singularity containers. This led to the birth of the singularityhub GitHub organization that I call
"Container Tools."

Other than providing a base to report issues for Singularity Hub, what else is there? 
There is a [singularity python](https://github.com/singularityhub/singularity-cli) client, 
meaning a handle to interact with the Singularity software via Python. Having awareness that Python is 
one of the main languages of scientific computing, I expected users would want to interact with containers
from within their scripts. I expected that other Python libraries might want to include interaction with 
Singularity containers. There is also an open source version of server, 
[Singularity Registry Server](https://github.com/singularityhub/sregistry), along with
a [Singularity Registry Client](https://github.com/singularityhub/sregistry-cli), that helps
with interaction with the server, along with many common cloud storage locations.
There are also several templates to help users get started with using continuous integration,
a [sif](https://www.github.com/singularityhub/sif) library for reading in a complex image format, and
a library called [container-tree](https://github.com/singularityhub/container-tree) that
helps those interested in researching containers.

At this point in time, I'm easily the primary contributor to all of these small projects.
When Singularity was not backed by a company, along with being one of the early main developers
and a driver for some of the features that still persist, I took responsibility to develop infrastructure
and supporting tools to support all users. Now that there is a commercial entity, it
is no longer my responsibility to drive innovation for this container technology, but
to support scientific users of containers. If the company is able to be profitable and provide
these same services, this will be a huge success for the community, and I look forward to
the day when Singularity Hub is no longer needed.

This isn't a huge success story, but rather an example of a small group of projects
that exist for the greater good. I created these projects to support reproducibility of
scientific computing, and the projects are committed to that.
