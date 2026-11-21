# Concourse

A concept app for ordering food, drink and merch at a football stadium, built around the Coventry Building Society Arena.

## The apps

| Page | What it is |
|---|---|
| `index.html` | Landing page with links to everything |
| `customer.html` | Customer (fan) app: stadium map, kiosks, menus, ordering, order tracking, "ready for collection" notification, ads |
| `kitchen.html` | Kitchen / staff screen: incoming orders, *Start preparing*, *Ready — notify customer*, *Collected*, demo autopilot |
| `demo.html` | Both apps side by side on one screen, for presenting |

## How to demo

1. Open `customer.html` and `kitchen.html` in two windows of the **same browser on the same device**.
2. Place an order in the customer app. It appears on the kitchen screen straight away.
3. On the kitchen screen press **Start preparing**, then **Ready — notify customer**. The customer app shows the notification.
4. Or leave **Demo autopilot** on (2 minutes by default) and orders go ready on their own.
5. Use **Clear demo orders** on the kitchen screen to reset.

The two apps share orders through the browser's local storage, so they only sync on the same device and browser. Syncing a real phone with a separate kitchen tablet needs a small backend (for example a realtime database).

## Notes

Concept prototype, not affiliated with the venue or club. The kiosk list comes from the venue's [matchday food & drink page](https://www.coventrybuildingsocietyarena.co.uk/matchdayfoodanddrink). Prices, menus, queue times, adverts and the match are illustrative, and payments are simulated.
