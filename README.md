# Basic ELK Stack Setup with Docker Compose

This repository provides a basic ELK Stack setup using Docker Compose. It includes the following components:

- **Elasticsearch**: A distributed, RESTful search and analytics engine.
- **Kibana**: A powerful visualization tool for Elasticsearch data.
- **Filebeat**: An agent that ships logs from local files or standard input to Elasticsearch.
- **Metricbeat**: An agent that collects system and service metrics and ships them to Elasticsearch.
- **Logstash**: A data processing pipeline that can be used to transform and enrich data before sending it to Elasticsearch.

Prerequisites:

    Docker
    Docker Compose

    If you don't have it installed follow the following guide at: https://docs.docker.com/get-started/get-docker/

## Getting Started

Clone the Repository:
```bash
git clone https://github.com/grcheulishvili/ELK-stack-docker.git
```
Start the Stack:
```bash
    cd elk-stack-docker
    docker compose up -d

    Access Kibana:
    Open your web browser and navigate to http://localhost:5601.
```
Configuration:

    The docker-compose.yml file contains the configuration for all the services. You can customize the configuration as needed.

## Additional Notes

    For production environments, consider using a more robust setup with multiple nodes for each component.
    Tinker the advanced features of Elasticsearch, Kibana, Filebeat, Metricbeat, and Logstash to customize your ELK Stack setup.
    Refer to the official documentation for each component for more detailed information and troubleshooting tips.

## License

This project is licensed under the GPL3 License.
