# Frontend Skills Interview

## Project Details

Please consider this document as a set of requirements, and deliver the code necessary to fulfill these requirements. If a requirement seems ambiguous, state your understanding of the requirements in a readme or inline comments along with your solution.

## Mission

Your mission is to write an application able to list, add, delete and update all the elements provided by the API.

Your application should be writen with Javascript and React.

## Delivery

You should deliver your code and the Dockerfile necesary to run it locally.

## API

To launch the API run:
```sh
docker run --name hiring -d -p 80:80 languagesensation/hiring-frontend:latest
```

### Endpoints

- GET http://localhost/posts (to list all posts)
- GET http://localhost/posts/1 (get one specific post)
- POST http://localhost/posts (create a new post)
- PUT http://localhost/posts/4 (update an existent post)
- DELETE http://localhost/posts/4 (delete a post)
