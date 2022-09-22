1. **Unit price excluding tax**
2. **Unit price including tax**
3. **Tax per item**
4. **Total excluding tax (rounded to 2 decimals)**
5. **Total including tax (rounded to 2 decimals)**
6. **Total tax (rounded to 2 decimals)**
7. **Tax Percentage**
8. **Fk link to the Tax % (and not store the tax amount**

9. **TaxFree - 0%**
10. **Vat - 17.5%**
11. **DiscountedVat - 15%**
12. **etc...**
13. **and then your stock table fields may have**

14. **ItemId**
15. **UnitPrice**
16. **fk_TaxRate**
  **your invoice_detail row table will be**

17. **fk_OrderId**
18. **fk_ItemId**
19. **PerItemPriceCharged (denormalized)**
20. **TaxRateCharged (denormalized)**
21. **QuantityOrdered**
22. **your invoice table will be**

23. **OrderId**
24. **fk_CustomerId**
