Simple daemon that displays the MOTD to port 8000 over http

With docker-compose:

```yaml
web:
  image: dockhero/motd-http
  ports:
    - "80:80"
```

