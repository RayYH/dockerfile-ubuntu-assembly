# Ubuntu assembly

A sample yaml file:

```yml
version: '3'
services:
  bash:
    image: rayyounghong/ubuntu-assembly:latest
    container_name: assembly-demo
    volumes:
      - .:/code
    working_dir: /code
    tty: true
    stdin_open: true
```