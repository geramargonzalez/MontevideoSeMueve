# Montevideo se mueve: Datos para una movilidad más segura

![Urban Mobility](https://img.shields.io/badge/Montevideo–Movilidad–blue)

## Descripción

Este proyecto analiza los siniestros viales ocurridos en Montevideo durante 2022 con el fin de extraer patrones críticos y proponer recomendaciones de política pública que contribuyan a una movilidad más segura en la capital uruguaya. Se centra en variables como edad, sexo, rol, tipo de vehículo, zona, momento del día y tipo de siniestro, y ofrece seis líneas de acción basadas en los hallazgos.

## Autores y Contexto

- **Diego Aguiar**  
- **Andrea Aranda**  
- **Gerardo González**  
- **Mariana Sambucetti**  

**Materia:** Fundamentos de Programación para la CD e IA  
**Docentes:** Nelcy Atehortua, Natalia Castro  
**Fecha:** 29 de mayo de 2025  

---

## Tabla de Contenidos

1. [Objetivos](#objetivos)  
2. [Conjunto de Datos](#conjunto-de-datos)  
3. [Metodología](#metodología)  
4. [Resultados Preliminares](#resultados-preliminares)  
5. [Recomendaciones de Política](#recomendaciones-de-política)  
6. [Estructura del Repositorio](#estructura-del-repositorio)  
7. [Requisitos e Instalación](#requisitos-e-instalación)  
8. [Uso](#uso)  
9. [Licencia](#licencia)  

---

## Objetivos

1. Analizar las características de los siniestros de tránsito en Montevideo en 2022.  
2. Identificar patrones críticos según perfil de los involucrados (edad, sexo, rol, tipo de vehículo, zona, hora y tipo de siniestro).  
3. Proponer recomendaciones de políticas públicas sustentadas en datos.

---

## Conjunto de Datos

- **Fuente:** [catalogodatos.gub.uy](https://catalogodatos.gub.uy)  
- **Descripción:** Registro anual completo de personas lesionadas en siniestros de tránsito en Montevideo (2022).  
- **Última actualización:** 31 de agosto de 2023 (UTC-03:00)  
- **Observaciones:** 7.802 registros, 19 variables (edad, fecha, rol, zona, tipo de resultado, tipo de siniestro, día de la semana, sexo, hora, departamento, localidad, tipo de vehículo, latitud, longitud, etc.).  

---

## Metodología

1. **Limpieza y Preprocesamiento**  
   - Verificación e imputación de valores faltantes.  
   - Ajuste de tipos de datos y selección de variables relevantes.  

2. **Visualización y Análisis**  
   - Estadísticas descriptivas.  
   - Mapas y gráficos temporales.  
   - Análisis de series horarias y espaciales.  

3. **Conclusiones**  
   - Síntesis de hallazgos.  
   - Limitaciones del análisis.  
   - Recomendaciones de políticas.

---

## Resultados Preliminares

- **Edad de los afectados:**  
  - Promedio: 35 años  
  - Mediana: 32 años  
  - Rango intercuartílico: 23–46 años  

- **Perfil general:**  
  - Predominan hombres conductores de vehículos birrodados.  
  - 87 % de los siniestros resultan en heridas leves.  
  - 83 % ocurren en zonas urbanas.  
  - 33 % se concentran en horario de la tarde.

---

## Recomendaciones de Política

1. **Rediseño de corredores de alta siniestralidad**  
   - Intervenciones físicas en cruces y limitadores de velocidad inteligentes.  
   - Carriles exclusivos para motos/transporte público.

2. **Redistribución horaria del control de tránsito**  
   - Cobertura ampliada en tardes y noches.  
   - Mejora de iluminación y coordinación de respuesta.

3. **Intervención educativa temprana (enfoque demográfico)**  
   - Educación vial obligatoria en secundaria (UTU y liceos).  
   - Campañas segmentadas para usuarios de birrodados.

4. **Protección avanzada de peatones**  
   - Semáforos inteligentes y botones de cruce.  
   - Ampliación de veredas y señalización renovada.

5. **Protección específica para adultos mayores**  
   - Zonas de “tránsito calmado” cerca de centros sensibles.  
   - Tiempo de cruce prolongado y rampas accesibles.

6. **Regulación del comportamiento de conductores**  
   - Campañas obligatorias al renovar licencias.  
   - Fiscalización de distracciones y descuentos por buen comportamiento.

---

## Estructura del Repositorio

```plaintext
.
├── data/                   # Datos originales y procesados
│   ├── raw/                # Archivos sin procesar
│   └── processed/          # Datos limpios para análisis
├── notebooks/              # Jupyter notebooks de análisis
├── src/                    # Código fuente (scripts de limpieza y visualización)
├── figures/                # Gráficos y mapas generados
├── README.md               # Este archivo
└── requirements.txt        # Dependencias del proyecto
