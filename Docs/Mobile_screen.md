Make all existing UI components fully mobile responsive, following the layout conventions of modern food-delivery apps (foodpanda, iFood, Pizza Hut style).

Requirements:

LAYOUT
- Convert multi-column/grid layouts to a single-column stacked layout on mobile (breakpoint below 768px).
- Product/menu cards should switch from vertical grid cards to full-width horizontal cards (image left ~35%, content right ~65%) to fit more items per scroll without wasted whitespace.
- Category filters should become a horizontal scrollable row of pill/chip buttons instead of a static row.
- Replace top navigation menu with a hamburger icon + fixed bottom tab bar (5 icons max: Home, Menu, Offers, Orders, Profile) with active-state highlighting.
- Hero/banner sections should scale down proportionally and keep text left-aligned with the image cropped/scaled to fit, not stretched.

SPACING & SIZING
- Screen margins: 16px on both sides.
- Gap between stacked cards: 12–16px.
- Touch targets (buttons, icons, quantity steppers) minimum 40x40px for accessibility/tap accuracy.
- Primary CTA buttons: full-width or near-full-width pill buttons, 48–52px height, rounded-full corners.
- Card border-radius: 16–20px, consistent across all components.

TYPOGRAPHY
- Scale down headline sizes by ~20–30% from desktop (e.g., 32px desktop headline → 22–24px mobile).
- Body/description text: 13–14px, adequate line-height (1.4–1.5) for readability on small screens.
- Truncate long descriptions to 1–2 lines with ellipsis on card views; full text only on detail pages.

INTERACTIVE ELEMENTS
- Sticky/floating cart summary bar at the bottom of menu screens showing item count + total + "View Cart" CTA.
- Quantity steppers (−/quantity/+) should be compact and thumb-friendly, positioned within easy reach (bottom third of screen where possible).
- Search bar: full-width, sticky below the top bar, with a filter icon docked to the right.
- Notification and cart icons in the top bar should always show badge counts.

GENERAL
- Preserve existing color palette, fonts, and component styling — only adjust layout, spacing, and sizing for smaller viewports.
- Test at common breakpoints: 375px (small phones), 390–430px (standard phones), 768px (tablet transition).
- Prioritize thumb-reachability: primary actions in the bottom half of the screen, secondary/informational content up top.