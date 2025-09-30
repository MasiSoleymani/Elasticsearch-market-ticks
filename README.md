                            Elasticsearch Market Ticks

A project that demonstrates how to:

	•	Connect to Elasticsearch (running in Docker)
	•	Explore market tick data stored in an Elasticsearch index
	•	Query data using Elasticsearch DSL in Python
	•	Perform basic analytics and visualization with Matplotlib

  1.	Setup
     
	•	Ran Elasticsearch & Kibana in Docker
	•	Verified connection on http://localhost:9200
	
  2.	Data Exploration
	
	•	Listed all indices
	•	Inspected the market-ticks index with fields:
	•	timestamp, symbol, bid, ask, last, vol
	
 3.	  Queries & Analytics
	
	•	Filtered by:
	•	symbol (e.g., AAPL)
	•	Time window
	•	Volume threshold
	•	Aggregated by minute for:
	•	Average Last Price
	•	Volume per Minute
	
4.	 Visualization
	
	•	Plotted:
	•	Average Last Price per Minute
	•	Volume per Minute
