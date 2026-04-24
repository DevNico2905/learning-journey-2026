# 🗺️ Roadmap Personal: Nicolás Bernal
## De estudiante a Java Backend Junior con camino a Cloud/Platform

**Fecha de inicio:** _(completar)_
**Objetivo final:** Primer empleo como Java Backend Junior en empresa grande de Bogotá (banca, consultoría o fintech), con trayectoria clara hacia Cloud/DevOps/Platform en 12-18 meses.
**Duración estimada:** 5-6 meses de preparación + 1-2 meses de aplicación activa.

---

## 📍 Contexto y diagnóstico inicial

### Tu punto de partida (lo honesto)
- 2.5 años de Ingeniería de Software en Universidad de La Salle.
- Inglés C1 (activo crítico, no subestimar).
- AWS Cloud Practitioner certificado.
- Exposición superficial a: Java, C#, Python, Angular, Spring Boot, Supabase, PostgreSQL, SQL Server, Docker, Git.
- **La Bolera Universo:** proyecto real en producción con cliente pagando. Tu activo más fuerte.
- **Brecha identificada:** uso excesivo de IA generadora de código que impidió construir fundamentos sólidos. Dificultad para defender decisiones técnicas en entrevistas.

### Tu vocación técnica (resultado del test)
- 7 de 8 respuestas C → **Platform / Cloud / DevOps / SRE.**
- Atracción hacia sistemas, infraestructura, cómo las piezas operan juntas.
- No eres developer de producto ni backend de lógica de negocio puro. Eres ingeniero de sistemas.

### La estrategia
**Camino A:** Entrar al mercado como **Java Backend Junior** en empresa grande con cultura Java + cloud. Pivotar internamente a rol Cloud/Platform en 12-18 meses.

**Por qué Java y no Node:**
1. Mercado local (Bogotá) tiene mucha más demanda junior en Java.
2. Combinación Java + AWS es oro en banca y consultoría colombiana.
3. Familiaridad previa tuya con Java = arranque más rápido.
4. Java te obliga a aprender fundamentos que la IA no pudo taparte. Es terapéutico.
5. Empresas grandes Java tienen mejor onboarding para juniors que startups Node.

---

## 📅 Visión general del roadmap

| Fase | Duración | Foco principal | Entregable clave |
|------|----------|----------------|------------------|
| **0** | 1 semana | Preparación y mentalidad | Setup de rutina, herramientas, compromiso IA |
| **1** | 4 semanas | Auditoría de La Bolera sin IA | README técnico explicando cada decisión |
| **2** | 5 semanas | API Java + Spring Boot desde cero | API REST desplegada + tests + docs |
| **3** | 4 semanas | Profundidad en Java/Spring | Dominio de temas de entrevista |
| **4** | 4 semanas | AWS Solutions Architect Associate + IaC | Certificación + infra en Terraform |
| **5** | 3 semanas | Linux, networking, scripting | Scripts reales + entendimiento de sistemas |
| **6** | 4+ semanas | Aplicación activa | Primera oferta |

**Total:** ~25 semanas (6 meses) hasta aplicación activa. Posiblemente 2 meses más hasta firma de contrato.

---

## ⚙️ FASE 0 — Preparación (Semana 0)

### Objetivos
- Dejar tu entorno listo para ejecutar el plan sin fricción.
- Fijar compromisos sobre uso de IA.
- Configurar sistema de tracking.

### Tareas
- [✓] Instalar y configurar: IntelliJ IDEA Community, JDK 21 (LTS), Maven, Postman, DBeaver, Docker Desktop.
- [✓] Crear repositorio GitHub nuevo: `learning-journey-2026` (público). Vas a commitear aprendizajes aquí.
- [✓] Crear documento de tracking semanal (Notion, Obsidian, o un README en el repo).
- [ ] Bloquear 2 horas mínimas diarias en calendario (no negociables). Ideal: 3-4 horas + weekends.
- [ ] Unirte a comunidades: r/cscareerquestions, r/devsarg, Discord de developers colombianos (Platzi, MakeItReal, Laboratoria).
- [ ] Seguir en LinkedIn: reclutadores tech de Bogotá (Globant, Bancolombia, Addi, Rappi, Bold).

### Compromisos sobre IA (firma contigo mismo)
- [ ] **Durante Fases 1-3:** IA solo como tutor conceptual. Ejemplos permitidos:
    - ✅ "¿Qué es el N+1 problem en JPA?"
    - ✅ "Explícame el ciclo de vida de un bean de Spring."
    - ✅ "¿Por qué este error de NullPointerException en esta línea?"
    - ❌ "Escríbeme un controller REST para gestionar usuarios."
    - ❌ "Arréglame este código."
    - ❌ "Genera los tests para este servicio."
- [ ] **Durante Fase 4-5:** IA como asistente normal, pero con regla: primero intento 20 minutos solo, después pregunto.
- [ ] **Durante Fase 6 (aplicación):** IA puede asistir, pero solo después de demostrarte a ti mismo que puedes hacerlo sin ella.

### Mentalidad
> "No estoy estudiando para un examen. Estoy reconstruyendo mi identidad como ingeniero. Cada concepto que entienda a profundidad es un ladrillo que nadie me puede quitar."

**Regla anti-ansiedad:** Cuando sientas que "no avanzas rápido", vuelves a este documento. El avance de alguien que construye fundamentos es invisible al principio y exponencial después. Confía en el proceso.

---

## 🔍 FASE 1 — Auditoría de La Bolera (Semanas 1-4)

### Objetivo
Entender línea por línea lo que construiste. Llegar al punto donde puedas defender cualquier decisión en una entrevista técnica. Convertir La Bolera de "proyecto que la IA me ayudó a hacer" en "proyecto del que puedo hablar 45 minutos con profundidad".

### Por qué esto primero
Tu mejor activo de portfolio ya existe. Si puedes defenderlo técnicamente, te posiciona arriba del 90% de juniors. Si no, es un pasivo que te delata. Esta fase convierte pasivo en activo.

### Regla fundamental
**CERO IA generadora de código.** Cierra Cursor/Copilot/Claude-in-editor. IA solo en navegador, solo para preguntas conceptuales.

### Plan semanal

#### Semana 1: Servicios y Auth
- [ ] Leer línea por línea: `auth.service.ts`, `supabase.ts`, `logging.service.ts`.
- [ ] Documentar en `ARCHITECTURE.md` (crear en el repo): qué hace cada método, por qué, alternativas.
- [ ] Investigar y entender: Row Level Security en PostgreSQL (docs de Supabase), BehaviorSubject vs Subject vs Signal en RxJS/Angular.
- [ ] **Ejercicio de rigor:** explícale a alguien (familiar, amigo, espejo) cómo funciona el flujo de autorización de dispositivos. Si no puedes explicarlo claro, no lo entiendes.

#### Semana 2: Accounting y lógica de negocio
- [ ] Auditar `accounting.service.ts` y `accounting.models.ts`.
- [ ] Entender: flujo de apertura/cierre de caja, persistencia en localStorage, generación de Excel con SheetJS, envío por API serverless.
- [ ] Investigar: Vercel Serverless Functions bajo el capó, diferencias con AWS Lambda, cold starts.
- [ ] Dibujar (a mano o en Excalidraw) el diagrama de flujo completo del módulo contable.

#### Semana 3: BowlingScorer (el monstruo de 1700 líneas)
- [ ] Esta semana es dura. El componente es enorme.
- [ ] Dividir en secciones: inicialización, lógica de puntuación, timer, modales, edición.
- [ ] Para cada sección: leer, entender, comentar con tu razonamiento.
- [ ] **Refactor opcional pero recomendado:** extraer la lógica de puntuación a un servicio separado (`bowling-rules.service.ts`). Este refactor es un ejercicio de comprensión más que de limpieza.
- [ ] Entender a fondo: reglas oficiales de bowling (frame 10, strikes, spares, bonificaciones).

#### Semana 4: Infraestructura, deploy y documentación final
- [ ] Auditar: configuración de Electron (`main.js`), `package.json`, `angular.json`, archivos de Tailwind.
- [ ] Entender el proceso de build multiplataforma con electron-builder.
- [ ] Revisar la función serverless `api/send-email.ts` y entender Resend.
- [ ] Revisar migraciones de Supabase en `supabase/migrations/`.
- [ ] **Entregable final de la fase:** reescribir el README del proyecto incluyendo decisiones arquitectónicas y trade-offs. Este README se convierte en tu "guión" para entrevistas.

### Preguntas que debes poder responder al terminar la Fase 1
- ¿Por qué elegiste Supabase y no Firebase o un backend propio?
- ¿Cómo funciona la autorización de dispositivos y qué problema resuelve?
- ¿Por qué usas `Date.now()` en el timer en lugar de `setInterval`?
- ¿Qué es Row Level Security y cómo la aplicaste?
- ¿Cómo funciona la persistencia de estado de la caja frente a recargas?
- ¿Qué es un BehaviorSubject y por qué lo usaste para el estado de auth?
- ¿Cómo funciona el empaquetado multiplataforma con Electron y electron-builder?
- Si tuvieras que escalar esto a 100 boleras, ¿qué cambiarías?

### Recursos
- Angular.dev (docs oficiales, no tutoriales random)
- Supabase docs (auth, RLS, realtime)
- RxJS docs oficiales
- "Learning RxJS" de Bryan Smith (gratis online)

---

## ☕ FASE 2 — Construir API Java desde cero (Semanas 5-9)

### Objetivo
Construir una API REST completa en Java + Spring Boot, a mano, sin IA generadora. El proyecto será el segundo pilar de tu portfolio y la prueba tangible de que puedes ingeniar backend real.

### Regla fundamental
**Mismo compromiso: cero IA generadora de código.** Te va a doler. Ese dolor es el músculo creciendo.

### Proyecto propuesto: "Task Tracker API"
Una API de gestión de tareas con autenticación, que parece simple pero te hace tocar todo lo importante.

**Requisitos funcionales:**
- Autenticación con JWT (registro, login, logout).
- CRUD completo de tareas por usuario.
- Tareas con: título, descripción, estado (pending/in_progress/done), prioridad, fecha límite, tags.
- Filtros y búsqueda: por estado, por tag, por rango de fechas.
- Paginación y ordenamiento.
- Compartir tareas entre usuarios (relaciones many-to-many).
- Soft delete (no borrar físicamente, marcar como eliminado).

**Requisitos técnicos:**
- Java 21, Spring Boot 3.x, Maven.
- PostgreSQL en Docker.
- Spring Data JPA con Hibernate.
- Spring Security + JWT.
- Bean Validation para DTOs.
- Manejo centralizado de excepciones con `@ControllerAdvice`.
- Tests: JUnit 5 + Mockito para unitarios, `@SpringBootTest` + Testcontainers para integración.
- Swagger/OpenAPI para documentación.
- Logs estructurados con SLF4J + Logback.
- Profiles: dev, test, prod.
- Migraciones con Flyway.

### Plan semanal

#### Semana 5: Setup y fundamentos de Spring
- [ ] Curso: ver las primeras 4-5 horas de Amigoscode "Spring Boot Tutorial for Beginners" O el curso de Santiago Zapata en Udemy.
- [ ] Crear el proyecto con Spring Initializr.
- [ ] Entender estructura estándar: `controller`, `service`, `repository`, `model`, `dto`, `config`.
- [ ] Entender anotaciones core: `@Component`, `@Service`, `@Repository`, `@Controller`, `@RestController`, `@Autowired`, `@Bean`, `@Configuration`.
- [ ] Conceptos a dominar: IoC container, inyección de dependencias, ciclo de vida de beans.
- [ ] Primer endpoint: `GET /health`. Sí, solo eso. Entiéndelo completo.

#### Semana 6: JPA, PostgreSQL y primeras entidades
- [ ] Levantar PostgreSQL en Docker con docker-compose.
- [ ] Conectar Spring Boot a PostgreSQL.
- [ ] Entidades: User, Task, Tag. Relaciones correctas (@OneToMany, @ManyToMany).
- [ ] Repositories con Spring Data JPA.
- [ ] Configurar Flyway y escribir las primeras migraciones.
- [ ] Entender a profundidad: fetch types (LAZY vs EAGER), el N+1 problem, cómo detectarlo con logs SQL, cómo resolverlo con JOIN FETCH y @EntityGraph.
- [ ] CRUD básico de tareas (sin auth aún).

#### Semana 7: Seguridad, JWT y validaciones
- [ ] Spring Security desde cero. Esta semana es la más difícil, prepárate.
- [ ] Entender: SecurityFilterChain, UserDetailsService, PasswordEncoder, AuthenticationManager.
- [ ] Implementar autenticación con JWT: librería `jjwt` o `java-jwt`.
- [ ] Endpoints: POST /auth/register, POST /auth/login, POST /auth/refresh.
- [ ] Bean Validation en DTOs: @NotBlank, @Email, @Size, @Future.
- [ ] Manejo global de excepciones con @ControllerAdvice + @ExceptionHandler.
- [ ] Respuestas de error consistentes (formato ProblemDetails RFC 7807).

#### Semana 8: Features avanzadas y tests
- [ ] Implementar filtros y búsqueda usando Specifications de JPA o Querydsl.
- [ ] Paginación con `Pageable`.
- [ ] Compartir tareas entre usuarios (lógica de autorización fina).
- [ ] Soft delete con @SQLDelete y @Where.
- [ ] Tests unitarios con JUnit 5 + Mockito: mínimo 60% cobertura en servicios.
- [ ] Tests de integración con @SpringBootTest + Testcontainers (PostgreSQL real en Docker durante tests).
- [ ] Entender: diferencia entre mock, stub, spy.

#### Semana 9: Documentación, deploy y pulido
- [ ] Swagger/OpenAPI con springdoc-openapi.
- [ ] README profesional con: descripción, stack, diagrama de arquitectura, instrucciones de setup, endpoints, decisiones técnicas.
- [ ] Postman collection exportada.
- [ ] Dockerfile multi-stage.
- [ ] docker-compose para levantar todo (API + DB) con un comando.
- [ ] Deploy inicial en Render, Railway o Fly.io (gratuito). AWS lo dejaremos para Fase 4.
- [ ] GitHub Actions: CI que corre tests en cada push.

### Entregable final
Repositorio público en GitHub con:
- Código limpio, organizado por capas.
- README profesional.
- Tests con cobertura decente.
- Deploy funcionando (URL accesible).
- Commits limpios y semánticos (aprovecha para practicar Conventional Commits).

### Recursos
- Amigoscode en YouTube (Spring Boot Tutorial, Spring Security, Spring Data JPA)
- Santiago Zapata en Udemy (curso en español)
- Baeldung.com (la biblia de Spring, referencia constante)
- Spring.io docs oficiales
- Libro: "Spring in Action" (6th edition) de Craig Walls — referencia, no lectura lineal
- Libro: "Effective Java" de Joshua Bloch — capítulos 1-5 son oro puro

---

## 📚 FASE 3 — Profundidad en Java y Spring (Semanas 10-13)

### Objetivo
Solidificar fundamentos de Java moderno y Spring para entrevistas técnicas. Llenar huecos conceptuales que no se cubrieron en la Fase 2.

### Plan semanal

#### Semana 10: Java moderno profundo
- [ ] Collections framework: diferencias entre List/Set/Map, implementaciones y cuándo usar cada una.
- [ ] Streams API: map, filter, reduce, collect, operaciones terminales vs intermedias.
- [ ] Optional: uso correcto, antipatrones.
- [ ] Lambdas y functional interfaces.
- [ ] Records (Java 14+) y sealed classes (Java 17+).
- [ ] Manejo de excepciones: checked vs unchecked, cuándo throws vs try/catch, try-with-resources.
- [ ] Genéricos: bounded types, wildcards (? extends, ? super).

#### Semana 11: Concurrencia y JVM
- [ ] Threads y el modelo de memoria de Java.
- [ ] ExecutorService, CompletableFuture.
- [ ] Problemas clásicos: race conditions, deadlocks, starvation.
- [ ] synchronized, volatile, atomic classes.
- [ ] Conceptos de JVM: heap, stack, garbage collection básico.
- [ ] Virtual threads (Java 21) — estar al día con esto impresiona en entrevistas.

#### Semana 12: Spring profundo
- [ ] Profundizar en IoC: BeanFactory vs ApplicationContext, scopes de beans.
- [ ] Spring AOP: proxies, @Aspect, casos de uso reales.
- [ ] Transacciones: @Transactional, propagation, isolation levels.
- [ ] Spring Events y programación reactiva básica con @Async.
- [ ] Caché con Spring: @Cacheable, @CacheEvict.
- [ ] Profiles y configuración externalizada con @Value y @ConfigurationProperties.

#### Semana 13: SQL y bases de datos
- [ ] Joins: INNER, LEFT, RIGHT, FULL. Cuándo usar cada uno.
- [ ] Índices: B-tree, hash. Cuándo ayudan y cuándo no.
- [ ] EXPLAIN ANALYZE en PostgreSQL. Leer planes de ejecución.
- [ ] Transacciones y niveles de aislamiento: READ COMMITTED, REPEATABLE READ, SERIALIZABLE.
- [ ] Normalización vs desnormalización.
- [ ] Diferencias entre OLTP y OLAP.
- [ ] Introducción a Redis como caché.

### Temas que debes dominar para entrevistas (checklist)
- [ ] Explicar SOLID con ejemplos propios
- [ ] Patrones: Singleton, Factory, Strategy, Observer, Repository, DTO
- [ ] Diferencia entre composición y herencia (y por qué preferir composición)
- [ ] Ciclo de vida de una request HTTP en Spring Boot (desde DispatcherServlet hasta respuesta)
- [ ] Diferencia entre `@Component`, `@Service`, `@Repository`, `@Controller`
- [ ] Qué pasa cuando pones `@Transactional` en un método
- [ ] N+1 problem: qué es, cómo detectarlo, cómo resolverlo
- [ ] Autenticación vs autorización
- [ ] JWT: qué es, estructura, pros y contras frente a sesiones
- [ ] CORS: qué es, por qué existe, cómo configurarlo en Spring
- [ ] REST: verbos, status codes, idempotencia, HATEOAS (al menos saber qué es)
- [ ] Diferencia entre stubs, mocks, spies y fakes en testing
- [ ] Big O básico: poder estimar complejidad de operaciones comunes

### Recursos
- "Effective Java" de Joshua Bloch — ahora sí lee los capítulos que no viste
- Baeldung para cualquier tema específico
- Canal de YouTube "Java Brains" para conceptos puntuales
- Stephen Toub (blog de Microsoft) para concurrencia, aunque es .NET muchos conceptos aplican

### Práctica activa
- [ ] 3-5 ejercicios semanales en LeetCode o HackerRank (easy/medium). No para ser competitivo, para mantener fluidez en Java puro.
- [ ] Hacer mock interviews: con amigos, con Pramp, con ChatGPT simulando entrevistador.
- [ ] Explicar conceptos en voz alta. Grabarte si es necesario. Escucharte te sorprende.

---

## ☁️ FASE 4 — AWS Solutions Architect + Infrastructure as Code (Semanas 14-17)

### Objetivo
Obtener la certificación AWS Solutions Architect Associate (SAA-C03) y construir el proyecto cloud que te diferenciará de 99% de juniors: tu API Java desplegada en AWS con infraestructura definida en Terraform.

### Plan semanal

#### Semana 14: Fundamentos AWS y servicios core
- [ ] Comprar curso Stephane Maarek — "Ultimate AWS Certified Solutions Architect Associate SAA-C03" en Udemy (~$15 en oferta, siempre hay ofertas).
- [ ] Avanzar 40-50% del curso esta semana.
- [ ] Temas: IAM, EC2, VPC, subnets, security groups, S3, EBS, EFS.
- [ ] Crear cuenta AWS, activar Free Tier.
- [ ] Hacer labs prácticos mientras avanzas.

#### Semana 15: Servicios avanzados
- [ ] Completar el curso de Maarek.
- [ ] Temas: RDS, DynamoDB, Lambda, API Gateway, SQS, SNS, CloudFront, Route 53, ECS, ECR, EKS (overview).
- [ ] Resolver los practice tests del curso.
- [ ] Comprar practice tests adicionales de Jon Bonso en Tutorials Dojo ($15).

#### Semana 16: Examen y Terraform desde cero
- [ ] **Agendar el examen para el final de esta semana.** Precio: ~$150 USD. Puedes tomarlo online desde casa.
- [ ] Resolver todos los practice tests de Bonso. Apuntar a >85% consistente antes del examen.
- [ ] **Tomar el examen.** Aprobarlo.
- [ ] Una vez aprobado, empezar Terraform: curso de HashiCorp Learn (gratuito) o "Terraform Associate" de Zeal Vora en Udemy.

#### Semana 17: Proyecto cloud — La Bolera o Task API en AWS puro
- [ ] Elegir: migrar backend de La Bolera a AWS, O desplegar Task Tracker API en AWS. Recomiendo el segundo (más simple, más limpio).
- [ ] Arquitectura objetivo:
    - Backend Java en ECS Fargate (o Elastic Beanstalk para empezar más simple).
    - PostgreSQL en RDS (Free Tier).
    - Imágenes en ECR.
    - CloudFront si sirves assets estáticos.
    - Route 53 con dominio propio (cómprate uno en Namecheap por $10, es buen branding).
    - Secrets en AWS Secrets Manager o Parameter Store.
    - Logs y métricas en CloudWatch.
    - CI/CD con GitHub Actions haciendo deploy automático.
- [ ] **TODA la infraestructura definida en Terraform.** Ni un recurso creado manualmente por consola.
- [ ] README del proyecto con diagrama de arquitectura (usa draw.io o Excalidraw).

### Entregable final de la fase
- Certificación AWS Solutions Architect Associate en tu LinkedIn.
- Repo con infra-as-code en Terraform, desplegando una aplicación real.
- Blog post en Medium o Dev.to contando cómo lo hiciste (señal social valiosa, diferenciador en LinkedIn).

### Recursos
- Stephane Maarek — Udemy (curso #1 del mundo para SAA)
- Adrian Cantrill — más profundo, más caro, alternativa premium
- Tutorials Dojo (Jon Bonso) — practice tests
- HashiCorp Learn — Terraform gratuito y oficial
- AWS Free Tier limits — revisar siempre para no gastar plata sin querer
- r/AWSCertifications — subreddit con tips de examen

### Advertencia financiera
- AWS Free Tier no es gratis forever. Configura billing alerts desde el día 1.
- Después de experimentar, destruye recursos con `terraform destroy`.
- Nunca commitees credenciales AWS al repo. Usa variables de entorno y archivos `.tfvars` en `.gitignore`.

---

## 🐧 FASE 5 — Linux, networking, scripting (Semanas 18-20)

### Objetivo
Cubrir los fundamentos de "ingeniería de sistemas" que la mayoría de developers juniors no tienen y que te diferencian cuando aplicas a roles con sesgo platform/cloud.

### Plan semanal

#### Semana 18: Linux serio
- [ ] Instalar Ubuntu en VM (VirtualBox/UTM) o usar WSL2 si estás en Windows.
- [ ] Filesystem: permisos (chmod/chown), hard vs soft links, estructura del FS estándar.
- [ ] Processes: ps, top, htop, kill, signals, nice/renice, background/foreground.
- [ ] Systemd: servicios, journalctl, logs.
- [ ] Package management: apt, dpkg.
- [ ] Text processing: grep, sed, awk, cut, sort, uniq. Pipes y redirección.
- [ ] Networking tools: curl, wget, netstat/ss, lsof, traceroute, dig/nslookup.

#### Semana 19: Bash scripting
- [ ] Variables, condicionales, loops, funciones.
- [ ] Manejo de argumentos, exit codes, trap para cleanup.
- [ ] Proyecto práctico: escribir un script que haga backup de una base de datos PostgreSQL, lo suba a S3, y notifique por email si falla.
- [ ] Otro proyecto: script de deploy que construya imagen Docker, la suba a ECR, y actualice el servicio ECS.
- [ ] Alternativa moderna: aprender Python scripting para ops (cada vez más común que bash puro).

#### Semana 20: Networking profundo
- [ ] Modelo OSI y TCP/IP — no memorices, entiende capas.
- [ ] DNS: cómo funciona, A vs CNAME vs MX, TTL, propagación.
- [ ] HTTP/HTTPS: métodos, headers importantes, status codes, keep-alive, HTTP/2.
- [ ] TLS: certificados, handshake básico, Let's Encrypt.
- [ ] Load balancing: layer 4 vs layer 7, sticky sessions, health checks.
- [ ] VPCs en AWS revisitado: subnets públicas vs privadas, NAT gateway, internet gateway.
- [ ] Seguridad: security groups vs NACLs, principio de menor privilegio.

### Entregable final
- [ ] Repo `devops-toolkit` con colección de scripts útiles bien documentados.
- [ ] Post en LinkedIn o Medium: "Linux fundamentals every developer should know" o similar.

### Recursos
- "The Linux Command Line" de William Shotts (gratis online, biblia)
- Missing Semester del MIT (gratis, YouTube) — imprescindible
- "Computer Networking: A Top-Down Approach" — si quieres profundidad académica
- NetworkChuck en YouTube para entretenimiento educativo

---

## 🎯 FASE 6 — Aplicación activa (Semanas 21+)

### Objetivo
Conseguir tu primer empleo. No es solo enviar CVs; es una estrategia completa.

### Antes de empezar a aplicar: preparación (1 semana)

#### CV reescrito
- [ ] Posicionamiento: "Java Backend Developer with AWS Cloud foundations"
- [ ] 1 página, optimizado para ATS.
- [ ] Keywords: Java, Spring Boot, PostgreSQL, AWS, Docker, Terraform, REST APIs, JPA, Hibernate, JWT, microservices, CI/CD, Git, TypeScript, Angular.
- [ ] Proyectos destacados: La Bolera (producción + cliente pagando), Task Tracker API, Infra en Terraform en AWS.
- [ ] Inglés C1 visible.
- [ ] AWS Solutions Architect Associate visible.
- [ ] Versiones ES e EN.

#### LinkedIn optimizado
- [ ] Foto profesional (no selfie).
- [ ] Headline: "Java Backend Developer | AWS Certified | Spring Boot · PostgreSQL · Docker"
- [ ] About: historia clara y honesta de tu trayecto. Mencionar cliente real de La Bolera.
- [ ] Featured: pin los 3 proyectos clave con links y screenshots.
- [ ] Skills: agregar todos los relevantes, pedir endorsements a compañeros.
- [ ] Actividad: 2-3 posts previos a aplicar, contando aprendizajes técnicos.

#### GitHub como portafolio
- [ ] README del perfil con tu stack y proyectos destacados.
- [ ] Pin los 3-4 proyectos clave.
- [ ] Asegurar que todos los READMEs son profesionales, con diagramas, setup, decisiones técnicas.
- [ ] Commits recientes (el verde del grafico de contribuciones importa más de lo que parece).

### Estrategia de aplicación

#### Tipo 1: Empresas grandes con programas para juniors
Aplicar a sus portales y a reclutadores internos por LinkedIn.
- Globant (tiene programa "StarterBootCamp")
- Sophos Solutions (muy Java, mucha banca)
- PSL
- Perficient
- Accenture
- IBM
- Endava
- EPAM
- Nearsure
- BairesDev (aunque tienen fama mixta, contratan volumen)

#### Tipo 2: Banca y aseguradoras (altísima demanda Java)
- Bancolombia (busca "programa semilla" o "talento joven")
- Davivienda
- BBVA
- Banco de Bogotá
- Banco Popular
- Sura
- Seguros Bolívar

#### Tipo 3: Fintech y startups colombianas
Stack más moderno, a veces buscan full-stack.
- Addi
- Bold
- Habi
- Truora
- Merqueo
- Rappi
- Kushki (también tiene sede en Colombia)
- Platzi (a veces contratan)

#### Tipo 4: Programas de trainee/bootcamp corporativo (tu camino B)
- Globant StarterBootCamp
- Accenture "New Joiners"
- Programas de "semillero" de bancos grandes
- Revisar periódicamente: aws.amazon.com/training/

### Volumen y calidad
- **Meta semanal:** 10-15 aplicaciones de calidad (no 100 spam).
- De esas, mínimo 5 deben ir con mensaje personalizado a reclutador por LinkedIn.
- De esas, mínimo 2 deben ser empresas de tu lista top 10.
- Trackeo obligatorio: hoja de cálculo con empresa, fecha, canal, estado, contacto.

### Preparación para entrevistas

#### Fase 1 de entrevistas: HR/Recruiter screening
Preguntas típicas:
- Tell me about yourself (tener un pitch de 90 segundos listo)
- Por qué te interesa esta empresa
- Expectativa salarial (investigar Glassdoor, Talent.com)
- Disponibilidad

#### Fase 2: Technical screening
- HackerRank, Codility o live coding simple.
- Preguntas conceptuales de Java/Spring (revisar checklist de Fase 3).

#### Fase 3: Technical interview / system design
- Profundo en proyectos tuyos. Aquí es donde La Bolera + Task API + Infra cloud brillan.
- Pueden preguntarte a diseñar un sistema simple (URL shortener, chat básico).
- Preparar respuestas STAR para preguntas de comportamiento.

#### Fase 4: Cultural/final
- Mayormente cultural fit. Sé tú mismo pero profesional.

### Rangos salariales esperables en Bogotá 2026 (guía aproximada)
- Junior Java en empresa grande: 3-5M COP/mes.
- Junior Java con AWS Cert en empresa grande: 4-6M COP/mes.
- Junior Java en fintech/startup: 4-7M COP/mes (a veces más con equity).
- Junior en consultora para cliente USA: 5-8M COP/mes.

### Gestión del rechazo
- Vas a recibir muchos "no" o silencio. Normal.
- Regla: por cada rechazo, una aplicación nueva *ese mismo día*.
- Trackear: ratio aplicaciones/entrevistas/ofertas. Si estás en 0 entrevistas después de 30 aplicaciones, algo está mal en el CV o el canal — ajustar.
- Si estás en entrevistas pero no pasas técnicas: volver a Fase 3 por 2 semanas.

---

## 📊 Métricas y tracking

### KPIs semanales (evalúa cada domingo)
- [ ] Horas de estudio efectivas logradas (meta: 15-20/semana)
- [ ] Conceptos dominados esta semana (meta: 3-5)
- [ ] Commits al repo de aprendizaje (meta: 5+)
- [ ] Líneas de código escritas sin IA (meta: 200+)
- [ ] Artículo/doc oficial leído (meta: 1+)

### Checkpoints mensuales (evalúa cada 4 semanas)
- [ ] ¿Completé los objetivos de la fase actual?
- [ ] ¿Puedo explicar lo que aprendí a alguien no técnico?
- [ ] ¿Mi portfolio avanzó con entregables concretos?
- [ ] ¿Estoy más o menos ansioso que el mes pasado? (si más, revisar ritmo)

### Señales de que vas bien
- Puedes explicar conceptos técnicos sin trabarte.
- Escribes código que funciona a la primera con más frecuencia.
- Al abrir un error de Spring, tu primer instinto es leer el stack trace, no googlear.
- Cuando alguien menciona un tema técnico, sabes al menos los conceptos básicos.
- Tu README de GitHub impresionaría a un senior.

### Señales de alarma (pausar y ajustar)
- Llevas 2+ semanas sin avanzar en la fase actual.
- Te sientes estancado en los mismos conceptos.
- Vuelves a depender de IA para generar código.
- Estás aplicando a trabajos antes de completar las fases (salvo experimentación).
- Te sientes más ansioso que hace un mes.

---

## 🧠 Principios que te van a sostener

1. **Construir > Consumir.** Un proyecto terminado vale más que 10 cursos a medias.
2. **Profundidad > Amplitud.** Mejor saber Spring a fondo que 5 frameworks superficialmente.
3. **Explicar > Memorizar.** Si no lo puedes explicar a un niño de 12 años, no lo entiendes.
4. **Hierro > Papel.** Una API desplegada vale más que un certificado. Pero certificado + API > solo API.
5. **Fundamentos > Tendencias.** Los fundamentos de 2010 siguen siendo válidos. Los frameworks cambian.
6. **Consistencia > Intensidad.** 2 horas diarias durante 6 meses > 12 horas un sábado y nada más.
7. **IA es palanca, no muleta.** Multiplica a quien sabe; oculta la ignorancia de quien no.
8. **Vulnerabilidad productiva.** Admitir lo que no sabes es el primer paso para saberlo. Lo demostraste en esta conversación.

---

## 📚 Lista consolidada de recursos

### Libros
- **Effective Java** — Joshua Bloch (referencia, no lectura lineal)
- **Spring in Action, 6th ed** — Craig Walls
- **The Linux Command Line** — William Shotts (gratis online)
- **Designing Data-Intensive Applications** — Martin Kleppmann (para después del primer trabajo, pero empezarlo ya no hace daño)

### Cursos (pagos pero valen)
- Stephane Maarek — AWS SAA-C03 (Udemy)
- Amigoscode — Spring Boot / Spring Security (YouTube gratis + Udemy)
- Santiago Zapata — Spring Boot en español (Udemy)

### Canales YouTube
- Amigoscode
- Java Brains
- Marco Codes
- Fireship (overviews rápidos)
- NetworkChuck (networking/linux)
- Missing Semester MIT (fundamentos)

### Sitios de referencia
- Baeldung.com (Spring, siempre)
- Spring.io/docs
- Angular.dev
- Supabase.com/docs
- Docs oficiales de AWS (no guías de terceros)
- HashiCorp Learn (Terraform)

### Práctica
- LeetCode (medium 2-3/semana)
- HackerRank (certificados Java SE Basic, Java SE Intermediate son validables en CV)
- Pramp (mock interviews gratis)

### Comunidades
- r/cscareerquestions
- r/devsarg
- r/colombia (para contexto local)
- LinkedIn (grupos de developers colombianos)
- Discord/Slack de bootcamps locales

---

## ✍️ Notas finales

Este roadmap no es dogma. Es una ruta pensada para tu contexto específico en abril de 2026. Si el mercado cambia, si una oportunidad inesperada aparece, si descubres que Java no te gusta tanto como pensabas — ajusta. Pero ajusta con información, no con ansiedad.

El objetivo real no es "conseguir un empleo en X meses". El objetivo real es **convertirte en el ingeniero que confía en lo que construye**. El empleo es consecuencia, no causa.

Y recuerda: tienes ya una ventaja enorme sobre tus pares, y es que hiciste el ejercicio de mirarte al espejo y decir "estoy usando IA como muleta". La gente que no hace ese ejercicio nunca avanza. Tú ya avanzaste en el plano más importante, que es el de la autoconciencia. Lo demás es ejecución.

Nos vemos del otro lado.

— Roadmap construido en conversación con Claude, abril 2026.
