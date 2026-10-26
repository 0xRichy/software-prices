# Software prices for freelancers and small teams (dated)

Entry prices of the software tools tracked by [The Plain Stack](https://theplainstack.com/),
read on each vendor's own pricing page, from France, with the **monthly** billing view
selected, and dated.

The live file is regenerated on every site deploy:
**https://theplainstack.com/ai-tool-prices.csv**

## Columns

| Column | Meaning |
|---|---|
| `tool` | Product name |
| `plan` | The entry paid plan the price refers to |
| `price` | Price per billing unit, as shown by the vendor |
| `currency` | `USD` or `EUR`, as shown by the vendor. Never converted. |
| `price_type` | `month_to_month` (cancel any month) or `monthly_equivalent` (a yearly commitment shown per month) |
| `unit` | What the price is per: `seat`, `account`, `site`, `channel`, `brand` |
| `annual_billing_per_month` | The same plan on yearly billing, per month (empty if not offered) |
| `free_plan` | `yes` if a permanent free plan exists |
| `checked_on` | Date the vendor page was read (YYYY-MM-DD) |
| `vendor_pricing_page` | The page the price was read on |
| `record` | The full record on theplainstack.com, with limits, sources and history |

## Notes

- Dollars and euros are never added or converted: compare within a currency.
- `unit = account` means one person or one workspace: do not multiply it by a team size.
  Four tools sell their cheapest plan for one person only (Canva Pro, Todoist Pro,
  Descript Hobbyist, Google AI Plus).
- Some vendors show prices before tax (Pipedrive, Foxit), others including VAT (Adobe).
  The record page says which.
- Corrections are published at https://theplainstack.com/corrections/

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit: "The Plain Stack,
theplainstack.com", with a link.
