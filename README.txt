# FEROZ KHKSA VIP SHORTNER

## Features
- Private admin-only login
- Public registration disabled
- Long URL -> short URL
- Custom short code
- Automatic short code
- Click counter
- Delete links
- Facebook/WhatsApp/Twitter Open Graph preview fields
- SQLite database
- Single Python application

## Setup
1. Install Python.
2. Run:
   pip install -r requirements.txt
3. Open app.py and change ADMIN_PHONE and ADMIN_PASSWORD.
4. Start:
   python app.py
5. Open:
   http://127.0.0.1:5000/login

## Public internet use
A real public short URL needs a domain and hosting/server. Set:
PUBLIC_BASE_URL=https://your-domain.com

Also set a strong:
SECRET_KEY=your-long-random-secret

Do not expose ADMIN_PASSWORD in public source code.
