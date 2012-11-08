pkglib_LIBRARIES = libdwengo.a

nobase_pkginclude_HEADERS = \
compiler.h \
dwengoADC.h \
dwengoBluetooth.h \
dwengoBoard.h \
dwengoClock.h \
dwengoConfig.h \
dwengoDelay.h \
dwengoI2C.h \
dwengoInterrupt.h \
dwengoLCD.h \
dwengoMotor.h \
dwengoRC.h \
dwengoSensorModule.h \
dwengoServo.h \
dwengoTimer.h \
dwengoUsart.h \
compiler/mplabc18.h \
compiler/pwm.h \
compiler/sdcc_pic16.h \
compiler/sdcc_pic16_pwm.h

libdwengo_a_SOURCES = \
dwengoADC.c \
dwengoBluetooth.c \
dwengoBoard.c \
dwengoClock.c \
dwengoDelay.c \
dwengoI2C.c \
dwengoInterrupt.c \
dwengoLCD.c \
dwengoMotor.c \
dwengoRC.c \
dwengoSensorModule.c \
dwengoServo.c \
dwengoTimer.c \
dwengoUsart.c


### Redefine implicit (suffix) rule to convert form .c to .o
.c.o:
	$(MCC_C) $(MCCFLAGS) $<

### Redefine library rule
libdwengo_a_AR = $(MCC_L) -q -c

# ; $(MCC_L) -q -r
