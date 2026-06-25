
# Laboratorio Virtual: Simulador de Saturación Dinámica de Infraestructura DevOps — UNAMAD

## 👥 Integrantes
* Panique Puma Patrich Robinho
* Santiago Condori Jhon Joel
* Vasquez Mego Moises

---

## 1. Selección de la Problemática Informática Real (Semana 1)
Durante los procesos de matrícula masiva en la UNAMAD, la infraestructura de software institucional experimenta un incremento exponencial de tráfico masivo por usuarios concurrentes. Este flujo de peticiones HTTP legítimas supera la capacidad nominal de procesamiento del clúster de servidores.

Esta sobrecarga provoca que las solicitudes queden retenidas en buffers de memoria interna, estructurando una **cola de solicitudes bloqueadas**. Al degradarse el sistema, el software de monitoreo automatizado inunda las pantallas del equipo de ingenieros de operaciones con un flujo masivo de alertas de emergencia por minuto. El equipo técnico debe intervenir directamente modificando código o scripts en vivo para levantar servidores virtuales, liberar memoria y apagar funciones secundarias. 

Sin embargo, la persistencia temporal de la crisis activa un comportamiento no lineal crítico: la **Fatiga de Alertas**. El exceso de estímulos visuales y sonoros degrada la capacidad cognitiva de los ingenieros, acumulando estrés informático. A medida que los operadores se fatigan, se vuelven significativamente más lentos para programar y desplegar los parches de infraestructura necesarios, generando un bucle donde la propia saturación del software ralentiza la capacidad humana de repararlo.

---

##  2. Análisis CATWOE Completo (Semana 2 - Hito 1)
* **C (Clientes):** Usuarios académicos y administrativos de la UNAMAD que experimentan la degradación o pérdida de disponibilidad de los servicios web durante el proceso de matrícula.
* **A (Actores):** Ingenieros de operaciones DevOps y Site Reliability Engineering (SRE) encargados de monitorear e intervenir el clúster a través de scripts de mitigación y parches de infraestructura.
* **T (Transformación):** * *Input:* Peticiones HTTP retenidas en cola de memoria y ráfagas estocásticas de alertas de error en buffers de monitoreo.
  * *Output:* Parches de código estables desplegados, clúster optimizado y cola de solicitudes totalmente procesada/liberada.
* **W (Weltanschauung):** Creencia matriz de que la continuidad y estabilidad de la gobernanza digital exige una gestión de despacho elástica que equilibre la capacidad operativa y la salud cognitiva del equipo técnico ante crisis informáticas.
* **O (Dueños):** Jefatura de la Oficina de Tecnologías de la Información (OTI), Dirección General de Administración y Rectorado de la UNAMAD.
* **E (Restricciones del Entorno):** Techo presupuestal anual inalterable asignado por el Ministerio de Economía y Finanzas (MEF) y las limitaciones asintóticas de ancho de banda y latencia física de la infraestructura de conectividad en la región.

---

##  3. Definición Raíz que Justifica el Software
Un sistema para la gestión y mitigación de incidentes críticos en la infraestructura de producción, propiedad de la Jefatura de la OTI, Dirección General de Administración y el Rectorado [O], operado por el equipo de ingenieros DevOps y SRE [A], que transforma las alertas de fallas de software acumuladas en el buffer en parches de código estables y servicios restablecidos [T], con el fin de garantizar la alta disponibilidad y la continuidad de las plataformas académicas y administrativas para la comunidad universitaria [C]; bajo la perspectiva de que la gobernanza digital universitaria exige un despacho elástico que equilibre la eficiencia del gasto público y la capacidad operativa ante crisis [W]; limitado estrictamente por el techo presupuestal asignado por el MEF y las restricciones físicas de conectividad de la región [E].