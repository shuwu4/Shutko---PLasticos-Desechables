Base de datos con ruby uwu

Bloc de notas que wa usar nomás pa' mamar jasjdasd
k no se me olvide borrarlo pq va a estar lleno de majaderías

Aquí vamos, tenemos k usar la terminal, qie en visual code sale desde "View" y "Show panel"
La neta no me descargué la traducción

Apenas estoy aprendiendo ruby así que es mi primera apliucación del mismo, ¡qué emocionante!

La instalación de ruby en el subsistema de linux fue realizada con los comandos de:
https://github.com/aprendev-com/curso-rails-principiantes/wiki/Instalar-Ruby-on-Rails-en-Linux

---------------	sudo service postgresql start--------------

para iniciar un servidor usando postrgresql xd
MUY IMPORTANTE!!!!!!!!!!!!!!

El usuario de ubuntu es: shut4

Por si acaso, se abrirá el servidor haciendo "SQL shell(psql)" junto con el pgadmin

Al parecer es necesario crear la carpeta en la raíz
o sea, cd y luego rails new
Luego la movemos hasta un directorio del disco C


Crearemos la carpeta necesaria para el uso de la
mediante el comando 

	rails new *Nombre de la carpeta*

El servidor se "prende" utilizando el comando

	rails server

La base de datos se aloja en http://localhost:3000 a menos que se especifique lo contrario

Ya que se me enclocha la consola de comandos, los productos serán:
sin mencionar los que se pueden añadir después c:

Product.create(title: "Tupper para quesadillas", description: "Su material rígido y resistente es ideal para conservar los alimentos frescos y en buen estado, vamos ¿A quién no le gusta una buena quesadilla?", price: 100)
Product.create(title: "Cuadriluch para sandwich", description: "Por ser un producto indeformable, fabricado con material rígido de alta densidad, es resistente a las ralladuras y de gran durabilidad, lo que lo hace ideal para el lunch de los niños.", price: 140)
Pero es más fácil ahora que está bien diseñado el catálogo

Novedad 26/05/2022

Ya se puede abrir la pagina en internet a trabvés del link
"www.shutko.herokuapp.com"

De lo contrario, las vistas HTML locales, solo accederpan  la página de internet si
 - Se tiene instalado ubuntu como subsistema de windows
 - Se tiene instalado ruby en la versión 3.1.2
 - Se tiene instalado rails
 - Se tiene instalado postresql


Se aplica el mismo principio.
Te localizas en la carpeta "Deko/catalogo"
 haces bundler, rails db:create, rails db:migrate, y finalmente rails s
una vez iniciado el servidor (Con rails s) se accede a localhost:3000 en el navegador y listoooOoO c:
