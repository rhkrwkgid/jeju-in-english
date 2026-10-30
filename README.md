# Jeju in English

A bilingual Jeju travel explorer powered by Korea Tourism Organization's English Tourism Information Service Open API.

## Features

- Switch the interface between Korean and English.
- Browse sample Jeju places immediately, or connect a newly issued API key to request live English tourism data.
- Search places and filter by category.
- Save places into a personal itinerary, remove them, and copy the itinerary.
- Open a place in Google Maps.

## Run

This is a buildless static app. Open `index.html` in a browser or host the repository with a static hosting service.

Select **Connect API / API 연결** and enter your newly issued service key to request live data for Jeju (area code `39`). The key is kept in the current browser tab's `sessionStorage` and is not included in this repository. Do not commit API keys. The API call is made directly from the browser, so a provider-side cross-origin (CORS) restriction may prevent live requests on some hosts.

## Data source

Korea Tourism Organization, English Tourism Information Service (GW), through the [Public Data Portal](https://www.data.go.kr/data/15101753/openapi.do).

Tourism information is supplied in English by the API; the Korean interface translates the app controls and built-in preview examples.

## License

No open-source license has been added. All rights reserved by default unless a license is added by the repository owner.
