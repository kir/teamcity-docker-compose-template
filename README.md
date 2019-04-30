Starts TeamCity 2018.2.4 in docker-compose with 2 nodes and one build agent, on Postgres database.

To start:

    docker-compose up

Next, open http://localhost:8111 for initial setup.

After creating a user, visit http://localhost:8111/agents.html?tab=unauthorizedAgents to authorize build agent.

To shutdown

    docker-compose down

For volumes and details see `docker-compose.yml`

