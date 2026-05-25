SnackFlow - (MVP)

SnackFlow is a high-efficiency, secure, Single-Page Application (SPA) container designed specifically for snackbar and boutique retail environments. It bridges front-of-house operational logging with a locked back-of-house financial analytics vault, ensuring data integrity, administrative security, and role-based interface control.

Key Features & Interface Architecture

The application is structured entirely as a dynamic Single-Page Application (SPA) using clean HTML5 semantic definitions, decoupled CSS layout engines,and native JavaScript state tracking.

Role-Based Authentication Gateway (Screen 1) Segmented Authentication: Split control interface allowing instant shifting between Employee Login and Owner Access modes. Terminal ID Verification: Pinpoints the physical workstation deployment location (e.g., terminal_lahti_01) to maintain physical transaction accountability.

Operational Front-of-House Dashboard (Screen 2) Action-Driven Panels: Clean, high-contrast command layouts for logging real-time customer sales or recording back-of-house grocery shipments. Live Audit Feed: A chronological activity log that prints administrative operations in real-time (e.g., "10:30 AM 50kg Flour logged by Jane D.") to deter internal inventory discrepancies.

Incremental Data Entry Form (Screens 3 & 4) Precise Stepper Forms: Quick-action increment (+) and decrement (-) controls optimized for fast-paced retail interactions. Live Basket Summaries: Instantly updates transaction lines dynamically in memory, formatting operational rows for swift review before committing metrics to storage.

Back-of-House Manager Override & Security (Screen 4 Gateway) Supervisor Token Gate: Protects destructive actions and administrative features behind a secure Supervisor Verification PIN overlay. Visual Privacy Masking: Employs hardware-accelerated blurring algorithms (backdrop-filter) to completely obscure operational views while authorization triggers are active.

Private Analytics Vault & Weekly Ledger (Screens 5, 6 & 7) Administrative Isolation: Completely hidden from standard staff views using strict layout visibility selectors (display: none !important). Visual Financial Analytics: Integrates responsive canvas chart representations monitoring Expense vs Profit and menu segment breakdown metrics. Macro Revenue Sheets: A localized system weekly ledger automatically totaling category groupings (Pies/Puff-Puffs vs. Beverages) into dynamic grand totals.

🛠️ Technical Implementation & Architecture Structural Layer (HTML5): Optimized single-document blueprint separating operational contexts using clear semantic ID containers. Presentation Layer (CSS3): Implements a balanced executive color scheme utilizing slate tones (#2C3E50) and neutral layout backgrounds (#BFC9D2). Utilizes CSS Grid (grid-template-columns) for modern side-by-side dashboard structural tracking and adaptive Flexbox alignment for uniform spacing. Logical Runtime Control (JavaScript): Driven by a clean central routing machine (routeToScreen) mapping layout viewport switches programmatically without page reloads.
