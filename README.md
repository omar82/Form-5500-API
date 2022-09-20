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
    "filing_id: 20210709094252NAL0004262307001": {
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
        "assets": "63553813421",
        "fund": [
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD EMPLOYEE BENEFIT INDEX FND",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "7540605711"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD TOTAL STOCK MRKT INDEX TRS",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "6742324255"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD RUSSELL 1000 VALUE INDX TR",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "918550624"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD RUSSELL 2000 VALUE INDX TR",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "575196304"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD EUROPEAN STOCK INDEX TRUST",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "423515544"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD RUSSELL 1000 GROWTH INDX T",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "2301487058"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD PACIFIC STOCK INDEX TRUST",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "345490498"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD RUSSELL 2000 GROWTH INDX T",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "916594135"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "PIMCO COMMODITIES PLUS TRUST II",
                "investment_manager": "WILMINGTON TRUST",
                "holding": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "PRIVEST",
                "investment_manager": "PRUDENTIAL INSURANCE CO.",
                "holding": "475881295"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "AQR GLOBAL RISK PARITY ENHANCED LIQ",
                "investment_manager": "AQR CAPITAL MANAGEMENT",
                "holding": "634254542"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "BRIDGEWATER ALL WEATHER PORTFOLIO",
                "investment_manager": "BRIDGEWATER ASSOCIATES, LP",
                "holding": "1179405214"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "STATE STREET MSCI INDIA INDEX NON-L",
                "investment_manager": "STATE STREET BANK AND TRUST COMPANY",
                "holding": "147874551"
            }
        ],
        "service_provider": [
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "STATESTREET",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "6466746",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "PRUDENTIAL INSURANCE COMPANY",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "4839232",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "PIMCO",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "4441058",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "METROPOLITAN LIFE INSURANCE COMPANY",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "4423114",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "RBC CAPITAL MARKETS",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "3239708",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BRIDGEWATER",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2879092",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "NEW YORK LIFE INSURANCE COMPANY",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2202381",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "FIDELITY INVESTMENTS INSTITUTIONAL",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2057955",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MASSACHUSETTS MUTUAL LIFE INSURANCE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2022144",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "VANGUARD",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "1895660",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "WESTERN ASSET MANAGEMENT",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "1866583",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "THE LOOMIS, SAYLES & COMPANY, L.P.",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "1553867",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "IBM",
                "relation": "EMPLOYER",
                "direct_compensation": "1159132",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BLACKROCK FINANCIAL MANAGEMENT",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "926858",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MACKAY SHIELDS, LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "684144",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "JP MORGAN",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "567218",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "NEUBERGER BERMAN",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "509879",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BARINGS LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "488678",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "FINANCIAL ENGINES",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "471855",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "PRICEWATERHOUSECOOPERS LLP",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "310500",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "NORTHEAST RETIREMENT SERVICES, INC.",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "285196",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "AON HEWITT INVESTMENT CONSULTING",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "97500",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "JELLYVISION LAB, INC.",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "72120",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "IVINS, PHILLIPS AND BARKER",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "53120",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "TOWERS WATSON",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "28766",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MORNINGSTAR",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "20591",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BUCK CONSULTANTS",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "16406",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "EVESTMENT ALLIANCE LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "15557",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "TAMALE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "9280",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MERCER INVESTMENT CONSULTING INC.",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "8864",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "ANDERSEN TAX LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "5250",
                "indirect_compensation": "0"
            }
        ],
        "insurance_broker": []
    },
    "filing_id: 20220708124640NAL0018324257001": {
        "filing_id": "20220708124640NAL0018324257001",
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
        "year": "2021",
        "assets": "67554919021",
        "fund": [
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD EMPLOYEE BENEFIT INDEX FND",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "9031816021"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD TOTAL STOCK MRKT INDEX TRS",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "7912112590"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD RUSSELL 1000 VALUE INDX TR",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "1126674412"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD RUSSELL 2000 VALUE INDX TR",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "724528970"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD EUROPEAN STOCK INDEX TRUST",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "446858673"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD RUSSELL 1000 GROWTH INDX T",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "2656616995"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD PACIFIC STOCK INDEX TRUST",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "326975257"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "VANGUARD RUSSELL 2000 GROWTH INDX T",
                "investment_manager": "VANGUARD FIDUCIARY TRUST COMPANY",
                "holding": "864672110"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "PRIVEST",
                "investment_manager": "PRUDENTIAL INSURANCE CO.",
                "holding": "426378325"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "AQR GLOBAL RISK PARITY ENHANCED LIQ",
                "investment_manager": "AQR CAPITAL MANAGEMENT",
                "holding": "487387596"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "BRIDGEWATER ALL WEATHER PORTFOLIO",
                "investment_manager": "BRIDGEWATER ASSOCIATES, LP",
                "holding": "988017463"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "STATE STREET MSCI INDIA INDEX NON-L",
                "investment_manager": "STATE STREET BANK AND TRUST COMPANY",
                "holding": "205391958"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "STATE STREET TRL MSCI EMERGING MKTS",
                "investment_manager": "STATE STREET BANK AND TRUST COMPANY",
                "holding": "2545562"
            }
        ],
        "service_provider": [
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "STATESTREET",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "6819101",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "METROPOLITAN LIFE INSURANCE COMPANY",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "5490372",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "PRUDENTIAL INSURANCE COMPANY",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "5207108",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "PIMCO",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "4490452",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "FIDELITY INVESTMENTS INSTITUTIONAL",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "3410007",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "THE LOOMIS, SAYLES & COMPANY, L.P.",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "3052716",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "RBC CAPITAL MARKETS",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2969825",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BRIDGEWATER",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2726415",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "VANGUARD",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2217575",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "NEW YORK LIFE INSURANCE COMPANY",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2208128",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MASSACHUSETTS MUTUAL LIFE INSURANCE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2080279",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "WESTERN ASSET MANAGEMENT",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "1291578",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "IBM",
                "relation": "EMPLOYER",
                "direct_compensation": "1145172",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "VOYA",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "955989",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MACKAY SHIELDS, LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "895006",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BLACKROCK FINANCIAL MANAGEMENT",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "690966",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "NEUBERGER BERMAN",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "552216",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "JP MORGAN",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "485870",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BARINGS LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "460894",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "FINANCIAL ENGINES",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "346926",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "PRICEWATERHOUSECOOPERS LLP",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "315500",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "NORTHEAST RETIREMENT SERVICES, INC.",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "284804",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MERCER INVESTMENT CONSULTING INC.",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "45525",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "IVINS, PHILLIPS AND BARKER",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "34724",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "TOWERS WATSON",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "27407",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MORNINGSTAR",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "21133",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "HAGER STRATEGIC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "16665",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "JACKSON LEWIS",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "8324",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BUCK CONSULTANTS",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "7244",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM 401 K PLUS PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "ANDERSEN TAX LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "5250",
                "indirect_compensation": "0"
            }
        ],
        "insurance_broker": []
    },
    "filing_id: 20210930093133NAL0001776499001": {
        "filing_id": "20210930093133NAL0001776499001",
        "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
        "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
        "address_1": "MD 261 NEW ORCHARD ROAD",
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
        "inception": "1976-12-14",
        "plan_catagory": "Welfare Benefit",
        "year": "2020",
        "assets": "17330998",
        "fund": [
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "IBM MEDICAL BENEFITS TRUST",
                "investment_manager": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "holding": "15448998"
            }
        ],
        "service_provider": [
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "FIDELITY",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2589690",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "AETNA",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2030011",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "ANTHEM INSURANCE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "1620414",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "CVS CAREMARK",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "315213",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "METROPOLITAN LIFE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "191325",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MERCER",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "185603",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "OPTUM HEALTH (UBH)",
                "relation": "PARTY-IN INTEREST",
                "direct_compensation": "110188",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "HTA, LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "102960",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "UNITED HEALTHCARE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "66458",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "ERNST & YOUNG",
                "relation": "PARTY-IN INTEREST",
                "direct_compensation": "60199",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BUDCO",
                "relation": "PARTY- INTEREST",
                "direct_compensation": "41023",
                "indirect_compensation": "0"
            }
        ],
        "insurance_broker": [
            {
                "plan": "IBM BENEFITS PLAN FOR RETIRED EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "broker": "PACIFIC RESOURCES BENEFITS ADVISORS",
                "commission": "0",
                "fee": "88723"
            }
        ]
    },
    "filing_id: 20210901135125NAL0002922608001": {
        "filing_id": "20210901135125NAL0002922608001",
        "plan": "IBM GLOBAL ASSIGNEE MEDICAL PROGRAM",
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
        "inception": "2005-11-01",
        "plan_catagory": "Welfare Benefit",
        "year": "2020",
        "assets": null,
        "fund": [],
        "service_provider": [],
        "insurance_broker": [
            {
                "plan": "IBM GLOBAL ASSIGNEE MEDICAL PROGRAM",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "broker": "AON CONSULTING",
                "commission": "63203",
                "fee": "0"
            }
        ]
    },
    "filing_id: 20210901134709NAL0001864547001": {
        "filing_id": "20210901134709NAL0001864547001",
        "plan": "IBM GROUP LIFE INSURANCE",
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
        "inception": "1934-09-19",
        "plan_catagory": "Welfare Benefit",
        "year": "2020",
        "assets": null,
        "fund": [],
        "service_provider": [],
        "insurance_broker": [
            {
                "plan": "IBM GROUP LIFE INSURANCE",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "broker": "PACIFIC RESOURCES BENEFITS ADVISORS",
                "commission": "0",
                "fee": "127442"
            }
        ]
    },
    "filing_id: 20210901135048NAL0002568960001": {
        "filing_id": "20210901135048NAL0002568960001",
        "plan": "IBM LONG TERM DISABILITY PLAN",
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
        "inception": "1993-01-01",
        "plan_catagory": "Welfare Benefit",
        "year": "2020",
        "assets": null,
        "fund": [],
        "service_provider": [],
        "insurance_broker": [
            {
                "plan": "IBM LONG TERM DISABILITY PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "broker": "MERCER HEALTH & BENEFITS LLC",
                "commission": "0",
                "fee": "8649"
            },
            {
                "plan": "IBM LONG TERM DISABILITY PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "broker": "MERCER HEALTH & BENEFITS LLC",
                "commission": "0",
                "fee": "70329"
            },
            {
                "plan": "IBM LONG TERM DISABILITY PLAN",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "broker": "MERCER HEALTH & BENEFITS LLC",
                "commission": "0",
                "fee": "10199"
            }
        ]
    },
    "filing_id: 20210930093233NAL0003277283001": {
        "filing_id": "20210930093233NAL0003277283001",
        "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
        "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
        "address_1": "MD 261 NEW ORCHARD ROAD",
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
        "inception": "1980-05-01",
        "plan_catagory": "Welfare Benefit",
        "year": "2020",
        "assets": "24698184",
        "fund": [
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "investment_entity": "IBM MEDICAL BENEFITS TRUST",
                "investment_manager": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "holding": "9995701"
            }
        ],
        "service_provider": [
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "ANTHEM INSURANCE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "16339122",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "AETNA",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "15427004",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "FIDELITY",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "8642372",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "CVS CAREMARK",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "4143035",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "WELLTOK",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "2412338",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "WILLIS TOWERS WATSON",
                "relation": "PARTY-IN INTEREST",
                "direct_compensation": "1305349",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MERCER",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "974422",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "HTA, LLC",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "833040",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "ERNST & YOUNG",
                "relation": "PARTY-IN INTEREST",
                "direct_compensation": "441462",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "CORE SOLUTIONS (MEDIFIT)",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "408035",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "OPTUM HEALTH (UBH)",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "386016",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "MAXIM HEALTHCARE SYSTEMS",
                "relation": "PARTY-IN INTEREST",
                "direct_compensation": "344087",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "UNITED HEALTHCARE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "336472",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "INFOTECH",
                "relation": "PARTY-IN INTEREST",
                "direct_compensation": "182155",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BI WORLDWIDE",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "167549",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "HMO CONSULTING",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "130625",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "THE VITALITY GROUP",
                "relation": "PARTY-IN-INTEREST",
                "direct_compensation": "43281",
                "indirect_compensation": "0"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "BUDCO",
                "relation": "PARTY-IN INTEREST",
                "direct_compensation": "24357",
                "indirect_compensation": "0"
            }
        ],
        "insurance_broker": [
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "broker": "MERCER HEALTH & BENEFITS LLC",
                "commission": "0",
                "fee": "465839"
            },
            {
                "plan": "IBM MEDICAL  DENTAL BENEFITS PLAN FOR REGULAR  PARTTIME EMPLOYEES",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "broker": "INTERNATIONAL BUSINESS MACHINES CO.",
                "commission": "0",
                "fee": "65733"
            }
        ]
    },
    "filing_id: 20210930093344NAL0003726849001": {
        "filing_id": "20210930093344NAL0003726849001",
        "plan": "IBM MEDICAL BENEFITS TRUST",
        "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
        "address_1": "NEW ORCHARD ROAD MD 261",
        "address2": "",
        "zip": "10504",
        "ein": "130871985",
        "phone": "8007969876",
        "sector_df": "Not Defined",
        "sub_sector_1_df": "Not Defined",
        "sub_sector_2_df": "Not Defined",
        "city": "ARMONK",
        "state": "NY",
        "plan_type": "Direct Filing Entity",
        "inception": "",
        "plan_catagory": "Direct Filing Entity DFE",
        "year": "2020",
        "assets": "25444699",
        "fund": [],
        "service_provider": [
            {
                "plan": "IBM MEDICAL BENEFITS TRUST",
                "sponsor": "INTERNATIONAL BUSINESS MACHINES CORPORATION",
                "service_provider": "JP MORGAN CHASE",
                "relation": "NONE",
                "direct_compensation": "10250",
                "indirect_compensation": "59936"
            }
        ],
        "insurance_broker": []
    },
    "filing_id: 20210901134823NAL0002033281001": {
        "filing_id": "20210901134823NAL0002033281001",
        "plan": "IBM MEDICAL DISABILITY INCOME PLAN",
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
        "inception": "1991-01-01",
        "plan_catagory": "Welfare Benefit",
        "year": "2020",
        "assets": null,
        "fund": [],
        "service_provider": [],
        "insurance_broker": []
    },
    "filing_id: 20210901135012NAL0002568256001": {
        "filing_id": "20210901135012NAL0002568256001",
        "plan": "IBM PAYROLL BENEFITS PLAN SEVERANCE VACATION AND SICK PAY",
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
        "inception": "1989-01-01",
        "plan_catagory": "Welfare Benefit",
        "year": "2020",
        "assets": null,
        "fund": [],
        "service_provider": [],
        "insurance_broker": []
    }
}
</pre>
