# Rideau Canal Dashboard API Documentation

` / `

- The main path of the application which serves thr dashboard

`/health`

- Used to health check the endpoint to ensure database is connected properly

`api/latest`

- This API endpoint gets the latest readings for all locations

`/api/history/:location`

- This API endpoint gets the historical data for the specified location

`/api/status`

- This API endpoint checks the status of the system to see if the ice is safe or not

`/api/all`

- This API endpoint retrieves and displays all data and is primarily used for debugging