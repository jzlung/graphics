CC = g++
ifeq ($(shell sw_vers 2>/dev/null | grep Mac | awk '{ print $$2}'),Mac)
	CFLAGS = -g -DGL_GLEXT_PROTOTYPES -I./include/ -I/usr/X11/include -DOSX -Ieigen/ -O1
	LDFLAGS = -framework GLUT -framework OpenGL \
    	-L"/System/Library/Frameworks/OpenGL.framework/Libraries" \
    	-lGL -lGLU -lm -lstdc++
else
	CFLAGS = -g -DGL_GLEXT_PROTOTYPES -Iglut-3.7.6-bin -Ieigen/ -w -O1
endif
	
RM = /bin/rm -f 
all: main 
main: as4.o 
	$(CC) $(CFLAGS) -o as4 as4.o $(LDFLAGS) -w
as4.o: as4.cpp
	$(CC) $(CFLAGS) -c as4.cpp -o as4.o -w
clean: 
	$(RM) *.o as4
 


