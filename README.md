# Appaka Commerce (WIP)

This is a suite of microservices to deploy a full e-commerce site.

Modules:
- Catalog: products, attributes and categories
- Warehouse: product stocks in warehouses
- Pricing: prices, discounts, vouchers, etc
- Customer: accounts, addresses, newsletters, etc
- Billing: payments, fees, etc
- Shipping: costs, routes, etc
- Logistic: units calculator, packaging, costs, etc
- Data: import/export data from/to 3rd party partners (Amazon, Google, ...)
- GraphQL: serving public data
- Web: website

Every microservice is developed in many languages (Java, Kotlin, Go, PHP, JS...), so you can make your own suite depending on your technical team skills. Even you can substitute any module with your own one, just following the API specification (RAML).

The final solution could be assembled by Docker or Kubernetes.
