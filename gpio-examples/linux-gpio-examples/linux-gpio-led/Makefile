PROJ=gpio-led
SRC=led_gpio.c
CFLAGS=-D CONSUMER=\"$(PROJ)\"

all:
	$(CC) $(SRC) $(CFLAGS) -o $(PROJ)

clean:
	rm $(PROJ)