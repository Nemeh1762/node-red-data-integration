# Node-RED Data Integration Project

This project demonstrates a Node-RED flow that integrates data from:
- MQTT (IoT sensors)
- Twitter API (HTTP request)

The data is normalized using a unified data model and stored in a MySQL database
using an event-driven architecture.

## Technologies Used
- Node-RED
- MQTT (HiveMQ)
- Twitter API (HTTP)
- MySQL

## Output
All incoming data is stored in a MySQL table named `data_stream`.
