# Airbnb-Listings-Analysis

A comprehensive data pipeline architecture is established, commencing with the identification of data sources from InsideAirbnb, which encompasses Airbnb Listings across various regions. The pipeline seamlessly integrates data into MongoDB Cluster0 via MongoDB Compass, ensuring efficient ingestion into Atlas. Following integration, data is ingested into Jupyter Lab operating through Docker in JetStream Cloud setup. Leveraging the "pymongo" Python package, the pipeline establishes a connection with the database, facilitating comprehensive data cleaning, preprocessing, and in-depth analysis using Python scripting (Pandas, Seaborn). Notably, the analysis uncovers significant trends in popular property types, top hosts for the Listings, and preferred neighborhoods based on pricing insights.

Moreover, data exploration reveals correlations between pricing and diverse factors such as location and property type. Leveraging advanced statistical techniques, the pipeline effectively processes and transforms raw data into actionable insights, empowering informed business decisions and targeted marketing strategies.

Subsequently, select insights from the analyzed data are stored or transmitted in document format, adhering to NoSQL standards, and are directed to a specified destination system. Finally, the analysis results are featured in the Airbnb_Analysis_L.A.ipynb, with key findings sent to MongoDB database for utilization. MongoDB's robust analytical and visualization features are leveraged to deliver enriched insights and visual representations, culminating in their publication within MongoDB Atlas. This interactive platform empowers stakeholders to seamlessly access and engage with the data, fostering intuitive exploration and a profound comprehension of underlying trends and patterns.

Data Flow Architecture:
![Architecture](https://github.com/sarutlaa/LA-s-Airbnb-Listings-/assets/141533429/2f0965bf-9f49-4824-8765-bd73a86c897a)


MongoDB Published Charts for 6th (a) and (b) Results:
https://charts.mongodb.com/charts-project-0-iayvh/public/dashboards/08c9b06e-8f22-4ad3-aa4b-dec744c288d0 

NOTE: This data is static and a pipeline to fetech the data directly from the Aibnb site and adding it in MongoDB is a good start for getting real time analytics. 

