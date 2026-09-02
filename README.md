# API Testing - JSONPlaceholder

Proyecto de pruebas de API REST realizado con Postman sobre la API pública JSONPlaceholder.

El objetivo del proyecto es demostrar conocimientos de QA en pruebas de API, incluyendo diseño de casos de prueba, validación de códigos de estado, validación de respuestas JSON, pruebas positivas y negativas y ejecución automatizada de una colección.

## 🛠️ Tecnologías utilizadas

- Postman
- REST API
- JSON
- JavaScript
- Git
- GitHub

## 🎯 API utilizada

JSONPlaceholder

Recurso probado:

`/users`

## 🧪 Casos de prueba

| ID | Método | Caso de prueba | Resultado |
|---|---|---|---|
| TC-API-001 | GET | Obtener todos los usuarios | ✅ PASS |
| TC-API-002 | GET | Obtener usuario por ID | ✅ PASS |
| TC-API-003 | GET | Consultar usuario inexistente | ✅ PASS |
| TC-API-004 | POST | Crear usuario | ✅ PASS |
| TC-API-005 | PUT | Actualizar usuario | ✅ PASS |
| TC-API-006 | DELETE | Eliminar usuario | ✅ PASS |
| TC-API-007 | PATCH | Actualización parcial de usuario | ✅ PASS |
| TC-API-008 | GET | Filtrar usuario por username | ✅ PASS |
| TC-API-009 | GET | Filtrar usuario inexistente | ✅ PASS |
| TC-API-010 | GET | Validar headers y formato de respuesta | ✅ PASS |

## ✅ Validaciones realizadas

Durante las pruebas se validaron:

- Códigos de estado HTTP: 200, 201 y 404.
- Estructura de las respuestas JSON.
- Campos obligatorios de los usuarios.
- Identificación de usuarios por ID.
- Creación y actualización de datos.
- Eliminación de usuarios.
- Actualizaciones parciales mediante PATCH.
- Filtrado mediante query parameters.
- Respuestas para usuarios inexistentes.
- Header `Content-Type`.
- Ejecución de assertions automáticas mediante scripts de Postman.

## 🚀 Ejecución de la colección

La colección completa fue ejecutada mediante Postman Collection Runner.

Resultado obtenido:

- 10 requests ejecutados.
- 28 tests ejecutados.
- 28 tests aprobados.
- 0 tests fallidos.
- 0 tests omitidos.

## 📸 Evidencias

Las capturas de las pruebas se encuentran en la carpeta:

`test-evidence/`

Incluye evidencias individuales de los casos TC-API-001 al TC-API-010 y el resumen de ejecución de la colección.

## 📦 Colección de Postman

El repositorio incluye la colección exportada de Postman:

`API Testing - JSONPlaceholder.postman_collection.json`

La colección puede importarse directamente en Postman para revisar y ejecutar las pruebas.

## 👨‍💻 Autor

Sergio Cano

Proyecto realizado como parte de mi portafolio de QA Testing.
