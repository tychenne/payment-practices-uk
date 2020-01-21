# Payment Practices of UK Buyers

Analysis of large buyer payments to suppliers in the UK from 2017 until December 2019.

## Background
#### From the description [on this kaggle page](https://www.kaggle.com/saikiran0684/payment-practices-of-uk-buyers), 

> A large business is a company or limited liability partnership that has at least two of the following: £36 million in turnover, or £18 million on its balance sheet, or 250 employees.

> UK's modest-sized enterprises are currently owed £26 billion in overdue payments, according to research by payments processing company Bacs. On average, the 307 large businesses that filed payment reports to the UK government met invoice payments late 71 % of the time. 

The dataset contains records from 2017 onwards till Dec 2019. Each row of data contains:
- The reporting period (start date and end date or the duration for which the buyer company has to report the payment numbers)
- filing information (When did the company file the records)
- Whether Payments were made during the reporting period
- Payment Metrics like Average time to pay
- Distribution of Invoices spanned across different Payment duration buckets
- Standard Payment Period (Shortest and Longest)
- Typical Payment Contractual terms agreed with Suppliers
- Changes made in Payment terms and have suppliers been notified of changes
- Does this company offer e-invoicing in relation to qualifying contracts?
- Does this company offer supply chain finance?
- Under its payment practices and policies, can this business deduct sums from payments under qualifying contracts as a charge for remaining on a supplier list?
- During the reporting period, did the company deduct sums from payments as a charge for remaining on a supplier list?

Ideas of what you could do with this dataset:
- Can you come up with a buyer credibility score? - the buyer with a high score can be trusted to make payments on time
- Can you come up with any useful insights or recommendations for groups of buyers that can be useful for any supplier for future transactions?

## Acknowledgements

This project was initially [hosted on kaggle](https://www.kaggle.com/saikiran0684/payment-practices-of-uk-buyers).

Thanks to the government of UK for [making this data publicly available](https://check-payment-practices.service.gov.uk/export).

This dataset contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

