# Cyber Security

## Information
- Supakorn Charoentong (Ctong)
- 6602041610054
- Email :s6602041610054@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Running a services
## Database
```sh
docker compose -f db.yaml up #monitoring
docker compose -f db.yaml up -d #background
```

## Admin
```sh
docker compose -f admin.yaml up #monitoring
docker compose -f admin.yaml up -d #background
```

## app
```sh
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up -d #background
```
