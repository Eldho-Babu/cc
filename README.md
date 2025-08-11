curl -L -O https://artifacts.elastic.co/downloads/beats/elastic-agent/elastic-agent-9.1.1-amd64.deb
sudo dpkg -i elastic-agent-9.1.1-amd64.deb
sudo systemctl enable elastic-agent
sudo systemctl start elastic-agent
sudo elastic-agent enroll --url=https://a41d3ad2b71546d1b59042523bed9072.fleet.us-central1.gcp.elastic.cloud:443 --enrollment-token=bUc4dGxKZ0JOM3M4MDE1WHhxWks6QVYwVDhfaDdrOEF6MjlzRzdMLXllUQ==
sudo systemctl restart elastic-agent

