# Lunches Dunches — GitHub Pages Edition

This is the consolidated phone-first Lunches Dunches app.

## Included
- Lunch menu with categories: Salads, Bowls, Sandwiches & Wraps, Smoothies & Drinks, Snacks
- Meal prices, calories, protein, carbs, fat and fiber
- 1–5 lunch planning
- Monday–Friday planner
- 3-lunch 10% discount and 5-lunch 20% discount
- 7-day lead-time checkout rule
- Orders and pickup-code/QR-style display
- Parent/child/school/grade profile
- Bento-return / lower-waste messaging
- Professional Kitchen area
- Ingredients with search/sort
- Drag-and-drop custom ingredient order saved locally
- Recipes and recipe costing
- Portion cost, selling price and food-cost percentage
- Inventory quantities and inventory value
- Invoice photo OCR with browser-side Tesseract loading
- JSON backup/import
- Chef Buddy for meal choices, nutrition, planning, costing, inventory and order help
- PWA manifest for Android home-screen installation

## GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `manifest.json`, `icon-192.png`, and `icon-512.png`.
3. In GitHub: Settings → Pages → Deploy from branch → choose `main` and `/root`.
4. Open the published URL on the Samsung phone.
5. Use the browser menu → Add to Home screen / Install app.

## Important
This version stores app data locally in the browser with localStorage. The checkout creates a local demonstration order; it does not charge a credit card or connect to a real vending machine/payment processor.

The invoice OCR library is loaded only when the user scans an image invoice, so the basic app remains lightweight.
