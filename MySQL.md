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

<h4>PHP Storm<h4>
<p>Anem a la tool box i iniciem aquest programa:</p>

![Selecció_2078](https://user-images.githubusercontent.com/82141541/171623278-ca3aa8f3-2ead-40e6-8922-1cafc2a6d67a.png)

<p>Creem un nou projecte:</p>

![Selecció_2079](https://user-images.githubusercontent.com/82141541/171623384-cc6fd630-8ee6-4d69-b993-4b0033a36868.png)

  
  
