## Distributed File System for IMDb Movies
* **DFS**: A Distributed File System is a file system that is distributed on multiple file servers or multiple locations. It allows programs to access or store isolated files as they do with the local ones, allowing programmers to access files from any network.  
* **Motivation**: Similar to personalized advertising, movie recommendation system filters movies in advance based on personal preference. In this way, people can save time in the process of picking movie.
* **Application**: This project automates the movie seletion process and the UI page gives the clear instruction on how to upload movie. For users who forget where the movie has been uploaded into, the UI page also lists the path of the movie.


---
## ETL Pipeline
<img width="578" alt="Screen Shot 2024-04-14 at 2 47 29 PM" src="https://github.com/Cxy990605/Distributed-File-System-for-IMDb-Movies/assets/99168940/dcd30211-5ed5-4265-b9ab-1129be53548f">

ETL | **Tech Stack** 
--- | --- 
`Extract` | Python
`Transform` | Pyhon,PySpark, SQL, JSON 
`Load` | AWS, Firebase, Spark


<dl>
  <dt>Step 1:</dt>
  <dd>Web scrape the dataset from IMDb website: <a href="https://www.imdb.com/">IMDb Data</a></dd>
</dl>

<dl>
  <dt>Step 2:</dt>
  <dd>Streamline Features and filter the TOP 10 movies in different genres.</dd>
</dl>
<img width="616" alt="Screen Shot 2024-04-14 at 2 48 14 PM" src="https://github.com/Cxy990605/Distributed-File-System-for-IMDb-Movies/assets/99168940/65fb0b44-da43-4df7-8ce2-1eb509e5b58f">

<img width="658" alt="Screen Shot 2024-04-14 at 3 04 30 PM" src="https://github.com/Cxy990605/Distributed-File-System-for-IMDb-Movies/assets/99168940/c0da47a7-22ce-4eb7-812d-a5d73c7385e9">

<dl>
  <dt>Step 3:</dt>
  <dd>Design an emulated distributed file system on <b>Google Firebase</b> and <b>AWS</b>, including NameNode and DataNode.</dd>
</dl>

<dl>
  <dt>Step 4:</dt>
  <dd>Develop an application by <b>Python GUI</b>.</dd>
</dl>
<img width="615" alt="Screen Shot 2024-04-14 at 2 50 00 PM" src="https://github.com/Cxy990605/Distributed-File-System-for-IMDb-Movies/assets/99168940/cbf8b61f-a127-410c-9879-650fb91f1824">

<dl>
  <dt>Step 5:</dt>
  <dd>Conduct <b>A/B testing</b> for UI optimization.</dd>
</dl>

---

## Achievement
* ✨ Garner **300+** downloads
* ✨ Boost initial response rate by 15%
* ✨ Maintain **12%** CTR for 6-month
