# Reference
- Main Source: https://www.digitalocean.com/community/tutorials/how-to-build-a-rest-api-with-prisma-and-postgresql

Run Prisma Studio : `npx prisma studio`

# Command
## CURL list

```
curl http://localhost:3000/users // get ALL users

curl http://localhost:3000/post/1 //get detail post

curl -X POST -H "Content-Type: application/json" -d '{"name":"Bob", "email":"bob@prisma.io"}' http://localhost:3000/user //add new user


curl -X POST -H "Content-Type: application/json" -d '{"title":"I am Bob", "authorEmail":"bob@prisma.io"}' http://localhost:3000/post //add new post

```

## Docker
Run Postgres on container `docker compose up -d`


