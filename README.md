# MetalStock-Analyzer

## 📋 Descripción del Proyecto
Sistema de información para predecir la demanda de productos en una tienda minorista del sector metalmecánico, con el objetivo de optimizar inventarios, reducir costos y mejorar la satisfacción del cliente.

## ⚙️ Requerimientos Funcionales

### 1. Sistema de Autenticación y Usuarios
- **RF1.1:** Implementar login con usuario y contraseña
- **RF1.2:** Gestionar al menos dos tipos de roles de usuario (por ejemplo, administrador y usuario regular)
- **RF1.3:** Permitir el registro de nuevos usuarios con aprobación de administrador
- **RF1.4:** Implementar cierre de sesión seguro
- **RF1.5:** Permitir la modificación de datos de usuario

### 2. Gestión de Datos Históricos
- **RF2.1:** Registrar y mantener un historial detallado de ventas con:
  - Fecha de venta
  - Producto vendido
  - Cantidad
  - Precio unitario
  - Cliente (si aplica)
- **RF2.2:** Calcular automáticamente métricas estadísticas:
  - Media de ventas por producto
  - Mediana de ventas por período
  - Moda en patrones de compra
  - Desviación estándar de ventas
- **RF2.3:** Identificar y registrar patrones de venta:
  - Tendencias por temporada
  - Productos más/menos vendidos
  - Relaciones entre productos (ventas conjuntas)

### 3. Análisis Predictivo
- **RF3.1:** Generar pronósticos de demanda utilizando modelos de series temporales
- **RF3.2:** Permitir la selección de diferentes períodos para el análisis (semanal, mensual, trimestral)
- **RF3.3:** Calcular niveles óptimos de inventario por producto
- **RF3.4:** Generar alertas automáticas cuando:
  - El stock está por debajo del nivel óptimo
  - Se detectan patrones inusuales de demanda
  - Se aproximan temporadas altas según histórico

### 4. Gestión de Factores Externos
- **RF4.1:** Registrar y actualizar información sobre:
  - Condiciones climáticas que afecten la demanda
  - Días festivos y eventos especiales
  - Campañas de marketing activas
  - Indicadores económicos relevantes
- **RF4.2:** Permitir la correlación de factores externos con patrones de demanda
- **RF4.3:** Capacidad de agregar/modificar/eliminar factores externos

### 5. Visualización y Reportes
- **RF5.1:** Generar gráficos de:
  - Tendencias de demanda
  - Comparativas de períodos
  - Proyecciones futuras
- **RF5.2:** Exportar reportes en formato PDF
- **RF5.3:** Dashboard con indicadores clave de rendimiento (KPIs)

## 🔧 Requerimientos No Funcionales

### 1. Tecnología y Desarrollo
- **RNF1.1:** Desarrollo completo en Java (JDK 17+)
- **RNF1.2:** Base de datos MySQL 8.0+
- **RNF1.3:** Sin uso de frameworks externos
- **RNF1.4:** Arquitectura MVC (Model-View-Controller)
- **RNF1.5:** Comentarios claros en el código
- **RNF1.6:** Control de versiones con Git

### 2. Interfaz de Usuario
- **RNF2.1:** GUI desarrollada con Java Swing
- **RNF2.2:** Tiempo de respuesta corto para operaciones regulares
- **RNF2.3:** Interfaz intuitiva con máximo 3 clics para acceder a cualquier funcionalidad
- **RNF2.4:** Mensajes de error claros y específicos
- **RNF2.5:** Validación en tiempo real de datos ingresados
- **RNF2.6:** Paleta de colores consistente y profesional

### 3. Seguridad
- **RNF3.1:** Registro de todas las operaciones críticas (log)
- **RNF3.2:** Timeout de sesión después de 15 minutos de inactividad
- **RNF3.3:** Control de acceso basado en roles

### 4. Rendimiento
- **RNF4.1:** Soporte para múltiples usuarios concurrentes
- **RNF4.2:** Optimización de consultas SQL

### 5. Portabilidad y Despliegue
- **RNF5.1:** Ejecutable en Windows 10/11
- **RNF5.2:** Script de instalación automatizado
- **RNF5.3:** No requerir privilegios de administrador para ejecutar

## 🛠️ Herramientas de Desarrollo
- Java JDK 17+
- MySQL 8.0+
- IDE recomendado: NetBeans/Eclipse/IntelliJ
- Git para control de versiones
- Para gestión de base de datos (Por definir)

## 📝 Guías de Desarrollo
1. Seguir estándares de codificación Java
2. Documentar todas las clases y métodos
3. Realizar reuniones para verificar el avance

## 🗓️ Fechas Importantes
- Entrega del informe: 27-11-2024 (sección 3D2) y 28-11-2024 (sección 3D1)
- Demo final: Según cronograma de actividades por sección
