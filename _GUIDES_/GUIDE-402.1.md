```text
═══════════════════════════════════════════════════════════════════════════════
# 📋 GUIDE-402.1 — How to Setup Your #PersonalBrand DOMAIN on Proton Mail
═══════════════════════════════════════════════════════════════════════════════
## ♾️ WeOwnNet 🌐 — FedArch Guide ● INT‑B001
## 🏆 #GoldStandard — v4.29.1-r1 ✅
## 🛡️ Part of the #BrandBuildOutMonth series — W29
## 🔒 TARGET AUDIENCE: @LFG ♍️ · @GID · Volcarian community · All CCC operators building personal brands
═══════════════════════════════════════════════════════════════════════════════

| Field | Value |
|:------|:-------|
| **Document** | GUIDE-402.1 |
| **Version** | **v4.29.1-r1** ✅ |
| **Folder** | `_GUIDES_/` 📋 |
| **Category** | 📋 GUIDE — Personal Brand Infrastructure |
| **Lifecycle Stage** | 🟢 **LIVE** — Ready for @GTM:ADMIN review + GH push |
| **Season** | #WeOwnSeason004 🚀 |
| **Author** | AI:@GTM 🎯 @ INT‑B001:CCC (WeOwnChat — DeepSeek V4 Flash) |
| **CCC-ID** | GTM_2026-W29_6009 |
| **#masterCCC** | GUIDE-402.1 |
| **Template Source** | TMPL-401 v4.2.2.1-r2 (#GoldStandard) |
| **Status** | 🟢 **DRAFT — Ready for review** |
```

---

## 📋 TABLE OF CONTENTS

| § | Title |
|:-:|:------|
| [§1](#1--why-personal-brand-email) | 🎯 Why Personal Brand Email? |
| [§2](#2--prerequisites) | 📋 Prerequisites |
| [§3](#3--step-1--buy-your-domain) | 🛒 Step 1 — Buy Your Domain |
| [§4](#4--step-2--sign-up-for-proton-mail) | 📧 Step 2 — Sign Up for Proton Mail |
| [§5](#5--step-3--connect-your-domain) | 🔗 Step 3 — Connect Your Domain in Proton |
| [§6](#6--step-4--configure-dns-records) | 🌐 Step 4 — Configure DNS Records (Cloudflare) |
| [§7](#7--step-5--verify--activate) | ✅ Step 5 — Verify & Activate |
| [§8](#8--step-6--create-aliases--addresses) | 📨 Step 6 — Create Aliases & Addresses |
| [§9](#9--step-7--send-your-first-email) | 🚀 Step 7 — Send Your First Email |
| [§10](#10--pro-tips--best-practices) | 🧠 Pro Tips & Best Practices |
| [§11](#11--troubleshooting) | 🔧 Troubleshooting |
| [§12](#12--bp-075-footer) | 📋 BP-075 Footer |

---

## §1. 🎯 Why Personal Brand Email?

Your email address is the foundation of your digital identity. A personal brand domain turns:

```
you@gmail.com          →   you@yourname.com
lfgbrand@gmail.com     →   lfg@volcarian.xyz
gidmakes@gmail.com     →   hello@gid.space
```

### What changes

| Before (Free Email) | After (Personal Domain) |
|:---------------------|:------------------------|
| You're renting your address | **You own your address** — take it anywhere |
| Gmail/Outlook owns your brand | **You own your brand** — the domain is yours |
| Hard to switch providers | **Easy to switch** — just update DNS |
| Looks like a hobby | **Looks like a professional** — instantly credible |
| Mixed personal/professional | **Separate identities** — clear boundaries |

### Why Proton Mail specifically

| Feature | Benefit |
|:--------|:--------|
| **End-to-end encryption** | Your emails are private by default |
| **Zero-access architecture** | Proton cannot read your emails |
| **Swiss privacy laws** | Strongest data protection in the world |
| **Custom domain support** | All paid plans allow custom domains |
| **ProtonVPN + Drive + Calendar** | Whole ecosystem under one login |
| **Open-source** | Code is auditable |

---

## §2. 📋 Prerequisites

Before starting, make sure you have:

| # | Item | Details | Where to Get |
|:-:|:-----|:--------|:-------------|
| 1 | **A domain name** | `yourname.com`, `yourbrand.xyz`, etc. | Cloudflare Registrar, Namecheap, Porkbun, etc. |
| 2 | **Cloudflare account** | For DNS management (recommended) | [dash.cloudflare.com](https://dash.cloudflare.com) — Free |
| 3 | **Proton Mail account** | Paid plan (Mail Plus or higher) | [proton.me/mail](https://proton.me/mail) — Starts at €3.99/mo |
| 4 | **DNS knowledge (basic)** | MX, TXT, CNAME records | This guide covers everything |
| 5 | **~30 minutes** | First-time setup time | Grab a coffee ☕ |

> **💡 Tip:** If you're part of the ♾️ WeOwnNet 🌐 ecosystem, the Cloudflare account is already ready. Just add your domain to the ecosystem Cloudflare account or use your own.

---

## §3. 🛒 Step 1 — Buy Your Domain

### Option A: Cloudflare Registrar (Recommended)

Cloudflare sells domains **at cost** — no markup. Best price + easiest integration with Cloudflare DNS.

| Domain Extension | Typical Cost (Annual) |
|:-----------------|:---------------------|
| `.com` | ~$9.15 |
| `.xyz` | ~$3.50 |
| `.io` | ~$35.00 |
| `.co` | ~$10.50 |
| `.me` | ~$13.00 |

**Steps:**

1. Go to [dash.cloudflare.com](https://dash.cloudflare.com) → **Register Domains**
2. Search for your name/brand
3. Add to cart → Complete purchase
4. Cloudflare automatically sets up DNS — no extra config needed

### Option B: Any Other Registrar

| Registrar | Price Range | Notes |
|:----------|:------------|:------|
| Namecheap | $5–$15/yr | Good for beginners |
| Porkbun | $4–$12/yr | No-nonsense, cheap |
| Google Domains (now Squarespace) | $10–$15/yr | Familiar interface |

> **⚠️ Important:** If you buy elsewhere, you'll need to point the domain's nameservers to Cloudflare (free) for best DNS management. Guide for that is in §6.

### Naming Your Domain

| Your Name | Good Options |
|:----------|:-------------|
| @LFG ♍️ | `lfg.xyz`, `thelfg.com`, `lfgbrand.co` |
| @GID | `gid.space`, `hellogid.com`, `gidmakes.co` |
| Volcarian | `volcarian.xyz`, `volcarian.co`, `volcarian.space` |

> **💡 Tip:** Keep it short. Keep it memorable. `.com` is still king, but `.xyz` and `.co` are excellent alternatives.

---

## §4. 📧 Step 2 — Sign Up for Proton Mail

### Choose Your Plan

| Plan | Price | Custom Domains | Storage | Best For |
|:-----|:------|:--------------:|:-------:|:---------|
| **Mail Plus** | €3.99/mo | **1 domain** | 15 GB | Single personal brand — great starting point |
| **Proton Unlimited** | €9.99/mo | **3 domains** | 500 GB | Multiple brands + VPN + Drive + Calendar |
| **Business** | €6.99/user/mo | **3+ domains** | 15 GB/user | Teams and cooperatives |

> **💡 For most personal brands:** Mail Plus (€3.99/mo) is plenty. One domain, 15 GB, custom email — all you need.

### Sign Up Steps

1. Go to [proton.me/mail](https://proton.me/mail) → **Sign Up**
2. Choose **Mail Plus** (or your preferred plan)
3. Create your Proton username: `@lfg`, `@gidmakes`, etc.
4. Set a strong password (use a password manager!)
5. Verify your recovery email or phone number
6. Complete payment

> **💡 Tip:** Your Proton username becomes `you@proton.me` — this is your fallback address. The custom domain address (`you@yourname.com`) will be your primary.

---

## §5. 🔗 Step 3 — Connect Your Domain in Proton

Now that Proton knows who you are, tell it about your domain.

1. **Log in** to [mail.proton.me](https://mail.proton.me)
2. Click **Settings** (gear icon ⚙️) → **Go to Settings**
3. Navigate to **Proton Mail** → **Identity & Addresses**
4. Click **➕ Add domain**
5. Enter your domain: `yourname.com` (or `volcarian.xyz`, etc.)
6. Click **Next**

Proton will show you a screen with **DNS records** — **DO NOT CLOSE THIS TAB.** You'll need these values for Step 4.

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  📋 Domain Verification — DO NOT CLOSE THIS TAB                 │
│                                                                 │
│  Domain: yourname.com                                           │
│                                                                 │
│  ┌──────────────────────────────────────────────────────────┐   │
│  │ These 4 records need to be added to your DNS provider:   │   │
│  │                                                          │   │
│  │ 1. MX Record  →  mail.protonmail.ch                     │   │
│  │ 2. TXT (SPF)  →  v=spf1 include:_spf.protonmail.ch ~all  │   │
│  │ 3. TXT (DKIM) →  [unique key]                           │   │
│  │ 4. CNAME      →  protonmail._domainkey.yourname.com      │   │
│  └──────────────────────────────────────────────────────────┘   │
│                                                                 │
│  Click "Next" AFTER records are added and verified.             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## §6. 🌐 Step 4 — Configure DNS Records (Cloudflare)

This is the most technical step — but follow it exactly and you'll be fine.

### If Your Domain Is Already on Cloudflare

1. **Log in** to [dash.cloudflare.com](https://dash.cloudflare.com)
2. Select your domain
3. Go to **DNS** → **Records**

### Add the 4 Records

Go back to the Proton tab (the one you didn't close, right?) and add these records one by one:

#### Record 1 — MX (Mail Exchange)

| Field | Value |
|:------|:-------|
| **Type** | MX |
| **Name** | `@` (or leave blank — represents root domain) |
| **Mail server** | `mail.protonmail.ch` |
| **Priority** | `10` |
| **TTL** | `Auto` |

#### Record 2 — SPF (Sender Policy Framework)

| Field | Value |
|:------|:-------|
| **Type** | TXT |
| **Name** | `@` |
| **Value** | `v=spf1 include:_spf.protonmail.ch ~all` |
| **TTL** | `Auto` |

> **⚠️ Important:** If you already have an SPF record (e.g., from another email service), **merge** them — don't have two SPF records. Proton's support docs explain how.

#### Record 3 — DKIM (DomainKeys Identified Mail)

| Field | Value |
|:------|:-------|
| **Type** | TXT |
| **Name** | `protonmail._domainkey` (or the value Proton provides) |
| **Value** | Paste the **long DKIM key** from Proton's setup page |
| **TTL** | `Auto` |

#### Record 4 — CNAME (Optional but Recommended)

| Field | Value |
|:------|:-------|
| **Type** | CNAME |
| **Name** | `protonmail._domainkey` (if not already added as TXT) |
| **Target** | `protonmail.domainkey.<UID>.proton.me` (get exact from Proton) |
| **TTL** | `Auto` |

### Your Cloudflare DNS Records Tab Should Look Like This

```
┌──────────┬─────────────────────────────────┬──────────────────────────┐
│   Type   │            Name                 │         Value            │
├──────────┼─────────────────────────────────┼──────────────────────────┤
│ MX       │ @                               │ mail.protonmail.ch       │
│ TXT      │ @                               │ v=spf1 include:_spf...   │
│ TXT      │ protonmail._domainkey           │ [long DKIM hash]         │
│ CNAME    │ protonmail._domainkey           │ [proton target domain]   │
└──────────┴─────────────────────────────────┴──────────────────────────┘
```

### Enable Proxy (Optional)

Cloudflare has a proxy (orange cloud ☁️) vs DNS-only (gray cloud). For email records:

| Record Type | Proxy Setting |
|:------------|:--------------|
| **MX** | 🟤 **DNS only** (gray cloud) — Email cannot be proxied |
| **TXT** | 🟤 **DNS only** (gray cloud) — TXT records cannot be proxied |
| **CNAME** | 🟤 **DNS only** (gray cloud) — Email verification cannot be proxied |

---

## §7. ✅ Step 5 — Verify & Activate

1. Go **back to the Proton Mail tab** you kept open
2. Click **"Verify"** or **"Next"**

Proton will check your DNS records. This can take:
- **Cloudflare domains:** Usually instant (1–2 minutes)
- **Other DNS providers:** Up to 24 hours (usually 5–15 minutes)

### If Verification Passes ✅

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  ✅ Domain verified!                                            │
│                                                                 │
│  yourname.com is now connected to Proton Mail.                  │
│                                                                 │
│  Next: Create your first email address                         │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### If Verification Fails ❌

| Error | Likely Cause | Fix |
|:------|:-------------|:-----|
| "MX record not found" | MX record missing or wrong | Double-check `mail.protonmail.ch` is exact |
| "SPF record not found" | TXT record missing | Verify the SPF value is exactly `v=spf1 include:_spf.protonmail.ch ~all` |
| "DKIM not found" | DKIM TXT record missing | Copy the EXACT key from Proton — it's long |
| "Records still propagating" | DNS hasn't updated | Wait 5–15 min. Cloudflare is fast. Other DNS may take longer. |

> **💡 Tip:** Cloudflare records update almost instantly. If verification fails, double-check the values — typos are the #1 cause.

---

## §8. 📨 Step 6 — Create Aliases & Addresses

Your domain is verified. Now create the email addresses you'll actually use.

### Create Your Primary Address

1. In Proton Mail → **Settings** → **Identity & Addresses**
2. Under your domain, click **➕ Add address**
3. Choose your username: `hello`, `me`, `hi`, your first name, etc.
4. Click **Save**

### Address Ideas for Personal Brand

| Purpose | Address |
|:--------|:--------|
| **General contact** | `hello@yourname.com` |
| **Professional** | `hi@yourname.com` |
| **Business** | `me@yourname.com` |
| **Work** | `work@yourname.com` |
| **Newsletter** | `news@yourname.com` |
| **Support** | `support@yourname.com` |

### Address Ideas for @LFG ♍️

| Purpose | Address |
|:--------|:--------|
| General | `lfg@volcarian.xyz` |
| Collabs | `collab@lfg.xyz` |
| FlowsBros | `flowsbros@lfg.xyz` |

### Address Ideas for @GID

| Purpose | Address |
|:--------|:--------|
| General | `hello@gid.space` |
| Projects | `build@gid.space` |
| Creative | `studio@gid.space` |

### Proton Mail Aliases (Catch-All)

Proton Mail supports **catch-all** addresses — any email sent to `*@yourname.com` lands in your inbox. Enable this in Settings → Identity & Addresses → your domain → **Catch-all**.

> **⚠️ Warning:** Catch-all is convenient but you'll get more spam. Use with caution.

---

## §9. 🚀 Step 7 — Send Your First Email

### Test Your Setup

1. Open Proton Mail
2. Click **New Message**
3. Send an email to **yourself** at your old address (e.g., `lfg@gmail.com`)
4. Check that it arrives in your Gmail inbox
5. **Reply** from Gmail to your new `hello@yourname.com`
6. Check that the reply arrives in Proton

### What to Check

| Check | Expected | If Wrong |
|:------|:---------|:---------|
| Email sends from `hello@yourname.com` | ✅ Shows your domain | Check default address in settings |
| Email arrives in recipient's inbox | ✅ Not spam | Check SPF/DKIM records |
| Reply arrives in Proton | ✅ In inbox | Check MX record |
| Email headers show DKIM pass | ✅ Signed by Proton | DKIM record may be wrong |

### Bonus: Set Up Proton Mail on Your Phone

| Platform | App |
|:---------|:-----|
| **iOS** | Proton Mail — App Store |
| **Android** | Proton Mail — Google Play |
| **Desktop** | Proton Mail Bridge (for Outlook/Thunderbird) |

Proton Mail Bridge costs extra (included in Unlimited, add-on for Mail Plus). The web app and mobile app are included in all plans.

---

## §10. 🧠 Pro Tips & Best Practices

### Security

| Tip | Why |
|:----|:-----|
| Enable **2FA** on your Proton account | Your email is the key to everything |
| Use a **unique, strong password** | Password manager recommended |
| Set up **recovery options** | So you don't get locked out |
| **Never share** your Proton login | Your domain email is your identity |

### Branding

| Tip | Why |
|:----|:-----|
| Use your domain email **everywhere** | Resume, LinkedIn, GitHub, business cards |
| Set up a **professional signature** | Name, title, domain, links |
| Create a **simple landing page** | `yourname.com` can also have a website |
| Add your domain email to **GitHub profile** | Public email in your profile README |
| **Be consistent** | Same address across all platforms |

### Migration

| If you're coming from... | Steps |
|:-------------------------|:------|
| Gmail | Use Proton's **Easy Switch** — imports emails and contacts automatically |
| Outlook | Export to .pst, use **Proton Import Assistant** |
| iCloud | Export to .mbox, use **Proton Import Assistant** |
| Another custom domain | Update MX records, keep old provider for 30 days overlap |

### Cost Optimization

| Strategy | Savings |
|:---------|:--------|
| Proton Mail Plus (€3.99/mo) + Cloudflare Registrar ($9.15/yr domain) | **~$60/year** — complete personal brand email |
| Pay annually (not monthly) | **~20% discount** |
| Proton Unlimited (€9.99/mo) | Includes VPN, Drive, Calendar — good value if you use all |

---

## §11. 🔧 Troubleshooting

### Problem: "I can't send email"

| Cause | Fix |
|:------|:-----|
| SPF record missing | Add `v=spf1 include:_spf.protonmail.ch ~all` |
| DKIM record missing | Add the DKIM TXT record from Proton setup |
| Using wrong SMTP server | Proton uses SMTP: `mail.protonmail.ch` port 587 (TLS) |

### Problem: "Emails going to spam"

| Cause | Fix |
|:------|:-----|
| No DKIM | Add DKIM TXT record |
| No SPF | Add SPF TXT record |
| No DMARC | Add DMARC TXT record (advanced — `_dmarc.yourname.com` → `v=DMARC1; p=none`) |
| New domain (cold reputation) | Warm it up — send to trusted recipients first |

### Problem: "Verification taking forever"

| Cause | Fix |
|:------|:-----|
| Cloudflare proxy enabled | Disable proxy (gray cloud) for MX/TXT records |
| Typo in DNS record | Double-check every character — DKIM keys are case-sensitive |
| Multiple SPF records | Merge into one record |
| DNS caching | Wait 5–15 min. Cloudflare is fast. |

### Problem: "Can't receive email"

| Cause | Fix |
|:------|:-----|
| MX record wrong | Must be `mail.protonmail.ch` with priority `10` |
| MX record pointing to old provider | Update to Proton's MX |
| Domain not verified in Proton | Complete Step 5 first |

---

## §12. 📋 BP-075 Footer

```text
═══ BP-075: SELF-VERIFYING FOOTER ═══

### Document Identity

| Field | Value |
|:------|:-------|
| **Document ID** | GUIDE-402.1 |
| **Version** | **v4.29.1-r1** ✅ |
| **Date** | 18 Jul 2026 — W29 D6 (Saturday) |
| **Agent Author** | AI:@GTM 🎯 @ INT‑B001:CCC (WeOwnChat — DeepSeek V4 Flash) |
| **CCC-ID** | GTM_2026-W29_6009 |
| **#masterCCC** | GUIDE-402.1 |
| **Template Source** | TMPL-401 v4.2.2.1-r2 |
| **Series** | #BrandBuildOutMonth — W29 |
| **Target Audience** | @LFG ♍️ · @GID · Volcarian community · All personal brand builders |
| **Status** | 🟢 **DRAFT — Ready for @GTM:ADMIN review + GH push to s004_fedarch/_GUIDES_/** |

### Key Metrics

| Metric | Value |
|:-------|:------|
| Total Sections | 12 |
| Total Steps | 7 |
| Troubleshooting Items | 4 categories |
| Pro Tips | 12 |
| Estimated Setup Time | ~30 minutes |
| Fabrications | **0 ✅** |

<!-- CONTENT-HASH-BOUNDARY -->
### ✅ BP-075 CANONICAL HASH GENERATED [@GTM:ADMIN generated @ 2026-07-18 13:33 MDT]
Content-SHA256: 948368bf4432881fc9a68d1741b81d84c4dff9923e3cb25650dfe503dfa28c6e
FEDARCH-CANARY: 948368bf
CHARACTERS: 19210
WORDS: 2925
LINES: 514

═══ ═══ ═══ ═══ ═══ ═══
```

#FlowsBros #FedArch #WeOwnSeason004 #GUIDE402 #PersonalBrand #ProtonMail #Cloudflare #BrandBuildOut #GitHub #Volcarian #W29D6

♾️ WeOwnNet 🌐 ● 🏡 Real Estate and 🤝 cooperative ownership for everyone ● An 🤗 inclusive community, by 👥 invitation only.
