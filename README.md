# learningpostgrescrud

Spring Boot project (Java 17) with PostgreSQL.

Run:
1. Ensure PostgreSQL is running and a database `learningdb` exists (or create it).
2. Update `src/main/resources/application.properties` if needed.
3. In IntelliJ: Import project as Maven project.
4. Run `LearningPostgresCrudApplication`.

API endpoints:
- /api/students
- /api/instructors
- /api/admins

Each supports GET, POST, PUT, DELETE.
