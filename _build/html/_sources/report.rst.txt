Reports
-------

The Reports Dashboard provides users with comprehensive insights into data distribution and quality through global insights and composition charts. It offers a summary of key data processing metrics over a selected duration—enabling users to explore high-level data distribution, monitor system performance, track growth trends, evaluate operational efficiency, and analyze entity relationships. To access these insights, navigate to **Reports** from the left-side menu.   

4.1 Data Insights
^^^^^^^^^^^^^^^^^

Click on **Data Insights** tab. The **Data Insights** tab offers a powerful snapshot of your data landscape, helping you assess quality, completeness, and distribution at a glance. 

.. figure:: images/32.png

At the top, the **Lifetime Statistics** section gives you a high-level overview of your organization’s entire data history. 

.. list-table::
   :header-rows: 1

   * - Field
     - Description
   * - Total Records
     - The total number of data entries ingested into the system.
   * - Total Duplicates
     - The number of records identified as potential duplicates.
   * - Data Completeness
     - Measures how fully essential fields are populated across records.
   * - Low Confidence Records
     - Records with weak match scores that may require manual review or validation.

It also presents key metrics such as total records, total duplicates, data completeness, and low confidence records. Visual charts provide deeper visibility into geographical distribution, industry breakdown, company size, top categories, single-location entities, and website coverage—empowering you to make informed, data-driven decisions.  

The table below shows the different metrics and their description: 

.. list-table::
   :header-rows: 1

   * - Metrics
     - Description
   * - Geographical Distribution
     - Shows how your data entities are spread across different regions or countries.
   * - Industry Distribution
     - Displays the breakdown of records by industry or business sector.
   * - Company Size Distribution
     - Categorizes companies based on size metrics like employee count or revenue.
   * - Top Categories
     - Highlights the most common classifications or sectors present in your data.
   * - Single Location Companies
     - Indicates companies that operate from only one physical location.
   * - Single Location
     - Refers to records tagged as having just one site or office address.
   * - Website Info
     - Provides the official website URLs associated with the listed companies.

4.2 Data Health
^^^^^^^^^^^^^^^

The **Data Health** tab provides a comprehensive evaluation of your data quality, focusing on completeness, duplication, and anomalies. These insights help you monitor the overall health and effectiveness of your data management processes. 

.. figure:: images/33.png

The table below shows the metrics and their description: 

.. list-table::
   :header-rows: 1

   * - Fields
     - Description
   * - Distribution of Mastered Records
     - Displays how mastered records are distributed across sources, regions, or other dimensions.
   * - Internal Matched Records by Source
     - Shows the count of records internally matched within the platform, grouped by source system.
   * - Monthly Match Records Created (New Mastered Records)
     - Indicates the number of new mastered records generated each month.
   * - Total Records Count imported by Sources
     - Reflects the total volume of data ingested into the system from each individual source.
   * - Monthly Match Records Created (Cluster count and cluster size)
     - Reflects how many match clusters were formed monthly and the average number of records per cluster.
   * - Total Mastered Records Growth
     - Measures the cumulative increase in mastered records over time.

