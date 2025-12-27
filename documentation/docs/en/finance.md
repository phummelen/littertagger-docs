# Finance

Running an app, a website, and the backend server costs money.  
We aim to be as transparent as possible because many of our supporters choose to sponsor specific line items.

Our main expense categories are:

- **Hosting** (servers & storage)  
- **Access** (domain name & TLS certificate)  
- **Mobile** (App‑store publishing fees)

Details for each area are given in the sections that follow.

**Want to help cover our next hosting bill?**

[👉 Become a sponsor](finance-patrons.md)

## 👥 Labour costs

Our team is entirely volunteer‑driven. While we do not currently pay contributors, we may offer occasional giveaways, prizes, or bonuses as gratitude.

Our contributors fall into three groups:

 - [Litterpickers](litterpickers.md)
 - [DevOps members](finance-devops.md)
 - [Patrons](finance-patrons.md)

## 🖥️ Hosting costs

We are running a basic server with all containers on it. Our DevOps team is keen on keeping the costs low. So even higher‑quality services that incur costs are discussed and investigated in-depth.
For now, we are hosting at AWS, where we have a small EC2 machine. For the storage of the photos we are using an AWS S3 bucket.
The costs of AWS are mentioned in the below table.

|Month|Costs|Sponsor|
|------|------|----------------------|
|2023-12| t.b.m.| Fred & Pieter Jan  |
|2024-01| t.b.m.| Your name here?    |

## Access costs

To be able to access (or connect to) the application we need a web address and a certificate.
We currently do not host custom email addresses; if this changes we will evaluate the associated cost.

## Web address (Domain Name DNS Record)

|Month|Costs|Sponsor|
|------|------|----------------------|
|2024-01| $11 | Pieter Jan Hummelen |
|2025-01| $11 | Fred Steenbergen |
|2026-01| $11 | Geni Jaho |

## TLS Certificate (HTTPS)

We secure the site with **Let’s Encrypt** certificates, which are renewed at **no cost**.
Because the renewal process is fully scripted, there are no recurring fees for the current setup.

!!! note "💡 Optional sponsorship"
If the community wishes to upgrade to a paid, extended‑validation or wildcard certificate in the future, a sponsor could cover the associated cost (typically ≈ $15 per year). Until then, the existing free Let’s Encrypt certificates keep the connection encrypted at zero expense.

## Mobile‑App Strategy (Current)

At this stage we have decided not to develop separate native applications for iOS and Android. The primary reasons are:

|Reason|Detail|
|-|-|
|Cost|Publishing a native app requires a $99 /year Apple Developer membership (even nonprofits must apply for the free program) and a one‑time $25 Google Play registration fee. Maintaining two codebases also adds ongoing development and testing expenses.|
|Device‑aware Laravel site|Our Laravel‑powered website is already responsive and works well on modern smartphones and tablets. Users can access all core features through the browser without the overhead of a dedicated app.|
|Resource focus|	By concentrating on the web platform we can allocate volunteer time and any sponsorship funds to higher‑impact areas such as server hosting, security certificates, and new feature development.|

We are exploring this option and will update the community once a prototype is ready.

**What this means for users**

 - **Full functionality** is available via the responsive website at [your‑domain.com] on any mobile browser.
 - **No app download** is required, so users avoid extra storage use and update prompts.
 - **Future‑ready** – Should the project grow or a need arise for native capabilities (offline maps, push notifications, etc.), we can revisit the app decision and seek dedicated sponsorship for that effort.


**Bottom line**: For now, we keep the experience lightweight, cost‑effective, and fully accessible through the web. If you or your organization would like to sponsor a future native app, let us know—we’ll gladly revisit the plan when resources allow.

---

**Overall monthly budget:** **≈ $35**  
Every contribution, no matter the size, moves us closer to a fully funded, sustainable project.  
[💚 Support the project](finance-patrons.md)