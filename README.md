# Lithium Project Datasets
This repository contains datasets compiled as part of an investigation into the global lithium mining boom by Columbia Journalism Investigations and Inside Climate News.
The data tracks lithium mining projects worldwide, including their locations, development stages, and associated companies and investors.

## Contents

This repository includes:

- A cleaned global dataset of lithium mining projects, covering proposed, developing, and operating sites
- A U.S.-specific dataset enriched with Social Vulnerability Index (SVI) data and additional granular geographic variables
- Shareholder datasets, including data on parent companies of subsidiaries holding lithium projects

## Methodology

The main dataset was compiled over several months using a combination of:

- S&P Global mining data
- Company reports, filings, and investor presentations
- Government databases
- Additional industry sources

Most data was collected manually. Some fields were generated through automated document and web scraping and then verified.

Project records include mines in operating, planned and early development stages. Each project was standardized to include unique ID's, location, company information and development status where available.

Geographic coordinates were taken from S&P Global or, where necessary, inferred from company disclosures and other public sources.

To support spatial analysis, we combined the project dataset with external geographic data, including:

- A global dataset of Indigenous lands compiled by Stephen T. Garnett et al. (2018, Nature Sustainability)  
- National-level Indigenous land data where available (e.g. U.S. tribal reservations)  
- Environmentally protected areas data from Protected Planet  

To account for uncertainty in reported coordinates and the spatial footprint of mining operations, we applied a 10-kilometer radius around each project location as an approximate zone of potential impact.

### Derived Spatial Analysis (United States)

For the U.S. subset of the dataset, we conducted additional spatial analysis to examine proximity between lithium projects and Indigenous lands.

Each project was linked to geographic boundaries using its coordinates. We then calculated the distance from each project to the nearest Indigenous reservation boundary using federal data on U.S. tribal reservations.

Projects were grouped into distance ranges (e.g. within 10, 15 and 20 miles) to assess how closely lithium development is sited near Indigenous lands.

In cases where projects are located near multiple reservations, distances were calculated to the nearest boundary. Additional analysis showed that most projects fall within proximity to at most one Indigenous territory.

These proximity measures are intended to identify geographic patterns and should not be interpreted as direct indicators of impact.

This dataset reflects the best available information at the time of collection and was cleaned and standardized to ensure consistency across sources.

## Limitations

This dataset is not a definitive record.

- The lithium sector is changing rapidly
- Project locations are approximate
- Company ownership and project status may change
- Some projects or data fields may be incomplete

The dataset represents a snapshot in time based on the best available information.

## Related Reporting

Read the full investigation:
[[link](https://insideclimatenews.org/news/03052026/america-lithium-rush-tribal-rights/)]

## Credits

Compiled by Johanna Hansel and Carla Samon Ros  
Columbia Journalism Investigations & Inside Climate News
