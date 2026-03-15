# 📡 Project: Ping-Kubernetes

Project Ping-Kubernetes builds and deploys Ping-Server and Ping-Client within a Kubernetes cluster.

## 📖 Usage

### 1️⃣ Pre-requisites:

#### Software:
      
```text
Open JDK version 21
Full docker e.g. curl -fsSL https://get.docker.com | sudo sh
Kubernetes (available within Docker Desktop on some platforms)
Kubectl command-line kubernetes tool.
```

Both client and server open port 8081.

```text
EXPOSE 8081
```
        
### 2️⃣ Build:

Navigate to $projectDir/bin directory and execute the following commands

```bash
./c
```

