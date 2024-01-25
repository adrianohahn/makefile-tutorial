blah: blah.o
	cc blah.o -o blah #Runs third

blah.o: blah.c
	cc -c blah.c -o blah.o #Runs second

# Creates blah.c
blah.c:
	echo "int main() {return 0;}" > blah.c #Runs first
