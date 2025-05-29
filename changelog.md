# 🛠️ CHANGELOG

## [1.0.0] - 2025-05-29

### Afegit
- Inicialització del projecte amb Flask.
- Integració de ngrok per exposar el servidor local públicament.
- Funció `obtener_info_web()` per fer scraping de pàgines internes.
- Configuració de CORS per permetre consultes externes sense bloquejos.
- Inclusió del client Gemini amb clau API per generar respostes.
- Impressió de l’URL públic del servidor a la consola.
- Filtrat de duplicats i enllaços externs durant el scraping.

### Canvis
- Millorat el format del contingut retornat amb títol i primeres línies dels paràgrafs.
- Afegida pausa d’1 segon entre sol·licituds per evitar penalitzacions per abús.

### Corregit
- Error que es produïa quan una pàgina no tenia títol (`NoneType` a `.string`).
- Millora en la gestió d'excepcions quan un enllaç no respon o dóna error HTTP.

### Eliminat
- S'ha eliminat la limitació que només permetia recórrer 1 nivell de profunditat (ara són 2).


