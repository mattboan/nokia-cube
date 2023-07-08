idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    REQUIRES pcd8544 esp_wifi nvs_flash freertos json esp_http_client KCONFIG)
