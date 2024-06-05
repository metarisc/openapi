# Metarisc OpenAPI Specification

Ce repository contient les [spécifications OpenAPI][openapi] pour l'API Metarisc :

- `openapi.yaml:` OpenAPI 3.0 specs de l'API publique Metarisc

## Vendor Extensions

Ces spécifications sont livrées avec quelques extensions spécifiques à la génération des sdk.

### `x-extension-metarisc-codegen-name`

Le namespace auquel appartient l'opération.

### `x-extension-metarisc-codegen-operation`

Le nom de l'opération.

### `x-extension-metarisc-codegen-scope`

La portée de l'opération (core, ping, moi ...).