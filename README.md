## **Ataques de cocodrilos en Costa Rica**

![](https://media.istockphoto.com/id/1253734587/es/foto/cocodrile-con-la-boca-abierta-de-fondo-textura-y-colores.jpg?s=612x612&w=0&k=20&c=BvRcU_ixb2USsaUt-bQc36fDRjVexZUM9nAfYh_lJJE=)

### **Introducción**

[*El pasado 13 de noviembre del 2022 murió un niño a causa de un cocodrilo en Matina, Limón*](https://www.eltiempo.com/mundo/latinoamerica/nino-de-8-anos-murio-tras-ser-devorado-por-un-cocodrilo-en-costa-rica-717276). A raíz de esta notici![Datos, 2005-2022](https://user-images.githubusercontent.com/129206442/232334995-cc4d483d-4a9b-48db-8a1b-b0ff7aafa596.jpg)
a se decidió investigar más sobre esta situación, ya que es normal que al año estos ataques frecuenten en los noticieros, sin embargo, la recolección de estos datos no es considerada lo suficientemente importante por el Sinac quien se encarga de este tipo de incidentes. el investigador Juan Bolaños actualmente este es el único que mantiene un registro de accidentes y muertes que hay en el país pues el Sinac no monitorea estos casos (Molina, 2019), los registros de Juan Bolaños tampoco se pudieron encontrar a lo largo de la investigación. 

### **Justificación**

La falta de información pública resulta en una población ignorante, logrando que ataques como estos no se tomen como la amenaza que realmente son. Este trabajo tiene como propósito mostrar la ubicación de los pocos casos que quedaron registrados en noticieros nacionales. 

### **Objetivo General:**

Mostrar la ubicación general de los ataques de cocodrilo en Costa Rica desde 2005-2022.

### **Objetivos Específicos:**

Identificar los principales cantones que reportan avistamientos de cocodrilos.

Reconocer las principales zonas de riesgo

### **Metodología**

Primeramente se utilizó Costa Rica como área de investigación, para la recolecta de datos se instó a los noticieros nacionales, estos eran casi los únicos que brindaba información acerca de ataques de cocodrilo desde el año 2005 hasta el 2022. Krissya León afirma que entre el 2016 y 2017 se reportaron en total 48 casos (León, 2018) casi 50 casos de los cuales solo 11 fueron rastreables. 
para la discretización de datos se optó por simplificar la agrupación de estos creando una tabla en excel con la información básica de cada caso: fecha, lugar, gravedad de ataque, nombre y edad esto con la finalidad de colocarlos en la tabla de atributos en qgis. 


![Datos, 2005-2022](https://user-images.githubusercontent.com/129206442/232335022-dfcb510e-d86f-4a77-ae1a-ebca9831f372.jpg)

Por último para la composición del mapa se creó una capa en formato Geopackage con punto como tipo de geometría en el sistema de coordenadas CRTM05, con los atributos mencionados anteriormente, esta capa se colocaría encima de un mapa base de Googlemaps roads. Se procedió a buscar manualmente el lugar aproximado de cada caso con sus respectivas propiedades, para después crear un mapa de calor usando arcgis online.

![Captura de pantalla 2023-04-16 115907](https://user-images.githubusercontent.com/129206442/232335062-4af208e6-71bc-4d8b-88e2-a26dd73cf5fc.png)
 
### **Conclusiones**

Gracias a todo lo anterior se puede concluir que, los ataques de cocodrilo son mucho más violentos en el agua, muy pocos de ellos ocurren en tierra firme, se puede observar que los lugares de riesgo son playas, desembocaduras de ríos y manglares. Precauciones a tomar en cuenta son, alejarse de los esterillos y evitar nadar en el mar cerca de una desembocadura de un río.  

En la [revista clínica de Céspedes Chávez](https://www.medigraphic.com/pdfs/revcliescmed/ucr-2018/ucr186g.pdf)  et al  en 2016 se reportaron 96 casos, en el 2017 fueron registrados 122. En total, 218 casos. Los datos revelan que la provincia que se mantiene con el mayor número de emergencias es Puntarenas (2018) casos de los cuales no se encontró un registro que esté abierto al público ¿Porque cree usted que estos casos no los publiquen? si fuera cierto que son tan pocos 

### **Bilbiografía**

1. Krissy, L. (2018, 7 marzo). Ataques de cocodrilos van en aumento. Crhoy. Recuperado 2 de noviembre de 2022, de https://www.crhoy.com/ambiente/ataques-de-cocodrilos-van-en-aumento/  

2. Benemérito Cuerpo de Bomberos de Costa Rica. (s. f.). Bomberos Costa Rica | Benemérito Cuerpo de Bomberos de Costa Rica. https://www.bomberos.go.cr/

3. Sandoval, L. F. (2017). Zonificación de las áreas propensas a incidentes por ataques de Crocodylus acutus en el Pacífico Central de Costa Rica utilizando un sistema de información geográfico. Tesis de maestría (inédita). Universidad Nacional. Heredia. Costa Rica. 84 p.

4. Vargas, J. M. & Teletica.com Redacción. (2016, 4 enero). Costa Rica es el país del Istmo con más ataques de cocodrilo. Teletica. https://www.teletica.com/reportajes/costa-rica-es-el-pais-del-istmo-con-mas-ataques-de-cocodrilo_60062

5. Solano C., H. & Quesada, A. C. (2021, 8 julio). Peón de camaronera sobrevive a ataque de cocodrilo en Osa: ‘Pensé que ese animal me ahogaba’. La Nación. https://www.nacion.com/sucesos/crimenes/peon-de-camaronera-sobrevive-a-ataque-de-cocodrilo/X6IR35KQOVBG7AD4STHPE6JLVQ/story/

6. Molina, L. (2019, 11 julio). Situación de los Cocodrilos permanece incierta tras fallo a favor del Sinac •. Semanario Universidad. https://semanariouniversidad.com/universitarias/situacion-de-los-cocodrilos-permanece-incierta-tras-fallo-a-favor-del-sinac/

7. Hugo, S. (2016, 22 julio). Médicos amputan parte de la pierna a turista atacado po un cocodrilo en Tamarindo. La Nación. https://www.nacion.com/sucesos/seguridad/medicos-amputan-parte-de-la-pierna-a-turista-atacado-por-un-cocodrilo-en-tamarindo/N42ZRIQX4BBA3HCGDDEHBDE2IQ/story/

8. Chaves R., K. (2021, 21 julio). Madre de hombre devorado por cocodrilos: ‘La angustia de no ver a sus hijos llevó a Omar a morir así’. La Nación. https://www.nacion.com/sucesos/accidentes/madre-de-hombre-devorado-por-cocodrilos-la-angustia-de-no-ver-a-sus-hijos-llevo-a-omar-a-morir-asi/UTVH77ML5JC5POHGOCXHTKWEVM/story/

9. La Nacion. (2021b, julio 21). Sobreviviente a ataque de cocodrilo: 'Cuando me mordió, pensé que me iba a morir' La NaciÃ 3 n. https://www.nacion.com/sucesos/accidentes/sobreviviente-a-ataque-de-cocodrilo-cuando-me-mordio-pense-que-me-iba-a-morir/7M7WFM4FWZCTJF6VNK5CNGVEJQ/story/

10. Cristian, M. (2022, 17 febrero). Hombre peleó en dos ocasiones contra cocodrilo para tratar de rescatar a su amigo.  Teletica. https://www.teletica.com/sucesos/hombre-peleo-en-dos-ocasiones-contra-cocodrilo-para-tratar-de-rescatar-a-su-amigo_305525

11. Sacrificaron al lagarto asesino - Nacionales - Periódico Al Día. Fútbol y noticias de Costa Rica. (s. f.). © 2010 Períodico Al Día. http://wvw.aldia.cr/ad_ee/2010/mayo/23/nacionales2378680.html

12. Juan Manuel, V. (2014, 23 febrero) Hombre resultó herido tras ataque de cocodrilo en río Tivives. Teletica. https://www.teletica.com/nacional/hombre-resulto-herido-tras-ataque-de-cocodrilo-en-rio-tivives_43993

13. Chaves, R. (2019, 28 noviembre). Mientras buscaba cocos en la playa, halla cuerpo de hombre. PZ Actual Noticias. https://pzactual.com/mientras-buscaba-cocos-en-la-playa-halla-cuerpo-de-hombre/

14. La Nacion. (2021a, julio 2). Rescataron cuerpo de niño muerto por cocodrilo en Cañas. La Nación. https://www.nacion.com/sucesos/rescataron-cuerpo-de-nino-muerto-por-cocodrilo-en-canas/GA6CAW27DVFKJMX36XRJMYPL3A/story/

15. Céspedes Chavez, Navarro Coto & Ledezma Cabezas. (2018). TEMA 2016: Vacuna contra virus del Papiloma Humano: Análisis de esquemas de dos dosificaciones. Revista Clínica de la Escuela de Medicina UCR-HSJD, 8(6). https://www.medigraphic.com/pdfs/revcliescmed/ucr-2018/ucr186g.pdf





