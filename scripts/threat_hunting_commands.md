# Échecs d’authentification sur le client Windows
```text
agent.name:"Windows-Client" AND rule.groups:"authentication_failed"```

# Modifications de groupes utilisateurs sur le client Windows
```text
agent.name:"Windows-Client" AND rule.groups:"group_changed"```

# Élèvations de privilèges via sudo sur le client Linux
```text
agent.name:"Linux-Client" AND rule.groups:"sudo"```