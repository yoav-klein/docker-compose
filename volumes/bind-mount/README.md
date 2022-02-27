
# Bind mounts
---

You can mount a host path as part of a definition of a single service, and there is
no need to define it in the top level `volumes` mapping.

In this example, we mount the `assets` directory to the `/assets` directory
in the container.
