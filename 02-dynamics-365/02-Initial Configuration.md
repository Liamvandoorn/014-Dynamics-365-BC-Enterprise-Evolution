
The initial ERP implementation will cover the following functional areas.

| Functional Area      | Configuration Scope                             |
| -------------------- | ----------------------------------------------- |
| Company Information  | Legal name, address and contact details         |
| General Ledger       | Chart of accounts and posting setup             |
| Currency             | SEK and EUR                                     |
| Locations            | Stockholm, Gothenburg and Malmö                 |
| Inventory            | Items, stock levels and units of measure        |
| Customers            | Customer records and payment terms              |
| Vendors              | Supplier records and purchasing information     |
| Sales & Receivables  | Sales orders, invoices and customer payments    |
| Purchases & Payables | Purchase orders, invoices and supplier payments |
| VAT                  | Swedish VAT configuration                       |
| Dimensions           | Department, Region and Business Unit            |
| Permissions          | Role-based access and permission sets           |

### Initial Configuration Decisions

- Gothenburg is the primary inventory location.
- Stockholm is the administrative headquarters.
- Malmö is a regional sales office without physical stock initially.
- SEK is the company's local accounting currency.
- EUR is supported for international purchasing.
- Employees are assigned to departments and physical locations.
- Business Central permissions are assigned according to operational responsibilities