# Rhombix Technologies - Cloud Computing Internship Task

## 📌 Task Overview
This project demonstrates deployment and management of a blockchain node using containerized infrastructure on Ubuntu, reflecting cloud computing concepts and virtualization.

---

## 🛠️ Tools Used
- Ubuntu Linux
- Docker
- Ethereum (Geth client)

---

## 🚀 Implementation Steps

### 1. Install Docker

```bash
sudo apt update
sudo apt install docker.io -y
```

### 2. Start Docker

```bash
sudo systemctl start docker
sudo systemctl enable docker
```

### 3. Deploy Blockchain Node

```bash
sudo docker run -d --name ethereum-node ethereum/client-go:stable --dev
```

### 4. Monitor Node Logs

```bash
sudo docker logs ethereum-node
```

### 5. Manage Node Lifecycle

```bash
sudo docker stop ethereum-node
sudo docker start ethereum-node
```

---

## 🎯 Outcome

Successfully deployed and managed a blockchain node using containerized infrastructure while demonstrating cloud computing concepts such as virtualization and isolated environments.

---

## 📚 Learning Outcomes

- Cloud computing fundamentals
- Blockchain node architecture
- Docker containerization
- Node monitoring and management
