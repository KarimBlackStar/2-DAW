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

---

## HOJA DE CRIBADO COMPLETADA

**Evaluador:** Sistema ATS + Equipo de Selección CYBERGAL

| Candidato | Puntuación ATS | ¿Pasa de fase? | Fortaleza principal | Alerta / duda | 
 | ----- | ----- | ----- | ----- | ----- | 
| **Daniel Varela** | 29 | ❌ NO | CV muy sincero y honesto. | CV genérico. No usa las palabras clave exactas de la oferta; el ATS no detecta sus conocimientos. | 
| **Laura Souto** | 83 | ✅ SÍ | Coherencia total entre lo que sabe y cómo lo demuestra (laboratorio en casa). | Ninguna alerta grave. Perfil muy sólido para un puesto Junior. | 
| **Hugo Costa** | 28 | ❌ NO | Formato atractivo visualmente. | El ATS no lee las "estrellitas" ni traduce el inglés ("Team player"). Cae en el filtro automático. | 
| **Marcos Rey** | 76 | ✅ SÍ | Supera el umbral por nombrar todas las tecnologías. | *Keyword stuffing*: lista tecnologías avanzadas pero su experiencia es instalando ordenadores e impresoras. | 
| **Iria Barreiro** | 77 | ✅ SÍ | Demuestra competencias a través de proyectos de aula muy bien explicados. | Ninguna alerta. Perfil muy bien adaptado y realista. | 
| **Noa Vidal** | 94 | ✅ SÍ | Puntuación ATS perfecta, encaja al 100% con los requisitos. | Alerta roja humana: usó IA y el proyecto descrito es irreal y demasiado avanzado para su nivel. | 

* **Tres candidaturas seleccionadas por RR. HH.:** 1) Laura Souto 2) Iria Barreiro 3) Noa Vidal
*(RR. HH. descarta a Marcos al revisar manualmente su CV y ver que es solo una lista de palabras clave sin experiencia coherente que la respalde).*

* **Dos candidaturas seleccionadas por el responsable IT:** 1) Laura Souto 2) Iria Barreiro

**Justificación del evaluador (Responsable IT):**
Seleccionamos a Laura e Iria porque sus currículums son coherentes. Laura tiene un laboratorio doméstico que demuestra su interés real, e Iria detalla proyectos de clase (como su laboratorio SIEM) que encajan perfectamente con lo que necesitamos. Descartamos a Noa porque, aunque el ATS le dio la nota más alta, su afirmación de haber diseñado una "arquitectura integral de ciberseguridad con respuesta automatizada en Azure" durante unas prácticas de FP es totalmente irreal y fruto de alucinar con la IA. Marcos fue descartado porque nombrar tecnologías sin haberlas usado en contexto no aporta valor real.

---

## FASE 4 · MINI ENTREVISTA

### Preguntas comunes para finalistas (Laura e Iria)

1. Has mencionado que tienes laboratorios/proyectos en casa o en clase. ¿Puedes explicarme cómo montaste la red y qué hypervisor usaste?
2. Si un usuario reporta que no puede acceder a una carpeta compartida en el servidor Windows, ¿cuáles son los pasos exactos que sigues para diagnosticarlo?
3. ¿Cómo configurarías una regla de firewall básica para permitir tráfico web pero bloquear ping (ICMP)?
4. ¿Qué información buscas primero cuando revisas los logs en un sistema de monitorización o SIEM?
5. ¿Qué comando en Linux usarías para ver tu IP actual y cuál para comprobar si hay conexión con el servidor DNS?
6. Háblame de alguna incidencia técnica que te haya costado resolver en tus prácticas o proyectos y cómo la solucionaste.
7. En esta empresa usamos herramientas que no has visto en el ciclo, ¿cómo es tu proceso para aprender una tecnología nueva desde cero?
8. ¿Qué estructura de permisos aplicarías en Active Directory para un departamento de contabilidad?
9. ¿Tienes experiencia gestionando repositorios en GitHub trabajando con otras personas? ¿Cómo resuelves un conflicto en el código o en la documentación?
10. ¿Por qué te interesa orientar tu carrera hacia la ciberseguridad y no solo a sistemas puros?

**Pregunta trampa para el CV optimizado con IA (Noa Vidal):**

11. *"En tu CV mencionas el diseño integral de una arquitectura con respuesta automatizada a incidentes en Azure. ¿Podrías detallarme qué servicios específicos de Azure empleaste para los playbooks de automatización y cómo calculasteis los costes de ingesta de logs en Microsoft Sentinel?"* (Esta pregunta técnica avanzada desmontaría rápidamente un proyecto exagerado por IA).

---

### Debate final

* **¿La candidatura con mayor puntuación ATS era la mejor?**
  No. Noa Vidal sacó la máxima nota porque la IA inyectó todas las palabras clave y redactó proyectos a medida, pero carecía de la experiencia real para sostenerlo en una entrevista.

* **¿Qué información importante perdió el cribado automático?**
  Perdió la honestidad y proyectos base de Daniel, y la capacidad de resolución (soft skills) que sugería el perfil de Hugo. Ambos podrían ser excelentes trabajadores, pero fueron eliminados simplemente por no saber "jugar al juego" del algoritmo o usar formatos incompatibles.

* **¿Qué diferencia hay entre nombrar una competencia y demostrarla?**
  Nombrarla (como hizo Marcos) es poner "Docker" o "SIEM" en una lista al azar; el ATS te puntúa, pero el humano desconfía. Demostrarla (como hizo Iria) es contextualizarla: *"Configuración de un entorno de aula para centralización de eventos de seguridad (SIEM)"*.

* **¿Un CV visual es necesariamente peor para un ATS? ¿Qué parte de esta simulación simplifica la realidad?**
  Generalmente sí, si abusa de gráficos. Elementos como barras de progreso (las estrellas de Hugo), columnas complejas o texto incrustado en imágenes suelen romper el análisis (*parsing*) del ATS. 
  La simulación simplifica la realidad porque los ATS modernos tienen procesamiento de lenguaje natural (NLP) y son capaces de entender sinónimos (sabrían que "Networking" equivale a "Redes"). Además, rara vez el corte es 100% automático sin que un humano dé un vistazo rápido a los descartados.

* **¿Es legítimo usar IA para adaptar un CV? ¿Dónde estaría el límite?**
  Es completamente legítimo usar IA para mejorar la redacción, corregir faltas de ortografía, estructurar la información y resaltar aspectos de tu experiencia real que encajan mejor con la oferta. El límite se cruza cuando la IA inventa responsabilidades, aumenta el nivel de conocimientos reales o crea proyectos ficticios.

* **¿Quién es responsable si una IA introduce una competencia o certificación falsa?**
  El 100% de la responsabilidad es del candidato. El CV es un documento profesional que lleva su nombre y es su deber revisar, validar y poder defender cada palabra escrita en él antes de enviarlo.
