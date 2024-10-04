# ACM FUN - React.js Project

ACM FUN is an exciting initiative by PECACM, aimed at engaging beginners in the world of development and open source contributions. 😄

Live URL:- https://acm-fun.vercel.app/

## Table of Contents

- [Description](#acm-fun---reactjs-project)
- [Features](#features)
- [Tech Used](#tech-used)
- [How to start](#how-to-start)
- [Contributing](#contributing)

## Features

- A fun and interactive web application built using React.js.
- Engage with open source contributions in a beginner-friendly environment.
- Collaborate with a community of like-minded individuals.

## Tech Used

React is a JavaScript library for building fast and interactive UIs.

Vercel is a cloud platform for deploying and scaling React applications.

## How to start

1. Clone the repository

```
  git clone https://github.com/PEC-CSS/acm-fun.git
```

2. Change the working directory

```
  cd acm-fun
```

3. Install dependencies

```
  npm install
```

4. Run the app

```
  npm start
```

5. Open your web browser and navigate to http://localhost:3000 to view the app.

The page will automatically reload when you make changes, and any lint errors will be displayed in the console.

6. To build for production use the command:

```
npm run build
```

This command bundles React in production mode and optimizes the build for the best performance. The build is minified, and the filenames include hashes. Once the build process is complete, your app is ready to be deployed.

## Docker Setup

This project is Dockerized to ensure seamless development and deployment. Follow the instructions below to build, run, and stop the Docker container.

### Prerequisites

- [Docker](https://www.docker.com/get-started) should be installed on your system.

### Building the Docker Image

To build the Docker image for this application, navigate to the root of the project (where the Dockerfile is located) and run the following command:

```bash
docker buildx build -t your-app .
```

- **`-t your-app`**: This tags the image with the name `your-app`.
- **`.`**: Refers to the current directory where the Dockerfile and project files are located.

### Running the Docker Container

Once the image is built, you can run the Docker container with the following command:

```bash
docker run -p 3000:3000 your-app
```

- **`-p 3000:3000`**: Maps port 3000 inside the container to port 3000 on your local machine, allowing you to access the app via `http://localhost:3000`.
- **`your-app`**: The name of the Docker image you built.

### Stopping the Docker Container

To stop the running Docker container, first find the container ID or name by running:

```bash
docker ps
```

This will list all running containers. Use the container ID or name in the following command to stop the container:

```bash
docker stop <container_id_or_name>
```

For example:

```bash
docker stop abc123
```


## Notes

- Ensure that you have Docker running before executing these commands.
- If you change the source code, you may need to rebuild the Docker image using the `docker buildx build` command.


### Customization Notes:
- Replace `your-app` with your desired image name.
- Make sure to provide instructions to install Docker if your users might not have it installed.

# Contributing

- To contribute to ACM FUN, refer to [Contributing Guidlines](./Contributing.md)

# Contributors

<a href="https://github.com/PEC-CSS/acm-fun/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=PEC-CSS/acm-fun" />
</a>

<br>

We welcome your contributions and hope you enjoy your journey with ACM FUN!
