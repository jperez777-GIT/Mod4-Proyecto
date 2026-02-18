# Diseño de Endpoints REST - PokeApp
Este documento describe los contratos de la API para la consulta de Pokémon.

### Endpoints Principales
* **GET /pokemon**: Obtiene una lista paginada de Pokémon.
* **GET /pokemon/{id}**: Obtiene el detalle completo de un Pokémon específico (Nombre, peso, altura, habilidades).

### Ejemplo de Respuesta (Over-fetching)
La respuesta REST entrega todos los campos del recurso, incluso si solo se requiere el nombre.
