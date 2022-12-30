# metric-beer-data

This repository holds the main data source for [metric.beer](https://metric.beer).
Any opening/closing inaccuracies should be reported or contributed here.
Any issues with the site itself should be reported to the respective project [here for the new version](https://github.com/richteer/metric-beer-rs), or [here for the old version](https://github.com/richteer/metric-beer).

## Contributing

### Corrections
If a brewery's hours have changed, feel free to either open an issue to report the change, or open a pull request with the change to `beer.json`.

This repository also happens to contain the data structures used by the [new version](https://github.com/richteer/metric-beer-rs) when parsing the JSON, so this repository will automatically check for valid input on opening a pull request.
If the check fails, please look at the output and make any adjustments.

### Requests
Requests for adding new breweries may be considered, but they are subject to my discretion.
I would like to keep the scope of this site to largely around the Metric Boulevard area (hence the name), but I am not opposed to accepting locations slightly out of the area (such as Beerworks).

### Code-related
I will consider any changes to the data structures or the testing infrastructure, but they must be done with consideration of the downstream projects.
Any changes to the data format will likely break the site projects, so any breaking changes should be combined with a fix to the frontends.