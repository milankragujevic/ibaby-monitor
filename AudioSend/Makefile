OBJS=AudioSend.o

all:${OBJS}

%.o : %.c
	$(CC) ${CFLAGS} ${INC} ${LIBS} -c -o $@ $^
	
clean:
	rm -f *.o
	
