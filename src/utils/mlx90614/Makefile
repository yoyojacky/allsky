#
# Oleg Kutkov <elenbert@gmail.com> (July 2016)
#

CC := gcc
PROGRAM = read_mlx90614
SRC := mlx90614.c
CFLAGS := -Wall -std=gnu99
TARGET_DIR := /opt/allsky/bin

all: $(PROGRAM)

$(PROGRAM): $(OBJECTS)
	$(CC) $(CFLAGS) $(SRC) -o $(PROGRAM)

install:
	mkdir -p $(TARGET_DIR)
	cp $(PROGRAM) $(TARGET_DIR)

clean:
	rm -fr $(PROGRAM) $(PROGRAM).o
