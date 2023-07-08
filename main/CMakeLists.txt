idf_component_register(SRCS "esp32_nat_router.c"
                            "http_server.c"
                    INCLUDE_DIRS "."
                    REQUIRES esp_lcd esp_http_server cmd_router cmd_nvs
                    cmd_system fatfs wpa_supplicant ssd1306)
