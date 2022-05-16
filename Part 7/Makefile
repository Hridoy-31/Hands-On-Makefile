files := file1 file2

some_target: $(files)
	echo "Look at the dependencies = " $(files)
	touch some_target

file1:
	touch file1

file2:
	touch file2

clean:
	rm -f $(files) some_target