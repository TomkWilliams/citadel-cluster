# citadel-cluster

Homelab production cluster on citadel, a bare metal Threadripper 1950X running Ubuntu Server 26.04 LTS.

Not started yet. Waiting on the learning cluster to be proven first.

## Plan

Same workflow as `citadel-learning`: directory-based cluster isolation via [devpod](https://devpod.sh/) + devcontainers, with its own `kubeconfig` and `.envrc`. direnv exports `KUBECONFIG` when you `cd` in.

This cluster is for homelab services, once I've worked through the [KubeCraft HomeLabOS](https://www.skool.com/kubecraft) curriculum in `citadel-learning` and have a setup I'm happy repeating.

## Repos

| Repo | Purpose |
|---|---|
| [`citadel-learning`](https://github.com/TomkWilliams/citadel-learning) | Course work and experimentation |
| `citadel-cluster` (this one) | Homelab production services |
