# Proyecto Individual II

## Análisis de telecomunicaciones

Soy analista de datos y una empresa prestadora de servicios de telecomunicaciones me ha encargado la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. La principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación. mi objetivo es orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.

## Descripción del Proyecto
Este proyecto se centra en analizar los datos relacionados con los servicios de conectividad y telecomunicaciones en distintas provincias de Argentina. El análisis abarca servicios de Internet, televisión y telefonía fija, explorando tendencias, patrones y desigualdades regionales. Mediante técnicas de Análisis Exploratorio de Datos (EDA). 

### Objetivo Principal
el objetivo principal del estudio es identificar indicadores clave de rendimiento (KPIs) y proporcionar información accionable para la toma de decisiones. Además se busca responder a las siguientes preguntas:

- ¿Cuál es la distribución de los accesos por tipo de tecnología en Argentina?
- ¿Cómo varían los servicios de conectividad entre las diferentes regiones?
- ¿Qué tendencias y patrones emergen del análisis exploratorio?

Los datos utilizados fueron procesados y analizados mediante Python, utilizando bibliotecas como Pandas, Seaborn y Matplotlib para cálculos y visualizaciones.

### Algunas observaciones identificadas son:
1. Distribución de accesos por tecnología
Resultado: En el último año, el 55% de los accesos totales fueron mediante cablemódem, mientras que la fibra óptica representa el 35%, consolidándose como la tecnología de mayor crecimiento.
2. Tasa de penetración de Internet
Resultado: En Capital Federal, la penetración alcanza el 116% de los hogares, mientras que en provincias como Chaco y Catamarca es inferior al 20%.
1. Velocidad promedio de bajada
Resultado: La velocidad promedio nacional es de 120 Mbps, con un máximo en Capital Federal (233 Mbps) y mínimos en regiones rurales.

## KPIs analizados
### KPI Crecimiento internet
Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia. La fórmula es la siguiente:

KPI Crec = ((Nuevo acceso − Acceso actual) / Acceso actual) ∗ 100

### KPI Grade up technology

KPI GT (Grade up technology) medirá el crecimiento de accesos por tecnologías modernas vs el total de accesos

GT = (accesos cablemodem + accesos fibra óptica) / total de accesos

KPI GT = (GT periodo actual - GT periodo nuevo)/periodo actual * 100

El KPI propuesto será de 3%, vale decir que se espera como meta que los accesos más rápidos a internet crezcan en razón del 3%

### KPI Incremento de velocidad media de internet

KPI IV (Incremento en velocidad media) medirá el aumento de la velocidad de internet por provincia

Incremento de velocidad = Mbps (media de bajada) periodo actual - Mbps (media de bajada) anterior

IV = (Mbps (media de bajada) periodo actual - Mbps (media de bajada) anterior) / Mbps (media de bajada) anterior

KPI IV = (IV periodo actual - IV periodo nuevo)/periodo actual * 100

El KPI propuesto será de 3%, vale decir que se espera como meta que la velocidad a internet crezcan en razón del 3%

## Conclusiones
### Crecimiento de la fibra óptica:
La fibra óptica está creciendo rápidamente y es la segunda tecnología más utilizada después del cable modem. Esto muestra una tendencia hacia conexiones más rápidas y confiables. Por el contrario la tecnología de ADSL que se caracteriza por ser más lenta viene en declive

### Desigualdad en conectividad:
Las provincias urbanas tienen mayor acceso y velocidades superiores, mientras que las zonas rurales enfrentan grandes brechas respecto a la tecnología.

### Impacto de la infraestructura:
Las provincias con mejor infraestructura, como Capital Federal y Buenos Aires, lideran en penetración y velocidad de descarga.

### Distribución de accesos telefónicos
Existe un liderazgo absoluto de la telefonía móvil respecto a la telefonía fija que ha venido en declive

### Accesos a televisión
La TV por suscripción acapara las preferencias en los hogares argentinos

## Recomendaciones
- Inversiones dirigidas a la fibra óptica:
Ampliar la infraestructura de fibra en regiones rurales para mejorar la conectividad y cerrar la brecha digital.

- Desarrollo de tecnologías inalámbricas:
Considerar el uso de tecnologías wireless para áreas remotas donde la fibra óptica es poco rentable.

- Promociones tipo packs:
Aplicar packs de promociones internet-tv satelital en zonas más rurales, ya que ambos servicios son complementarios a través de antenas satelitales