# Blinkit Sales and Delivery Performance Dashboard

An interactive Power BI dashboard that analyzes sales performance and delivery reliability for a quick commerce business (Blinkit). It answers four operational questions on a single page: how much revenue is being generated, which categories drive it, how that revenue trends over time, and whether deliveries are meeting the on-time target.

<img width="1263" height="737" alt="image" src="https://github.com/user-attachments/assets/429b51c1-475f-4afe-82bc-1141ee4ab2be" />


## Business Problem

Quick commerce depends on two things: selling the right products and delivering them within the promised window. Leadership needs one view that shows sales health and delivery health together, so that a drop in revenue, a weak category or a slipping on-time rate can be spotted quickly.

This dashboard consolidates order, product, customer, delivery and feedback data into a single report with a fixed on-time target of 90 percent.

## Business Questions Answered

Each visual is titled with the question it answers.

| Dashboard Visual | Business Question |
|---|---|
| KPI card row | How large is the business in terms of orders, customers, revenue and basket value, and what share of orders arrive on time? |
| Line chart | How is revenue trending month by month? |
| Clustered bar chart | Which categories earn the most? |
| Gauge | Are we hitting our on-time target? |
| Donut chart | How reliable is our delivery? |
| Date, Category and Rating slicers | How do these answers change for a given period, product category or customer rating? |

## KPIs

| KPI | Definition | Value (full period) |
|---|---|---|
| Total Orders | Distinct count of `order_id` | 5,000 |
| Total Customers | Distinct count of `customer_id` placing orders | 2,172 |
| Total Revenue | Sum of `order_total` | 11,009,308.50 |
| Avg Order Value | Total Revenue divided by Total Orders | 2,201.86 |
| On-Time % | Orders with status "On Time" divided by Total Orders | 69.4% |
| On-Time Target | Fixed benchmark used on the gauge | 90% |

## Repository Structure

```
blinkit-sales-delivery-dashboard/
|-- datasets/
|-- Blinkit_Sales_and_Delivery_Performance_Dashboard.pbix
|-- dashboard_preview.png
|-- README.md
```

## Tools

- Power BI Desktop
- Power Query (M)
- DAX
- Chiclet Slicer custom visual

## Author

**Azli Khan**
B.Tech, Computer Science and Engineering (AI and ML), Baderia Global Institute of Engineering and Management, Jabalpur (RGPV)
Aspiring Data Engineer and Data Analyst

- LinkedIn: [linkedin.com/in/azli-khan07](https://www.linkedin.com/in/azli-khan07)
- GitHub: [github.com/Azli45](https://github.com/Azli45)
