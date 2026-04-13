# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
I used the provided system metrics datasets comparing a reference period and a current period. The data includes requests, errors, and latency, which helped me analyze how system behavior changed over time.

### Signals
I created drift signals based on the differences between the reference and current averages. I also added an overall drift flag to make it easier to quickly see if the system is drifting.

### Experiments
I modified the thresholds to make the drift detection more sensitive and added a combined overall drift flag. I also created custom output files to separate my results from the original example.

### Results
The system flagged drift across all metrics, showing clear differences between the reference and current data. The custom outputs were successfully generated in the artifacts folder.

### Interpretation
This shows that the system performance has changed noticeably. As an analyst, this helps quickly identify when something needs attention instead of manually reviewing every metric.
