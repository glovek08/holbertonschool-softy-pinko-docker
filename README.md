<p align="right">
  <a href="https://holbertonschool.uy/" target="_blank" style="border:0;">
    <img src="https://github.com/glovek08/glovek08/blob/main/holberton_logo.png?raw=true" height="50" alt="Holberton Logo"/>
  </a>
</p>

# Holbertonschool - Softy Pinko Docker

Containerized app infrastructure with Docker – reverse proxy, load balancer (Round Robin), two API servers, and a front-end server for scalable, portable deployment.

## Resources

* [Docker Tutorial](https://docs.docker.com/get-started/introduction/)
* [Install docker on Linux](https://docs.docker.com/desktop/setup/install/linux/)
* [Install docker on Windows](https://docs.docker.com/desktop/setup/install/windows-install/)

## Context

Docker is a platform that allows you to containerize your applications, meaning that you can package them into portable, self-contained environments which can run anywhere. This means that you can quickly move your application from one environment to another, such as from your local computer to a server, without worrying about dependencies or configuration issues. Docker achieves this by using containers, which are isolated environments that contain everything an application needs to run, such as libraries, dependencies, and configurations. Docker containers are lightweight and can be started and stopped quickly, making them ideal for modern software development and deployment. With Docker, you can also quickly scale your application by running multiple containers of the same application on different hosts (or the same host, as we will do in this project), and manage them using Docker Compose or other orchestration tools.

Ultimately, what you will create in this project is an infrastructure for an application that utilizes a reverse proxy, a load balancer, two application servers, and one front-end server.

<img src="./assets/fat_guy_diagram.png" alt="Network Load Share">
