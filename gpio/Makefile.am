bin_PROGRAMS = gpio
gpio_SOURCES = gpio.c readall.c
gpio_CPPFLAGS = -Wall -Wextra -I. -I../wiringPi -I../devLib -pthread
gpio_LDFLAGS = -lcrypt -lpthread -lrt -lm
gpio_LDADD = ../wiringPi/libwiringPi.la ../devLib/libwiringPiDev.la

