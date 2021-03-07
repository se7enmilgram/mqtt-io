- [**MQTT IO**](/)

- Configuration

  - [Usage Scenarios](config/scenarios.md)
  - [Interrupts](config/interrupts.md)
  - [Home Assistant Discovery](config/ha_discovery.md)
  - [Validation](config/validation.md)
  - Section Reference
    - [mqtt](config/reference/mqtt/)
        - [- host](config/reference/mqtt/?id=mqtt-host)
        - [- port](config/reference/mqtt/?id=mqtt-port)
        - [- user](config/reference/mqtt/?id=mqtt-user)
        - [- password](config/reference/mqtt/?id=mqtt-password)
        - [- client_id](config/reference/mqtt/?id=mqtt-client_id)
        - [- topic_prefix](config/reference/mqtt/?id=mqtt-topic_prefix)
        - [- clean_session](config/reference/mqtt/?id=mqtt-clean_session)
        - [- protocol](config/reference/mqtt/?id=mqtt-protocol)
        - [- keepalive](config/reference/mqtt/?id=mqtt-keepalive)
        - [- status_topic](config/reference/mqtt/?id=mqtt-status_topic)
        - [- status_payload_running](config/reference/mqtt/?id=mqtt-status_payload_running)
        - [- status_payload_stopped](config/reference/mqtt/?id=mqtt-status_payload_stopped)
        - [- status_payload_dead](config/reference/mqtt/?id=mqtt-status_payload_dead)
        - [- client_module](config/reference/mqtt/?id=mqtt-client_module)
        - [- ha_discovery](config/reference/mqtt/?id=mqtt-ha_discovery)
          - [- enabled](config/reference/mqtt/?id=mqtt-ha_discovery-enabled)
          - [- prefix](config/reference/mqtt/?id=mqtt-ha_discovery-prefix)
          - [- name](config/reference/mqtt/?id=mqtt-ha_discovery-name)
        - [- tls](config/reference/mqtt/?id=mqtt-tls)
          - [- enabled](config/reference/mqtt/?id=mqtt-tls-enabled)
          - [- ca_certs](config/reference/mqtt/?id=mqtt-tls-ca_certs)
          - [- certfile](config/reference/mqtt/?id=mqtt-tls-certfile)
          - [- keyfile](config/reference/mqtt/?id=mqtt-tls-keyfile)
          - [- cert_reqs](config/reference/mqtt/?id=mqtt-tls-cert_reqs)
          - [- tls_version](config/reference/mqtt/?id=mqtt-tls-tls_version)
          - [- ciphers](config/reference/mqtt/?id=mqtt-tls-ciphers)
          - [- insecure](config/reference/mqtt/?id=mqtt-tls-insecure)
    - [gpio_modules](config/reference/gpio_modules/)
    - [sensor_modules](config/reference/sensor_modules/)
    - [stream_modules](config/reference/stream_modules/)
    - [digital_inputs](config/reference/digital_inputs/)
    - [digital_outputs](config/reference/digital_outputs/)
    - [sensor_inputs](config/reference/sensor_inputs/)
    - [logging](config/reference/logging/)

- Deployment

  - [Supervisor](deployment/supervisor.md)
  - [Docker](deployment/docker.md)

- Development

  - [Config Schema](dev/config_schema.md)

  - Modules

    - [Overview](dev/modules/overview.md)
    - [GPIO](dev/modules/gpio.md)
    - [Sensors](dev/modules/sensors.md)
    - [Streams](dev/modules/streams.md)