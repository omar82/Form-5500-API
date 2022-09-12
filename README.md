# Form-5500-API

Currently the API gives access to +9 million US corporate retirement plan filings with details about the organaization, participants, assets, investment, service providers, fees and a more.

The API is organized around REST.

Further information can be found on <tt>https://www.data-mining.co.uk</tt>

The base URL and patters is as follows;

<tt>https://www.data-mining.co.uk/api/{API_KEY}/{EIN}</tt>

<tt>API_KEY: 85c937c37e91d24c55ff4b47435dec9f</tt>

<tt>EIN: Employer Identification Number</tt>

EXAMPLE:

<tt>https://data-mining.co.uk/api/7c42774df07cf3e08e52708603a9731c/742497109</tt>


This is a basic endpoint that will return the following JSON
<pre>
[
    {
        "ID": "1",
        "ACK_ID": "20210303174313NAL0000556787001",
        "PLAN_NAME": "I HAVE A DREAM FOUNDATIONCOLORADO 403B PLAN",
        "url_id": "IHAVEADREAM-FOUNDATION-COLORADO403-B-PLAN",
        "SPONSOR_DFE_NAME": "I HAVE A DREAM FOUNDATION COLORADO",
        "SPONS_DFE_MAIL_US_ADDRESS1": "1836 GRANT ST",
        "SPONS_DFE_MAIL_US_ADDRESS2": "",
        "SPONS_DFE_MAIL_US_ZIP": "80203",
        "SPONS_DFE_EIN": "742497109",
        "SPONS_DFE_PHONE_NUM": "3038615005",
        "ADMIN_SIGNED_NAME": "STEPHANIE DREILING",
        "SPONS_SIGNED_NAME": "STEPHANIE DREILING",
        "FORM_PLAN_YEAR_BEGIN_DATE": "2020-01-01",
        "FORM_TAX_PRD": "2020-12-31",
        "sector": "Health Care And Social Assistance",
        "sub_sector_1": "Social AssistanceT",
        "sub_sector_2": "Individual And Family ServicesT",
        "SPONS_DFE_MAIL_US_CITY": "DENVER",
        "SPONS_DFE_MAIL_US_STATE": "CO",
        "plan_type": "Multiemployer Plan",
        "PLAN_EFF_DATE": "2009-01-01",
        "plan_catagory": "Defined Contribution",
        "TYPE_PENSION_BNFT_CODE": "2F2G2M2T",
        "TYPE_WELFARE_BNFT_CODE": "",
        "YEAR": "2020",
        "ASSETS": "0"
    }
]
</pre>
