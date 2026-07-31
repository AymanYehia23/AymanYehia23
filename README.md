# Ayman Yehia

**Mobile Software Engineer · Flutter · ERPNext/Frappe**

[Portfolio](https://aymanyehia23.github.io/) · [LinkedIn](https://linkedin.com/in/ayman-swe) · [Email](mailto:aymannyehia23@gmail.com)

I build mobile products for businesses whose work happens away from a desk: field sales, distribution, logistics, B2B commerce, HR, and operational reporting.

Most of my professional code is private. This profile focuses on the engineering decisions behind it: where authority lives, how failures cross layers, how one client adapts to several ERP deployments, and how a release reaches both stores.

At ERPCloud.Systems, I initiated the company's first B2B e-commerce product line and developed it over 14 months. Across the wider portfolio, I personally submitted 14 client-branded apps across 19 Google Play and App Store listings, using shared Flutter/ERPNext codebases rather than treating every brand as an unrelated build.

## How I approach mobile systems

- Keep pricing, payment state, identity, and other business-critical authority on the server or database.
- Prefer one configurable mechanism over a new implementation for every screen, report, or client.
- Treat failure handling as architecture: typed outcomes, clear layer boundaries, and one owner for each failure class.
- Refactor working systems when their structure starts making every change expensive.
- Design for weak connections, older Android hardware, GPS-dependent workflows, and users who cannot stop to troubleshoot.

## Selected engineering work

| Work | What it demonstrates |
| --- | --- |
| **Class A Distribution** · [Android](https://play.google.com/store/apps/details?id=com.erpcloudsystems.classaec) · [iOS](https://apps.apple.com/us/app/class-a-distribution/id6755358917) | The origin build of a configurable B2B commerce product line, plus its GitHub Actions, Fastlane, and Shorebird release pipeline. |
| **Al Dosary** · [Android](https://play.google.com/store/apps/details?id=ecs.nextapp.eldossary) | End-to-end ownership of a logistics and fleet-operations subsystem inside a team application, including a metadata-driven ERPNext report engine. |
| **DMC Travel Booking** | An 18-module, trilingual Flutter client integrating live hotel availability, rate revalidation, and server-confirmed card payments. |
| **Colada** · [Android](https://play.google.com/store/apps/details?id=com.colada.coladaapp) · [iOS](https://apps.apple.com/eg/app/colada-%D9%83%D9%88%D9%84%D8%A7%D8%AF%D8%A7/id1608914841) | Contributions to offer redemption, Stripe checkout, and real-time pickup flows for a restaurant offers and loyalty platform. |

The deeper case studies, including decisions, trade-offs, and limitations, are on my [portfolio](https://aymanyehia23.github.io/).

## Public work

- **[ERPNext e-commerce setup guide](https://github.com/AymanYehia23/erp-next-ecommerce-documentation)**: a VitePress documentation site for configuring a B2B commerce app against an ERPNext instance, with a symptom-indexed troubleshooting guide. [Read the live docs](https://aymanyehia23.github.io/erp-next-ecommerce-documentation/).
- **[Ebitcoiner](https://github.com/AymanYehia23/ebitcoiner)**: my 2022 B.Sc. graduation project, a Flutter/BLoC cloud-mining client with a multi-currency wallet. It was never published; the repository remains an honest record of an academic project and a later toolchain-maintenance pass.

## Working stack

| Area | Technologies |
| --- | --- |
| Mobile | Flutter, Dart, Riverpod, BLoC/Cubit, Android, iOS |
| Architecture | Feature-first Clean Architecture, dependency injection, typed failure handling, REST/Dio |
| Business systems | ERPNext/Frappe, CRM, HR, inventory, finance, reporting |
| Mobile capabilities | Firebase, notifications, deep links, geolocation, scanning, printing, localization/RTL |
| Delivery | GitHub Actions, Fastlane, Shorebird, Android/iOS signing and store submission |

I tend to learn technology when a product creates a real constraint: WebSockets for live order state, Stripe for payments, a hotel bedbank for rate revalidation, BLE for field printing, or PostgreSQL rules for point-of-sale integrity.

Based in Egypt. Open to relocation opportunities in the UK and EU.
