## gitlab-ci-multi-runner 

/etc/gitlab-runner/config.toml 


```
concurrent = 1
check_interval = 0

[[runners]]
  name = "docker-runner"
  url = "http://192.168.80.129:10080/"
  token = "d467ad2920cde2412918b05ddb8cc2"
  executor = "docker"
  [runners.docker]
    tls_verify = false
    image = "busybox"
    privileged = false
    disable_cache = false
    volumes = ["/cache","/root/.docker/:/root/.docker/","/etc/localtime:/etc/localtime","/etc/timezone:/etc/timezone","/var/run/docker.sock:/var/run/docker.sock", "/opt/maven/repository:/opt/maven/repository", "/opt/maven/conf:/usr/share/maven/conf"]
    shm_size = 0
  [runners.cache]
```
