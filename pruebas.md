
[comment]: <!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!> 
&nbsp;
### AUTOBUS_ROUTE <a name="id9"></a>
&nbsp;

|Name|Value|
|----|---------|
|h<img width=200/>|h<img width=800/>|


[comment]: <!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!> 
&nbsp;
### AUTOBUS_OPERATOR <a name="id6"></a>
&nbsp;

|Campo|Tipo|Ejemplo|Descripción|URL|
|--------|-------|------------|---------------------|---------------------|
|ikey<img width=100/>|VARCHAR(50) <img width=100/>|BUSOPE01<img width=100/>|Identificador de la   Tabla (PK). <img width=800/>|<img width=500/>|
|serving_pt_for|VARCHAR(50)|CRTM|Esta propiedad indica para qué   Autoridad está trabajando la entidad operadora.|http://w3id.org/transmodel/organisations#servingPTFor|
|telephone|VARCHAR(200)|+34 91 406 88   10|Teléfono de   información y contacto con la entidad.|http://schema.org/telephone|
|email|VARCHAR(200)|https://www.emtmadrid.es/AtencionAlCliente/Agradecimientos    |Correo   electrónico de información.|http://schema.org/email|
|url|VARCHAR(400)|https://www.emtmadrid.es/Servicios/Contactar|Dirección   URL pública donde puedes obtener información de la entidad.|http://schema.org/url|
|street_address|VARCHAR(200)|Calle Cerro   de la Plata, 4|La dirección   de una parada.|http://schema.org/address|
|postal_code|VARCHAR(10)|28007|Una   dirección postal según el vocabulario esdir.|http://vocab.linkeddata.es/datosabiertos/def/urbanismo-infraestructuras/direccion-postal#DireccionPostal|
|legal_name|VARCHAR(200)|Empresa Municipal de   Transportes|Nombre legal. |http://schema.org/legalName|
|alternate_name|VARCHAR(200)|EMT|Nombre   alternativo, popular o por el que se conoce a algo.|http://schema.org/alternateName|


[comment]: <!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!> 

&nbsp;
### AUTOBUS_INCIDENCIA <a name="id10"></a>
&nbsp;


|     Campo                 |     Tipo             |     Ejemplo                                                                                   |     Descripción                                                                                                |     URL                                                                                        |
|---------------------------|----------------------|-----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
|     ikey                  |     VARCHAR(50)      |     BUSINC01                                                                                  |     Identificador de la   Tabla (PK).                                                                          |                                                                                                |
|     id                    |     VARCHAR(50)      |     29059944-382A-49AA-A068-B55BF2FAC51F                                                      |                                                                                                                |     http://purl.org/dc/terms/identifier                                                        |
|     description           |     VARCHAR(4000)    |     Corte de calles   entre el cruce de Alcalá con Gran Vía y la Plaza de la Independencia    |     Una   descripción del recurso dentro de un contexto dado.                                                  |     http://purl.org/dc/terms/description                                                       |
|     tipo_incidencia       |     VARCHAR(50)      |     obras                                                                                     |     Es de tipo   SKOS:     http://vocab.linkeddata.es/datosabiertos/kos/transporte/trafico/tipo-incidencia     |     http://vocab.ciudadesabiertas.es/def/transporte/trafico#tipoIncidencia                     |
|     date_posted           |     DATETIME         |     2020-03-31   08:00:00                                                                     |     La fecha y   hora de publicación de una incidencia (en formato fecha ISO 8601)                             |     http://schema.org/datePosted                                                               |
|     num_sentidos          |     INTEGER          |     2                                                                                         |     Número de   sentidos de circulación                                                                        |     http://vocab.ciudadesabiertas.es/def/transporte/trafico#numSentidos                        |
|     num_carriles          |     INTEGER          |     8                                                                                         |     Número de   carriles de circulación                                                                        |     http://vocab.ciudadesabiertas.es/def/transporte/trafico#numCarriles                        |
|     es_recurrente         |     BIT(1)           |     0                                                                                         |     Esta   propiedad permite describir si la incidencia es recurrente o no.                                    |     http://vocab.ciudadesabiertas.es/def/transporte/trafico#esRecurrente                       |
|     fecha_fin_prevista    |     DATETIME         |     2020-05-03   23:59:00                                                                     |     La fecha y   hora prevista de finalización de una incidencia planificada (en formato fecha   ISO 8601).    |     http://vocab.ciudadesabiertas.es/def/transporte/trafico#fechaFinPrevista                   |
|     x_etrs89              |     DECIMAL(13,5)    |     440124.33000                                                                              |     Coordenada X   en metros (ETRS89).                                                                         |     https://datos.ign.es/def/geo_core#xETRS89                                                  |
|     y_etrs89              |     DECIMAL(13,5)    |     4474637.17000                                                                             |     Coordenada Y   en metros (ETRS89).                                                                         |     https://datos.ign.es/def/geo_core#yETRS89                                                  |
|     incidencia_tramo      |     VARCHAR(50)      |     TRAFTRAM01                                                                                |     Relación de   la Incidencia con el Tramo donde se produce la misma.                                        |     http://vocab.ciudadesabiertas.es/def/transporte/trafico/index-es.html#incidenciaEnTramo    |





