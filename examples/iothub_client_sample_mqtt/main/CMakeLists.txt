set(COMPONENT_SRCS 
			"custom_hsm_x509.c" 
			"iothub_client_sample_mqtt.c"
			"azure_main.c"
			)
set(COMPONENT_ADD_INCLUDEDIRS ".")

set(COMPONENT_EMBED_TXTFILES "certs/device_cert.pem")

register_component()

component_compile_definitions(SET_TRUSTED_CERT_IN_SAMPLES)
