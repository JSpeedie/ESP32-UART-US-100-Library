set(srcs "us-test.c")

idf_component_register(SRCS "${srcs}"
                    REQUIRES driver
                    PRIV_REQUIRES esp32-uart-us-100
                    INCLUDE_DIRS ".")
