idf_component_register(SRCS "cmd_system_sleep.c" "cmd_system.c" "cmd_system_common.c"
                    INCLUDE_DIRS .
                    REQUIRES console spi_flash driver)

target_sources(${COMPONENT_LIB} PRIVATE cmd_system_sleep.c)
