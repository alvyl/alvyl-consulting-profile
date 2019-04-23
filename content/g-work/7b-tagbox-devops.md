+++
title = "Tagbox Devops"
date = 2019-04-22T15:02:43+05:30
weight = 8
draft = true
+++

- We helped scale Tagbox's Big-Data Analytics platform infrastructure to be able to support 
    - 5O,OOO edge node sensors collecting one telemetry data poirrt every 1 minute (Typical Sample Data Rate (TSDR))
    - Data from these sensors is collected and relayed to the backend via 500 gateway devices in burst mode.
    - The analyzed and raw information collected from sensors will be consumed by 1000+ users at any given instant of time.

**Technologies/Tools:** Terraform, Azure, Docker, Airflow, Kubernetes