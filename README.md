Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

I covered fundamental data lake concepts, distinguishing its use cases from those of a data warehouse. We delved into the data lake's components, emphasizing the direct SQL querying of files for swift ad hoc analysis.

Addressing file structure changes within the data lake was a key focus, tackling scenarios like new fields, altered data types, and missing data. We extensively discussed effective handling techniques, including Glue Catalog Management and schema evolution, with a specific aim to minimize disruptions in downstream systems.

Exploration of diverse data formats (CSV, Parquet, Avro, ORC) ensued, highlighting their strengths and weaknesses. Our journey extended to Glue ETL, exploring its robustness as an Apache Spark-based solution for data transformation.

The course was project-oriented, featuring hands-on exercises. To exemplify Athena's scalability, we conducted queries on the vast Amazon Customer Reviews dataset, comprising over 130 million reviews. The culmination involved constructing a serverless application. Utilizing Kinesis Firehose, Lambda, Comprehend AI, Glue, Athena, and S3, we engineered a system capable of processing an unlimited volume of customer reviews, conducting sentiment analysis, and storing results in the data lake for seamless querying.on!  
  
