# Propuesta de trabajo

Estas son algunas ideas y procedimientos que propongo para mejorar tu empresa en el ámbito informático.

Una meta principal es lograr confianza en la estabilidad de los sistemas incluso en la eventualidad de picos de visitas.

Otra en segundo plano pero fundamental es la seguridad de los datos de clientes o asociados y en general todo.

Lograr implantar una filosofía de desarrollo continuo mediantes tests y pipelines de deployments a prueba de fallos en producción.

Con Firebase Authentication podemos mejorar la experiencioa de registro de nuevos usuarios para que puedan usar sus cuentas de google, facebook, twitter, etc)

Personalmente me importa mucho la imagen de la empresa. Encuentro inaceptable caídas, demoras, mesajes de errores sin sentido.

Aqui hago un resúmen de las capacidades y tareas que espero desplegar para crear una nueva estructura informática para portalterreno.

## Ingeniería de software

- Diseño de soluciones con UML
- Diseño de apis y modelos de dominio
- Diseño de todo el ciclo de vida de apis y apps 
- Codificación marco de backend y supervición de buenas prácticas en frontend: 
  - Quiero desarrollar los marcos generales de codificación en backend (node.js) para luego poder destinar trabajo a programadores de apoyo.
  - Supervisar calidad de implementación de código en frontend, desarrollo y uso de tests.
- Dirigir equipo de programadores junior y semi senior
- Uso de metodología ágil o custom. En esto soy pragmático y flexible pero exigente en resultados. Los tiempos son siempre un tema y en general siempre hay atrasos. Es parte de la realidad del ciclo de vida del software. Pero el compromiso es la excelencia en los resultados.
- Herramientas:
  - Visual Paradigm o simitar (UML)_
  - Trello (Asignación de tareas o Agile)
  - Slack

## Diseño de tests
  - Tests e2d con cypress: tests de vueltas completas desde la app, llendo a backend y volviendo a la app.
  - Test de apis con jest: tests unitarios y simulación de llamadas a apis o workers. Uso de mocks para llamadas externas: Solo se testea la api, se da por hecho que los third party harán bien su trabajo.
  - Tests de carga/stress con blazemeter: Se prueban diferentes combinaciones de configuraciones máquinas, bases de datos, etc, para afinar la infraestructura tanto en tiempos normales como de cargas repentinas.

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

- Análisis de riegos
- Protocolos de manejo de contingencias
- Plataformas multilenguaje en apis y apps: Hay que mantener archivos de textos en diferentes lenguages. En el código se usan placeholders para los textos los que se reemplazan en tiempo de ejecución según idioma seleccionado por el usuario o colegido por headers HTTP enviados por la app.

## Lineas de estudio e investigación continua de nuevas tecnologias
  - Elixir: permitiría ahorro en capacidad computacional y mejor manejo de errores
  - Blockchain: Decentralizacón de datos, Responsabilida legal compartida?
  - IA y Big data: análisis de data actual, predicciones de mercado, entrenamiento de modelos, who knows...

## Educación personal continua
- Estoy mejorando mi inglés con clases semanales
- Espero tomar el curso ["Master en Data Science y Big Data"](https://www.iebschool.com/programas/master-data-science) con lo cual espero aportar mucho más valor en el corto y mediano plazo.
  - Empieza el 28/10/2011
  - 10 meses
  - U$S 6.250

## Libertad para viajar
- Puedo viajar de ser necesario y llegado el momento para entrenar a otros equipos de desarrolladores e ingenieros para mantener un marco unificado de calidad e interoperabilidad de sistemas y esquemas trabajo.

## Conclusión

Me gusta el estado en que se encuentra portalterreno ahora. Es el momento ideal para, despues de haber implantado fuertemente su posición diferenciadora en el mercado nacional y estar entrando con seguridad a otros países, asegurar lo que se tiene y planear con tranquilidad pero eficiencia el próximo paso.   
Una versión 2 usando todo lo mejor que nos ofrece la tecnología cloud junto a la experiencia, responsabilidad y excelencia que espero poner a sus disposición.