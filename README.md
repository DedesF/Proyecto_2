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
La fibra óptica está creciendo rápidamente y es la segunda tecnología más utilizada después del cable modem. Esto muestra una tendencia hacia conexiones más rápidas y confiables. Por el contrario la tecnología de ADSL que se caracteriza por ser más lenta viene en declive.

Las provincias urbanas tienen mayor acceso y velocidades, ya que deben liderar en infraestructura, mientras que las zonas rurales enfrentan grandes brechas respecto a la tecnología.

Existe un liderazgo absoluto de la telefonía móvil respecto a la telefonía fija que ha venido en declive a través de los años.
La TV por suscripción acapara las preferencias en los hogares argentinos.


## Recomendaciones
En las zonas más pobladas es necesario entrar a competir con tecnología de punta como fibra óptica o cable módem, ya que la competencia es mayor que en zonas menos pobladas.

Ampliar la infraestructura de fibra óptica en regiones más rurales para mejorar la conectividad y comenzar a provocar cierre de la brecha digital.

Sí la fibra óptica es poco rentable considerar el uso de tecnologías de cable módem o wireless para las áreas más remotas o con pocos habitantes.

Aplicar packs de promociones internet, tv satelital y telefonía fija, ya que son servicios que pueden ser brindados a través de antenas satelitales.