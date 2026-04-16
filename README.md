# Catholic Cardinals Data

List of Roman Catholic Cardinals in multiple formats: JSON, CSV, and XML.

## Download

To download the latest list of Cardinals, please go to the [releases page](https://github.com/ChrisVo/cardinals/releases).

**Available formats:**
- **JSON**: `cardinals.json` - Full structured data
- **CSV**: `cardinals.csv` - Spreadsheet-compatible format
- **XML**: `cardinals.xml` - XML structured format

## Automated Updates

This repository automatically scrapes cardinal data from Wikipedia **daily at midnight UTC**. When changes are detected:
- The `cardinals.json` file is updated
- A new release is created with the updated data
- Changes are logged in [CHANGELOG.md](CHANGELOG.md)

The workflow detects:
- **New Cardinals** - Recently appointed cardinals
- **Removed Cardinals** - Cardinals who have passed away or resigned
- **Modified Cardinals** - Changes to existing cardinal information (title, office, etc.)

An example of an JSON object:

```
    {
      "Rank": "1",
      "Name": "Giovanni Battista Re",
      "Country": "Italy",
      "Born": "30 January 1934",
      "Order": "CB",
      "Consistory": "21 February 2001",
      "Office": "Prefect emeritus of the Congregation for Bishops",
      "PapalConclaveEligible": false,
      "CreatedCardinalBy": "Pope John Paul II"
    }
```

---

## Requirements
- Python3+

## Usage

1. Clone this repository
2. Install dependencies

    `pip install -r requirements.txt`

3. Run script

    `python cardinal.py`

---
## Sources
[The data is scraped from the "list of cardinals" Wikipedia page](https://en.wikipedia.org/wiki/List_of_current_cardinals)

---

<!-- CARDINAL_LIST_START -->
## Complete List of Cardinals
Total: **243 cardinals**

- **Eligible to vote in Papal Conclave**: 121
- **Ineligible to vote** (over 80 years old): 122

| Rank | Name | Country | Born | Office |
|------|------|---------|------|--------|
| 1 | Giovanni Battista Re* | Italy | 30 January 1934 | Prefect emeritus of the Congregation for Bishops (Dean) |
| 2 | Leonardo Sandri* | Argentina | 18 November 1943 | Prefect emeritus of the Dicastery for the Eastern Churches (Vice Dean) |
| 3 | Francis Arinze* | Nigeria | 1 November 1932 | Prefect emeritus of the Congregation for Divine Worship and the Discipline of th |
| 4 | Tarcisio Bertone SDB* | Italy | 2 December 1934 | Secretary of State emeritus of His Holiness and Camerlengo emeritus of the Holy  |
| 5 | José Saraiva Martins CMF* | Portugal | 6 January 1932 | Prefect emeritus of the Congregation for the Causes of Saints |
| 6 | Pietro Parolin | Italy | 17 January 1955 | Secretary of State of His Holiness |
| 7 | Marc Ouellet PSS* | Canada | 8 June 1944 | Prefect emeritus of the Dicastery for Bishops |
| 8 | Fernando Filoni | Italy | 15 April 1946 | Grand Master of the Order of the Holy Sepulchre |
| 9 | Beniamino Stella* | Italy | 18 August 1941 | Prefect emeritus of the Congregation for the Clergy |
| 10 | Luis Antonio Tagle | Philippines | 21 June 1957 | Pro-Prefect of the Dicastery for Evangelization |
| 11 | Bechara Boutros al-Rahi OMM* | Lebanon | 25 February 1940 | Patriarch of Antioch(Maronite Church) |
| 12 | Louis Raphaël I Sako | Iraq | 4 July 1948 | Patriarch emeritus of Baghdad(Chaldean Church) |
| 13 | Michael Michai Kitbunchu* | Thailand | 25 January 1929 | Archbishop emeritus of Bangkok |
| 14 | Paul Poupard* | France | 30 August 1930 | President emeritus of the Pontifical Councils for Culture and for Interreligious |
| 15 | Friedrich Wetter* | Germany | 20 February 1928 | Archbishop emeritus of Munich and Freising |
| 16 | Nicolás de Jesús López Rodríguez* | Dominican Republic | 31 October 1936 | Archbishop emeritus of Santo Domingo |
| 17 | Roger Mahony* | United States | 27 February 1936 | Archbishop emeritus of Los Angeles |
| 18 | Camillo Ruini* | Italy | 19 February 1931 | Vicar General emeritus for Rome and Archpriest emeritus of the Papal Basilica of |
| 19 | Julius Darmaatmadja SJ* | Indonesia | 20 December 1934 | Archbishop emeritus of Jakarta |
| 20 | Emmanuel Wamala* | Uganda | 15 December 1926 | Archbishop emeritus of Kampala |
| 21 | Adam Maida* | United States | 18 March 1930 | Archbishop emeritus of Detroit |
| 22 | Vinko Puljić* | Bosnia and Herzegovina | 8 September 1945 | Archbishop emeritus of Vrhbosna |
| 23 | Juan Sandoval Íñiguez* | Mexico | 28 March 1933 | Archbishop emeritus of Guadalajara |
| 24 | James Stafford* | United States | 26 July 1932 | Major Penitentiary emeritus |
| 25 | Salvatore De Giorgi* | Italy | 6 September 1930 | Archbishop emeritus of Palermo |
| 26 | Antonio María Rouco Varela* | Spain | 20 August 1936 | Archbishop emeritus of Madrid |
| 27 | Christoph Schönborn OP* | Austria[d] | 22 January 1945 | Archbishop emeritus of Vienna |
| 28 | Norberto Rivera Carrera* | Mexico | 6 June 1942 | Archbishop emeritus of Mexico |
| 29 | Jānis Pujats* | Latvia | 14 November 1930 | Archbishop emeritus of Riga |
| 30 | Crescenzio Sepe* | Italy | 2 June 1943 | Archbishop emeritus of Naples |
| 31 | Walter Kasper* | Germany | 5 March 1933 | President emeritus of the Pontifical Council for Promoting Christian Unity |
| 32 | Audrys Bačkis* | Lithuania | 1 February 1937 | Archbishop emeritus of Vilnius |
| 33 | Francisco Javier Errázuriz Ossa ISch* | Chile | 5 September 1933 | Archbishop emeritus of Santiago de Chile |
| 34 | Wilfrid Napier OFM* | South Africa | 8 March 1941 | Archbishop emeritus of Durban |
| 35 | Óscar Rodríguez Maradiaga SDB* | Honduras | 29 December 1942 | Archbishop emeritus of Tegucigalpa and Coordinator emeritus of the Council of Ca |
| 36 | Juan Luis Cipriani Thorne* | Peru | 28 December 1943 | Archbishop emeritus of Lima |
| 37 | Julián Herranz Casado* | Spain | 31 March 1930 | President emeritus of the Pontifical Council for Legislative Texts |
| 38 | Angelo Scola* | Italy | 7 November 1941 | Archbishop emeritus of Milan |
| 39 | Anthony Olubunmi Okogie* | Nigeria | 16 June 1936 | Archbishop emeritus of Lagos |
| 40 | Gabriel Zubeir Wako* | Sudan | 27 February 1941 | Archbishop emeritus of Khartoum |
| 41 | Justin Rigali* | United States | 19 April 1935 | Archbishop emeritus of Philadelphia |
| 42 | Ennio Antonelli* | Italy | 18 November 1936 | President emeritus of the Pontifical Council for the Family |
| 43 | Peter Turkson | Ghana | 11 October 1948 | Chancellor of the Pontifical Academy of Sciences and the Pontifical Academy of S |
| 44 | Josip Bozanić | Croatia | 20 March 1949 | Archbishop emeritus of Zagreb |
| 45 | Philippe Barbarin | France | 17 October 1950 | Archbishop emeritus of Lyon |
| 46 | Péter Erdő | Hungary | 25 June 1952 | Archbishop of Esztergom–Budapest |
| 47 | Franc Rodé CM* | Slovenia | 23 September 1934 | Prefect emeritus of the Congregation for Institutes of Consecrated Life and Soci |
| 48 | Agostino Vallini* | Italy | 17 April 1940 | Pontifical Legate emeritus for the Basilicas of Saint Francis and Saint Mary of  |
| 49 | Gaudencio Borbon Rosales* | Philippines | 10 August 1932 | Archbishop emeritus of Manila |
| 50 | Jean-Pierre Ricard* | France | 25 September 1944 | Archbishop emeritus of Bordeaux |
| 51 | Antonio Cañizares Llovera* | Spain | 15 October 1945 | Archbishop emeritus of Valencia |
| 52 | Seán Patrick O'Malley OFMCap* | United States | 29 June 1944 | Archbishop emeritus of Boston and President emeritus of the Pontifical Commissio |
| 53 | Stanisław Dziwisz* | Poland | 27 April 1939 | Archbishop emeritus of Kraków |
| 54 | Joseph Zen Ze-kiun SDB* | China(Hong Kong)[f] | 13 January 1932 | Bishop emeritus of Hong Kong |
| 55 | Giovanni Lajolo* | Italy | 3 January 1935 | President emeritus of the Pontifical Commission for Vatican City State |
| 56 | Angelo Comastri* | Italy | 17 September 1943 | Vicar General emeritus for Vatican City, Archpriest emeritus of the Papal Basili |
| 57 | Stanisław Ryłko* | Poland | 4 July 1945 | Archpriest emeritus of the Papal Basilica of Saint Mary Major |
| 58 | Raffaele Farina SDB* | Italy | 24 September 1933 | Archivist and Librarian emeritus of the Holy Roman Church |
| 59 | Seán Brady* | Ireland[g] | 16 August 1939 | Archbishop emeritus of Armagh |
| 60 | Lluís Martínez i Sistach* | Spain | 29 April 1937 | Archbishop emeritus of Barcelona |
| 61 | Angelo Bagnasco* | Italy | 14 January 1943 | Archbishop emeritus of Genoa |
| 62 | Théodore-Adrien Sarr* | Senegal | 28 November 1936 | Archbishop emeritus of Dakar |
| 63 | Oswald Gracias* | India | 24 December 1944 | Archbishop emeritus of Bombay |
| 64 | Francisco Robles Ortega | Mexico | 2 March 1949 | Archbishop of Guadalajara |
| 65 | Daniel DiNardo | United States | 23 May 1949 | Archbishop emeritus of Galveston–Houston |
| 66 | Odilo Scherer | Brazil | 21 September 1949 | Archbishop of São Paulo |
| 67 | John Njue* | Kenya | 1 January 1946[h] | Archbishop emeritus of Nairobi |
| 68 | Robert Sarah* | Guinea | 15 June 1945 | Prefect emeritus of the Congregation for Divine Worship and the Discipline of th |
| 69 | Francesco Monterisi* | Italy | 28 May 1934 | Archpriest emeritus of the Papal Basilica of Saint Paul Outside the Walls |
| 70 | Raymond Leo Burke | United States | 30 June 1948 | Patron emeritus of the Sovereign Military Order of Malta |
| 71 | Kurt Koch | Switzerland | 15 March 1950 | Prefect of the Dicastery for Promoting Christian Unity |
| 72 | Mauro Piacenza* | Italy | 15 September 1944 | Major Penitentiary emeritus |
| 73 | Gianfranco Ravasi* | Italy | 18 October 1942 | President emeritus of the Pontifical Council for Culture |
| 74 | Paolo Romeo* | Italy | 20 February 1938 | Archbishop emeritus of Palermo |
| 75 | Donald Wuerl* | United States | 12 November 1940 | Archbishop emeritus of Washington |
| 76 | Raymundo Damasceno Assis* | Brazil | 15 February 1937 | Archbishop emeritus of Aparecida |
| 77 | Kazimierz Nycz | Poland | 1 February 1950 | Archbishop emeritus of Warsaw |
| 78 | Malcolm Ranjith | Sri Lanka | 15 November 1947 | Archbishop of Colombo |
| 79 | Reinhard Marx | Germany | 21 September 1953 | Archbishop of Munich and Freising and Coordinator of the Council for the Economy |
| 80 | Walter Brandmüller* | Germany | 5 January 1929 | President emeritus of the Pontifical Committee for Historical Sciences |
| 81 | Manuel Monteiro de Castro* | Portugal | 29 March 1938 | Major Penitentiary emeritus |
| 82 | Santos Abril y Castelló* | Spain | 21 September 1935 | Archpriest emeritus of the Papal Basilica of Saint Mary Major |
| 83 | Antonio Maria Vegliò* | Italy | 3 February 1938 | President emeritus of the Pontifical Council for the Pastoral Care of Migrants a |
| 84 | Giuseppe Bertello* | Italy | 1 October 1942 | President emeritus of the Pontifical Commission for Vatican City State |
| 85 | Francesco Coccopalmerio* | Italy | 6 March 1938 | President emeritus of the Pontifical Council for Legislative Texts |
| 86 | João Braz de Aviz | Brazil | 24 April 1947 | Prefect emeritus of the Dicastery for Institutes of Consecrated Life and Societi |
| 87 | Edwin Frederick O'Brien* | United States | 8 April 1939 | Grand Master emeritus of the Order of the Holy Sepulchre |
| 88 | Domenico Calcagno* | Italy | 3 February 1943 | President emeritus of the Administration of the Patrimony of the Apostolic See |
| 89 | Giuseppe Versaldi* | Italy | 30 July 1943 | Prefect emeritus of the Congregation for Catholic Education |
| 90 | George Alencherry* | India | 19 April 1945 | Major Archbishop emeritus of Ernakulam–Angamaly(Syro-Malabar Church) |
| 91 | Thomas Collins | Canada | 16 January 1947 | Archbishop emeritus of Toronto |
| 92 | Wim Eijk | Netherlands | 22 June 1953 | Archbishop of Utrecht |
| 93 | Giuseppe Betori | Italy | 25 February 1947 | Archbishop emeritus of Florence |
| 94 | Timothy M. Dolan | United States | 6 February 1950 | Archbishop emeritus of New York |
| 95 | Rainer Woelki | Germany | 18 August 1956 | Archbishop of Cologne |
| 96 | John Tong Hon* | China(Hong Kong)[f] | 31 July 1939 | Bishop emeritus of Hong Kong |
| 97 | James Michael Harvey | United States | 20 October 1949 | Archpriest of the Papal Basilica of Saint Paul Outside the Walls |
| 98 | Baselios Cleemis | India | 15 June 1959 | Major Archbishop of Trivandrum(Syro-Malankara Church) |
| 99 | John Onaiyekan* | Nigeria | 29 January 1944 | Archbishop emeritus of Abuja |
| 100 | Rubén Salazar Gómez* | Colombia | 22 September 1942 | Archbishop emeritus of Bogotá |
| 101 | Lorenzo Baldisseri* | Italy | 29 September 1940 | Secretary-General emeritus of the Synod of Bishops |
| 102 | Gerhard Ludwig Müller | Germany | 31 December 1947 | Prefect emeritus of the Congregation for the Doctrine of the Faith |
| 103 | Vincent Nichols* | United Kingdom | 8 November 1945 | Archbishop emeritus of Westminster |
| 104 | Leopoldo Brenes | Nicaragua | 7 March 1949 | Archbishop of Managua |
| 105 | Gérald Lacroix ISPX | Canada | 27 July 1957 | Archbishop of Quebec |
| 106 | Jean-Pierre Kutwa* | Ivory Coast | 22 December 1945 | Archbishop emeritus of Abidjan |
| 107 | Orani João Tempesta OCist | Brazil | 23 June 1950 | Archbishop of São Sebastião do Rio de Janeiro |
| 108 | Gualtiero Bassetti* | Italy | 7 April 1942 | Archbishop emeritus of Perugia–Città della Pieve |
| 109 | Mario Aurelio Poli | Argentina | 29 November 1947 | Archbishop emeritus of Buenos Aires |
| 110 | Andrew Yeom Soo-jung* | South Korea | 5 December 1943 | Archbishop emeritus of Seoul |
| 111 | Ricardo Ezzati SDB* | Chile[i] | 7 January 1942 | Archbishop emeritus of Santiago de Chile |
| 112 | Philippe Ouédraogo* | Burkina Faso | 31 December 1945[j] | Archbishop emeritus of Ouagadougou |
| 113 | Orlando Quevedo OMI* | Philippines | 11 March 1939 | Archbishop emeritus of Cotabato |
| 114 | Chibly Langlois | Haiti | 29 November 1958 | Bishop of Les Cayes |
| 115 | Manuel Clemente | Portugal | 16 July 1948 | Patriarch emeritus of Lisbon |
| 116 | Berhaneyesus Demerew Souraphiel CM | Ethiopia | 14 July 1948 | Archbishop of Addis Abeba(Ethiopian Church) |
| 117 | John Dew | New Zealand | 5 May 1948 | Archbishop emeritus of Wellington |
| 118 | Pierre Nguyễn Văn Nhơn* | Vietnam | 1 April 1938 | Archbishop emeritus of Hanoi |
| 119 | Alberto Suárez Inda* | Mexico | 30 January 1939 | Archbishop emeritus of Morelia |
| 120 | Charles Maung Bo SDB | Myanmar | 29 October 1948 | Archbishop of Yangon |
| 121 | Kriengsak Kovitvanit | Thailand | 27 June 1949 | Archbishop emeritus of Bangkok |
| 122 | Francesco Montenegro | Italy | 22 May 1946 | Archbishop emeritus of Agrigento |
| 123 | Daniel Sturla SDB | Uruguay | 4 July 1959 | Archbishop of Montevideo |
| 124 | Ricardo Blázquez* | Spain | 13 April 1942 | Archbishop emeritus of Valladolid |
| 125 | José Luis Lacunza Maestrojuán OAR* | Panama[k] | 24 February 1944 | Bishop emeritus of David |
| 126 | Arlindo Gomes Furtado | Cape Verde | 15 November 1949 | Bishop emeritus of Santiago de Cabo Verde |
| 127 | Soane Patita Paini Mafi | Tonga | 19 December 1961 | Bishop of Tonga |
| 128 | Luis Héctor Villalba* | Argentina | 11 October 1934 | Archbishop emeritus of Tucumán |
| 129 | Júlio Duarte Langa* | Mozambique | 27 October 1927 | Bishop emeritus of Xai-Xai |
| 130 | Dieudonné Nzapalainga CSSp | Central African Republic | 14 March 1967 | Archbishop of Bangui |
| 131 | Carlos Osoro Sierra* | Spain | 16 May 1945 | Archbishop emeritus of Madrid |
| 132 | Sérgio da Rocha | Brazil | 21 October 1959 | Archbishop of São Salvador da Bahia |
| 133 | Blase J. Cupich | United States | 19 March 1949 | Archbishop of Chicago |
| 134 | Patrick D'Rozario CSC* | Bangladesh | 1 October 1943 | Archbishop emeritus of Dhaka |
| 135 | Baltazar Enrique Porras Cardozo* | Venezuela | 10 October 1944 | Archbishop emeritus of Caracas |
| 136 | Jozef De Kesel | Belgium | 17 June 1947 | Archbishop emeritus of Mechelen–Brussels |
| 137 | Maurice Piat CSSp* | Mauritius | 19 July 1941 | Bishop emeritus of Port-Louis |
| 138 | Carlos Aguiar Retes | Mexico | 9 January 1950 | Archbishop of Mexico |
| 139 | John Ribat MSC | Papua New Guinea | 9 February 1957 | Archbishop of Port Moresby |
| 140 | Joseph W. Tobin CSsR | United States | 3 May 1952 | Archbishop of Newark |
| 141 | Jean Zerbo* | Mali | 27 December 1943 | Archbishop emeritus of Bamako |
| 142 | Juan José Omella | Spain | 21 April 1946 | Archbishop of Barcelona |
| 143 | Anders Arborelius OCD | Sweden | 24 September 1949 | Bishop of Stockholm |
| 144 | Louis-Marie Ling Mangkhanekhoun IVD* | Laos | 8 April 1944 | Apostolic Vicar emeritus of Vientiane |
| 145 | Gregorio Rosa Chávez* | El Salvador | 3 September 1942 | Auxiliary Bishop emeritus of San Salvador |
| 146 | Angelo De Donatis | Italy | 4 January 1954 | Major Penitentiary |
| 147 | Joseph Coutts* | Pakistan | 21 July 1945 | Archbishop emeritus of Karachi |
| 148 | António Marto | Portugal | 5 May 1947 | Bishop emeritus of Leiria–Fátima |
| 149 | Pedro Barreto SJ* | Peru | 12 February 1944 | Archbishop emeritus of Huancayo |
| 150 | Désiré Tsarahazana | Madagascar | 13 June 1954 | Archbishop of Toamasina |
| 151 | Giuseppe Petrocchi | Italy | 19 August 1948 | Archbishop emeritus of L'Aquila |
| 152 | Thomas Aquino Manyo Maeda | Japan | 3 March 1949 | Archbishop of Osaka–Takamatsu |
| 153 | Toribio Ticona Porco* | Bolivia | 25 April 1937 | Bishop Prelate emeritus of Corocoro |
| 154 | Ignatius Suharyo Hardjoatmodjo | Indonesia | 9 July 1950 | Archbishop of Jakarta |
| 155 | Juan García Rodríguez | Cuba | 11 July 1948 | Archbishop of San Cristóbal de la Habana |
| 156 | Fridolin Ambongo Besungu OFMCap | Democratic Republic of the Congo | 24 January 1960 | Archbishop of Kinshasa |
| 157 | Jean-Claude Hollerich SJ | Luxembourg | 9 August 1958 | Archbishop of Luxembourg |
| 158 | Álvaro Leonel Ramazzini Imeri | Guatemala | 16 July 1947 | Bishop of Huehuetenango |
| 159 | Matteo Zuppi | Italy | 11 October 1955 | Archbishop of Bologna |
| 160 | Cristóbal López Romero SDB | Morocco[l] | 19 May 1952 | Archbishop of Rabat |
| 161 | Sigitas Tamkevičius SJ* | Lithuania | 7 November 1938 | Archbishop emeritus of Kaunas |
| 162 | Antoine Kambanda | Rwanda | 10 November 1958 | Archbishop of Kigali |
| 163 | Wilton Daniel Gregory | United States | 7 December 1947 | Archbishop emeritus of Washington |
| 164 | Jose Advincula OP | Philippines | 30 March 1952 | Archbishop of Manila |
| 165 | Celestino Aós Braco OFMCap* | Chile[m] | 6 April 1945 | Archbishop emeritus of Santiago de Chile |
| 166 | Augusto Paolo Lojudice | Italy | 1 July 1964 | Archbishop of Siena–Colle di Val d'Elsa–Montalcino and Bishop of Montepulciano–C |
| 167 | Felipe Arizmendi Esquivel* | Mexico | 1 May 1940 | Bishop emeritus of San Cristóbal de Las Casas |
| 168 | Jean-Marc Aveline | France | 26 December 1958 | Archbishop of Marseille |
| 169 | Peter Okpaleke | Nigeria | 1 March 1963 | Bishop of Ekwulobia |
| 170 | Leonardo Ulrich Steiner OFM | Brazil | 6 November 1950 | Archbishop of Manaus |
| 171 | Filipe Neri Ferrão | India | 20 January 1953 | Archbishop of Goa and Daman and Patriarch of the East Indies |
| 172 | Robert W. McElroy | United States | 5 February 1954 | Archbishop of Washington |
| 173 | Virgílio do Carmo da Silva SDB | East Timor | 27 November 1967 | Archbishop of Díli |
| 174 | Oscar Cantoni | Italy | 1 September 1950 | Bishop of Como |
| 175 | Anthony Poola | India | 15 November 1961 | Archbishop of Hyderabad |
| 176 | Paulo Cezar Costa | Brazil | 20 July 1967 | Archbishop of Brasília |
| 177 | William Goh | Singapore | 25 June 1957 | Archbishop of Singapore |
| 178 | Adalberto Martínez Flores | Paraguay | 8 July 1951 | Archbishop of Asunción |
| 179 | Giorgio Marengo IMC | Mongolia[n] | 7 June 1974 | Apostolic Prefect of Ulaanbaatar |
| 180 | Jorge Enrique Jiménez Carvajal CJM* | Colombia | 29 March 1942 | Archbishop emeritus of Cartagena |
| 181 | Arrigo Miglio* | Italy | 18 July 1942 | Archbishop emeritus of Cagliari |
| 182 | Pierbattista Pizzaballa OFM | Jerusalem[o] | 21 April 1965 | Latin Patriarch of Jerusalem |
| 183 | Stephen Brislin | South Africa | 24 September 1956 | Archbishop of Johannesburg |
| 184 | Ángel Sixto Rossi SJ | Argentina | 11 August 1958 | Archbishop of Córdoba |
| 185 | Luis José Rueda Aparicio | Colombia | 3 March 1962 | Archbishop of Bogotá |
| 186 | Grzegorz Ryś | Poland | 9 February 1964 | Archbishop of Kraków |
| 187 | Stephen Ameyu Martin Mulla | South Sudan | 10 January 1964 | Archbishop of Juba |
| 188 | José Cobo Cano | Spain | 20 September 1965 | Archbishop of Madrid |
| 189 | Protase Rugambwa | Tanzania | 31 May 1960 | Archbishop of Tabora |
| 190 | Sebastian Francis | Malaysia | 11 November 1951 | Bishop of Penang |
| 191 | Stephen Chow Sau-yan SJ | China(Hong Kong)[f] | 7 August 1959 | Bishop of Hong Kong |
| 192 | François-Xavier Bustillo OFMConv | France[p] | 23 November 1968 | Bishop of Ajaccio |
| 193 | Américo Aguiar | Portugal | 12 December 1973 | Bishop of Setúbal |
| 194 | Diego Rafael Padrón Sánchez* | Venezuela | 17 May 1939 | Archbishop emeritus of Cumaná |
| 195 | Carlos Castillo Mattasoglio | Peru | 28 February 1950 | Archbishop of Lima |
| 196 | Vicente Bokalic Iglic CM | Argentina | 11 June 1952 | Archbishop of Santiago del Estero |
| 197 | Luis Cabrera Herrera OFM | Ecuador | 11 October 1955 | Archbishop of Guayaquil |
| 198 | Fernando Chomalí Garib | Chile | 10 March 1957 | Archbishop of Santiago de Chile |
| 199 | Tarcisio Isao Kikuchi SVD | Japan | 1 November 1958 | Archbishop of Tokyo |
| 200 | Pablo Virgilio David | Philippines | 2 March 1959 | Bishop of Kalookan |
| 201 | Ladislav Nemet SVD | Serbia[q] | 7 September 1956 | Archbishop of Belgrade |
| 202 | Jaime Spengler OFM | Brazil | 6 September 1960 | Archbishop of Porto Alegre |
| 203 | Ignace Bessi Dogbo | Ivory Coast | 17 August 1961 | Archbishop of Abidjan |
| 204 | Jean-Paul Vesco OP | Algeria[r] | 10 March 1962 | Archbishop of Algiers |
| 205 | Dominique Mathieu OFMConv | Iran[s] | 13 June 1963 | Archbishop of Tehran–Isfahan |
| 206 | Roberto Repole | Italy | 29 January 1967 | Archbishop of Turin and Bishop of Susa |
| 207 | Baldassare Reina | Italy | 26 November 1970 | Vicar General for Rome and Archpriest of the Papal Basilica of Saint John Latera |
| 208 | Frank Leo | Canada | 30 June 1971 | Archbishop of Toronto |
| 209 | Mykola Bychok CSsR | Australia[t] | 13 February 1980 | Eparch of Saints Peter and Paul of Melbourne(Ukrainian Greek Church) |
| 210 | Domenico Battaglia | Italy | 20 January 1963 | Archbishop of Naples |
| 211 | Dominique Mamberti | France | 7 March 1952 | Prefect of the Supreme Tribunal of the Apostolic Signatura |
| 212 | Mario Zenari* | Italy | 5 January 1946 | Apostolic Nuncio emeritus |
| 213 | Kevin Farrell | United States[u] | 2 September 1947 | Prefect of the Dicastery for the Laity, Family and Life |
| 214 | Ernest Simoni* | Albania | 18 October 1928 | Priest of the Archdiocese of Shkodër–Pult |
| 215 | Luis Ladaria Ferrer SJ* | Spain | 19 April 1944 | Prefect emeritus of the Dicastery for the Doctrine of the Faith |
| 216 | Giovanni Angelo Becciu[w]* | Italy | 2 June 1948 | Prefect emeritus of the Congregation for the Causes of Saints |
| 217 | Konrad Krajewski | Poland | 25 November 1963 | Archbishop of Łódź |
| 218 | Aquilino Bocos Merino CMF* | Spain | 17 May 1938 | Superior General emeritus of the Missionary Sons of the Immaculate Heart of Mary |
| 219 | José Tolentino de Mendonça | Portugal | 15 December 1965 | Prefect of the Dicastery for Culture and Education |
| 220 | Michael Czerny SJ | Canada[x] | 18 July 1946 | Prefect of the Dicastery for Promoting Integral Human Development |
| 221 | Michael Fitzgerald MAfr* | United Kingdom | 17 August 1937 | Apostolic Nuncio emeritus |
| 222 | Mario Grech | Malta | 20 February 1957 | Secretary-General of the Synod of Bishops |
| 223 | Marcello Semeraro | Italy | 22 December 1947 | Prefect of the Dicastery for the Causes of Saints |
| 224 | Mauro Gambetti OFMConv | Italy | 27 October 1965 | Vicar General for Vatican City, Archpriest of the Papal Basilica of Saint Peter  |
| 225 | Silvano Maria Tomasi CS* | Italy | 12 October 1940 | Special Delegate to the Sovereign Military Order of Malta |
| 226 | Raniero Cantalamessa OFMCap* | Italy | 22 July 1934 | Preacher emeritus of the Papal Household |
| 227 | Enrico Feroci* | Italy | 27 August 1940 | Pastor of the Shrine of Our Lady of Divine Love in Castel di Leva, Rome |
| 228 | Arthur Roche | United Kingdom | 6 March 1950 | Prefect of the Dicastery for Divine Worship and the Discipline of the Sacraments |
| 229 | Lazarus You Heung-sik | South Korea | 17 November 1951 | Prefect of the Dicastery for the Clergy |
| 230 | Fernando Vérgez Alzaga LC* | Spain | 1 March 1945 | President emeritus of the Pontifical Commission for Vatican City State |
| 231 | Gianfranco Ghirlanda SJ* | Italy | 5 July 1942 | Patron of the Sovereign Military Order of Malta |
| 232 | Fortunato Frezza* | Italy | 6 February 1942 | Canon of the Chapter of the Papal Basilica of Saint Peter |
| 233 | Claudio Gugerotti | Italy | 7 October 1955 | Prefect of the Dicastery for the Eastern Churches |
| 234 | Víctor Manuel Fernández | Argentina | 18 July 1962 | Prefect of the Dicastery for the Doctrine of the Faith |
| 235 | Emil Paul Tscherrig | Switzerland | 3 February 1947 | Apostolic Nuncio emeritus |
| 236 | Christophe Pierre* | France | 30 January 1946 | Apostolic Nuncio emeritus |
| 237 | Ángel Fernández Artime SDB | Spain | 21 August 1960 | Pro-Prefect of the Dicastery for Institutes of Consecrated Life and Societies of |
| 238 | Agostino Marchetto* | Italy | 28 August 1940 | Secretary emeritus of the Pontifical Council for the Pastoral Care of Migrants a |
| 239 | Angelo Acerbi* | Italy | 23 September 1925 | Apostolic Nuncio emeritus |
| 240 | Rolandas Makrickas | Lithuania | 31 January 1972 | Archpriest of the Papal Basilica of Saint Mary Major |
| 241 | Timothy Radcliffe OP* | United Kingdom | 22 August 1945 | Master emeritus of the Order of Preachers |
| 242 | Fabio Baggio CS | Italy | 15 January 1965 | Undersecretary of the Migrants and Refugees Section of the Dicastery for Promoti |
| 243 | George Koovakad | India | 11 August 1973 | Prefect of the Dicastery for Interreligious Dialogue |

*\* Cardinals over 80 years old are ineligible to vote in a papal conclave*

<!-- CARDINAL_LIST_END -->