# POR: Leal Oliva Carlos Fernando
# No. Control: 18212205
# Archivo Makefile: Codigo que compila un programa definido.
# Fecha: 24//11/2020
# Materia: Lenguajez de interfaz.

# Makefile
all: teclado
programa: teclado.o  # enlazarlo para correrlo
	ld -o $@ $+
programa.o: teclado.s # compilarlo nos genera el .o
	as -g -mfpu=vfpv2 -o $@ $<
clean:   # limpiar todo que no se ocupa como lo .o basura
	rm -vf teclado *.o
