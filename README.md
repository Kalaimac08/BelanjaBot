BelanjaBot 💸📱
Your personal Android expense-tracker bot built for Malaysians: record daily spending, snap & store receipts, manage monthly budgets, grow savings goals, and track LHDN tax-relief categories (YA 2025 & YA 2026) so filing your taxes is painless.
📲 Install the app (APK)
File: BelanjaBot.apk (debug build, ~17 MB, Android 8.0 / API 26 and above)
Download BelanjaBot.apk to your phone (or transfer it via USB / Google Drive / WhatsApp / Telegram "Saved Messages" to yourself).
Tap the file. Android will warn about installing unknown apps → tap Settings → Allow from this source (this is normal for any app installed outside the Play Store).
Tap Install, then open BelanjaBot. 🎉
Privacy: all data (expenses, receipts, savings) stays inside the app's private storage on your phone. Nothing is uploaded anywhere. Uninstalling the app deletes its data — export CSVs regularly if you uninstall (see below).
✨ What it does
Tab
Features
Home
Month overview, today's spend, budget progress, category breakdown, recent expenses, tax-relief tagged total
Expenses
Full history grouped by date, filters (All / This month / 🧾 Tax-relief), delete, Export CSV
+ Add
Amount, category emojis chips, date picker, note, Tax deductible? toggle → LHDN relief category, 📷 receipt photo / 🖼️ gallery (auto-compressed & stored offline)
Budget
Overall monthly budget + per-category budgets; bars turn yellow ≥ 80% and red ≥ 100%
Savings
Multiple goals (e.g. emergency fund, holiday), add/withdraw funds, progress bars
Tax
All Malaysian relief categories with live limits, claimed, remaining, group caps (Medical RM10,000, Life+EPF RM7,000), YA 2025 / YA 2026 switch, tax-saving estimator by bracket, Export for e-Filing (CSV), automatic-reliefs reference list
Tax-relief workflow
When recording an expense, switch on 🧾 Tax deductible? and pick the LHDN category (e.g. Lifestyle for your new phone, Sports for gym, Education & medical insurance for premiums).
Attach the receipt photo — it stays linked to the expense.
In the Tax tab, watch each category fill toward its RM limit. Bars max out when you hit the LHDN cap (so you never over-track).
At filing time, tap 📤 Export for e-Filing (CSV) — a summary with claimed/effective amounts (caps applied) plus a line-item list of entries and receipt file names.
Keep original receipts for 7 years — LHDN can request proof in an audit.
Export & backup
Expenses CSV: Home ⋮ menu → Export this month; Expenses → share icon.
Tax Relief CSV: Tax tab → Export for e-Filing.
Share straight into Google Drive, WhatsApp, email, etc. CSVs open in Excel.
🛠️ Rebuild from source (optional)
The project is a standard Android Studio project (Kotlin + Jetpack Compose + Room).
# Open in Android Studio (Hedgehog or newer) → Sync → Run.
# Or command line:
./gradlew assembleDebug
Tech: Kotlin 1.9.24, AGP 8.5.2, Compose BOM 2024.06.00, Room 2.6.1 (KSP), Coil, Material 3, minSdk 26 / targetSdk 34.
⚠️ Disclaimer
BelanjaBot is a personal tracking aid. Tax relief figures reflect LHDN categories for YA 2025/YA 2026 (incl. Budget 2025 & Budget 2026 announcements) — always verify on hasil.gov.my before filing. Not tax advice.
See MALAYSIA_TAX_RELIEF.md for the full relief reference used by the app.
