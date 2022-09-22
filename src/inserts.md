*Unit price excluding tax*
*Unit price including tax*
*Tax per item*
*Total excluding tax (rounded to 2 decimals)*
*Total including tax (rounded to 2 decimals)*
*Total tax (rounded to 2 decimals)*
*Tax Percentage*
*Fk link to the Tax % (and not store the tax amount*

*TaxFree - 0%
*Vat - 17.5%*
*DiscountedVat - 15%*
*etc...*
*and then your stock table fields may have*

*ItemId*
*UnitPrice*
*fk_TaxRate*
*your invoice_detail row table will be*

*fk_OrderId*
*fk_ItemId*
*PerItemPriceCharged (denormalized)*
*TaxRateCharged (denormalized)*
*QuantityOrdered*
*your invoice table will be*

*OrderId*
*fk_CustomerId*
