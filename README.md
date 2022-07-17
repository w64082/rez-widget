# Rez API Widget

<b>This is school project for testing and education purposes - not ready to commercial use.</b>

This software allows you to test connection to REST API and use:

- available visits listing,
- make reservation,

# Setup Docker

- docker-compose build
- docker-compose up -d

# Run API on host by Docker

- visit: http://localhost:9090

# TODO - improvements:

- structures for config based on .env file,
- some cache of requests data,
- better validators and error handling,
- logs aggregation Open Telemetry,
- unit tests for requests (on mocks),
- use DRY instead of copy/paste in methods,