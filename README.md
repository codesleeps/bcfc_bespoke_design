# BCFC Bespoke Design — Luxury Venetian Wall Art

A premium, high-end portfolio and interactive product customizer website for **BCFC Bespoke Design**, showcasing handcrafted Venetian plaster wall art, gold leaf statement panels, and boardroom murals.

---

## Technical Stack
- **Core Structure**: HTML5 semantic markup.
- **Styling**: Modern, premium CSS3 stylesheet featuring smooth transitions, perspective 3D effects, custom cursors, and responsive layouts.
- **Interactions**: Vanilla JavaScript for the custom designer, admin creator portal, and contact flow.
- **Icons**: Tabler Icons CDN integration.

---

## Key Features

### 1. Interactive Plaster Panel Customizer
An in-browser design customizer that allows prospective clients to configure custom artisan plaster panels:
- **Size Options**: A2, A1, A0, or custom dimensions.
- **Plaster Texture**: Choice between textured Marmorino lime-based plaster or smooth, high-sheen Venetian plaster.
- **Precious Metal Inlays**: Design options for Signature Gold Leaf, Silver Leaf, or Artisan Copper Leaf detailing.
- **Timber Species Frame**: Custom frames crafted from European Oak, Walnut, Ash, or a matching plastered timber frame.
- **Live Estimation Engine**: Calculates exact panel thickness, estimated weight (in kg), and approximate pricing in real-time as choices are adjusted.

### 2. Artisan Showcase Grid
A showcase of premium completed projects:
- **Continuous Shimmer Tilt**: Images features a perspective 3D rotation (`plasterTilt`) and a linear gold glare sweep (`plasterGlare`) looping by default to simulate how the burnished Venetian plaster and gold leaf panels reflect light in real-world environments.
- **Clean Interface**: No mock video controls or overlays, ensuring a clean, loading-free visual grid.

### 3. Dedicated Specifications Sheet
An integrated specification view (bcfc_spec_sheet.html) providing detailed architects' specifications, structural weights, load tolerances, and wall mounting instructions.

### 4. Admin Creator Portal
An embedded portal allowing creators to test layout insertions by adding custom highlights directly into the live page feed.

### 5. Structured Contact Flows
- Fully integrated contact form that formats user enquiries and redirects them directly to the official WhatsApp business line: **`+447908677945`**.

---

## File Structure
- [index.html](index.html): Contains the main showcase layouts, customization panel, creator portal, and primary styling.
- [bcfc_spec_sheet.html](bcfc_spec_sheet.html): Contains material compositions, architectural load sheets, and mounting dimensions.

---

## Getting Started

### Local Development
To view the site locally, you can open `index.html` directly in any web browser, or spin up a simple local server:

**Using Python:**
```bash
python3 -m http.server 8000
```
Then visit: `http://localhost:8000`

**Using Node (http-server):**
```bash
npx http-server ./ -p 8000
```
Then visit: `http://localhost:8000`
