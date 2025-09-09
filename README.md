# SmartLearningHub
A collaborative, open-source platform for team coding and learning
# SmartLearningHub

SmartLearningHub is a collaborative, open-source platform for teams to code, share, and learn together—accessible from anywhere.

## Features

- User, Team, and Project management (REST API)
- Internet-ready (CORS enabled)
- Easily extend for real-time collab, DB, and authentication

## Running Locally

1. Install Java 17+ and Maven.
2. Clone this repository.
3. Run: `mvn spring-boot:run`
4. Visit: http://localhost:8080/api/users etc.

## Deploying Online

- Heroku: [Spring Boot on Heroku Guide](https://devcenter.heroku.com/articles/deploying-spring-boot-apps-to-heroku)
- Railway, Render: Just connect your repo and deploy.
- For DB: Add your cloud DB config in `application.properties`.

## Next Steps

- Add authentication (JWT/OAuth2)
- Integrate PostgreSQL or MongoDB for persistence
- Add WebSocket for real-time code editing

---

**Contributions welcome!**
