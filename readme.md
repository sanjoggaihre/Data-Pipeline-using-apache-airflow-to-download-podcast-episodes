First of all apache airflow should be installed on the computer.
Then we modify the ~/airflow/airflow.cfg file, where we update the path where our dags are present also we set the value of false for default dags examples and default dags connection from the same cfg files.
Then we run the airflow on standalone mode by typing airflow standalone in terminal. The podcasts are downloaded on the podcast_episodes folder which is not shown here.
The data pipeline is shown below.

![data pipeline](https://github.com/sanjoggaihre/Data-Pipeline-using-apache-airflow-to-download-podcast-episodes/blob/main/pipeline.png?raw=true)
