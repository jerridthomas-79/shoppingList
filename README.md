# Shopping List Repository

This repository uses a CSV file as the database for a shopping list. Below is the schema used for the data.

## Schema

- **item**: Name of the item (string)
- **where**: Store where the item is located (string)
  - Allowed values: Fareway, Hy-Vee, Wal-Mart, Target, Costco
- **quantity**: Quantity of the item (integer >= 1)