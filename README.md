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

## 🗺️ Atlas Provincial de Huerto y Heladas (13 Provincias Activas)

| Provincia | Comunidad Autónoma | Enlace al Estudio Provincial |
| :--- | :--- | :--- |
| **A Coruña** | Galicia | [Ver 1 municipios de A Coruña](https://huerto-clima.pages.dev/provincias/a-coruna.html) |
| **Albacete** | Castilla-La Mancha | [Ver 1 municipios de Albacete](https://huerto-clima.pages.dev/provincias/albacete.html) |
| **Almería** | Andalucía | [Ver 1 municipios de Almería](https://huerto-clima.pages.dev/provincias/almeria.html) |
| **Burgos** | Castilla y León | [Ver 1 municipios de Burgos](https://huerto-clima.pages.dev/provincias/burgos.html) |
| **Ciudad Real** | Castilla-La Mancha | [Ver 1 municipios de Ciudad Real](https://huerto-clima.pages.dev/provincias/ciudad-real.html) |
| **Cuenca** | Castilla-La Mancha | [Ver 1 municipios de Cuenca](https://huerto-clima.pages.dev/provincias/cuenca.html) |
| **Córdoba** | Andalucía | [Ver 2 municipios de Córdoba](https://huerto-clima.pages.dev/provincias/cordoba.html) |
| **Guadalajara** | Castilla-La Mancha | [Ver 2 municipios de Guadalajara](https://huerto-clima.pages.dev/provincias/guadalajara.html) |
| **Madrid** | Comunidad de Madrid | [Ver 27 municipios de Madrid](https://huerto-clima.pages.dev/provincias/madrid.html) |
| **Málaga** | Andalucía | [Ver 5 municipios de Málaga](https://huerto-clima.pages.dev/provincias/malaga.html) |
| **Sevilla** | Andalucía | [Ver 4 municipios de Sevilla](https://huerto-clima.pages.dev/provincias/sevilla.html) |
| **Teruel** | Aragón | [Ver 1 municipios de Teruel](https://huerto-clima.pages.dev/provincias/teruel.html) |
| **Toledo** | Castilla-La Mancha | [Ver 3 municipios de Toledo](https://huerto-clima.pages.dev/provincias/toledo.html) |

---

## 🍅 Calendarios Municipales de Siembra y Heladas (50 Municipios)

| Municipio | Provincia | Altitud | Última Helada Segura (Cultivos Sensibles) | Periodo Libre de Heladas | Ficha Completa |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Madrid** | Madrid | `657 m` | 31 de marzo | `232 días` | [Ver calendario de Madrid](https://huerto-clima.pages.dev/municipios/madrid.html) |
| **Sevilla** | Sevilla | `14 m` | 18 de febrero | `306 días` | [Ver calendario de Sevilla](https://huerto-clima.pages.dev/municipios/sevilla.html) |
| **Málaga** | Málaga | `11 m` | Sin riesgo severo | `365 días` | [Ver calendario de Málaga](https://huerto-clima.pages.dev/municipios/malaga.html) |
| **Córdoba** | Córdoba | `106 m` | 25 de marzo | `228 días` | [Ver calendario de Córdoba](https://huerto-clima.pages.dev/municipios/cordoba.html) |
| **A Coruña** | A Coruña | `25 m` | 6 de enero | `359 días` | [Ver calendario de A Coruña](https://huerto-clima.pages.dev/municipios/a-coruna.html) |
| **Móstoles** | Madrid | `660 m` | 4 de abril | `218 días` | [Ver calendario de Móstoles](https://huerto-clima.pages.dev/municipios/mostoles.html) |
| **Almería** | Almería | `20 m` | Sin riesgo severo | `365 días` | [Ver calendario de Almería](https://huerto-clima.pages.dev/municipios/almeria.html) |
| **Alcalá de Henares** | Madrid | `588 m` | 22 de mayo | `153 días` | [Ver calendario de Alcalá de Henares](https://huerto-clima.pages.dev/municipios/alcala-de-henares.html) |
| **Leganés** | Madrid | `665 m` | 31 de marzo | `223 días` | [Ver calendario de Leganés](https://huerto-clima.pages.dev/municipios/leganes.html) |
| **Fuenlabrada** | Madrid | `664 m` | 31 de marzo | `223 días` | [Ver calendario de Fuenlabrada](https://huerto-clima.pages.dev/municipios/fuenlabrada.html) |
| **Getafe** | Madrid | `622 m` | 31 de marzo | `223 días` | [Ver calendario de Getafe](https://huerto-clima.pages.dev/municipios/getafe.html) |
| **Burgos** | Burgos | `859 m` | 12 de junio | `100 días` | [Ver calendario de Burgos](https://huerto-clima.pages.dev/municipios/burgos.html) |
| **Albacete** | Albacete | `686 m` | 22 de abril | `196 días` | [Ver calendario de Albacete](https://huerto-clima.pages.dev/municipios/albacete.html) |
| **Alcorcón** | Madrid | `711 m` | 4 de abril | `218 días` | [Ver calendario de Alcorcón](https://huerto-clima.pages.dev/municipios/alcorcon.html) |
| **Marbella** | Málaga | `27 m` | Sin riesgo severo | `365 días` | [Ver calendario de Marbella](https://huerto-clima.pages.dev/municipios/marbella.html) |
| **Dos Hermanas** | Sevilla | `42 m` | 18 de febrero | `306 días` | [Ver calendario de Dos Hermanas](https://huerto-clima.pages.dev/municipios/dos-hermanas.html) |
| **Torrejón de Ardoz** | Madrid | `585 m` | 22 de mayo | `153 días` | [Ver calendario de Torrejón de Ardoz](https://huerto-clima.pages.dev/municipios/torrejon-de-ardoz.html) |
| **Parla** | Madrid | `648 m` | 31 de marzo | `223 días` | [Ver calendario de Parla](https://huerto-clima.pages.dev/municipios/parla.html) |
| **Alcobendas** | Madrid | `669 m` | 24 de abril | `193 días` | [Ver calendario de Alcobendas](https://huerto-clima.pages.dev/municipios/alcobendas.html) |
| **Rivas-Vaciamadrid** | Madrid | `590 m` | 24 de abril | `185 días` | [Ver calendario de Rivas-Vaciamadrid](https://huerto-clima.pages.dev/municipios/rivas-vaciamadrid.html) |
| **Las Rozas de Madrid** | Madrid | `718 m` | 28 de abril | `174 días` | [Ver calendario de Las Rozas de Madrid](https://huerto-clima.pages.dev/municipios/las-rozas-de-madrid.html) |
| **San Sebastián de los Reyes** | Madrid | `672 m` | 24 de abril | `193 días` | [Ver calendario de San Sebastián de los Reyes](https://huerto-clima.pages.dev/municipios/san-sebastian-de-los-reyes.html) |
| **Mijas** | Málaga | `428 m` | 5 de marzo | `262 días` | [Ver calendario de Mijas](https://huerto-clima.pages.dev/municipios/mijas.html) |
| **Guadalajara** | Guadalajara | `708 m` | 1 de mayo | `178 días` | [Ver calendario de Guadalajara](https://huerto-clima.pages.dev/municipios/guadalajara.html) |
| **Pozuelo de Alarcón** | Madrid | `690 m` | 28 de abril | `174 días` | [Ver calendario de Pozuelo de Alarcón](https://huerto-clima.pages.dev/municipios/pozuelo-de-alarcon.html) |
| **Toledo** | Toledo | `529 m` | 1 de abril | `226 días` | [Ver calendario de Toledo](https://huerto-clima.pages.dev/municipios/toledo.html) |
| **Vélez-Málaga** | Málaga | `60 m` | Sin riesgo severo | `365 días` | [Ver calendario de Vélez-Málaga](https://huerto-clima.pages.dev/municipios/velez-malaga.html) |
| **Talavera de la Reina** | Toledo | `373 m` | 22 de abril | `198 días` | [Ver calendario de Talavera de la Reina](https://huerto-clima.pages.dev/municipios/talavera-de-la-reina.html) |
| **Valdemoro** | Madrid | `615 m` | 31 de marzo | `223 días` | [Ver calendario de Valdemoro](https://huerto-clima.pages.dev/municipios/valdemoro.html) |
| **Estepona** | Málaga | `19 m` | Sin riesgo severo | `365 días` | [Ver calendario de Estepona](https://huerto-clima.pages.dev/municipios/estepona.html) |
| **Alcalá de Guadaíra** | Sevilla | `46 m` | 5 de marzo | `277 días` | [Ver calendario de Alcalá de Guadaíra](https://huerto-clima.pages.dev/municipios/alcala-de-guadaira.html) |
| **Ciudad Real** | Ciudad Real | `628 m` | 4 de abril | `215 días` | [Ver calendario de Ciudad Real](https://huerto-clima.pages.dev/municipios/ciudad-real.html) |
| **Majadahonda** | Madrid | `743 m` | 28 de abril | `174 días` | [Ver calendario de Majadahonda](https://huerto-clima.pages.dev/municipios/majadahonda.html) |
| **Collado Villalba** | Madrid | `903 m` | 30 de abril | `180 días` | [Ver calendario de Collado Villalba](https://huerto-clima.pages.dev/municipios/collado-villalba.html) |
| **Boadilla del Monte** | Madrid | `689 m` | 28 de abril | `174 días` | [Ver calendario de Boadilla del Monte](https://huerto-clima.pages.dev/municipios/boadilla-del-monte.html) |
| **Aranjuez** | Madrid | `495 m` | 4 de mayo | `171 días` | [Ver calendario de Aranjuez](https://huerto-clima.pages.dev/municipios/aranjuez.html) |
| **Arganda del Rey** | Madrid | `618 m` | 24 de abril | `185 días` | [Ver calendario de Arganda del Rey](https://huerto-clima.pages.dev/municipios/arganda-del-rey.html) |
| **Pinto** | Madrid | `604 m` | 31 de marzo | `223 días` | [Ver calendario de Pinto](https://huerto-clima.pages.dev/municipios/pinto.html) |
| **Colmenar Viejo** | Madrid | `883 m` | 1 de mayo | `187 días` | [Ver calendario de Colmenar Viejo](https://huerto-clima.pages.dev/municipios/colmenar-viejo.html) |
| **Cuenca** | Cuenca | `946 m` | 3 de mayo | `172 días` | [Ver calendario de Cuenca](https://huerto-clima.pages.dev/municipios/cuenca.html) |
| **Tres Cantos** | Madrid | `710 m` | 1 de mayo | `178 días` | [Ver calendario de Tres Cantos](https://huerto-clima.pages.dev/municipios/tres-cantos.html) |
| **Mairena del Aljarafe** | Sevilla | `85 m` | 18 de febrero | `310 días` | [Ver calendario de Mairena del Aljarafe](https://huerto-clima.pages.dev/municipios/mairena-del-aljarafe.html) |
| **Lucena** | Córdoba | `485 m` | 22 de marzo | `236 días` | [Ver calendario de Lucena](https://huerto-clima.pages.dev/municipios/lucena.html) |
| **Teruel** | Teruel | `915 m` | 20 de mayo | `131 días` | [Ver calendario de Teruel](https://huerto-clima.pages.dev/municipios/teruel.html) |
| **Galapagar** | Madrid | `878 m` | 30 de abril | `180 días` | [Ver calendario de Galapagar](https://huerto-clima.pages.dev/municipios/galapagar.html) |
| **Azuqueca de Henares** | Guadalajara | `627 m` | 5 de mayo | `167 días` | [Ver calendario de Azuqueca de Henares](https://huerto-clima.pages.dev/municipios/azuqueca-de-henares.html) |
| **Illescas** | Toledo | `583 m` | 2 de abril | `219 días` | [Ver calendario de Illescas](https://huerto-clima.pages.dev/municipios/illescas.html) |
| **Villaviciosa de Odón** | Madrid | `650 m` | 4 de abril | `218 días` | [Ver calendario de Villaviciosa de Odón](https://huerto-clima.pages.dev/municipios/villaviciosa-de-odon.html) |
| **Paracuellos de Jarama** | Madrid | `688 m` | 19 de abril | `186 días` | [Ver calendario de Paracuellos de Jarama](https://huerto-clima.pages.dev/municipios/paracuellos-de-jarama.html) |
| **Villanueva de la Cañada** | Madrid | `652 m` | 18 de abril | `202 días` | [Ver calendario de Villanueva de la Cañada](https://huerto-clima.pages.dev/municipios/villanueva-de-la-canada.html) |

👉 **[Ver el Directorio Completo organizado por Provincias](./DIRECTORIO_MUNICIPIOS.md)**

---

## 📄 Aviso Legal y Propiedad Intelectual

© **Huerto y Clima España** ([huerto-clima.pages.dev](https://huerto-clima.pages.dev/)). Todos los derechos reservados.
Este repositorio contiene únicamente la documentación metodológica pública y el directorio geográfico de acceso al portal web. El motor de cálculo agroclimático, las plantillas y el software de compilación son propiedad intelectual privada.
