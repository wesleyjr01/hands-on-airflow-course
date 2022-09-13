# hands-on-airflow-course
Following the The Complete Hands-On Introduction to Apache Airflow Course from Udemy

* An **Operator** defines a **Task** in your data pipeline.

* **Providers** allows to use external sources as operators, like AWS or DBT.

* A **Sensor** is a special type of operator that waits for something to happen before executing the next task. For example, if you want to wait for files, you can use the **FileSensor**. If you want to wait for an entry in an S3 bucket, you can use the **S3KeySensor**.

### Access Container Postgres DB from command line
1) `docker exec -it hands-on-airflow-course_postgres_1 /bin/bash`
2) `psql -Uairflow`
3) `SELECT * FROM users;`