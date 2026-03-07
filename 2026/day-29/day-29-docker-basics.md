### Task 1: What is Docker?
Research and write short notes on:
- What is a container and why do we need them?
- Containers vs Virtual Machines — what's the real difference?
- What is the Docker architecture? (daemon, client, images, containers, registry)

Draw or describe the Docker architecture in your own words.

### Task 2: Install Docker
1. Install Docker on your machine (or use a cloud instance)
2. Verify the installation
3. Run the `hello-world` container
4. Read the output carefully — it explains what just happened

![Images](image/task2.png)
 
 ### Task 3: Run Real Containers
1. Run an **Nginx** container and access it in your browser
2. Run an **Ubuntu** container in interactive mode — explore it like a mini Linux machine
3. List all running containers
4. List all containers (including stopped ones)
5. Stop and remove a container

![Images](image/task3.png) 

### Task 4: Explore
1. Run a container in **detached mode** — what's different?
2. Give a container a custom **name**
3. Map a **port** from the container to your host
4. Check **logs** of a running container
5. Run a command **inside** a running container

![Images](image/task4.png)


## Hints
- `docker run`, `docker ps`, `docker stop`, `docker rm`
- Interactive mode: `-it` flag
- Detached mode: `-d` flag
- Port mapping: `-p host:container`
- Naming: `--name`
- Logs: `docker logs`
- Exec into container: `docker exec`

![Images](image/task5a.png)


![Images](image/task5b.png)
