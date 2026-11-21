<div align="center">

# 🎟️ Vouchly (Beta)

### **India's Trust-First P2P Marketplace for Gift Cards, Coupons, Subscription Vouchers & Official Group Plans**

[![Status](https://shields.io)](https://github.com)
[![Market](https://shields.io(INR%20₹)-blue?style=for-the-badge)](https://github.com)
[![Compliance](https://shields.io)](https://github.com)
[![Privacy](https://shields.io)](https://github.com)
[![License](https://shields.io)](#-copyright--intellectual-property)

[The Idea & Vision](#-the-idea--vision) • [Core Features](#-core-features) • [User Workflows](#-user-workflows) • [6-Pillar Trust Architecture](#-6-pillar-trust--safety-architecture) • [Fees & Tax Compliance](#-fees-limits--tax-compliance) • [Roadmap](#-product-roadmap) • [Legal & Copyright](#-copyright--intellectual-property)

</div>

---

## 💡 The Idea & Vision

### The Problem
Every year in India, millions of rupees worth of digital rewards—earned via UPI apps (Google Pay, PhonePe, Paytm), credit card points, and corporate gifting—go **unused and expire**. At the same time, consumers looking for discounts or multi-user subscription plans (like YouTube Premium, Spotify Family, Microsoft 365, or OTT family packs) are forced to either pay full retail price or rely on risky, unmoderated Telegram/WhatsApp groups where scams, password leaks, and account bans are common.

### The Vouchly Solution
**Vouchly** bridges this gap by creating a structured, escrow-backed, peer-to-peer (P2P) digital value exchange built specifically for Indian consumers:
1. **Liquidity for Unused Value:** Sellers turn idle gift cards, single-use cashback coupons, and transferable subscription vouchers into instant UPI cash.
2. **Safe Cost-Splitting:** Hosts of official multi-seat subscriptions can split empty seats with verified members using the service's **official invite link**—eliminating password or OTP sharing completely.
3. **Zero-Trust Security:** Buyers never pay blindly, and sellers never expose codes publicly. Codes stay cryptographically/logically locked until payment succeeds, backed by screen-record dispute resolution.

> **⚠️ Current Beta Scope:** Vouchly Beta is an interactive MVP built to validate user demand and test core UX flows. In this phase, payment gateways are simulated, and all listings, requests, and preferences are persisted locally in the user's browser (`localStorage`) with zero third-party tracking.

---

## ✨ Core Features & Capabilities

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔒 Pay-to-Unlock Vault</h3>
      <p>Voucher codes, gift card PINs, and redemption links are strictly hidden from public view. The code unlocks exclusively for the buyer once escrow payment is confirmed.</p>
    </td>
    <td width="50%" valign="top">
      <h3>👥 Official Group Plan Splitting</h3>
      <p>Split 2 to 5 seats on official multi-user plans (Monthly or Yearly). Members join with their own personal login via official invites—never shared credentials.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ Smart UPI Offer Auto-Fill</h3>
      <p>Sellers can paste raw reward text copied directly from GPay or PhonePe, automatically extracting and formatting brand names, offer titles, and descriptions.</p>
    </td>
    <td width="50%" valign="top">
      <h3>📢 "Want to Buy" Demand Board</h3>
      <p>Can't find a specific voucher? Buyers post what they need along with their maximum price ceiling (₹), triggering instant email alerts to matching sellers.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧮 Live Earnings & Seat Calculators</h3>
      <p>Real-time calculation of net seller payouts (after the 5% fee) when listing vouchers, and automatic per-seat cost splitting when creating group plans.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🔍 Granular Discovery & Reporting</h3>
      <p>Filter across 8+ categories (Gift Cards, Coupons, Subscriptions, Shopping, Food, Fashion, Entertainment, Travel), sort by biggest discount, and flag suspicious listings in one click.</p>
    </td>
  </tr>
</table>

---

## 🔄 Detailed User Workflows

### 1. Selling a Voucher or Gift Card
```text
[Paste GPay/PhonePe Text or Enter Details] ──▶ [Set Face Value & Asking Price (≤ ₹5,000)]
                                                         │
[Payout Released to UPI (-5% Fee)] ◀── [Buyer Pays & Unlocks Code] ◀── [Code Stored in Hidden Vault]
```
* **Mandatory Disclosures:** Sellers must declare ownership, confirm the issuer allows transferability, complete PAN/state details for tax compliance, and consent to their legal name and state appearing on the buyer's receipt.

### 2. Splitting an Official Group Plan
```text
[Host Lists Official Plan & Total Price] ──▶ [Selects 2–5 Seats & Billing Cycle]
                                                         │
[Monthly Staged Payouts to Host] ◀── [Members Join via Official Invite] ◀── [Per-Seat Cost Calculated]
```
* **Anti-Abuse Protection:** Even for **Yearly** plans, funds are held in escrow and disbursed to the host **month-by-month** as long as each member's seat remains active. If a host cancels early or removes a member, unused months are automatically refunded.

### 3. Posting a "Want to Buy" Request
* Buyers specify the desired brand/item, maximum budget (`₹`), and alert email (with explicit consent and one-click withdrawal). Matching sellers are notified immediately to fulfill the demand.

---

## 🛡️ 6-Pillar Trust & Safety Architecture

Vouchly is architected from the ground up to eliminate P2P digital fraud while complying with India's **Consumer Protection (E-Commerce) Rules, 2020**:

| Pillar | Security Mechanism | Operational Rule |
| :--- | :--- | :--- |
| **1. Verified Sellers** | **KYC & Penny-Drop** | Mandatory PAN verification and bank/UPI penny-drop check before publishing. Optional corporate or college email badges for higher trust. |
| **2. Regulated Escrow** | **RBI-Authorised Gateway** | Vouchly never holds user funds directly. Money stays in an RBI-authorised escrow account until the dispute window expires. |
| **3. Screen-Record Proof** | **Objective Dispute Evidence** | Buyers must screen-record the unlock-and-redeem process. **Valid video proof = instant refund; no proof = no refund.** |
| **4. Tiered Payout Holds** | **Reputation-Based Release** | First-time sellers face a **48-hour payout hold**. Sellers with **10+ clean trades and 0 disputes** unlock **15-minute fast payouts**. |
| **5. Automated Screening** | **Hard Caps & Bans** | Strict **₹5,000 cap** per listing. Zero tolerance for stolen codes, account logins, OTPs, Google Ads credits, or non-transferable offers. |
| **6. Grievance Redressal** | **Statutory Compliance** | Dedicated Grievance Officer acknowledges all complaints within **24 hours** and resolves cases within **15 days**. |

---

## 💰 Fees, Limits & Tax Compliance

Vouchly maintains transparent, India-compliant unit economics:

| Component | Structure / Policy |
| :--- | :--- |
| **Buyer Platform Fee** | **`₹0`** (Completely free for buyers) |
| **Seller Commission** | **`5%`** flat fee on completed sales |
| **Listing Value Cap** | **`₹5,000`** maximum per listing (Phase 1 Beta limit) |
| **E-Commerce TDS** | **`0.1%`** deducted under Section 194-O for sellers exceeding ₹5 lakh in annual gross sales |
| **GST TCS** | **`0.5%`** Tax Collected at Source where applicable, itemized clearly on payout statements |
| **Receipt Transparency** | Seller's legal name (per PAN) and state are displayed on buyer invoices per E-Commerce Rules |

### Strictly Prohibited Items
* Account usernames, passwords, or OTP-based logins
* Google Ads credits or promotional ad balances
* Expired, already-redeemed, duplicate, or stolen codes
* Vouchers explicitly marked non-transferable by the issuing brand
* Personal data or unauthorized digital goods

---

## 🗺️ Product Roadmap

- [x] **Phase 1: Beta Validation Prototype (Current)**
  - Core marketplace UI, Pay-to-Unlock flow, Group Plan calculator, Demand Board, and browser-based `localStorage` persistence.
- [ ] **Phase 2: Backend & Escrow Integration**
  - Integration with RBI-authorised payment gateway split-escrow APIs and automated UPI penny-drop / PAN KYC verification.
- [ ] **Phase 3: Automated Code Validation & Notifications**
  - Real-time coupon format validation, automated email alerts for "Want to Buy" matches, and in-app video proof upload portal.
- [ ] **Phase 4: Seller Reputation & Mobile App**
  - Public trust scores, instant 15-minute payout tier automation, and dedicated Android/iOS apps.

---

## 🚀 Getting Started (Local Development)

### Prerequisites
* Any modern web browser (Chrome, Edge, Firefox, Safari)
* Optional: [Node.js](https://nodejs.org) or VS Code Live Server for local HTTP serving

### Installation & Run
```bash
# 1. Clone this repository
git clone https://github.com.git

# 2. Move into the project directory
cd vouchly-beta

# 3. Serve locally (or double-click index.html)
npx serve .
```

---

## 📄 Policies & Legal Framework

The platform includes complete policy architectures covering:
* **Terms of Service & Seller Agreement**
* **Group Plan Terms** (Official invite enforcement & staged refund rules)
* **Refunds & Disputes Policy** (Screen-record verification standard)
* **Prohibited Items Policy**
