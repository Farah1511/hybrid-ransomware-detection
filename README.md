# Hybrid Ransomware Detection using Deep Learning

## 📌 Project Overview
This project explores hybrid deep learning approaches for detecting ransomware and zero-day malware.  
We use **EMBER dataset** (features), **BODMAS dataset** (binaries), and apply models:
- MLP (baseline)
- CNN (byte images)
- Transformer (opcode/API sequences)


## 🚀 Workflow
1. Load EMBER dataset → train baseline MLP.
2. Convert BODMAS binaries → byte images → train CNN.
3. Extract opcode/API sequences → train Transformer.
4. Fuse models → hybrid approach.
5. Test on zero-day + family hold-out.

