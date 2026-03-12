# LandChain (KhestraBlocks HackIndia MVP)

A demo blockchain-based property registry platform for hackathon judging.

## Features
- Demo Google login flow.
- Identity verification upload (Aadhaar / Government ID / Property docs).
- Wallet generation (public/private key and wallet address).
- Property marketplace with filters (city, zone, price, size).
- Property details and ownership transfer flow.
- Fake blockchain block creation using SHA-256 hashing.
- Public blockchain explorer.
- Government authority dashboard for Proof-of-Authority style approvals.

## Tech Stack
- Frontend: HTML, CSS, JavaScript-ready templates with glassmorphism style.
- Backend: Python + Flask.
- Database: SQLite.
- Blockchain simulation: Python module.

## Run Locally
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

Open `http://127.0.0.1:5000`.

## Demo Flow
1. Login with Google (demo form).
2. Upload identity documents.
3. Generate wallet.
4. Register / browse properties in marketplace.
5. Transfer ownership from property detail page.
6. View generated block in Blockchain Explorer.
7. Review pending approvals in Government Node dashboard.
