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

## 🧠 Tipos de Pruebas Implementadas

1. **Smoke Test:** Validación rápida del entorno y los endpoints.
2. **Load Test:** Verifica el comportamiento del sistema con carga esperada.
3. **Stress Test:** Evalúa los límites y la estabilidad bajo alta concurrencia.
4. **Spike Test:** Observa la respuesta ante picos repentinos de tráfico.
5. **Endurance Test:** Mide la estabilidad y consumo de recursos durante largos periodos.

---

## 🧪 Estructura del Proyecto

performance-tests/
├── scripts/ # Scripts de ejecución y análisis
├── tests/ # Escenarios de prueba (.jmx, .js, .scala, etc.)
│ ├── load_test.jmx
│ ├── stress_test.jmx
│ └── spike_test.jmx
├── reports/ # Resultados y reportes generados
│ └── summary.html
├── data/ # Archivos CSV o JSON con datos de prueba
└── README.md

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