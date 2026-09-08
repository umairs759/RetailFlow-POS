🚀 Quick Start

Option 1: Just Open It

    Download the index.html file from this repo

    Double-click it — that's it. It runs in any modern browser (Chrome, Edge, Firefox, Safari)

Option 2: Host on GitHub Pages (Free)

    Push this repo to GitHub

    Go to Settings → Pages → Source → Deploy from branch → main

    Your store console is live at https://yourusername.github.io/RetailFlow-POS/

Option 3: Run Locally (Optional)
bash

# No build step, no dependencies. Just serve the file:
npx serve .
# or
python -m http.server 8080

🔌 Hardware That Works Out of the Box

Device	How It Connects	Notes

USB Barcode Scanner	Keyboard-wedge emulation	Scan directly into billing — no setup needed

Bluetooth Scanner	HID profile	Same as USB, works on laptops & tablets

Thermal Receipt Printer (58/80mm)	USB/Bluetooth/Network	Uses browser print dialog — no driver needed

Cash Drawer	Connects to receipt printer	Triggered by receipt print

Android Phone/Tablet	Bluetooth scanner + OTG	Full mobile experience

📱 Mobile-First Design

The entire console is fully responsive. On a phone or tablet:

    The sidebar collapses into a hamburger menu

    Buttons and touch targets are sized for fingers

    Barcode scanning works with the camera (via external scanner apps) or Bluetooth scanners

🗂 Data & Storage

    100% local — everything stores in your browser's localStorage

    No internet required — works during load-shedding, no sync delays

    No server costs — your data never leaves the shop

    Backup tip: Export by clicking the storage key in DevTools → Application → Local Storage, or use the WhatsApp receipts as your daily record

🧪 Pre-Loaded Demo Data

The app ships with:

    12 fully-configured products with realistic Pakistani prices and expiry dates

    40+ additional starter catalog entries for common FMCG items

    3 sample customers ready for khata testing

    Demo barcodes for products that have them

    To reset to factory data: Clear the anjum_iqbal_store_v4 key from your browser's Local Storage.

🛠 Tech Stack

Layer	Technology

Frontend	Vanilla HTML5, CSS3 (custom properties), JavaScript (ES6+)

Fonts	Fraunces (display), Inter (UI), JetBrains Mono (figures)

Storage	localStorage (zero external dependencies)

Build	None — it's a single, self-contained HTML file

Deployment	GitHub Pages, Netlify, Vercel, or any static host

No frameworks. No build step. No npm. No server. This makes it:

    🔒 Secure — no cloud, no data leaks

    ⚡ Fast — loads instantly, works offline

    💰 Cheap — free to run forever

🎨 Design Philosophy

The interface follows a "dark luxury retail" aesthetic:

    Obsidian ground with subtle radial gradients for depth

    Brass accent — evokes trust and premium quality

    Emerald & crimson for financial states (profit/loss, in-stock/out)

    Serif display font (Fraunces) for brand moments

    Monospace figures — numbers feel exact, like a ledger

    Generous spacing — uncluttered, professional, easy to read at a glance

Every pixel was chosen to make the shopkeeper feel like they're using a premium tool, not a spreadsheet.
📋 Feature Comparison

Feature	RetailFlow POS	Basic Register	Excel	Other POS

Barcode scanning	✅	❌	❌	⚠️ paid

Khata / Udhaar tracking	✅	❌	❌	⚠️ complicated

WhatsApp reminders	✅	❌	❌	❌

Expiry watch	✅	❌	❌	❌

Shift / drawer audit	✅	❌	❌	❌

Cost & profit margin	✅	❌	⚠️ manual	✅

Works offline	✅	✅	✅	❌

No monthly fee	✅	✅	✅	❌

Mobile-friendly	✅	❌	❌	⚠️

🔮 Roadmap

What's coming next:

    □

    PWA / Offline install — install as an app icon on phone
    □

    Cloud backup — optional encrypted sync to Google Drive
    □

    Multi-store support — run two branches from one account
    □

    Supplier order sheets — auto-generate purchase orders from low stock
    □

    Barcode label printing — print shelf labels with price
    □

    Customer purchase history — see what each customer buys most
    □

    Daily profit report — auto-calculated end-of-day summary

🤝 Contributing

This is an open-source project built for Pakistani retailers. If you run a shop or know someone who does:

    Use it — every bug you find, every feature you wish for, matters

    Report issues — open a GitHub issue with screenshots

    Suggest features — what would make your shop run smoother?

    Spread the word — share this repo with other shopkeepers


⚠️ Important Note

This project is a frontend demonstration and runs entirely in the browser. It does not include:

    A backend server

    Multi-device syncing

    WhatsApp Business API integration (uses wa.me click-to-chat links instead)

For a production multi-counter deployment, you would need to add a server (Node.js, Firebase, Supabase, etc.) — but for 95% of single-counter Pakistani shops, this is all they need.

📄 License

MIT — free to use, modify, and distribute. Credit appreciated but not required.
🙏 Acknowledgments

Built with love for the shopkeepers of Pakistan who keep our economy running — one thela, one dukan, one khata at a time.

Made by Umair · GitHub: @umairs759

🚀 Deploy in 60 Seconds

bash

# Clone the repo
git clone https://github.com/umairs759/RetailFlow-POS.git
cd RetailFlow-POS

# Just open it
open index.html
# or
start index.html

# Or deploy to GitHub Pages:

# 1. Push to your GitHub repo

# 2. Settings → Pages → Source → main branch

# 3. Your POS is live at: https://yourusername.github.io/RetailFlow-POS/


💬 Feedback

If you use this in your shop, I want to hear from you:

    What worked?

    What broke?

    What feature would make your day easier?

Open an issue or reach out — every suggestion shapes the next version.
