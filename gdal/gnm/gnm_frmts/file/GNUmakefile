

include ../../../GDALmake.opt

OBJ	=	gnmfiledriver.o gnmfilenetwork.o

CPPFLAGS	:=	-I. -I../ -I../../ $(CPPFLAGS)

default:	$(OBJ:.o=.$(OBJ_EXT))

clean:
	rm -f *.o $(O_OBJ)
	rm -f *.lo $(O_OBJ)

install-obj:	$(O_OBJ:.o=.$(OBJ_EXT))



