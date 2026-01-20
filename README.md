# Mi API de Preguntas (Node.js)

API **educacional** creada únicamente para **enseñar y probar endpoints** en Node.js con Express.  
No incluye autenticación ni lógica avanzada; su objetivo es servir datos JSON de forma simple para prácticas de frontend, testing o consumo de APIs.

---

## Tecnologías usadas

- Node.js (>= 14)
- Express
- CORS

---

## Puesta en marcha

1. Instalar dependencias:

```bash
npm install
```

2. Iniciar el servidor:

```bash
npm start
```

Por defecto, la API se levanta en:

```
http://localhost:3000
```

---

## 🔗 Endpoints disponibles

### Obtener todas las preguntas

**GET** `/api/questions`

Devuelve un array JSON con todas las preguntas disponibles.

#### Ejemplo de respuesta

```json
[
  {
    "q": "¿Cuál es el paradigma económico que se caracteriza por su falta de consideración hacia el reciclaje y la reutilización, siguiendo un esquema de extracción, producción, consumo y desecho?",
    "options": [
      "Modelo de Negocio Circular",
      "Economía Circular",
      "Economía Sostenible",
      "Modelo de Economía Lineal"
    ],
    "answer": 3
  }
]
```

---

## Notas

- La API es **pública y sin autenticación**.
- Los datos se cargan desde un archivo local `questions.json`.
- Pensada para **aprendizaje**, pruebas con `fetch`, `axios`, Postman o prácticas de frontend.
- No se recomienda para uso en producción.

---

## Estructura básica

```
├── server.js
├── questions.json
├── package.json
└── README.md
```

---

## Uso educativo

Ideal para:

- Aprender consumo de APIs REST
- Pruebas de CORS
- Simulación de backend sencillo
- Ejercicios de JavaScript / frontend

---

Exactamente lo necesario para practicar endpoints.
