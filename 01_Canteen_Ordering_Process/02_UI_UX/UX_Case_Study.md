
# UI/UX Design Case Study

## UX Goal
Design a fast, low-friction ordering experience for students who may be ordering while moving between classes.

## Primary Persona
**Student Customer**

Needs:
- Fast menu discovery
- Clear prices
- Quick reorder/add-to-cart
- Transparent order status

Pain points:
- Waiting in queues
- Not knowing whether an order has started
- Repeating order details

## User Journey

**Open App → Discover Menu → Select Item → Cart → Checkout → Confirmation → Track → Pickup**

## Information Architecture

Home
- Categories
- Popular Items
- Search

Item Detail
- Image
- Price
- Description
- Quantity
- Add to Cart

Cart
- Items
- Quantity controls
- Total
- Checkout

Order Tracking
- Order ID
- Status timeline
- Estimated time
- Pickup action

## Usability Heuristics Applied

1. Visibility of system status — order timeline.
2. Match with real world — familiar cart/checkout language.
3. User control — edit/remove cart items.
4. Consistency — repeated status labels and actions.
5. Error prevention — order review before submission.
6. Recognition over recall — categories and visible prices.
7. Accessibility — readable text and clear state indicators.

## Design System

- Typography: Inter / system sans-serif
- Layout: 8px spacing system
- Radius: 12–16px cards
- Primary action: high-contrast CTA
- Status: distinct labels for Pending / Preparing / Ready
- Components: cards, chips, buttons, bottom navigation, timeline
