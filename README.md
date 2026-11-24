# Cheap Brazil VPS: What Does a São Paulo Server Cost, Which Plan Fits a Small Site or Windows RDP, and Where Do Renewals Change the Bill? (Full Plan Table + Billing Checklist)

A cheap Brazil VPS runs from about **$2.99 to $7.99 per month** for 512 MB to 2 GB of RAM in São Paulo. Evoxt lists 512 MB at $2.99/mo, 1 GB at $4.99/mo, and 2 GB with two vCPUs at $6.95/mo. OliveVPS starts at $3.99/mo for 1 GB, and LightNode's 2 GB plan is $7.71/mo.

The 512 MB tier suits a static site, a WireGuard endpoint, or a monitoring probe. A WordPress install with MySQL, a small WooCommerce store, or a game server is better on 2 GB. That is where the real comparison starts, because the cheapest plan and the cheapest useful plan are rarely the same thing.

> **Quick pick:** Evoxt's **2 GB / 2 vCPU plan at $6.95/mo** is the useful middle for a small site, a VPN with room for services, or a Windows RDP box. The 1 GB at $4.99/mo handles a lean single site. The 512 MB at $2.99/mo is a tunnel or probe, not a WordPress host. 👉 [See Evoxt's Brazil plans and current checkout price](https://bit.ly/EvoXt)

## Evoxt's São Paulo lineup: all 11 plans

Evoxt sells KVM VPS with NVMe storage and monthly billing. The São Paulo lineup runs from 512 MB to 32 GB. The 2 GB tier appears twice, once with 1 vCPU and once with 2 vCPU. The second vCPU adds $0.96/mo, which is the smallest step in the table.

| Plan (RAM / vCPU) | NVMe | Traffic | Billing | Price (USD) | Order |
| --- | --- | ---: | --- | ---: | --- |
| 512 MB / 1 vCPU | 5 GB | 500 GB | Monthly | $2.99/mo | [Order 512 MB](https://bit.ly/EvoXt) |
| 1 GB / 1 vCPU | 10 GB | 750 GB | Monthly | $4.99/mo | [Order 1 GB](https://bit.ly/EvoXt) |
| 2 GB / 1 vCPU | 20 GB | 1 TB | Monthly | $5.99/mo | [Order 2 GB / 1 vCPU](https://bit.ly/EvoXt) |
| 2 GB / 2 vCPU | 20 GB | 2 TB | Monthly | $6.95/mo | [Order 2 GB / 2 vCPU](https://bit.ly/EvoXt) |
| 4 GB / 2 vCPU | 30 GB | 2 TB | Monthly | $11.99/mo | [Order 4 GB / 2 vCPU](https://bit.ly/EvoXt) |
| 4 GB / 4 vCPU | 30 GB | 3 TB | Monthly | $14.99/mo | [Order 4 GB / 4 vCPU](https://bit.ly/EvoXt) |
| 8 GB / 4 vCPU | 60 GB | 4 TB | Monthly | $23.99/mo | [Order 8 GB / 4 vCPU](https://bit.ly/EvoXt) |
| 8 GB / 8 vCPU | 60 GB | 5 TB | Monthly | $29.99/mo | [Order 8 GB / 8 vCPU](https://bit.ly/EvoXt) |
| 16 GB / 8 vCPU | 80 GB | 6 TB | Monthly | $47.99/mo | [Order 16 GB / 8 vCPU](https://bit.ly/EvoXt) |
| 16 GB / 16 vCPU | 80 GB | 8 TB | Monthly | $60.95/mo | [Order 16 GB / 16 vCPU](https://bit.ly/EvoXt) |
| 32 GB / 16 vCPU | 100 GB | 10 TB | Monthly | $95.99/mo | [Order 32 GB / 16 vCPU](https://bit.ly/EvoXt) |

The table reflects the published monthly prices and traffic allowances at the time of writing. Taxes, payment method, and any Windows license surcharge can change the checkout total. The published OS list includes CentOS 7.9, Debian/Ubuntu, AlmaLinux, Rocky Linux, and Windows Server 2012/2016/2022, so confirm Windows availability if that is the reason you are buying.

## The monthly price is only one line on the invoice

Hostinger's Brazil promotion shows why the headline rate needs a second look. KVM 1 is advertised at $6.49/mo, but the checkout is $155.76 for 24 months. The same term renews at $11.99/mo. If that renewal price holds for another two years, the first four years cost $443.52, or $9.24/mo on average. The $6.49 rate is a first-term price.

Other providers use different clocks. LightNode bills $0.012/hour or $7.71/mo, so releasing the instance stops the meter. KernelHost is prepaid in euros from €35.99/mo with no contract. OliveVPS bills monthly and backs every plan with a 7-day money-back guarantee.

HOSTKEY publishes an annual tiny/pico lineup and a separate monthly lineup with different specs. Its annual pico is $1.92/mo equivalent ($23.02/year) for 1 GB, 1 vCPU, 40 GB SSD, and 3 TB at 1 Gbps. Its monthly 4 GB plan is $10/mo. Those are not the same product set, so do not compare the two HOSTKEY numbers as if they were one plan.

## What a cheap Brazil VPS actually includes

Cheap plans differ more in the details than in the RAM. The table below uses each provider's own billing term and currency.

| Provider | Entry price and billing | RAM / CPU | Disk / traffic | Windows | Note |
| --- | --- | --- | --- | --- | --- |
| OliveVPS | $3.99/mo monthly | 1 GB / 1 vCPU | 25 GB NVMe / 1 TB | No on Starter; Pro $7.99+ | 7-day refund; Equinix SP4; /64 IPv6 |
| LightNode | $7.71/mo or $0.012/hr | 2 GB / 1 vCPU | 50 GB NVMe / 1 TB | Yes, RDP | All four plans have 50 GB disk; 1 to 4 TB traffic |
| KernelHost | from €35.99/mo prepaid | 2 GB / 1 vCPU | 20 GB SSD / unlimited | No | 1 Gbps, 3.2 Tbps DDoS; no IPv6 promise |
| Hostinger | $6.49/mo on 24-month prepay ($155.76); renews $11.99/mo | 4 GB / 1 vCPU | 50 GB NVMe / 4 TB | Not confirmed on the Brazil page | First-term promo; four-year average $9.24/mo if renewal holds |
| HOSTKEY | $1.92/mo equivalent on annual pico ($23.02/yr) | 1 GB / 1 vCPU | 40 GB SSD / 3 TB at 1 Gbps | Not stated in the Brazil excerpt | Separate monthly 4 GB plan is $10/mo |

## The disk trap: more RAM does not always mean more storage

LightNode's four Brazil plans all carry 50 GB NVMe, from the 2 GB Start to the 16 GB Enterprise. KernelHost gives every São Paulo Edge plan 20 GB SSD and lets you expand to 300 GB.

Evoxt scales from 5 GB on the 512 MB plan to 100 GB on the 32 GB plan, but the cheap end is tight. A 5 GB or 10 GB disk disappears fast with a WordPress backup, a Docker image, or a game world. If you plan to host more than one site, read the disk line before the RAM line.

## Windows, IPv6, and the Brazil IP question

Windows support changes the shortlist. LightNode offers Windows/RDP in São Paulo. OliveVPS sells Windows only on Pro at $7.99/mo and Premium at $15.99/mo. Its $3.99 Starter is Linux only. KernelHost does not offer Windows on its São Paulo Edge VPS.

Evoxt's published OS list includes Windows Server 2012/2016/2022, so check whether a license surcharge applies before you order. If you need RDP for accounting software or a Windows-only tool, a cheap Linux plan is not a substitute. 👉 [Check Evoxt's Windows-ready Brazil plans](https://bit.ly/EvoXt)

IPv6 is another line item. OliveVPS includes a routed /64 with every São Paulo instance. KernelHost says IPv6 varies by location and makes no promises. Ask Evoxt support if you need IPv6.

A Brazil IP is not the same as a Brazil data center. KernelHost explicitly says it does not guarantee that third-party IP databases will place an address in Brazil. The data center location is the contract. The country label is a database opinion.

For local SEO, set the country target in Search Console and publish local content. For payment or streaming checks, test the actual IP. Ask for a test IP and run ping and traceroute from your users' network before you commit.

## Which plan should you buy?

**Static site, WireGuard endpoint, uptime probe.** 512 MB is enough for a lean Linux install. Evoxt's $2.99 plan and HOSTKEY's annual pico at $1.92/mo equivalent are the low-cost entries. A default WordPress with MySQL will usually exhaust 512 MB once a page builder and a few plugins are active.

**One small WordPress site with cache.** 1 GB works. Evoxt's $4.99 plan and OliveVPS's $3.99 Starter are the direct options. The OliveVPS Starter is Linux only. If you run WooCommerce, a page builder, or several plugins, move to 2 GB.

**Small WooCommerce store, API, or a game server for a few players.** 2 GB and 2 vCPU. Evoxt's **$6.95/mo** plan is the value pick here. LightNode's $7.71 2 GB plan includes Windows/RDP. 👉 [Order Evoxt's 2 GB / 2 vCPU plan](https://bit.ly/EvoXt)

**Docker, multiple sites, a database, or Windows RDP.** 4 GB is the floor. Evoxt's 4 GB/2 vCPU is $11.99/mo and 4 GB/4 vCPU is $14.99/mo. OliveVPS Premium at $15.99 has 4 GB and Windows. KernelHost's €35.99 entry is for unlimited traffic at 1 Gbps, not for the lowest bill.

**Streaming or large downloads.** KernelHost's unlimited traffic at 1 Gbps is the specialist option. Evoxt's top plan includes 10 TB at $95.99/mo. For a normal small site, 1 to 4 TB is enough.

## FAQ

### Can a $3.99 Brazil VPS run WordPress?

1 GB RAM and 1 vCPU can run a low-traffic WordPress site with a cache plugin and a lightweight stack. A default install with MySQL, a page builder, and several plugins will hit memory limits. If you sell products or run WooCommerce, buy 2 GB.

OliveVPS Starter is Linux only. Its Pro plan at $7.99 is the first Windows option. Evoxt's 2 GB/1 vCPU at $5.99 or 2 GB/2 vCPU at $6.95 gives more headroom for a few dollars more.

### Why do some Brazil VPS plans say unlimited traffic?

KernelHost's São Paulo Edge VPS is unlimited at up to 1 Gbps. Port speed and fair-use policy still shape what you can do.

LightNode publishes 1 to 4 TB across its four plans. Hostinger publishes 4 to 32 TB. Evoxt publishes 500 GB to 10 TB. OliveVPS includes 1 to 5 TB and charges $0.005/GB overage. If your workload is video or large downloads, compare the unlimited plan's port speed and price against a capped plan with overage fees.

### Is a Brazil IP always treated as Brazilian?

No. KernelHost says it does not guarantee third-party geo databases will place its São Paulo IPs in Brazil. A São Paulo data center gives you the latency. The country label depends on the database.

Test the IP with the services you care about. For SEO, use Search Console country targeting. If you need a routed IPv6 block, OliveVPS includes a /64. KernelHost does not promise IPv6.

### Can I pay monthly, and what happens at renewal?

OliveVPS sells monthly with a 7-day money-back guarantee. LightNode bills hourly or monthly. KernelHost is prepaid in euros with no contract. Hostinger's $6.49/mo is a 24-month prepay. Renewal is $11.99/mo for the same term.

Evoxt's table is monthly, but confirm the renewal price and refund terms at checkout. The plan name is not the contract. The term and renewal line are.

## Before you order

Confirm three things: the billing term and renewal price, whether Windows is included or a surcharge, and whether you get IPv4 plus IPv6. Ask for a test IP and run a ping from your users' network. A São Paulo data center cuts latency for Brazilian users. It does not fix a bad route from your own location.

Evoxt's 512 MB at $2.99 and 2 GB/2 vCPU at $6.95 cover two very different jobs. For a small site that will grow, the 2 GB/2 vCPU plan is the one that will not need an upgrade after the first plugin. 👉 [Check Evoxt's Brazil plans and current price](https://bit.ly/EvoXt)
