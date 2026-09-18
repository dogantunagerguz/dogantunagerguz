# From business needs to daily decisions

I combine service-business operations with analytical development. I identify the decision a team needs to make, inspect what its records can support, address gaps in the data, and build reporting that fits the way the team works.

My operations role began in January 2025; the selected BI and operational analytics projects below began in January 2026. I work from Berlin in a hybrid arrangement with the business in Turkey. The projects cover driver training, psychotechnical assessment and travel-agency operations.

## Decisions behind the projects

| Responsibility | A decision I made | Inspectable evidence |
|---|---|---|
| Understand the business need | Started the travel project by asking which routine consumed the team's time; customer loyalty was the initial question. | [Travel: brief and wider use cases](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/docs/story.md#what-was-asked-and-what-wasnt) |
| Address missing data | Requested monthly exports because the source had no booking date; used filenames to create month-level proxies. | [Python preparation code](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/src/merger.py) |
| Challenge unreliable totals | Corrected hotel identifiers and table grain when joins multiplied sales rows. | [Travel: modelling decisions](https://github.com/dogantunagerguz/travel-agency-customer-segmentation/blob/main/docs/story.md#what-i-built) |
| Develop useful additional analysis | Expanded a commercial-licence targeting request to other licence segments and financial analysis. | [Driving school: what was added](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/docs/story.md#what-was-asked-and-what-was-added) |
| Make analysis usable | Connected eligibility segments to contact details and renewal dates to manageable outreach priorities. | [Driving-school workflow](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/docs/decision-workflow.md) · [Renewal workflow](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/blob/main/docs/decision-workflow.md) |
| Check delivery and interpret results | Added reproducible SQL companions, data-quality checks and automated tests; keep reported business observations separate from demo outputs. | [Renewal SQL evidence](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/tree/main/sql) · [Operational delivery notes](https://github.com/dogantunagerguz/driving-school-targeting-and-finance/blob/main/docs/story.md#operational-delivery-notes) |

The project stories explain my decisions; the public code makes the technical implementation inspectable. Business outcomes described as author-reported remain observations from the wider engagement.

## A shared delivery standard

For further development, I use the following checklist. This is the target standard; a checklist item is complete only when the linked project contains its implementation or operating record.

1. Define the business question, decision owner, available capacity and review period.
2. Document sources, record grain, keys and missing fields.
3. Validate the data and identify who will resolve exceptions.
4. Build repeatable preparation and reporting layers; test repeated loads and changed inputs.
5. Define each KPI's numerator, denominator, date scope and intended decision.
6. Agree refresh ownership, acceptance checks, failure handling and handover.
7. Evaluate use and impact with comparable periods and populations.

The [renewal decision workflow](https://github.com/dogantunagerguz/psychotechnical-renewal-tracker/blob/main/docs/decision-workflow.md) separates the current implementation from the additional event data and operational agreement needed to measure timely contact and completed renewals.

## Two views of the same work

| BI and data roles | Operations and process roles |
|---|---|
| Data preparation, SQL, model grain, validation, DAX and Power BI delivery | Business questions, process design, cost visibility, prioritisation, coordination and daily use |

Both views refer to the same project records. The operational solutions use Power BI; SQL companions use synthetic data. Travel and driving-school reports refresh manually, while the psychotechnical deployment uses scheduled Power BI Service refresh. Calls, outcome entry and appointment arrangements remain staff activities.
