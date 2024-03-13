This Application requires version Elasticsearch 8.12.1 from Elastic Search official website. 
Download elasticsearch-8.12.1-windows-x86_64 and Latest Windows PowerBI.

Use a curl PUT command to insert a json file into ElasticSearch Server,
Then Use Web API to get data in Powerbi when ElasticSearch is running.
Web API should be at http://localhost:9200

To do an Elastic Search,
Enter the URL http://localhost:9200/<index>/<type>/_search as the Web API endpoint. Replace <index> and <type> with the appropriate values for your Elasticsearch index and document type.
Power BI will retrieve data from Elasticsearch based on the configured Web API endpoint. You can then visualize and analyze the data in Power BI as needed.
