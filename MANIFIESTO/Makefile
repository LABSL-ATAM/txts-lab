all: pdf odt html manpage

pdf: 
	pandoc MANIFIESTO.md -o MANIFIESTO.pdf

odt:
	pandoc -s MANIFIESTO.md -o MANIFIESTO.odt

html:
	pandoc -s MANIFIESTO.md -o MANIFIESTO.html

manpage:
	pandoc -t man -s MANIFIESTO.md -o MANIFIESTO.1

clean:
	rm MANIFIESTO.pdf MANIFIESTO.html MANIFIESTO.odt MANIFIESTO.1


