# Unique selling points

This is a list, often three for some reason, of positive shop characteristics like; *same day delivery* or *free EU shipping over 50 euro* ed.

## Tech notes

You can add multiple usps in the repeateble zone and they will be shown within the `prismicio.static.slices.add_to_cart.usps` element. You can then place the update and move handles so you can target where you would like to show the usps 

- Update: `<update handle="prismicio_static_usps"/>`, 
- Move: `<move element="prismicio.static.slices.usps" destination="somewhere" as="usps"/>`
