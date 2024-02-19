Dingolytics
===========

**Dingolytics** is an open source data collection and analytics platform.

- Website: https://dingolytics.com
- GitHub: https://github.com/Dingolytics

This repository contains a basic example for self-hosted configuration
of Dingolytics platform. It is based on Docker and Docker Compose as a
well-known toolset for running applications in containers.

The following services are included in the configuration:

- Dingolytics API and workers
- Dingolytics Web UI
- PostgreSQL
- Redis
- ClickHouse
- Vector


## Quick Start

In short, you need to create a `.env` file and run `docker-compose up --build` command.

More detailed instructions are below.

1. Clone the repository

```bash
git clone https://github.com/Dingolytics/dingolytics-selfhosted.git
```

2. Create a `.env` file with the credentials in the root directory of the repository. You can use the `env.example` as a template.

3. Adjust the `docker-compose.yml` file if necessary. For example, uncomment the `caddy` service if you want to use Caddy as a reverse proxy.

4. Run the following command to start the platform.

```bash
docker-compose up --build -d
```

5. Open the Web UI in your browser. The default URL is `http://localhost:8001`.


## Feedback

If you have any questions or feedback, please feel free to open an issue on GitHub or contact us via Telegram of Slack channels.

- Issues: https://github.com/Dingolytics/dingolytics
- Telegram: ...
- Slack: ...
