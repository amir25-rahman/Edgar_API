# Edgar_API-

Hello,

This is a python scirpt that will use the API provided by EDGAR (https://www.sec.gov/edgar/searchedgar/companysearch). <br>

<b>Please read the API request rules here:</b><br>

Metadata: https://www.sec.gov/os/accessing-edgar-data <br>
Interfaces: https://www.sec.gov/edgar/sec-api-documentation <br>
FaQ : https://www.sec.gov/os/webmaster-faq#developers <br>


<b>Insttructions:</b><br>
1) Change the "User-Agent" in headers<br>
2) Use "My_stock" to lookup the CIK number, then replace that CIK into the "URL" and run my script. <br>

Document and Entity Information(DEI): Gives EntityCommonStockSharesOutstanding & EntityPublicFloat<br>
GAAP(U.S only & $USD): Will give you all the accounts with the appropriate filings(year/type/quarter)<br>
