idf_component_register(SRCS "main.c" "ecc_task.c"
                       INCLUDE_DIRS "."
		       REQUIRES mbedtls micro-ecc)
