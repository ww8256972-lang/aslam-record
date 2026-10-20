# ASLAM RECORD — Native Android Shop Management App

**ASLAM RECORD** is a modern, native Android application built with Kotlin, Jetpack Compose, Material 3, and Room Database. Designed for retail shopkeepers and wholesalers to manage inventory, sales, purchases, customer credit ledgers (Khata / Udhar), receipts, expenses, and WhatsApp payment reminders.

## Build

```bash
git clone https://github.com/ww8256972-lang/aslam-record.git
cd aslam-record
chmod +x gradlew
./gradlew assembleDebug
```

Open in Android Studio (JDK 17+) for best results.

## Features

- Product & inventory management
- Sales & digital invoices
- Customer & supplier Khata (credit ledger)
- Expenses & financial reports (P&L)
- WhatsApp reminders & share receipts
- AI assistant (Gemini API — key via secrets / .env, not hardcoded)

## Security

- Do not commit `.env`, keystores, or real API keys
- Use `.env.example` as a template only
