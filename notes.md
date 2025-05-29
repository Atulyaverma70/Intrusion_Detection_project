# Type of attacks
1. DoS attack(Denial of service)
    * A DoS attack is an attempt to make a machine, network, or service unavailable to its intended users by flooding it with excessive requests.
        * Types
            * DoS (Single Source): One machine sends massive traffic.
            * DDoS (Distributed DoS): Multiple machines (botnet) launch the attack simultaneously.
                * Common Techniques
                    * Ping Flood (ICMP Flood)
                    * SYN Flood
                    * UDP Flood
                    * HTTP Flood
2. Port Scanning
    * Port scanning is a reconnaissance technique used by attackers to discover open ports and services running on a networked device.
    * goal: To identify potential entry points for further attacks.
3. Brute force attack
    * A brute force attack is an attempt to gain unauthorized access by systematically trying every possible combination of passwords or encryption keys.
    * goal: To crack passwords, encryption, or PINs by trying all possibilities.
4.  MITM (Man-in-the-Middle) Attack
    * A MITM attack occurs when a malicious actor secretly intercepts and possibly alters communication between two parties who think they are directly communicating.
    * To eavesdrop, alter messages, or steal credentials.

# Signature- Based IDS vs Anomaly based IDS
* Signature- Based IDS
    * Detects intrusions by comparing network traffic or system behavior to a database of known attack signatures (patterns).
    * Works like antivirus software — if a pattern matches, it's flagged as an attack.
* Anomaly Based Attack
    * Uses machine learning/statistical models to learn "normal" behavior of a system or network.
    * Flags deviations from this baseline as potential threats.
