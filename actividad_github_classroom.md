# Práctica temática: **Diseño de Mini Proyecto Documentado para Sistemas**

## 1) Propósito de la actividad
En esta tarea vas a **diseñar una propuesta de proyecto pequeño** (no un proyecto grande), con enfoque principal en:

- documentación técnica,
- planeación realista,
- estructura del repositorio,
- justificación del caso de uso.

La meta es que primero demuestres que sabes **pensar y comunicar** una solución antes de escribir mucho código.

---

## 2) Descripción general
Vas a proponer una práctica temática pequeña para ejecutarse en terminal, orientada a arquitectura de computadoras y programación de sistemas.

Debes elegir **un lenguaje principal**:

- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante sobre ARM64 Assembly:** úsalo solo si tu propuesta es **muy pequeña y acotada** (por ejemplo, rutinas simples, manipulación básica de datos o ejercicios cortos de entrada/salida).

### Restricciones de alcance (obligatorias)
Tu propuesta debe ser de bajo costo técnico para que pueda trabajarse con herramientas gratuitas y límites de uso razonables.

**Evita**:
- proyectos grandes,
- frameworks complejos,
- APIs pagadas,
- bases de datos,
- servicios en la nube,
- contenedores,
- dependencias difíciles de instalar.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Directorios opcionales:

- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio
Usa esta estructura mínima como referencia:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## 5) Contenido requerido por archivo

### `README.md`
Incluye:
1. Nombre del proyecto.
2. Lenguaje principal elegido (ARM64 Assembly, C, Python o Bash).
3. Resumen de 5 a 8 líneas del problema que buscas resolver.
4. Alcance delimitado (qué **sí** hace y qué **no** hace).
5. Instrucciones básicas para ejecutar (si ya existe código inicial).

---

### `docs/propuesta.md`
Incluye secciones con este formato:

1. **Título de la práctica temática**
   - Ejemplo: “Asistente de Estudio en Terminal”.

2. **Problema a resolver**
   - ¿Qué necesidad concreta atiende?

3. **Objetivo general**
   - Una sola oración clara y medible.

4. **Objetivos específicos**
   - 3 a 5 objetivos puntuales.

5. **Alcance técnico**
   - Funcionalidades mínimas.
   - Límites del proyecto.

6. **Lenguaje elegido y justificación**
   - ¿Por qué ese lenguaje es el adecuado para esta práctica pequeña?

7. **Estimación breve de esfuerzo**
   - Tiempo estimado total (horas).
   - Riesgos principales (máximo 3) y cómo mitigarlos.

---

### `docs/caso_de_uso.md`
Incluye:

1. **Perfil de usuario**
   - ¿Quién usaría la herramienta?

2. **Escenario principal de uso**
   - Contexto inicial.
   - Entrada que proporciona el usuario.
   - Salida esperada.

3. **Flujo básico paso a paso**
   - De 6 a 10 pasos numerados.

4. **Criterios de éxito del caso de uso**
   - ¿Cómo sabrás que el caso se cumple correctamente?

---

### `docs/estructura_repositorio.md`
Incluye:

1. Árbol del repositorio (actual o planeado).
2. Descripción de cada carpeta/archivo relevante.
3. Convenciones mínimas:
   - nombres de archivos,
   - estilo de scripts,
   - organización de pruebas,
   - ubicación de evidencias (si aplica).

---

### `docs/plan_de_pruebas.md`
Incluye:

1. **Estrategia de pruebas manuales** (mínimo 5 casos).
2. Para cada caso de prueba:
   - ID,
   - objetivo,
   - entrada,
   - procedimiento,
   - resultado esperado,
   - criterio de aceptación.
3. Pruebas de error (entradas inválidas o vacías).
4. Evidencia esperada (captura, log o salida de terminal).

---

## 6) Criterios de evaluación sugeridos (rúbrica)

| Criterio | Porcentaje |
|---|---:|
| Claridad de la propuesta (`docs/propuesta.md`) | 25% |
| Calidad del caso de uso (`docs/caso_de_uso.md`) | 20% |
| Coherencia de la estructura del repositorio (`docs/estructura_repositorio.md`) | 20% |
| Calidad y cobertura del plan de pruebas (`docs/plan_de_pruebas.md`) | 20% |
| Claridad general del `README.md` y presentación | 15% |

---

## 7) Requisitos de calidad

- Redacción técnica clara, sin ambigüedades.
- Coherencia entre problema, objetivos, alcance y pruebas.
- Proyecto **pequeño y realizable**.
- Comandos de ejecución simples y reproducibles.
- Enfoque en terminal y herramientas locales.

---

## 8) Entrega en GitHub Classroom

1. Acepta la tarea en GitHub Classroom.
2. Crea/edita los archivos solicitados.
3. Realiza commits con mensajes claros.
4. Verifica que la estructura final del repositorio sea legible.
5. Entrega la liga de tu repositorio dentro del plazo.

---

## 9) Ideas de temas permitidos (solo referencia)
Puedes inspirarte en alguno de estos temas, sin salirte del alcance pequeño:

- **Mini Toolkit en ARM64**
- **Asistente de Estudio en Terminal**
- **Reporteador de Información del Sistema**
- **Organizador de Archivos**
- **Juego de Aprendizaje en Línea de Comandos**

---

## 10) Resultado esperado
Al final de esta actividad debes tener una propuesta técnicamente sólida, bien documentada y lista para evolucionar a implementación incremental en una práctica posterior.
