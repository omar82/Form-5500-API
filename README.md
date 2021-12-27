# Form-5500-API
Currently the API gives access to c.9.9 million US corporate retirement plan filings with details about the organaization, participants, assets, investment, service providers, fees and a more.

The API is organized around REST.

Further information can be found on https://www.data-mining.co.uk

The base URL and patters is as follows;

<code>https://www.data-mining.co.uk/api/{API_KEY}/{SEARCH_QUERY}</code>

API KEY: <code>721937f76ee4118d05d4268531b648ae</code>
Example Search Query : <code>goldman sachs</code>

https://www.data-mining.co.uk/api/721937f76ee4118d05d4268531b648ae/goldman%20sachs

This will return the following JSON

<code>
[
    {
        "name": "GOLDMAN SACHS & CO. LLC HEALTH & WELFARE PLAN",
        "plan_sponsor": "GOLDMAN SACHS & CO. LLC",
        "address_line_1": "200 WEST STREET 19 FLOOR",
        "address_line_2": "",
        "zip": "10282",
        "ein": "135108880",
        "phone": "2129022001",
        "admin_person": "",
        "tax_year_begin": "2018-01-01",
        "tax_year_end": "2018-12-31",
        "sector_level_1": "Finance and Insurance",
        "sector_level_2": "Securities, Commodity Contracts, and Other Financial Investments and Related ActivitiesT",
        "sector_level_3": "Securities and Commodity Contracts Intermediation and BrokerageT",
        "city": "New York",
        "state": "NY",
        "plan_type": "Single-Employer Plan",
        "plan_inception": "1970-01-01",
        "plan_catagory": "Welfare Benefit",
        "assets": null
    }
]  
</code>
