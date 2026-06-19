# WB Accountability Tracker — v1 Source Archive

**A community-preserved copy of the original static template behind West Bengal's public promise ledger.**

> The creator of the [WB Accountability Tracker](https://tracker.wbupdates.com/) explicitly shared the v1 source code for anyone to fork, self-host, and adapt. This repository preserves that template so the format stays accessible — even as the live site evolves.
>
> 👉 **Live, actively updated tracker:** [tracker.wbupdates.com](https://tracker.wbupdates.com/)

---

## About the Project

The **[WB Accountability Tracker](https://tracker.wbupdates.com/)** is West Bengal's independent public ledger — a non-partisan, citizen-built website that documents every promise made by the BJP government in its 2026 election manifesto (*Bhoroshar Shopoth*) and tracks their fulfilment over the 2026–2031 term.

It is not affiliated with any political party. It receives no funding. It is maintained by ordinary people of West Bengal who believe elected governments should be held to what they publicly promised.

The [BJP promise tracker for West Bengal](https://tracker.wbupdates.com/) currently monitors:

- 15 headline commitments from the BJP manifesto
- Additional non-manifesto government actions via the [Initiatives page](https://tracker.wbupdates.com/initiatives.html)
- A live chronological [public record of BJP Sarkar updates](https://tracker.wbupdates.com/latest.html)

---

## What Does the Tracker Watch?

These are some of the major [BJP Sarkar promises in West Bengal](https://tracker.wbupdates.com/) currently on the ledger:

| Promise | Category | Status |
|---|---|---|
| ₹3,000/month Lakshmir Bhandar for women | Social Welfare | ○ Pending |
| Free bus travel for women | Transport | ○ Pending |
| DA arrears for state employees | Government Employment | ○ Pending |
| Border fencing on Bangladesh border | Security | ○ Pending |
| Bhaipo Mukto Bangla (end political nepotism) | Governance | ○ Pending |
| Restoration of central scheme funds | Finance | ○ Pending |
| Employment generation commitments | Economy | ○ Pending |

*Status shown here is illustrative. For live, sourced statuses, visit [tracker.wbupdates.com](https://tracker.wbupdates.com/).*

---

## Status Definitions

The [WB BJP manifesto tracker](https://tracker.wbupdates.com/) uses a strict, evidence-based status system:

| Symbol | Status | What it means |
|---|---|---|
| ✓ | **Fulfilled** | Official gazette, bill enacted, or verified on-ground beneficiary delivery — sourced from Tier 1/2 publication |
| ◑ | **In Progress** | Credible announcement or cabinet statement with source link confirming active pursuit |
| ✗ | **Evaded** | Government action has structurally closed the door on this promise |
| ○ | **Pending** | No action taken yet — could still happen within the term |

For the full sourcing methodology, visit the [WB Accountability Tracker methodology section](https://tracker.wbupdates.com/#methodology).

---

## Why This Repo Exists

The live [BJP promise tracking website for West Bengal](https://tracker.wbupdates.com/) includes this open invitation from its creators:

> *"Anyone can fork this tracker and maintain their own version — for their district, their constituency, or their own set of promises to watch. The complete source code of this website is freely available. No login, no backend, no cost."*

This repository takes that invitation seriously. It preserves the v1 static HTML template so that:

1. The original format is version-controlled and recoverable
2. Anyone can fork it to build a **constituency-level** or **district-level** tracker
3. The template stays alive even as [tracker.wbupdates.com](https://tracker.wbupdates.com/) moves to newer versions

The [FAQ page](https://tracker.wbupdates.com/faq.html) of the original site also explains why the v1 was shared via Pastebin rather than GitHub — this repo simply makes it more accessible to developers.

---

## Deploy Your Own Free Copy

The v1 is 100% static — no server, no database, no subscription. Deploy in minutes:

### GitHub Pages (Recommended)
```
1. Fork this repository
2. Settings → Pages → Source: main branch, / (root)
3. Live at: https://yourusername.github.io/wb-tracker-v1/
```

### Cloudflare Pages
```
1. Connect GitHub fork → Cloudflare Pages
2. No build command (pure static)
3. Free custom domain included
```

### Netlify Drop
```
1. Download this repo as ZIP
2. Drag folder to netlify.com/drop
3. Instantly live
```

---

## Adapting for Your Constituency or District

To build a tracker for your MLA, your block, or your own promise set:

**Step 1 — Replace the promise data**
Edit the promise array in `index.html`. Each entry follows a proper structure.

**Step 2 — Update the header**
Change the subject name, oath date, and term end date in the countdown section.

**Step 3 — Update metadata**
Edit the `<title>`, `<meta description>`, and OG tags for your specific tracker.

**Step 4 — Host it free**
Use GitHub Pages, Cloudflare Pages, or Netlify as above.

---

## Sourcing Standards

If you build on this template, the original [West Bengal government promise tracker](https://tracker.wbupdates.com/) recommends following this source hierarchy for credibility:

1. **Gold standard:** Official government gazette or Government Order (GO)
2. State government press release or official cabinet statement
3. PTI / ANI wire reports carried by national publications (Business Standard, The Hindu, Indian Express, Hindustan Times)

Quotes from party social media do not qualify. This strict hierarchy is what makes the [WB Accountability Tracker](https://tracker.wbupdates.com/) trustworthy.

Full methodology: [tracker.wbupdates.com/faq.html](https://tracker.wbupdates.com/faq.html)

---

## Submit Updates to the Live Tracker

This archive is static — it does not update with new promise statuses.

For live BJP Sarkar updates and to submit corrections or new information to the active [West Bengal promise tracker](https://tracker.wbupdates.com/):

**[✏ Submit an update or correction →](https://tally.so/r/ja5B74)**

The team behind [tracker.wbupdates.com](https://tracker.wbupdates.com/) reviews every submission against the source hierarchy before updating any status.

---

## Related Pages on the Live Tracker

| Page | What it covers |
|---|---|
| [🏠 Main Dashboard](https://tracker.wbupdates.com/) | Live promise statuses, countdown, completion rate |
| [📋 Public Record](https://tracker.wbupdates.com/latest.html) | Chronological log of all BJP Sarkar updates |
| [📌 Other Initiatives](https://tracker.wbupdates.com/initiatives.html) | Non-manifesto government actions tracked separately |
| [❓ FAQ](https://tracker.wbupdates.com/faq.html) | Methodology, sourcing, independence, how to contribute |

---

## Topics & Keywords

This repo and the live [BJP West Bengal tracker](https://tracker.wbupdates.com/) relate to:

`west bengal accountability` · `bjp sarkar promises` · `west bengal election 2026` · `suvendu adhikari promises` · `bhoroshar shopoth tracker` · `wb bjp manifesto` · `promise tracker india` · `west bengal government tracker` · `bjp promise checker` · `wb tracker` · `india government accountability` · `political promise tracker`

---

## Disclaimer

This repository and the original [WB Accountability Tracker](https://tracker.wbupdates.com/) are **not government websites**, are **not affiliated with any political party**, and receive **no political funding**. This is a civic archival and open-source effort.

*"This is not a political website. It is a public notepad maintained by ordinary people of West Bengal — so we don't forget what was promised to us."*
— [tracker.wbupdates.com](https://tracker.wbupdates.com/)

---

## Credits

- **Original project:** [WB Accountability Tracker](https://tracker.wbupdates.com/) — citizen-built, volunteer-maintained
- **v1 source:** Shared publicly by the original creator for open reuse
- **This archive:** Community-maintained GitHub mirror

---

*Archived June 2026 · v1 template · West Bengal 2026–2031 term*
