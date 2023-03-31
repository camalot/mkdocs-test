An option to stop the server after a specified time has been added for niche applications (e.g. billing saving on AWS Fargate). The function is incompatible with the Autopause functionality, as they basically cancel out each other.

Note that the docker container variables have to be set accordingly (restart policy set to "no") and that the container has to be manually restarted.

A starting, example compose file has been provided in [examples/docker-compose-autostop.yml](examples/docker-compose-autostop.yml).

Enable the Autostop functionality by setting:

```
-e ENABLE_AUTOSTOP=TRUE
```

The following environment variables define the behaviour of auto-stopping:
* `AUTOSTOP_TIMEOUT_EST`, default `3600` (seconds)
  describes the time between the last client disconnect and the stopping of the server (read as timeout established)
* `AUTOSTOP_TIMEOUT_INIT`, default `1800` (seconds)
  describes the time between server start and the stopping of the server, when no client connects inbetween (read as timeout initialized)
* `AUTOSTOP_PERIOD`, default `10` (seconds)
  describes period of the daemonized state machine, that handles the stopping of the server

> To troubleshoot, add `DEBUG_AUTOSTOP=true` to see additional output