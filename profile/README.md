# 📸 Photogenics Desktop Application

Professional Self-Service Photobooth Software  
Integrated Payment • Cloud Delivery • Hardware Support

---

## 🚀 Overview

Photogenics is a professional desktop-based photobooth application designed to operate independently through digital payment integration.  

The system eliminates operator dependency by automating:

- Payment confirmation
- Photo session flow
- Printing process
- Softfile cloud distribution
- QR-based download access

This project follows the official Business Requirements Document (BRD).

---

## 🎯 Core Objectives

- Eliminate operator dependency via automated QRIS payment system
- Provide full internal customization control
- Allow customers to add personalized text without breaking frame aesthetics
- Deliver secure cloud-based softfile access via QR Code
- Maintain privacy through automatic file deletion

---

## 🏗️ System Architecture

Photogenics is built as a hybrid system:

Desktop Application (Windows)
+
Cloud Service (Softfile Hosting)
+
Payment Gateway Integration (QRIS)
+
Hardware Integration (Camera & Printer)

---

## 🖥️ Platform & Hardware

### Platform
- Windows Desktop Application

### Hardware Support
- Camera: Canon 1300D
- Printer: DNP RX1 / RX1HS
- Monitor: Taffware 1560MTS FHD Touchscreen

---

## 📋 Scope (Version 1 - Basic)

### Included Features

#### 📷 Capture Modes
- Photo
- Live Photo
- GIF

#### 🖼 Layout Options
- 3 Photo Horizontal Stripe
- 4 Photo Vertical Stripe
- 4 Photo Non-Stripe
- 6 Photo Non-Stripe

#### 🖌 Frame & Text
- Frame-based output only
- Custom text (name, birthday, etc.)
- Text follows frame font automatically
- No manual font selection

#### 🎨 Photo Editing
- Black & White Filter
- Vintage Filter
- Mirror / Unmirror
- Reset

#### 💳 Payment Integration
- QRIS integration (basic version)
- Merchant account provided by client
- No refund automation
- No dashboard
- No settlement reporting

#### ☁️ Cloud & QR System
- QR Code for softfile access
- Direct download link (valid for 3 days)
- QR printed on photo
- No email automation

#### 🖨 Printing
- Additional print option
- QR code printed on photo

---

## ❌ Not Included (Out of Scope)

- Admin dashboard
- Advanced printer handling
- Multi-package / bundling
- Add-on session duration
- Advanced editing tools
- Sticker editor
- Email auto-send
- Custom transition
- Music
- OS multi-device support
- Theme: "All Eyes On You"

---

## 🔄 User Flow

1. Home
2. Tutorial (Step-by-step)
3. Add-on Print Quantity
4. Voucher Input
5. Payment Confirmation
6. Payment (QRIS)
7. Layout Selection
8. Frame Selection & Confirmation
9. Capture (Preview & Retake)
10. Photo Effects (Mirror / Filter / Reset)
11. Print + QR Code Generation
12. QR Code Softfile Display
13. Download Page
14. Session Completion & Print Pickup Announcement

---

## 🔐 Non-Functional Requirements

- Original photo files auto-deleted locally after 3 days
- Windows OS locked (no minimize / folder access)
- Offline resilience:
  - If internet disconnects after payment:
    - Session continues
    - Data stored locally
    - Auto-upload when internet reconnects

---

## 🧩 Modules (Suggested Structure)

- desktop-app
- cloud-service
- payment-integration
- hardware-integration
- qr-generator
- storage-manager

---

## 🛡 Security & Privacy

- Temporary cloud storage (3-day expiration)
- Auto-deletion system
- No permanent local storage
- Secure download via QR-based direct link

---

## 📦 Versioning

Current Version: v1.0 (Basic Release Scope)

Future versions may include:
- Admin dashboard
- Advanced analytics
- Multi-device support
- Automated email delivery
- Advanced editing tools
- Cloud control panel

---

## 👥 Stakeholders

Primary:
- Customers (Photobooth Users)

Secondary:
- Business Owner

---

## 📌 Development Notes

This application is designed as a scalable product ecosystem, not just an event tool.

Long-term expansion may include:
- Multi-device orchestration
- Cloud management dashboard
- Vendor licensing system
- API integration

---

## 📄 License

Proprietary Software  
All rights reserved.

---

## 🏢 Organization

Developed under Photogenics Core System
