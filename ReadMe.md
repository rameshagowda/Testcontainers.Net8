NOTE: Make sure you are running docker locally
1. Testcontainers works on docker container. Each dependencies like database, Redis cache, External APIs etc will have its own container while running the integration tests.
Follow this link: https://testcontainers.com/guides/getting-started-with-testcontainers-for-dotnet
Bonus: Run CI pipeline to test with GH runners.