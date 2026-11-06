# 🌱 Huerto y Clima España — Calendarios de Siembra, Riego y Fechas de Helada por Municipio

🌐 **Acceso directo a la plataforma web:** [**https://huerto-clima.pages.dev/**](https://huerto-clima.pages.dev/)

**Huerto y Clima España** es un portal agroclimático de consulta pública que calcula las **fechas seguras de última helada primaveral y primera helada otoñal**, las **necesidades mensuales de riego por goteo ($ET_0$ FAO-56)** y el **calendario de siembra, trasplante y cosecha de 22 cultivos hortícolas** adaptado al microclima real de cada municipio español.

---

## 🔬 Metodología Agroclimática y Fuentes de Datos

Cada estudio municipal de [**Huerto y Clima España**](https://huerto-clima.pages.dev/) combina observaciones meteorológicas oficiales e integración bioclimática:

### 1. Arquitectura Híbrida de Datos (AEMET OpenData + Copernicus ERA5)
- **Observación en estación oficial (AEMET):** Prioriza series diarias de estaciones termométricas oficiales situadas en el entorno inmediato del municipio ($\le 15\text{ km}$ y $\le 150\text{ m}$ de diferencia altitudinal).
- **Reanálisis climático ERA5 (ECMWF):** Series diarias (2016–2025) de radiación y evapotranspiración potencial para el balance hídrico completo.

### 2. Doble Umbral de Helada ($0\ ^\circ\text{C}$ y $2\ ^\circ\text{C}$) y Percentil 90
- **Helada meteorológica ($\le 0\ ^\circ\text{C}$ en garita):** Referencia para cultivos rústicos de invierno y crucíferas.
- **Helada agronómica a ras de suelo ($\le 2\ ^\circ\text{C}$ en garita):** Cuando el termómetro a 1,5 m marca $2\ ^\circ\text{C}$ en noches despejadas de inversión térmica, la hoja a nivel del suelo ya experimenta $0\ ^\circ\text{C}$. Es el umbral crítico para solanáceas y cucurbitáceas (**tomate, pimiento, berenjena, calabacín, pepino**).
- **Fecha Segura (Percentil 90):** Fecha a partir de la cual el riesgo estadístico de helada tardía es inferior al 10 % (solo 1 de cada 10 años).

### 3. Balance Hídrico Mensual (FAO-56) y 22 Cultivos Modelados
- **Déficit hídrico neto ($\text{L}/\text{m}^2/\text{día}$):** Diferencia mensual entre la evapotranspiración de referencia ($ET_0$) y la precipitación efectiva ($80\%$), con calculadora interactiva de caudal de riego según superficie de huerto o bancal.
- **Integral térmica ($GDD_{10}$):** Calendario específico de semillero protegido, siembra directa/trasplante al exterior y recolección para 22 hortalizas.

---

## 🥬 Calendarios Nacionales por Cultivo (22 Hortalizas)

Consulta cuándo sembrar o trasplantar cada cultivo en España según su rango térmico óptimo y tolerancia a las heladas:

| Cultivo | Método | Temporada | Sensibilidad a Heladas | Estudio Nacional del Cultivo |
| :--- | :--- | :--- | :--- | :--- |
| **Tomate** | Trasplante | Verano | Alta | [Cuándo plantar tomate en España](https://huerto-clima.pages.dev/cultivos/tomate) |
| **Pimiento** | Trasplante | Verano | Alta | [Cuándo plantar pimiento en España](https://huerto-clima.pages.dev/cultivos/pimiento) |
| **Berenjena** | Trasplante | Verano | Alta | [Cuándo plantar berenjena en España](https://huerto-clima.pages.dev/cultivos/berenjena) |
| **Calabacín** | Siembra directa | Verano | Alta | [Cuándo plantar calabacín en España](https://huerto-clima.pages.dev/cultivos/calabacin) |
| **Pepino** | Siembra directa | Verano | Alta | [Cuándo plantar pepino en España](https://huerto-clima.pages.dev/cultivos/pepino) |
| **Judía verde** | Siembra directa | Verano | Alta | [Cuándo plantar judía verde en España](https://huerto-clima.pages.dev/cultivos/judia-verde) |
| **Melón** | Trasplante | Verano | Alta | [Cuándo plantar melón en España](https://huerto-clima.pages.dev/cultivos/melon) |
| **Sandía** | Trasplante | Verano | Alta | [Cuándo plantar sandía en España](https://huerto-clima.pages.dev/cultivos/sandia) |
| **Maíz dulce** | Siembra directa | Verano | Alta | [Cuándo plantar maíz dulce en España](https://huerto-clima.pages.dev/cultivos/maiz-dulce) |
| **Calabaza** | Siembra directa | Verano | Alta | [Cuándo plantar calabaza en España](https://huerto-clima.pages.dev/cultivos/calabaza) |
| **Patata** | Siembra directa | Verano | Media | [Cuándo plantar patata en España](https://huerto-clima.pages.dev/cultivos/patata) |
| **Lechuga** | Trasplante | Invierno | Baja | [Cuándo plantar lechuga en España](https://huerto-clima.pages.dev/cultivos/lechuga) |
| **Espinaca** | Siembra directa | Invierno | Baja | [Cuándo plantar espinaca en España](https://huerto-clima.pages.dev/cultivos/espinaca) |
| **Acelga** | Siembra directa | Invierno | Baja | [Cuándo plantar acelga en España](https://huerto-clima.pages.dev/cultivos/acelga) |
| **Zanahoria** | Siembra directa | Invierno | Baja | [Cuándo plantar zanahoria en España](https://huerto-clima.pages.dev/cultivos/zanahoria) |
| **Rábano** | Siembra directa | Invierno | Baja | [Cuándo plantar rábano en España](https://huerto-clima.pages.dev/cultivos/rabano) |
| **Cebolla** | Trasplante | Invierno | Baja | [Cuándo plantar cebolla en España](https://huerto-clima.pages.dev/cultivos/cebolla) |
| **Ajo** | Siembra directa | Invierno | Baja | [Cuándo plantar ajo en España](https://huerto-clima.pages.dev/cultivos/ajo) |
| **Haba** | Siembra directa | Invierno | Baja | [Cuándo plantar haba en España](https://huerto-clima.pages.dev/cultivos/haba) |
| **Guisante** | Siembra directa | Invierno | Baja | [Cuándo plantar guisante en España](https://huerto-clima.pages.dev/cultivos/guisante) |
| **Brócoli** | Trasplante | Invierno | Baja | [Cuándo plantar brócoli en España](https://huerto-clima.pages.dev/cultivos/brocoli) |
| **Col** | Trasplante | Invierno | Baja | [Cuándo plantar col en España](https://huerto-clima.pages.dev/cultivos/col) |

---

## 🗺️ Atlas Provincial de Huerto y Heladas (52 Provincias)

| Provincia | Comunidad Autónoma | Enlace al Estudio Provincial |
| :--- | :--- | :--- |
| **A Coruña** | Galicia | [Ver 9 municipios de A Coruña](https://huerto-clima.pages.dev/provincias/a-coruna) |
| **Albacete** | Castilla-La Mancha | [Ver 6 municipios de Albacete](https://huerto-clima.pages.dev/provincias/albacete) |
| **Alicante** | Comunitat Valenciana | [Ver 25 municipios de Alicante](https://huerto-clima.pages.dev/provincias/alicante) |
| **Almería** | Andalucía | [Ver 9 municipios de Almería](https://huerto-clima.pages.dev/provincias/almeria) |
| **Araba** | País Vasco | [Ver 2 municipios de Araba](https://huerto-clima.pages.dev/provincias/araba) |
| **Asturias** | Principado de Asturias | [Ver 7 municipios de Asturias](https://huerto-clima.pages.dev/provincias/asturias) |
| **Badajoz** | Extremadura | [Ver 5 municipios de Badajoz](https://huerto-clima.pages.dev/provincias/badajoz) |
| **Barcelona** | Cataluña | [Ver 34 municipios de Barcelona](https://huerto-clima.pages.dev/provincias/barcelona) |
| **Bizkaia** | País Vasco | [Ver 10 municipios de Bizkaia](https://huerto-clima.pages.dev/provincias/bizkaia) |
| **Burgos** | Castilla y León | [Ver 3 municipios de Burgos](https://huerto-clima.pages.dev/provincias/burgos) |
| **Cantabria** | Cantabria | [Ver 7 municipios de Cantabria](https://huerto-clima.pages.dev/provincias/cantabria) |
| **Castellón** | Comunitat Valenciana | [Ver 9 municipios de Castellón](https://huerto-clima.pages.dev/provincias/castellon) |
| **Ceuta** | Ceuta | [Ver 1 municipios de Ceuta](https://huerto-clima.pages.dev/provincias/ceuta) |
| **Ciudad Real** | Castilla-La Mancha | [Ver 11 municipios de Ciudad Real](https://huerto-clima.pages.dev/provincias/ciudad-real) |
| **Cuenca** | Castilla-La Mancha | [Ver 2 municipios de Cuenca](https://huerto-clima.pages.dev/provincias/cuenca) |
| **Cáceres** | Extremadura | [Ver 2 municipios de Cáceres](https://huerto-clima.pages.dev/provincias/caceres) |
| **Cádiz** | Andalucía | [Ver 15 municipios de Cádiz](https://huerto-clima.pages.dev/provincias/cadiz) |
| **Córdoba** | Andalucía | [Ver 8 municipios de Córdoba](https://huerto-clima.pages.dev/provincias/cordoba) |
| **Gipuzkoa** | País Vasco | [Ver 7 municipios de Gipuzkoa](https://huerto-clima.pages.dev/provincias/gipuzkoa) |
| **Girona** | Cataluña | [Ver 8 municipios de Girona](https://huerto-clima.pages.dev/provincias/girona) |
| **Granada** | Andalucía | [Ver 11 municipios de Granada](https://huerto-clima.pages.dev/provincias/granada) |
| **Guadalajara** | Castilla-La Mancha | [Ver 10 municipios de Guadalajara](https://huerto-clima.pages.dev/provincias/guadalajara) |
| **Huelva** | Andalucía | [Ver 6 municipios de Huelva](https://huerto-clima.pages.dev/provincias/huelva) |
| **Huesca** | Aragón | [Ver 3 municipios de Huesca](https://huerto-clima.pages.dev/provincias/huesca) |
| **Illes Balears** | Illes Balears | [Ver 12 municipios de Illes Balears](https://huerto-clima.pages.dev/provincias/illes-balears) |
| **Jaén** | Andalucía | [Ver 7 municipios de Jaén](https://huerto-clima.pages.dev/provincias/jaen) |
| **La Rioja** | La Rioja | [Ver 3 municipios de La Rioja](https://huerto-clima.pages.dev/provincias/la-rioja) |
| **Las Palmas** | Canarias | [Ver 9 municipios de Las Palmas](https://huerto-clima.pages.dev/provincias/las-palmas) |
| **León** | Castilla y León | [Ver 4 municipios de León](https://huerto-clima.pages.dev/provincias/leon) |
| **Lleida** | Cataluña | [Ver 1 municipios de Lleida](https://huerto-clima.pages.dev/provincias/lleida) |
| **Lugo** | Galicia | [Ver 1 municipios de Lugo](https://huerto-clima.pages.dev/provincias/lugo) |
| **Madrid** | Comunidad de Madrid | [Ver 72 municipios de Madrid](https://huerto-clima.pages.dev/provincias/madrid) |
| **Melilla** | Melilla | [Ver 1 municipios de Melilla](https://huerto-clima.pages.dev/provincias/melilla) |
| **Murcia** | Región de Murcia | [Ver 15 municipios de Murcia](https://huerto-clima.pages.dev/provincias/murcia) |
| **Málaga** | Andalucía | [Ver 18 municipios de Málaga](https://huerto-clima.pages.dev/provincias/malaga) |
| **Navarra** | Comunidad Foral de Navarra | [Ver 6 municipios de Navarra](https://huerto-clima.pages.dev/provincias/navarra) |
| **Ourense** | Galicia | [Ver 1 municipios de Ourense](https://huerto-clima.pages.dev/provincias/ourense) |
| **Palencia** | Castilla y León | [Ver 1 municipios de Palencia](https://huerto-clima.pages.dev/provincias/palencia) |
| **Pontevedra** | Galicia | [Ver 9 municipios de Pontevedra](https://huerto-clima.pages.dev/provincias/pontevedra) |
| **Salamanca** | Castilla y León | [Ver 2 municipios de Salamanca](https://huerto-clima.pages.dev/provincias/salamanca) |
| **Santa Cruz de Tenerife** | Canarias | [Ver 9 municipios de Santa Cruz de Tenerife](https://huerto-clima.pages.dev/provincias/santa-cruz-de-tenerife) |
| **Segovia** | Castilla y León | [Ver 1 municipios de Segovia](https://huerto-clima.pages.dev/provincias/segovia) |
| **Sevilla** | Andalucía | [Ver 22 municipios de Sevilla](https://huerto-clima.pages.dev/provincias/sevilla) |
| **Soria** | Castilla y León | [Ver 1 municipios de Soria](https://huerto-clima.pages.dev/provincias/soria) |
| **Tarragona** | Cataluña | [Ver 10 municipios de Tarragona](https://huerto-clima.pages.dev/provincias/tarragona) |
| **Teruel** | Aragón | [Ver 2 municipios de Teruel](https://huerto-clima.pages.dev/provincias/teruel) |
| **Toledo** | Castilla-La Mancha | [Ver 14 municipios de Toledo](https://huerto-clima.pages.dev/provincias/toledo) |
| **Valencia** | Comunitat Valenciana | [Ver 23 municipios de Valencia](https://huerto-clima.pages.dev/provincias/valencia) |
| **Valladolid** | Castilla y León | [Ver 4 municipios de Valladolid](https://huerto-clima.pages.dev/provincias/valladolid) |
| **Zamora** | Castilla y León | [Ver 2 municipios de Zamora](https://huerto-clima.pages.dev/provincias/zamora) |
| **Zaragoza** | Aragón | [Ver 4 municipios de Zaragoza](https://huerto-clima.pages.dev/provincias/zaragoza) |
| **Ávila** | Castilla y León | [Ver 1 municipios de Ávila](https://huerto-clima.pages.dev/provincias/avila) |

---

## 🍅 Calendarios Municipales de Siembra y Heladas (465 Municipios)

| Municipio | Provincia | Altitud | Última Helada Segura (Cultivos Sensibles) | Periodo Libre de Heladas | Ficha Completa |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Madrid** | Madrid | `657 m` | 31 de marzo | `232 días` | [Ver calendario de Madrid](https://huerto-clima.pages.dev/municipios/madrid) |
| **Barcelona** | Barcelona | `12 m` | 21 de febrero | `309 días` | [Ver calendario de Barcelona](https://huerto-clima.pages.dev/municipios/barcelona) |
| **València** | Valencia | `15 m` | 22 de enero | `343 días` | [Ver calendario de València](https://huerto-clima.pages.dev/municipios/valencia) |
| **Sevilla** | Sevilla | `14 m` | 18 de febrero | `306 días` | [Ver calendario de Sevilla](https://huerto-clima.pages.dev/municipios/sevilla) |
| **Zaragoza** | Zaragoza | `208 m` | 15 de marzo | `264 días` | [Ver calendario de Zaragoza](https://huerto-clima.pages.dev/municipios/zaragoza) |
| **Málaga** | Málaga | `11 m` | Sin riesgo severo | `365 días` | [Ver calendario de Málaga](https://huerto-clima.pages.dev/municipios/malaga) |
| **Murcia** | Murcia | `43 m` | 29 de enero | `336 días` | [Ver calendario de Murcia](https://huerto-clima.pages.dev/municipios/murcia) |
| **Palma** | Illes Balears | `13 m` | Sin riesgo severo | `365 días` | [Ver calendario de Palma](https://huerto-clima.pages.dev/municipios/palma) |
| **Las Palmas de Gran Canaria** | Las Palmas | `8 m` | Sin riesgo severo | `365 días` | [Ver calendario de Las Palmas de Gran Canaria](https://huerto-clima.pages.dev/municipios/las-palmas-de-gran-canaria) |
| **Alicante** | Alicante | `12 m` | 16 de febrero | `318 días` | [Ver calendario de Alicante](https://huerto-clima.pages.dev/municipios/alicante) |
| **Bilbao** | Bizkaia | `19 m` | 1 de abril | `247 días` | [Ver calendario de Bilbao](https://huerto-clima.pages.dev/municipios/bilbao) |
| **Córdoba** | Córdoba | `106 m` | 25 de marzo | `228 días` | [Ver calendario de Córdoba](https://huerto-clima.pages.dev/municipios/cordoba) |
| **Valladolid** | Valladolid | `690 m` | 29 de abril | `182 días` | [Ver calendario de Valladolid](https://huerto-clima.pages.dev/municipios/valladolid) |
| **Vigo** | Pontevedra | `28 m` | 13 de marzo | `271 días` | [Ver calendario de Vigo](https://huerto-clima.pages.dev/municipios/vigo) |
| **L'Hospitalet de Llobregat** | Barcelona | `8 m` | 7 de febrero | `295 días` | [Ver calendario de L'Hospitalet de Llobregat](https://huerto-clima.pages.dev/municipios/l-hospitalet-de-llobregat) |
| **Gijón** | Asturias | `10 m` | 24 de febrero | `297 días` | [Ver calendario de Gijón](https://huerto-clima.pages.dev/municipios/gijon) |
| **Vitoria-Gasteiz** | Araba | `525 m` | 29 de abril | `205 días` | [Ver calendario de Vitoria-Gasteiz](https://huerto-clima.pages.dev/municipios/vitoria-gasteiz) |
| **A Coruña** | A Coruña | `25 m` | 6 de enero | `359 días` | [Ver calendario de A Coruña](https://huerto-clima.pages.dev/municipios/a-coruna) |
| **Elche** | Alicante | `86 m` | 29 de enero | `332 días` | [Ver calendario de Elche](https://huerto-clima.pages.dev/municipios/elche) |
| **Granada** | Granada | `684 m` | 28 de marzo | `230 días` | [Ver calendario de Granada](https://huerto-clima.pages.dev/municipios/granada) |
| **Badalona** | Barcelona | `6 m` | 7 de febrero | `323 días` | [Ver calendario de Badalona](https://huerto-clima.pages.dev/municipios/badalona) |
| **Terrassa** | Barcelona | `277 m` | 30 de marzo | `237 días` | [Ver calendario de Terrassa](https://huerto-clima.pages.dev/municipios/terrassa) |
| **Sabadell** | Barcelona | `190 m` | 16 de abril | `221 días` | [Ver calendario de Sabadell](https://huerto-clima.pages.dev/municipios/sabadell) |
| **Cartagena** | Murcia | `10 m` | 12 de enero | `353 días` | [Ver calendario de Cartagena](https://huerto-clima.pages.dev/municipios/cartagena) |
| **Oviedo** | Asturias | `232 m` | 14 de abril | `224 días` | [Ver calendario de Oviedo](https://huerto-clima.pages.dev/municipios/oviedo) |
| **Jerez de la Frontera** | Cádiz | `56 m` | 26 de enero | `339 días` | [Ver calendario de Jerez de la Frontera](https://huerto-clima.pages.dev/municipios/jerez-de-la-frontera) |
| **Móstoles** | Madrid | `660 m` | 4 de abril | `218 días` | [Ver calendario de Móstoles](https://huerto-clima.pages.dev/municipios/mostoles) |
| **Santa Cruz de Tenerife** | Santa Cruz de Tenerife | `35 m` | Sin riesgo severo | `365 días` | [Ver calendario de Santa Cruz de Tenerife](https://huerto-clima.pages.dev/municipios/santa-cruz-de-tenerife) |
| **Pamplona** | Navarra | `449 m` | 17 de abril | `205 días` | [Ver calendario de Pamplona](https://huerto-clima.pages.dev/municipios/pamplona) |
| **Almería** | Almería | `20 m` | Sin riesgo severo | `365 días` | [Ver calendario de Almería](https://huerto-clima.pages.dev/municipios/almeria) |
| **Alcalá de Henares** | Madrid | `588 m` | 22 de mayo | `153 días` | [Ver calendario de Alcalá de Henares](https://huerto-clima.pages.dev/municipios/alcala-de-henares) |
| **Leganés** | Madrid | `665 m` | 31 de marzo | `223 días` | [Ver calendario de Leganés](https://huerto-clima.pages.dev/municipios/leganes) |
| **Donostia / San Sebastián** | Gipuzkoa | `8 m` | 15 de marzo | `285 días` | [Ver calendario de Donostia / San Sebastián](https://huerto-clima.pages.dev/municipios/donostia-san-sebastian) |
| **Fuenlabrada** | Madrid | `664 m` | 31 de marzo | `223 días` | [Ver calendario de Fuenlabrada](https://huerto-clima.pages.dev/municipios/fuenlabrada) |
| **Getafe** | Madrid | `622 m` | 31 de marzo | `223 días` | [Ver calendario de Getafe](https://huerto-clima.pages.dev/municipios/getafe) |
| **Castelló de la Plana** | Castellón | `27 m` | 22 de febrero | `307 días` | [Ver calendario de Castelló de la Plana](https://huerto-clima.pages.dev/municipios/castello-de-la-plana) |
| **Burgos** | Burgos | `859 m` | 12 de junio | `100 días` | [Ver calendario de Burgos](https://huerto-clima.pages.dev/municipios/burgos) |
| **Albacete** | Albacete | `686 m` | 22 de abril | `196 días` | [Ver calendario de Albacete](https://huerto-clima.pages.dev/municipios/albacete) |
| **Santander** | Cantabria | `15 m` | 8 de marzo | `293 días` | [Ver calendario de Santander](https://huerto-clima.pages.dev/municipios/santander) |
| **Alcorcón** | Madrid | `711 m` | 4 de abril | `218 días` | [Ver calendario de Alcorcón](https://huerto-clima.pages.dev/municipios/alcorcon) |
| **San Cristóbal de La Laguna** | Santa Cruz de Tenerife | `546 m` | Sin riesgo severo | `365 días` | [Ver calendario de San Cristóbal de La Laguna](https://huerto-clima.pages.dev/municipios/san-cristobal-de-la-laguna) |
| **Marbella** | Málaga | `27 m` | Sin riesgo severo | `365 días` | [Ver calendario de Marbella](https://huerto-clima.pages.dev/municipios/marbella) |
| **Logroño** | La Rioja | `384 m` | 16 de abril | `206 días` | [Ver calendario de Logroño](https://huerto-clima.pages.dev/municipios/logrono) |
| **Badajoz** | Badajoz | `185 m` | 5 de marzo | `261 días` | [Ver calendario de Badajoz](https://huerto-clima.pages.dev/municipios/badajoz) |
| **Salamanca** | Salamanca | `798 m` | 29 de abril | `180 días` | [Ver calendario de Salamanca](https://huerto-clima.pages.dev/municipios/salamanca) |
| **Lleida** | Lleida | `155 m` | 30 de marzo | `225 días` | [Ver calendario de Lleida](https://huerto-clima.pages.dev/municipios/lleida) |
| **Huelva** | Huelva | `24 m` | 13 de febrero | `318 días` | [Ver calendario de Huelva](https://huerto-clima.pages.dev/municipios/huelva) |
| **Dos Hermanas** | Sevilla | `42 m` | 18 de febrero | `306 días` | [Ver calendario de Dos Hermanas](https://huerto-clima.pages.dev/municipios/dos-hermanas) |
| **Tarragona** | Tarragona | `69 m` | 22 de febrero | `289 días` | [Ver calendario de Tarragona](https://huerto-clima.pages.dev/municipios/tarragona) |
| **Torrejón de Ardoz** | Madrid | `585 m` | 22 de mayo | `153 días` | [Ver calendario de Torrejón de Ardoz](https://huerto-clima.pages.dev/municipios/torrejon-de-ardoz) |
| **Parla** | Madrid | `648 m` | 31 de marzo | `223 días` | [Ver calendario de Parla](https://huerto-clima.pages.dev/municipios/parla) |
| **Mataró** | Barcelona | `28 m` | 25 de enero | `319 días` | [Ver calendario de Mataró](https://huerto-clima.pages.dev/municipios/mataro) |
| **Algeciras** | Cádiz | `20 m` | Sin riesgo severo | `365 días` | [Ver calendario de Algeciras](https://huerto-clima.pages.dev/municipios/algeciras) |
| **León** | León | `837 m` | 6 de mayo | `170 días` | [Ver calendario de León](https://huerto-clima.pages.dev/municipios/leon) |
| **Santa Coloma de Gramenet** | Barcelona | `56 m` | 7 de febrero | `323 días` | [Ver calendario de Santa Coloma de Gramenet](https://huerto-clima.pages.dev/municipios/santa-coloma-de-gramenet) |
| **Alcobendas** | Madrid | `669 m` | 24 de abril | `193 días` | [Ver calendario de Alcobendas](https://huerto-clima.pages.dev/municipios/alcobendas) |
| **Jaén** | Jaén | `573 m` | 31 de marzo | `235 días` | [Ver calendario de Jaén](https://huerto-clima.pages.dev/municipios/jaen) |
| **Cádiz** | Cádiz | `11 m` | 8 de enero | `357 días` | [Ver calendario de Cádiz](https://huerto-clima.pages.dev/municipios/cadiz) |
| **Reus** | Tarragona | `117 m` | 11 de marzo | `270 días` | [Ver calendario de Reus](https://huerto-clima.pages.dev/municipios/reus) |
| **Roquetas de Mar** | Almería | `10 m` | Sin riesgo severo | `365 días` | [Ver calendario de Roquetas de Mar](https://huerto-clima.pages.dev/municipios/roquetas-de-mar) |

👉 **[Ver el Directorio Completo con los 465 Municipios organizados por Provincias](./DIRECTORIO_MUNICIPIOS.md)**

---

## ☀️ Proyecto Climático Hermano: GeoSolar & Aerotermia España

- 🌐 **Web oficial:** [**https://geosolar-espana.pages.dev/**](https://geosolar-espana.pages.dev/)
- 📦 **Repositorio de documentación:** [**github.com/naxetem/geosolar-espana**](https://github.com/naxetem/geosolar-espana)
- **Contenido:** Calculadoras técnicas de **Placas Solares Fotovoltaicas** (producción específica `kWh/kWp`, ángulo óptimo e impacto térmico NOCT) y **Aerotermia** (Grados-Día $HDD_{15}$, Zona Climática CTE y rendimiento estacional $SCOP$ a 35 °C y 55 °C) para los **465 municipios y 52 provincias** de España.

---

## 📄 Aviso Legal y Propiedad Intelectual

© **Huerto y Clima España** ([huerto-clima.pages.dev](https://huerto-clima.pages.dev/)). Todos los derechos reservados.
Este repositorio contiene únicamente la documentación metodológica pública y el directorio geográfico de acceso al portal web. El motor de cálculo agroclimático, las plantillas y el software de compilación son propiedad intelectual privada.
