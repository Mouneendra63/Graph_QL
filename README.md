# Graph_QL

1. This graphql queries is based on the countries
2. https://countries.trevorblades.com  this is the website link where we can compile and get response of request about countries
3. Sample code and output

Code:
{
  country(code :"US")
  {
    code
    phone
    awsRegion
    capital
    languages{
      name
    }
    continent
    {
      code
      name
      countries
      {
        currency
      }
    }
  }
}



Output:
{
  "data": {
    "country": {
      "code": "US",
      "phone": "1",
      "awsRegion": "us-east-2",
      "capital": "Washington D.C.",
      "languages": [
        {
          "name": "English"
        }
      ],
      "continent": {
        "code": "NA",
        "name": "North America",
        "countries": [
          {
            "currency": "XCD"
          },
          {
            "currency": "XCD"
          },
          {
            "currency": "AWG"
          },
          {
            "currency": "BBD"
          },
          {
            "currency": "EUR"
          },
          {
            "currency": "BMD"
          },
          {
            "currency": "USD"
          },
          {
            "currency": "BSD"
          },
          {
            "currency": "BZD"
          },
          {
            "currency": "CAD"
          },
          {
            "currency": "CRC"
          },
          {
            "currency": "CUC,CUP"
          },
          {
            "currency": "ANG"
          },
          {
            "currency": "XCD"
          },
          {
            "currency": "DOP"
          },
          {
            "currency": "XCD"
          },
          {
            "currency": "DKK"
          },
          {
            "currency": "EUR"
          },
          {
            "currency": "GTQ"
          },
          {
            "currency": "HNL"
          },
          {
            "currency": "HTG,USD"
          },
          {
            "currency": "JMD"
          },
          {
            "currency": "XCD"
          },
          {
            "currency": "KYD"
          },
          {
            "currency": "XCD"
          },
          {
            "currency": "EUR"
          },
          {
            "currency": "EUR"
          },
          {
            "currency": "XCD"
          },
          {
            "currency": "MXN"
          },
          {
            "currency": "NIO"
          },
          {
            "currency": "PAB,USD"
          },
          {
            "currency": "EUR"
          },
          {
            "currency": "USD"
          },
          {
            "currency": "SVC,USD"
          },
          {
            "currency": "ANG"
          },
          {
            "currency": "USD"
          },
          {
            "currency": "TTD"
          },
          {
            "currency": "USD,USN,USS"
          },
          {
            "currency": "XCD"
          },
          {
            "currency": "USD"
          },
          {
            "currency": "USD"
          }
        ]
      }
    }
  }
}
