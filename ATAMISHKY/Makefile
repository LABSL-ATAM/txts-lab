all: clean docu view

docu: 
	pandoc -s -S --toc ayuda.md -B header.html -A footer.html -o DOCUMENTACION.html

clean: 
	rm DOCUMENTACION.html

view:
	opera DOCUMENTACION.html
