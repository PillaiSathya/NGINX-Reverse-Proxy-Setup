📘 NGINX Reverse Proxy Setup with Docker
A practical Docker-based setup demonstrating how to configure NGINX as a reverse proxy for multiple services. This simulates real-world routing in a microservices environment.

🚀 Project Structure
pgsql
Copy
Edit
reverse_proxy_project/
├── frontend/
│   └── index.html
├── backend/
│   └── index.html
├── nginx/
│   └── default.conf
└── docker-compose.yml
🔧 Technologies Used
🐳 Docker & Docker Compose

🌐 NGINX

🧱 HTML (static pages)

🔄 Reverse Proxy concepts

🛠️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/PillaiSathya/NGINX-Reverse-Proxy-Setup.git
cd NGINX-Reverse-Proxy-Setup
Start the Docker services:

bash
Copy
Edit
docker-compose up -d
Open your browser:

http://localhost:8081/frontend/

http://localhost:8081/backend/

🧠 What I Learned
How NGINX works as a reverse proxy

How to route paths like /frontend and /backend to different containers

How to configure NGINX using default.conf

Docker Compose service linking & volume mounting

📸 Screenshots
![front](https://github.com/user-attachments/assets/a11a3aaa-8a72-4080-9477-a855cfc41bdd)
![back](https://github.com/user-attachments/assets/3b80d499-e063-4f5b-a6e2-2f72dda787c5)



