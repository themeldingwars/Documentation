# Networking

## Web API

Partially documented Web APIs as OpenAPI specification:

### Operator

| Method | Endpoint                       | Listed | Request | Response |
|--------|--------------------------------|--------|---------|----------|
| GET    | /api/v1/products/Firefall_Beta | ✔️     | ✔️     | ✔️      |
| GET    | /check                         | ✔️     | ✔️     | ✔️      |

### In-Game

| Method | Endpoint                       | Listed | Request | Response |
|--------|--------------------------------|--------|---------|----------|
| GET    | /login_alerts                  | ✔️     | ✔️     | ✔️      | 
| GET    | /panelmanager                  | ❌     | ❌     | ❌      |
| GET    | /dashboard/promotions          | ❌     | ❌     | ❌      |
| GET    | /dashboard/store_products      | ❌     | ❌     | ❌      |

### Client API

| Method | Endpoint                        | Listed | Request | Response |
|--------|---------------------------------|--------|---------|----------|
| POST   | /api/v1/oracle/ticket           | ✔️     | ❌     | ❌      |
| POST   | /api/v1/server/list             | ✔️     | ❌     | ❌      |
| GET    | /api/v1/social/friend_list.json | ✔️     | ✔️     | ❌      |
| GET    | /api/v1/social/static_data.json | ✔️     | ✔️     | ❌      |
| POST   | /api/v2/accounts/login          | ✔️     | ✔️     | ❌      |
| GET    | /api/v2/characters/list         | ✔️     | ✔️     | ✔️      |

### Launcher

| Method | Endpoint                        | Listed | Request | Response |
|--------|---------------------------------|--------|---------|----------|
| GET    | /launcher                       | ✔️     | ✔️     | ❌      |

### Further Reading

- Display the OpenAPI spec in a nice way: https://editor.swagger.io/
- Firefall API documentation: https://firefall.gamepedia.com/Ingame_Host

## Game Server

See [Game Server Protocol Overview](https://github.com/themeldingwars/Documentation/wiki/Game-Server-Protocol-Overview) on the wiki.