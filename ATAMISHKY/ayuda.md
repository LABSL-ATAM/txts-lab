
-----------------------------------------------------------------------

# Atamishky

**Atamishky** es el nombre con el que bautizamos a nuestro sistema de búsquedas y referencias bibliográficas.

## ¿Cuál es su finalidad?

Su idea fundacional es implementar un sistema que instrumente la **búsqueda de material bibliográfico** en nuestra Mediateca, para brindarle accesibilidad y presencia online. 

Desde la perspectiva institucional, permite relevar el material bibliográfico y gestionar préstamos. Desde el punto de vista del usuario, posibilita la interacción, criterios de filtrado dinámicos y búsqueda por campos accesible y eficaz.

## ¿Quiénes lo desarrollaron?

Pertenece al **Área Transdepartamental de Artes Multimediales** de la **Universidad Nacional de Arte** (UNA) y su desarrollo se enmarca dentro de las actividades del **[Laboratorio de Software Libre](https://labsl.multimediales.com.ar)** del Área (bajo la coordinación de Gustavo Yzaguirre). Durante su desarrollo, nos ajustamos a las necesidades y requerimientos de nuestra Mediateca (bajo la coordinación de Juan Viera).

El desarrollo _comenzó en el 2015_ y **sigue activo al día de la fecha**. El sistema puede ser [descargado y utilizado libremente](https://github.com/LABSL-ATAM/atamishky), bajo las cláusulas del software libre.

Se basó en BeBop, un sistema de búsqueda con backend Java/BibTeX del cual todavía quedan reminiscencias de su arquitectura y backend aunque la mayoría ha sido reescrito en favor de nuestra implementación.

## Características

Brevemente, estas son las características principales de Atamishky:

-
-
-
-
-



-----------------------------------------------------------------------

# Sobre la tecnología involucrada (notas para administradores)

## Instalación

## Backend

## ¿Cómo realizo la conversión del catálogo para ser levantado por Atamishky?

## ¿Cómo realizo los hashs de verificación de los archivos xslt?

## ¿Cómo cambio la contraseña de los préstamos?

-----------------------------------------------------------------------

# Sobre la interfaz

## Acerca de la forma de uso del buscador

Para comenzar una búsqueda, utilice la solapa de la izquierda y
seleccione el criterio de filtrado.

**Todas las búsquedas son indiferentes a mayúsculas y minúsculas**
(case-insensitive).

## Criterios de búsqueda predefinidos

Puede seleccionar alguno de los siguientes criterios:

-   TODO
-   Título
-   Autor
-   Descripción
-   Libros
-   Música
-   Videos
-   Otros

Los primeros cuatro criterios afectan a cualquier tipo de material: es
indistinto si es un libro o una película, por ejemplo.

Si la opción **Título** es utilizada como criterio, se buscan todos los
títulos que coincidan con el texto introducido.

Similarmente, si se utiliza el texto buscado como parte de la
**descripción** de algun material bibliográfico del catálogo, bajo una
búsqueda del mismo criterio, se conforma una lista de las entradas
resultantes.

*Por ejemplo, si un grupo de peliculas incluyen la palabra "Audiovision"
en su descipcion, buscando por **Descripción** el texto "audiov" el
grupo completo aparece en los resultados (posiblemente acompañado de
resultados adicionales, ya que el texto introducido no es exactamente
"audiovision", pero coincide).*

La opción **Autor** filtra en la lista total de autores, por los nombres
y/o apellidos que lo incluyan. Asi, "ado" incluye a Adorno y a Adolfo
Bioy Casares como resultados posibles, por ejemplo.

Los últtimos cuatro criterios, en cambio, *buscan cualquier texto en los
materiales que concuerden con el tipo*: por ejemplo, una búsqueda de
"music" en el criterio por defecto (TODOS) va a mostrar como resultados
validos materiales que pueden ser del tipo libro o música. En cambio, si
se utiliza el criterio **Libros**, todas las entradas que no sean de
este tipo son filtradas de antemano: busca únicamente en el caso de las
entradas del catálogo que pertenezcan al mismo tipo.

## Criterios de búsqueda dinámicos

Adicionalmente, **es posible utilizar -casi- cualquier criterio como
filtrado dinámico**: autores, títulos, idiomas, soporte, editoriales...
Alcanza con cliquear en el enlace para convertir al elemento en un
filtro.

En el encabezado de la página se especifica el tipo de filtrado actual.

## Criterios de organización del catálogo adicionales

Estos son dos (por el momento) y funcionan como colecciones de
referencias: una categorización inmediatamente superior al tipo de
material que agrupa varias entradas y funciona como conjunto.

-   Tag
-   Bibliografia

Los **tags** o etiquetas, sirven para clasificar cualquier referencia
acorde a un concepto, que permita relacionar varias entradas.

La opción **ver todos** muestra la lista de tags completa; los tags con
mayores ocurrencias dentro del catálogo se ven mas grandes. Para ver los
tags relacionados a alguna entrada en particular, alcanza con consultar
la informacion detallada de la entrada, a través del enlace **mas info**
de la derecha.

-------------------------------------------------------------------------------

# Notas adicionales para los gestores y administradores de bibliotecas

## ¿Cómo organizo el catálogo?

## ¿Cómo exporto en CSV?

## ¿Cómo gestiono los préstamos?

-------------------------------------------------------------------------------

# Apéndices

## 1. Licencia Atamishky

Por el momento, el software es distribuído bajo la licencia WTFPL.


```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2016 LABSL-ATAM (MarxBro aka G.Yz) <labsl@cpamvirtual.com.ar>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```


## 2. Licencia BeBop

``` 
 
Copyright (c) 2006-2009, Universita della Svizzera Italiana,
Faculty of Informatics, Advanced Learning and Research Institute (ALaRI),
Onur Derin, All rights reserved.

Redistribution and use in source and binary forms, with or without modification, 
are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list 
of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this 
list of conditions and the following disclaimer in the documentation and/or other 
materials provided with the distribution.

3. Neither the name of ALaRI nor the names of its contributors may be used to endorse 
or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY 
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES 
OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT 
SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, 
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, 
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, 
STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT 
OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

The licenses for the third party libraries used in this software can be found
alongside with the third party libraries in relevant folders of this software.
```
