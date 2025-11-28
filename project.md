# Project: Shah Clock Agencies - Wholesale Gifting Website
**Version:** 1.0  
**Date:** November 28, 2025  
**Status:** Ready for Development  

---

## 1. Project Overview
**Objective:**  
Build a fast, static, and responsive website for **Shah Clock Agencies** to serve as a digital catalog for wholesale buyers. The site will highlight product categories and drive inquiries via WhatsApp or Phone.

**Target Audience:**  
- Corporate Gift Buyers
- Retail Shop Owners
- Event Organizers

**Key Features:**  
- **Zero Bloat:** Pure HTML/CSS for maximum speed.
- **Mobile-First:** Optimized for browsing on phones (where most WhatsApp inquiries originate).
- **Clear Navigation:** Simple flow from Home → Category → Enquiry.

---

## 2. Sitemap & Page Structure
The project consists of **7 HTML files**:

1.  `index.html` (Landing Page)
2.  `bottles.html` (Category Listing)
3.  `mugs.html` (Category Listing)
4.  `notebooks.html` (Category Listing)
5.  `pens.html` (Category Listing)
6.  `electronics.html` (Category Listing)
7.  `bags.html` (Category Listing)

---

## 3. Detailed Requirements

### 3.1 Global Navigation (Header)
*   **Logo:** "Shah Clock Agencies" (Text or Image)
*   **Subtitle:** "Wholesale Gifting Supplier"
*   **Menu Items:** 
    *   [Categories](#categories)
    *   [About](#about)
    *   [Why Us](#why)
    *   [Contact](#contact)
*   **CTA Button:** "Enquiry" (Links to Contact or WhatsApp)

### 3.2 Home Page (`index.html`)
*   **Hero Section:** 
    *   Headline: "Bulk Gifting Made Simple"
    *   Subtext: "We provide bottles, mugs, notebooks, pens, electronics & bags for retailers and corporate bulk buyers."
    *   Action: [View Categories] [Contact Us]
*   **Category Grid:** 
    *   Display 6 cards. Clicking a card opens the corresponding HTML page.
    *   *Data:* Bottles, Mugs, Notebooks, Pens, Electronics, Bags.
*   **About Section:** 
    *   Text about practical gifting and wholesale pricing.
*   **Why Us:** 
    *   3 Columns: Wholesale Pricing, Quality Range, Quick Support.
*   **Footer/Contact:** 
    *   Phone, Email, Location, and Copyright info.

### 3.3 Category Pages (Template)
*   **Header:** Consistent with Home page.
*   **Page Title:** e.g., "Wholesale Bottles Collection"
*   **Product Grid:** 
    *   Responsive Grid (1 col mobile, 3 col desktop).
    *   **Card Content:** Image, Product Name, Description, MOQ (e.g., "Min: 50 pcs").
    *   **Action:** "Ask Price" button linking to WhatsApp.
*   **Navigation:** "← Back to Home" link.

---

## 4. Design Specifications

### Color Palette
*   **Primary (Navy/Slate):** `#0F172A` (Header, Footer, Headings)
*   **Accent (Gold/Amber):** `#F59E0B` (Buttons, Highlights)
*   **Background:** `#F8FAFC` (Light Grey/White)
*   **Text:** `#334155` (Dark Grey for readability)

### Typography
*   **Font:** Inter, Roboto, or sans-serif system fonts.
*   **Base Size:** 16px.
*   **Headings:** Bold and clear.

### Layout Rules
*   **Container Width:** Max 1200px, centered.
*   **Padding:** Generous whitespace (e.g., `padding: 4rem 0` for sections).
*   **Mobile:** Stack flex containers vertically using `@media (max-width: 768px)`.

---

## 5. Technical Implementation

### Folder Structure
