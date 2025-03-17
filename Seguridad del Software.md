### **📌 TODO sobre Seguridad del Software 🚀**  

La **Seguridad del Software** es la capacidad de un programa para resistir ataques y proteger la información. **Si el software no es seguro, puede ser hackeado, robado o manipulado.** Así que su seguridad **¡no es opcional!** 🔥  

---

## **🔹 Conceptos clave que SÍ o SÍ debes saber**  

✅ **¿Qué es la Seguridad del Software?**  
Es la protección del software contra ataques maliciosos, errores humanos o vulnerabilidades. El objetivo es **garantizar la confidencialidad, integridad y disponibilidad** de los datos y recursos.  

✅ **¿Por qué es importante?**  
Si un software es inseguro, los atacantes pueden:  
❌ Robar información (datos bancarios, contraseñas)  
❌ Modificar archivos o sistemas (corrupción de datos)  
❌ Bloquear el acceso (ransomware)  
❌ Usar el sistema para ataques a otros (botnets)  

✅ **Diferencia entre Seguridad y Protección del Software**  
- **Seguridad:** Evita ataques desde fuera y dentro.  
- **Protección:** Evita que un usuario normal haga algo indebido en el sistema.  

📢 **Ejemplo:** Un firewall (seguridad) impide accesos no autorizados, mientras que los permisos de usuario (protección) evitan que un empleado borre archivos clave accidentalmente.  

---

## **🔹 Prácticas esenciales de Seguridad del Software 🔐**  

📌 **1. Modelado de amenazas** 🕵️‍♂️  
Antes de escribir código, hay que **predecir ataques**. Se identifican **actores maliciosos** y sus posibles métodos de ataque.  
🔸 **Ejemplo:** Un hacker que intenta inyectar código malicioso en un formulario web.  

📌 **2. Codificación Segura** 💻  
El código debe escribirse **sin fallos que puedan explotarse**. Para ello:  
✅ Usa validaciones de entrada.  
✅ No almacenes contraseñas en texto plano.  
✅ Evita SQL Injection usando consultas preparadas.  

📌 **3. Pruebas de Seguridad** 🧪  
Se realizan pruebas para encontrar fallos **antes de que un hacker lo haga**. Algunas pruebas incluyen:  
🔹 **Pruebas de penetración** (hackeo controlado para ver si el sistema resiste).  
🔹 **Escaneo de vulnerabilidades** (uso de herramientas para detectar fallos).  
🔹 **Revisión de código** (buscar errores en el código antes del despliegue).  

📌 **4. Gestión de Vulnerabilidades** 🚨  
Es un proceso continuo de actualización y monitoreo del software para **cerrar brechas de seguridad**.  
🔹 **Ejemplo:** Si se descubre un fallo en un sistema operativo, la empresa debe lanzar un **parche de seguridad**.  

---

## **🔹 Seguridad en el Ciclo de Vida del Desarrollo del Software (SDLC)**  

📌 **1. Requisitos de seguridad:** Definir qué riesgos existen.  
📌 **2. Diseño seguro:** Aplicar principios de seguridad desde la arquitectura.  
📌 **3. Implementación segura:** Seguir buenas prácticas de codificación.  
📌 **4. Pruebas de seguridad:** Identificar y corregir vulnerabilidades.  
📌 **5. Despliegue seguro:** Asegurar el software antes de publicarlo.  
📌 **6. Mantenimiento continuo:** Monitorear y actualizar para nuevas amenazas.  

📢 **Ejemplo:** Si creas una app bancaria, debes asegurarte de que las transacciones estén encriptadas y que el usuario no pueda ser suplantado.  


### **📌 Todo lo que necesitas saber sobre Autenticación, Autorización y Cifrado🚀**
La **Autenticación**, **Autorización** y **Cifrado** son pilares fundamentales en la seguridad informátic. Comprender estos conceptos es esencial para proteger sistemas y datos sensible. A continuación, te ofrecemos una guía completa para asegurar ese 100/100 en tu prueb.

---

## **🔹 Autenticación: ¿Quién eres? 🕵️‍♂️*

La **autenticación** es el proceso mediante el cual un sistema verifica la identidad de un usuario o dispositv. Es esencial para garantizar que solo las personas autorizadas accedan a recursos específis.

**Puntos clave:**

- **Autenticación del servidor** El servidor verifica la identidad del usuario que intenta accer.
- **Autenticación del cliente** El cliente verifica que el servidor es legítimo y confiae.
- **Métodos comunes de autenticación:**
  - **Contraseñas** La forma más habitual, aunque puede ser vulnerable si no se gestionan correctamee.
  - **Biometría** Uso de huellas dactilares, reconocimiento facial o de z.
  - **Tarjetas inteligentes** Dispositivos físicos que almacenan credenciales de segurid.
  - **Certificados digitales** Emitidos por entidades de confianza como Verisign o Thawte, garantizan la autenticidad de servidores y usuars.

**Ejemplo práctico** Al acceder a tu correo electrónico, introduces tu nombre de usuario y contraseña. El servidor verifica estos datos para confirmar tu identidad antes de otorgarte acco.

---

## **🔹 Autorización: ¿Qué puedes hacer? �**

Una vez autenticado, la **autorización** determina los recursos y acciones a los que tienes pemso. Es el proceso que define tus privilegios dentro del siema.

**Aspectos esenciales:*

- La autorización siempre sigue a la autenticación; primero se verifica quién eres y luego qué puedes cer
- Los permisos pueden variar según el usuario, rol o grupo al que pertencas
- Algunos recursos pueden estar disponibles sin necesidad de autorización específica, como páginas web púbcas.

**Ejemplo práctio:** En una empresa, un empleado del departamento de recursos humanos puede tener acceso a información salarial, mientras que un empleado de otro departamen no.

---

## **🔹 Cifrado: Protegiendo la información en tránsit 🔒**

El **cifrado** transforma datos legibles en un formato ininteligible para protegerlos durante la transmisión o almacenmento. Solo quienes posean la clave de descifrado adecuada pueden acceder a la información oginal.

**Puntos destacados:**

- **Protocolos comunes:**
  - **SSL (Secure Socket Laer):** Utilizado para asegurar conexiones web, visible en URLs que comienzan con "hts://".
  - **SSH (Secure Shll):** Proporciona una forma segura de acceder a sistemas motos.
- **Aplicaciones del cifrado**
  - Protección de datos sensibles como números de tarjetas de crédito o información personal durante transacciones elínea
  - Asegurar comunicaciones entre clientes y servidores para evitar interceptaciones malintencnadas.

**Ejemplo prácico:** Al realizar una compra en línea, el cifrado asegura que los datos de tu tarjeta de crédito viajen de forma segura desde tu navegador hasta el servidor del comerciante, protegiéndolos de posibles interctores.

---

## **🔹 Integrando Autenticación, Autorización y Cifrado en la vida diaia 🌐**

Estos tres conceptos trabajan juntos para garantizar la seguridad en múltiples escenarios cidianos.

**Caso práctico: Viaje en avión**

1. **Compra del boleto en línea:**
   - **Cfrado:** Protege la información de tu tarjeta de crédito durante la trsacción.
2. **Check-in en el aeropuerto:**
   - **Autentiación:** Verificación de tu identidad mediante documento oficial boleto.
3. **Embarque en el avión:**
   - **Autoriación:** Confirmación de que tienes permiso para abordar ese vuelo eecífico.

**Aplicaciones en informática:**

- **Cfrado:** Protege datos personales al registrarte o realizar comprasn línea.
- **Autentiación:** Verifica tu identidad al iniciar sesión en servicios como correo electrónico o redesociales.
- **Autoriación:** Determina qué acciones puedes realizar dentro de una plataforma, como acceder a configuraciones avanzadas o informaciónensible.


### **🚀 Los 12 Factores para Aplicaciones: La Guía Infalible📚🔥**  

Si quieres crear aplicaciones modernas, escalables y listas para la nube, **la metodología de los 12 factores** es tu mejor aliada. Con estos principios, puedes construir software robusto, portable y fácil de mantener. **¡Vamos a desglosarlo de forma clara y dinámica para que lo domines al 100%!**  

---

## **🎯 1. Código Base: Un Repo, Muchos Despliegues**  

🔹 **¿De qué trata?**  
Toda la aplicación debe estar en **un solo repositorio** de código, aunque pueda desplegarse en distintos entornos (desarrollo, pruebas, producción).  

💡 **Clave para el éxito:**  
- Usa **Git** o **Mercurial** para gestionar tu código.  
- No tengas múltiples repositorios para una misma app.  

✅ **Ejemplo:** Un equipo trabaja en una app guardada en **GitHub**, con versiones separadas para desarrollo y producción, pero **todo viene del mismo código base**.  

---

## **🛠 2. Dependencias: No asumas nada, decláralo todo**  

🔹 **¿De qué trata?**  
Nada de asumir que las librerías ya están instaladas en el sistema. Usa **gestores de dependencias** para declararlas explícitamente.  

💡 **Clave para el éxito:**  
- Usa archivos como `package.json` (Node.js), `requirements.txt` (Python) o `pom.xml` (Java).  
- Evita instalar cosas manualmente en el sistema operativo.  

✅ **Ejemplo:** Un proyecto en Node.js usa un `package.json` que lista todas las librerías necesarias, asegurando que cada despliegue tenga **exactamente** las mismas dependencias.  

---

## **🔐 3. Configuración: Todo en Variables de Entorno**  

🔹 **¿De qué trata?**  
Las credenciales, URLs y otras configuraciones **nunca deben estar en el código**. Guárdalas en **variables de entorno**.  

💡 **Clave para el éxito:**  
- No pongas contraseñas en archivos como `config.js` o `settings.py`.  
- Usa `dotenv` o herramientas similares para gestionar variables de entorno.  

✅ **Ejemplo:** En lugar de escribir `DATABASE_URL = "mysql://usuario:password@servidor"`, lo defines como una **variable de entorno**, y el código lo obtiene dinámicamente.  

---

## **📦 4. Servicios de Apoyo: Todo es un Recurso Adjunto**  

🔹 **¿De qué trata?**  
Bases de datos, colas de mensajes o almacenamiento en la nube deben tratarse como **recursos externos** que pueden cambiar sin afectar el código.  

💡 **Clave para el éxito:**  
- Usa variables de entorno para conectar con servicios externos.  
- Permite cambiar un servicio (como PostgreSQL por MySQL) sin modificar el código.  

✅ **Ejemplo:** Hoy tu app usa **Amazon S3** para guardar imágenes, pero mañana decides cambiar a **Google Cloud Storage**. ¡Ningún problema si sigues este principio!  

---

## **🚀 5. Construcción, Lanzamiento, Ejecución: Etapas Claras**  

🔹 **¿De qué trata?**  
Separa bien estas tres fases:  
1. **Construcción:** Se compila el código y se instalan dependencias.  
2. **Lanzamiento:** Se configura la app con variables de entorno.  
3. **Ejecución:** Se corre la app en un servidor.  

💡 **Clave para el éxito:**  
- Usa herramientas como **Docker** o **CI/CD** (Jenkins, GitHub Actions) para automatizar esto.  

✅ **Ejemplo:** Un pipeline de despliegue en **GitHub Actions** que, al hacer un commit, automáticamente construye, configura y despliega la app en producción.  

---

## **🔄 6. Procesos: Sin Estado y Reutilizables**  

🔹 **¿De qué trata?**  
Las aplicaciones deben ejecutarse en **procesos independientes** y **sin estado**.  

💡 **Clave para el éxito:**  
- No guardes información en memoria (usa una base de datos o caché en su lugar).  
- Cada proceso debe ser **replicable** sin problemas.  

✅ **Ejemplo:** En lugar de almacenar sesiones de usuario en memoria, una app web usa **Redis** o **JWTs**, permitiendo escalar sin problemas.  

---

## **🌐 7. Vinculación de Puertos: La App Se Sirve Sola**  

🔹 **¿De qué trata?**  
Tu aplicación debe ejecutar su propio **servidor web** y estar lista para recibir tráfico sin necesitar configuración extra.  

💡 **Clave para el éxito:**  
- Usa **Express.js**, **Flask**, **Spring Boot**, etc., en lugar de depender de servidores externos preconfigurados.  

✅ **Ejemplo:** Un backend en **Node.js** que inicia su propio servidor en el puerto `3000`, en lugar de esperar que un Apache o Nginx lo sirva.  

---

## **📈 8. Concurrencia: Escalar con Procesos**  

🔹 **¿De qué trata?**  
En lugar de hacer que un solo proceso haga todo, **divide la carga en múltiples procesos pequeños**.  

💡 **Clave para el éxito:**  
- Usa **procesos en paralelo** para mejorar rendimiento.  
- Separa procesos de tareas diferentes, como API y procesamiento de datos.  

✅ **Ejemplo:** Una app usa un proceso para atender peticiones HTTP y otro para manejar trabajos en segundo plano con **RabbitMQ**.  

---

## **📂 9. Descartabilidad: Manejo Limpio de Errores**  

🔹 **¿De qué trata?**  
Las apps deben **iniciarse y apagarse rápido** sin dejar residuos ni estados corruptos.  

💡 **Clave para el éxito:**  
- Usa **logs estructurados** y maneja errores de forma limpia.  
- Asegura que la app pueda apagarse sin perder datos importantes.  

✅ **Ejemplo:** Una app en **Docker** que se puede matar y reiniciar sin pérdida de datos porque usa una base de datos externa.  

---

## **🔄 10. Desarrollo/Producción: Similares pero Separados**  

🔹 **¿De qué trata?**  
El entorno de **desarrollo** debe ser lo más similar posible al de **producción**.  

💡 **Clave para el éxito:**  
- Usa **Docker** para garantizar entornos consistentes.  
- Minimiza diferencias entre **staging** y **producción**.  

✅ **Ejemplo:** Una app que se prueba en **Docker en local** y se despliega en **Kubernetes en producción**, con la misma configuración.  

---

## **📜 11. Logs: Registro en Flujo Continuo**  

🔹 **¿De qué trata?**  
Los logs deben ser **eventos estructurados** enviados a un sistema externo para análisis.  

💡 **Clave para el éxito:**  
- Usa **Splunk**, **ELK (Elasticsearch, Logstash, Kibana)** o **CloudWatch** para gestionar logs.  

✅ **Ejemplo:** En vez de guardar logs en archivos, una app envía sus eventos a **ElasticSearch** para monitoreo en tiempo real.  

---

## **🔀 12. Procesos de Administración: Ejecuta Comandos Como Tareas Puntuales**  

🔹 **¿De qué trata?**  
Las tareas administrativas (migraciones, limpieza de datos) deben ejecutarse como comandos temporales, no procesos permanentes.  

💡 **Clave para el éxito:**  
- Usa scripts específicos (`rake db:migrate`, `python manage.py migrate`).  

✅ **Ejemplo:** Una app Django usa `python manage.py migrate` para actualizar la base de datos sin tocar el código principal.  

