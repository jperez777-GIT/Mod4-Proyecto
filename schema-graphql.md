# Definición de Esquema GraphQL
Propuesta para optimizar las consultas evitando el sobre-procesamiento de datos.

### Esquema (Types)
type Pokemon {
  id: ID!
  name: String!
  weight: Int
  height: Int
  evolutions: [Pokemon]
}

### Query de Ejemplo
query {
  pokemon(id: "1") {
    name
    evolutions {
      name
    }
  }
}
