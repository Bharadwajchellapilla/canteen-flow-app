# SmartServe Diner

Create a modern, professional web application UI for a college project titled:

“Dr. B.R. Ambedkar University”

SmartServr Canteen

The application should be clean, visually appealing, and mobile-friendly like a real food ordering app.

🎨 DESIGN:

- Background: light (#f8f9fa)

- Primary color: green (#28a745)

- Accent color: blue (#007bff)

- Font: Inter or Roboto

- UI: rounded cards, soft shadows, smooth animations

- Fully responsive (mobile + desktop)

-------------------------------

MODULE 1: CUSTOMER (QR MENU)

-------------------------------

- User scans QR code placed on table → menu opens instantly

- Display table number clearly (e.g., Table 3)

Menu Categories:

Tiffin:

Coffee ₹8, Tea ₹5, Milk ₹7, Idli ₹12, Plain Dosa ₹15, Masala Dosa ₹25 (⭐ Popular)

Meals:

Plate Meals ₹40, Full Meals ₹55, Veg Fried Rice ₹50, Egg Fried Rice ₹65

Snacks:

Samosa ₹5, Veg Puff ₹10, Egg Puff ₹20, Veg Noodles ₹20, Chicken Noodles ₹60 (⭐ Popular)

Each Item Card:

- Name + Price

- Veg (🟢) / Non-Veg (🔴) indicator

- “Add” button

- Customization options:

  - Less Sugar

  - Extra Hot

  - Extra Spicy

Cart System:

- Top cart icon with item count

- Bottom sticky bar showing total price

- “Place Order” button

Order Flow:

- Generate token number automatically (FIFO queue)

- Show status: “Waiting for Payment”

Payment:

- Option 1: Scan & Pay (UPI QR display)

- Option 2: Cash on Delivery

- After payment → status updates to “Paid”

-------------------------------

MODULE 2: CHEF DASHBOARD

-------------------------------

- Display ONLY paid orders

- FIFO queue system

- Order card includes:

  - Token number

  - Table number

  - Ordered items

Buttons:

- “Preparing”

- “Ready”

- Highlight current order

- Smooth real-time updates

-------------------------------

MODULE 3: ADMIN DASHBOARD

-------------------------------

(Login required)

Features:

- Total Orders Today

- Total Revenue

- Most Sold Item

- Monthly Profit/Loss

Visualizations:

- Bar Chart (daily sales)

- Pie Chart (item distribution)

Extra:

- Stock management

- Menu update (add/edit items)

-------------------------------

MODULE 4: TOKEN DISPLAY

-------------------------------

- Large display screen:

  - “Now Serving: Token #12”

  - “Next: #13, #14”

- Big bold font

- High visibility UI

-------------------------------

FLOW:

-------------------------------

Customer scans QR → Menu opens → Selects items → Places order → Token generated → Payment done → Chef receives order → Prepares → Marks ready → Token displayed → Customer collects food

-------------------------------

EXTRA FEATURES:

-------------------------------

- Smooth animations

- Real-time feel

- Clean professional UI

- Fast and minimal interaction

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://canteen-flow-app.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/64991040-66dd-48bf-9efe-b6f04b9b44f1).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
