objects = first.o second.o final.o

all: $(objects)

$(objects): %.o: %.c

all.c:
	echo "int main() { return 0; }" > all.c

%.c:
	touch $@

clean:
	rm -f *.o *.c all
