
# GatePass QRSystem - QR Scanner for Security


A lightweight QR code scanning system that uses a camera to scan QR passes in real-time at gates, enhancing security and monitoring entry/exit efficiently.


## Project Overview



This project is a real-time QR scanner built to quickly validate QR codes presented by employees or visitors at gate entry points. It uses a camera to scan the QR codes and immediately determines whether the pass is valid.
## Features

✅ Real-Time QR Scanning

Uses device camera (webcam or mobile camera) for scanning.

Instantly detects and decodes QR codes.


🔐 Security Validation

Can be integrated with a backend to verify QR validity.

Prevents unauthorized or expired QR passes from entry.

📊 Simple Feedback

✅ Green indicator for valid QR codes.

❌ Red indicator for invalid/expired QR codes.
## Tech Stack

| Layer    | Technology                    |
| -------- | ----------------------------- |
| Frontend | HTML, CSS, JavaScript, Tailwind     |
| Backend  | PHP / Laravel                 |
| Database | MySQL                         |
 |QR Scanner Library | html5-qrcode|
| Hosting  | Localhost / Live server       |



## Run Locally

Clone the project

```bash
git clone https://github.com/MasterPhyoPyaeSone/Gate_Scanner-.git
```

Go to the project directory

```bash
  cd Gate_Scanner

```

Install dependencies

```bash
  composer install
  npm install

```

Configure environment

```bash
  DB_DATABASE=QR_SCANNER_SYSTEM
  DB_USERNAME=root
  DB_PASSWORD=

```

Run migrations

```bash
  php artisan migrate --seed
```

Start the server

```bash
  npm run start
  or
  composer run dev
```
