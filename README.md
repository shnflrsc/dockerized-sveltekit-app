# dockerized-sveltekit-app

### This is the first docker image I created myself 🥳🎉
This project is a simple static site made with Bun and SvelteKit. I wrote a simple Dockerfile that sets up dependencies, builds the project and runs it with nginx.

First build the image:
```bash
docker build -t username/dockerized-sveltekit-app .
```
Then run the container:
```bash
docker run -d -p 8000:80 username/dockerized-sveltekit-app
```

Finally, access the site through `http://localhost:8000`.
