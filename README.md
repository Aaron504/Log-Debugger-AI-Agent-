# Log-Debugger-AI-Agent-

<img width="477" height="325" alt="Screenshot 2025-08-08 173917" src="https://github.com/user-attachments/assets/531a5c62-e4c2-435e-b31d-0f8fa677e721" />


<h1>Log Debugger AI Agent for Cloud Monitoring & Root Cause Analysis</h1>

Developed an AI-powered log analysis agent using CrewAI and the OpenAI API to simulate a cloud monitoring and logging workflow. The agent ingests AWS CloudWatch-style and Datadog-style logs, detects anomalies, and provides detailed root cause analysis with actionable remediation steps. Built and tested in a Python virtual environment using PowerShell and VS Code, with secure API key management via .env and automated log parsing using pandas.

Key Highlights:

- Designed a reusable AI agent architecture for monitoring environments.

- Simulated real-world logging scenarios without needing live AWS or Datadog accounts.

- Implemented secure environment variable handling with python-dotenv.

- Automated log ingestion from multiple simulated sources.

- Delivered detailed, human-readable incident reports for operational troubleshooting.


  
<h2>Environments and Technologies Used</h2>

- Visual Studio Code (with Python extension)
- Python Environment
- CrewAI
- OpenAI API
- VS Code
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 11 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 – Project Setup
- Step 2 – Create .env file for API Key
- Step 3 – Create Sample Logs
- Step 4 – Python Script to Load Logs
- Step 5 – Create the Log Debugger AI Agent
- Step 6 – Run the Agent







<h2>Deployment and Configuration Steps</h2>

 Step 1 – Project Setup

 <img width="975" height="511" alt="Screenshot 2025-08-08 111057" src="https://github.com/user-attachments/assets/c4e968bd-de84-4ab8-8e3c-2adfcfa4067e" />
 <img width="976" height="478" alt="Screenshot 2025-08-08 111144" src="https://github.com/user-attachments/assets/a3533d9c-8dda-4105-97c1-bad29a7dd3ed" />

 Step 2 – Create .env file for API Key

For security reasons, I didn't put the real OpenAI API key in there.

<img width="1011" height="696" alt="Screenshot 2025-08-08 112002" src="https://github.com/user-attachments/assets/ecb7917f-f451-474e-81ca-28897529e82b" />

Step 3 – Create Sample Logs

We’ll make 2 fake log files in a logs folder:

<img width="1066" height="308" alt="Screenshot 2025-08-08 120634" src="https://github.com/user-attachments/assets/efd3d9c1-c7e7-4c86-864c-cdfd070e5f60" />
<img width="1045" height="267" alt="Screenshot 2025-08-08 120643" src="https://github.com/user-attachments/assets/7c5722c5-a29d-4f2e-86c0-63fe273a32b3" />

Step 4 – Python Script to Load Logs

<img width="1030" height="390" alt="Screenshot 2025-08-08 121251" src="https://github.com/user-attachments/assets/532ce977-a9d4-40ff-91a6-1b3129f2542c" />

Step 5 – Create the Log Debugger AI Agent

<img width="964" height="748" alt="Screenshot 2025-08-08 121907" src="https://github.com/user-attachments/assets/a024da2d-4420-4626-a1a7-31a6be7638b0" />

Step 6 – Run the Agent

<img width="1501" height="952" alt="Screenshot 2025-08-08 171024" src="https://github.com/user-attachments/assets/1faaebe5-bdae-467c-bb3c-09c4803b5df1" />
<img width="1504" height="790" alt="Screenshot 2025-08-08 171051" src="https://github.com/user-attachments/assets/3cc30fcc-d99e-48b2-a195-6cbff594ec47" />
<img width="1520" height="218" alt="Screenshot 2025-08-08 171119" src="https://github.com/user-attachments/assets/60817035-7722-48c5-9167-047d88a5155d" />
<img width="1503" height="899" alt="Screenshot 2025-08-08 171141" src="https://github.com/user-attachments/assets/8e9662d5-f8df-484c-8987-3a48cc2b9ad9" />
<img width="1518" height="828" alt="Screenshot 2025-08-08 171211" src="https://github.com/user-attachments/assets/3d76c894-7715-4884-a801-8fa9be4bc86f" />





































