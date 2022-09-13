# Form-5500-API

Currently the API gives access to +9 million US corporate retirement plan filings with details about the organaization, participants, assets, investment, service providers, fees and a more.

The API is organized around REST.

Further information can be found on <tt>https://www.data-mining.co.uk</tt>

The base URL and patters is as follows;

<tt>https://www.data-mining.co.uk/api/{API_KEY}/{EIN}</tt>

<tt>API_KEY: 85c937c37e91d24c55ff4b47435dec9f</tt>

<tt>EIN: Employer Identification Number</tt>

EXAMPLE:

<tt>https://data-mining.co.uk/api/7c42774df07cf3e08e52708603a9731c/130871985</tt>


This is a basic endpoint that will return the following JSON
<pre>
{
    "PLAN DATA": [
        {
            "filing_id": "20210709094252NAL0004262307001",
            "plan": "IBM 401 K PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "address_1": "NEW ORCHARD ROAD MD 261",
            "address2": "",
            "zip": "10504",
            "ein": "130871985",
            "phone": "8007969876",
            "sector_df": "Professional Scientific and Technical Services",
            "sub_sector_1_df": "Professional Scientific and Technical ServicesT",
            "sub_sector_2_df": "Computer Systems Design and Related ServicesT",
            "city": "ARMONK",
            "state": "NY",
            "plan_type": "Single Employer Plan",
            "inception": "1983-07-01",
            "plan_catagory": "Defined ContributionOther Pension Benefit",
            "year": "2020",
            "assets": "63553813421"
        }
    ],
    "INVESTMENT FUNDS": [
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "VANGUARD EMPLOYEE BENEFIT INDEX FND",
            "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
            "holding": "7540605711"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "VANGUARD TOTAL STOCK MRKT INDEX TRS",
            "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
            "holding": "6742324255"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "VANGUARD RUSSELL 1000 VALUE INDX TR",
            "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
            "holding": "918550624"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "VANGUARD RUSSELL 2000 VALUE INDX TR",
            "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
            "holding": "575196304"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "VANGUARD EUROPEAN STOCK INDEX TRUST",
            "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
            "holding": "423515544"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "VANGUARD RUSSELL 1000 GROWTH INDX T",
            "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
            "holding": "2301487058"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "VANGUARD PACIFIC STOCK INDEX TRUST",
            "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
            "holding": "345490498"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "VANGUARD RUSSELL 2000 GROWTH INDX T",
            "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
            "holding": "916594135"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "PIMCO COMMODITIES PLUS TRUST II",
            "investment_manager": "WILMINGTON TRUST",
            "holding": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "PRIVEST",
            "investment_manager": "PRUDENTIAL INSURANCE CO.",
            "holding": "475881295"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "AQR GLOBAL RISK PARITY ENHANCED LIQ",
            "investment_manager": "AQR CAPITAL MANAGEMENT",
            "holding": "634254542"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "BRIDGEWATER ALL WEATHER PORTFOLIO",
            "investment_manager": "BRIDGEWATER ASSOCIATES, LP",
            "holding": "1179405214"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "investment_entity": "STATE STREET MSCI INDIA INDEX NON-L",
            "investment_manager": "STATE STREET BANK AND TRUST COMPANY",
            "holding": "147874551"
        }
    ],
    "SERVICE PROVIDER": [
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "STATESTREET",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "6466746",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "PRUDENTIAL INSURANCE COMPANY",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "4839232",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "PIMCO",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "4441058",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "METROPOLITAN LIFE INSURANCE COMPANY",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "4423114",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "RBC CAPITAL MARKETS",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "3239708",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "BRIDGEWATER",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "2879092",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "NEW YORK LIFE INSURANCE COMPANY",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "2202381",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "FIDELITY INVESTMENTS INSTITUTIONAL",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "2057955",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "MASSACHUSETTS MUTUAL LIFE INSURANCE",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "2022144",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "VANGUARD",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "1895660",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "WESTERN ASSET MANAGEMENT",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "1866583",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "THE LOOMIS, SAYLES & COMPANY, L.P.",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "1553867",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "IBM",
            "relation": "EMPLOYER",
            "direct_compensation": "1159132",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "BLACKROCK FINANCIAL MANAGEMENT",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "926858",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "MACKAY SHIELDS, LLC",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "684144",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "JP MORGAN",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "567218",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "NEUBERGER BERMAN",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "509879",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "BARINGS LLC",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "488678",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "FINANCIAL ENGINES",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "471855",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "PRICEWATERHOUSECOOPERS LLP",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "310500",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "NORTHEAST RETIREMENT SERVICES, INC.",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "285196",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "AON HEWITT INVESTMENT CONSULTING",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "97500",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "JELLYVISION LAB, INC.",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "72120",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "IVINS, PHILLIPS AND BARKER",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "53120",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "TOWERS WATSON",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "28766",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "MORNINGSTAR",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "20591",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "BUCK CONSULTANTS",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "16406",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "EVESTMENT ALLIANCE LLC",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "15557",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "TAMALE",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "9280",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "MERCER INVESTMENT CONSULTING INC.",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "8864",
            "indirect_compensation": "0"
        },
        {
            "plan": "IBM 401 (K) PLUS PLAN",
            "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
            "service_provider": "ANDERSEN TAX LLC",
            "relation": "PARTY-IN-INTEREST",
            "direct_compensation": "5250",
            "indirect_compensation": "0"
        }
    ]
}
</pre>
