# Tradefeeds-Bond-Yields-API

<a href="https://tradefeeds.com/bond-yields-api/" rel="nofollow"> Tradefeeds Bond Yields API</a> provides real-time bond yields data. The data coverage focuses on 10-year government bonds issued by more than 50 countries around the world. Data on treasury notes of countries in Europe, Africa, Asia, South America, Asia as well as USA, Australia, New Zealand is contained in the Bond Yields Database. Tradefeeds offers the bond data on the daily, weekly and monthly percentage changes in bond yields. There has been a steady interest in the number of investors, researchers and financial analysts who request bond yields data. Investors prefer to invest in 10-year government bonds as they will certainly get the face value of the bond together with the coupon payments.The Bond Yields database is set up in such a way that goverment bonds are arranged according to the name of the country. 

The data on bond yields is available through JSON REST API or retrieved in downloadable excel or csv files. Tradefeeds Bond Yields API database is suitable for use by any type of customers - from developers who build their trading applications for a specific audience to in-house teams in all-sized companies. The bond yields data is highly demanded by financial analysts and investors both of whom use it to do detailed financial research. You can find accurate and regulartly updated data on bond yields. Tradefeeds data scientists update the API database each quarter.

Tradefeeds subscription packages are developed in such a way to serve all customers' needs. For the moment, there is no free trial provided. In case that you are a researcher or a student, we could negotiate a free trial. Sign up for an API key and we work out your case. <a href="https://tradefeeds.com/pricing-subscription-plans/" rel="nofollow">Sign up for an API key</a> and we work out your case.



<h2><a id="user-content-ways-to-access-bond-yields-data" class="anchor" href="https://github.com/Tradefeeds-Financial-data-API/Bond-Yields-API#ways-to-access-bond-data" aria-hidden="true"></a>Ways to bond yields data</h2>
<ul>
 	<li><strong>JSON REST API</strong></li>
 	<li><strong>Excel CSV download</strong></li>
 	<li><strong>PDF reports</strong></li>
 	<li><strong>Email link</strong></li>
</ul>

<h2>Documentation</h2>

Our <a href="https://tradefeeds.com/api-documentation/" rel="nofollow">documentation</a> includes input API filtering parameters, output response objects with explanation of their meaning. Clear request and response examples are given on the documentation page. Furthermore, we provide SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala. Below you can check the data output for French bonds yields. 

https://data.tradefeeds.com/api/v1/bond_yields?key=API-KEY&country=france


    "status": {
        "code": 200,
        "message": "OK",
        "details": ""
    },
    "result": {
        "output": [
            {
                "region": "europe",
                "country": "france",
                "type": "10Y",
                "yield": "2.482",
                "daypricechange": "0.0070",
                "weekchange": "-0.02%",
                "monthchange": "-0.37%",
                "yearchange": "2.42%",
                "date": "2022:11:17"
            }
        ]

 You can also check the data output for bond yields that we cover for the Asian region. 
 
 https://data.tradefeeds.com/api/v1/bond_yields?key=API-KEY&region=asia
    
    "result": {
        "output": [
            
            {
                "region": "asia",
                "country": "china",
                "type": "10Y",
                "yield": "2.822",
                "daypricechange": "0.0260",
                "weekchange": "0.11%",
                "monthchange": "0.12%",
                "yearchange": "-0.11%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "hong kong",
                "type": "10Y",
                "yield": "3.547",
                "daypricechange": "0.1490",
                "weekchange": "-0.50%",
                "monthchange": "-0.34%",
                "yearchange": "2.06%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "indonesia",
                "type": "10Y",
                "yield": "7.003",
                "daypricechange": "0.0000",
                "weekchange": "-0.31%",
                "monthchange": "-0.43%",
                "yearchange": "0.83%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "israel",
                "type": "10Y",
                "yield": "3.2",
                "daypricechange": "0.0050",
                "weekchange": "0.01%",
                "monthchange": "-0.18%",
                "yearchange": "2.15%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "india",
                "type": "10Y",
                "yield": "7.283",
                "daypricechange": "0.0090",
                "weekchange": "-0.06%",
                "monthchange": "-0.14%",
                "yearchange": "0.94%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "japan",
                "type": "10Y",
                "yield": "0.244",
                "daypricechange": "0.0010",
                "weekchange": "-0.01%",
                "monthchange": "-0.01%",
                "yearchange": "0.16%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "south korea",
                "type": "10Y",
                "yield": "3.854",
                "daypricechange": "0.0370",
                "weekchange": "-0.24%",
                "monthchange": "-0.42%",
                "yearchange": "1.52%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "malaysia",
                "type": "10Y",
                "yield": "4.281",
                "daypricechange": "0.0500",
                "weekchange": "-0.23%",
                "monthchange": "-0.17%",
                "yearchange": "0.71%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "philippines",
                "type": "10Y",
                "yield": "7.351",
                "daypricechange": "0.2450",
                "weekchange": "-0.25%",
                "monthchange": "0.15%",
                "yearchange": "2.33%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "pakistan",
                "type": "10Y",
                "yield": "12.93",
                "daypricechange": "0.0080",
                "weekchange": "0.02%",
                "monthchange": "0.18%",
                "yearchange": "2.07%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "qatar",
                "type": "10Y",
                "yield": "4.51",
                "daypricechange": "0.0210",
                "weekchange": "-0.20%",
                "monthchange": "-0.46%",
                "yearchange": "2.27%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "singapore",
                "type": "10Y",
                "yield": "3.142",
                "daypricechange": "0.0920",
                "weekchange": "-0.35%",
                "monthchange": "-0.39%",
                "yearchange": "1.36%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "thailand",
                "type": "10Y",
                "yield": "2.69",
                "daypricechange": "0.2400",
                "weekchange": "-0.24%",
                "monthchange": "-0.53%",
                "yearchange": "0.70%",
                "date": "2022:11:16"
            },
            {
                "region": "asia",
                "country": "taiwan",
                "type": "10Y",
                "yield": "1.62",
                "daypricechange": "0.0800",
                "weekchange": "-0.13%",
                "monthchange": "-0.18%",
                "yearchange": "1.08%",
                "date": "2022:11:17"
            },
            {
                "region": "asia",
                "country": "vietnam",
                "type": "10Y",
                "yield": "5.129",
                "daypricechange": "0.0180",
                "weekchange": "-0.04%",
                "monthchange": "0.07%",
                "yearchange": "3.12%",
                "date": "2022:11:17"
            }
        ]







<h2>Customer support</h2>
In case that you encounter a data issue or you want to have more features added to the API, please contact us at support@tradefeeds.com.
 
<h2>Legal</h2>

<p> The use of Tradefeeds proprietary data and API database is subject to the&nbsp;<a href="https://tradefeeds.com/terms-and-conditions-on-data/">Tradefeeds Terms &amp; Conditions.</a></p>
