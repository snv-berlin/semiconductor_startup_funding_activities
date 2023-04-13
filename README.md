# Semiconductor startup funding 2020-2022 dataset
### About dataset
Data underlying the publication 'Who is funding the chips of the future? Analysis of global semiconductor startup funding activities' (Hess et al. 2023)

This research dataset (published under the CC0 1.0 license) contains information about startup funding rounds mentioned in blogposts on SemiEngineering.com between January 2020 and December 2023. The information was collected manually between August 2022 and January 2023. The data was manually enriched via Crunchbase.com. For further information, check 'Who is funding the chips of the future?', published by Hess et al. in April 2023. The data was collected via SemiEngineering.com, Crunchbase.com and additional manual research. 

For more information about the license, refer to: https://creativecommons.org/publicdomain/zero/1.0/deed.de

### Dataset variable description
Each row designates a transaction from an investor to a startup.

**semiengineering_url** - URL of SemiEngineering blogpost in which the transaction/funding round was mentioned.

**startup_name** - Name of the startup that received the transaction

**startup_country** - Country of the startup that received the transaction

**startup_country_eu_grouped** - Country of the startup received the transaction (EU countries grouped)


**crunchbase_startup_url** - Profile of the startup received the transactionon Crunchbase.com, if available

**part_of_SNV_analysis** - Shows whether the transaction was used in our analysis of semiconductor startups. If the core business model of the startup mentioned in the SemiEngineering blogposts was not directly related to the semiconductor ecosystem, it was not included in our analysis. This was often the case for startups innovating battery applications. Please note: only transactions with value 'yes' in this column were considered in our analysis. Considering all transactions in this dataset (including the transactions marked 'no' in this column) might lead to different results.

**funding_round_id** - Composed string to identify transactions belonging to the same funding round.

**crunchbase_funding_round_url** - Profile of the funding round on Crunchbase.com, if available

**no_investors_per_funding_round** - Number of investors who took part in the funding round the transaction was part of.

**funding_amount_info** - Shows whether the funding round the transaction was part of 

**crunchbase_funding_round_announced_date** - Shows the announced date noted on the funding round profile on Crunchbase.com at the time of data collection, if available

**crunchbase_funding_stage** - Shows the funding stage noted on the funding round profile on Crunchbase.com at the time of data collection, if available

**crunchbase_funding_type** - Shows the funding type noted on the funding round profile on Crunchbase.com at the time of data collection, if available

**crunchbase_investor_url** - Profile of the investor on Crunchbase.com, if available

**investor_name** - Name of the investor who made the transaction

**crunchbase_investor_type** - Shows the funding type noted on the funding round profile on Crunchbase.com at the time of data collection, if available

**investor_country** - Headquarter country of the investor who made the transaction

**investor_country_eu_grouped** - Headquarter country of the investor who made the transaction (EU countries grouped)

**money_raised_original_currency** - Money raised in the original currency

**money_raised_original_currency_minimum_estimate** - Money raised in the original currency containing minimum estimates for rounds with partially disclosed funding amounts (e.g., "tens of millions of US dollars")

**money_raised_original_currency_maximum_estimate** - Money raised in the original currency containing maximum estimates for rounds with partially disclosed funding amounts (e.g., "tens of millions of US dollars")

**investment_max_original_currency** - Money raised in the original currency containing maximum estimates for rounds with partially disclosed funding amounts (e.g., "tens of millions of US dollars") in numerial format

**investment_min_original_currency** - Money raised in the original currency containing minimum estimates for rounds with partially disclosed funding amounts (e.g., "tens of millions of US dollars") in numerial format

**investment_max_USD** - Money raised in USD containing maximum estimates for rounds with partially disclosed funding amounts (e.g., "tens of millions of US dollars") in numerial format

**investment_min_USD** - Money raised in USD containing minimum estimates for rounds with partially disclosed funding amounts (e.g., "tens of millions of US dollars") in numerial format

**date_for_currency_conversion** - date used to convert currency to USD via the GOOGLEFINANCE() function in Google Docs.

