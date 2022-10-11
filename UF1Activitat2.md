# LLENGUATGE INTERPRETAT

## RUBY


**INTERPRETAT**
No es tradueix tot de cop i s’executa directament el codi màquina sinó que l’intèrpret (un altre programa) s’encarrega d’anar executant indirectament el codi instrucció per instrucció.

###### EXEMPLE :

![image](https://user-images.githubusercontent.com/114908591/195207824-f3afec8c-86fe-4c72-93ee-08beeeb62a47.png)


Descarguem el ruby

![image](https://user-images.githubusercontent.com/114908591/195208010-2d276b7a-e1fe-48b6-a8e4-a1a17601d3ae.png)


Aquí hem mirat la versió.

![image](https://user-images.githubusercontent.com/114908591/195208069-b384d113-6038-48ec-89c4-692cdb7a80cd.png)


Amb el nano hem creat un hello world.


![image](https://user-images.githubusercontent.com/114908591/195208112-458f6f4d-975c-4f65-9d63-a897d28504c9.png)


El nom de l’executable és .rb (hello_world.rb).
Ruby és l’executable.
![image](https://user-images.githubusercontent.com/114908591/195208145-206e8755-d538-4dcb-8974-c113af18b2e5.png)


Aquí hem posat un exemple, el “irb” serveix per a fer operacions.
![image](https://user-images.githubusercontent.com/114908591/195208196-fc88873d-18ce-431a-aea0-483d23b7e6fc.png)
![image](https://user-images.githubusercontent.com/114908591/195208262-00ba2e3d-0b34-444d-9ae5-b5714c835a59.png)




Aquí ja tenim el codi bé i ens dona un número aleatori de entre l’1 i el 6.
### Avantatges:

- És independent de la màquina i del sistema operatiu, ja que no conté instruccions pròpies d'un processador sinó que conté trucades a funcions que l'intèrpret haurà de reconèixer. 

- A més, un llenguatge interpretat permet modificar en temps d'execució el codi que s'està executant així com afegir-hi nou

### Desavantatges:

- Velocitat. És l'aspecte més notable.

- Portabilitat. Ja que gairebé tots els llenguatges compilats, existeixen per a totes les plataformes, no així les màquines virtuals o frameworks, encara que en el cas de Java, s'ha fet un excel·lent treball pel que fa a això.

### IDE PER A DESARROLLADORES DE RUBY
-  **Aptana Studio**: suporta les últimes tecnologies per a navegadors amb HTML5, CSS3L JavaScript, Ruby, etc.
- **Net Beans**: estaba pensat per desenvolupar en Java pero és comaptible amb JavaFX, PHP, JavaScriopt, Ruby, etc.
- **RubyMine**: té tot el que un desenvolupador de Rubt necessita en un entorn de desnvolupament.


Webs visitades:

https://openwebinars.net/blog/que-es-ruby/ 
https://www.rubyguides.com/2015/03/ruby-random/
https://apuntes.de/ruby/la-linea-de-comandos/#gsc.tab=0
https://www.ecured.cu/Lenguaje_interpretado#Ventajas
https://programacion.net/articulo/los_5_mejores_ides_para_ruby_on_rails_1077

# LLENGUATGE COMPILAT

## C

El compilador no és més que un traductor entre el llenguatge d’alt nivell i el codi màquina, entre el que entenen les persones i el que entén la CPU.

### Avantatges
- **Multiplataforma:** el llenguatge C pot ser executat en qualsevol tipus de programari o maquinari.
- **Ús de llenguatge eficient:** Utilitza llenguatge compilat i s’acobla de manera efectiva amb el llenguatge assemblador, així com també és el que millor aprofita la CPU de la màquina.
- **Alt nivell d’exercici:** el primer que has de saber sobre el llenguatge C és que es molt eficient per fer trucades directes al sistema operatiu.
- **Té ús eficient** de la memòria i compta am **funcions i variables estàtiques**
### Desavantatges
- **Llenguatge incomplet:** no té prou operadors per fer més abstracta la traducció del sistema. No té un llenguatge visual, per lo que impedeix que es pugui deduir intuïtivament.
- **Manca de funcions:** no té alliberament de memòria automàtica, lo que significa que ho hauràs de fer manualment. No tè suport per a la programaciò orientada a objectes.
- **No permet checking a temps d’execució:** el llenguatge C mostra el error després d’haver compilats estos, en lloc de fer-ho en temps d’execució.

### IDE PER A DESARROLLADORES DE C

- **Virtual Studio:** 
	- Compatible amb: Windows, macOS i Linux.
	- Finalització de codi usant IntelliSense.
	- Integració Git incorporada.
	- Fácil desenvolupament d’Azure.
	- Suport integrat de depurador i VCS.
- **Xcode:**
	- Compatible amb macOS.
	- Depurador gràfic.
	- Anàlisi de codi estàtic.
	- Documentació completa.
	- Integració contínua.
- **Eclipse:**
	- Comunitat rica i de codi obert.
	- Compatible amb: Windows, macOS i Linux.
	- Creació de projectes més senzilla.
	- Admet anàlisi de codi estàtic.
	- Fàcil depuració.







Aquí hem instal·lat el gcc per a poder fer servir coses del c.
El “gcc -o ___” és el comando per a passar de codi font a codi executable.
El nom de l’executable és .c.



Hem creat amb el gedit un fitxer i hem ficat aquest codi per a que ens digue un número aleatori de l’1 al 6:




Passem de codi font a codi executable.


Això és el resultat



##### BIBLIOGRAFIA
https://vitux.com/how-to-write-and-run-a-c-program-in-linux/
https://itsfoss.com/run-c-program-linux/
https://linuxhint.com/rand-function-in-c-language/ (exemples de ranomcommand
https://www.geeksforgeeks.org/generating-random-number-range-c/














Aquí hem instal·lat el python3.

Amb el touch creem un fitxer.
EL “chmod +x” és per a passar de codi font a codi executable.


Aquest és el codi.


El resultat.
Python3 és per a mostrar el resultat.

A bytecode:


el nom de l’executable és .py.
el comando és python -m (he posat 3 perquè m’he descarregat el 3)

(no puc obrir-ho però és el bytecode).

### AVANTATGES
- Es arriben a executar en qualsevol plataforma.
- No ocupen gairebé espai a la memòria.
- L’entorn de la feina és el que s’arriba a encarregar de que el maquinari executa les instruccions que se’ls doni.
- Les variables de dades utilitzades arriben a ser dinàmiques pel que no es restringeixen a un tipus en específic.
- Aquest llenguatges són molt utilitzats en el desenvolupament web i de l’electrònica.

### DESAVANTATGES
- L’execució d’aquests llenguatges és més lenta a diferència del llenguatges compilats.
- Són difícils de depurar.
- Es necessita d’un programari que serveix per interpretar les instruccions del processador.
- No tots el programes es troben disponibles en totes les plataformes..




###### IDES
PyCharm.
KDevelop.
SlickEdit.



### WEBGRAFIA
https://www.clubdetecnologia.net/blog/2014/lenguajes-alternativos-de-la-java-virtual-machine/
https://askubuntu.com/questions/244378/running-python-file-in-terminal
https://linuxhint.com/run-python-scripts-linux/
https://opensource.com/article/18/4/introduction-python-bytecode 
https://programacion.net/articulo/los_5_mejores_ides_para_ruby_on_rails_1077 
https://www.crehana.com/blog/transformacion-digital/ventajas-desventajas-lenguaje/ 
https://es.acervolima.com/10-mejores-ide-para-desarrolladores-de-c-o-c-en-2021/ 
