all: clean docu view

docu: 
	pandoc -s -S --toc ayuda.md -B header.html -A footer.html -c nah.css -o DOCUMENTACION.html

clean: 
	rm DOCUMENTACION.html

view:
	firefox DOCUMENTACION.html
