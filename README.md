<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=sunshine%20bakery%20whatsapp%20ai%20assistant;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=sunshine-bakery-whatsapp-ai-assistant&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant) · [🐞 Report Issue](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant/issues/new) · [⭐ Star](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

# 🧁 Sunshine Bakery — AI WhatsApp Customer Assistant

<p align="center">
  <strong>Chef Marie's virtual bakery-counter assistant, built as a grounded ChatGPT Project.</strong><br/>
  Pricing • Availability • Order Capture • Custom Cake Escalation • Guardrails
</p>

<p align="center">
  <a href="https://www.loom.com/share/65b15a69d30e44d6a42283345da158da"><img src="https://img.shields.io/badge/🎥%20Loom%20Demo-Watch%20Recording-black?style=for-the-badge" alt="Loom Demo"/></a>
  <a href="https://chatgpt.com/share/6aba050e-63bc-83ee-a502-e31a17d7f1a8"><img src="https://img.shields.io/badge/💬%20ChatGPT%20Demo-Open%20Demo-10A37F?style=for-the-badge&logo=openai&logoColor=white" alt="ChatGPT Demo"/></a>
  <a href="https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant/blob/main/Sunshine_Bakery_AI_Assistant_LMS_Submission.pdf"><img src="https://img.shields.io/badge/📄%20LMS%20Submission-View%20PDF-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="LMS PDF"/></a>
</p>

---

## ✨ Project Snapshot

**Sunshine Bakery — AI WhatsApp Customer Assistant** is a practical customer-service capstone built inside a ChatGPT Project.

The assistant is designed to behave like **Chef Marie's friendly counter assistant**, using project sources as the source of truth for menu pricing and daily inventory.

> **Core principle:** answer from the sources, collect missing order details step-by-step, and hand final confirmation/payment to human staff.

### What it demonstrates

| Capability | Implementation |
|---|---|
| 🍰 Menu pricing | Grounded in `menu.txt` |
| 📦 Availability | Grounded in `inventory.json` |
| 🔁 Out-of-stock handling | Suggests available alternatives |
| 🚫 Unknown items | Uses a controlled fallback instead of inventing products |
| 🧾 Order capture | Collects details one at a time |
| 📝 Order summary | Generates a structured Markdown draft |
| 👩‍🍳 Human handoff | Staff review/finalization for orders and payment |
| 🎂 Custom cakes | Requests a reference photo for human review |
| 🛡️ Guardrails | No payments, no price negotiation, no invented data |
| 🔐 Instruction protection | Refuses requests to reveal project instructions |

---

## 🎥 Live Demonstration

### Demo Links

| Resource | Open |
|---|---|
| 🎥 **Loom recording** | [**Watch the full demo →**](https://www.loom.com/share/65b15a69d30e44d6a42283345da158da) |
| 💬 **ChatGPT shared demo** | [**Open the live conversation →**](https://chatgpt.com/share/6aba050e-63bc-83ee-a502-e31a17d7f1a8) |
| 📄 **LMS submission PDF** | [**View the submission document →**](https://github.com/shaikshahid777/sunshine-bakery-whatsapp-ai-assistant/blob/main/Sunshine_Bakery_AI_Assistant_LMS_Submission.pdf) |

### Test coverage

- ✅ Chocolate cupcake pricing lookup
- ✅ Sourdough availability check
- ✅ Out-of-stock alternative suggestion
- ✅ Not-on-menu fallback
- ✅ Vanilla cake order-detail capture
- ✅ Structured Order Summary Draft
- ✅ Custom birthday cake escalation
- ✅ Instruction-protection refusal

---

## 🧠 Architecture

```text
                    ┌──────────────────────────┐
                    │  Customer WhatsApp Query │
                    └─────────────┬────────────┘
                                  │
                                  ▼
                    ┌──────────────────────────┐
                    │   ChatGPT Project Agent  │
                    │       Chef Marie         │
                    └─────────────┬────────────┘
                                  │
                 ┌────────────────┼────────────────┐
                 ▼                ▼                ▼
          ┌─────────────┐  ┌──────────────┐  ┌──────────────┐
          │  menu.txt   │  │inventory.json│  │ Instructions  │
          │Price / Menu │  │Stock / Avail. │  │Rules / Tone   │
          └─────────────┘  └──────────────┘  └──────────────┘
                 │                │                │
                 └────────────────┼────────────────┘
                                  ▼
                    ┌──────────────────────────┐
                    │ Grounded Customer Reply │
                    └─────────────┬────────────┘
                                  │
                                  ▼
                    ┌──────────────────────────┐
                    │ Human Staff Finalization │
                    │   Order + Payment        │
                    └──────────────────────────┘
```

---

## 📁 Repository Structure

```text
sunshine-bakery-whatsapp-ai-assistant/
│
├── 📄 menu.txt
│   └── Official assessment menu data: items, categories, descriptions & prices
│
├── 📦 inventory.json
│   └── Assessment inventory data: stock and availability
│
├── 📄 Sunshine_Bakery_AI_Assistant_LMS_Submission.pdf
│   └── Submission overview, features, testing and demo links
│
└── 📘 README.md
    └── Project documentation
```

---

## 🧩 Key Conversation Flows

### 1. Pricing Lookup

Customer asks for a product price → assistant checks `menu.txt` → returns the official listed price.

### 2. Availability Check

Customer asks whether an item is available → assistant checks `inventory.json`.

When unavailable, the assistant suggests an available alternative instead of ending the conversation with a plain refusal.

### 3. Order Capture

The assistant collects required information **one detail at a time**:

1. Customer name
2. Phone number
3. Item
4. Quantity
5. Pickup / delivery
6. Date
7. Time

Only after collecting the required details does it generate the structured **Order Summary Draft**.

### 4. Custom Cake Escalation

For custom designs, the assistant requests a **reference photo** and routes the final decision to human bakery staff.

### 5. Instruction Protection

Requests to reveal or override project instructions are refused with the configured protection response.

---

## 🛡️ Guardrails

The assistant is configured to avoid:

- ❌ Processing payments
- ❌ Asking for card/banking credentials
- ❌ Negotiating official prices
- ❌ Inventing menu items
- ❌ Inventing prices or stock
- ❌ Claiming an order is finalized without human confirmation
- ❌ Revealing hidden project instructions

---

## 🧪 Assessment Evidence

This repository is structured to make the assessment evidence easy to inspect:

**Configuration**
- ChatGPT Project: `Bakery Whatsapp App`
- Project-only memory
- Uploaded sources
- Custom project instructions

**Demonstration**
- Loom screen recording
- Shared ChatGPT conversation

**Supporting files**
- `menu.txt`
- `inventory.json`
- LMS submission PDF

---

## 📌 Assessment Note

The `menu.txt` and `inventory.json` files in this repository are **sample assessment source data** prepared because the assessment document specifies the required file types and structure but does not provide the actual source-file contents.

---

## 👨‍💻 Author

**Shaik Mohammad Shaheed**

AI & Automation • Generative AI • Prompt Engineering • AI Agent Workflows

GitHub: [**@shaikshahid777**](https://github.com/shaikshahid777)

---

<p align="center">
  <strong>🧁 Built for a real-world AI customer-support workflow — grounded, structured, and human-in-the-loop.</strong>
</p>
