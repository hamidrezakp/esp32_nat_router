idf_component_register(SRCS request_handler.c response_handler.c get_data_handler.c
                            storage_handler.c auth_handler.c web_server.c
                    
                    INCLUDE_DIRS include 
                    EMBED_FILES www/output/gzip/dark.css.gz www/output/gzip/error_404.html.gz www/output/gzip/functions.js.gz www/output/gzip/index.html.gz www/output/gzip/info.html.gz www/output/gzip/info.js.gz www/output/gzip/main.css.gz www/output/gzip/scan.js.gz www/output/gzip/settings.html.gz www/output/gzip/settings.js.gz
                    REQUIRES esp_http_server esp-tls json esp_http_client utils 
                                cmd_router cmd_nvs ota_handler wifi_handler)



