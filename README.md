# DevOps Internship - Task 7
## System Monitoring with Netdata

### 📊 Task Description
Installed and configured Netdata monitoring tool using Docker to visualize system performance metrics.

### 🚀 What I Did
1. **Installed Netdata** using Docker container
2. **Accessed the dashboard** at http://localhost:19999
3. **Monitored system resources**: CPU, Memory, Disk, Docker containers
4. **Explored real-time metrics** and alerting system
5. **Generated system load** to test monitoring capabilities

### 🛠️ Commands Used
```powershell
docker run -d --name=netdata -p 19999:19999 netdata/netdata
