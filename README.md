# File Server w/ NginX

This is a simple NginX server used as a file server.

## Usage

To put your files on the server, get into the container with
this command:

```bash
docker exec -it [container_hash] sh
```

Then put your files inside `/www/data` directory.