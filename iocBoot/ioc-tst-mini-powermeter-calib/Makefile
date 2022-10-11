IOC_TOP = /cds/group/pcds/epics/ioc/common/ads-ioc/R0.6.0

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = lcls-plc-mini-powermeter-calib
PROJECT_PATH := ../../lcls-plc-mini-powermeter-calib/lcls-plc-mini-powermeter-calib.tsproj
PLC = mini_powermeter_calib

PYTMC_OPTS :=
PREFIX = PLC:TST:WFS:SPM:CALIB

include $(IOC_TOP)/iocBoot/templates/Makefile.base

