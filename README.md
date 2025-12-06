# training
hese are the links your page can open, and what triggers each one:

1) Today “Open ↗ / Open schedule ↗” button (#todayOpenLink)

It sets href to the first match in this order:

MODULE_LINK_MAP[row.session_title]

Example in your code:
Power Greetings → https://codepen.io/Babak-Rosenthal-Mohammadi/live/YPqJbOa/302675055f3662cac9a312392ac6df1e

row.reference_url (from your CSV row in sales_training_schedule.csv)

Fallback: the schedule CSV itself

https://raw.githubusercontent.com/BabakRosewater/training/main/sales_training_schedule.csv

When no training is scheduled today, it forces:

Text: “Open schedule ↗”

Link: https://raw.githubusercontent.com/BabakRosewater/training/main/sales_training_schedule.csv

2) All the “MAIN TRAINING TILES” links (hard-coded in HTML)

These always open exactly these URLs:

Signature Sales Journey
https://codepen.io/Babak-Rosenthal-Mohammadi/live/pvyWOja/ee7d34594320d6db407467a89e4462a7

Phone Skills (placeholder)
https://example.com/phone-training

Product Knowledge
https://codepen.io/Babak-Rosenthal-Mohammadi/live/KwzXpOz/5e2693f30e1fa668dc7926cab01ac9dde

Sales Lease Training
https://codepen.io/Babak-Rosenthal-Mohammadi/live/dPMjoLL/1c902fb0041f4de48ff7e6b79032daad

Objections
https://codepen.io/Babak-Rosenthal-Mohammadi/live/NPNaLrv

CRM (placeholder)
https://example.com/crm-training

Role-Play (placeholder)
https://example.com/roleplay-library

New Hire (placeholder)
https://example.com/new-hire-306090

Coaching (placeholder)
https://example.com/manager-coaching

Sales Team Hub (Variable Operations Hub)
https://codepen.io/Babak-Rosenthal-Mohammadi/live/MYyEXOY
