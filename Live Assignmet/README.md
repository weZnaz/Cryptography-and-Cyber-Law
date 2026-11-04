# OSI 7-Layer Communication Simulation

**Student:** Syed Nazmul Islam  
**ID:** IT22023  
**Department:** ICT, MBSTU

## Overview
This project simulates communication through all **7 layers of the OSI Model** using C socket programming and Python visualization.

### OSI Layers
1. Application
2. Presentation
3. Session
4. Transport
5. Network
6. Data Link
7. Physical

## How It Works
- Python takes the user message.
- C Client performs OSI layer encapsulation.
- Data is sent using TCP socket.
- C Server performs decapsulation.
- The original message is recovered.
- Python shows the communication flow.

## Technologies
- C
- Python
- TCP Socket
- VS Code

## Run
```bash
make
./server
./client
```

For Python visualization:
```bash
python3 python/user_app.py
```

## Output Screenshots

### Output 1
<!-- Insert Screenshot 1 here -->
<img width="945" height="851" alt="Screenshot 2026-11-04 105053" src="https://github.com/user-attachments/assets/c7a85a8d-4f1e-4df0-b7f8-2aa91ddd2f9c" />



### Output 2
<!-- Insert Screenshot 2 here -->
<img width="962" height="812" alt="Screenshot 2026-11-04 105038" src="https://github.com/user-attachments/assets/b4513845-7ff2-4f14-ae92-7908a23c3d95" />

## Learning Outcome
This project helped me understand the **OSI 7-layer model, encapsulation, decapsulation, and TCP socket communication**.

## Author
**Syed Nazmul Islam**  
**IT22023 | ICT | MBSTU**
