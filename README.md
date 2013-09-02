RESTeasy

RESTeasy is a simple REST client for WinRT. Using RESTEasy, fetching data from an json http end point
is easy and fast. Support for design time data is also included.

To use RESTeasy in your view model

 string url = "<json endpoint>";
            
 var client = new RestClient();
 var results = await client.GetAsync<ResponseModel>(url);