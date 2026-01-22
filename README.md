📘 Prometheus + Alertmanager + Grafana + Nginx Monitoring Setup

This project provides a complete monitoring stack using:
    Prometheus – metrics collection
    Alertmanager – alert dispatching
    Grafana – dashboards
    Node Exporter – system metrics
    Nginx Exporter – Nginx metrics
    Nginx – sample service to monitor
    Everything runs through Docker Compose.

🚀 Features
    ✔ Nginx monitored with nginx-prometheus-exporter
    ✔ Host-level metrics with node-exporter
    ✔ Custom Prometheus alert rules
    ✔ Email alerts via Alertmanager
    ✔ Grafana dashboards (port 3000)
    ✔ Prometheus web UI (port 9090)
    ✔ Alertmanager web UI (port 9093)
    ✔ Fully containerized — no manual installs

🔧 How to Run the Monitoring Stack
Make sure you have:
        Docker
        Docker Compose
Then start the stack:
        docker compose up -d
Stop everything:
        docker compose down

🔥 Access the Services
        Service	URL
            Prometheus	http://localhost:9090
            Alertmanager	http://localhost:9093
            Grafana	http://localhost:3000
            Nginx	http://localhost:8090

        📈 Prometheus Alert Rules
            Alert rules are stored in:
            /alert/alert.yml

🛠 Common Commands
Check Docker logs:
        
        docker logs alertmanager
        docker logs prometheus
        docker logs grafana

❤️ Author

Built by Srishti Singh
Monitoring setup with Prometheus, Grafana & Alertmanager.
