# Slide Notes:

## Slidedeck Location/Link:
[http://jinkit.slides.com/v1k0d3n/meetup-ccog-001](http://jinkit.slides.com/v1k0d3n/meetup-ccog-001)

### A few sample Docker container to run during the presentation:
**Ghost (showing volume mounts):**
```
docker run  -d --name ghost --restart=always -p 8888:2368 -v /path/of/choice:/var/lib/ghost ghost:latest
```



**Consul Service-Discovery (created for demonstration):**
```
docker run -d \
-p 8300:8300 -p 8301:8301 \
-p 8302:8302 -p 8400:8400 \
-p 8500:8500 -p 8600:8600/udp \
v1k0d3n/consul:latest \
-bootstrap -client \
0.0.0.0 -server \
-ui-dir /opt/consul/web_ui
```

**OSSEC HIDPS Container (Referenced, but not using):**
```
docker run -d \
-p 1514:1514/udp \
-p 1515:1515 \
-p 514:514/udp \
-p 5601:5601 \
-v /Users/bjozsa/Docker/OSSEC/data:/var/ossec/data \
--name ossec \
wazuh/ossec-elk
```
