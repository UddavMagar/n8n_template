# 🧩 n8n Docker Project Template

This template helps you quickly set up a self-hosted [n8n](https://n8n.io) workflow automation instance using Docker and Docker Compose.

---

## 🚀 Quick Start

### Prerequisites

- Docker and Docker Compose installed  
- Git installed

### Setup & Run


# Clone this template into your new project folder
```sh
git clone https://github.com/UddavMagar/n8n_template.git my-new-project
```


# Enter the project folder
```sh
cd my-new-project
```


# (Optional) Remove Git history if you want to make your own repo
```sh
rm -rf .git
```


# Run the n8n container
```sh
docker compose up -d
```



# To stop the running container, run:
```sh
docker compose down
```




Access n8n Editor
Open your browser and go to:

http://localhost:5678


You will be prompted to log in with basic authentication.

Default credentials are:

Username: admin

Password: admin123

⚠️ Important: These are default development credentials.
Please change the username and password in the docker-compose.yml file before deploying to production, or adjust them to your preference for security.