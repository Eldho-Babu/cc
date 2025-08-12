curl -L -O https://artifacts.elastic.co/downloads/beats/elastic-agent/elastic-agent-9.1.1-amd64.deb 
sudo dpkg -i elastic-agent-9.1.1-amd64.deb
sudo systemctl enable elastic-agent 
sudo systemctl start elastic-agent 
sudo elastic-agent enroll --url=https://ca3811bf87a5483fb0ddf15007ae82ea.fleet.us-central1.gcp.elastic.cloud:443 --enrollment-token=NzJqTm5KZ0I3UnZtNkxlRkFQcm46T3FHVGFRUW41ZkNJQ1oxdE10RU1jZw== 
curl http://testmyids.com

