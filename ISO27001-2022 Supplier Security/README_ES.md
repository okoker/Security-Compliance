# Autoevaluación de Ciberseguridad para Proveedores ISO 27001:2022

Una herramienta de evaluación HTML completa y autónoma para que los proveedores evalúen y documenten su nivel de madurez en ciberseguridad en línea con los estándares ISO 27001:2022.

## Descripción General

Esta herramienta permite a los proveedores completar una autoevaluación detallada de ciberseguridad que cubre 10 dominios de seguridad clave con 39 preguntas. La evaluación se guarda localmente como un archivo HTML que puede reabrirse, modificarse y compartirse por correo electrónico.

## Características Principales

- **Archivo HTML autónomo** - No requiere servidor, base de datos ni conexión a Internet
- **Seguimiento automático del progreso** - Barra de progreso visual que se actualiza al responder preguntas
- **Puntuación de madurez en tiempo real** - Cálculo instantáneo de puntuación basado en sus respuestas
- **Persistencia de respuestas** - Guarda las respuestas directamente en el archivo HTML al descargarlo
- **Reapertura y edición** - Puede reabrir y modificar respuestas antes del envío final
- **Soporte multilingüe** - Disponible en inglés, español, francés y alemán

## Guía Rápida para Proveedores

### Paso 1: Abrir la Evaluación
1. Descargue el archivo `supplier-cybersecurity-assessment.html`
2. Haga doble clic en el archivo para abrirlo en su navegador web
3. La evaluación se abrirá sin conexión - no se necesita conexión a Internet

### Paso 2: Completar la Información de la Empresa
Complete los campos requeridos en la parte superior:
- Nombre de la Empresa
- Persona de Contacto
- Dirección de Correo Electrónico
- Número de Teléfono
- Fecha de Evaluación (se completa automáticamente con la fecha actual)

### Paso 3: Responder las Preguntas de Seguridad
La evaluación cubre 10 dominios de seguridad:
1. Política y Gobernanza de Seguridad de la Información
2. Gestión de Activos
3. Control de Acceso
4. Protección de Datos
5. Seguridad Física y Ambiental
6. Seguridad de Operaciones
7. Seguridad de Red
8. Gestión de Incidentes
9. Continuidad del Negocio
10. Cumplimiento y Monitoreo

Para cada pregunta, seleccione su nivel de madurez:

| Nivel | Puntos | Descripción |
|-------|--------|-------------|
| **No Implementado** | 0 | Control no establecido |
| **Parcialmente Implementado** | 1 | Control parcialmente establecido, aplicación inconsistente |
| **Implementado** | 3 | Control establecido y aplicado consistentemente |
| **Completamente Maduro** | 5 | Control totalmente integrado, monitoreado y mejorado continuamente |
| **No Aplicable** | N/A | La pregunta no aplica a su organización |

### Paso 4: Seguir su Progreso
- La barra de progreso muestra el porcentaje de finalización (basado en preguntas respondidas)
- La puntuación se actualiza automáticamente al responder preguntas
- Vea su puntuación de madurez actual en tiempo real

### Paso 5: Guardar su Evaluación
1. Haga clic en el botón **"💾 Guardar Evaluación en Disco"** en la parte inferior
2. Su navegador descargará un archivo llamado: `security_assessment-[suempresa]-[fecha].html`
3. El archivo contiene todas sus respuestas y puede reabrirse más tarde

### Paso 6: Revisar o Modificar (Opcional)
1. Localice el archivo guardado en su carpeta de Descargas
2. Haga doble clic para reabrirlo en su navegador
3. Todas sus respuestas anteriores se mostrarán
4. Realice los cambios necesarios
5. Haga clic en **"💾 Guardar Evaluación en Disco"** nuevamente para guardar la versión actualizada
6. Nota: La fecha en el nombre del archivo se actualizará para reflejar cuándo lo guardó por última vez

### Paso 7: Enviar al Cliente
1. Envíe por correo electrónico el archivo HTML final guardado a su contacto del cliente
2. Pueden abrirlo en cualquier navegador para revisar sus respuestas
3. Su puntuación de madurez será visible en el documento

## Sistema de Puntuación

### Cálculo de Puntuación
- **Puntuación máxima posible:** 195 puntos (39 preguntas × 5 puntos cada una)
- **La puntuación es acumulativa:** Su puntuación total es la suma de todas las preguntas respondidas
- **Las respuestas "No Aplicable"** no contribuyen a la puntuación

### Niveles de Madurez

| Rango de Puntuación | Nivel de Madurez | Descripción |
|---------------------|------------------|-------------|
| **0** | Sin Evaluación | Evaluación no iniciada |
| **1-50** | Inicial | Se necesitan mejoras significativas |
| **51-100** | En Desarrollo | Prácticas de seguridad básicas establecidas |
| **101-150** | Definido | Buenas prácticas de seguridad establecidas |
| **151-195** | Optimizado | Prácticas de seguridad maduras |

## Detalles Técnicos

### Convención de Nomenclatura de Archivos
Los archivos guardados siguen este formato:
```
security_assessment-nombreempresa-AAAA-MM-DD.html
```
- El nombre de la empresa se trunca a un máximo de 12 caracteres
- La fecha se actualiza automáticamente cada vez que guarda
- Ejemplo: `security_assessment-miempresa-2025-11-05.html`

### Compatibilidad con Navegadores
- ✅ Chrome/Edge (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Todos los navegadores modernos

### Privacidad y Seguridad de Datos
- **No se transmiten datos** - Todo permanece en su computadora
- **Sin seguimiento** - Sin análisis ni conexiones externas
- **Completamente sin conexión** - Funciona sin Internet
- **Usted controla el archivo** - Usted decide cuándo y cómo compartirlo

## Soporte

Para preguntas o problemas:
- Verifique que está usando un navegador web moderno
- Asegúrese de que JavaScript esté habilitado en su navegador
- Verifique que tenga permiso para descargar archivos
- Intente abrir el archivo en un navegador diferente si ocurren problemas

## Licencia

Esta herramienta se proporciona tal cual para fines de evaluación de seguridad de proveedores.

---

**Versión:** 2.0  
**Última Actualización:** Noviembre 2025  
**Marco de Cumplimiento:** ISO 27001:2022
