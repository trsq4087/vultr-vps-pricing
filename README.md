# Vultr $6 VPS: What the 1 vCPU / 1 GB Plan Includes, What Backups and DDoS Add to the Bill, and When a $5 Rival Is the Better Buy (Full Plan Table)

Vultr's $6.00/mo VPS is the **High Performance AMD 1 vCPU / 1 GB** plan: one vCPU, 1 GB of RAM, **25 GB of NVMe** storage and **2 TB of monthly transfer**. Billing is monthly, there is no contract, and the price does not jump when the term renews. The configuration and price below were checked against Vultr's live pricing on **2026-11-12**.

That plan is the correct purchase for a small site, a Telegram or Discord bot, a proxy node, a staging box, or a light API. It is the wrong purchase if you need more than 24 GB of RAM in a single instance, unmetered bandwidth, or a server that someone else administers for you.

Vultr lists 16 VPS plans in total, running from $6.00/mo to $216.00/mo. The top figure is the São Paulo price for the 12 vCPU / 24 GB machine; the same box is $144.00/mo in US regions. Every plan Vultr sells uses NVMe storage, which is the main reason the $6 tier is worth a look at all rather than a $4 SSD box elsewhere.

> **Quick pick:** most readers should buy the $6.00/mo High Performance AMD 1 vCPU / 1 GB. If you can live with previous-generation Intel and regular SSD instead of NVMe, the Regular tier starts at $3.50/mo and saves you $30 a year. 👉 [Start with the $6.00/mo High Performance plan](https://bit.ly/VuLtr)

## Full Vultr plan table (High Performance AMD, verified 2026-11-12)

| Plan | vCPU / RAM | Storage | Transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| High Performance AMD 1 vCPU / 1 GB | 1 / 1 GB | 25 GB NVMe | 2 TB | **$6.00/mo** | [Start with the $6.00 plan](https://bit.ly/VuLtr) |
| High Performance AMD 1 vCPU / 2 GB | 1 / 2 GB | 50 GB NVMe | 3 TB | $12.00/mo | [Take the $12.00 plan](https://bit.ly/VuLtr) |
| High Performance AMD 2 vCPU / 2 GB | 2 / 2 GB | 60 GB NVMe | 4 TB | $18.00/mo | [Get 2 vCPU for $18.00](https://bit.ly/VuLtr) |
| High Performance AMD 2 vCPU / 4 GB | 2 / 4 GB | 100 GB NVMe | 5 TB | $24.00/mo | [Deploy the $24.00 plan](https://bit.ly/VuLtr) |
| High Performance AMD 4 vCPU / 8 GB | 4 / 8 GB | 180 GB NVMe | 6 TB | $48.00/mo | [Check the $48.00 plan](https://bit.ly/VuLtr) |
| High Performance AMD 4 vCPU / 12 GB | 4 / 12 GB | 260 GB NVMe | 7 TB | $72.00/mo | [See the $72.00 plan](https://bit.ly/VuLtr) |
| High Performance AMD 8 vCPU / 16 GB | 8 / 16 GB | 350 GB NVMe | 8 TB | $96.00/mo | [Open the $96.00 plan](https://bit.ly/VuLtr) |
| High Performance AMD 12 vCPU / 24 GB | 12 / 24 GB | 500 GB NVMe | 12 TB | $144.00/mo | [View the 24 GB plan](https://bit.ly/VuLtr) |

São Paulo costs roughly 50% more for identical specs. The same eight sizes bill at $9 / $18 / $27 / $36 / $72 / $108 / $144 / $216 there. Every other region we checked charges the US price.

This table covers one product line only. Vultr also sells Regular Performance from **$3.50/mo** ($2.50/mo for an IPv6-only instance), High Frequency from **$6.00/mo**, Optimized Cloud Compute from **$28.00/mo** with dedicated vCPUs, and VX1 from **$43.80/mo** for the smallest 2 vCPU / 8 GB shape. The $6 figure everyone quotes is the NVMe shared-CPU entry point, not the absolute cheapest thing Vultr sells.

## What the Vultr $6 VPS includes, and what it quietly leaves out

The included list is short and verifiable: NVMe on every tier, 2 TB of transfer on the $6 plan, and a choice of more than 30 regions across five continents (third-party counts range from 31 to 34 depending on the week they were taken). Amsterdam, Frankfurt, London, Warsaw, Tokyo, Osaka, Seoul, Singapore, Mumbai, Sydney, Melbourne, Toronto, São Paulo, Johannesburg and Tel Aviv are all on the list. If you need a node near users in a city most budget hosts skip, that coverage is the actual product.

The exclusions matter more, because they never appear in the headline price.

**Automatic backups add 20% to the base fee.** Turn backups on for the $6 plan and you pay about **$7.20/mo**. Backups are charged at 20% of the instance price and Vultr keeps only the two most recent copies, so it is closer to a safety net than a retention archive.

**DDoS protection is not included.** It costs **$10.00/mo per IP** and covers up to 10 Gbps. That is more than the server itself.

**Transfer is capped and metered.** Overage runs **$0.01/GB**, and Vultr bills on the higher of inbound or outbound, not the sum. The $6 plan's 2 TB is generous for a website and tight for a seedbox or a media relay.

**Port 25 is blocked by default.** Running a mail server means opening a support ticket first.

**Nothing inside the server is managed.** Vultr describes instances as entirely self-managed. Kernel updates, firewall rules, the web server, PHP and WordPress are yours. Support covers the platform and the host machine.

**The 100% uptime SLA is narrower than the badge suggests.** It covers network and host-node availability only. You have to file a ticket to claim credits, scheduled maintenance announced 24 hours ahead is excluded, GPU instances are outside it, and credits start at 12 hours of downtime.

**Support is ticket, email and Slack, with no live chat or phone.** Two low-priority tickets filed on 2026-11-02 were both answered after roughly **19.5 hours** by the same agent. Urgent tickets may move faster; that is one data point, not a service guarantee.

👉 [See the $6.00/mo plan and current add-on pricing](https://bit.ly/VuLtr)

## The real monthly bill, not the sticker price

Run the arithmetic before you compare Vultr against a $3 host with a big renewal jump.

| Configuration | Monthly | First year |
| --- | --- | --- |
| $6 plan, bare | $6.00 | $72.00 |
| $6 plan + automatic backups | $7.20 | $86.40 |
| $6 plan + backups + DDoS protection | $17.20 | $206.40 |
| $6 plan + 50 GB block storage | $11.00 | $132.00 |

Block storage is $0.10/GB/mo with a 10 GB minimum, snapshots are $0.05/GB/mo and keep billing after you destroy the source instance, and object storage starts at $0.018/GB/mo with a 250 GB floor. Any of these can double a small bill if you enable them and forget them.

The offsetting advantage is that **$6.00 stays $6.00**. There is no intro rate, no coupon that expires, and no renewal hike. Vultr's tracked pricing has not moved since 2026-10-27. Compare that with Contabo's Cloud VPS 4, which gives 8 GB of RAM and 4 vCPU for $5.28/mo on a two-year prepay of $126.72 and renews at $6.60/mo. Cheap annual prepay deals usually claw the discount back at renewal. Vultr does not play that game, and for a server you plan to keep, flat pricing is worth real money.

One more note on discounts: Vultr publishes rotating codes, but none could be verified as active during this check, so treat the $6.00 as the price you will actually pay. New accounts are offered up to **$300 in cloud credit** valid for 30 days, with a card or PayPal attached to unlock the full catalog. Some reviews still quote a $50 offer, so confirm the amount on the signup screen rather than assuming. Unused credit disappears after 30 days and billing starts on your card at that point.

## How $6 compares with the same money elsewhere

| Provider | Entry price | What the entry plan gives |
| --- | --- | --- |
| Vultr | $6.00/mo | 1 vCPU, 1 GB, 25 GB NVMe, 2 TB |
| DigitalOcean | $6.00/mo | 1 vCPU, 1 GB, SSD |
| Linode | $5.00/mo | 1 GB class plan |
| Hetzner | $5.97/mo | 1 GB class plan |
| IONOS | $5.00/mo | 1 GB class plan |
| Hostinger | $5.19/mo | 1 GB class plan |
| AWS Lightsail | $7.00/mo | 1 GB, SSD |
| Contabo | $5.28/mo (2-year prepay) | 8 GB RAM, 4 vCPU, renews at $6.60 |

The honest read: Vultr is not the cheapest door in. Across 34 budget hosts, the median entry price is $5.77/mo, so $6.00 sits just above the middle. At 8 GB, AWS Lightsail charges $44.00 against Vultr's $48.00, and at 16 GB Lightsail is $74.00 against $96.00, a 23% gap. Lightsail also scales to 512 GB of RAM and 72 vCPU while Vultr stops at 24 GB and 12 vCPU. Contabo's prepay deal beats Vultr on raw RAM and vCPU at a lower monthly figure.

Vultr wins on three things: NVMe storage on the cheapest tier where Lightsail still ships SSD, a flat renewal price, and regions that Lightsail does not cover, including Warsaw, Milan, Mexico City, Santiago, Johannesburg and Tel Aviv. For a 1 GB server, Vultr is also $1.00/mo cheaper than Lightsail.

Value rankings split depending on scope. One tracker puts no Vultr plan in its overall top 50; a narrower ranking limited to 2–16 GB plans with at least 2 vCPU places the $24 plan second, the $48 plan third and the $96 plan fifth. Read the criteria before you trust either number.

## Which plan to buy for which job

**Personal blog, static site, small WordPress install.** The $6.00 plan. 1 GB of RAM runs a cached WordPress site fine, and 25 GB of NVMe holds more than most blogs will ever need. Add backups and you are at $7.20/mo.

**Docker with a database container, or a Node/Python API with real traffic.** Move to the $12.00 plan for 2 GB of RAM and 50 GB of disk, or the $18.00 plan if you want a second vCPU. Running MySQL alongside an app on 1 GB is how people end up debugging the OOM killer at 2 a.m.

**Anything a team depends on.** Shared vCPUs are time slices on a core other tenants also use, and a noisy neighbour can dent your throughput. Vultr's dedicated-CPU Optimized line starts at $28.00/mo, and VX1 starts at $43.80/mo for 2 vCPU / 8 GB with billing on actual hours rather than the 672-hour monthly cap that applies to Cloud Compute and Optimized. VX1's launch materials claim up to 82% more performance per dollar than hyperscaler equivalents; that is vendor marketing, not an independent benchmark.

**Heavy bandwidth use.** Look elsewhere. Vultr caps transfer on every plan, from 2 TB to 12 TB, and bills $0.01/GB beyond it. Nothing in the catalog is unmetered.

Independent speed data is thin. A November 2026 test of two WordPress sites on Vultr measured a cached TTFB median of 32 ms and an uncached median of 271 ms, with zero failed requests, but server response time climbed to 5,877 ms and 6,893 ms at 40–50 concurrent users and both sites graded E. Two sites is a small sample and the tester says so. Treat it as a reason to benchmark your own workload, not as a verdict. Running `iperf3` and `fio` in the first hour on any new region is cheap insurance.

👉 [Deploy the $6.00/mo plan and benchmark it yourself](https://bit.ly/VuLtr)

## Before you enter a card number

New accounts may be asked for identity verification, and reviewers report the request sometimes arriving after a top-up rather than at signup. Complete verification before you depend on the server.

Reputation is mixed and worth reading with the sample size in mind. Trustpilot showed **1.5 out of 5 across 589 reviews as of 2026-10-27**. Complaints cluster around sudden account suspensions, verification demands after payment, and slow ticket replies. Positive reviews cite stability and low prices. Both patterns show up repeatedly enough to be real; neither describes every account.

Resizing keeps the same IP address, but if the host machine has no room Vultr migrates the instance, which can mean brief downtime. Even an in-place upgrade takes several minutes and reboots the server.

## The decision

If you want one NVMe server in a specific city for a small site, bot or API and you are comfortable running Linux yourself, buy the **$6.00/mo High Performance AMD 1 vCPU / 1 GB**. Budget $7.20/mo if you want backups, and skip the $10 DDoS add-on unless you have actually been targeted.

Go to the **$12.00 or $18.00 plan** the moment a database, a second container or more than a handful of concurrent users enters the picture. Go to **Optimized or VX1** when other people's uptime depends on yours. And if you need 8 GB of RAM on the tightest possible budget with a two-year commitment, Contabo's prepay price is lower than Vultr's $48.00.

Two things to confirm on the order page before you click: the exact credit amount your new account is offered, and whether the region you picked carries the standard price or the São Paulo surcharge.

👉 [Check the $6.00/mo plan and all 16 Vultr configurations](https://bit.ly/VuLtr)
