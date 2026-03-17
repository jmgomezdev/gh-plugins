# ghcopilot-hub-minimal

Plugin minimo de GitHub Copilot CLI para validar la idea de empaquetar una parte del hub como plugin nativo.

Contenido incluido:

- agente `Explore`
- skill `ghcopilot-hub-consumer`

Instalacion local desde este repositorio:

```bash
copilot plugin install ./plugins/ghcopilot-hub-minimal
```

Comprobaciones utiles:

```text
/plugin list
/agent
/skills list
```

Si modificas el contenido del plugin local, reinstalalo para refrescar la cache de Copilot CLI:

```bash
copilot plugin install ./plugins/ghcopilot-hub-minimal
```

Este plugin no reemplaza el CLI declarativo del repositorio. Solo valida el empaquetado nativo de agentes y skills
para Copilot CLI.