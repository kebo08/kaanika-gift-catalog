# kaanika.gifts — GIFT CATALOG

An interactive, responsive gift catalog with five combos. Built for GitHub Pages.

| Combo | Selling price (INR) | Includes |
| --- | ---: | --- |
| 01 | ₹995 | Blender, thank you card, bag |
| 02 | ₹905 | Calendar flipper, small sipper, laptop stand, thank you card, bag |
| 03 | ₹800 | Vacuum bottle, Clue card game, thank you card, bag |
| 04 | ₹805 | Laptop bag, Clue card game, thank you card |
| 05 | ₹975 | Laptop bag, Protonic cable set, small sipper, thank you card |

## Hosting

Enable GitHub Pages from the `main` branch, `/ (root)`. No build process or server is required. Product assets and animation scripts are embedded in `index.html`. Google Fonts is optional; system fonts provide a fallback.

## Content and images

Product visuals combine matching transparent assets from the original catalog with AI-generated cutouts guided by the owner's reference photographs. Gift bags, game cards and the animated packaging are illustrative. No Splunk branding or gift box is used.

## Bag animation

The bag opens in separate front and back layers. Products rise from the dock, fall through the opening, and disappear behind the front panel before the handles settle closed. Watch/replay controls run the packing sequence; the bag can be reopened. Gift-bag and laptop-bag presentations match their respective combos.

## Accessibility

Keyboard combo navigation, visible focus states, reduced-motion static layout, and a no-JavaScript list of all combos are included.

## Editing

The catalog content is in the `CATALOG` object inside `index.html`; prices are numeric rupee amounts. All site styles and scripts are contained in the same file for portable hosting.
