# EJERCICIOS DE APRENDIZAJE
## Ejercicio_Extra_1

Archivo EMR: 

##Abrir el script de la base de datos llamada “nba.sql” y ejecutarlo para crear todas las tablas e
insertar datos en las mismas. A continuación, generar el modelo de entidad relación. Deberá
obtener un diagrama de entidad relación igual al que se muestra a continuación:

### 1. Mostrar el nombre de todos los jugadores ordenados alfabéticamente.
```
SELECT Nombre AS "Nombre Jugadores"  FROM jugadores ORDER BY Nombre ASC;
+----------------------+
| Nombre Jugadores     |
+----------------------+
| Aaron Brooks         |
| Aaron Gray           |
| Aaron Mckie          |
| Acie Law             |
| Adam Morrison        |
| Adonal Foyle         |
| Adrian Griffin       |
| Al Harrington        |
| Al Horford           |
| Al Jefferson         |
| al thornton          |
| Alando Tucker        |
| Aleksandar Pavlovic  |
| Alexander Johnson    |
| Allen Iverson        |
| Alonzo Mourning      |
| Amare Stoudemire     |
| Amir Johnson         |
| Anderson Varejao     |
| Andray Blatche       |
| Andre Brown          |
| Andre Iguodala       |
| Andre Miller         |
| Andre Owens          |
| Andrea Bargnani      |
| Andrei Kirilenko     |
| Andres Nocioni       |
| Andrew Bouqt         |
| Andrew Bynum         |
| Andris Biedrns       |
| Antawn Jamison       |
| Anthony Carter       |
| Anthony Johnson      |
| Anthony Parker       |
| Antoine Walker       |
| Antoine Wright       |
| Antonio Daniels      |
| Antonio McDyess      |
| Arron Afflalo        |
| Austin Croshere      |
| Awvee Store          |
| Baron Davis          |
| Ben Gordon           |
| Ben Wallace          |
| Beno Udrih           |
| Blake Ahearn         |
| Bobby Jackson        |
| Bobby Jones          |
| Bobby Simmons        |
| Bonzi Wells          |
| Boris Diaw           |
| Bostjan Nachbar      |
| Brad Miller          |
| Brandan Wright       |
| Brandon Bass         |
| Brandon Roy          |
| Brendan Haywood      |
| Brent Barry          |
| Brevin Knight        |
| Brian Cardinal       |
| Brian Cook           |
| Brian Scalabrine     |
| Brian Scalabrine     |
| Brian Skinner        |
| Bruce Bowen          |
| C.J. Miles           |
| C.J. Watson          |
| Calvin Booth         |
| Carl Landry          |
| Carlos Arroyo        |
| Carlos Boozer        |
| Carlos Delfino       |
| Carmelo Anthony      |
| Caron Butler         |
| Casey Jacobsen       |
| Cedric Simmons       |
| Channing Frye        |
| Charlie Bell         |
| Charlie Villanueva   |
| Chauncey Billups     |
| Cheikh Samb          |
| Chris Andersen       |
| Chris Duhon          |
| Chris Kaman          |
| Chris Mihm           |
| Chris Paul           |
| Chris Quinn          |
| Chris Richard        |
| Chris Wilcox         |
| Chuck Hayes          |
| Chucky Atkins        |
| Coby Karl            |
| Corey Brever         |
| Corey Maggette       |
| Craig Smith          |
| Cuttino Mobley       |
| D.J. Strawberry      |
| Daequan Cook         |
| Damien Wilkins       |
| Damon Jones          |
| Damon Stoudamire     |
| Dan Dickau           |
| Dan Gadzuric         |
| Daniel Gibson        |
| Danny Granger        |
| Darius Miles         |
| Darius Songaila      |
| Darko Milicic        |
| Darrel Armstrong     |
| David Harrison       |
| David Lee            |
| David West           |
| Delonte West         |
| Demetris Nichols     |
| Derek Anderson       |
| Derek Fisher         |
| Deron Williams       |
| DeSagana Diop        |
| DeShawn Stevenson    |
| Desmond Mason        |
| Devean George        |
| Devin Brown          |
| Devin Harris         |
| Didier Ilunga-Mbenga |
| Dikembre Mutombo     |
| Dirk Nowitzki        |
| Dominic McGuire      |
| Donyell Marshall     |
| Dorell Wright        |
| Drew Gooden          |
| Dwayne Jones         |
| Dwight Howard        |
| Dwyane Wade          |
| Earl Barron          |
| Earl Boykins         |
| Earl Watson          |
| Eddie House          |
| Eddie Jones          |
| Eddy Curry           |
| Eduardo Najera       |
| Elton brand          |
| Emeka Okafor         |
| Eric Piatkowski      |
| Eric Snow            |
| Erick Dampier        |
| Etan Thomas          |
| Fabricio Oberto      |
| Francisco Elson      |
| Francisco Garcia     |
| Fred Jones           |
| Gabe Pruitt          |
| Gerald Wallace       |
| Gilbert Arenas       |
| Glen Davis           |
| Gordan Giricek       |
| Grant Hill           |
| Greg Buckner         |
| Greg Oden            |
| Hakim Warrick        |
| Hedo Turkoglu        |
| Herbert Hill         |
| Hilton Armstrong     |
| Ian Mahinmi          |
| Ike Diogu            |
| Ime Udoka            |
| Ira Newble           |
| J.J.Redick           |
| Jacque Vaughn        |
| Jake Voskuhl         |
| Jamaal Magloire      |
| Jamaal Tinsley       |
| Jamal Crawford       |
| Jamario Moon         |
| James Augustine      |
| James Jones          |
| James Posey          |
| JamesOn Curry        |
| Jammer Nelson        |
| Jannero Pargo        |
| Jared Dudley         |
| Jared Jeffries       |
| Jarrett Jack         |
| Jarron Collins       |
| Jarvis Hayes         |
| Jason Collins        |
| Jason Hart           |
| Jason Kapono         |
| Jason Kidd           |
| Jason Maxiell        |
| Jason Richardson     |
| Jason Smith          |
| Jason Terry          |
| Jason Williams       |
| Javaris Crittenton   |
| Jeff Foster          |
| Jeff Green           |
| Jeremy Richardson    |
| Jermaine O'Neal      |
| Jermareo Davidson    |
| Jerome James         |
| Jerry Stackhouse     |
| Joakin Noah          |
| Joe Johnson          |
| Joe Smith            |
| joel Anthony         |
| Joel Przybilla       |
| Joey Graham          |
| Johan Petro          |
| Jordan Farmar        |
| Jorge Garbajosa      |
| Jose Barea           |
| Jose Calderon        |
| Josh Boone           |
| Josh Childress       |
| Josh Howard          |
| Josh McRoberts       |
| Josh Powell          |
| Josh Smith           |
| JR Smith             |
| Juan Carlos Navarro  |
| Juan Dixon           |
| Julian Wright        |
| Juwan Howard         |
| Kareem Rush          |
| Keith Bogans         |
| Keith Van Horn       |
| Kelenna Azubuike     |
| Kendrick Perkins     |
| Keny Thomas          |
| Kenyon Dooling       |
| Kenyon Martin        |
| Kevin Durant         |
| Kevin Garnett        |
| Kevin Martin         |
| Kevin Ollie          |
| Kirk Hinrich         |
| Kirk Snyder          |
| Kobe Bryant          |
| Kosta Perovic        |
| Kris Humphries       |
| Kurt Thomas          |
| Kwame Brown          |
| Kyle Korver          |
| Kyle Lowry           |
| Kyrylo Fesenko       |
| Lamar Odom           |
| LaMarcus Aldridge    |
| Lance Allred         |
| Larry Hughes         |
| Leandro Barbosa      |
| LeBron James         |
| Leon Powe            |
| Linas Kleiza         |
| Lindsey Hunter       |
| Linton Johnson III   |
| Loren Woods          |
| Lorenzen Wright      |
| Louis Amundson       |
| Louis Williams       |
| Luis Scola           |
| Luke Ridnour         |
| Luke Walton          |
| Luol Deng            |
| Luther Head          |
| Maceo Baston         |
| Malik Allen          |
| Malik Rose           |
| Manu Ginobili        |
| Marcin Gortat        |
| Marco Belinelli      |
| Marcus Banks         |
| Marcus Camby         |
| Marcus Williams      |
| Marcus Williams      |
| Mardy Collins        |
| Mario West           |
| Mark Blount          |
| Mark Madsen          |
| Marko Jaric          |
| Marquis Daniels      |
| Martell Webster      |
| Marvin Williams      |
| Matt Barnes          |
| Matt Bonner          |
| Matt Carroll         |
| Matt Harpring        |
| Maurice Ager         |
| Maurice Evans        |
| Mehmet Okur          |
| Melvin Ely           |
| Michael Doleac       |
| Michael Finley       |
| Michael Redd         |
| Michael Ruffin       |
| Mickael Gelabale     |
| Mickael Pietrus      |
| Mike Bibby           |
| Mike Conley          |
| Mike Dunleavy        |
| Mike Harris          |
| Mike James           |
| mike john salmons    |
| Mike Miller          |
| Mikki More           |
| Mo Williams          |
| Monta Ellis          |
| Morris Almond        |
| Morris Peterson      |
| Mouhamed Sene        |
| Nate Robinson        |
| Nazr Mohammed        |
| Nenad Krstic         |
| Nene                 |
| Nick Collison        |
| Nick Fazekas         |
| Nick Young           |
| Oleksiy Pecherov     |
| Othella Harrington   |
| P.J.Brown            |
| Pat Garrity          |
| Patrick O'Bryant     |
| Pau Gasol            |
| Paul Davis           |
| Paul Millsap         |
| Paul Pierce          |
| Peja Stojakovic      |
| Primoz Brezec        |
| Quentin Richardson   |
| Quincy Douby         |
| Quinton Ross         |
| Raef LaFremtz        |
| Rafer ALston         |
| Raja Bell            |
| Rajon Rondo          |
| Ramon Sessions       |
| Randolph Morris      |
| Randy Foye           |
| Rashard Lewis        |
| Rashard McCants      |
| Rasheed Wallace      |
| Rasho Nesterovic     |
| Rasual Butler        |
| Ray Allen            |
| Raymond Felton       |
| Reggie Evans         |
| Renaldo Balkman      |
| Richard Hamilton     |
| Richard Jefferson    |
| Ricky Davis          |
| Robert Horry         |
| Robert Swift         |
| Rodney Carney        |
| Rodney Stuckey       |
| Roger Mason          |
| Ron Artest           |
| Ronald Dupree        |
| Ronald Murray        |
| Ronnie Brewer        |
| Ronnie Price         |
| Ronny Turiaf         |
| Royal Ivey           |
| Rudy Gay             |
| Ryan Bowen           |
| Ryan Gomes           |
| Ryan Hollins         |
| Salim Stoudamire     |
| Sam Cassell          |
| Samuel Dalembert     |
| Sasha Vujacic        |
| Scot Pollard         |
| Sean Marks           |
| Sean May             |
| Sean Williams        |
| Sebastian Telfair    |
| Sergio Rodriguez     |
| Shane Battier        |
| Shannon Brown        |
| Shaquille ONeal      |
| Shareef Abdur-Rahim  |
| Shaun Livingston     |
| Shavlik Randolph     |
| Shawn Marion         |
| Shawne Williams      |
| Shelden Williams     |
| Smush Parker         |
| Solomon Jones        |
| Speedy Claxton       |
| Spencer Hawes        |
| Stephane Lasme       |
| Stephen Graham       |
| Stephen Jackson      |
| Stephon Marbury      |
| Steve Blake          |
| Steve Francis        |
| Steve Nash - C       |
| Steve NOvak          |
| Steven Hunter        |
| Stromile Swift       |
| T.J. Ford            |
| Taurean Green        |
| Tayshaun Prince      |
| Thabo Sefolosha      |
| Thaddeus Young       |
| Theo Ratliff         |
| Tim Duncan           |
| Tim Thomas           |
| Tony Allen           |
| Tony Battie          |
| Tony Parker          |
| Tracy McGrady        |
| Travis Diener        |
| Travis Outlaw        |
| Trenton Hassell      |
| Trevor Ariza         |
| Troy Murphy          |
| Tyronn Lue           |
| Tyrus Thonas         |
| Tyson Chandler       |
| Udonis Haslem        |
| Vince Carter         |
| Vladimir Radmanovic  |
| Von Wafer            |
| Wally Szczerbiak     |
| Walter Herrmann      |
| Willie Green         |
| Wilson Chandler      |
| Yakhouba Diawarra    |
| Yao Ming             |
| Yi Jianlian          |
| Zach Randolph        |
| Zaza Pachulia        |
| Zydrunas Ilgauskas   |
+----------------------+
```
### 2. Mostrar el nombre de los jugadores que sean pivots (‘C’) y que pesen más de 200 libras, ordenados por nombre alfabéticamente.
```
SELECT Nombre AS "Nombre Jugaodor", Posicion AS "Posición", Peso AS "Peso Jugador" FROM jugadores WHERE Posicion LIKE '%C%' AND Peso > 200;
+----------------------+-----------+--------------+
| Nombre Jugaodor      | Posición  | Peso Jugador |
+----------------------+-----------+--------------+
| Michael Doleac       | C         |          262 |
| Al Jefferson         | C-F       |          265 |
| Mark Madsen          | C-F       |          250 |
| Craig Smith          | F-C       |          250 |
| Paul Davis           | c         |          270 |
| Chris Kaman          | C         |          265 |
| Josh Powell          | C-F       |          240 |
| Kwame Brown          | C         |          270 |
| Jason Collins        | C-F       |          255 |
| Darko Milicic        | C-F       |          275 |
| Andrew Bynum         | C         |          285 |
| Pau Gasol            | F-C       |          250 |
| Didier Ilunga-Mbenga | C         |          255 |
| Chris Mihm           | C         |          265 |
| Ronny Turiaf         | F-C       |          250 |
| Andrea Bargnani      | C-F       |          250 |
| Maceo Baston         | C-F       |          230 |
| Primoz Brezec        | C         |          255 |
| Rasho Nesterovic     | C         |          255 |
| Eddy Curry           | C         |          285 |
| Jerome James         | C         |          285 |
| Randolph Morris      | C         |          260 |
| Calvin Booth         | C         |          250 |
| Samuel Dalembert     | C         |          250 |
| Herbert Hill         | F-C       |          240 |
| Lance Allred         | C         |          250 |
| Zydrunas Ilgauskas   | C         |          260 |
| Dwayne Jones         | C-F       |          251 |
| Joe Smith            | F-C       |          225 |
| Anderson Varejao     | C-F       |          240 |
| Ben Wallace          | C-F       |          240 |
| Othella Harrington   | F-C       |          235 |
| Ryan Hollins         | C         |          230 |
| Sean May             | F-C       |          266 |
| Nazr Mohammed        | C         |          250 |
| Emeka Okafor         | F-C       |          255 |
| Andrew Bouqt         | C         |          260 |
| Dan Gadzuric         | C         |          245 |
| Michael Ruffin       | F-C       |          248 |
| Jake Voskuhl         | C         |          255 |
| Aaron Gray           | C         |          270 |
| Joakin Noah          | C-F       |          232 |
| P.J.Brown            | F-C       |          239 |
| Kendrick Perkins     | C         |          264 |
| Scot Pollard         | C-F       |          278 |
| Brian Scalabrine     | F-C       |          235 |
| Al Horford           | C-F       |          245 |
| Zaza Pachulia        | C         |          280 |
| joel Anthony         | C         |          245 |
| Earl Barron          | C-F       |          245 |
| Mark Blount          | C-F       |          250 |
| Alonzo Mourning      | C         |          261 |
| Spencer Hawes        | C         |          245 |
| Brad Miller          | C         |          261 |
| Mikki More           | F-C       |          225 |
| Shelden Williams     | F-C       |          250 |
| Lorenzen Wright      | C         |          255 |
| Brian Scalabrine     | F-C       |          235 |
| Chris Andersen       | F-C       |          228 |
| Hilton Armstrong     | C-F       |          235 |
| Tyson Chandler       | C         |          235 |
| Melvin Ely           | C-F       |          261 |
| Dikembre Mutombo     | C         |          260 |
| Luis Scola           | F-C       |          245 |
| Loren Woods          | C         |          260 |
| Yao Ming             | C         |          310 |
| Matt Bonner          | C-F       |          240 |
| Tim Duncan           | F-C       |          260 |
| Robert Horry         | F-C       |          240 |
| Ian Mahinmi          | C         |          230 |
| Fabricio Oberto      | C         |          245 |
| Kurt Thomas          | C-F       |          235 |
| LaMarcus Aldridge    | F-C       |          245 |
| Channing Frye        | C         |          248 |
| Greg Oden            | C         |          250 |
| Joel Przybilla       | C         |          255 |
| Brendan Haywood      | C         |          263 |
| Oleksiy Pecherov     | C-F       |          234 |
| Etan Thomas          | C         |          260 |
| Tony Battie          | F-C       |          240 |
| Adonal Foyle         | C         |          270 |
| Marcin Gortat        | F-C       |          240 |
| Dwight Howard        | F-C       |          265 |
| Erick Dampier        | C         |          265 |
| Jamaal Magloire      | C         |          265 |
| Josh Boone           | C         |          237 |
| DeSagana Diop        | C         |          280 |
| Nenad Krstic         | F-C       |          240 |
| Stromile Swift       | F-C       |          220 |
| Sean Williams        | F-C       |          235 |
| Marcus Camby         | C         |          235 |
| Steven Hunter        | F-C       |          240 |
| Nene                 | F-C       |          250 |
| Jarron Collins       | C         |          239 |
| Kyrylo Fesenko       | C         |          288 |
| Paul Millsap         | F-C       |          258 |
| Mehmet Okur          | C         |          263 |
| Jeff Foster          | C         |          250 |
| David Harrison       | C         |          280 |
| Troy Murphy          | C-F       |          245 |
| Jermaine O'Neal      | F-C       |          260 |
| Theo Ratliff         | C         |          235 |
| Cheikh Samb          | C         |          245 |
| Rasheed Wallace      | C-F       |          230 |
| Nick Collison        | F-C       |          255 |
| Francisco Elson      | C         |          235 |
| Johan Petro          | C         |          247 |
| Mouhamed Sene        | C         |          230 |
| Robert Swift         | C         |          245 |
| Boris Diaw           | F-C       |          235 |
| Sean Marks           | F-C       |          250 |
| Shaquille ONeal      | C         |          325 |
| Amare Stoudemire     | C-F       |          249 |
| Andris Biedrns       | C         |          230 |
| Al Harrington        | F-C       |          250 |
| Patrick O'Bryant     | C         |          250 |
| Kosta Perovic        | C         |          240 |
+----------------------+-----------+--------------+
```
### 3. Mostrar el nombre de todos los equipos ordenados alfabéticamente.
```
SELECT Nombre AS "Nombre de Equipos" FROM equipos ORDER BY Nombre ASC;
+-------------------+
| Nombre de Equipos |
+-------------------+
| 76ers             |
| Bobcats           |
| Bucks             |
| Bulls             |
| Cavaliers         |
| Celtics           |
| Clippers          |
| Grizzlies         |
| Hawks             |
| Heat              |
| Hornets           |
| Jazz              |
| Kings             |
| Knicks            |
| Lakers            |
| Magic             |
| Mavericks         |
| Nets              |
| Nuggets           |
| Pacers            |
| Pistons           |
| Raptors           |
| Rockets           |
| Spurs             |
| Suns              |
| Supersonics       |
| Timberwolves      |
| Trail Blazers     |
| Warriors          |
| Wizards           |
+-------------------+
```
### 4. Mostrar el nombre de los equipos del este (East).
```
 SELECT Nombre AS "Nombre Equipo" FROM equipos WHERE Conferencia = "East";
+---------------+
| Nombre Equipo |
+---------------+
| 76ers         |
| Bobcats       |
| Bucks         |
| Bulls         |
| Cavaliers     |
| Celtics       |
| Hawks         |
| Heat          |
| Knicks        |
| Magic         |
| Nets          |
| Pacers        |
| Pistons       |
| Raptors       |
| Wizards       |
+---------------+
```
### 5. Mostrar los equipos donde su ciudad empieza con la letra ‘c’, ordenados por nombre.
```
 SELECT Nombre AS "Nombre Equipo", Ciudad FROM equipos WHERE Ciudad LIKE "c%";
+---------------+-----------+
| Nombre Equipo | Ciudad    |
+---------------+-----------+
| Bobcats       | Charlotte |
| Bulls         | Chicago   |
| Cavaliers     | Cleveland |
+---------------+-----------+
```
### 6. Mostrar todos los jugadores y su equipo ordenados por nombre del equipo.
```
SELECT Nombre AS "Nombre Jugador", Nombre_equipo AS "Nombre Equipo"  FROM jugadores ORDER BY  Nombre_equipo ASC;
+----------------------+---------------+
| Nombre Jugador       | Nombre Equipo |
+----------------------+---------------+
| Louis Amundson       | 76ers         |
| Thaddeus Young       | 76ers         |
| Louis Williams       | 76ers         |
| Jason Smith          | 76ers         |
| Shavlik Randolph     | 76ers         |
| Kevin Ollie          | 76ers         |
| Andre Miller         | 76ers         |
| Andre Iguodala       | 76ers         |
| Willie Green         | 76ers         |
| Reggie Evans         | 76ers         |
| Samuel Dalembert     | 76ers         |
| Rodney Carney        | 76ers         |
| Calvin Booth         | 76ers         |
| Herbert Hill         | 76ers         |
| Gerald Wallace       | Bobcats       |
| Jason Richardson     | Bobcats       |
| Emeka Okafor         | Bobcats       |
| Adam Morrison        | Bobcats       |
| Nazr Mohammed        | Bobcats       |
| Ryan Hollins         | Bobcats       |
| Othella Harrington   | Bobcats       |
| Raymond Felton       | Bobcats       |
| Jared Dudley         | Bobcats       |
| Jermareo Davidson    | Bobcats       |
| Matt Carroll         | Bobcats       |
| Earl Boykins         | Bobcats       |
| Derek Anderson       | Bobcats       |
| Sean May             | Bobcats       |
| Awvee Store          | Bucks         |
| Dan Gadzuric         | Bucks         |
| Yi Jianlian          | Bucks         |
| Mo Williams          | Bucks         |
| Jake Voskuhl         | Bucks         |
| Charlie Villanueva   | Bucks         |
| Bobby Simmons        | Bucks         |
| Ramon Sessions       | Bucks         |
| Michael Ruffin       | Bucks         |
| Michael Redd         | Bucks         |
| Desmond Mason        | Bucks         |
| Royal Ivey           | Bucks         |
| Charlie Bell         | Bucks         |
| Andrew Bouqt         | Bucks         |
| Chris Duhon          | Bulls         |
| Luol Deng            | Bulls         |
| Drew Gooden          | Bulls         |
| Ben Gordon           | Bulls         |
| Aaron Gray           | Bulls         |
| Kirk Hinrich         | Bulls         |
| Larry Hughes         | Bulls         |
| Demetris Nichols     | Bulls         |
| Joakin Noah          | Bulls         |
| Andres Nocioni       | Bulls         |
| Thabo Sefolosha      | Bulls         |
| Cedric Simmons       | Bulls         |
| JamesOn Curry        | Bulls         |
| Shannon Brown        | Bulls         |
| Tyrus Thonas         | Bulls         |
| Joe Smith            | Cavaliers     |
| Lance Allred         | Cavaliers     |
| Devin Brown          | Cavaliers     |
| Daniel Gibson        | Cavaliers     |
| Zydrunas Ilgauskas   | Cavaliers     |
| LeBron James         | Cavaliers     |
| Damon Jones          | Cavaliers     |
| Dwayne Jones         | Cavaliers     |
| Aleksandar Pavlovic  | Cavaliers     |
| Eric Snow            | Cavaliers     |
| Wally Szczerbiak     | Cavaliers     |
| Anderson Varejao     | Cavaliers     |
| Ben Wallace          | Cavaliers     |
| Delonte West         | Cavaliers     |
| Kevin Garnett        | Celtics       |
| Glen Davis           | Celtics       |
| Kendrick Perkins     | Celtics       |
| Eddie House          | Celtics       |
| Paul Pierce          | Celtics       |
| Sam Cassell          | Celtics       |
| P.J.Brown            | Celtics       |
| Tony Allen           | Celtics       |
| Ray Allen            | Celtics       |
| Scot Pollard         | Celtics       |
| James Posey          | Celtics       |
| Leon Powe            | Celtics       |
| Gabe Pruitt          | Celtics       |
| Rajon Rondo          | Celtics       |
| Brian Scalabrine     | Celtics       |
| Josh Powell          | Clippers      |
| Marcus Williams      | Clippers      |
| al thornton          | Clippers      |
| Tim Thomas           | Clippers      |
| Quinton Ross         | Clippers      |
| Smush Parker         | Clippers      |
| Cuttino Mobley       | Clippers      |
| Corey Maggette       | Clippers      |
| Brevin Knight        | Clippers      |
| Chris Kaman          | Clippers      |
| Shaun Livingston     | Clippers      |
| Nick Fazekas         | Clippers      |
| Dan Dickau           | Clippers      |
| Paul Davis           | Clippers      |
| Elton brand          | Clippers      |
| Hakim Warrick        | Grizzlies     |
| Juan Carlos Navarro  | Grizzlies     |
| Darko Milicic        | Grizzlies     |
| Aaron Mckie          | Grizzlies     |
| Kyle Lowry           | Grizzlies     |
| Casey Jacobsen       | Grizzlies     |
| Rudy Gay             | Grizzlies     |
| Javaris Crittenton   | Grizzlies     |
| Mike Conley          | Grizzlies     |
| Jason Collins        | Grizzlies     |
| Brian Cardinal       | Grizzlies     |
| Kwame Brown          | Grizzlies     |
| Andre Brown          | Grizzlies     |
| Mike Miller          | Grizzlies     |
| Mike Bibby           | Hawks         |
| Josh Childress       | Hawks         |
| Speedy Claxton       | Hawks         |
| Al Horford           | Hawks         |
| Joe Johnson          | Hawks         |
| Solomon Jones        | Hawks         |
| Acie Law             | Hawks         |
| Zaza Pachulia        | Hawks         |
| Jeremy Richardson    | Hawks         |
| Josh Smith           | Hawks         |
| Salim Stoudamire     | Hawks         |
| Mario West           | Hawks         |
| Marvin Williams      | Hawks         |
| Dorell Wright        | Heat          |
| Blake Ahearn         | Heat          |
| joel Anthony         | Heat          |
| Earl Barron          | Heat          |
| Jason Williams       | Heat          |
| Dwyane Wade          | Heat          |
| Chris Quinn          | Heat          |
| Alonzo Mourning      | Heat          |
| Shawn Marion         | Heat          |
| Stephane Lasme       | Heat          |
| Alexander Johnson    | Heat          |
| Udonis Haslem        | Heat          |
| Ricky Davis          | Heat          |
| Daequan Cook         | Heat          |
| Mark Blount          | Heat          |
| Marcus Banks         | Heat          |
| David West           | Hornets       |
| Julian Wright        | Hornets       |
| Bonzi Wells          | Hornets       |
| Peja Stojakovic      | Hornets       |
| Morris Peterson      | Hornets       |
| Chris Paul           | Hornets       |
| Jannero Pargo        | Hornets       |
| Mike James           | Hornets       |
| Melvin Ely           | Hornets       |
| Tyson Chandler       | Hornets       |
| Rasual Butler        | Hornets       |
| Ryan Bowen           | Hornets       |
| Hilton Armstrong     | Hornets       |
| Chris Andersen       | Hornets       |
| Ronnie Brewer        | Jazz          |
| Morris Almond        | Jazz          |
| Carlos Boozer        | Jazz          |
| Deron Williams       | Jazz          |
| Ronnie Price         | Jazz          |
| Mehmet Okur          | Jazz          |
| Paul Millsap         | Jazz          |
| C.J. Miles           | Jazz          |
| Kyle Korver          | Jazz          |
| Andrei Kirilenko     | Jazz          |
| Jason Hart           | Jazz          |
| Matt Harpring        | Jazz          |
| Kyrylo Fesenko       | Jazz          |
| Jarron Collins       | Jazz          |
| Brian Scalabrine     | Kings         |
| Ron Artest           | Kings         |
| Lorenzen Wright      | Kings         |
| Shelden Williams     | Kings         |
| Beno Udrih           | Kings         |
| Keny Thomas          | Kings         |
| mike john salmons    | Kings         |
| Mikki More           | Kings         |
| Brad Miller          | Kings         |
| Kevin Martin         | Kings         |
| Anthony Johnson      | Kings         |
| Spencer Hawes        | Kings         |
| Francisco Garcia     | Kings         |
| Quincy Douby         | Kings         |
| Shareef Abdur-Rahim  | Kings         |
| Renaldo Balkman      | Knicks        |
| Nate Robinson        | Knicks        |
| Quentin Richardson   | Knicks        |
| Zach Randolph        | Knicks        |
| Randolph Morris      | Knicks        |
| Stephon Marbury      | Knicks        |
| David Lee            | Knicks        |
| Fred Jones           | Knicks        |
| Malik Rose           | Knicks        |
| Jared Jeffries       | Knicks        |
| Jerome James         | Knicks        |
| Eddy Curry           | Knicks        |
| Jamal Crawford       | Knicks        |
| Mardy Collins        | Knicks        |
| Wilson Chandler      | Knicks        |
| Trevor Ariza         | Lakers        |
| Coby Karl            | Lakers        |
| Andrew Bynum         | Lakers        |
| Kobe Bryant          | Lakers        |
| Luke Walton          | Lakers        |
| Sasha Vujacic        | Lakers        |
| Ronny Turiaf         | Lakers        |
| Vladimir Radmanovic  | Lakers        |
| Lamar Odom           | Lakers        |
| Ira Newble           | Lakers        |
| Chris Mihm           | Lakers        |
| Didier Ilunga-Mbenga | Lakers        |
| Pau Gasol            | Lakers        |
| Derek Fisher         | Lakers        |
| Jordan Farmar        | Lakers        |
| James Augustine      | Magic         |
| Carlos Arroyo        | Magic         |
| Tony Battie          | Magic         |
| Keith Bogans         | Magic         |
| Brian Cook           | Magic         |
| Kenyon Dooling       | Magic         |
| Maurice Evans        | Magic         |
| Adonal Foyle         | Magic         |
| Pat Garrity          | Magic         |
| Marcin Gortat        | Magic         |
| Dwight Howard        | Magic         |
| Rashard Lewis        | Magic         |
| Jammer Nelson        | Magic         |
| J.J.Redick           | Magic         |
| Hedo Turkoglu        | Magic         |
| Malik Allen          | Mavericks     |
| Devean George        | Mavericks     |
| Antoine Wright       | Mavericks     |
| Jason Terry          | Mavericks     |
| Jerry Stackhouse     | Mavericks     |
| Dirk Nowitzki        | Mavericks     |
| Jamaal Magloire      | Mavericks     |
| Tyronn Lue           | Mavericks     |
| Jason Kidd           | Mavericks     |
| Eddie Jones          | Mavericks     |
| Juwan Howard         | Mavericks     |
| Josh Howard          | Mavericks     |
| Erick Dampier        | Mavericks     |
| Brandon Bass         | Mavericks     |
| Jose Barea           | Mavericks     |
| Trenton Hassell      | Nets          |
| Maurice Ager         | Nets          |
| Darrel Armstrong     | Nets          |
| Josh Boone           | Nets          |
| Vince Carter         | Nets          |
| DeSagana Diop        | Nets          |
| Devin Harris         | Nets          |
| Richard Jefferson    | Nets          |
| Nenad Krstic         | Nets          |
| Bostjan Nachbar      | Nets          |
| Stromile Swift       | Nets          |
| Keith Van Horn       | Nets          |
| Marcus Williams      | Nets          |
| Sean Williams        | Nets          |
| Anthony Carter       | Nuggets       |
| JR Smith             | Nuggets       |
| Nene                 | Nuggets       |
| Eduardo Najera       | Nuggets       |
| Kenyon Martin        | Nuggets       |
| Linas Kleiza         | Nuggets       |
| Allen Iverson        | Nuggets       |
| Steven Hunter        | Nuggets       |
| Taurean Green        | Nuggets       |
| Yakhouba Diawarra    | Nuggets       |
| Marcus Camby         | Nuggets       |
| Chucky Atkins        | Nuggets       |
| Carmelo Anthony      | Nuggets       |
| Jermaine O'Neal      | Pacers        |
| Troy Murphy          | Pacers        |
| Ronald Murray        | Pacers        |
| Travis Diener        | Pacers        |
| Andre Owens          | Pacers        |
| Kareem Rush          | Pacers        |
| Jamaal Tinsley       | Pacers        |
| Shawne Williams      | Pacers        |
| David Harrison       | Pacers        |
| Danny Granger        | Pacers        |
| Stephen Graham       | Pacers        |
| Jeff Foster          | Pacers        |
| Mike Dunleavy        | Pacers        |
| Ike Diogu            | Pacers        |
| Marquis Daniels      | Pacers        |
| Arron Afflalo        | Pistons       |
| Chauncey Billups     | Pistons       |
| Richard Hamilton     | Pistons       |
| Juan Dixon           | Pistons       |
| Rasheed Wallace      | Pistons       |
| Rodney Stuckey       | Pistons       |
| Cheikh Samb          | Pistons       |
| Theo Ratliff         | Pistons       |
| Tayshaun Prince      | Pistons       |
| Jason Maxiell        | Pistons       |
| Amir Johnson         | Pistons       |
| Lindsey Hunter       | Pistons       |
| Walter Herrmann      | Pistons       |
| Jarvis Hayes         | Pistons       |
| Antonio McDyess      | Pistons       |
| Jamario Moon         | Raptors       |
| Anthony Parker       | Raptors       |
| Rasho Nesterovic     | Raptors       |
| Jason Kapono         | Raptors       |
| Linton Johnson III   | Raptors       |
| Kris Humphries       | Raptors       |
| Joey Graham          | Raptors       |
| T.J. Ford            | Raptors       |
| Carlos Delfino       | Raptors       |
| Jose Calderon        | Raptors       |
| Primoz Brezec        | Raptors       |
| Maceo Baston         | Raptors       |
| Andrea Bargnani      | Raptors       |
| Jorge Garbajosa      | Raptors       |
| Yao Ming             | Rockets       |
| Loren Woods          | Rockets       |
| Luis Scola           | Rockets       |
| Steve NOvak          | Rockets       |
| Dikembre Mutombo     | Rockets       |
| Tracy McGrady        | Rockets       |
| Carl Landry          | Rockets       |
| Bobby Jackson        | Rockets       |
| Luther Head          | Rockets       |
| Chuck Hayes          | Rockets       |
| Mike Harris          | Rockets       |
| Steve Francis        | Rockets       |
| Aaron Brooks         | Rockets       |
| Shane Battier        | Rockets       |
| Rafer ALston         | Rockets       |
| Matt Bonner          | Spurs         |
| Brent Barry          | Spurs         |
| Jacque Vaughn        | Spurs         |
| Ime Udoka            | Spurs         |
| Kurt Thomas          | Spurs         |
| Damon Stoudamire     | Spurs         |
| Tony Parker          | Spurs         |
| Fabricio Oberto      | Spurs         |
| Bobby Jones          | Spurs         |
| Robert Horry         | Spurs         |
| Manu Ginobili        | Spurs         |
| Michael Finley       | Spurs         |
| Tim Duncan           | Spurs         |
| Bruce Bowen          | Spurs         |
| Ian Mahinmi          | Spurs         |
| Leandro Barbosa      | Suns          |
| Raja Bell            | Suns          |
| Boris Diaw           | Suns          |
| Gordan Giricek       | Suns          |
| Grant Hill           | Suns          |
| Sean Marks           | Suns          |
| Steve Nash - C       | Suns          |
| Shaquille ONeal      | Suns          |
| Eric Piatkowski      | Suns          |
| Brian Skinner        | Suns          |
| Amare Stoudemire     | Suns          |
| D.J. Strawberry      | Suns          |
| Alando Tucker        | Suns          |
| Donyell Marshall     | Supersonics   |
| Nick Collison        | Supersonics   |
| Ronald Dupree        | Supersonics   |
| Kevin Durant         | Supersonics   |
| Francisco Elson      | Supersonics   |
| Mickael Gelabale     | Supersonics   |
| Jeff Green           | Supersonics   |
| Adrian Griffin       | Supersonics   |
| Johan Petro          | Supersonics   |
| Luke Ridnour         | Supersonics   |
| Mouhamed Sene        | Supersonics   |
| Robert Swift         | Supersonics   |
| Earl Watson          | Supersonics   |
| Chris Wilcox         | Supersonics   |
| Damien Wilkins       | Supersonics   |
| Greg Buckner         | Timberwolves  |
| Corey Brever         | Timberwolves  |
| Antoine Walker       | Timberwolves  |
| Sebastian Telfair    | Timberwolves  |
| Kirk Snyder          | Timberwolves  |
| Craig Smith          | Timberwolves  |
| Chris Richard        | Timberwolves  |
| Rashard McCants      | Timberwolves  |
| Mark Madsen          | Timberwolves  |
| Al Jefferson         | Timberwolves  |
| Marko Jaric          | Timberwolves  |
| Ryan Gomes           | Timberwolves  |
| Randy Foye           | Timberwolves  |
| Michael Doleac       | Timberwolves  |
| Darius Miles         | Trail Blazers |
| LaMarcus Aldridge    | Trail Blazers |
| Steve Blake          | Trail Blazers |
| Channing Frye        | Trail Blazers |
| Jarrett Jack         | Trail Blazers |
| James Jones          | Trail Blazers |
| Raef LaFremtz        | Trail Blazers |
| Josh McRoberts       | Trail Blazers |
| Greg Oden            | Trail Blazers |
| Travis Outlaw        | Trail Blazers |
| Joel Przybilla       | Trail Blazers |
| Sergio Rodriguez     | Trail Blazers |
| Brandon Roy          | Trail Blazers |
| Von Wafer            | Trail Blazers |
| Martell Webster      | Trail Blazers |
| C.J. Watson          | Warriors      |
| Brandan Wright       | Warriors      |
| Mickael Pietrus      | Warriors      |
| Kosta Perovic        | Warriors      |
| Patrick O'Bryant     | Warriors      |
| Stephen Jackson      | Warriors      |
| Al Harrington        | Warriors      |
| Monta Ellis          | Warriors      |
| Baron Davis          | Warriors      |
| Austin Croshere      | Warriors      |
| Andris Biedrns       | Warriors      |
| Marco Belinelli      | Warriors      |
| Matt Barnes          | Warriors      |
| Kelenna Azubuike     | Warriors      |
| Gilbert Arenas       | Wizards       |
| Andray Blatche       | Wizards       |
| Caron Butler         | Wizards       |
| Antonio Daniels      | Wizards       |
| Brendan Haywood      | Wizards       |
| Antawn Jamison       | Wizards       |
| Roger Mason          | Wizards       |
| Dominic McGuire      | Wizards       |
| Oleksiy Pecherov     | Wizards       |
| Darius Songaila      | Wizards       |
| DeShawn Stevenson    | Wizards       |
| Etan Thomas          | Wizards       |
| Nick Young           | Wizards       |
+----------------------+---------------+
```
### 7. Mostrar todos los jugadores del equipo “Raptors” ordenados por nombre.
```
SELECT Nombre AS "Nombre Jugadores - Raptors" FROM jugadores WHERE Nombre_equipo = "Raptors" ORDER BY  Nombre ASC;
+----------------------------+
| Nombre Jugadores - Raptors |
+----------------------------+
| Andrea Bargnani            |
| Anthony Parker             |
| Carlos Delfino             |
| Jamario Moon               |
| Jason Kapono               |
| Joey Graham                |
| Jorge Garbajosa            |
| Jose Calderon              |
| Kris Humphries             |
| Linton Johnson III         |
| Maceo Baston               |
| Primoz Brezec              |
| Rasho Nesterovic           |
| T.J. Ford                  |
+----------------------------+
```
### 8. Mostrar los puntos por partido del jugador ‘Pau Gasol’.
```
SELECT Puntos_por_partido AS "Puntos por Partido - Pau Gasol" FROM estadisticas INNER JOIN jugadores ON estadisticas.jugador = jugadores.codigo WHERE Nombre ="Pau Gasol";
+--------------------------------+
| Puntos por Partido - Pau Gasol |
+--------------------------------+
|                           17.6 |
|                             19 |
|                           17.7 |
|                           17.8 |
|                           20.4 |
|                           20.8 |
|                           18.9 |
+--------------------------------+
```
### 9. Mostrar los puntos por partido del jugador ‘Pau Gasol’ en la temporada ’04/05′
```
SELECT Puntos_por_partido AS "Puntos por Partido - Pau Gasol" FROM estadisticas INNER JOIN jugadores ON estadisticas.jugador = jugadores.codigo WHERE Nombre ="Pau Gasol" AND temporada = "04/05";
+--------------------------------+
| Puntos por Partido - Pau Gasol |
+--------------------------------+
|                           17.8 |
+--------------------------------+

```
### 10. Mostrar el número de puntos de cada jugador en toda su carrera.
```
SELECT Nombre AS "Nombre Jugador", SUM(Puntos_por_partido) AS "Puntos Toda Carrera" FROM estadisticas INNER JOIN jugadores ON estadisticas.jugador = jugadores.codigo GROUP BY Nombre;
+----------------------+---------------------+
| Nombre Jugador       | Puntos Toda Carrera |
+----------------------+---------------------+
| Greg Buckner         |   47.79999923706055 |
| Michael Doleac       |  46.799999952316284 |
| Mark Madsen          |   16.49999988079071 |
| Antoine Walker       |  207.80000019073486 |
| Elton brand          |  179.60000228881836 |
| Brevin Knight        |   88.00000190734863 |
| Corey Maggette       |  146.29999923706055 |
| Cuttino Mobley       |  157.60000133514404 |
| Tim Thomas           |  118.80000066757202 |
| Brian Cardinal       |  34.900000393390656 |
| Aaron Mckie          |                85.5 |
| Mike Miller          |   116.5999984741211 |
| Kobe Bryant          |   296.4000029563904 |
| Derek Fisher         |   109.2000002861023 |
| Chris Mihm           |   51.69999980926514 |
| Ira Newble           |  36.299999952316284 |
| Lamar Odom           |  138.70000171661377 |
| Rasho Nesterovic     |   66.89999914169312 |
| Jamal Crawford       |  112.09999895095825 |
| Stephon Marbury      |  233.79999828338623 |
| Quentin Richardson   |   92.20000076293945 |
| Malik Rose           |   71.29999923706055 |
| Calvin Booth         |  31.599999964237213 |
| Andre Miller         |  129.10000133514404 |
| Kevin Ollie          |   34.15000009536743 |
| Zydrunas Ilgauskas   |   142.9000005722046 |
| Damon Jones          |    64.2999997138977 |
| Joe Smith            |  152.19999933242798 |
| Eric Snow            |    82.8000009059906 |
| Wally Szczerbiak     |   135.8000020980835 |
| Ben Wallace          |   73.90000021457672 |
| Derek Anderson       |                 112 |
| Earl Boykins         |   83.40000009536743 |
| Othella Harrington   |   77.40000009536743 |
| Nazr Mohammed        |  53.499999046325684 |
| Desmond Mason        |    98.2000002861023 |
| Michael Ruffin       |                13.5 |
| Jake Voskuhl         |  31.300000071525574 |
| Larry Hughes         |                 157 |
| Ray Allen            |   256.6999988555908 |
| P.J.Brown            |  131.50000023841858 |
| Sam Cassell          |  234.90000343322754 |
| Kevin Garnett        |   265.3999996185303 |
| Eddie House          |   64.10000038146973 |
| Paul Pierce          |  229.29999923706055 |
| Scot Pollard         |   42.80000019073486 |
| James Posey          |    85.2000002861023 |
| Mike Bibby           |   163.0999994277954 |
| Mark Blount          |   61.09999990463257 |
| Ricky Davis          |   127.2000002861023 |
| Shawn Marion         |   146.9299989938736 |
| Alonzo Mourning      |   237.9000015258789 |
| Jason Williams       |  114.40000057220459 |
| Shareef Abdur-Rahim  |  196.59999871253967 |
| Ron Artest           |  149.39999771118164 |
| Anthony Johnson      |  62.399998903274536 |
| Brad Miller          |  115.80000019073486 |
| Mikki More           |   44.40000033378601 |
| Keny Thomas          |   80.10000121593475 |
| Lorenzen Wright      |   93.09999942779541 |
| Ryan Bowen           |  20.399999976158142 |
| Morris Peterson      |   91.89999961853027 |
| Peja Stojakovic      |  175.70000076293945 |
| Bonzi Wells          |   111.2999997138977 |
| Rafer ALston         |   78.60000014305115 |
| Steve Francis        |   151.4000005722046 |
| Bobby Jackson        |   112.2000002861023 |
| Tracy McGrady        |  239.89999866485596 |
| Dikembre Mutombo     |  158.60000085830688 |
| Brent Barry          |   117.9000015258789 |
| Bruce Bowen          |   69.59999918937683 |
| Tim Duncan           |               237.5 |
| Michael Finley       |  214.10000133514404 |
| Robert Horry         |  107.90000009536743 |
| Damon Stoudamire     |  172.80000066757202 |
| Kurt Thomas          |  120.40000057220459 |
| Jacque Vaughn        |  47.299999952316284 |
| Raef LaFremtz        |   91.30000066757202 |
| Joel Przybilla       |   24.50000025331974 |
| Antonio Daniels      |   85.49999976158142 |
| Antawn Jamison       |  192.10000133514404 |
| DeShawn Stevenson    |   64.29999947547913 |
| Kenyon Dooling       |   53.19999980926514 |
| Adonal Foyle         |   43.60000038146973 |
| Pat Garrity          |   58.80000019073486 |
| Rashard Lewis        |   159.2999997138977 |
| Hedo Turkoglu        |                  93 |
| Erick Dampier        |    97.2999997138977 |
| Juwan Howard         |  217.30000042915344 |
| Eddie Jones          |   199.8999993801117 |
| Jason Kidd           |   198.9000005722046 |
| Tyronn Lue           |    86.9500002861023 |
| Jamaal Magloire      |   66.10000014305115 |
| Dirk Nowitzki        |  218.69999980926514 |
| Jerry Stackhouse     |  231.19999980926514 |
| Jason Terry          |  142.80000114440918 |
| Devean George        |   51.30000042915344 |
| Darrel Armstrong     |  112.49999976158142 |
| Vince Carter         |  232.50000381469727 |
| Stromile Swift       |   69.40000009536743 |
| Keith Van Horn       |   144.0999994277954 |
| Chucky Atkins        |   91.50000023841858 |
| Marcus Camby         |  127.20000123977661 |
| Anthony Carter       |   42.30000066757202 |
| Kenyon Martin        |  110.60000038146973 |
| Eduardo Najera       |   41.59999966621399 |
| Matt Harpring        |  115.20000171661377 |
| Jason Hart           |   32.49999976158142 |
| Jeff Foster          |  43.299999952316284 |
| Jermaine O'Neal      |  159.39999866485596 |
| Chauncey Billups     |   157.9000015258789 |
| Richard Hamilton     |  160.50000381469727 |
| Lindsey Hunter       |  120.30000042915344 |
| Antonio McDyess      |   161.9000005722046 |
| Theo Ratliff         |   96.49999952316284 |
| Rasheed Wallace      |  197.20000171661377 |
| Adrian Griffin       |   31.99999964237213 |
| Donyell Marshall     |  158.60000109672546 |
| Raja Bell            |   72.39999961853027 |
| Grant Hill           |   236.9000005722046 |
| Steve Nash - C       |  164.40000081062317 |
| Shaquille ONeal      |   397.7499990463257 |
| Eric Piatkowski      |   93.00000047683716 |
| Brian Skinner        |                45.5 |
| Austin Croshere      |   68.30000042915344 |
| Baron Davis          |   176.2000002861023 |
| Al Harrington        |  122.10000038146973 |
| Stephen Jackson      |  111.30000162124634 |
| Kwame Brown          |   48.69999933242798 |
| Jason Collins        |  30.199999809265137 |
| Pau Gasol            |  132.19999885559082 |
| Vladimir Radmanovic  |   64.90000009536743 |
| Primoz Brezec        |   39.99999952316284 |
| Eddy Curry           |   94.30000019073486 |
| Jerome James         |   29.00000035762787 |
| Zach Randolph        |  109.40000033378601 |
| Jason Richardson     |   131.4000015258789 |
| Gerald Wallace       |   73.70000004768372 |
| Charlie Bell         |    31.0999995470047 |
| Bobby Simmons        |   52.19999933242798 |
| Brian Scalabrine     |  23.700000047683716 |
| Speedy Claxton       |   53.40000057220459 |
| Joe Johnson          |  116.80000305175781 |
| Chris Andersen       |   25.49999976158142 |
| Tyson Chandler       |                  56 |
| Mike James           |   69.59999918937683 |
| Shane Battier        |  42.499999046325684 |
| Loren Woods          |  14.199999928474426 |
| Tony Parker          |  112.29999923706055 |
| Gilbert Arenas       |  152.89999771118164 |
| Brendan Haywood      |   52.29999923706055 |
| Etan Thomas          |   35.89999961853027 |
| Carlos Arroyo        |   50.40000033378601 |
| Maurice Evans        |  26.299999713897705 |
| Malik Allen          |   35.40000057220459 |
| DeSagana Diop        |  13.799999833106995 |
| Trenton Hassell      |  42.399999141693115 |
| Richard Jefferson    |                 124 |
| Steven Hunter        |   29.59999990463257 |
| Jarron Collins       |  31.700000524520874 |
| Andrei Kirilenko     |   89.40000057220459 |
| Troy Murphy          |   78.09999895095825 |
| Jamaal Tinsley       |   74.89999961853027 |
| Earl Watson          |   50.09999895095825 |
| Sean Marks           |  20.399999856948853 |
| Marko Jaric          |  47.200000286102295 |
| Dan Dickau           |                  19 |
| Smush Parker         |   36.60000038146973 |
| Casey Jacobsen       |   18.40000009536743 |
| Maceo Baston         |   8.100000143051147 |
| Jared Jeffries       |  30.700000047683716 |
| Fred Jones           |   41.50000071525574 |
| Reggie Evans         |   27.00000023841858 |
| Devin Brown          |  39.600000619888306 |
| Dan Gadzuric         |                29.5 |
| Drew Gooden          |   73.30000019073486 |
| mike john salmons    |                40.5 |
| Rasual Butler        |   44.50000047683716 |
| Melvin Ely           |  32.100000619888306 |
| Jannero Pargo        |  32.100000500679016 |
| Yao Ming             |   118.5999984741211 |
| Manu Ginobili        |    87.7999997138977 |
| Caron Butler         |   97.09999942779541 |
| Roger Mason          |  16.100000381469727 |
| Bostjan Nachbar      |  32.299999713897705 |
| Nene                 |   49.40000057220459 |
| Carlos Boozer        |  101.89999771118164 |
| Mehmet Okur          |   79.50000047683716 |
| Mike Dunleavy        |   72.79999923706055 |
| Ronald Murray        |  45.399999022483826 |
| Kareem Rush          |  28.700000643730164 |
| Juan Dixon           |  49.299999713897705 |
| Tayshaun Prince      |   69.90000033378601 |
| Chris Wilcox         |   51.60000014305115 |
| Gordan Giricek       |   62.83000087738037 |
| Amare Stoudemire     |  114.19999980926514 |
| Chris Kaman          |   52.90000009536743 |
| Luke Walton          |  29.199999570846558 |
| T.J. Ford            |   45.40000009536743 |
| Linton Johnson III   |   12.59999966621399 |
| Jason Kapono         |   34.19999933242798 |
| Willie Green         |  45.200000286102295 |
| LeBron James         |  136.79999923706055 |
| Aleksandar Pavlovic  |  30.500000476837158 |
| Matt Carroll         |  38.700000286102295 |
| Mo Williams          |   61.80000019073486 |
| Kirk Hinrich         |   72.19999980926514 |
| Kendrick Perkins     |  21.299999952316284 |
| Zaza Pachulia        |   38.59999918937683 |
| Marcus Banks         |   36.90000009536743 |
| Udonis Haslem        |   50.19999980926514 |
| Dwyane Wade          |  119.50000190734863 |
| David West           |   65.99999976158142 |
| Ime Udoka            |   18.99999976158142 |
| Steve Blake          |   35.30000066757202 |
| James Jones          |  29.800000429153442 |
| Darius Songaila      |   35.09999942779541 |
| Keith Bogans         |   38.90000009536743 |
| Josh Howard          |   75.60000038146973 |
| Carmelo Anthony      |  123.29999923706055 |
| Kyle Korver          |   51.79999923706055 |
| Marquis Daniels      |   43.09999990463257 |
| Jarvis Hayes         |                  43 |
| Ronald Dupree        |  12.899999856948853 |
| Francisco Elson      |  20.600000143051147 |
| Luke Ridnour         |   44.40000009536743 |
| Leandro Barbosa      |   61.90000104904175 |
| Boris Diaw           |   41.10000038146973 |
| Matt Barnes          |   27.90000033378601 |
| Mickael Pietrus      |   42.40000057220459 |
| Al Jefferson         |   51.59999990463257 |
| Kirk Snyder          |  21.700000047683716 |
| Sebastian Telfair    |  31.700000286102295 |
| Shaun Livingston     |  22.500000476837158 |
| Quinton Ross         |   19.09999942779541 |
| Darko Milicic        |   18.49999976158142 |
| Trevor Ariza         |  25.999999523162842 |
| Didier Ilunga-Mbenga |   5.400000035762787 |
| Sasha Vujacic        |   19.90000057220459 |
| Carlos Delfino       |  21.699999809265137 |
| Kris Humphries       |   16.59999966621399 |
| Andre Iguodala       |   59.30000019073486 |
| Anderson Varejao     |                  23 |
| Delonte West         |   38.80000019073486 |
| Emeka Okafor         |                56.5 |
| Royal Ivey           |  15.699999809265137 |
| Awvee Store          |   6.100000023841858 |
| Luol Deng            |   61.79999923706055 |
| Chris Duhon          |   27.59999990463257 |
| Ben Gordon           |   72.39999961853027 |
| Andres Nocioni       |   48.69999980926514 |
| Tony Allen           |                31.5 |
| Josh Childress       |   44.90000057220459 |
| Josh Smith           |   54.60000038146973 |
| Dorell Wright        |  19.100000143051147 |
| Kevin Martin         |    57.6000018119812 |
| Beno Udrih           |                28.5 |
| Matt Bonner          |                24.5 |
| Dwight Howard        |   66.30000019073486 |
| Jammer Nelson        |   47.19999980926514 |
| Devin Harris         |   41.89999961853027 |
| Nenad Krstic         |   46.39999961853027 |
| JR Smith             |   43.30000019073486 |
| David Harrison       |  18.799999713897705 |
| Nick Collison        |   32.30000066757202 |
| Robert Swift         |   9.100000023841858 |
| Damien Wilkins       |  30.800000190734863 |
| Andris Biedrns       |  27.200000047683716 |
| Ryan Gomes           |   32.30000066757202 |
| Rashard McCants      |  27.799999713897705 |
| Josh Powell          |  10.200000047683716 |
| Hakim Warrick        |   28.19999933242798 |
| Andrew Bynum         |   9.400000214576721 |
| Ronny Turiaf         |  13.900000095367432 |
| Jose Calderon        |  25.800000190734863 |
| Joey Graham          |                  17 |
| David Lee            |   26.59999990463257 |
| Nate Robinson        |   32.10000038146973 |
| Shavlik Randolph     |                 197 |
| Louis Williams       |  17.700000166893005 |
| Dwayne Jones         |   3.199999988079071 |
| Sean May             |   20.09999942779541 |
| Andrew Bouqt         |   35.89999961853027 |
| Charlie Villanueva   |                36.5 |
| Salim Stoudamire     |   23.09999942779541 |
| Marvin Williams      |   36.40000057220459 |
| Earl Barron          |  10.200000166893005 |
| Francisco Garcia     |  23.700000286102295 |
| Chris Paul           |                54.5 |
| Chuck Hayes          |  12.299999952316284 |
| Luther Head          |  27.399999618530273 |
| Fabricio Oberto      |   10.90000033378601 |
| Channing Frye        |  28.600000381469727 |
| Jarrett Jack         |   28.59999942779541 |
| Travis Outlaw        |                14.5 |
| Von Wafer            |  2.5999999046325684 |
| Martell Webster      |  24.299999713897705 |
| Andray Blatche       |  13.200000286102295 |
| Brandon Bass         |   12.40000033378601 |
| Antoine Wright       |  13.600000143051147 |
| Linas Kleiza         |  22.200000286102295 |
| C.J. Miles           |  11.100000143051147 |
| Ronnie Price         |   9.099999904632568 |
| Deron Williams       |   45.80000019073486 |
| Travis Diener        |                14.5 |
| Ike Diogu            |  19.799999713897705 |
| Stephen Graham       |   9.450000047683716 |
| Danny Granger        |   40.29999923706055 |
| Andre Owens          |                   7 |
| Amir Johnson         |  16.199999809265137 |
| Jason Maxiell        |  15.200000047683716 |
| Johan Petro          |  17.399999618530273 |
| Monta Ellis          |   43.40000057220459 |
| Randy Foye           |  23.200000762939453 |
| Craig Smith          |  16.799999713897705 |
| Paul Davis           |   4.100000023841858 |
| Nick Fazekas         |   5.300000190734863 |
| Andre Brown          |  4.1000001430511475 |
| Rudy Gay             |  31.199999809265137 |
| Kyle Lowry           |   15.40000057220459 |
| Jordan Farmar        |  13.500000476837158 |
| Jorge Garbajosa      |  11.599999904632568 |
| Anthony Parker       |  31.399999499320984 |
| Renaldo Balkman      |   8.300000190734863 |
| Mardy Collins        |                 7.5 |
| Randolph Morris      |  3.8999999165534973 |
| Louis Amundson       |   2.899999976158142 |
| Rodney Carney        |  12.400000095367432 |
| Daniel Gibson        |  15.299999713897705 |
| Ryan Hollins         |   4.700000047683716 |
| Adam Morrison        |  11.800000190734863 |
| Shannon Brown        |                 5.5 |
| Thabo Sefolosha      |  10.299999713897705 |
| Cedric Simmons       |  3.5000001192092896 |
| Tyrus Thonas         |                  12 |
| Leon Powe            |  12.099999904632568 |
| Rajon Rondo          |  17.000000476837158 |
| Solomon Jones        |   4.299999952316284 |
| Jeremy Richardson    |   1.600000023841858 |
| Alexander Johnson    |   8.599999904632568 |
| Chris Quinn          |  11.099999904632568 |
| Quincy Douby         |  7.6000001430511475 |
| Hilton Armstrong     |                   6 |
| Steve NOvak          |   5.400000095367432 |
| Bobby Jones          |   6.900000095367432 |
| LaMarcus Aldridge    |  26.700000762939453 |
| Sergio Rodriguez     |   6.200000047683716 |
| Brandon Roy          |   35.89999961853027 |
| James Augustine      |   2.299999952316284 |
| Marcus Williams      |  12.700000286102295 |
| Yakhouba Diawarra    |   7.200000047683716 |
| Ronnie Brewer        |   16.59999990463257 |
| Paul Millsap         |   14.90000057220459 |
| Shawne Williams      |  10.599999904632568 |
| Walter Herrmann      |  11.899999856948853 |
| Mickael Gelabale     |   8.900000095367432 |
| Mouhamed Sene        |   4.199999928474426 |
| Kelenna Azubuike     |  15.700000286102295 |
| Patrick O'Bryant     |   3.399999976158142 |
| Chris Richard        |   1.899999976158142 |
| al thornton          |  12.699999809265137 |
| Mike Conley          |   9.300000190734863 |
| Javaris Crittenton   |                   5 |
| Juan Carlos Navarro  |  10.899999618530273 |
| Coby Karl            |  1.7999999523162842 |
| Andrea Bargnani      |  10.199999809265137 |
| Jamario Moon         |                 8.5 |
| Wilson Chandler      |   7.300000190734863 |
| Herbert Hill         |                   0 |
| Jason Smith          |                 4.5 |
| Thaddeus Young       |   7.800000190734863 |
| Lance Allred         |                   0 |
| Jermareo Davidson    |   3.200000047683716 |
| Jared Dudley         |   5.800000190734863 |
| Raymond Felton       |  14.100000381469727 |
| Michael Redd         |  22.700000762939453 |
| Ramon Sessions       |   8.100000381469727 |
| Yi Jianlian          |   8.600000381469727 |
| Aaron Gray           |   3.799999952316284 |
| Demetris Nichols     |   0.699999988079071 |
| Joakin Noah          |   6.599999904632568 |
| Glen Davis           |   4.300000190734863 |
| Gabe Pruitt          |  2.0999999046325684 |
| Al Horford           |  10.199999809265137 |
| Acie Law             |   4.199999809265137 |
| Mario West           |  0.8999999761581421 |
| Blake Ahearn         |   6.900000095367432 |
| joel Anthony         |  3.9000000953674316 |
| Daequan Cook         |   8.699999809265137 |
| Stephane Lasme       |   5.199999809265137 |
| Spencer Hawes        |   4.300000190734863 |
| Shelden Williams     |                   3 |
| Julian Wright        |  3.9000000953674316 |
| Aaron Brooks         |                   5 |
| Mike Harris          |   3.700000047683716 |
| Carl Landry          |   8.100000381469727 |
| Luis Scola           |  10.300000190734863 |
| Ian Mahinmi          |                 3.5 |
| Josh McRoberts       |                 1.5 |
| Dominic McGuire      |  1.2999999523162842 |
| Oleksiy Pecherov     |  3.5999999046325684 |
| Nick Young           |   7.300000190734863 |
| Tony Battie          |   6.699999809265137 |
| Brian Cook           |                   4 |
| Marcin Gortat        |  1.2000000476837158 |
| Jose Barea           |   4.300000190734863 |
| Maurice Ager         |   6.900000095367432 |
| Josh Boone           |   8.199999809265137 |
| Sean Williams        |   5.599999904632568 |
| Taurean Green        |   1.600000023841858 |
| Morris Almond        |   1.399999976158142 |
| Kyrylo Fesenko       |   1.600000023841858 |
| Arron Afflalo        |                 3.5 |
| Cheikh Samb          |  1.7999999523162842 |
| Rodney Stuckey       |   7.599999904632568 |
| Kevin Durant         |  20.299999237060547 |
| Jeff Green           |  10.300000190734863 |
| D.J. Strawberry      |   2.200000047683716 |
| Alando Tucker        |   3.700000047683716 |
| Marco Belinelli      |  2.4000000953674316 |
| Kosta Perovic        |   1.399999976158142 |
| C.J. Watson          |   3.700000047683716 |
| Brandan Wright       |                   4 |
| Corey Brever         |   5.599999904632568 |
+----------------------+---------------------+
```
### 11. Mostrar el número de jugadores de cada equipo.
```
SELECT Nombre_equipo AS "Nombre Equipo", COUNT(codigo) AS "Numero de Jugadores" FROM jugadores GROUP BY Nombre_equipo;
+---------------+---------------------+
| Nombre Equipo | Numero de Jugadores |
+---------------+---------------------+
| 76ers         |                  14 |
| Bobcats       |                  14 |
| Bucks         |                  14 |
| Bulls         |                  15 |
| Cavaliers     |                  14 |
| Celtics       |                  15 |
| Clippers      |                  15 |
| Grizzlies     |                  14 |
| Hawks         |                  13 |
| Heat          |                  16 |
| Hornets       |                  14 |
| Jazz          |                  14 |
| Kings         |                  15 |
| Knicks        |                  15 |
| Lakers        |                  15 |
| Magic         |                  15 |
| Mavericks     |                  15 |
| Nets          |                  14 |
| Nuggets       |                  13 |
| Pacers        |                  15 |
| Pistons       |                  15 |
| Raptors       |                  14 |
| Rockets       |                  15 |
| Spurs         |                  15 |
| Suns          |                  13 |
| Supersonics   |                  15 |
| Timberwolves  |                  14 |
| Trail Blazers |                  15 |
| Warriors      |                  14 |
| Wizards       |                  13 |
+---------------+---------------------+
```
### 12. Mostrar el jugador que más puntos ha realizado en toda su carrera.
```
SELECT Nombre AS "Nombre Jugador", SUM(Puntos_por_partido) AS "Record Puntos 1er Lugar" FROM estadisticas INNER JOIN jugadores ON estadisticas.jugador = jugadores.codigo GROUP BY Nombre ORDER BY SUM(Puntos_por_partido) DESC LIMIT 1;
+-----------------+-------------------------+
| Nombre Jugador  | Record Puntos 1er Lugar |
+-----------------+-------------------------+
| Shaquille ONeal |       397.7499990463257 |
+-----------------+-------------------------+
```
### 13. Mostrar el nombre del equipo, conferencia y división del jugador más alto de la NBA.
```
SELECT Nombre AS "Nombre Equipo", Conferencia, Division FROM equipos WHERE Nombre = (SELECT Nombre_equipo FROM jugadores ORDER BY Altura DESC LIMIT 1);
+---------------+-------------+-----------+
| Nombre Equipo | Conferencia | Division  |
+---------------+-------------+-----------+
| Rockets       | West        | SouthWest |
+---------------+-------------+-----------+
```
### 14. Mostrar la media de puntos en partidos de los equipos de la división Pacific.
```
SELECT AVG(puntos_local) AS "Media Puntos Locales", AVG(puntos_visitante) AS "Media Puntos Visitantes"  FROM partidos WHERE equipo_local IN ( SELECT Nombre FROM equipos WHERE Division = "Pacific") AND equipo_visitante IN (SELECT Nombre FROM equipos WHERE Division = "Pacific");
+----------------------+-------------------------+
| Media Puntos Locales | Media Puntos Visitantes |
+----------------------+-------------------------+
|             103.1278 |                104.3417 |
+----------------------+-------------------------+
1 row in set (0,02 sec)
```
### 15. Mostrar el partido o partidos (equipo_local, equipo_visitante y diferencia) con mayor diferencia de puntos.
```
SELECT equipo_local AS "Equipo Local", equipo_visitante  AS "Equipo Visitante", (puntos_local - puntos_visitante) AS Diferencia FROM partidos WHERE (puntos_local - puntos_visitante) = (SELECT MAX(puntos_local - puntos_visitante) FROM partidos);
+--------------+------------------+------------+
| Equipo Local | Equipo Visitante | Diferencia |
+--------------+------------------+------------+
| Magic        | Suns             |        108 |
+--------------+------------------+------------+
```
### 16. Mostrar la media de puntos en partidos de los equipos de la división Pacific.
```
Repetición del Ejercicios 14
```
### 17. Mostrar los puntos de cada equipo en los partidos, tanto de local como de visitante.
```
 SELECT equipo_local AS "Nombre Equipo", SUM(puntos_local) AS "Puntos como Local" FROM partidos GROUP BY equipo_local;;
+---------------+-------------------+
| Nombre Equipo | Puntos como Local |
+---------------+-------------------+
| 76ers         |             55164 |
| Bobcats       |             53855 |
| Bucks         |             53997 |
| Bulls         |             53411 |
| Cavaliers     |             53195 |
| Celtics       |             54500 |
| Clippers      |             54731 |
| Grizzlies     |             54925 |
| Hawks         |             54954 |
| Heat          |             53580 |
| Hornets       |             54211 |
| Jazz          |             54186 |
| Kings         |             53457 |
| Knicks        |             54987 |
| Lakers        |             53383 |
| Magic         |             54728 |
| Mavericks     |             54248 |
| Nets          |             53962 |
| Nuggets       |             54173 |
| Pacers        |             54091 |
| Pistons       |             55100 |
| Raptors       |             53485 |
| Rockets       |             55158 |
| Spurs         |             53744 |
| Suns          |             52053 |
| Supersonics   |             54461 |
| Timberwolves  |             55471 |
| Trail Blazers |             53321 |
| Warriors      |             55562 |
| Wizards       |             53587 |
+---------------+-------------------+
SELECT equipo_visitante  AS "Nombre Equipo", SUM(puntos_visitante) AS "Puntos como Visitante" FROM partidos GROUP BY equipo_visitante;
+---------------+-----------------------+
| Nombre Equipo | Puntos como Visitante |
+---------------+-----------------------+
| 76ers         |                 54582 |
| Bobcats       |                 52643 |
| Bucks         |                 53895 |
| Bulls         |                 54307 |
| Cavaliers     |                 52922 |
| Celtics       |                 54570 |
| Clippers      |                 54443 |
| Grizzlies     |                 53741 |
| Hawks         |                 54972 |
| Heat          |                 53589 |
| Hornets       |                 52795 |
| Jazz          |                 52299 |
| Kings         |                 54113 |
| Knicks        |                 54450 |
| Lakers        |                 54661 |
| Magic         |                 55034 |
| Mavericks     |                 53741 |
| Nets          |                 54915 |
| Nuggets       |                 53517 |
| Pacers        |                 54372 |
| Pistons       |                 53151 |
| Raptors       |                 55042 |
| Rockets       |                 53756 |
| Spurs         |                 53382 |
| Suns          |                 53644 |
| Supersonics   |                 55550 |
| Timberwolves  |                 54766 |
| Trail Blazers |                 54655 |
| Warriors      |                 54754 |
| Wizards       |                 55791 |
+---------------+-----------------------+
```
### 18. Mostrar quien gana en cada partido (codigo, equipo_local, equipo_visitante, equipo_ganador), en caso de empate sera null.
```
SELECT codigo AS "Codigo", equipo_local AS "Equipo Local", equipo_visitante  AS "Equipo Visitante", IF((puntos_local - puntos_visitante)<0,"Visitante",IF((puntos_local - puntos_visitante)=0,NULL,"Local")) AS "Equipo Ganador" FROM partidos;
+--------+---------------+------------------+----------------+
| Codigo | Equipo Local  | Equipo Visitante | Equipo Ganador |
+--------+---------------+------------------+----------------+
|      1 | Raptors       | Lakers           | Visitante      |
|      2 | Raptors       | Grizzlies        | Visitante      |
|      3 | Raptors       | Clippers         | Local          |
|      4 | Raptors       | Knicks           | Visitante      |
|      5 | Raptors       | Timberwolves     | Visitante      |
|      6 | Raptors       | Celtics          | Visitante      |
|      7 | Raptors       | 76ers            | Visitante      |
|      8 | Raptors       | Nets             | Visitante      |
|      9 | Raptors       | Pistons          | Local          |
|     10 | Raptors       | Cavaliers        | Visitante      |
|     11 | Raptors       | Pacers           | Local          |
|     12 | Raptors       | Bulls            | Local          |
|     13 | Raptors       | Bucks            | Visitante      |
|     14 | Raptors       | Magic            | Visitante      |
|     15 | Raptors       | Wizards          | Local          |
|     16 | Raptors       | Hawks            | Visitante      |
|     17 | Raptors       | Bobcats          | Local          |
|     18 | Raptors       | Heat             | Local          |
|     19 | Raptors       | Jazz             | Local          |
|     20 | Raptors       | Nuggets          | Visitante      |
|     21 | Raptors       | Trail Blazers    | Local          |
|     22 | Raptors       | Supersonics      | NULL           |
....
|  15487 | Kings         | Raptors          | Visitante      |
|  15488 | Kings         | Lakers           | Visitante      |
|  15489 | Kings         | Grizzlies        | Local          |
|  15490 | Kings         | Clippers         | NULL           |
|  15491 | Kings         | Knicks           | Visitante      |
|  15492 | Kings         | Timberwolves     | Visitante      |
|  15493 | Kings         | Celtics          | Local          |
|  15494 | Kings         | 76ers            | Visitante      |
|  15495 | Kings         | Nets             | Visitante      |
|  15496 | Kings         | Pistons          | Local          |
|  15497 | Kings         | Cavaliers        | Visitante      |
|  15498 | Kings         | Pacers           | Local          |
|  15499 | Kings         | Bulls            | Visitante      |
|  15500 | Kings         | Bucks            | Visitante      |
|  15501 | Kings         | Magic            | Visitante      |
|  15502 | Kings         | Wizards          | Visitante      |
|  15503 | Kings         | Hawks            | Visitante      |
|  15504 | Kings         | Bobcats          | Local          |
|  15505 | Kings         | Heat             | Local          |
|  15506 | Kings         | Jazz             | Local          |
|  15507 | Kings         | Nuggets          | Local          |
|  15508 | Kings         | Trail Blazers    | Local          |
|  15509 | Kings         | Supersonics      | Visitante      |
|  15510 | Kings         | Warriors         | Visitante      |
|  15511 | Kings         | Hornets          | Local          |
|  15512 | Kings         | Spurs            | Local          |
|  15513 | Kings         | Rockets          | Visitante      |
|  15514 | Kings         | Mavericks        | Visitante      |
|  15515 | Kings         | Suns             | Visitante      |
|  15516 | Hornets       | Raptors          | Local          |
|  15517 | Hornets       | Lakers           | Local          |
|  15518 | Hornets       | Grizzlies        | Visitante      |
|  15519 | Hornets       | Clippers         | Local          |
|  15520 | Hornets       | Knicks           | Visitante      |
|  15521 | Hornets       | Timberwolves     | Local          |
|  15522 | Hornets       | Celtics          | Visitante      |
|  15523 | Hornets       | 76ers            | Local          |
|  15524 | Hornets       | Nets             | Local          |
|  15525 | Hornets       | Pistons          | Visitante      |
|  15526 | Hornets       | Cavaliers        | Local          |
|  15527 | Hornets       | Pacers           | Visitante      |
|  15528 | Hornets       | Bulls            | Visitante      |
|  15529 | Hornets       | Bucks            | Local          |
|  15530 | Hornets       | Magic            | Visitante      |
|  15531 | Hornets       | Wizards          | Local          |
|  15532 | Hornets       | Hawks            | Visitante      |
|  15533 | Hornets       | Bobcats          | Visitante      |
|  15534 | Hornets       | Heat             | Visitante      |
|  15535 | Hornets       | Jazz             | Visitante      |
|  15536 | Hornets       | Nuggets          | Local          |
|  15537 | Hornets       | Trail Blazers    | Visitante      |
|  15538 | Hornets       | Supersonics      | Visitante      |
|  15539 | Hornets       | Warriors         | Visitante      |
|  15540 | Hornets       | Kings            | Local          |
|  15541 | Hornets       | Spurs            | Visitante      |
|  15542 | Hornets       | Rockets          | Local          |
|  15543 | Hornets       | Mavericks        | Visitante      |
|  15544 | Hornets       | Suns             | Local          |
|  15545 | Spurs         | Raptors          | Visitante      |
|  15546 | Spurs         | Lakers           | Local          |
|  15547 | Spurs         | Grizzlies        | Local          |
|  15548 | Spurs         | Clippers         | Local          |
|  15549 | Spurs         | Knicks           | Visitante      |
|  15550 | Spurs         | Timberwolves     | Visitante      |
|  15551 | Spurs         | Celtics          | Visitante      |
|  15552 | Spurs         | 76ers            | Visitante      |
|  15553 | Spurs         | Nets             | Local          |
|  15554 | Spurs         | Pistons          | Visitante      |
|  15555 | Spurs         | Cavaliers        | Local          |
|  15556 | Spurs         | Pacers           | Local          |
|  15557 | Spurs         | Bulls            | Visitante      |
|  15558 | Spurs         | Bucks            | Local          |
|  15559 | Spurs         | Magic            | Visitante      |
|  15560 | Spurs         | Wizards          | Local          |
|  15561 | Spurs         | Hawks            | Visitante      |
|  15562 | Spurs         | Bobcats          | Local          |
|  15563 | Spurs         | Heat             | Local          |
|  15564 | Spurs         | Jazz             | Visitante      |
|  15565 | Spurs         | Nuggets          | Visitante      |
|  15566 | Spurs         | Trail Blazers    | Visitante      |
|  15567 | Spurs         | Supersonics      | Local          |
|  15568 | Spurs         | Warriors         | Visitante      |
|  15569 | Spurs         | Kings            | Visitante      |
|  15570 | Spurs         | Hornets          | Visitante      |
|  15571 | Spurs         | Rockets          | Local          |
|  15572 | Spurs         | Mavericks        | Local          |
|  15573 | Spurs         | Suns             | Local          |
|  15574 | Rockets       | Raptors          | Visitante      |
|  15575 | Rockets       | Lakers           | Local          |
|  15576 | Rockets       | Grizzlies        | Visitante      |
|  15577 | Rockets       | Clippers         | Local          |
|  15578 | Rockets       | Knicks           | Local          |
|  15579 | Rockets       | Timberwolves     | Visitante      |
|  15580 | Rockets       | Celtics          | Visitante      |
|  15581 | Rockets       | 76ers            | Local          |
|  15582 | Rockets       | Nets             | Visitante      |
|  15583 | Rockets       | Pistons          | Local          |
|  15584 | Rockets       | Cavaliers        | Local          |
|  15585 | Rockets       | Pacers           | Local          |
|  15586 | Rockets       | Bulls            | Visitante      |
|  15587 | Rockets       | Bucks            | Visitante      |
|  15588 | Rockets       | Magic            | Local          |
|  15589 | Rockets       | Wizards          | Local          |
|  15590 | Rockets       | Hawks            | Visitante      |
|  15591 | Rockets       | Bobcats          | Local          |
|  15592 | Rockets       | Heat             | Visitante      |
|  15593 | Rockets       | Jazz             | Local          |
|  15594 | Rockets       | Nuggets          | Visitante      |
|  15595 | Rockets       | Trail Blazers    | Local          |
|  15596 | Rockets       | Supersonics      | Visitante      |
|  15597 | Rockets       | Warriors         | Local          |
|  15598 | Rockets       | Kings            | Visitante      |
|  15599 | Rockets       | Hornets          | Visitante      |
|  15600 | Rockets       | Spurs            | Local          |
|  15601 | Rockets       | Mavericks        | Visitante      |
|  15602 | Rockets       | Suns             | Visitante      |
|  15603 | Mavericks     | Raptors          | Local          |
|  15604 | Mavericks     | Lakers           | Local          |
|  15605 | Mavericks     | Grizzlies        | Local          |
|  15606 | Mavericks     | Clippers         | Visitante      |
|  15607 | Mavericks     | Knicks           | Visitante      |
|  15608 | Mavericks     | Timberwolves     | Visitante      |
|  15609 | Mavericks     | Celtics          | Local          |
|  15610 | Mavericks     | 76ers            | Local          |
|  15611 | Mavericks     | Nets             | Visitante      |
|  15612 | Mavericks     | Pistons          | Local          |
|  15613 | Mavericks     | Cavaliers        | Visitante      |
|  15614 | Mavericks     | Pacers           | Visitante      |
|  15615 | Mavericks     | Bulls            | Local          |
|  15616 | Mavericks     | Bucks            | Visitante      |
|  15617 | Mavericks     | Magic            | Local          |
|  15618 | Mavericks     | Wizards          | Visitante      |
|  15619 | Mavericks     | Hawks            | Local          |
|  15620 | Mavericks     | Bobcats          | Visitante      |
|  15621 | Mavericks     | Heat             | Local          |
|  15622 | Mavericks     | Jazz             | Local          |
|  15623 | Mavericks     | Nuggets          | Local          |
|  15624 | Mavericks     | Trail Blazers    | Local          |
|  15625 | Mavericks     | Supersonics      | Local          |
|  15626 | Mavericks     | Warriors         | Local          |
|  15627 | Mavericks     | Kings            | Local          |
|  15628 | Mavericks     | Hornets          | Local          |
|  15629 | Mavericks     | Spurs            | Local          |
|  15630 | Mavericks     | Rockets          | Visitante      |
|  15631 | Mavericks     | Suns             | Local          |
|  15632 | Suns          | Raptors          | Local          |
|  15633 | Suns          | Lakers           | Visitante      |
|  15634 | Suns          | Grizzlies        | Visitante      |
|  15635 | Suns          | Clippers         | Local          |
|  15636 | Suns          | Knicks           | Visitante      |
|  15637 | Suns          | Timberwolves     | Local          |
|  15638 | Suns          | Celtics          | Visitante      |
|  15639 | Suns          | 76ers            | Visitante      |
|  15640 | Suns          | Nets             | Visitante      |
|  15641 | Suns          | Pistons          | Visitante      |
|  15642 | Suns          | Cavaliers        | Visitante      |
|  15643 | Suns          | Pacers           | Local          |
|  15644 | Suns          | Bulls            | Local          |
|  15645 | Suns          | Bucks            | Local          |
|  15646 | Suns          | Magic            | Visitante      |
|  15647 | Suns          | Wizards          | Visitante      |
|  15648 | Suns          | Hawks            | Visitante      |
|  15649 | Suns          | Bobcats          | Visitante      |
|  15650 | Suns          | Heat             | Visitante      |
|  15651 | Suns          | Jazz             | Local          |
|  15652 | Suns          | Nuggets          | Local          |
|  15653 | Suns          | Trail Blazers    | Visitante      |
|  15654 | Suns          | Supersonics      | Local          |
|  15655 | Suns          | Warriors         | Visitante      |
|  15656 | Suns          | Kings            | Visitante      |
|  15657 | Suns          | Hornets          | Local          |
|  15658 | Suns          | Spurs            | Visitante      |
|  15659 | Suns          | Rockets          | Local          |
|  15660 | Suns          | Mavericks        | Visitante      |
+--------+---------------+------------------+----------------+
15660 rows in set (0,02 sec)
```
