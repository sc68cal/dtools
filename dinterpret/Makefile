# This file was automatically generated by Spank 0.9.5
# See http://nurd.se/~noname/spank for more information

SRCS= ../common/common.c ../libdcpu/src/dcpu.c src/main.c src/debugger.c
OBJS= /tmp/dinterpret.tempfiles/..___common___common.c.o /tmp/dinterpret.tempfiles/..___libdcpu___src___dcpu.c.o /tmp/dinterpret.tempfiles/src___main.c.o /tmp/dinterpret.tempfiles/src___debugger.c.o
CFLAGS= -ggdb -std=gnu99 -Wall -I../common -I../libdcpu/include -DSPANK_COMPILER_GCC -DSPANK_ENV_UNIX -D'SPANK_NAME="untitled project"' -D'SPANK_BINNAME="dinterpret"' -D'SPANK_VERSION="0.1"' -D'SPANK_HOMEPAGE="none"' -D'SPANK_AUTHOR="author of untitled project"' -D'SPANK_EMAIL="nomail@example.com"' -D'SPANK_PREFIX=""'  `PKG_CONFIG_PATH=$PKG_CONFIG_PATH:.:spank pkg-config --cflags sdl`
LDCALL= gcc -o dinterpret /tmp/dinterpret.tempfiles/..___common___common.c.o /tmp/dinterpret.tempfiles/..___libdcpu___src___dcpu.c.o /tmp/dinterpret.tempfiles/src___main.c.o /tmp/dinterpret.tempfiles/src___debugger.c.o `PKG_CONFIG_PATH=$PKG_CONFIG_PATH:.:spank pkg-config --libs sdl` 
COMPILER=gcc
TARGET=dinterpret

all: dinterpret

/tmp/dinterpret.tempfiles/..___common___common.c.o: ../common/common.c
	@-mkdir -p /tmp/dinterpret.tempfiles
	@$(COMPILER) -c ../common/common.c -o /tmp/dinterpret.tempfiles/..___common___common.c.o $(CFLAGS)

/tmp/dinterpret.tempfiles/..___libdcpu___src___dcpu.c.o: ../libdcpu/src/dcpu.c
	@-mkdir -p /tmp/dinterpret.tempfiles
	@$(COMPILER) -c ../libdcpu/src/dcpu.c -o /tmp/dinterpret.tempfiles/..___libdcpu___src___dcpu.c.o $(CFLAGS)

/tmp/dinterpret.tempfiles/src___main.c.o: src/main.c
	@-mkdir -p /tmp/dinterpret.tempfiles
	@$(COMPILER) -c src/main.c -o /tmp/dinterpret.tempfiles/src___main.c.o $(CFLAGS)

/tmp/dinterpret.tempfiles/src___debugger.c.o: src/debugger.c
	@-mkdir -p /tmp/dinterpret.tempfiles
	@$(COMPILER) -c src/debugger.c -o /tmp/dinterpret.tempfiles/src___debugger.c.o $(CFLAGS)

dinterpret: $(OBJS)

	 @$(LDCALL)

clean:
	@-rm -f /tmp/dinterpret.tempfiles/..___common___common.c.o
	@-rm -f /tmp/dinterpret.tempfiles/..___libdcpu___src___dcpu.c.o
	@-rm -f /tmp/dinterpret.tempfiles/src___main.c.o
	@-rm -f /tmp/dinterpret.tempfiles/src___debugger.c.o
	@-rm -f $(TARGET)
