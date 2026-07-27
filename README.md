*Plantilla de tu Proyecto: Edita esta plantilla usando el ícono del lápiz y coloca la información de tu grupo.*


# Proyecto de Diseño Biomédico 2

**Integrantes del Equipo:**
*   Estudiante 1
*   Estudiante 2
*   Estudiante 3
*   ...

**Nombre del Proyecto:** [Escribir aquí el nombre]
**Stakeholder/Cliente:** [Nombre de la empresa, institución o usuario]

---

## ⚠️ Instrucciones de Gestión (LEER OBLIGATORIAMENTE)
<details> <summary> Click aquí para expandir </summary>
   
Para la evaluación de este curso, utilizamos la metodología **"Si no está en el Issue, no existe"**.

Este curso evalúa desempeño **individual** dentro del equipo. Este repositorio se creó a
partir del usuario de GitHub que cada integrante reportó a su profesor el día de la
conformación de grupos — ese usuario es tu identidad de trabajo aquí, y todo lo que subas
queda registrado con él. Haz tus propios commits, con tu propia cuenta: no subas evidencia
de un compañero "de favor" con tu usuario, porque le quitas la trazabilidad de su trabajo.
Si cambiaste de usuario de GitHub después de esa clase, avísale a tu profesor para que
ajuste tu invitación.

### 1. Configuración Inicial (Semana 1)
1.  Vayan a la pestaña **Projects** de este repositorio.
2.  Creen un **New Project** y seleccionen la vista **Table**.
3.  Vayan a la pestaña **Issues** -> **Milestones** y creen 3 hitos:
    *   `Semana 5 - Diseño Conceptual`
    *   `Semana 11 - Pruebas y Validación`
    *   `Semana 17 - Entrega Final`
4.  Carguen todas sus tareas en el Project Board, asignen un **Responsable** y una **Fecha**.

### 2. Cómo entregar tareas
El profesor **NO revisará** carpetas al azar buscando archivos. El profesor revisará el **Project Board**.
*   Cada tarea completada debe tener un **Issue cerrado**.
*   Para cerrar un Issue válidamente, deben vincular la evidencia:
    *   **Si es código/diseño:** En el commit message usen `fixes #numero_issue`.
    *   **Si es documento/foto:** Arrastren el archivo dentro del comentario del Issue y ciérrenlo.

### 3. Formato de la documentación: Markdown, no binarios
Como la evaluación es individual, la documentación de equipo (informes, actas, matrices de
selección, bitácoras, justificación ingenieril) se escribe en archivos de texto **Markdown
(`.md`)** dentro del repositorio — **no** en Word, Google Docs ni OneDrive compartido.
*   **¿Por qué?** Un `.md` editado y comiteado por cada persona deja un historial claro de
    quién escribió qué y cuándo. Un documento compartido en Drive/OneDrive NO tiene esa
    trazabilidad: para la evaluación individual, ese trabajo "no existe" aunque el equipo sí
    lo haya hecho.
*   Pueden usar Google Docs para lluvia de ideas o borradores rápidos, pero el entregable
    final que se evalúa debe quedar como `.md` en el repositorio.
*   Esta restricción aplica solo a la **redacción colaborativa de documentos**. Los archivos
    binarios (CAD, esquemáticos, PCB, simulaciones, fotos, video) sí se suben tal cual, en las
    carpetas de `03_Ingenieria_Tecnica` y `04_Multimedia_Prototipo` descritas abajo.
*   Para insertar una imagen dentro de un `.md` (ej. una foto de avance o un boceto), arrástrala
    directamente al editor de texto de GitHub — se sube sola y queda enlazada en el archivo.

### 4. Trabajar juntos en videollamada (sin perder la autoría)
Si están acostumbrados a abrir un documento de Google Docs/OneDrive en videollamada y
construirlo hablando entre todos, pueden lograr lo mismo con `.md` así:
*   **Dividan el documento por secciones o por archivos, cada uno con un dueño.** Ej.:
    `estado_del_arte.md` lo escribe una persona, `requerimientos.md` otra. En la llamada
    discuten y construyen el contenido juntos en tiempo real, pero cada quien escribe y
    comitea su propia parte desde su propio computador.
*   Así la conversación es simultánea (como en Drive), pero cada commit sigue siendo 100%
    de una sola persona — sin eso, la evaluación individual no se puede sostener.
*   Existen herramientas de edición simultánea "estilo Google Docs" para código (ej. VS Code
    Live Share), pero las descartamos para este curso: por defecto todo el texto tecleado en
    la sesión termina comiteado a nombre de quien controla la sesión, así que no resuelven el
    problema de trazabilidad individual sin disciplina extra — más complejidad sin beneficio
    real sobre la opción de "sección con dueño".

---

## 📂 Estructura del Repositorio (Design History File)

Este repositorio organiza el proyecto separando la evidencia documental de los archivos técnicos de ingeniería.

*   **/01_Gestion_del_Proyecto**: Cronograma, Presupuesto, Licencias, Cartas de intención, Acuerdos legales,...

*   **/02_DHF_Proceso_Diseno**: **DOCUMENTACIÓN (INFORMES Y EVIDENCIA)**
    *   *Fase_1_Investigacion*: Definición de requerimientos, normas y estado del arte, etc
    *   *Fase_2_Conceptual*: Matrices de selección, bocetos y definición de arquitectura, etc
    *   *Fase_3_Diseno_Detalle*: **Justificación ingenieril.** Aquí van los informes de cálculos, resultados de simulaciones, BOM final y especificaciones técnicas.
    *   *Fase_4_Validacion*: Protocolos de pruebas, resultados de validación con usuarios, análisis estadístico, etc

*   **/03_Ingenieria_Tecnica**: **ARCHIVOS FUENTE EDITABLES (HERRAMIENTAS)**
    *   *Calculos_Simulaciones*: Archivos de Excel, Scripts (MATLAB/Python), Simulaciones (Ansys/Proteus), simulaciones de SolidWorks, etc.
    *   *Mecanica_CAD*: Archivos nativos de modelado 3D y planos de fabricación.
    *   *Electronica*: Esquemáticos, diseño de PCB (Gerbers) y listas de materiales.
    *   *Software_Firmware*: Código fuente documentado.

*   **/04_Multimedia_Prototipo**: **MATERIAL DE DIVULGACIÓN.**
    *   Fotos de alta calidad del prototipo final.
    *   Video de funcionamiento (Demo) para la presentación final.
    *   Renders comerciales o material para el Póster/Pitch.

*   **/05_Reporte_Final_ABET**: 
    *   Aquí se entregará el documento final compilado ("Capstone Project") siguiendo la plantilla institucional.
    *   Este documento debe alimentarse de la información generada en la carpeta `02_DHF`.

</details>

---

## 📝 Resumen del Problema
*(Editar esta sección en la Semana 2)*
Describa brevemente en 1 párrafo cuál es la necesidad clínica o problema que están resolviendo.
