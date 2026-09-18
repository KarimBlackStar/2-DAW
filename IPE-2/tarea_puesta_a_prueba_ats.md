# MISIÓN: SOBREVIVIR AL ATS (SOLUCIONARIO)

**Pack de simulación de cribado para IPE II · Familia profesional de Informática**

**Objetivo:** comprender cómo una oferta, las palabras clave y la evidencia de competencias influyen en un primer cribado automatizado, y por qué superar el filtro no equivale a ser la mejor candidatura.

## FICHA DE MISIÓN

CYBERGAL ha recibido 126 candidaturas para cubrir una vacante junior. Antes de que RR. HH. revise los currículos, un sistema ATS realiza un primer cribado. Solo las candidaturas que alcancen el umbral pasan a la siguiente fase.

| Fase | Rol | Decisión | 
 | ----- | ----- | ----- | 
| 1 | ATS | ¿Supera 65 puntos? | 
| 2 | RR. HH. | ¿Qué 3 candidaturas parecen más sólidas y coherentes? | 
| 3 | Responsable IT | ¿Qué 2 personas pasan a la entrevista técnica? | 
| 4 | Entrevista | ¿A quién contrataríais y por qué? | 

## HOJA DE CRIBADO COMPLETADA

**Evaluador:** Sistema ATS + Equipo de Selección CYBERGAL

| Candidato | Puntuación ATS | ¿Pasa de fase? | Fortaleza principal | Alerta / duda | 
 | ----- | ----- | ----- | ----- | ----- | 
| **Daniel Varela** | 24<br>*(ASIR +15, Resolución de problemas +2, Trabajo en equipo +2, CV adaptado +5)* | &#10060; NO | CV sincero y honesto. | No usa términos exactos. Pierde los puntos de idioma por poner "nivel intermedio" y no especificar "B1/B2". | 
| **Laura Souto** | 83<br>*(ASIR +15, Linux +5, Windows Server +5, TCP/IP +5, Active Directory +5, Firewalls +5, Monitorización de sistemas +5, Inglés B2 +10, Resolución de problemas +2, Trabajo en equipo +2, Python +3, Docker +3, Git/GitHub +3, Proyecto relacionado +10, CV adaptado +5)* | &#9989; SÍ | Coherencia total entre conocimientos y demostración (laboratorio doméstico). | Perfil muy sólido, sin alertas. | 
| **Hugo Costa** | 25<br>*(ASIR +15, Linux +5, Resolución de problemas +2, Python +3)* | &#10060; NO | Formato visualmente atractivo. | El ATS no lee "estrellitas", no traduce "Team player" ni asume que "Windows" equivale a "Windows Server". | 
| **Marcos Rey** | 76<br>*(ASIR +15, Linux +5, Windows Server +5, TCP/IP +5, Active Directory +5, Firewalls +5, Monitorización de sistemas +5, SIEM +5, Inglés B2 +10, Resolución de problemas +2, Trabajo en equipo +2, Python +3, Docker +3, Azure +3, Git/GitHub +3)* | &#9989; SÍ | Supera el umbral por inyectar casi todas las palabras clave de la oferta. | Lista de certificaciones y tecnologías (CCNA, SIEM, Docker) que no concuerdan con su experiencia (instalar equipos e impresoras). Su CCNA no suma porque no afirma tenerlo, solo lo lista. | 
| **Iria Barreiro** | 70<br>*(ASIR +15, Linux +5, Windows Server +5, TCP/IP +5, Active Directory +5, SIEM +5, Inglés B1 +10, Trabajo en equipo +2, Git/GitHub +3, Proyecto relacionado +10, CV adaptado +5)* | &#9989; SÍ | Demuestra competencias a través de proyectos reales de aula. | Pierde puntos porque el ATS busca literalmente "resolución de problemas", "monitorización de sistemas" o "firewalls", y ella usa variaciones ("resolución de incidencias", "monitorización de servidores", "firewall" en singular). | 
| **Noa Vidal** | 94<br>*(ASIR +15, Linux +5, Windows Server +5, TCP/IP +5, Active Directory +5, Firewalls +5, Monitorización de sistemas +5, SIEM +5, Inglés B2 +10, Resolución de problemas +2, Trabajo en equipo +2, Python +3, Docker +3, CCNA +3, Azure +3, Git/GitHub +3, Proyecto relacionado +10, CV adaptado +5)* | &#9989; SÍ | Puntuación perfecta, redactado para el algoritmo. | Proyecto descrito totalmente irreal para unas prácticas de FP. Evidente uso sin filtro de IA. | 

* **Tres candidaturas seleccionadas por RR. HH.:** 1) Laura Souto 2) Iria Barreiro 3) Noa Vidal
  *(Marcos es descartado al instante por Recursos Humanos: es evidente que solo puso palabras clave sin experiencia que las respalde).*

* **Dos candidaturas seleccionadas por el responsable IT:** 1) Laura Souto 2) Iria Barreiro

**Justificación del evaluador (Responsable IT):**
Seleccionamos a Laura e Iria porque sus currículums son coherentes y realistas. Laura tiene un laboratorio en casa e Iria detalla proyectos de clase (laboratorio SIEM) que encajan con una posición Junior. Descartamos a Noa: aunque superó el ATS con nota máxima, afirmar que diseñó una "arquitectura integral de ciberseguridad automatizada en Azure" durante una FCT es mentira, fruto de generar el CV con IA sin adaptarlo a la realidad.

## FASE 4 · MINI ENTREVISTA

### Preguntas comunes para finalistas (Laura e Iria)

 1. Has mencionado que tienes laboratorios/proyectos. ¿Puedes explicarme cómo montaste la red y qué hypervisor usaste?
 2. Si un usuario reporta que no puede acceder a una carpeta compartida en Windows Server, ¿qué pasos sigues para diagnosticarlo?
 3. ¿Cómo configurarías una regla de firewall básica para permitir tráfico web pero bloquear ping (ICMP)?
 4. ¿Qué información buscas primero al revisar los logs en un sistema de monitorización?
 5. ¿Qué comando en Linux usarías para ver tu IP actual y cuál para comprobar si llegas al servidor DNS?
 6. Háblame de alguna incidencia técnica que te haya costado resolver en tus prácticas y cómo lo solucionaste.
 7. Usamos herramientas que no has visto en el ciclo, ¿cómo es tu proceso para aprender una tecnología nueva?
 8. ¿Qué estructura de permisos aplicarías en Active Directory para el departamento de contabilidad?
 9. ¿Tienes experiencia con GitHub trabajando en equipo? ¿Cómo resuelves un conflicto de versiones?
10. ¿Por qué te interesa orientar tu carrera hacia la ciberseguridad y no solo a sistemas?

**Pregunta trampa para el CV optimizado con IA (Noa Vidal):**

11. *"En tu CV mencionas el diseño integral de una arquitectura con respuesta automatizada a incidentes en Azure. ¿Qué servicios específicos de Azure empleaste para los playbooks y cómo calculaste los costes de ingesta de logs en Microsoft Sentinel?"*

### Debate final

* **¿La candidatura con mayor puntuación ATS era la mejor?**
  No. El ATS puntúa coincidencias de texto. Noa Vidal sacó la máxima nota inyectando palabras clave y proyectos inventados por IA, pero cae en la fase humana/entrevista.

* **¿Qué información importante perdió el cribado automático?**
  A perfiles válidos pero mal redactados. Daniel es honesto y Hugo puede tener buenas habilidades, pero fueron eliminados por no usar el vocabulario literal que exige la máquina ("nivel intermedio" en vez de B1).

* **¿Qué diferencia hay entre nombrar una competencia y demostrarla?**
  Nombrarla es hacer una lista (Marcos). Demostrarla es contextualizarla en una experiencia o proyecto (Iria: *"Configuración de un entorno de aula para centralización de eventos"*).

* **¿Un CV visual es necesariamente peor para un ATS? ¿Qué parte de esta simulación simplifica la realidad?**
  Sí. Las columnas complejas, iconos y barras de progreso (como las de Hugo) impiden que el ATS extraiga el texto. La simulación simplifica la realidad porque los ATS actuales usan procesamiento de lenguaje natural y sí asocian ciertos sinónimos.

* **¿Es legítimo usar IA para adaptar un CV? ¿Dónde estaría el límite?**
  Es legítimo para mejorar la redacción, corregir ortografía y destacar experiencia real. El límite se cruza al inventar responsabilidades o inflar conocimientos que no se poseen.

* **¿Quién es responsable si una IA introduce una competencia o certificación falsa?**
  El candidato. El CV es un documento personal y profesional; es su responsabilidad revisar y poder defender cada palabra escrita en él.
