# Form-5500-API

Currently the API gives access to +9 million US corporate retirement plan filings with details about the organaization, participants, assets, investment, service providers, fees and a more.

The API is organized around REST.

Further information can be found on <tt>https://www.data-mining.co.uk</tt>

The base URL and patters is as follows;

<tt>https://www.data-mining.co.uk/api/{API_KEY}/{EIN}</tt>

<tt>API_KEY: 85c937c37e91d24c55ff4b47435dec9f</tt>

<tt>EIN: Employer Identification Number</tt>

EXAMPLE:

<tt>https://data-mining.co.uk/api/7c42774df07cf3e08e52708603a9731c/311334685</tt>


This is a basic endpoint that will return the following JSON
<pre>
{
    "PLAN DATA": [
        {
            "filing_id": "20211008104504NAL0012833377001",
            "plan": "LIFESAFER INTERLOCK INC 401K PROFIT SHARING PLAN",
            "sponsor": "1 A LIFESAFER INC",
            "address_1": "3630 PARK 42 DRIVE SUITE 140C",
            "address2": "",
            "zip": "45242",
            "ein": "311334685",
            "phone": "5136519560",
            "sector_df": "Professional Scientific and Technical Services",
            "sub_sector_1_df": "Professional Scientific and Technical ServicesT",
            "sub_sector_2_df": "Other Professional Scientific and Technical ServicesT",
            "city": "CINCINNATI",
            "state": "OH",
            "plan_type": "Single Employer Plan",
            "inception": "1999-01-01",
            "plan_catagory": "Defined ContributionOther Pension Benefit",
            "year": "2020",
            "assets": "9199698"
        }
    ],
    "INVESTMENT FUNDS": [
        {
            "plan": "LIFESAFER INTERLOCK INC 401K PROFIT SHARING PLAN",
            "sponsor": "1 A LIFESAFER INC",
            "investment_entity": "SEPARATE ACCOUNT D",
            "investment_manager": "VOYA RETIREMENT INSURANCE AND ANNUITY CO",
            "holding": "8748455"
        }
    ],
    "SERVICE PROVIDER": [
        {
            "plan": "LIFESAFER INTERLOCK INC 401K PROFIT SHARING PLAN",
            "sponsor": "1 A LIFESAFER INC",
            "service_provider": "VOYA RETIREMENT INSURANCE AND ANNUI",
            "relation": "N\/A",
            "direct_compensation": "11030",
            "indirect_compensation": "0"
        },
        {
            "plan": "LIFESAFER INTERLOCK INC 401K PROFIT SHARING PLAN",
            "sponsor": "1 A LIFESAFER INC",
            "service_provider": "TRI-STATE PLAN ADMINISTRATION, INC.",
            "relation": "N\/A",
            "direct_compensation": "5600",
            "indirect_compensation": "0"
        },
        {
            "plan": "LIFESAFER INTERLOCK INC 401K PROFIT SHARING PLAN",
            "sponsor": "1 A LIFESAFER INC",
            "service_provider": "LPL FINANCIAL",
            "relation": "N\/A",
            "direct_compensation": "0",
            "indirect_compensation": "23093"
        }
    ],
    "INSURANCE BROKER": [
        {
            "plan": "LIFESAFER INTERLOCK INC 401K PROFIT SHARING PLAN",
            "sponsor": "1 A LIFESAFER INC",
            "broker": "TRI-STATE PLAN ADMINISTRATION, INC.",
            "commission": "0",
            "fee": "3981"
        }
    ]
}
</pre>
