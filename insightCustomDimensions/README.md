* A single controller that receives HTTP requests
* A request filter similar to the one you have in your code using the @Order tag.
* Inside the filter, create your custom span and apply the filter as you currently do in your code.
* Collect a dummy custom property that is expected to be added to your request.
* Enable App Insights Java Agent 3.7.2
* Use the same applicationinsights.json file that you have on your current Application.
* Even if this dummy code does not reproduce the issue, it will help our engineering team to
  understand this scenario.

To Reproduce
Submitting a PR with an example reproducing the issue
in [this repository](https://github.com/microsoft/ApplicationInsights-Java-Repros) would make it
easier for the Application Insight maintainers to help you. Before doing this, you have to fork this
repository.