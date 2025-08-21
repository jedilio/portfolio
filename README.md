# Jackie Dilio — Data & Retail Analytics Portfolio

**Turning 15+ years of retail experience and raw data into clear, actionable insights.**

I blend **retail operations** (15+ years of store leadership) with **data science & automation** (Python, SQL, Excel/Office Scripts).  
I specialize in identifying inefficiencies and building practical tools that make stores faster and decisions clearer — often starting with raw, messy data and transforming it into actionable insights.  

I’m now seeking an opportunity to continue growing my data skills in a retail environment, where I can combine my operational expertise with analytics to drive smarter, more efficient business decisions. I am adaptable, eager to learn, and committed to bringing both talent and dedication to any area of the business.

- 📍 Greensboro, NC (open to remote)
- 💼 Focus: Retail analytics, inventory management, markdown optimization, forecasting, and dashboards — powered by automation and Python.  
- 🔗 LinkedIn: [Jacquelene Dilio](https://www.linkedin.com/in/jacquelene-dilio-687aa58b)  
- 📧 Email: [jedilio@me.com](mailto:jedilio@me.com)  

---

## Featured Projects

### 1) Automatic Inventory Markdown Merge to Create Store Specific Markdown List
- **Problem:** - Store teams spent hours cross-referencing long markdown lists against on-hand inventory. Since much of the list contained products they didn’t carry — and many items had nearly identical names — managers wasted significant time identifying only the relevant markdowns.
- **What I built:** A Python pipeline that merged company markdown lists with store-level inventory data, then auto-generated store-specific PDF packets. These were clean, paginated, and easy to share with teams — ensuring each store only saw the markdowns relevant to them.
- **Impact:** Reduced manual checking on average by ~68%, saving stores payroll hours on markdown day. Store teams received clearer, targeted lists, leading to faster execution and fewer errors.
- **Stack:** Python (pandas, openpyxl, matplotlib), Microsoft Excel/Office Scripts, Microsoft Powerpoint
- **Case study:** [`projects/retail-markdowns.md`](projects/retail-markdowns.md)

### 2) Core Style ID Matching for Manufacturer Transition (ALDO ↔ WWW)
- **Problem:** Core styles existed under two parallel ID systems (ALDO Generic IDs and WWW Generic IDs). This broke joins in reports, misaligned markdowns, and this made it especially difficult to verify availability for online orders when only one ID was referenced.
- **What I built:** A Python workflow that cleans and standardizes IDs, normalizes style names, and maps **ALDO ↔ WWW** into a unified **CORE_STYLE_ID**. Each core style carries **both** Generic IDs, enabling dual-inventory checks across systems for stores and e-commerce.
- **Impact:** Unified reporting across systems, simpler markdown alignment, and fewer fulfillment cancelations from “phantom stock” by checking both inventories per order.
- **Stack:** Python (pandas), CSV/Excel exports for sharing
- **Case study:** [`projects/core-style-id-matching.md`](projects/core-style-id-matching.md)

### 3) Size Integrity & Coverage Validation
- **Problem:** Size runs in stores and DCs were inconsistent (missing widths or unbalanced quantities for each size). This created gaps on the wall, inaccurate replenishment, and noisy reporting (e.g., having width built into style name and could not be sorted properly in reporting).
- **What I built:** A Python pipeline that standardizes size/width formats, detects anomalies (missing sizes, duplicates, cross-gender/width leaks), and produces exception reports. It also computes site-level **coverage %** versus an optimal size run and renders a **Site × Style heatmap** so gaps stand out immediately.
- **Impact:** Cleaner planogram execution, more accurate replenishment, and clearer reporting. Reduced manual auditing and helped prioritize the highest-impact size fills and transfers.
- **Stack:** Python (pandas, matplotlib), Excel/CSV outputs, visual aid - PDF heatmaps.
- **Case study:** [`projects/size-integrity.md`](projects/size-integrity.md)

### 4) Store Sell-Through Analysis
- **Problem:** Measuring store-level sell-through was difficult due to mislabeled product categories and widths embedded in style names. This obscured true performance, leading to missed opportunities in replenishment, markdown timing, and allocation decisions.
- **What I built:** A Python workflow that calculates **sell-through %** at the store/style level, cleans and normalizes product data (including pulling widths out of style names to better track full styles vs. size variants), and produces trend reports. The analysis surfaces fast movers vs. slow movers, enabling data-driven actions on replenishment, transfers, or markdowns.
- **Impact:** Delivered clear visibility into store-level performance, improved markdown timing, and supported smarter allocation. Helped leadership quickly identify which stores were excelling and which needed intervention.
- **Stack:** Python (pandas, matplotlib), Excel/CSV outputs
- **Case study:** [`projects/sell-through.md`](projects/sell-through.md)

### 5) Interim Performance Dashboards During Transition (WWW → ALDO)
- **Problem:** During the transition from WWW to ALDO, no dashboards were set up in SAP. This would have left stores and leadership without visibility into sales and performance metrics for nearly a year.
- **What I built:** Using Python, I transformed raw transactional data into clean reporting datasets and created interim dashboards. These dashboards tracked KPIs such as sales, ATV, IPT, shoecare, and orders, giving stakeholders timely visibility before SAP dashboards were available. I also merged performance data with store- and associate-level objectives to clearly show growth or decline against targets.
- **Impact:** Restored visibility during a critical transition period. Leadership and stores could monitor performance, make allocation and markdown decisions, and stay aligned on business goals. By tying results directly to objectives, managers gained a clearer view of progress at both the store and associate level, making it easier to coach and celebrate wins.
- **Stack:** Python (pandas, matplotlib), Excel/CSV outputs, PDF dashboard reports
- **Case study:** [`projects/interim-dashboards.md`](projects/interim-dashboards.md)

### 6) NFL Rookie Card Trend Prediction (Machine Learning - Regression Model Optimization Project)
- **Problem:** Identify which rookie cards will appreciate fastest.
- **What I built:** Regression model on time-based sales data; engineered features (position, team, 30-day trend).
- **Impact:** Improved targeting of fast-rising cards.
- **Stack:** Machine Learning through Python (pandas, scikit-learn), plotting
- **Case study:** [`projects/nfl-card-trends.md`](projects/nfl-card-trends.md)

### 6) Document Creation & Standardization (Adobe Suite & Microsoft Office)
- **Problem:** Key leadership documents — including bi-annual performance reviews and fleet-wide agendas — were absent during a critical period. This created an urgent need to build them from scratch in order to run the business properly and provide structure for leaders across the fleet.
- **What I built:** Designed and standardized professional templates using Adobe Acrobat and Microsoft Office (Word, Excel). These included multiple-position performance review documents and a weekly fleet agenda for stores. The templates were structured for easy updates and re-use, ensuring consistency over time.
- **Impact:** **Impact:** Provided a reliable, professional set of documents that improved communication, held stores and associates to specific objectives and standards, and saved time during recurring review and planning cycles. Ensured that leaders across the fleet had a clear, consistent framework for evaluating performance and tracking initiatives.
- **Stack:** Adobe Acrobat, Microsoft Office Suite (Word, Excel)
- **Case study:** [`projects/document-creation.md`](projects/document-creation.md)

---

## Skills & Technical Expertise
- **Programming & Data:** Python (pandas, NumPy, scikit-learn, matplotlib), SQL, R  
- **Data Science & Analytics:** Forecasting, regression modeling, predictive price modeling, data scraping & cleaning  
- **Visualization & Reporting:** Power BI, Tableau, Jupyter Notebook, Excel/Office Scripts, Adobe Creative Suite  
- **Databases & Big Data:** PostgreSQL, Neo4J, MongoDB  
- **Retail Expertise:** Allocation, inventory management, markdown execution, store operations, dashboards  
- **Other Skills:** Strategic & analytical thinking, cross-functional collaboration, team leadership

---

## Resume
📄 [View My Resume](./resume.pdf)

> Tip: Each project page below shows the business context, approach, results, and artifacts (code, PDFs, screenshots).
