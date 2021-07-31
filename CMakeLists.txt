idf_component_register(
    SRCS lora.c
    INCLUDE_DIRS .
    REQUIRES freertos esp_system driver soc
)