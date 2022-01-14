# A Basic Nginx Webserver

My Pod isn't working. I mean it's working and running,
and the service is fine as well.

I get the high port, 30-something, but when I do `curl localhost:30???`,
I just get

```
curl: (52) Empty reply from server
```

## Extra Question

Is there a way I can see whether it's the pod or service that's the problem?
Like, is there a command I can run,
so I can curl the pod on e.g. `localhost:8080`?
