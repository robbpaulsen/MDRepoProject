# Que es MarkDown.md

## MarkDown es un lenguaje derivado del HTML, su sintaxis es muy parecida y combina un poco de XML.

## Un archivo MarkDown.md debe de contener al menos alguna de estos elementos :

1. Cabeceras
2. Estilos de Texto
3. Listas
4. Imágenes
5. Links
6. Citas
7. Bloques de Código
8. Tablas
9. Foot notes
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
2. _Italica_
3. ~~Tachado~~
4. **_Negrita e Itálica**
5. **_~Negrita, Itálica y Tachado~_**

## Listas en Archivos .md
1. Elemento 1
2. Elemento 2
	1. SubElemento 1
	2. SubElemento 2
3. Elemento 3

## Adjuntar Imágenes a un archivo .md

### Se tiene que cuidar la sintaxis ya que MarkDown nos permite incluir Imágenes que no necesariamente tenemos guardadas sino que estan en un dirección URL. La sintaxis es la que sigue :

Sintaxis para imagen en MarkDown
* [Nombre de la Imagen] (URL://de.la.imagen/que/queremos/)

Sintaxis para Imagen en Obsidian
+ ![Nombre de la Imagen](https://estono.esla.imagen)

Sintaxis para Imagen en nuestra Galería
* ![[NombreDeLaImagenEnGaleria]]

### Acortar una liga en Obsidian

#### El MarkDown es una parte muy importante dentro de los proyectos, entonces se le invierte mucho tiempo para que tu texto sea entendible y que lleve al lector a querer seguir leyendo. Al incluir Urls en su forma normal si tiene mucho contraste contra todo el resto del texto, pero podemos personalizar esa Url para presentarla como algo diferente y es recortando esta Url :

![[SigueEst@Ligapara saberMAS]](https://google.com/)

## Conectando Ideas y Proyectos

### Algo muy desesperante para mi, es el saber que había entendido la resolución de un problema o un tema en general y no recordar el por que estaba investigando al respecto. El MarkDown por ser una vertiente de HTML y XML es muy común trabajar con SoftLinks/Links/Ligas si al estar documentado esto nos serviría como complemento para otra idea, proyecto o simplemente agregarlo como un capitulo extra a ese proyecto que ya esta empezado, podemos hacerlo generando un link este solo debemos de colocarlo al pie de la página y solo aparenta ser el nombre del capitulo o tema documentado. Ejemplo;

##### SE NECESITARA MOVER EL CURSOR HACIA LA LINEA DEL TEXTO PARA PODER VER LA SINTAXIS EN CRUDO

## CITAS en MarkDown

### Para hacer referencia a una cita o simplemente complementar la documentación con alguna frase aspiracional aquí ya podemos jugar con los últimos bloques que vimos.
* Listas
* Imágenes embebidas
* Páginas
* Ligas

Podemos ir agregando a cada paso de la documentación. Siempre cuidando la Sintaxis :

> "La esperanza es el peor de los males, pues prolonga el sufrimiento del hombre"
>
-- Friedrich Nietzsche


![[/home/ozymandias/Documents/GitHub/MarkDownProjectRepo/Img/Nietzsche.jpg]](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Nietzsche187a.jpg/220px-Nietzsche187a.jpg)

## BLOQUES DE CODIGO
Ejecutamos el siguiente comando `python3 -m http.server` para iniciar un web server en el puerto **8000** por default sino lo especificamos en nuestro bloque.


''' PYTHON3
print("El Servidor HTTP no esta activo, Por favor dejen de escanearlo. Para el que esta usando como desquiciado SSH bruteforce, síguele dando yo tengo palomitas hechas y viendo Friends.")
'''

## TABLAS
|No | Nombre |	Apellido	| Numero de Teléfono |
|--1-|---JOHNNY-----|----CAGE------|--------99999999------------|








