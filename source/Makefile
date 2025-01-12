objs = ursheet.o solver.o
flags = -Wall -Wextra -Wpedantic -std=c11 -Wno-switch
exec = ursh

all: $(exec)

$(exec): $(objs)
	gcc	-o $(exec) $(objs)

%.o: %.c
	gcc	-c $< $(flags)

clean:
	rm	-rf $(objs) $(exec)
