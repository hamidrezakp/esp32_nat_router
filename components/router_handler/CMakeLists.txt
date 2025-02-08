idf_component_register(SRCS router_handler.c 
                            
                    INCLUDE_DIRS include
                    REQUIRES cmd_router utils
					PRIV_REQUIRES lwip esp_netif
				)
