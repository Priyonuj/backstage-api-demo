# backstage-api-demo

This repository contains the Backstage catalog integration and metadata for the `yaml2textdes` API.

## Overview

**yaml2textdes** is an API that converts YAML data to PlantUML images, enabling rapid diagram creation from configuration files.

- **API Endpoint**: [https://v-fn-001.azurewebsites.net/api/yaml2textdes](https://v-fn-001.azurewebsites.net/api/yaml2textdes)
- **Backstage Catalog Info**: See `catalog-info.yaml`

## Features

- Convert YAML directly to PlantUML diagrams.
- Integrate with Backstage for discoverability and monitoring.
- Easily extensible for other formats and diagram types.

## Usage

1. Send YAML data to the API endpoint via POST request.
2. Receive a PlantUML image URL or content in response.

**Example request:**
```bash
curl -X POST \
  -H "Content-Type: application/x-yaml" \
  --data-binary "@yourfile.yaml" \
  https://v-fn-001.azurewebsites.net/api/yaml2textdes
```

## Backstage Integration

- The `catalog-info.yaml` file describes the API's metadata and is used for discovery in Backstage.
- Annotations enable Lighthouse performance monitoring and technical documentation.

## Contributing

Contributions, issues and feature requests are welcome!  
Feel free to check [issues page](https://github.com/Priyonuj/backstage-api-demo/issues).

## License

This project is [MIT licensed](LICENSE).

---

**Owner:** Priyonuj Dey  
**Location:** Rajpur Sonarpur, WB
