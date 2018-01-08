# LEVEL 1: 💰 Figures

## Overview

We want to establish *invoices* for our beloved *customers*.

A delivery price is established upon these rules:

- The price of one delivery is the sum of the pick-up price and the drop-off price.
- pick-up & drop-off prices are fetched from their *zipcode*.
- There is a *default* prices table. (`default_prices`)
- Customers may have a *custom* prices table for specific zipcodes. (`custom_prices`)
- Invoices must have *unique* identifier and a VAT value.

## Expected behavior

Process the `input.json` to obtain the same invoices prices as in `output.json`.

## Caveats

- VAT rate is 20% on all customers


_May the force be with you_
