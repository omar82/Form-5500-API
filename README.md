# Form-5500-API

Currently the API gives access to +9 million US corporate retirement plan filings with details about the organaization, participants, assets, investment, service providers, fees and a more.

The API is organized around REST.

Further information can be found on <tt>https://www.data-mining.co.uk</tt>

The base URL and patters is as follows;

<tt>https://www.data-mining.co.uk/api_test/{SEARCH_QUERY}</tt>


SEARCH_QUERY : <tt>goldman sachs</tt>

<tt>https://www.data-mining.co.uk/api_test/goldman%20sachs</tt>

This is a basic endpoint that will return the following JSON
<pre>
{
    "size bytes": 2007,
    "ttfb ms": 39,
    "results #": 3,
    "data out": [
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
        },
        {
            "name": "GOLDMAN SACHS & CO. LLC HEALTH & WELFARE PLAN",
            "plan_sponsor": "GOLDMAN SACHS & CO. LLC",
            "address_line_1": "200 WEST STREET, FLOOR 19",
            "address_line_2": "",
            "zip": "10282",
            "ein": "135108880",
            "phone": "2129022001",
            "admin_person": "",
            "tax_year_begin": "2019-01-01",
            "tax_year_end": "2019-12-31",
            "sector_level_1": "Finance and Insurance",
            "sector_level_2": "Securities, Commodity Contracts, and Other Financial Investments and Related ActivitiesT",
            "sector_level_3": "Securities and Commodity Contracts Intermediation and BrokerageT",
            "city": "New York",
            "state": "NY",
            "plan_type": "Single-Employer Plan",
            "plan_inception": "1970-01-01",
            "plan_catagory": "Welfare Benefit",
            "assets": null
        },
        {
            "name": "GOLDMAN SACHS & CO. LLC HEALTH & WELFARE PLAN",
            "plan_sponsor": "GOLDMAN SACHS & CO. LLC",
            "address_line_1": "200 WEST STREET, FLOOR 19",
            "address_line_2": "",
            "zip": "10282",
            "ein": "135108880",
            "phone": "8012127541",
            "admin_person": "",
            "tax_year_begin": "2020-01-01",
            "tax_year_end": "2020-12-31",
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
}
</pre>


<h2>Code Snippets</h2>

<strong>Node JS</strong>

<pre>
var axios = require("axios").default;

var options = {
  method: 'GET',
  url: 'https://www.data-mining.co.uk/api_test/goldman%20sachs',
  headers: {
    'Key': 'form-5500-data.TEST',
  }
};

axios.request(options).then(function (response) {
	console.log(response.data);
}).catch(function (error) {
	console.error(error);
});
</pre>
