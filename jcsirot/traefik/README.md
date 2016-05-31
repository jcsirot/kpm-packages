
jcsirot/traefik
===========

# Install

Tag the HTTP entry points with the label "traefik-entrypoint" set to "yes"

```
# kubectl label node <node-name> traefik-entrypoint=yes
```

kpm deploy jcsirot/traefik
