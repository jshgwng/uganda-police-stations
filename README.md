# Uganda Police Stations Database
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview
This open source project aims to provide a comprehensive list of police stations in Uganda. The data is available in both JSON and SQL formats, making it easy to integrate into various applications and databases.

## Features
**JSON Format:** The data is provided in a JSON file, offering a simple and flexible structure for easy integration into your projects.

**SQL Script:** Additionally, a SQL script is included for those who prefer working with relational databases.
## Data Structure
The JSON file contains an array of objects, where each object represents a police station. The SQL script is designed to create a table with columns corresponding to relevant information about each police station.
```
[
  {
    "id": 1,
    "name": "Kampala Central Police Station",
  },
...
]
``````
## Usage
### JSON
To use the JSON data, simply incorporate the provided police_stations.json file into your project. You can parse the file and access the information as needed.

### SQL
For those working with databases, execute the police_stations.sql script to create a table named police_stations. You can then perform SQL queries to retrieve information about specific police stations.

```
SELECT * FROM police_stations WHERE id = '1';
```
## Contribution
Contributions are welcome! If you have additional information about police stations or would like to improve the existing data, feel free to submit a pull request. Please follow the contribution guidelines when contributing.

## License
This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/license/mit/) file for details.

## Acknowledgments
- [Uganda Police Website](https://www.upf.go.ug/all-police-counter-phone-contacts-countrywide/)
