Instituto Tecnológico del Suroccidente 
Mazatenango Suchitepéquez 
Cuarto bachillerato en Ciencias y letras 
Waldir Castillo Mota 
Computación 





Investigación:
Etiquetas HTML






Sophía Alejandra López García 
25/03/2022






Puesta en forma de los caracteres
<B>…</B>	Texto en negrita
<BIG>…</BIG>	Ampliación del tamaño de los caracteres
<BLINK>…</BLINK>	Texto parpadeante (Netscape solo)
<EM>…</EM>	Texto en itálico
<FONT color=»#XXXXXX»>
…</FONT>	Texto en color donde
XXXXXX es un valor hexadecimal
<FONT size=X>…</FONT>	Tamaño de los caracteres donde
X es un valor de 1 a 7
<I>…</I>	Texto en itálico
<NOBR>…</NOBR>	Impide las rupturas automáticas
de línea de los browser
<PRE>…</PRE>	Texto preformateado, o sea con una visualización
de todos los espacios y saltos de línea
<SMALL>…</SMALL>	Reducción del tamaño de los caracteres
<STRONG>…</STRONG>	Puesta en negrita del texto
<SUB>…</SUB>	Texto en indicio
<SUP>…</SUP>	Texto en exponente
<U>…</U>	Texto subrayado
 
Puesta en forma del texto
<!–…–>	Comentarios ignorado por el navegador
<BR>	A la línea
<BLOCKQUOTE>…
</BLOCKQUOTE>	Citación (introduce un retracto de texto)
<CENTER>…</CENTER>	Centra cada elemento comprendido en la etiqueta
<DIV align=center> …</DIV>	Centra el elemento encuadrado por la etiqueta
<DIV align=left> …</DIV>	Alinea el elemento a la izquierda
<DIV align=right> …</DIV>	Alinea el elemento a la derecha
<Hx>…</Hx>
<Hx align=center>…</Hx>
<Hx align=left>…</Hx>
<Hx align=right>…</Hx>	Título o x tiene un valor de 1 à 7
Título centrado
Título alineado a la izquierda
Titulo alineado a la derecha
<P>…</P>
<P align=center>…</P>
<P align=left>…</P>
<P align=right>…</P>	Nuevo párrafo
Párrafo centrado
Párrafo alineado a la izquierda
Párrafo alineado a la derecha
Listas
<UL>
<LI>
</UL>	Lista no numerada
Elemento de lista
<OL>
<LI>
</OL>	Lista numerada
Elemento de lista
<DL>
<DT>…</DT>
<DD>…</DD>
</DL>	Lista de glosario
Termino de glosario (sin retracto)
Explicación del termino (con retracto)
Rayas
<HR>	Línea de separación. Raya horizontal
<HR width=»x%»>	Anchura de la raya en %
<HR width=x>	Anchura de la raya en pixeles
<HR size=x>	Altura de la raya en pixeles
<HR align=center>
<HR align=left>
<HR align=right>	Raya centrada
Raya alineada a la izquierda
Raya alineada a la derecha
<HR noshade>	Raya sin efecto de sombreado
Enlaces
<A href=»http://…»>…</A>	Enlace hacia una página Web
<A href=»mailto:…»>…</A>	Enlace hacia una dirección Email
<A href=»fichier.htm»>…</A>	Enlace hacia la página fichero.htm
situada en el mismo directorio
<A name=»xyz»>…</A>	Definición de una ancla
<A href=»xyz»>…</A>
<A href=»fichier#xyz»>…</A>	Enlace hacia una ancla
Imagenes	
<IMG scr=»xyz.gif»>
<IMG scr=»xyz.pjg>	Inserción de una imagen al formato Gif o Jpg
(ver enlaces para la dirección)	
<IMG … width=x height=y>	Puesta a la escala de la imagen en pixeles	
<IMG … border=x>	Definición del borde de una imagen con un enlace	
<IMG … alt=»votre texte»>	Texto alternativo cuando la imagen no esta mostrada	
<IMG … align=bottom>
<IMG … align=middle>
<IMG … align=top>
<IMG … align=left>
<IMG … align=right>	Alinea la imagen abajo
Alinea la imagen en el medio
Alinea la imagen arriba
Alinea la imagen a la izquierda
Alinea la imagen a la derecha	
<IMG … hspace=x>
<IMG … vspace=y>	Espaciamiento horizontal entre la imagen y el texto Espaciamiento vertical entre la imagen y el texto	
Tablas
<TABLE>…</TABLE>	Definición de una tabla
<TABLE width=»x%»>	Anchura de la tabla en %
<TABLE width=x>	Anchura de la tabla en pixeles
<TABLE border=x>	Anchura del borde
<TABLE cellpadding=x>	Espacio entre el borde y el texto
<TABLE cellspacing=x>	Espesor de la raya entre las celdas
<TR>…</TR>	Línea de la tabla
<TD>…</TD>	Celda de la tabla
<TD bgcolor=»#XXXXXX»>	Color de una celda de la tabla
<TD width=»x%»>
<TD width=x>	Anchura de columna en %
Anchura de columna en pixeles
<TD align=center>
<TD align=left>
<TD align=right>	Texto centrado en la celda
Texto alineado a la izquierda en la celda
Texto alineado a la derecha en la celda
<TD valign=bottom>
<TD valign=middle>
<TD valign=top>	Alineación hacia arriba del contenido de la celda Centrado vertical del contenido de una celda
Alineación hacia el bajo del contenido de la celda
<TD colspan=x>
<TD rowspan=x>	Numero de celdas para fusionar horizontalmente Numero de celdas para fusionar verticalmente
Frames
<FRAMESET>…</FRAMESET>	Define una estructura de frames
(reemplaza la etiqueta BODY)
<FRAMESET rows=»x%,y%,…»>	División horizontal de la ventana en %
<FRAMESET cols=»x%,y%,…»>	División vertical de la ventana en %
<FRAME src=»fichier.htm»>	Fichero mostrado en una ventana de frames
<NOFRAMES>…</NOFRAMES>	Contenido para los browser no previstos para los frames
Fichero Html
<HTML>…</HTML>	Principio y fin del fichero Html
<HEAD>…</HEAD>	Zona de encabezamiento de un fichero Html
<TITLE>…</TITLE>	Titulo visualizado por el browser (elemento de HEAD)
<BODY>…</BODY>	Principio y fin del cuerpo del fichero Html
<BODY bgcolor=»#XXXXXX»>	Color del fondo (en hexadecimal)
<BODY background=»xyz.gif»>	Imagen del fond
