Documentation Jenkins Image:
https://github.com/jenkinsci/docker/blob/master/README.md

Anleitung für dich:

```
docker compose
```
wenn alles läuft sollte unter

```
http://localhost:4300
```

jenkins erreichbar sein

passwort wird verlangt? das steht im container drin.


```
docker exec <jenkins container name> cat /var/jenkins_home/secrets/initialAdminPassword
```

