# cms-preventive-services-webscraper

This was a scratch webscraper to get health services that CMS classifies as preventive.

This is particularly significant for Medicare Advantage and Exchange plans, because these services must be covered at 100% by the health plan. Knowing whether the service is the member or plan's responsibility has an impact on actuarial pricing.

At the time of writing, CMS had this information codified in PDFs (claims processing manual) or a web tool. This repo assists with scraping the web tool to gather all preventive services and associated HCPCS procedure codes and ICD 10 diagnosis codes.
