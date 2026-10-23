# Network Packet Analyzer

A web-based **Network Packet Analyzer** designed to monitor, analyze, and visualize network packet information through an interactive dashboard. The project helps users inspect packet details, identify communication between source and destination IP addresses, analyze protocols, and troubleshoot network-related issues.

## 🚀 Features

- **Packet Monitoring:** View captured or imported network packet records.
- **Source IP Address:** Identify the IP address from which a packet originates.
- **Destination IP Address:** Identify the packet's destination IP address.
- **Protocol Detection:** View protocols such as TCP, UDP, ICMP, and others when supported by the packet data.
- **Interactive Dashboard:** Display packet information in an organized interface.
- **Packet Filtering:** Filter packet records based on available criteria.
- **Troubleshooting:** Inspect packet information to help investigate network communication issues.
- **Logout:** Exit the dashboard securely.

## 🛠️ Tech Stack

- **Frontend:** React.js, Vite
- **Styling:** Tailwind CSS
- **Backend:** Node.js, Express.js
- **Icons:** Lucide React
- **Data Source:** Packet dataset / CSV data (depending on the configured version)

## 📂 Project Structure

```text
network-packet-analyzer/
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
├── backend/
│   ├── server.js
│   └── package.json
├── README.md
└── .gitignore
```

*Note: Update this structure to match your actual repository folders and files.*

## ⚙️ Installation and Setup

### Prerequisites

Install the following before running the project:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)
- Git (optional, for cloning the repository)

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd network-packet-analyzer
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Install Dependencies

Open a terminal in the frontend directory:

```bash
cd frontend
npm install
```

Open another terminal in the backend directory:

```bash
cd backend
npm install
```

### 3. Start the Backend

From the backend directory, run:

```bash
npm start
```

If your `package.json` does not define a start script, use the command configured for your backend, such as `node server.js`.

### 4. Start the Frontend

From the frontend directory, run:

```bash
npm run dev
```

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173
```

Make sure the frontend API configuration matches the backend server address and port.

## 📊 How It Works

1. The user logs in to the application.
2. The dashboard displays available packet information.
3. The user examines source IPs, destination IPs, protocols, and other available packet fields.
4. The user filters packet records to investigate particular network communications.
5. The user uses the displayed information to support basic network troubleshooting.

**Important:** If the current version uses CSV or sample data, the dashboard analyzes that data rather than capturing live network traffic. Live packet capture requires an appropriate capture mechanism, permissions, and backend integration.

## 🔐 Security and Privacy

- Use authentication and authorization controls appropriate for the application.
- Do not commit passwords, API keys, or other secrets to GitHub.
- Restrict access to captured traffic because packet data may contain sensitive information.
- Perform network monitoring only on systems and networks you own or have permission to analyze.

## 🔮 Future Enhancements

- Real-time packet capture and analysis.
- Advanced filtering by IP address, protocol, and port.
- Packet statistics and graphical visualizations.
- Suspicious traffic alerts and anomaly detection.
- Packet export and downloadable analysis reports.
- Improved authentication and role-based access control.

## 🎯 Project Objective

The objective of this project is to develop an interactive network monitoring tool that helps users understand packet communication, examine network traffic information, and practice fundamental network analysis and troubleshooting concepts.

## 👨‍💻 Author

**Prakhar Bhagbole**



## 📄 License

This project is intended for educational and learning purposes. Add a license file if you want to specify the terms under which others may use or modify the project.
