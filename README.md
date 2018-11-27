# Vim

Vim es un editor de código en terminal muy útil que tiene plugins para programar en muchos lenguajes.

> Al principio uno puede ser muy lento pero si sigues practicando llega un punto en que algo hace click y será extemadamente rápido.

Un curso muy bueno de Vim y totalmente gratuito lo encuentras en [Curso de Vim de hipertextual.com](https://hipertextual.com/archivo/tag/curso-de-vim/)

# Modos

modo normal (esc) -> hjkl para moverse.
modo insertar (i) -> Ingresa texto.
modo comandos (:) -> Para insertar comandos del editor o plugins.
modo visual(v) -> Seleccionar texto con el cursor, con comandos.
modo selección (Ctrl+G desde el modo visual) -> Reemplaza texto.
modo ex(Q): Igual a comandos pero no se devuelve al modo normal, se entra con Q y sale con ui.

# Comandos
diw: Borrar palabra donde está el cursor.
cis: Cambiar la frase en la que estoy.
ci": Cambia lo que haya entre comillas.
c/foo: Cambia lo que haya antes de "foo"
ctx: Cambia todo lo que haya hata la letra "x".
vap: Selecciona un párrafo.
.: Repertir el último comando o secuencia de comandos antes de **esc**.
dd: Borra una línea.
>>: Identar.
$: Al final de la línea.
a: Insertar al caracter siguiente.
A: Insertar al final de la línea y al caracter siguiente.
u: Deshacer.
Ctrl-r : Regresar.
gg: Primera línea del documento.
G: Final del documento.
o: Inicio de la frase.
e: Final de las palabras.
E: Final de las palabras (incluye caracteres).
w, W: Igual pero el inicio de las palabras.
b, B: Igual pero en reversa.
{}: Inicio y final del párrafo.
10+Ctrl+a: Sumará 10 al número donde estás.
10+Ctrl+x: Igual pero resta.
c: Cambiar modo.
d: Borrar.
y: copiar.
/: Buscar.
p: Pegar línea debajo.
P: Pegar en la misma línea.
Ctrl+o: Bala para un comando en el modo insertar.
Ctrl+v: {Código} de carácter especial.
ga: En el modo normal para saber el código.
R: Modo reemplazar palabras.
r: Reemplaza un caracter y modo normal.
s: Igual que el anterior pero termina en modo insertar.
~: Capitalizar mayúscula y minúscula por caracter.
U: Texto en modo visual a mayúsculas.
>: En visual toda la selección identa.
5p: Muestra lo que hay en la línea 5.
2,10p: Muestra las líneas del 2 al 10.
.,+3p: Muestra la línea donde está el cursor y 3 más hacia abajo.
.m0: Mover la línea en la que estás al principio del archivo.
4t9: Copiar la línea 4 debajo de la línea 9.
%s/Madrid/Bilbao: Reemplaza "Madrid" por "Bilbao" en todo el texto.
shell: Entrar en la shell, salor con exit.
![comando shell]
: -> Repetir el último comando desde el modo normal.
ls: Lista de buffers.
bn: Abre el buffer siguiente.
bp: Abre el buffer anterior.
bf: Abre el primer buffer de la lista.
bl: Abre el último buffer de la lista.
bd: Elimina el buffer de la lista.
wa: Guarda todos los buffers a la vez.
qa: Sale de todos los buffers a la vez.
sp: Split horizontal.
vsp: Split vertical.
sp ó vsp [archivo]: Hace split del archivo si no se indica si abre el archivo abierto.

# Manejo de paneles

Ctrl-w+w: Moverse entre paneles
Ctrl-w+h: Ir al panel de la izquierda.
Ctrl-w+j: Ir al panel de abajo.
Ctrl-w+k: Ir al panel de arriba.
Ctrl-w+l: Ir al panel de la derecha.
Ctrl-w+c ó cl: Cierra el panel.
Ctrl-w+o ó on: Mantener el panel abierto, cerrar las otras.
Ctrl-w+: Iguala la altura y anchura de los paneles.
Ctrl-w+-: Maximiza la altura del panel activo.
Ctrl-w+i: Maximiza el ancho del panel activo.
NCtrl-w+-: La altura será N filas.
NCtrl-w+i: La anchura será N columnas.
h window_moving: Ayuda.

# Manejo de pestañas
tab new: Abre una nueva pestaña.
led {ruta}: Cambia la ruta donde apunta el panel.
windo led {ruta}: Cambia la ruta donde apuntan todos los paneles de una pestaña.
Ctrl-w+t: Mueve el panel actual a una pestaña nueva.
tabe {archivo}: Abre el archivo en una nueva pestaña.
tabc: Cerrar todas las pestañas menos la actual.
tabn {N}: Ir a la pestaña N.
tanp: Ir a la pestaña anterior.
tab move [N]: Mover pestañas.
h tabpage: Ayuda

# Otros comandos útiles
b: Primera letra, palabra anterior.
gc: Última letra, palabra anterior.
w: Primera letra palabra siguiente.
e: Última letra, palabra siguiente.
f{caracter}: Va hacia adelante hasta encontrar el caracter.
F{caracter}: Igual pero en sentido contrario.
i: Repite la búsqueda del caracter.
I: Da la vuelta a la última búsqueda.

# Folding
za: Abrir o cerrar.
zo: Abrir carpeta
zc: Cerrar carpeta.
zR: Abrir todas las carpetas.
zM: Cerrar todas las carpetas.

# NerdTree
o: Abrir en ventana previa.
go: Anterior.
t: Abrir en nuevo tab.
T: Abrir en nuevo tab silenciosamente.
i: Abrir Split.
gi: Split anterior.
s: Abrir vsplit.
gs: Previsualizar en split.
gd: Ubica el paquete y lo abre.


# Algo muy pro, creando un cuadro
Ctrl+v: Entrar en modo visual
3j: Seleccionar 3 líneas hacia abajo.
r|: Reemplazar por |.
yyp: Copiar y pegar línea abajo.
Vr-: Reemplazar por -
gv: Repetir selección anterior.








