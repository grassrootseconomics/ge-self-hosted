## ge-self-hosted

Self hosted stack used as public and internal tools and services.

- Uses a single overlay network for the entire stack `traefik_ge`. When adding a new services, ensure it is available in this network
- Dependency graph is not defined, you will need to do this manually i.e. bring postgres up first before a service which relies on it
- Volumes are folders within each service folder

