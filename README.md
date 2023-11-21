# Confluent Cloud - Flink SQL Shoe Store Workshop
Shoe Store Loyalty Engine - Flink SQL Workshop in Confluent Cloud running on AWS only

![image](terraform/img/Flink_Hands-on_Workshop_Complete.png)

For a good preparation and first understanding, please read this [guide](https://www.confluent.io/blog/getting-started-with-apache-flink-sql/).

## Required Confluent Cloud Resources 
  * Manual creation with this [guide](prereq.md)
  * Automatated creation using Terraform  [guide](terraform/README.md)

## Workshop Labs
  *  Lab 1: Flink Tables, Select Statements, Aggregations, Time Windows [Lab1](lab1.md)
  *  Lab 2: Join Statements, Data Enrichment, Statement Sets  [Lab2](lab2.md)

The Labs will design a loyality program within Flink SQL. The complete Mapping of dynamic Tables and Topics will be shown in next graphic.

![image](terraform/img/flink_sql_diagram.png)

## Notification Client 
  * Use Python Notification client [guide](notification_client.md)

## Costs
The lab execution do not consume much money. We calculated an amount of less than 10$ for a couple of hours testing.
