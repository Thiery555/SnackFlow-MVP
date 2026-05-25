SnackFlow - (MVP)
(IT/ Designer perspective)

SnackFlow is a high-efficiency, secure, Single-Page Application (SPA) container designed specifically for snackbar and boutique retail environments. It bridges front-of-house operational logging with a locked back-of-house financial analytics vault, ensuring data integrity, administrative security, and role-based interface control.

Key Features & Interface Architecture

The application is structured entirely as a dynamic Single-Page Application (SPA) using clean HTML5 semantic definitions, decoupled CSS layout engines,and native JavaScript state tracking.

Role-Based Authentication Gateway (Screen 1) Segmented Authentication: Split control interface allowing instant shifting between Employee Login and Owner Access modes. Terminal ID Verification: Pinpoints the physical workstation deployment location (e.g., terminal_lahti_01) to maintain physical transaction accountability.

Operational Front-of-House Dashboard (Screen 2) Action-Driven Panels: Clean, high-contrast command layouts for logging real-time customer sales or recording back-of-house grocery shipments. Live Audit Feed: A chronological activity log that prints administrative operations in real-time (e.g., "10:30 AM 50kg Flour logged by Jane D.") to deter internal inventory discrepancies.

Incremental Data Entry Form (Screens 3 & 4) Precise Stepper Forms: Quick-action increment (+) and decrement (-) controls optimized for fast-paced retail interactions. Live Basket Summaries: Instantly updates transaction lines dynamically in memory, formatting operational rows for swift review before committing metrics to storage.

Back-of-House Manager Override & Security (Screen 4 Gateway) Supervisor Token Gate: Protects destructive actions and administrative features behind a secure Supervisor Verification PIN overlay. Visual Privacy Masking: Employs hardware-accelerated blurring algorithms (backdrop-filter) to completely obscure operational views while authorization triggers are active.

Private Analytics Vault & Weekly Ledger (Screens 5, 6 & 7) Administrative Isolation: Completely hidden from standard staff views using strict layout visibility selectors (display: none !important). Visual Financial Analytics: Integrates responsive canvas chart representations monitoring Expense vs Profit and menu segment breakdown metrics. Macro Revenue Sheets: A localized system weekly ledger automatically totaling category groupings (Pies/Puff-Puffs vs. Beverages) into dynamic grand totals. 
                                                             END


📖 End-User & System Operation Guide
(End-User Perspective)
This practical manual explains how staff and owners interact with the SnackFlow software MVP layouts on a daily basis.

👥 Staff Operations: Displays & Functions
1. Station Initialization (Screen-Login)
What it displays: A clean authentication gateway requesting a Terminal ID configuration.
How to use it: The employee enters the assigned station identifier (e.g., `terminal_lahti_01`) and clicks `Authenticate Session`
to open the terminal registry.

2. Main Workstation Hub (Screen-Employee-Dashboard)
What it displays: The central navigational dashboard showing active command buttons alongside a live chronological activity stream.
How to use it: Staff can click `Manual Sales Entry Flow` to process standard daily client orders or click `Log Grocery Deliveries` to
update the storage logs. The live feed to the right constantly displays recent logs so staff can verify their inputs instantly.

3. Sales & Delivery Keypads (Screen-Sales-Entry)
What it displays: Rapid data-entry panels featuring quantity adjustment keypads (`+` and `-` controls) for simple item catalog processing.
How to use it: The operator clicks the step keypads to adjust item amounts (e.g., matching a batch order of pies or puff-puffs) and hits `Commit & Record Log` to instantly lock the batch transaction entries into system memory.

 👑 Manager Operations: Reports & Dashboards
1. Security Override Gate (Modal-Manager-Auth)
What it displays: A secure, blurred PIN-validation modal overlay that blocks unauthorized entry.
How to use it: When restricted sections are selected, a manager must enter their private access PIN code to safely clear the UI lock.

2. Executive Management Panel (Screen-Owner-Dashboard)
What it displays: The administrative landing area granting exclusive root-access entry points to private business, financial, and analytical data.
How to use it: The business owner selects `View Analytics Vault` to open financial charting data.

3. Live Business Analytics Vault (Screen-Analytics-Vault)
What it displays: An interactive executive reporting dashboard featuring dynamic trending line charts and menu category allocation charts.
How to use it: Used by the owner to analyze weekly revenue trajectories, evaluate product category margins (Food vs. Beverage), and compare operating expense curves against sales performance metrics.

4. Automated Weekly Reconciliation (Screen-Weekly-Ledger)
What it displays: A complete summary matrix ledger breaking down weekly transactions by day and item sold.
How to use it: Displays real-time subtotal groupings and systematic calculations, providing the owner with instant financial data to verify cash drawer matches without manual paperwork.
                                                                 END

























🛠️ Technical Implementation & Architecture Structural Layer (HTML5): Optimized single-document blueprint separating operational contexts using clear semantic ID containers. Presentation Layer (CSS3): Implements a balanced executive color scheme utilizing slate tones (#2C3E50) and neutral layout backgrounds (#BFC9D2). Utilizes CSS Grid (grid-template-columns) for modern side-by-side dashboard structural tracking and adaptive Flexbox alignment for uniform spacing. Logical Runtime Control (JavaScript): Driven by a clean central routing machine (routeToScreen) mapping layout viewport switches programmatically without page reloads.
