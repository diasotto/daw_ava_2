# dsw_ava_2

**Nome:** Otto Dias
**Data:** 06/05/2025  
**Unidade Curricular:** Desenvolver Serviços Web

## O que é uma API Rest?

Uma API REST permite que diferentes sistemas se comuniquem utilizando o protocolo HTTP. Ela segue princípios como stateless (sem estado), uso de verbos HTTP (GET, POST, PUT, DELETE) e acesso a recursos via URLs.

## Códigos de Erro HTTP

- **200 OK:** Requisição feita com sucesso.
- **201 Created:** Recurso criado.
- **400 Bad Request:** Erro na requisição.
- **401 Unauthorized:** Acesso negado.
- **404 Not Found:** Recurso não encontrado.
- **500 Internal Server Error:** Erro interno.

## Diferenças entre JSON, Texto Plano e XML

- **JSON:** Leve, fácil de ler por humanos e processar por máquinas. Ex: `{ "nome": "Otto" }`
- **Texto Plano:** Sem formatação. Ex: `Otto`
- **XML:** Estruturado com tags. Ex: `<nome>Otto</nome>`

## Procedimentos

1. Criar projeto com `composer init`
2. Instalar Slim com `composer require slim/slim slim/psr7`
3. Criar o `index.php` com os endpoints `/uma-api`, `/codigos` e `/error`
4. Testar com Postman, Insomnia ou navegador.

---

## 🔗 Entregar

Link do repositório no Github com tudo funcionando bonitinho.
