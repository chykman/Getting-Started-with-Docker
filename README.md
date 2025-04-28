
---

# Getting Started with Docker

## 1. Launching an EC2 Instance and Login

- Spin up a new **EC2 instance** and login via SSH.
  ![image](https://github.com/user-attachments/assets/5b13f061-94b9-4730-82d4-da6ed3045892)
  ![image](https://github.com/user-attachments/assets/c940aedc-fd57-433c-8425-77e14609dfa6)
  ![image](https://github.com/user-attachments/assets/50ca841b-c51a-4094-bdb8-3ce9e8cb231e)

## 2. Preparing the Server

- Update all installed packages.
  ![image](https://github.com/user-attachments/assets/bc5765c7-e633-4260-aea5-4cfa91b85699)

- Install essential packages and certificate authorities.
  ![image](https://github.com/user-attachments/assets/6e24796c-02f6-4f56-bf68-25115af07c8b)

- Create a directory for Docker-related files with specific permissions.
  ![image](https://github.com/user-attachments/assets/bab87863-b617-45ed-bb7e-4a019ae4c519)

- Download Docker GPG key into the created folder.
  ![image](https://github.com/user-attachments/assets/da4466d7-6100-4581-8a5e-68405ebd5ca4)

- Set read permissions for the GPG key.
  ![image](https://github.com/user-attachments/assets/f77e880b-6e77-43f8-ad3a-9d28ab2dd534)

- Add Docker repository to APT sources.
  ![image](https://github.com/user-attachments/assets/1940a4dc-20db-48bd-b7d8-a48f6f7d578a)

## 3. Installing Docker

- Install Docker packages.
  ![image](https://github.com/user-attachments/assets/ae70ad99-924c-4f2f-b572-1ede31444cfa)
  ![image](https://github.com/user-attachments/assets/bfea9c50-5761-477b-bc64-41759a092e24)

- Verify Docker installation.
  ![image](https://github.com/user-attachments/assets/4e6f889d-e5cc-4f93-9a18-004b4de29ad1)

- Enable running Docker without root .
  ![image](https://github.com/user-attachments/assets/a5d1bf72-3a54-4a79-b7f5-cf41dee5a9fb)

## 4. Running Docker Containers

- Run the **Hello World** Docker container to verify installation.
  ![image](https://github.com/user-attachments/assets/a60e0185-bb59-4e5b-b670-c4d929863386)

- Check available Docker images.
  ![image](https://github.com/user-attachments/assets/72436dd8-ef95-4656-8fd3-d65e116ee175)

## 5. Basic Docker Commands

- **Docker Run**: Run a container based on the nginx image.
  ![image](https://github.com/user-attachments/assets/810529a0-680d-4a65-b0bc-947e9ea1c9b1)

- **Docker ps**: View running Docker containers.
  ![image](https://github.com/user-attachments/assets/c89e6ecc-f8fc-4e65-aa23-8df71fa9467f)

- **Docker ps -a**: List all Docker containers (running and stopped).
  ![image](https://github.com/user-attachments/assets/4edccdc5-59b2-4a9b-83b6-af3c56495d39)

- **Docker stop**: Stop a running container.
  ![image](https://github.com/user-attachments/assets/4ef770e0-2e51-4762-b478-62563549e9eb)

- **Docker pull**: Download Docker images from Docker Hub.
  ![image](https://github.com/user-attachments/assets/774f7adf-fb16-4258-b38f-acdf7b4ca068)

- **Docker push**: Push a local Docker image to Docker Hub.
  ![image](https://github.com/user-attachments/assets/6f199c95-a6f8-48dc-80fb-5a61208a966a)

- **Docker images**: List all locally stored images.
  ![image](https://github.com/user-attachments/assets/daa98603-cad3-4ebc-b59c-5a54295c0d97)

- **Docker rmi**: Remove one or more images from the local machine.
  ![image](https://github.com/user-attachments/assets/2079ecb6-8c10-401d-892c-98d7b546d24e)

---

