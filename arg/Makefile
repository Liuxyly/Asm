MAIN = args
OBJ = $(MAIN).o

args:$(OBJ)
	ld -s -o $(MAIN) $(OBJ)
$(MAIN).o: $(MAIN).s

.PHONY:clean
clean:
	rm $(MAIN) $(OBJ)
