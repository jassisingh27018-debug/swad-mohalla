# 🍲 Swad Mohalla — *Rasoi se rozgar tak*

A hyperlocal online marketplace where local food entrepreneurs, especially women-led home kitchens, can register, list homemade food (meals, achar, papad, snacks), manage orders, set their own prices and connect with customers in their own locality. Food moves by a **dabbawala-style delivery model** using coded dabbas, Dabba Points and local delivery partners.

Built by **Team Data Dynamo** for **BuildHer Bharat 2026**.

> **Note:** This is a clickable front-end prototype with dummy data. There is no real backend, payment or delivery yet.

## 🔗 Live demo

`https://<jassisingh27018-debug>.github.io/swad-mohalla/`

(Enable it under **Settings → Pages → Deploy from branch → `main` / root**.)

## The problem

| Gap | Today |
|---|---|
| **Customer** | Home kitchens are found only by word of mouth and WhatsApp groups |
| **Vendor** | Orders, menus, prices and payments are juggled in notebooks and chats |
| **Delivery** | Independent partners lack clear order details and predictable pickups |

## Three interfaces

- **Customer** — discover nearby kitchens, browse menus, order now / pre-book / subscribe monthly, pay by UPI or cash on delivery, track and rate the meal.
- **Seller** — create a storefront, list items and prices, accept orders, set daily capacity, and use **Finance Saathi**.
- **Delivery partner** — set availability, see nearby requests with payout and distance, accept or reject freely, pick up and deliver with an OTP.

## What makes it different

- **Finance Saathi** — cost-per-item calculator, daily cash book, and a savings and growth planner, so a cook sees her real profit, not just her orders.
- **Dabbawala-style delivery** — coded dabbas (e.g. `SM-12`), veg / non-veg colour tags, Dabba Points and delivery slots.
- **Partners choose their runs** — accept or reject each request; rejected offers move on.
- **Pre-booking and monthly subscriptions** for regular tiffin customers.
- **Multilingual** — English, हिन्दी, मराठी, বাংলা, தமிழ், తెలుగు, ગુજરાતી.
- **Light and dark mode**, mobile-first layout.

## Run it locally

No build step. It is a single self-contained file.

```bash
git clone https://github.com/<jassisingh27018-debug>/swad-mohalla.git
cd swad-mohalla
# just open index.html in a browser, or:
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Repository structure

```
swad-mohalla/
├── index.html      # the full clickable prototype (HTML + CSS + JS)
├── docs/           # the hackathon pitch deck (PPTX)
├── LICENSE         # MIT
└── README.md
```

## Proposed production stack (Phase 1 MVP)

| Layer | Plan |
|---|---|
| Front end | Responsive PWA in React with role-based screens |
| Back end | Node.js and Express (login, orders, dispatch) |
| Database | PostgreSQL or Supabase (menus, orders, ledgers) |
| Integrations | Maps, UPI payments, speech-to-text |

**Roadmap:** Phase 1 MVP → Phase 2 local pilot with a few home kitchens → Phase 3 scale (voice-first onboarding, subscriptions, group orders, festival hampers, SHG storefronts).

## 👩‍💻 Team Data Dynamo

- Jassi Singh (Team Leader)
- Aarushi Goel
- Avika Kaushik
- Richa Mishra

## License

Released under the [MIT License](LICENSE).
