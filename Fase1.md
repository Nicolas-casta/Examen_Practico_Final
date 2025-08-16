# Participantes: Nicolas Castaño Diosa y Juan Miguel Sanchez

# Análisis y Toma de Requerimientos: Aplicación de Finanzas Personales

## Tarea 1.1: Investigación de Usuario y Análisis Competitivo

### Hallazgos de Investigación

Los jóvenes profesionales entre 22-35 años representan un segmento demográfico con necesidades financieras específicas y crecientes. Esta población está experimentando transiciones importantes en sus vidas: primer empleo formal, independencia económica, primeras inversiones significativas y posiblemente la formación de un hogar. Sin embargo, muchos carecen de educación financiera sólida y enfrentan un entorno económico desafiante.

La investigación muestra que este grupo valora la simplicidad, la experiencia digital fluida y las soluciones que se integran fácilmente en su estilo de vida. Buscan herramientas que no solo les ayuden a administrar su dinero, sino que también les eduquen y motiven a desarrollar hábitos financieros saludables. La gamificación y los elementos sociales son particularmente atractivos para este segmento.

La pandemia ha acelerado la adopción de herramientas financieras digitales, y existe una creciente preocupación por la seguridad de los datos financieros. Los usuarios buscan aplicaciones que ofrezcan un equilibrio entre funcionalidad, seguridad y facilidad de uso, con una preferencia por interfaces intuitivas que no requieran conocimientos financieros avanzados.

### Análisis de Competidores

#### 1. Mint

**Fortalezas:**
- Integración completa con múltiples cuentas bancarias y tarjetas de crédito
- Categorización automática de gastos con alta precisión
- Alertas personalizables para pagos y presupuestos
- Interfaz limpia y fácil de navegar

**Debilidades:**
- Limitada disponibilidad internacional
- Funcionalidades de inversión básicas
- Modelo de monetización basado en publicidad que puede resultar intrusivo
- Escasos elementos de gamificación

#### 2. YNAB (You Need A Budget)

**Fortalezas:**
- Metodología de presupuesto probada y efectiva
- Enfoque educativo sólido sobre finanzas personales
- Comunidad activa de usuarios
- Reportes detallados y personalizables

**Debilidades:**
- Curva de aprendizaje pronunciada
- Precio de suscripción relativamente alto
- Sincronización bancaria limitada en algunos países
- Interfaz menos atractiva visualmente

#### 3. Fintonic

**Fortalezas:**
- Fuerte enfoque en el análisis predictivo de gastos
- Recomendaciones personalizadas de productos financieros
- Buena integración con el sistema bancario local
- Alertas de cargos duplicados o sospechosos

**Debilidades:**
- Menor enfoque en objetivos de ahorro a largo plazo
- Limitada funcionalidad sin conexión
- Elementos de gamificación poco desarrollados
- Interfaz ocasionalmente sobrecargada de información

### Necesidades Clave del Usuario

1. **Visibilidad financiera completa**: Necesidad de ver todas sus cuentas, gastos e ingresos en un solo lugar con categorización automática e inteligente.

2. **Planificación de objetivos financieros**: Capacidad para establecer metas de ahorro específicas (viajes, fondo de emergencia, entrada para vivienda) con seguimiento visual del progreso.

3. **Educación financiera contextual**: Acceso a consejos y educación financiera relevante según su situación particular y momento de vida.

4. **Motivación para hábitos financieros saludables**: Elementos que incentiven y recompensen comportamientos financieros positivos.

5. **Seguridad y privacidad**: Garantía de que sus datos financieros están protegidos con los más altos estándares de seguridad.

6. **Simplicidad y bajo esfuerzo**: Interfaces intuitivas que no requieran conocimientos financieros avanzados ni dedicación excesiva de tiempo.

7. **Insights personalizados**: Análisis de patrones de gasto con recomendaciones accionables y personalizadas.

## Tarea 1.2: Definición de Requerimientos Funcionales y No Funcionales

### Requerimientos Funcionales

1. El sistema debe permitir la conexión segura con múltiples cuentas bancarias y tarjetas de crédito.
2. El sistema debe categorizar automáticamente las transacciones con capacidad de reclasificación manual.
3. El sistema debe permitir la creación y seguimiento de objetivos de ahorro con fechas límite y montos específicos.
4. El sistema debe generar reportes visuales de gastos e ingresos por categoría, tiempo y comercio.
5. El sistema debe enviar notificaciones personalizables sobre actividades inusuales, pagos próximos y logros de objetivos.
6. El sistema debe ofrecer un módulo de presupuesto mensual con alertas de exceso de gasto.
7. El sistema debe proporcionar recomendaciones personalizadas basadas en patrones de gasto e ingresos.
8. El sistema debe incluir un sistema de gamificación con logros, desafíos y recompensas virtuales.
9. El sistema debe permitir la captura manual de gastos en efectivo con opción de fotografía de recibos.
10. El sistema debe ofrecer proyecciones financieras basadas en comportamientos históricos.
11. El sistema debe permitir la exportación de datos en formatos estándar (CSV, PDF).
12. El sistema debe incluir un módulo educativo con contenido adaptado al perfil financiero del usuario.

### Requerimientos No Funcionales

1. **Seguridad**: El sistema debe cumplir con estándares de seguridad financiera (cifrado de extremo a extremo, autenticación de dos factores).
2. **Rendimiento**: La aplicación debe cargar en menos de 3 segundos y responder a interacciones en menos de 1 segundo.
3. **Usabilidad**: La interfaz debe ser intuitiva y accesible para usuarios sin conocimientos financieros avanzados.
4. **Disponibilidad**: El sistema debe estar disponible el 99.9% del tiempo, con mantenimientos programados fuera de horas pico.
5. **Escalabilidad**: La plataforma debe soportar hasta 1 millón de usuarios concurrentes sin degradación del servicio.
6. **Privacidad**: El sistema debe cumplir con regulaciones de protección de datos (GDPR, CCPA) y ofrecer controles de privacidad granulares.
7. **Compatibilidad**: La aplicación debe funcionar en iOS 12+ y Android 8.0+, optimizada para diferentes tamaños de pantalla.
8. **Accesibilidad**: La interfaz debe cumplir con estándares WCAG 2.1 nivel AA para usuarios con discapacidades.

### User Stories

1. **Como** joven profesional, **quiero** conectar todas mis cuentas bancarias a la aplicación, **para** tener una visión unificada de mis finanzas sin tener que revisar múltiples plataformas.
   - **Criterios de aceptación**: Soporte para al menos 20 bancos principales, proceso de conexión en menos de 3 pasos, actualización de transacciones cada 24 horas como mínimo.

2. **Como** usuario con múltiples gastos, **quiero** que mis transacciones se categoricen automáticamente, **para** entender fácilmente en qué gasto mi dinero sin esfuerzo manual.
   - **Criterios de aceptación**: Precisión de categorización superior al 85%, opción de corregir categorías incorrectas, aprendizaje de preferencias de categorización.

3. **Como** ahorrador principiante, **quiero** establecer objetivos de ahorro visuales con fechas límite, **para** motivarme a alcanzar metas financieras específicas.
   - **Criterios de aceptación**: Creación de objetivos con imágenes personalizadas, seguimiento de progreso visual, sugerencias de montos de ahorro basados en ingresos.

4. **Como** usuario preocupado por la seguridad, **quiero** que mis datos financieros estén protegidos con los más altos estándares, **para** usar la aplicación sin preocupaciones sobre mi privacidad.
   - **Criterios de aceptación**: Cifrado de datos en reposo y en tránsito, autenticación biométrica, opción de bloqueo con PIN, cumplimiento con estándares de seguridad financiera.

5. **Como** usuario visual, **quiero** ver gráficos y visualizaciones claras de mis patrones de gasto, **para** identificar áreas de mejora en mis finanzas personales.
   - **Criterios de aceptación**: Al menos 5 tipos diferentes de visualizaciones, filtros por período y categoría, comparativas con meses anteriores.

6. **Como** usuario que busca mejorar, **quiero** recibir consejos personalizados basados en mis hábitos financieros, **para** tomar mejores decisiones con mi dinero.
   - **Criterios de aceptación**: Al menos 3 recomendaciones semanales personalizadas, consejos accionables y específicos, opción de marcar consejos como útiles o no útiles.

7. **Como** usuario motivado por logros, **quiero** un sistema de gamificación que me recompense por buenos hábitos financieros, **para** mantenerme comprometido con mi salud financiera.
   - **Criterios de aceptación**: Sistema de puntos y niveles, desafíos semanales, logros desbloqueables, comparación anónima con otros usuarios similares.

8. **Como** usuario ocupado, **quiero** poder registrar gastos en efectivo rápidamente, **para** mantener un registro completo de mis finanzas incluso cuando no uso métodos de pago electrónicos.
   - **Criterios de aceptación**: Registro de gastos en menos de 3 toques, escaneo de recibos con OCR, sugerencias inteligentes basadas en ubicación y patrones previos.

9. **Como** planificador financiero, **quiero** establecer presupuestos por categorías, **para** controlar mis gastos en áreas específicas y recibir alertas cuando me acerque a los límites.
   - **Criterios de aceptación**: Presupuestos personalizables por categoría, alertas configurables (80%, 90%, 100%), ajustes automáticos basados en patrones históricos.

10. **Como** usuario que aprende, **quiero** acceder a contenido educativo sobre finanzas personales, **para** mejorar mis conocimientos financieros mientras uso la aplicación.
    - **Criterios de aceptación**: Biblioteca de contenido categorizado por nivel y tema, recomendaciones basadas en comportamiento financiero, formato multimedia (texto, video, infografías).

### Matriz de Priorización MoSCoW

#### Must Have (Debe tener)
- Conexión segura con cuentas bancarias y tarjetas
- Categorización automática de transacciones
- Visualización básica de gastos e ingresos
- Altos estándares de seguridad y privacidad
- Creación y seguimiento de objetivos de ahorro
- Notificaciones de actividades importantes

#### Should Have (Debería tener)
- Sistema de presupuesto por categorías
- Registro manual de gastos en efectivo
- Recomendaciones personalizadas básicas
- Exportación de datos financieros
- Interfaz optimizada para diferentes dispositivos móviles

#### Could Have (Podría tener)
- Sistema de gamificación completo
- Módulo educativo extenso
- Proyecciones financieras avanzadas
- Escaneo de recibos con OCR
- Comparativas sociales anónimas

#### Won't Have (No tendrá en esta versión)
- Asesoramiento financiero profesional personalizado
- Marketplace de productos financieros
- Funcionalidades de inversión avanzadas
- Integración con criptomonedas
- Gestión de impuestos

## Tarea 1.3: Documentación IEEE 830 Básica

# Especificación de Requisitos de Software
## Aplicación de Finanzas Personales para Jóvenes Profesionales

### 1. Introducción

#### 1.1 Propósito
Este documento tiene como objetivo definir los requisitos funcionales y no funcionales para el desarrollo de una aplicación móvil de finanzas personales dirigida a jóvenes profesionales entre 22 y 35 años. El documento servirá como base para el diseño, desarrollo y evaluación del sistema.

#### 1.2 Ámbito del Sistema
La aplicación, denominada provisionalmente "FinSmart", permitirá a los usuarios gestionar sus finanzas personales de manera integral, facilitando el seguimiento de gastos e ingresos, la creación y monitoreo de objetivos de ahorro, y el análisis de patrones financieros. El sistema incluirá elementos de gamificación para fomentar hábitos financieros saludables y proporcionará educación financiera contextual.

#### 1.3 Definiciones, Acrónimos y Abreviaturas
- **API**: Application Programming Interface
- **OCR**: Optical Character Recognition
- **2FA**: Two-Factor Authentication
- **GDPR**: General Data Protection Regulation
- **CCPA**: California Consumer Privacy Act
- **WCAG**: Web Content Accessibility Guidelines

### 2. Descripción General

#### 2.1 Perspectiva del Producto
FinSmart será una aplicación móvil independiente que se integrará con sistemas bancarios existentes a través de APIs seguras. La aplicación funcionará en dispositivos iOS y Android, con una arquitectura cliente-servidor que garantice la seguridad de los datos financieros de los usuarios.

#### 2.2 Funciones del Producto
Las principales funciones de FinSmart incluyen:
- Integración con cuentas bancarias y tarjetas de crédito
- Seguimiento y categorización de gastos e ingresos
- Establecimiento y monitoreo de objetivos de ahorro
- Análisis de patrones financieros con insights personalizados
- Sistema de gamificación para fomentar hábitos financieros saludables
- Módulo educativo adaptado al perfil financiero del usuario

#### 2.3 Características de los Usuarios
Los usuarios principales serán jóvenes profesionales entre 22 y 35 años con las siguientes características:
- Familiaridad básica a intermedia con tecnología móvil
- Diversos niveles de alfabetización financiera
- Ingresos regulares pero posiblemente limitados
- Objetivos financieros en desarrollo (ahorro para vivienda, viajes, educación, etc.)
- Preferencia por soluciones digitales integradas en su estilo de vida

#### 2.4 Restricciones
- La aplicación debe cumplir con regulaciones financieras y de protección de datos aplicables
- El sistema debe funcionar en dispositivos móviles con iOS 12+ y Android 8.0+
- La integración bancaria dependerá de las APIs disponibles de cada institución financiera
- El rendimiento debe mantenerse óptimo incluso con conexiones de internet limitadas

#### 2.5 Suposiciones y Dependencias
- Se asume que los usuarios tendrán acceso a internet de forma regular
- Se depende de la disponibilidad y estabilidad de las APIs de instituciones financieras
- Se asume que los usuarios estarán dispuestos a compartir sus datos financieros a cambio de valor añadido

### 3. Requisitos Específicos

#### 3.1 Interfaces Externas

##### 3.1.1 Interfaces de Usuario
- Interfaz móvil optimizada para uso frecuente y rápido
- Diseño adaptable a diferentes tamaños de pantalla
- Soporte para modo oscuro y claro
- Cumplimiento con estándares de accesibilidad WCAG 2.1 nivel AA

##### 3.1.2 Interfaces de Hardware
- Compatibilidad con sensores biométricos para autenticación
- Acceso a cámara para escaneo de recibos
- Optimización para diferentes resoluciones de pantalla

##### 3.1.3 Interfaces de Software
- APIs para integración con instituciones financieras
- Integración con sistemas de notificaciones del dispositivo
- Compatibilidad con servicios de almacenamiento en la nube para respaldos

