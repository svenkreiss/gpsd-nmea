# Author: Sven Kreiss <sk@svenkreiss.com>, Mar 29, 2011

SRC  = src/main.c
SRC += src/nmeaparser/nmea_parse.c
SRC += src/nmeaparser/gpsutils.c
SRC += src/nmeaparser/geoid.c

INCDIR = ./src/nmeaparser

all:main

main:$(SRC)
	gcc -lm -std=gnu99 -I$(INCDIR) $(SRC) -o main

clean:
	rm main
	
	
	
	
