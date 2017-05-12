# Traffic Datasets for Cambridge, MA

Downloaded from the City of Cambridge's [open data portal](https://data.cambridgema.gov/browse) in March 2017. This repo contains most of the traffic datasets from the portal at the time.

Datasets+files include...
- [average_daily_traffic](https://data.cambridgema.gov/Traffic-Parking-and-Transportation/Average-Daily-Traffic-Counts-1972-to-2017/v43b-kqeq), 1972 - 2017
  - **WARNING:** Some cells are blank; not every year has data or AM/PM averages.
  - NOTE: Sanitized version contains geographic coordinates, max per row, min per row, and mean per row. **WARNING:** May need to add year label because it's possible not every year was in the original dataset.

- [commercial_parking](https://data.cambridgema.gov/Traffic-Parking-and-Transportation/Commercial-Parking/t8tm-muns)

- [intersections](https://data.cambridgema.gov/Traffic-Parking-and-Transportation/Intersections/8m9a-yuzk)
  - NOTE: Sanitized version contains only geographic coordinates.

- [metered_parking](https://data.cambridgema.gov/Traffic-Parking-and-Transportation/Metered-Parking-Spaces/6h7q-rwhf)
  - NOTE: Sanitized version contains only meter-ID's and geographic coordinates.

- [municipal_parking](https://data.cambridgema.gov/Traffic-Parking-and-Transportation/Municipal-Parking-Lots/27w3-catu)

- [parking_tickets_14_16](https://data.cambridgema.gov/Traffic-Parking-and-Transportation/Cambridge-Parking-Tickets-for-the-period-January-2/vnxa-cuyr), Jan 2014 - Jun 2016, (81 MB)
  - NOTE: Several sanitized versions.

.... `sanitized_parking_tickets.csv` contains only the geographic coordinates of every parking ticket in the original dataset.

.... the files labeled `sanitized_tickets-[VIOLATION TYPE].csv` contain the geographic coordinates of every parking ticket _of a particular type of violation_ from the original dataset. Where applicable, different violation types have been grouped together for similarity.

- [police_crash_data](https://data.cambridgema.gov/Public-Safety/Police-Department-Crash-Data-Historical/ybny-g9cv), Jan 2015 - Jan 2016
  - NOTE: Sanitized version contains only information from crashes involving two vehicles. Information includes geographic coordinates and the two vehicle types (e.g. auto, truck).

- [snow_emergency_tow_routes](https://data.cambridgema.gov/Traffic-Parking-and-Transportation/Snow-Emergency-Tow-Routes/c28n-xhxw)


## Look into...
 - [land use map](https://data.cambridgema.gov/Planning/Land-Use-Map/srp4-fhjz) - Do public buildings require more parking than residential areas?
 - [fire hydrants](https://data.cambridgema.gov/Geographic-Information-GIS-/Hydrants/szvy-s7ga) - Correlation with parking tickets?
 