# CODTECH-TASK-2

Project name :- vulnerability scanning tool
Name :- Mekala Hemanth
Company :- CODTECH IT SOLUTIONS 
ID :- CT08PD775 Domain :- Cyber Security & Ethical Hacking
Duration :- May to june 2024 
Mentor :- SRAVANI GOUNI

Creating a simple vulnerability scanning tool involves checking for common security issues like open ports, outdated software versions, and misconfigurations. For this implementation, we'll use Python with libraries such as socket, nmap, and requests.

Requirements
Python Libraries:
nmap: To scan for open ports and services.
requests: To check HTTP headers and detect outdated software versions.

Explanation of the Code
Open Ports Scanning:

nmap.PortScanner() is used to scan ports 1-1024 on the target.
Open ports are listed for further analysis.
HTTP Headers Check:

We send a GET request to the target and inspect the HTTP headers.
Feedback includes server software information and potential version disclosure.
Placeholder logic is used to flag outdated software, which can be replaced with actual version comparison.
SSL/TLS Check:

We verify if the target URL uses HTTPS, indicating SSL/TLS is enabled.
Feedback is provided based on whether SSL/TLS is detected.
Overall Vulnerability Scan:

The scan_vulnerabilities function integrates all checks and returns a comprehensive report.
Usage
To use the tool, specify the target domain or IP address in the target variable and call the scan_vulnerabilities function. The results include open ports, HTTP headers feedback, and SSL/TLS feedback.

This is a basic implementation and can be extended with more detailed checks for various vulnerabilities, more sophisticated version comparisons, and integration with external vulnerability databases.

