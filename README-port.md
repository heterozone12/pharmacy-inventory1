Port: Docker Compose for running the PHP app

Quick start

1. Ensure Docker and Docker Compose are installed.
2. From the repo root run:

```bash
docker-compose up -d
```

3. Open the app in your browser: http://localhost:8080/
4. phpMyAdmin is available at: http://localhost:8081/ (user: `user`, pass: `password`)

MySQL credentials (for local/dev only)
- root: `rootpass`
- database: `pharmacy`
- user: `user` / `password`

Notes
- The `./www` folder is mounted into the container at `/var/www/html` so code edits are immediate.
- This setup is intended for local development only. Change secrets before production.
