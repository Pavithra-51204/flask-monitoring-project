# Monitoring Dockerized Flask Applications with Telegraf, InfluxDB, and Chronograf

## Overview

This project sets up a monitoring stack using Telegraf, InfluxDB, Chronograf, cAdvisor, and Grafana to monitor a Dockerized Flask application. This setup allows you to collect, store, and visualize metrics from your application and Docker containers.


## Components

- **Flask Application**: A simple Python Flask application that serves HTTP requests.
- **Telegraf**: An agent for collecting and sending metrics to InfluxDB.
- **InfluxDB**: A time-series database for storing metrics.
- **Chronograf**: A user interface for managing and visualizing data from InfluxDB.
- **cAdvisor**: Provides container-level metrics for Docker containers.
- **Grafana**: A visualization tool for creating dashboards to view metrics.


