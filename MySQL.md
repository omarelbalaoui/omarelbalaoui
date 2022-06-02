<h1 align="center">Instal·lació i configuració: MYSQL</h>
<h3> Durant aquest document podem veure les deferents formes que tenim per crear i utilitzar una base de dades a mysql</h3>

<p>Per començar aquesta instal·lació anem a actualitzar el sistema amb les comandes "apt-get update" i "apt-get upgrade"</p>

<h4>Entorn de comandes</h4>
<p>A continuació instal·lem el server mysql amb la següent comanda:</p>

![Selecció_2061](https://user-images.githubusercontent.com/82141541/171621533-c457c40c-d5c9-4b39-adf8-a4d5eb6fc019.png)

<p>Una vegada hem pogut instal·lar el servidor tenim el fitxer debian.cnf ubicat a "/etc/mysql" que conte un dels usuaris que tenim per accedir al servidor, com es comprova efectivament podem accedir al servidor amb l'usuari indicat al fitxer:</p>

![Selecció_2062](https://user-images.githubusercontent.com/82141541/171622014-2acd5427-e6f6-498b-b4b4-1602b323a06c.png)


<p>Creem la base de dades anomenada "tasks"</p>

![Selecció_2063](https://user-images.githubusercontent.com/82141541/171622122-ae173245-fb0e-45be-9d22-ccfbb7642433.png)

<p>I a continuació creem la taula tasques dins de la base de dades creada anteriorment</p>

![Selecció_2064](https://user-images.githubusercontent.com/82141541/171622289-c99565a6-f2c6-4a57-b32c-c0ba9f44cbc0.png)

<h4>MySQL workbench</h4>
<p>Anem a la pagina web de mysql i decarreguem la següent versió del mysql workbench:</p>

![Selecció_2065](https://user-images.githubusercontent.com/82141541/171622536-3cafe91e-b343-4e3a-a5de-31c2c29fd5c2.png)

<p>A continuació intentem instal·lar el paquet pero ens dona problemes de llibreries:</p>

![Selecció_2066](https://user-images.githubusercontent.com/82141541/171622678-48fe2b12-da72-4c1f-a9b3-74873749df42.png)

<p>Utilitzem la comanda "apt-get --fix-broken install" per solucionar aquest error:</p>

![Selecció_2070](https://user-images.githubusercontent.com/82141541/171622829-50c00ec3-b739-433b-9c5c-f21bf7f570d9.png)

<p>Com es veu una vegada solucionat l'error de les llibreries l'instal·lacio es satisfactoria:</p>

![Selecció_2071](https://user-images.githubusercontent.com/82141541/171622977-607678d0-7cd0-487f-8a4e-714f8d485851.png)

<p>Una vegada hem iniciat el programa anem a edita la connexió:</p>

![Selecció_2076](https://user-images.githubusercontent.com/82141541/171623031-1fcdd878-3237-4481-a1d8-1a5801982a7c.png)

<p>



</p>

<h4>PHP Storm</h4>
<p>Anem a la tool box i iniciem aquest programa:</p>

![Selecció_2078](https://user-images.githubusercontent.com/82141541/171623278-ca3aa8f3-2ead-40e6-8922-1cafc2a6d67a.png)

<p>Creem un nou projecte:</p>

![Selecció_2079](https://user-images.githubusercontent.com/82141541/171623384-cc6fd630-8ee6-4d69-b993-4b0033a36868.png)

<p>Anem a l'apartat "database":</p>
  
![Selecció_2080](https://user-images.githubusercontent.com/82141541/171623691-59fe3fc6-fd84-4848-97ed-23b92ac7e5b6.png)
  
<p>Afegim una nova font de dades aquesta vegada sel·leccionem "MySQL"</p>

![Selecció_2082](https://user-images.githubusercontent.com/82141541/171623925-a8ad05ab-b2fe-4f28-baa6-66c30581bc90.png)

<p>Afegim les dades necessaries per fer la connexio a la base de dades:</p>

![Selecció_2084](https://user-images.githubusercontent.com/82141541/171624062-bd3448f6-2bc0-4c86-8479-83ba6f687d40.png)

<p>Per afegir una tasca cliquem botó dret a la taula que volem modificar i sel·leccionem "add rom"</p>

![Selecció_2086](https://user-images.githubusercontent.com/82141541/171624105-88ea6657-c6bf-4629-ba08-8b29300b598d.png)

<p>Afegim la fila i cliquem en "Submit" per guardar l'informació:</p>

![Selecció_2087](https://user-images.githubusercontent.com/82141541/171624437-80fbd5c3-46c2-47bd-b376-c81054e01ef5.png)

<p>Podem comprovar mitjançant l'entron de comandes que s'ha fet el canvi correctament:</p>

![Selecció_2088](https://user-images.githubusercontent.com/82141541/171624612-8493a926-39c5-43f2-b75f-e84b65c337d0.png)

<h4>PHPStorm</h4>
<p>Creem la carpeta on volem guardar el nostre projecte i executem la comanda phpstorm per obrir aquesta carpeta amb el projecte:</p>

![Selecció_2091](https://user-images.githubusercontent.com/82141541/171625019-db3e2ba3-f4ed-4564-b868-328cf40d355d.png)

<p>Creem un nou fitxer al que anomenem "index.php"</p>

![Selecció_2092](https://user-images.githubusercontent.com/82141541/171625136-eec8d9ca-f282-498b-91a0-ee1226455c77.png)

![Selecció_2093](https://user-images.githubusercontent.com/82141541/171625152-e2cc76d4-0be7-4af1-907c-8d7580dd8481.png)

<p>Aquest es el contingut del fitxer "index.pp"</p>

<p>Executem aquest fitxer com a servidor i com es veu ens mostra el missatge correctament:</p>

<p>Modifiquem el fitxer per enllaçar-ho amb un nou arxiu que es diu Task.php i fer log in a la base de dades</p>

![Selecció_2099](https://user-images.githubusercontent.com/82141541/171626016-ba6ec27a-c297-4233-a4dd-45eec7e3c538.png)

<p>Contigut del fitxer Task.php</p>

![Selecció_2098](https://user-images.githubusercontent.com/82141541/171626081-fb3b7ee5-9194-468c-992f-77d0fa9a5c1b.png)






