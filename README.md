# api-users-auth

just for learning, docker, nginx and redis, implementing sha256 for encrypt session tokens with password, password that the server generate the half of it and the client the other part, so none one alone can decrypt.
the api was fragmented into 2 different projects, auth and users, for learn about scalibity and load balacing, each one run into a docker container that is runners by docker compose.

auth is not login/signup, is unique login with account that will exist only by certain time, time decided by client (max 7 days).
