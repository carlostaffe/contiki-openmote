CONTIKI_PROJECT = modbus-master
all: $(CONTIKI_PROJECT)

PROJECT_SOURCEFILES += modbusProtocol.c modbus-api.c rs485-dev.c
CFLAGS += -DPROJECT_CONF_H=\"project-conf.h\"

CONTIKI = ../..
include $(CONTIKI)/Makefile.include
