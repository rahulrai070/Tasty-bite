# 🍕 Tasty Bites — Food Ordering Interface

A responsive, mobile-first food ordering UI built with vanilla HTML, CSS, and JavaScript. Focused on smooth navigation, menu browsing, and cart management — no frameworks, no build tools, just clean front-end fundamentals.

**🔗 Live demo:** [rahulrai070.github.io/Tasty-bite](https://rahulrai070.github.io/Tasty-bite/)

## Features

- **Category filtering** — browse dishes by Starters, Mains, or Drinks with instant re-rendering, no page reload
- **Menu browsing** — dish cards with images, descriptions, and pricing, rendered dynamically from a JS data array
- **Item selection** — add items with one tap; quantity stepper (+/−) appears once an item is in the cart
- **Cart management** — live subtotal, service charge, and total; remove items individually
- **Persistent cart** — order is saved to `localStorage`, so it survives a page refresh
- **Mobile-first design** — sticky bottom order bar on small screens, slide-in cart drawer styled like a kitchen order ticket
- **Responsive layout** — menu grid adapts from 1 column (mobile) to 3 columns (desktop)
- **Accessibility touches** — keyboard `Esc` to close cart, `aria` attributes on interactive elements, respects `prefers-reduced-motion`

## Tech stack

- HTML5
- CSS3 (custom properties, Flexbox, CSS Grid, no framework)
- Vanilla JavaScript (ES6+, no dependencies)
- Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces), [Work Sans](https://fonts.google.com/specimen/Work+Sans), [Space Mono](https://fonts.google.com/specimen/Space+Mono) via Google Fonts

## Project structure

\`\`\`
Tasty-bite/
├── index.html      # Page markup
├── style.css       # Design tokens, layout, components
├── script.js       # Menu data, rendering, cart logic
└── *.jpg / *.avif  # Dish and banner images
\`\`\`

## Running locally

No build step required.

\`\`\`bash
git clone https://github.com/rahulrai070/Tasty-bite.git
cd Tasty-bite
\`\`\`

Then just open \`index.html\` in your browser, or serve it locally:

\`\`\`bash
python -m http.server 8000
\`\`\`

## Notes

- This is a front-end demo — "Send to kitchen" simulates checkout (clears the cart and shows a confirmation) since there's no backend or payment processing connected.
- Dish photos are pulled from Unsplash for demo purposes.

## Author

**Rahul Rai** — [GitHub](https://github.com/rahulrai070)