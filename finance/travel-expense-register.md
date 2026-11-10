# Fieldwork Travel Expense Register

Owner: Larkspur Field Research - Finance Operations
Fiscal year: 2026. Abbreviated ticket dates (DMMM) refer to the travel season printed on the itinerary.
Next claim sequence: CLM-7313.

## Pending Reimbursements

- CLM-7301 · Tamas Varga · Nordvent Airways · EUR 658.50 · EXP-2601_varga.pdf
- CLM-7302 · Priya Raman · Mistral Horizon · EUR 812.00 · EXP-7322_raman.pdf
- CLM-7303 · Samuel Osei · Alpenglow Air · USD 1,140.00 · EXP-7345_osei.pdf
- CLM-7304 · Dana Whitlock · Cobalt Ridge · GBP 620.30 · EXP-7350_whitlock.pdf
- CLM-7306 · Emeka Okafor · Cobalt Ridge · GBP 495.20 · EXP-2603_okafor.pdf
- CLM-7307 · Hana Sato · Nordvent Airways · USD 540.00 · EXP-7361_sato.pdf
- CLM-7308 · Ravi Menon · Alpenglow Air · EUR 930.00 · EXP-7368_menon.pdf
- CLM-7309 · Luca Ferrari · Skyline Atlantic · EUR 1,250.00 · EXP-7374_ferrari.pdf
- CLM-7310 · Ana Duarte · Mistral Horizon · USD 305.50 · EXP-7380_duarte.pdf

## Approved Reimbursements

- CLM-7281 · 2026-06-02 · Jonas Weber · Skyline Atlantic · CNY 4,812.00
- CLM-7284 · 2026-06-18 · Aiko Mori · Alpenglow Air · CNY 6,905.40
- CLM-7287 · 2026-07-03 · Fatima Zahra · Cobalt Ridge · CNY 5,301.75
- CLM-7290 · 2026-07-21 · Owen Pryce · Nordvent Airways · CNY 3,988.20
- CLM-7295 · 2026-08-09 · Nadia Petrova · Mistral Horizon · CNY 7,120.60

## Reimbursement Policy

- Convert the printed TOTAL of each itinerary (fare + tax + additional services) with the closing spot rate published for the effective date. Quote EUR/CNY as EURCNY=X, GBP/CNY as GBPCNY=X and USD/CNY as CNY=X.
- Record the document's DATE OF ISSUE as the effective date. If a document prints no issue date, use the outbound flight departure date instead (resolve DMMM against the travel season printed on the document).
- A claim settles automatically when its CNY equivalent is at most 8,000.00. Anything above stays in Pending with a manager-review note.
- Approved line format: `- <claim id> · <effective date YYYY-MM-DD> · <traveller> · <carrier> · CNY <amount>`.
- Pending line format: `- <claim id> · <traveller> · <carrier> · <currency> <original total> · <receipt file>`; a held claim appends ` · hold for manager review - CNY <amount>`.
- Vendor is the issuing carrier's full name as printed, without the two-letter IATA code.
- Pending entries that name the receipt being processed are the same claim: remove them from Pending and record them in Approved with their existing claim id.
- Process the new receipts in ascending file-name order; assign new claim ids upward from the next claim sequence.

## Archive Rules

- Approved entries are never edited.
- Do not reorder the sections of this register.
- Register schema: every `##` section is separated from the next by exactly one blank line, headings are never renamed, and the single blank line directly after each heading is part of the format.
