idf_component_register(SRCS "websocket_client.c"
                    INCLUDE_DIRS "include"    
                    REQUIRES esp_websocket_client esp_event
                    )
