# 🚀 Vendor AI Onboarding System (n8n & Supabase)

## 📌 Roadmap & Progress Checklist

### 🟢 Phase 1: Trigger & First Contact
- [x] Integrate **Supabase Trigger / Webhook** to start onboarding upon C-level approval.
- [x] Send automated welcome message via **WhatsApp API**.
- [x] Send automated onboarding welcome email via **Gmail API**.
- [x] Log contact status and timestamps in **Supabase**.

---

### 🟡 Phase 2: Documents Collection & Auto-Reminders
- [ ] Set up **Webhook** to receive vendor documents (License, Tax ID, Bank Details) via WhatsApp/Email.
- [ ] Store received documents in **Supabase Storage**.
- [ ] Implement **Auto-Reminder Loop (x2)** if documents are missing or ignored.

---

### 🔵 Phase 3: Catalog & Terms Setup
- [ ] Send automated link/form to collect product catalog and pricing requirements.
- [ ] Save catalog details to **Supabase** profile.
- [ ] Capture vendor terms agreement (`terms_accepted = true`).

---

### 🔴 Phase 4: C-Level Review & Decision (Human Judgment)
- [ ] Generate AI summary report of complete vendor profile for C-Level review.
- [ ] Handle **C-Level Approval**:
  - [ ] `IF APPROVED`: Activate vendor profile & send confirmation via WhatsApp/Email.
  - [ ] `IF DECLINED`: Close submission & send thank you/decline email.

---
