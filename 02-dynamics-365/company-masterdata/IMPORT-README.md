# Master Data

This folder contains synthetic starter master data for the fictional portfolio project that is coherent with the initial company profile.

## Files
- `employees.csv` — 32 fictional employees across six departments.
- `customers.csv` — five fictional B2B customers.
- `suppliers.csv` — four fictional suppliers.
- `products.csv` — six initial inventory items.
- `locations.csv` — Stockholm, Gothenburg and Malmö locations.

## To configure in BC

| Employees | Employee records | User accounts and permissions                      | **IsDone** |
| --------- | ---------------- | -------------------------------------------------- | ---------- |
| Customers | Customer records | Posting groups, payment terms, credit policies     |            |
| Suppliers | Vendor records   | Posting groups, payment terms, purchasing policies |            |
| Products  | Item records     | Inventory posting, costing, VAT, replenishment     |            |
| Locations | Location records | Warehouse setup and inventory processes            |            |
## Important notes
- All names, addresses, email addresses and business records are fictional.
- Email addresses use `example.com`.
- VAT registration numbers are deliberately marked `TEST-NOT-VALID`; replace them only with valid test identifiers if your environment requires a specific format.
- The CSVs are conceptual source master data, not guaranteed one-click Business Central configuration imports. Map columns to the relevant Business Central pages/configuration packages or use AL/API imports.
- Posting groups, payment terms, units of measure, item categories and location codes must exist in Business Central before importing records that reference them.
- Product prices and costs are illustrative, in SEK, and exclude VAT.