
# devLearnDevOps 👋

Esta compañia esta diseñada para crear un proceso de aprendizaje para todo Ingeniero DevOps, aqui se va a encontrar con un path de aprendizaje desde Nivel Basic hasta Expert, teniendo en cuenta cada una de las ramas fundamentals del curso. 

## DevOps Basic

((https://github.com/devLearnDevOps/.github/blob/main/DevOps.jpg) "a title")

### 1. Fundamentos Esenciales (La Base de Todo)
Antes de saltar a las herramientas, necesitas una base sólida.

    * Sistema Operativo Linux: DevOps se ejecuta predominantemente en Linux.

        Qué aprender: Línea de comandos (Bash), estructura del sistema de archivos, permisos (chmod, chown), administración de procesos, editores de texto (Vim/Nano), networking básico (ip, ping, netstat).

    * Redes: Es crucial entender cómo se comunican los sistemas.

        Qué aprender: Modelo TCP/IP, DNS, HTTP/HTTPS, puertos, firewalls, diferencias entre LAN, WAN, VPN.

    * Conceptos de Virtualización: La base de la nube.

        Qué aprender: Qué es un hipervisor, diferencia entre Type 1 y Type 2 (VMware, Hyper-V, VirtualBox).

    * Un Lenguaje de Scripting: Para automatizar todo.

        Python y/o Bash: Python es más poderoso para herramientas complejas, Bash es esencial para scripts rápidos en Linux. Enfócate en Python si tienes que elegir uno.

### 2. La Columna Vertebral: Control de Versiones y CI/CD
El corazón de la integración y entrega continua.

    *  Git (y plataformas como GitHub, GitLab, Bitbucket):

        Qué aprender: Flujos de trabajo (Feature Branch, GitFlow), merge, rebase, cherry-pick, resolución de conflictos, hooks.

    * CI/CD (Integración Continua / Entrega Continua):

        Conceptos: Qué son los pipelines, las etapas (build, test, deploy), la diferencia entre CI y CD.

        Herramientas:

            - Jenkins: El abuelo, muy poderoso y flexible (requiere más configuración).
            - GitLab CI/CD: Muy integrado e popular.
            - GitHub Actions: Dominante en el ecosistema de GitHub.
            - CircleCI, Travis CI: Otras alternativas populares.

### 3. Infraestructura como Código (IaC)
La práctica definitiva de DevOps: gestionar infraestructura con código.

    * IaC de Configuración:

        - Ansible: Agente-less, usa YAML. Ideal para configurar servidores e instalar software. Muy fácil de empezar.

        - Chef / Puppet: Más antiguos, basados en agente. Muy potentes en entornos grandes y complejos.

    * IaC de Provisión:

        - Terraform (IMPRESCINDIBLE): El rey. Permite definir y provisionar recursos de cloud (servidores, redes, bases de datos) de manera declarativa. Aprenderlo es no negociable.

        - AWS CloudFormation / Azure Resource Manager: La herramienta nativa de cada cloud provider. Útil, pero menos universal que Terraform.

### 4. Contenedores y Orquestación
El paradigma moderno de empaquetar y desplegar aplicaciones.

    * Docker:

        Qué aprender: Qué es una imagen y un contenedor, crear Dockerfiles, construir imágenes, manejar volúmenes y redes, docker-compose para entornos multi-contenedor.

    * Orquestación de Contenedores (Kubernetes - K8s):

        - Conceptos: Es el sistema operativo de la nube. Aprende sus componentes principales: Pods, Deployments, Services, Ingress, ConfigMaps, Secrets.

        Qué aprender: Instalar y configurar clusters (puedes empezar con Minikube o Kind en tu laptop), desplegar aplicaciones, gestionar el ciclo de vida. Es la habilidad más demandada.

### 5. Una Plataforma de Nube (Cloud)
Todo pasa en la nube. Elige una y profundiza.

    * AWS (Amazon Web Services): El mercado líder. Tiene el ecosistema más grande.

    * Azure: Muy fuerte en empresas que ya usan Microsoft.

    * Google Cloud Platform (GCP): Muy innovador, especialmente con Kubernetes y Data/AI.

    Qué aprender (para cualquiera que elijas):

        - Cómputo: EC2 (AWS), VMs (Azure), Compute Engine (GCP).
        - Almacenamiento: S3 (AWS), Blob Storage (Azure), Cloud Storage (GCP).
        - Networking: VPC, Load Balancers, DNS.
        - Bases de datos gestionadas: RDS, DynamoDB (AWS), etc.
        - Servicios de identidad: IAM (Roles y Políticas).

### 6. Monitoreo y Observabilidad
"Si no puedes medirlo, no puedes mejorarlo".

    * Monitoreo y Alertas:

        - Prometheus: La herramienta estándar para métricas en Kubernetes y sistemas cloud-native.

        - Grafana: Para visualizar las métricas de Prometheus y otras fuentes con dashboards.

    * Logging:

        - ELK Stack (Elasticsearch, Logstash, Kibana) o EFK (Fluentd en lugar de Logstash): Para centralizar, buscar y analizar logs.

    * Trazado Distribuido:

        - Jaeger o Zipkin: Para rastrear una solicitud a través de múltiples microservicios y encontrar cuellos de botella.

### 7. Habilidades "Blandas" y Cultura
DevOps es tanto una cultura como un conjunto de herramientas.

    * Mentalidad de Automatización: Pregúntate siempre "¿Puedo automatizar esto?".

    * Colaboración y Comunicación: Eres el puente entre desarrolladores y operaciones. Debes hablar ambos idiomas.

    * Metodologías Ágiles: Entender Scrum, Kanban.

    * Seguridad (DevSecOps): Integrar la seguridad desde el principio. Conceptos de scanning de vulnerabilidades en imágenes de Docker, gestión de secretos (con herramientas como HashiCorp Vault), políticas de seguridad.

## Plan de Aprendizaje Sugerido (Ruta de 12-18 meses)
* Fase 1 (Mes 1-3): Domina Linux, Redes y Git. Aprende Python o refuerza Bash.

* Fase 2 (Mes 4-6): Elige un cloud provider (recomendado AWS) y haz sus cursos fundamentals. Aprende Docker a fondo.

* Fase 3 (Mes 7-9): Salta a Terraform y Ansible. Aprende a provisionar infraestructura en tu cloud.

* Fase 4 (Mes 10-12): Entra de lleno en Kubernetes. Es complejo, dedícale tiempo. Configura un cluster y despliega aplicaciones.

* Fase 5 (Mes 13+): Integra todo con un pipelines CI/CD (GitLab CI o GitHub Actions). Añade monitoreo con Prometheus/Grafana.

Nunca Pares: La tecnología evoluciona rápido. Mantente curioso, lee blogs, sigue a expertos en Twitter/LinkedIn y experimenta constantemente.
