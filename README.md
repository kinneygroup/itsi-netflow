## Summary
The ITSI Content Pack for NetFlow from Kinney Group is specifically designed to monitor network traffic and performance using NetFlow data. It leverages Splunk ITSI to provide in-depth analysis and visualization of network traffic, ensuring critical systems are operating optimally. This content pack is an essential tool for IT professionals looking to enhance the reliability and security of their network infrastructure.

* Comprehensive Network Traffic Analysis: Offers detailed insights into network traffic patterns, enabling optimized network performance and security.
* Critical Data Collection and Processing: Monitors the real-time collection and processing of NetFlow data, helping IT professionals swiftly identify and address potential issues.
* Enhanced Visualization: Facilitates better decision-making on network adjustments by visualizing processed NetFlow data through dashboards and reports.

This ITSI Content Pack is open source and available for community collaboration and enhancement on [GitHub](https://www.github.com/kinneygroup).

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas).

## Details
The ITSI Content Pack for NetFlow contains service definitions and KPIs ready to import to ITSI. The KPI Thresholds and importance values are set to defaults so that they can be tuned manually for your use case. After configuration, this content pack provides a comprehensive view of network traffic and performance.

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas).

### Services
NetFlow monitoring encompasses several specialized services, each targeting specific aspects of network traffic and performance:

1. Network Traffic Analysis
    * Description: This service is responsible for the overall analysis of network traffic, including the collection, processing, and visualization of NetFlow data.
    
2. Flow Collection
    * Description: This service handles the collection of NetFlow data from various network devices.
    
3. Flow Processing
    * Description: This service processes the collected NetFlow data, including parsing, aggregation, and enrichment.
    
4. Flow Visualization
    * Description: This service is responsible for visualizing the processed NetFlow data, providing dashboards and reports for network analysis.
    
5. Flow Exporters
    * Description: This service involves the network devices configured to export NetFlow data to the collection service.
    

### KPIs
Each service utilizes specific KPIs to measure its effectiveness:

1. Flow Records Collected Count
    * Description: Number of flow records collected from network devices.
    
2. Collection Latency
    * Description: Time taken to collect flow records from network devices.
    
3. Collection Errors Count
    * Description: Number of errors encountered during the collection of flow records.
    
4. Processed Flow Records Count
    * Description: Number of flow records successfully processed.
    
5. Processing Latency
    * Description: Time taken to process flow records.
    
6. Processing Errors Count
    * Description: Number of errors encountered during the processing of flow records.
    
7. Dashboard Load Time
    * Description: Time taken to load visualization dashboards.
    
8. Visualization Errors Count
    * Description: Number of errors encountered in visualizing flow data.
    
9. Visualization Latency
    * Description: Time taken to visualize processed flow data.
    
10. Exporter Availability
    * Description: Availability status of flow exporters.
    
11. Exported Flow Records Count
    * Description: Number of flow records exported by network devices.
    
12. Exporter Errors Count
    * Description: Number of errors encountered by flow exporters.
    

### Relationships
#### Dependencies:
Services are interconnected; for instance, Network Traffic Analysis is dependent on Flow Collection, Flow Processing, and Flow Visualization. Similarly, Flow Processing relies on Flow Collection to provide the raw NetFlow data that needs to be processed.

#### Hierarchical Structure:
Some services form a hierarchy, such as Flow Collection depending on Flow Exporters, illustrating a layered approach to network traffic monitoring where base metrics support broader performance indicators.

## Installation

### Installation prerequisites:

[Splunk Addon for NetFlow](https://splunkbase.splunk.com)

[Splunk App for Content Packs](https://splunkbase.splunk.com/app/5391)

[Splunk ITSI](https://www.splunk.com/en_us/products/it-service-intelligence.html)

## Troubleshooting

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

[Github and Readme](https://www.github.com/kinneygroup)

support@kinneygroup.com

## Contact

To provide feedback, visit our [Github and Readme](https://www.github.com/kinneygroup) for our content packs.

support@kinneygroup.com

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas).

## Version History

| Version | Date  | Description                |
|---------|-------|----------------------------|
| 0.0.1   | 05/21/24 | Initial Preview Release    |

## Considerations:

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)