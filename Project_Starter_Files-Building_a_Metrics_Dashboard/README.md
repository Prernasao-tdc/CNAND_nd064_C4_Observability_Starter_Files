**Note:** For the screenshots, you can store all of your answer images in the `answer-img` directory.

## Verify the monitoring installation

Action: Run the command kubectl get pods --namespace monitoring and kubectl get services --namespace monitoring to show the running pods and services.

## Setup the Jaeger and Prometheus source
Action: Expose Grafana using kubectl port-forward service/grafana --namespace monitoring 3000:80.
Setup: Log into Grafana and configure Prometheus as a data source.

## Create a Basic Dashboard
Action: Create a dashboard in Grafana that uses Prometheus as a data source.

## Describe SLO/SLI
Description: Write a brief explanation of SLIs (Service Level Indicators) based on an SLO (Service Level Objective) of monthly uptime and request response time.

## Creating SLI metrics.
Action: Describe five metrics that are important for measuring SLIs.

## Create a Dashboard to measure our SLIs
Action: Create a dashboard in Grafana that measures uptime and error rates (e.g., 40x and 50x errors) over a 24-hour period.

## Tracing our Flask App
Action: Create a Jaeger span in your Flask app to measure backend processes.e.

## Jaeger in Dashboards
Action: Add the Jaeger metrics to your Grafana dashboard.
## Report Error
Trouble Ticket Template: Fill out the trouble ticket with relevant details about the errors you are encountering.

TROUBLE TICKET

Name:

Date:

Subject:

Affected Area:

Severity:

Description:


## Creating SLIs and SLOs
Action: Name four SLIs that would measure the success of the SLO guaranteeing 99.95% uptime.

## Building KPIs for our plan
Action: Create a list of 2-3 KPIs that accurately measure the SLIs and SLOs.

## Final Dashboard
Action: Create a list of 2-3 KPIs that accurately measure the SLIs and SLOs.