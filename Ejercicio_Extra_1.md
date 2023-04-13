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
