# order-form
A simple spreadsheet powered order form

- Convert a google spreadsheet with your inventory into a easy to use customer order form
- Allow customers to submit their orders as a Google form response in a single click

**Google Sheet Format**

Format your sheet with these fields:

```
Category	Product	Cost	Unit	Min Unit	Available Units
Organice Rice	Basmati White Rice	330	1kg	0.1	5
Organice Rice	Surti Kolam Rice	220	1kg	0.1	5
Organice Rice	Ambe Mohar Rice	270	1kg	0.1	5
Organice Rice	Local Goan Red Rice	130	1kg	0.1	5
Pulses	Masoor Dal (Whole)	300	1kg	0.1	3
Pulses	Masoor Dal (Split)	330	1kg	0.1	3
Pulses	Moong Dal Green (Whole)	300	1kg	0.1	3
Pulses	Moong Dal (Split) Green	320	1kg	0.1	3
```

**Configure App**

- Publish your Google Sheet to the web as a CSV and copy the csv link
- Click the configure button on the app:
  -  `Inventory Sheet CSV URL` : Paste your CSV url or add the SheetID directly to the url with `?sheetId=YOUR_SHEET_ID`
  -  `Order Form URL` : Link to the order form
 
