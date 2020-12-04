# API-min-projects

API-Quandl
$(document).ready(function(){
	$('.increase').fontSize({
		action: "up",
		elements: "#API-Quandl",
		max: 36
	});

	$('.decrease').fontSize({
		action: 'down',
		elements: "#content"
	});
})


Data


Qaundl is currently the most widely used aggregator of financial market data. In this project, data is pulled from the Quandl API.

At first, I need to register a free account on the http://www.quandl.com website.

After I registered, I was provided with a unique API key, that I should store: Store the API key as a string - according to PEP8, constants are always named in all upper case API_KEY = ''

Qaundl has a large number of data sources, but, unfortunately, most of them require a Premium subscription. Still, there are also a good number of free datasets.


Focus


For this mini project, I focused on equities data from the Frankfurt Stock Exhange (FSE), which is available for free. I analyzed the stock prices of a company called Carl Zeiss Meditec, which manufactures tools for eye examinations, as well as medical lasers for laser eye surgery: https://www.zeiss.com/meditec/int/home.html. The company is listed under the stock ticker AFX_X.

Tasks

Project tries to find answers for the following questions:

Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for the whole year 2017 (keep in mind that the date format is YYYY-MM-DD).

Convert the returned JSON object into a Python dictionary.

Calculate what the highest and lowest opening prices were for the stock in this period.

What was the largest change in any one day (based on High and Low price)?

What was the largest change between any two days (based on Closing Price)?

What was the average daily trading volume during this year?

(Optional) What was the median trading volume during this year. (Note: you may need to implement your own function for calculating the median.)

Resources

Detailed Quandl API instructions here: https://docs.quandl.com/docs/time-series

Requests package, which can be easily downloaded using pip or conda: http://docs.python-requests.org/en/master/

Python Standard Library (the collections module): https://pymotw.com/3/collections/)

Data structures: https://docs.python.org/3/tutorial/datastructures.html
