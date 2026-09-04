# 🏭 Portal del Empleado - Calculadora Salarial 6x2

Una aplicación web progresiva (PWA) diseñada para gestionar la rotación de turnos y calcular proyecciones salariales exactas para empleados bajo el esquema de trabajo 6x2 (6 días de trabajo, 2 de descanso). 

Desarrollada inicialmente para el personal de **Papelera Rosato S.A.**, esta herramienta automatiza la complejidad de la liquidación de sueldos industriales, brindando transparencia y control financiero al trabajador.

## ✨ Características Principales

* **🔄 Motor de Rotación 6x2:** Calcula automáticamente el ciclo continuo de turnos (Mañana, Tarde, Noche) y francos basándose en una fecha de inicio configurada por el usuario.
* **💰 Proyección Salarial Quincenal:** Estima el salario bruto y neto dividido en 1ra y 2da quincena, aplicando descuentos sindicales, viáticos, bonos por título y premios por presentismo.
* **⏱️ Gestión de Variables Diarias:** Permite imputar horas extras (diferenciando días normales y feriados), ausencias, llegadas tarde (con su respectiva lógica de penalización) y días feriados trabajados/no trabajados.
* **📊 Tesorería y Ranking:** Mantiene un historial de los meses calculados y genera un ranking personal de los períodos con mayores ingresos.
* **📄 Exportación PDF:** Genera comprobantes de liquidación detallados con la librería `jsPDF`, ideales para control personal o reclamos.
* **☁️ Sincronización en la Nube:** Autenticación mediante Google y almacenamiento de configuraciones e historial de meses utilizando Firebase Firestore. Incluye un "Modo Invitado" de uso efímero.
* **📸 Optimización de Imágenes:** Compresión automática de fotos de perfil mediante Canvas API y codificación Base64, almacenadas directamente en la base de datos para evitar costos de Storage.

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, Tailwind CSS (vía CDN), Vanilla JavaScript (ES Modules).
* **Backend / BaaS:** Firebase Authentication, Cloud Firestore.
* **Librerías Externas:** FontAwesome (Iconos), jsPDF & jsPDF-AutoTable (Generación de reportes).

## 🚀 Uso e Instalación

Dado que la aplicación está construida con Vanilla JS y módulos nativos, no requiere un proceso de *build* complejo (como Node.js o Webpack). 

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/calculadora-6x2.git](https://github.com/tu-usuario/calculadora-6x2.git)
