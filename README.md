Prometheus-Grafana Demo
A simple project demonstrating how to set up Prometheus and Grafana for monitoring applications and system metrics.

📚 Overview
This project sets up a basic monitoring stack using:

Prometheus — to collect and store metrics.

Grafana — to visualize metrics.

Node Exporter — to expose system metrics (CPU, memory, disk usage, etc).

It can be easily extended to monitor services like Spring Boot applications or Docker containers.

🛠 Tech Stack
Prometheus

Grafana

Node Exporter

Docker & Docker Compose (optional for easy setup)

Linux / Windows (system monitoring)

🚀 Project Structure
prometheus-grafana-demo-updated/
├── prometheus.yml   # Prometheus configuration file
├── docker-compose.yml  # (optional) for containerized setup
├── grafana/         # Grafana configurations (dashboards, datasources)
├── exporters/       # Node Exporter setup
└── README.md
⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/rtpuja/prometheus-grafana-demo-updated.git
cd prometheus-grafana-demo-updated
2. Start Services (using Docker Compose)
docker-compose up -d
This will start:

Prometheus at http://localhost:9090

Grafana at http://localhost:3000

Node Exporter at http://localhost:9100

Default Grafana Login: admin/admin

📈 How to Use
Access Prometheus at http://localhost:9090

Verify targets under Status → Targets.

Access Grafana at http://localhost:3000

Add Prometheus as a data source (if not already configured).

Import sample dashboards (Node Exporter Dashboard, etc.).

View Metrics

Monitor CPU, Memory, Disk, Network stats.

Build custom dashboards as needed.

📋 Example Dashboards
Node Exporter Full

Prometheus 2.0 Stats

Docker Container Monitoring (optional)

🔥 Future Enhancements
Add monitoring for Spring Boot application metrics using Micrometer.

Setup alerting rules in Prometheus.

Integrate Slack/Email alerts.

Add Grafana provisioning.

🤝 Contributing
Contributions are welcome!
Feel free to fork this repository, create a branch, make changes, and submit a pull request.

📄 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Pooja Kumawat
GitHub | LinkedIn

🚀 Happy Monitoring!
Bonus:
If you also want a badge at the top for a stylish look, you can add this line right after the title:


