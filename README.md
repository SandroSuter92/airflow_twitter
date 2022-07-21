# airflow_twitter - GroupWork - Msc Applied Information and Data Science - DWL01

In this repository you can find the DAG's used to build a Data Lake out of Twitter- and Crypto Data. The goal of this groupwork was to check if we can predict the course developement of the defined coins while looking at the activity of predefined #Hashtags. The DAG's run on Apache Airflow and are written in Python.

The goal of the DAG's is to regularly fetch Data from twitter about Bitcoin and Cardano. Additionally an other DAG was created to check wether Elon Musk has tweeted something about these Cryptos.

## DAG's

[Bitcoin Twitter](https://github.com/SandroSuter92/airflow_twitter/blob/master/project/dags/BTC_dag.py)

[Cardano Twitter](https://github.com/SandroSuter92/airflow_twitter/blob/master/project/dags/ADA_dag.py)

[Elon Musk Twitter](https://github.com/SandroSuter92/airflow_twitter/blob/master/project/dags/Musk_dag.py)
