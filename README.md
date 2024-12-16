# BigBanyanTree

<p align="center">
  <img src="assets/bbt.jpg" width="50%">
</p>      
<br>
BigBanyanTree is an initiative to empower engineering colleges to set up their data engineering clusters and drive
interest in data processing and analysis using tools such as Apache Spark.

 
The endeavour comprised of 3 main steps:

- Set up a ***dedicated Apache Spark cluster*** along with Jupyterlab interface to run Spark jobs.
- Parse a ***random 1% sample of the Common Crawl data dumps*** spanning the years 2018 to 2024, extracting various
  attributes.
- Perform **various analyses on the extracted datasets** and open-source our findings.

Check out the open-sourced HuggingFace datasets we created
at  

### Apache Cluster Setup

We first set up an Apache Spark cluster in standalone mode on a dedicated Hetzner server. The entire server setup was
made quite simple and straightforward by making use of `Docker` and `Docker Compose`.

To get a more in-depth understanding of our Apache Spark cluster setup, check out the following resources :

 

### CommonCrawl Data Processing

Common Crawl releases data dumps every few months, containing raw HTML source code of the literal Internet, and
open-sources this data using archival file storage formats such as **WARC** (Web Archive).

Under the BigBanyanTree project, we undertook two main data processing tasks:

- Extracting webpage JavaScript libraries from `src` tags within HTML `script` tags, among other fields.
- Enriching server IP & geolocation data using the MaxMind Database.

For a deep dive into both these topics, check out our blogs :

 
- [Server MaxMind Data Enrichment](https://datascience.fm/bigbanyantree-enriching-warc-data-with-ip-information-from-maxmind/)

    - [Serializability in Spark](https://datascience.fm/serializability-in-spark-using-non-serializable-objects-in-spark-transformations/)

### Extracted Data Analysis

TODO
