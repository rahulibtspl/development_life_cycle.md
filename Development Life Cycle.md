## Development Life Cycle

* Application environment (Infrastructure as code): `Docker`
	* Identical across team, staging & production.
	* Isolated when working on multiple projects at same time.
	* Version based
	* Sync

* Version Control: `Git`
* Code Review: `Pull Request`
* Continuous Integration: `Jenkins`
	* Static analysis: `Linting Rules`
	* Code building: `Gradle or Make` 
	* Running test cases: `Unit or Integration`
	* Code coverage report
	* Artifacts generation: `Artifactory`
	* Document Generation
* Continous Deployment: `Kubernetes`
	* Automating deployment
	* Scaling
	* Management of containerized applications
		* Automated binpacking
		* Self-healing
		* Horizontal scaling
		* Service discovery and load balancing
		* Automated rollouts and rollbacks
		* Secret and Configuration Management
		* Storage Orchestration
		* Batch Execution
		 
## Databases

### How to pick a database

* Structure of a data model : Rigid vs Dynamic
* Relation between data models
* Nature of queries on the data
* Size of the data
* Speed of reads/writes
* Scaling
* Reliability
* Resiliency
* In Memory vs Persistence vs Distributed.
* CAP (Consistency, Availability, Partitioning) Theorem

### Types
* Relational: `Postgres, MySQL`
* Key-Value: `Redis, Memcached, Riak`
	* Caching
	* Queueing
	* Distributing Information/Tasks
	* Keeping live information. 
* Column: `Cassandra, HBase`
	* Keeping unstructured
	* Non-Volatile information
	* Huge Size
	* Performant 
* Document: `Mongo DB, Couchbase` 
	* Nested
	* Json compatible
* Graph: `Neo4j, OrientDB`
	* Handling complex relational information.
	* Modelling and Handling 
* Search Engine: `ElasticSearch`
	* Query: Structured, Unstructured, Geo, Metric
	* Analyze: Aggregate operations
	* Speed: Fast 
	* Scalable.
	* Flexibility.
* Time Series: `Prometheus`
	* 

## Application

### Client Server Architecture
### Microservices
### Backend
### Frontend



##### References
https://kubernetes.io/

https://www.digitalocean.com/community/tutorials/understanding-sql-and-nosql-databases-and-different-database-models

https://www.digitalocean.com/community/tutorials/a-comparison-of-nosql-database-management-systems-and-models

https://prometheus.io/
