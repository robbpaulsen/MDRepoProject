# Que es MarkDown.md

## MarkDown es un lenguaje derivado del HTML, su syntaxis es muy parecida y combina un poco de XML.

## Un archivo MarkDown.md debe de contener al menos alguna de estos elementos :

1. Cabeceras
2. Estilos de Texto
3. Listas
4. Imageens
5. Links
6. Citas
7. Bloques de Codigo
8. Tablas
9. Foot Notes
10. Avisos / Notificaciones

## HEADERS - CABECERAS

# Nivel 1
## Nivel 2
### Nivel 3
#### Nivel 4
##### Nivel 5
###### Nivel 6

## Nos deja llegar hasta una profundidad de 6 niveles.

## ESTILOS DE TEXTO :
1. **Negrita**
2. _Cursiva_
3. ~~Tachado~~
4. ==Resaltado==

## Listas en Archivos .md
1. Elemento 1
2. Elemento 2
	1. SubElemento 1
	2. SubElemento 2
3. Elemento 3

## Adjuntar Imagenes a un archivo .md

### Se tiene que cuidar la syntaxis ya que MarkDown nos permite incluir imagenes que no necesariamente tenemos guardadas sino que estan en un direccion URL. La syntaxis es la que sigue :

Syntaxis para imagen en MarkDown
* [Nombre de la Imagen] (URL://de.la.imagen/que/queremos/)

Syntaxis para Imagen en Obsidian
+ ![Nombre de la Imagen](https://estono.esla.imagen)

Syntaxis para Imagen en nuestra Galeria
* ![[NombreDeLaImagenEnGaleria]]

### Acortar una liga en Obsidian
#### El MarkDown es una parte muy improtante dentro de los proyectos, entonces se le invierte mucho tiempo para que tu texto sea entendible y que lleve al lector a querer seguir leyendo. Al incluir Urls en su forma normal si tiene mucho contraste contra todo el resto del texto, pero podemos personalizar esa Url para presentarla como algo diferente y es recortando esta Url :

![[SigueEst@Ligapara saberMAS]](https://google.com/)

###### LOS SIMBOLOS QUE AGREGUE AL INICIO Y QUE SE REPITEN AL FINAL LOS AGREGUE PARA QUE SE PUEDA APRECIAR EN CRUDO COMO DEBE DE SER LA SYNTAXIS PARA PODER RECORTAR LA LIGA. DE QUEDAR DUDA SOLO ES CUESTION DE POSICIOANR EL CURSOR EN LA LINEA DE TEXTO DE LA LIGA Y NOS MOSTRARA LA SYNTXIS EN CRUDO.

## Conectando Ideas y Proyectos

### Algo muy desesperante para mi, es el saber que habia entendido la resolucion de un problema o un tema en general y no recordar el por que estaba investigando al respecto. El MarkDown por ser una vertiente de HTML y XML es muy comun trabajar con SoftLinks/Links/Ligas si al estar documentado esto nos serviria como complemento para otra idea, proyecto o simplemente agregarlo com un capitulo extra a ese proyecto que ya esta empezado, podemos hacerlo generando un link este solo debemos de colocarlo al pie de la pagina y solo aparenta ser el nombre del capitulo o tema documentado. Ejemplo;

##### SE NECESITARA MOVER EL CURSOR HACIA LA LINEA DEL TEXTO PARA PODER VER LA SYNTAXIS EN CRUDO

## CITAS en MarkDown

### Para hacer referencia a una cita o simplemente complementar la documentacion con alguna frase aspiracional aqui ya podemos jugar con los ultimos bloques que vimos.
* Listas
* Imagenes embebidas
* Paginas
* Ligas

Podemos ir agregando a cada paso de la documentacion. Siempre cuidando la Syntaxis :

                  # CITA
> "La Esperanza es el peor de los males, >pues perpetua el sufrimiento del Hombre"
>\-Friedrich Nietzsche


![[/home/ozymandias/Documents/GitHub/MarkDownProjectRepo/Img/Nietzsche.jpg]](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Nietzsche187a.jpg/220px-Nietzsche187a.jpg)

## BLOQUES DE CODIGO
Ejecutamos el siguiente comando `python3 -m http.server` para iniciar un web server en el puerto **8000** por default sino lo especificamos en nuestro bloque.


''' PYTHON3
print("El Servidor HTTP no esta activo, Porfavor dejen de escanearlo. Para el que esta usando como desquiciado SSH bruteforce, siguele dando yo tengo palomitas hechas y viendo Friends, mejor pinta con acuarela esto jamas sera lo tuyo")
'''

## TABLAS
|No | Nombre |	Apellido	| Numero de Telefono |
|--1-|---LUIS-----|----RODRIGUEZ------|--------528466132------------|