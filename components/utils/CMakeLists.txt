idf_component_register(SRCS utils.c initialization.c nvm.c mac_generator.c mac_filter.c
                            
                    INCLUDE_DIRS include
                    REQUIRES cmd_router cmd_nvs nvs_flash json esp_http_server 
                    driver esp_hw_support esp_timer efuse)