# resumoApiREST

# Api REST e RESTFul


API REST (Interface de Programação de Aplicações Representacional): É um conjunto de princípios arquiteturais que guiam o design de serviços web. O termo "REST" refere-se a Representational State Transfer, indicando a transferência de representações de recursos entre sistemas.

**Características Principais:**
- Usa os métodos HTTP (GET, POST, PUT, DELETE) para operações em recursos.
- Pode ou não ser stateless (sem estado), dependendo da implementação.
- Os recursos são identificados por URLs.
- Suporta diferentes formatos de representação, como JSON, XML.

API RESTful: É uma implementação concreta dos princípios REST. Uma API é considerada RESTful quando adere estritamente às restrições e práticas recomendadas do estilo arquitetural REST.

**Características Principais:**
- Geralmente é stateless, seguindo o princípio de não manter o estado da sessão do cliente entre solicitações.
- Usa práticas específicas para criar URLs significativas e hierárquicas.
- Adere estritamente aos métodos HTTP para operações em recursos.
- Utiliza formatos de representação, como JSON, para transmitir dados.

## Diferenças entre REST e RESTFul

REST e RESTful são dois termos frequentemente usados ​​em conjunto, mas há uma diferença importante entre eles. **REST** é um conjunto de princípios arquitetônicos para serviços web, enquanto **RESTful** é um termo usado para descrever uma API que implementa esses princípios.

As principais diferenças entre REST e RESTful são as seguintes:

- **REST é um conjunto de princípios, enquanto RESTful é uma implementação desses princípios.**
- **Uma API RESTful deve seguir todos os princípios REST.**
- **Uma API RESTful pode ser implementada de várias maneiras diferentes.**

## HTTP (HTTP Verbs)

- **GET:** Obtém dados de um recurso especificado.
- **POST:** Envia dados para serem processados ​​para um recurso especificado.
- **PUT:** Atualiza um recurso especificado com novos dados.
- **DELETE:** Remove um recurso especificado.
- **HEAD:** Semelhante ao GET, mas usado para obter apenas os cabeçalhos sem o corpo da resposta.
- **OPTIONS:** Retorna os métodos HTTP suportados pelo servidor para o URL especificado.
- **PATCH:** Aplica modificações parciais a um recurso.

## HTTP Status Code

  

- **200 OK:** Indica que a solicitação foi bem-sucedida.
- **201 Created:** Indica que a solicitação foi bem-sucedida e resultou na criação de um novo recurso.
- **204 No Content:** Indica que a solicitação foi bem-sucedida, mas não há conteúdo para ser retornado.
- **400 Bad Request:** Indica que a solicitação do cliente é inválida ou malformada.
- **401 Unauthorized:** Indica que a solicitação não foi autorizada, geralmente devido à falta de credenciais válidas.
- **403 Forbidden:** Indica que o servidor entende a solicitação, mas recusa-se a autorizá-la.
- **404 Not Found:** Indica que o recurso solicitado não foi encontrado no servidor.
- **500 Internal Server Error:** Indica que ocorreu um erro interno no servidor enquanto processava a solicitação do cliente.
- **503 Service Unavailable:** Indica que o servidor não está pronto para manipular a solicitação. Geralmente, isso ocorre devido a manutenção ou sobrecarga temporária.


  
---
Autor do resumo: Paulo Cesar Cadena de Almeida Filho - 01563936
