# Business Model Canvas: Sistema de Gestión para Comerciantes Mayoristas de Frutas y Verduras (MVP)

**Versión:** 1.0 (MVP)
**Fecha:** 11 de noviembre de 2025
**Autor:** Business Strategist & Product Visionary

---

## 1. Problem Statement

Los comerciantes independientes de frutas y verduras que operan en el segmento mayorista en Latinoamérica enfrentan un problema de gestión operativa y financiera que impacta directamente su rentabilidad. Su modelo de negocio, basado en la confianza y en procesos manuales (cuadernos, calculadoras, memoria), es altamente vulnerable a errores y omisiones. La falta de digitalización les impide tener una visión clara de la salud de su negocio, resultando en pérdidas económicas significativas.

El núcleo del problema radica en tres áreas críticas: **control de inventario perecedero**, **gestión de cobranzas a crédito** y **cálculo de rentabilidad real**. Los comerciantes no pueden cuantificar con precisión cuánto producto pierden por deterioro (merma), lo que les impide optimizar sus compras. Además, el seguimiento de deudas de clientes es informal, llevando a olvidos que se traducen en pérdidas directas de ingresos. Finalmente, sin una herramienta que consolide costos, ventas y mermas por cada "carga" o lote de compra, es imposible para ellos saber qué productos son realmente rentables y cuáles generan pérdidas, forzándolos a tomar decisiones basadas en la intuición en lugar de en datos concretos.

## 2. MVP Hypothesis

Para validar la solución propuesta, el MVP se centrará en probar las siguientes hipótesis fundamentales:

1.  **Hipótesis de Rentabilidad:** Si proporcionamos a los comerciantes una herramienta para registrar los costos de cada carga de inventario y las ventas asociadas, podrán identificar la rentabilidad por producto y carga, permitiéndoles tomar decisiones de compra más informadas y aumentar su margen de ganancia en al menos un 5% en los primeros 3 meses.
2.  **Hipótesis de Cobranza:** Si la aplicación ofrece un sistema de seguimiento de deudas (créditos) y recordatorios de pago automáticos (vía WhatsApp), los comerciantes reducirán el tiempo promedio de cobro en un 30% y disminuirán las pérdidas por deudas olvidadas en al menos un 15%.
3.  **Hipótesis de Eficiencia y Adopción:** Si la herramienta digitaliza el registro de ventas e inventario de una forma simple e intuitiva (similar a usar una calculadora o WhatsApp), los comerciantes ahorrarán al menos 45 minutos diarios en tareas administrativas y considerarán que el valor aportado justifica un costo de suscripción mensual bajo.

---

## 3. Business Model Canvas (MVP)

| **8. Key Partners** | **7. Key Activities** | **2. Value Propositions** | **4. Customer Relationships** | **1. Customer Segments** |
| :--- | :--- | :--- | :--- | :--- |
| <ul><li>Asociaciones de comerciantes en centrales de abastos.</li><li>Proveedores de software de facturación (para futuras integraciones).</li><li>Proveedores de servicios de mensajería (WhatsApp API).</li><li>Influencers o líderes de opinión en la comunidad de comerciantes.</li></ul> | <ul><li>**Desarrollo y Mantenimiento:** Construcción y mejora continua de la aplicación móvil/web.</li><li>**Marketing y Ventas:** Campañas de adquisición en centrales de abastos y canales digitales.</li><li>**Soporte al Cliente:** Onboarding, resolución de dudas vía WhatsApp y tutoriales simples.</li><li>**Análisis de Datos:** Monitoreo de uso para validar hipótesis y guiar el desarrollo.</li></ul> | **Para el Comerciante MVP:**<br><ul><li>**Control Financiero Simple:** "Sepa exactamente cuánto gana por cada carga de aguacates que vende".</li><li>**Reducción de Pérdidas:** "Deje de perder dinero por olvidos en los cobros y por producto dañado".</li><li>**Ahorro de Tiempo:** "Dedique menos tiempo a los cuadernos y más tiempo a vender".</li></ul><br>**Features Clave del MVP:**<br>1. Registro de compras de inventario.<br>2. Registro de ventas (contado/crédito).<br>3. Estado de cuentas por cliente.<br>4. Reporte de rentabilidad por carga.<br>5. Registro de mermas. | <ul><li>**Auto-servicio:** El cliente gestiona todo desde la app.</li><li>**Soporte Asistido:** Canal de soporte directo vía WhatsApp para resolver dudas y recibir feedback.</li><li>**Comunidad:** Creación de grupos de WhatsApp/Facebook para compartir consejos y mejores prácticas entre usuarios.</li></ul> | **Segmento Principal:**<br>Comerciantes independientes de frutas y verduras al por mayor en Latinoamérica.<br><br>**Características:**<br><ul><li>Edad: 25-55 años.</li><li>Nivel tecnológico: Usuario habitual de smartphone y WhatsApp.</li><li>Operación: Compras en centrales de abastos 2-4 veces/semana.</li><li>Clientes: 10-30 clientes recurrentes.</li><li>Pain Points: No conocen su rentabilidad real, pierden dinero en cobros y mermas, el proceso manual es lento.</li></ul> |
| **6. Key Resources** | **3. Channels** |
| <ul><li>**Plataforma Tecnológica:** Aplicación móvil (Android primero) y/o PWA.</li><li>**Equipo de Desarrollo:** Ingenieros de software y diseñador UX/UI.</li><li>**Capital Intelectual:** Conocimiento del dominio (modelo de negocio de los comerciantes).</li><li>**Capital Financiero:** Inversión inicial para desarrollo y marketing (Bootstrap/Seed).</li></ul> | <ul><li>**Directo / Físico:** Promotores en las principales centrales de abastos (volantes, demos en vivo).</li><li>**Digital:** Publicidad segmentada en Facebook e Instagram. Grupos de WhatsApp y Facebook de comerciantes.</li><li>**Referidos:** Programa "invita a un colega y gana un mes gratis".</li></ul> |
| **9. Cost Structure** | **5. Revenue Streams** |
| <ul><li>**Costos de Desarrollo:** Salarios del equipo de tecnología (principal costo).</li><li>**Costos de Infraestructura:** Servidores en la nube (AWS, Firebase), bases de datos, APIs de terceros (ej. WhatsApp).</li><li>**Costos de Adquisición de Clientes (CAC):** Salarios de promotores, presupuesto para marketing digital.</li><li>**Costos Operativos:** Soporte al cliente.</li></ul> | **Modelo Freemium con Suscripción (para el MVP):**<br><ul><li>**Plan Gratuito (Free):** Funcionalidad limitada. Ej: hasta 20 clientes y 5 reportes al mes. Diseñado para que prueben el valor principal.</li><li>**Plan Pro (Suscripción):** Funcionalidad completa e ilimitada por una tarifa mensual baja (ej. $5 - $10 USD/mes).<br><br>*Se ofrecerá un periodo de prueba gratuito (Free Trial) de 30 días del Plan Pro.*</li></ul> |
