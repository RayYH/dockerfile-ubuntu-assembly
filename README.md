# Ubuntu assembly

Below is a simple `docker-compose.yml` file:

```yml
version: '3'
services:
  assembly_demo:
    # x84 environment, if you want a x86 environment
    # change the `latest` tag to i386
    image: rayyounghong/ubuntu-assembly:latest
    container_name: assembly_demo
    volumes:
      - .:/code
    working_dir: /code
    tty: true
    stdin_open: true
```
