# RetoSoftkaPerformance
Acá encontraras el reto de perfomance para mas info leer README


Título del Proyecto
Reto performance 

Comenzando 🚀
Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

# 🚀 Proyecto de Pruebas de Performance

Este proyecto tiene como objetivo evaluar el **rendimiento, escalabilidad y estabilidad** de los servicios y aplicaciones bajo diferentes cargas de trabajo.  
Se busca identificar cuellos de botella, límites de capacidad y métricas clave de desempeño.

---

## 🧩 Objetivos

- Medir el tiempo de respuesta de los endpoints principales.
- Evaluar la capacidad de concurrencia del sistema.
- Analizar el comportamiento bajo estrés y carga sostenida.
- Identificar degradaciones de rendimiento o errores en picos de tráfico.

---

## ⚙️ Herramientas Utilizadas

| Herramienta | Descripción |
|--------------|-------------|
| **JMeter / k6 / Gatling** | Motor principal de pruebas de carga y estrés. |


---

#▶️ Cómo Ejecutar el Proyecto

Abrir Apache JMeter y cargar el archivo .jmx correspondiente al plan de pruebas.
Verificar que el archivo CSV esté ubicado correctamente y que las variables estén bien definidas.
Configurar el número de hilos (usuarios virtuales), ramp-up y duración en el componente Thread Group.
Iniciar la ejecución con el botón Start o presionando Ctrl + R.
Observar los resultados en tiempo real a través de los listeners:
Ver Árbol de Resultados
Informe Agregado
Tabla de Resultados
Gráficos de rendimiento

---



🧪 Estructura del Plan de Pruebas
El plan de pruebas está diseñado en Apache JMeter y contiene los siguientes componentes:

Plan de Pruebas
CSV Data Set Config: configuración de datos de entrada para escenarios dinámicos.
Grupo de Hilos: define el número de usuarios virtuales y duración de la prueba.
Petición HTTP: solicitud al endpoint bajo prueba.
Gestor de Cabecera HTTP: define headers como Content-Type, Authorization, etc.
Aserción de Respuesta: valida códigos de estado y contenido esperado.
Ver Árbol de Resultados: muestra respuestas individuales.
Informe Agregado: consolida métricas como TPS, latencia, errores, percentiles.

markdown
Copiar código

---

## 🧰 Configuración del Entorno

### Requisitos Previos
- [Java 11+](https://adoptium.net/) (para JMeter)
- [Git](https://git-scm.com/)

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/kevingarciamontes/RetoSoftkaPerformance.git



##  Autor : Kevin Garcia Montes
