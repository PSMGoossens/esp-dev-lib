#idf_component_register(SRCS "smbus.c" INCLUDE_DIRS include)

set(COMPONENT_ADD_INCLUDEDIRS include)
set(COMPONENT_SRCS "qwiic_twist.c")

set(COMPONENT_PRIV_REQUIRES "esp32-smbus")

register_component()
