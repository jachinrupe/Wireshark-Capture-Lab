# Wireshark-Capture-Lab
This lab captures Network traffic using Wireshark on Windows and analyzes it. I aim to use different protocols to show Network analysis using different Wireshark filters.

Traffic Types Captured
- ICMP — Captured via ping google.com
- DNS — Captured via nslookup CMD prompt
- TCP 3-Way Handshake — Captured via a fresh web connection
- TCP Port 80 Traffic (HTTP-related) — Captured despite modern HTTPS enforcement

Screenshots
1. ICMP (Ping Traffic)
<img width="1444" height="392" alt="Screenshot 2026-06-18 153516" src="https://github.com/user-attachments/assets/bd6e4f5d-83f6-44e5-9ee5-cbef9faae4e7" />
2. DNS (used nslookup on CMD prompt
<img width="1235" height="457" alt="Screenshot 2026-06-18 154209" src="https://github.com/user-attachments/assets/45d7e350-bcad-41c3-bf8b-ee80d88987f8" />
3. TCP 3-Way Handshake
- Captured the SYN → SYN-ACK → ACK sequence during a connection setup.
<img width="1198" height="250" alt="Screenshot 2026-06-18 154353" src="https://github.com/user-attachments/assets/d60f60e3-382c-4604-af74-2b36168d1f32" />
4. TCP Port 80 Traffic
<img width="1238" height="465" alt="Screenshot 2026-06-18 155245" src="https://github.com/user-attachments/assets/16675956-4de8-4679-a3ed-0251994e31f0" />
5. Varying traffic capture
<img width="1403" height="458" alt="Screenshot 2026-06-18 155501" src="https://github.com/user-attachments/assets/09c891bb-6d9b-4b69-9baa-62fa0f9c6559" />

Concepts Practiced
- Packet capturing and saving
- Applying Wireshark filters
- Analyzing ICMP, DNS, TCP handshakes, and HTTP
- Documenting findings with screenshots
- Real-world troubleshooting with HTTPS-only environments
