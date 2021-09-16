# ansible-betterbird
> A fully automated build script for [Betterbird](https://www.betterbird.eu/) using Ansible.

There are two ways to build (and package) the app:

### Native
Simply run ...

```./betterbird.sh```

... to invoke the playbook and run everything natively on your local host.

### Containerized
If you don't want to "spoil" your system with all the necessary build-dependencies (Python, NodeJS, Rust, etc.) then you can take the Docker-route and just run ...

```docker-compose up```

... to trigger the build inside a container.
