# Call-Center-Data

## Overview


Data source: https://www.kaggle.com/datasets/satvicoder/call-center-data

## Metrics
Provided
- Average Waiting Time
- Service Level
- Incoming Calls
Derived
- Load Metric - Answered Calls × Average Talk Duration
- Abandonment Rate - Answered Calls ÷ Incoming Calls

## Key Findings
Load Metric represents the volume of work during a given index and provides a consistent way to describe facility work load on a given day. 

When service related metrics are evaluated against the Load Metric, clear patterns emerge.

Average Waiting Time, Service Level, and Abandonment Rate remain relatively stable and low across Load Metric values of 0.0 to 0.6. Between 0.7 and 0.9, performance begins to degrade, with notable increasing in Waiting Time and Abandonment Rate alongside declining Service Level. Beyond a Load Metric of 1.0, service related metrics have high variability with large fluctuations across all metrics.

Waiting Time increases earlier and more sharply than other service related metrics, making it an early indicator of emerging performance issues. Changes in waiting time appear before changes in Service Level and Abandonment Rate. This pattern suggests monitoring Load Metric alongside Waiting Time provides an early warning system for performance breakdown. 

As Load Metric increases, so does Average Incoming Calls. Average Incoming Calls increase steadily when evaluated with Load Metric in a seemingly linear relationship. It does not drastically change during Load Metrics of 0.7 to 0.9 or 1.0+. This indicates declining performance is a driven by service capacity overload rather than increases in demand. 

## Limitations


## Further Steps
