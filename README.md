# Laboratorio 3 GitHub Actions

## Ejercicio 1. Workflow CI para el proyecto de frontend

En la clase hemos estado trabajando con el proyecto de la API, pero en este ejercicio trabajarás sobre el proyecto de frontend.

Debes crear un nuevo workflow que se dispare cuando haya cambios en el proyecto hangman-front y exista una nueva pull request (deben darse las dos condiciones a la vez). El workflow ejecutará las siguientes operaciones:

- Build del proyecto
- Ejecución de los test unitarios


## Ejercicio 2. Workflow CD para el proyecto de frontend

Crea un nuevo workflow que se dispare manualmente y haga lo siguiente:

- Crear una nueva imagen de Docker
- Publicar dicha imagen en el container registry de GitHub
  
Nota: intenta usar las actions de Docker vistas en clase

## Ejercicio 3. Workflow para ejecutar tests E2E (opcional)

Crea un workflow que se lance de la manera que elijas y ejecute los tests e2e que encontrarás en este enlace. Puedes usar Docker Compose o Cypress action para ejecutar los tests.