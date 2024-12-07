# SIEM Project

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Elastic Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.
- Kali Linux virtualmachine to generate traffic 

## Steps

1. **Set Up the Environment:**
   - Installed **Kali Linux** as the primary security platform.
   - Installed **Elastic Stack** (Elasticsearch, Logstash, and Kibana) on a server or VM.

2. **Install Elasticsearch:**
   - Downloaded and install Elasticsearch on your server.
   - Configured the `elasticsearch.yml` file to set cluster settings and enable network access.
   - Started the Elasticsearch service.

3. **Install Kibana:**
   - Installed Kibana and connect it to the Elasticsearch instance by configuring the `kibana.yml` file.
   - Start Kibana and access the web interface via `http://<server-ip>:5601`.

4. **Install and Configure Logstash:**
   - Installed Logstash and configure it to parse logs from various sources.
   - Created input, filter, and output pipelines in the `logstash.conf` file to forward logs to Elasticsearch.

5. **Enable Beats for Data Collection:**
   - Installed **Filebeat**, **Metricbeat**, or other Elastic Beats on endpoints to collect logs, metrics, and other data.
   - Configured the Beats to ship data to Logstash or Elasticsearch.

6. **Simulate Log Generation:**
   - Used **Kali Linux tools** (e.g., Metasploit,### Steps to Create a SIEM Project Using Elastic and Kali Linux

1. **Set Up the Environment:**
   - Install **Kali Linux** as the primary security platform.
   - Install **Elastic Stack** (Elasticsearch, Logstash, and Kibana) on a server or VM.

2. **Install Elasticsearch:**
   - Download and install Elasticsearch on your server.
   - Configure the `elasticsearch.yml` file to set cluster settings and enable network access.
   - Start the Elasticsearch service.

3. **Install Kibana:**
   - Install Kibana and connect it to the Elasticsearch instance by configuring the `kibana.yml` file.
   - Start Kibana and access the web interface via `http://<server-ip>:5601`.

4. **Install and Configure Logstash:**
   - Install Logstash and configure it to parse logs from various sources.
   - Create input, filter, and output pipelines in the `logstash.conf` file to forward logs to Elasticsearch.

5. **Enable Beats for Data Collection:**
   - Install **Filebeat**, **Metricbeat**, or other Elastic Beats on endpoints to collect logs, metrics, and other data.
   - Configure the Beats to ship data to Logstash or Elasticsearch.

6. **Simulate Log Generation:**
   - Use **### Steps to Create a SIEM Project Using Elastic and Kali Linux

1. **Set Up the Environment:**
   - Install **Kali Linux** as the primary security platform.
   - Install **Elastic Stack** (Elasticsearch, Logstash, and Kibana) on a server or VM.

2. **Install Elasticsearch:**
   - Download and install Elasticsearch on your server.
   - Configure the `elasticsearch.yml` file to set cluster settings and enable network access.
   - Start the Elasticsearch service.

3. **Install Kibana:**
   - Install Kibana and connect it to the Elasticsearch instance by configuring the `kibana.yml` file.
   - Start Kibana and access the web interface via `http://<server-ip>:5601`.

4. **Install and Configure Logstash:**
   - Install Logstash and configure it to parse logs from various sources.
   - Create input, filter, and output pipelines in the `logstash.conf` file to forward logs to Elasticsearch.

5. **Enable Beats for Data Collection:**
   - Install **Filebeat**, **Metricbeat**, or other Elastic Beats on endpoints to collect logs, metrics, and other data.
   - Configure the Beats to ship data to Logstash or Elasticsearch.

6. **Simulate Log Generation:**
   - Use **Kali Linux tools** (e.g., Metasploit, Nmap, or Hydra) to generate simulated security events.
   - Capture logs from firewalls, servers, or applications for analysis.

7. **Visualize and Analyze in Kibana:**
   - Create visualizations and dashboards in Kibana to monitor events, detect anomalies, and investigate alerts.
   - Set up alerts for suspicious activities using Kibana’s alerting features.

8. **Integrate with Threat Intelligence:**
   - Enhance the SIEM by integrating open-source threat intelligence feeds or custom rules for detecting specific threats.

9. **Test the System:**
   - Validate the system by running penetration tests or generating logs from known threats to ensure proper detection and correlation.

10. **Maintain and Update:**
    - Regularly update Elastic Stack components and refine configurations based on
 organizational needs and threat landscape changes.

![Screenshot 2024-12-01 133545](https://github.com/user-attachments/assets/a157b69d-adeb-4515-b6eb-a6c0b59fb3dc)
![Screenshot 2024-12-01 133643](https://github.com/user-attachments/assets/71af4f75-00a5-4f15-84b5-86745a7afcc1)
![Screenshot 2024-12-01 133620](https://github.com/user-attachments/assets/1ccca180-94d4-433e-8522-77c9a15306ee)
