# SPDX-License-Identifier: EPICS
TOP=../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE

#----------------------------------------------------
#  Optimization of db files using dbst (DEFAULT: NO)
#DB_OPT = YES

#----------------------------------------------------
# Create and install (or just install) into <top>/db
# databases, templates, substitutions like this
#DB += xxx.db
DB += Phytron_AIO.db
DB += Phytron_AIO_MCC.db
DB += Phytron_CMD.db
DB += Phytron_DIO.db
DB += Phytron_DIO_MCC1.db
DB += Phytron_I1AM01.db
DB += Phytron_MCC.db
DB += Phytron_MCM01.db
DB += Phytron_motor.db

#----------------------------------------------------
# If <anyname>.db template is not named <anyname>*.template add
# <anyname>_template = <templatename>

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

