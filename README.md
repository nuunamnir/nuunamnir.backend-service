# Backend Service (archived)

This repository is archived. Development continues at [yths/yths.backend-service](https://github.com/yths/yths.backend-service).

The codebase was renamed and de-themed during the consolidation so that the service is theme-agnostic and reusable:

| Old (here) | New (yths.backend-service) |
|---|---|
| systemd unit `nuunamnir.backend.service` | `backend.service` |
| env file `~/.config/nuunamnir.backend.env` | `~/.config/backend.env` |
| env-var prefix `NBS_*` | `BACKEND_*` |
| package `nuunamnir-backend-service` | `backend-service` |

See the new repo's [docs/install.md](https://github.com/yths/yths.backend-service/blob/main/docs/install.md) for the current setup.
