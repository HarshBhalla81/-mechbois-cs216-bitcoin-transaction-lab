# mechbois-cs216-bitcoin-transaction-lab

## Objective
To understand the creation and validation of Bitcoin transactions using Legacy (P2PKH) and SegWit (P2SH-P2WPKH) address formats by interacting with `bitcoind` using Python, analyzing transaction scripts, and comparing transaction sizes.

---

## Project Structure
│
├── src/
│ ├── legacy_p2pkh.py
│ ├── segwit_p2sh_p2wpkh.py
│
├── requirements.txt
├── README.md
└── report.pdf

---

## Tools & Technologies
- Bitcoin Core (`bitcoind`, `bitcoin-cli`)
- Python 3
- python-bitcoinlib
- python-bitcoinrpc

---

## Team
**Team Name:** MechBois  
(Team member details mentioned in the report)

---

## Notes
- Bitcoin Core is run in **regtest mode**.
- Private keys are managed by the Bitcoin Core wallet.
- Transactions are created, signed, and decoded using RPC calls.
