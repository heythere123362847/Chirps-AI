<p align="center">
  <img src="https://i.ibb.co/pvDMQfmv/android-chrome-192x192.png" alt="Chirps AI" width="80" />
</p>

<h1 align="center">Chirps AI</h1>

<p align="center">
  <strong>The AI Sales Agent That Lives on Your Website</strong><br />
  Voice calls · Live search · Generative UI · One line of code
</p>

<p align="center">
  <a href="https://chirps.cc">Website</a> ·
  <a href="https://chirps.cc/how-it-works">How It Works</a> ·
  <a href="https://chirps.cc/pricing">Pricing</a> ·
  <a href="https://chirps.cc/support">Support</a> ·
  <a href="https://chirps.cc/dashboard">Dashboard</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-Proprietary-red" alt="License" />
</p>

---

## What is Chirps AI?

Chirps AI is an embeddable AI sales agent that turns your website visitors into customers — completely on autopilot.

It learns your business by crawling your website, then engages every visitor 24/7 with intelligent text chat, **real-time AI voice calls** directly in the browser, **live website search** during conversations, and **interactive UI components** (forms, product cards, booking calendars) generated inside the chat widget.

One line of code. 60-second setup. Works on any website.

```html
<script src="https://chirps.cc/widget.js" data-id="your-assistant-id"></script>
```

---

## Table of Contents

- [Features](#features)
  - [AI Chat](#-ai-chat)
  - [Voice Calling](#-voice-calling)
  - [Live Website Search](#-live-website-search)
  - [AI Artifacts (Generative UI)](#-ai-artifacts-generative-ui)
  - [Artifacts Studio (No-Code Builder)](#-artifacts-studio-no-code-builder)
  - [Knowledge Engine](#-knowledge-engine)
  - [Agent Takeover](#-agent-takeover)
  - [Lead Capture](#-lead-capture)
  - [Custom Branding](#-custom-branding)
  - [Domain Security](#-domain-security)
  - [Geolocation Tracking](#-geolocation-tracking)
  - [Affiliate Program](#-affiliate-program)
- [Dashboard](#dashboard)
  - [Overview](#overview)
  - [Assistants](#assistants)
  - [Conversations](#conversations)
  - [Leads](#leads)
  - [Billing](#billing)
  - [Affiliate](#affiliate)
  - [Settings](#settings)
- [Integrations](#integrations)
  - [E-Commerce & CMS](#e-commerce--cms)
  - [AI Coding Tools](#ai-coding-tools-vibe-coding)
- [How It Works](#how-it-works)
- [Pricing](#pricing)
- [Widget](#widget)
- [Contributing](#contributing)
- [Links](#links)

---

## Features

### 💬 AI Chat

Every assistant is powered by advanced large language models with retrieval-augmented generation (RAG). The AI doesn't hallucinate — it only answers based on your business data.

- **Multi-turn conversations** with smart context windowing (up to 50 messages of history)
- **File attachments** — customers can upload images (PNG, JPG, WEBP) for visual analysis, or documents (PDF, DOCX, TXT, Markdown) for reference
- **Function calling** — the AI can trigger real-time actions during conversations (search your site, display products, show forms)
- **Artifact tags** — AI responses can contain interactive UI components rendered inline
- **Context-aware** — the AI remembers the full conversation and picks up where it left off
- **Streaming-ready** — responses are generated and delivered in real-time

### 🎙️ Voice Calling

Real-time AI voice calls directly in the browser. No phone number needed. No app download.

- **Full-duplex audio** — natural, conversational back-and-forth with interruption handling (barge-in)
- **Multiple voice personas** — choose from different AI voices to match your brand personality
- **Chat context handoff** — voice calls automatically receive the text conversation history, so the AI picks up where the text left off
- **Tool calling in voice** — the AI can search your site, show product cards, display forms, and open booking calendars during a live voice call
- **Automatic transcription** — all voice conversations are transcribed and logged
- **Web Audio API visualizer** — real-time audio visualization in the widget during calls
- **Mute/unmute controls** and call timer

### 🔍 Live Website Search

Unlike traditional chatbots that only know what they were trained on, Chirps AI can **browse your website in real-time** during a conversation.

- **Domain-scoped** — the AI only searches YOUR website, never competitors
- **Always current** — finds products, pages, and content you added seconds ago
- **Verified URLs** — the AI returns real, clickable links from your actual site
- **No hallucination** — if a product or page doesn't exist on your site, the AI won't invent it
- **Price verification** — extracts live pricing from your product pages
- **Automatic card generation** — when products are found, the AI can automatically display them as interactive product cards with "Buy Now" buttons

### 🧩 AI Artifacts (Generative UI)

Artifacts are interactive UI components that the AI generates **inside the chat window** during conversations. Instead of sending customers to external forms or pages, everything happens in-chat.

| Artifact Type | What It Does |
|---|---|
| **Lead Capture Form** | Collects name, email, phone, and custom fields. Fully customizable. Data goes to your Leads dashboard. |
| **Booking Calendar** | Displays available time slots. Customer books a meeting without leaving the chat. |
| **Product Cards** | Shows product image, title, price, description, and a CTA button with a direct link. Supports single cards and multi-card sliders. |
| **CSAT Survey** | Customer satisfaction rating survey, triggered after issue resolution. |
| **Custom Artifacts** | Build any UI component using the no-code Artifacts Studio. Schema-driven rendering. |

**Why this matters:** Traditional chatbots say *"Click here to fill out our contact form"* and send users to a new page. Chirps shows the form **inside the chat**. Zero friction = higher conversion.

### 🎨 Artifacts Studio (No-Code Builder)

Build custom interactive artifacts without writing a single line of code.

**What you can create:**
- Custom lead qualification surveys
- Pricing calculators
- Product comparison tables
- Feedback forms
- Appointment scheduling widgets
- Order tracking interfaces
- Any schema-driven UI component

**How it works:**
1. Open Artifacts Studio in your dashboard
2. Design your component (fields, labels, types, submit button)
3. Define trigger rules (e.g., "Show when user asks about pricing")
4. Save — the AI immediately starts using it in live conversations

**For developers:** Custom Artifacts support a `chirps:artifact` window event, allowing advanced users to build fully custom React/HTML components that integrate with the chat widget.

### 🧠 Knowledge Engine

Teach your AI everything about your business using three methods:

#### Website Crawling
- Paste your website URL → Chirps crawls and extracts text, navigation, products, FAQs, and metadata
- Configurable crawl depth and max pages per plan
- **Re-crawl** with one click when your site content changes
- Extracts structured product data: name, price, URL, image, and currency

#### Document Upload
Upload files directly to your assistant's knowledge base:
- **PDF** — product catalogs, manuals, whitepapers
- **DOCX** — Word documents, SOPs, proposals
- **TXT / Markdown** — plain-text knowledge bases, internal docs

Documents are chunked into optimized segments using sentence-boundary splitting and stored as vector embeddings for semantic retrieval.

#### Auto-Learning (Harvest)
The AI learns from successful conversations automatically. As you interact with customers, Chirps identifies useful patterns and adds them to its knowledge — making it smarter every day without manual effort.

### 👤 Agent Takeover

Seamlessly switch between AI and human in any conversation.

- **Monitor live conversations** in real-time from the dashboard
- **Take over from the AI** at any point for complex situations
- **Hand back to AI** when done — the AI continues with full context
- **Per-conversation toggle** — agent mode is set per conversation, not globally
- When a human agent is active, the AI stops responding automatically

### 📋 Lead Capture

Every lead captured through chat artifacts is stored and accessible:

- Full contact details (name, email, phone, custom fields)
- Linked to the originating conversation
- Timestamped with conversation history
- Exportable from the dashboard
- Country/geolocation data attached

### 🎨 Custom Branding

Make the widget look like your own product:

- **Brand colors** — primary color applied to buttons, links, and UI accents
- **AI Avatar** — upload a custom photo or logo
- **Welcome message** — the first message customers see
- **Widget placement** — bottom-right or bottom-left
- **Business name and description** shown in the widget header
- **Custom voice persona** — select from available AI voices

### 🔒 Domain Security

Every assistant is domain-locked to prevent unauthorized use:

- Widget validates the `Origin` header against your configured `business_url`
- Prevents other websites from embedding your assistant and using your message quota
- `localhost` is always allowed for development/testing
- Unauthorized requests return `403 Forbidden`

### 🌍 Geolocation Tracking

Automatically captures visitor location from IP addresses:

- Country code detection for every conversation
- Stored alongside conversation metadata
- Useful for understanding your audience's geographic distribution

### 🤝 Affiliate Program

Built-in referral system with dashboard tracking:

- Generate unique referral links
- Track clicks, signups, and conversions
- Commission-based payouts
- Full affiliate dashboard with analytics

---

## Dashboard

The Chirps dashboard is your command center for managing all aspects of your AI assistants.

### Overview

The main dashboard page shows:
- Total conversations, messages, and leads at a glance
- Usage against your plan limits (messages used vs. total available)
- Quick links to create new assistants or view recent conversations
- Plan status and upgrade prompts

### Assistants

Create and manage your AI assistants. Each assistant is independent with its own:

- **Name, role, and personality** — e.g., "Emma — Sales Specialist"
- **System prompt** — detailed instructions on how the AI should behave
- **Business URL** — the website the AI represents (used for live search and domain lock)
- **Knowledge base** — crawled pages, uploaded documents, and harvested data
- **Widget configuration** — colors, avatar, placement, welcome message, voice settings
- **Artifacts configuration** — enable/disable specific artifact types, customize trigger rules, field labels, CTA text
- **Active/inactive toggle** — pause an assistant without deleting it

**Assistant editing is organized into tabs:**
- **Setup** — name, role, personality, system prompt
- **Knowledge** — URL crawling, document upload, knowledge blocks, re-crawl
- **Design** — widget colors, avatar, branding, placement
- **Embed** — copy your embed code snippet
- **Artifacts** — configure forms, booking, cards, CSAT, and custom artifacts

### Conversations

View and manage all customer conversations across your assistants:

- **Real-time conversation feed** — see messages as they arrive
- **Full transcript** — complete text and voice call history
- **Agent takeover controls** — toggle between AI and human agent
- **Conversation metadata** — session ID, IP address, country, timestamps
- **Filter by assistant** — view conversations for a specific assistant

### Leads

All leads captured through AI artifacts in one place:

- Name, email, phone, and custom fields
- Linked to the originating conversation and assistant
- Timestamps and geolocation data
- Search and filter capabilities
- Export options

### Billing

Manage your subscription directly from the dashboard:

- View current plan and usage
- Upgrade or downgrade plans
- Manage payment methods
- View invoices and billing history
- Promotion codes supported at checkout

### Affiliate

Track your referral performance:

- Unique referral link generation
- Click tracking
- Signup and conversion metrics
- Commission tracking
- Payout history

### Settings

Account-level settings:

- Profile management
- Email and password
- Account preferences

---

## Integrations

Chirps AI works on any website, but we have dedicated step-by-step guides for 20 platforms.

### E-Commerce & CMS

| Platform | Integration Method |
|---|---|
| **Shopify** | Paste the script in Theme Settings → Custom Code |
| **WordPress** | Use a plugin like "Header & Footer Scripts" or paste in `header.php` |
| **WooCommerce** | Same as WordPress — embed script in theme or via plugin |
| **Webflow** | Add to Project Settings → Custom Code → Footer |
| **Wix** | Marketing Tools → Custom Code → Add to Body |
| **Squarespace** | Settings → Advanced → Code Injection → Footer |
| **Framer** | Site Settings → Custom Code → End of Body |

### AI Coding Tools ("Vibe Coding")

If you built your app with an AI coding tool, adding Chirps takes under 60 seconds:

| Tool | How to Add |
|---|---|
| **Lovable** | Prompt: *"Add this script tag to the layout"* |
| **Cursor** | Add the script tag to your `index.html` or layout component |
| **Claude Code** | Ask Claude to add the embed snippet to your HTML |
| **Windsurf** | Add via the IDE's file editor to your layout |
| **v0 by Vercel** | Add the script tag to your generated component |
| **Bolt.new** | Paste in the HTML template |
| **Replit** | Add to your `index.html` |
| **Antigravity** | Add to your project's layout file |
| **Base44** | Add to your app's HTML template |
| **Emergent** | Add to your project's HTML |
| **GitHub Copilot** | Ask Copilot to add the embed snippet |
| **VS Code** | Manually add to your HTML/layout file |
| **Xcode** | Add to your web view's HTML content |

Each platform has a **dedicated integration page** at `chirps.cc/integrations/[platform]` with screenshots and step-by-step instructions.

---

## How It Works

### 1. Create an Assistant
Give it a name, role, and personality instructions. Define how it should talk and what it should focus on.

### 2. Train on Your Business
- **Paste your website URL** — Chirps crawls your site and learns your products, pricing, FAQs, and policies
- **Upload documents** — Add internal PDFs, guides, or spreadsheets that aren't publicly available
- **Auto-learn** — The AI gets smarter from every conversation

### 3. Customize the Design
Match your brand colors, upload an avatar, write a welcome message, and configure which features are enabled (voice, forms, booking, etc.)

### 4. Embed on Your Website
Copy your unique embed code — one `<script>` tag — and paste it into your site.

```html
<script src="https://chirps.cc/widget.js" data-id="your-assistant-id"></script>
```

### 5. Go Live
Your AI assistant now engages every visitor, 24 hours a day, 7 days a week. Monitor conversations, capture leads, and take over when needed — all from the dashboard.

---

## Pricing

| Feature | Free | Starter ($19/mo) | Pro ($49/mo) | Enterprise ($129/mo) |
|---|---|---|---|---|
| AI Assistants | 1 | 10 | 50 | Unlimited |
| AI Messages/month | 50 | 2,000 | 10,000 | 100,000 |
| Training sessions | 1 | 10 | 50 | Unlimited |
| Re-crawls | 1 | 10 | 50 | Unlimited |
| Knowledge Harvest | 1 | 10 | 50 | Unlimited |
| Max pages per crawl | 5 | 10 | 25 | Unlimited |
| Max crawl depth | 2 | 5 | 10 | Unlimited |
| Custom Branding | ❌ | ✅ | ✅ | ✅ |
| File Upload | ❌ | ✅ | ✅ | ✅ |
| Voice Calling | ✅ | ✅ | ✅ | ✅ |
| Conversations & Agent Takeover | ✅ | ✅ | ✅ | ✅ |
| AI Artifacts | ✅ | ✅ | ✅ | ✅ |
| Custom Artifacts Studio | ❌ | ✅ | ✅ | ✅ |

**Custom plans** available for enterprises requiring custom AI models, dedicated infrastructure, SLA guarantees, SSO/SAML, white-label options, or on-premise deployment. [Contact us →](https://chirps.cc/support)



---

## Widget

The Chirps widget (`widget.js`) is a self-contained, framework-agnostic JavaScript bundle that can be embedded on any website.

### Features
- **Shadow DOM isolation** — widget CSS never conflicts with host site styles
- **Async loading** — loads after the page is visible, zero performance impact on the host site
- **Full chat UI** — message bubbles, typing indicators, file attachment button, emoji support
- **Voice call interface** — call button, real-time audio visualizer, mute/unmute, call timer
- **Artifact rendering** — parses `{{ARTIFACT: {...}}}` tags and renders interactive forms, cards, booking calendars, and surveys inline
- **Multi-card slider** — product cards are displayed in a swipeable carousel when multiple results are found
- **Custom event system** — dispatches `chirps:artifact` window events for custom artifact integration
- **Responsive design** — works on desktop and mobile
- **Configurable placement** — bottom-right or bottom-left

### Embed Code

```html
<script src="https://chirps.cc/widget.js" data-id="your-assistant-id"></script>
```

That's it. One line. No npm packages, no API keys in your codebase, no build step.

### Advanced: Custom Artifact Events

Listen for artifact submissions from the widget:

```javascript
window.addEventListener('chirps:artifact', (event) => {
  const { type, data } = event.detail;
  console.log('Artifact submitted:', type, data);
  // Handle form submissions, booking confirmations, etc.
});
```

---

---

## Contributing

Chirps AI is developed by [Monzed](https://monzed.com). We are not currently accepting outside contributions, but we welcome feedback and feature requests.

- **Bug reports:** [chirps.cc/support](https://chirps.cc/support)
- **Feature requests:** [chirps.cc/support](https://chirps.cc/support)
- **Email:** team@monzed.com

---

## Links

| Resource | URL |
|---|---|
| Website | [chirps.cc](https://chirps.cc) |
| Dashboard | [chirps.cc/dashboard](https://chirps.cc/dashboard) |
| How It Works | [chirps.cc/how-it-works](https://chirps.cc/how-it-works) |
| Pricing | [chirps.cc/pricing](https://chirps.cc/pricing) |
| Support | [chirps.cc/support](https://chirps.cc/support) |
| Company | [monzed.com](https://monzed.com) |
| Twitter/X | [@monzedlabs](https://x.com/monzedlabs) |
| LinkedIn | [Monzed](https://www.linkedin.com/company/monzed/) |
| GitHub | [Monzed-Labs](https://github.com/Monzed-Labs) |
| YouTube | [Monzed](https://www.youtube.com/channel/UCF6G1KTT-tfnGJaRMsvBNQg) |
| Instagram | [@monzedlabs](https://www.instagram.com/monzedlabs/) |

---

<p align="center">
  <strong>Built with conviction by <a href="https://monzed.com">Monzed</a></strong><br />
  Estonia, EU 🇪🇪
</p>
