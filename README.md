# Propuesta de trabajo

- Diseño de soluciones con UML
- Diseño de apis y modelos de dominio
- Diseño de todo el ciclo de vida de apis y apps 
- Codificación general de backend y supervición de frontend
- Dirigir equipo de programadores 
- Metodología ágil o custom
- Herramientas:
  - Visual Paradigm o simitar (UML)_
  - Trello (Asignación de tareas o Agile)
  - Slack

## Diseño de tests
  - Tests e2d con cypress
  - Test de apis con jest
  - Tests de carga/stress con blazemeter

## Diseño de deployments e integración continua (CI/CD)
  - Modelo Gitflow para desarrollo (features branches) y parches (hotfix)
  - Deployments gatillados por git push
  - Pasos: 
    - Test local
    - Upload a repo
    - Despliegue a máquinas de test:
      - Green/blue: La nueva versión se pone alcance de un pequeño porcentaje de usuarios y luego de va ampliando gradualmente al 100%
      - Canary: Se prueba con un conjunto de usuarios y se evalua performance
      - A/B: Se prueba con un conjunto de usuarios definidos segun alguna propiedad de ellos (localidad, país, browser/mobile)
      - Shadow: Se redirige tráfico real de forma interna a un código que se quiera probar. El usuario no nota diferencias.
    - Despliegue a máquinas de production
    - Logs

## Diseño de infraesctrutura con pulumi en GCP y/o AWS
  - GCP: Compute engine, Cloud SQL, Cloud DNS, Cloud run, Cloud functions, Cloud storage, etc.
  - AWS: EC2, Code Pipeline, RDS, VPC, S3, SNS, etc.
  - Firebase: Authentication, Cloud messaging ,etc.
- Análisis de riegos
- Protocolos de manejo de contingencias
- Plataformas multilenguaje en apis y apps: Hay que mantener archivos de textos en diferentes lenguages. En el código se usan placeholders para los textos los que se reemplazan en tiempo de ejecución según idioma seleccionado por el usuario o colegido por headers HTTP enviados por la app.

## Lineas de estudio e investigación continua de nuevas tecnologias
  - Elixir: permitiría ahorro en capacidad computacional y mejor manejo de errores
  - Blockchain: Decentralizacón de datos, Responsabilida legal compartida?
  - IA y Big data: análisis de data actual, predicciones de mercado, entrenamiento de modelos, who knows...

## Educación continua
- Estoy mejorando mi inglés con clases semanales
- Espero tomar el curso ["Master en Data Science y Big Data"](https://www.iebschool.com/programas/master-data-science) con lo cual espero aportar mucho más valor en el corto y mediano plazo.
  - Empieza el 28/10/2011
  - 10 meses
  - U$S 6.250