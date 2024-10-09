# Elasticsearch Profile Flame Graph

[![GitHub License](https://img.shields.io/github/license/sezaakgun/elasticsearch-profile-flame-graph)](https://github.com/sezaakgun/elasticsearch-profile-flame-graph/blob/main/LICENSE)

## Overview

Elasticsearch Profile Flame Graph is a tool designed to visualize Elasticsearch query performance using flame graphs. This project enables users to gain deeper insights into Elasticsearch profiling data, helping identify bottlenecks and optimize query performance effectively.

## Example

Here is a simple example of using the tool:

1. Profile a sample query in Elasticsearch:

```json
{
  "profile": true,
  "query": {
    "match": {
      "field": "value"
    }
  }
}
```

2. Copy the profiling result.

3. Open the HTML page provided in this repository, paste the profiling result, and analyze the query performance.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the GPL-3.0 License. See the [LICENSE](https://github.com/sezaakgun/elasticsearch-profile-flame-graph/blob/main/LICENSE) file for more details.

## Contact

- GitHub: [@sezaakgun](https://github.com/sezaakgun)
