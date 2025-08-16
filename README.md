curl -L -O https://artifacts.elastic.co/downloads/beats/elastic-agent/elastic-agent-9.1.2-amd64.deb 
sudo dpkg -i elastic-agent-9.1.2-amd64.deb
sudo systemctl enable elastic-agent 
sudo systemctl start elastic-agent 
sudo elastic-agent enroll --url=https://0853148f094240ffb992887990072c8d.fleet.us-central1.gcp.cloud.es.io:443 --enrollment-token=d2RUU29aZ0IyWVhIM1hUa29BM3Q6SlBLeUxmczdJNHZDYjk4SFNROXV5dw== 

