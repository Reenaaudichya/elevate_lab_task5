# elevate_lab_task5
# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
The objective of this task was to capture live network traffic, identify protocols, and analyze network endpoints using Wireshark[cite: 1].

## Steps Taken
1.  **Capture**: Installed Wireshark and initiated a live packet capture on the active Wi-Fi interface[cite: 1].
2.  **Traffic Generation**: Browsed websites to generate active HTTP/HTTPS and DNS traffic[cite: 1].
3.  **Analysis**: Used the "Endpoints" statistics feature to analyze communication partners and filtered by protocols (TCP, UDP, IPv4, IPv6).
4.  **Export**: Saved the capture as `wirshark_task5.pcapng`[cite: 1].

## Findings
*   **Protocols Identified**:
    *   **TCP**: Observed high traffic volume on port 443 (HTTPS), indicating secure web communication[cite: 2].
    *   **UDP**: Identified DNS traffic (Port 53) used for domain name resolution[cite: 2].
    *   **IPv4/IPv6**: Confirmed both protocol versions were present in the network communication[cite: 2].
*   **Endpoints**: Analyzed multiple remote IP addresses connected to the local machine, identifying various external servers involved in the browsing session[cite: 2].

## Deliverables
*   `wirshark_task5.pcapng` (Packet capture file)
*   Screenshots of endpoint statistics and protocol filters.
