# data-governance-frontend
Frontend for the Data Governance component

# certh-dataports-frontend-data_governance_use_case

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.12.

## Serve

You have to serve this dist folder with a server. For example, using Node server you can run `http-server          dist/DataPorts --p 8090` and then you can view the frontend component running at `http://localhost:8090`. 

## Integration with backend

The frontend component calls backend endpoints from base url `http://localhost:9999`. If you want to run backend component at another port (e.g. 8080), you can replace all `http://localhost:9999` with `http://localhost:8080`.
