idf_component_register(SRCS "main.c"
                       INCLUDE_DIRS "."
                       EMBED_FILES "index.html"
                       REQUIRES esp_wifi esp_http_server nvs_flash esp_hal_ledc esp_driver_ledc)
