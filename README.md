# Hi, I'm Issaka Mohammed

Business Central Developer (AL) | MB-800 & MB-820 Certified | BSc Computer Science, MSc Information Systems

I build Dynamics 365 Business Central extensions: from data model and
business logic through automated testing, reporting, and real external
integrations. The three projects below were each built end-to-end:
architecture decisions, working AL, automated test coverage, and
documentation of real platform behaviors discovered along the way,
including bugs caught and fixed, not just features that worked on the
first try.

## 📦 Projects

### [Warehouse Control](https://github.com/issakamo/business-central-warehouse-control)
<a href="https://github.com/issakamo/business-central-warehouse-control"><img src="images/Project1_WarehouseControl_icon_216.png" alt="Warehouse Control" width="80"></a>
Inventory exception detection and warehouse visibility. Automatically
flags stock discrepancies and receiving variances during real posting
processes, prioritizes them by variance severity, and surfaces them
through a Role Center dashboard, Item Card integration, and management
reporting.
**Demonstrates:** event subscribers on standard posting codeunits,
FlowField vs. frozen-snapshot data modeling, Word-layout reports,
permission sets, automated tests.

### [Purchase Control](https://github.com/issakamo/business-central-purchase-control)
<a href="https://github.com/issakamo/business-central-purchase-control"><img src="images/Project2_PurchaseControl_icon_216.png" alt="Purchase Control" width="80"></a>
Purchase order risk detection with full 3-way match validation
(PO ↔ receipt ↔ invoice). Weighted risk scoring, a vendor reliability
scorecard with a minimum-sample-size guard, and administrative-closure
handling so resolved risk clears itself automatically.
**Demonstrates:** multi-document business logic, a staged decision-
table risk model, Business Central platform behaviors found and
documented through manual verification (including a real match-status
masking bug caught by hand-testing in the Web Client, not by an
automated test).

### [FX Integration](https://github.com/issakamo/business-central-fx-integration)
<a href="https://github.com/issakamo/business-central-fx-integration"><img src="images/Project3_FXIntegration_icon_216.png" alt="FX Integration" width="80"></a>
Automated foreign exchange rate sync from a live external API
([Frankfurter](https://frankfurter.dev)) into Business Central's native
currency data, plus a read-only outbound OData v4 API.
**Demonstrates:** AL `interface` types for a swappable, testable
connector (mock vs. live HTTP), `HttpClient`/JSON parsing, retry and
audit logging, and a safety guard against writing incorrect financial
master data.

## 🛠️ Technical Focus

`AL` · `Dynamics 365 Business Central` · Event-driven extension design
· `HttpClient` / JSON / REST & OData v4 · Automated testing (AL Test
Framework) · Word-based reporting · Docker-based local BC development

## 📄 Certifications

- MB-800: Microsoft Dynamics 365 Business Central Functional Consultant
- MB-820: Microsoft Dynamics 365 Business Central Developer

## 📫 Let's Connect

[LinkedIn](https://linkedin.com/in/issakamo)
Open to Business Central Developer / Technical Consultant roles in the US.
