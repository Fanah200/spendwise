# Week 2 Budget Tracker Upgrade - SpendWise

An upgraded, semantic layout for the SpendWise Personal Budget & Expense Tracker interface. This version implements structured administrative data tables, upgraded form validation inputs, and multimedia assets.

## Features Implemented

### 1. Expense Tracking Table
- Replaced the previous generic item list with a clean structural table using semantic elements (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`).
- Styled using clean border structural merges, cell padding spacing, alternating row highlights (`tr:nth-child(even)`), and reactive background shifts on user row hover.

### 2. Upgraded Input Capture
- Upgraded the manual category type field to a secure drop-down picker panel (`<select>`) hosting core structural budget assignments (Groceries, Utilities, Entertainment, Salary/Income, Other).
- Implemented corresponding form mapping fields via matching ID anchors (`id="text-input"`, `id="amount-input"`, `id="category-input"`, `id="date-input"`).
- Altered the operational submission element to use an isolated `type="button"` container to establish a foundation for coming scripts.

### 3. Multimedia Features & Interactivity
- Placed an illustrative asset logo (`<img>`) inline with the app title using descriptive alt markers and width dimensions.
- Provided an educational sandbox presentation viewport (`<iframe>`) pointing to introductory asset scheduling strategies.
- Introduced an interactive collapsible details component (`<details>` and `<summary>`) explaining baseline dashboard interactions.

### 4. Advanced Selector Integration
- **Direct Child Selector** (`.form-control > input`): Standardizes layout behavior across explicit internal user inputs.
- **Focus Pseudo-class** (`input:focus`): Illuminates boundary lines dynamically when fields receive user focus attention.
- **Descendant Selector** (`.history-container td`): Distributes clean padding rules systematically throughout your structured ledger cell outputs.
