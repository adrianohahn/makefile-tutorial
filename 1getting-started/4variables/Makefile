# Variables can only be strings
files := file1 file2
some_file:
	echo "Look at this variable: " $(files)
	touch some_file

file1:
	touch file1

file2:
	touch file2

clean:
	rm -f file1 file2 some_file