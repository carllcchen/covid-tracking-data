## Data Backups

**Do not use this repository to download or display data**. Use the [COVID Tracking API](https://covidtracking.com/api) instead.

---

This folder contains CSV and JSON data backups from the [Covid Tracking API](https://covidtracking.com/api) as well as several federal data files, from the CDC and the HHS. These are the sources for the federal data in this folder (note that they are not direct download links, they're meant to give context instead):

### HHS

- COVID-19 Reported Patient Impact and Hospital Capacity by State: https://healthdata.gov/dataset/covid-19-reported-patient-impact-and-hospital-capacity-state
- COVID-19 Reported Patient Impact and Hospital Capacity by State Timeseries: https://healthdata.gov/dataset/covid-19-reported-patient-impact-and-hospital-capacity-state-timeseries
- COVID-19 Diagnostic Laboratory Testing (PCR Testing) Time Series: https://healthdata.gov/dataset/covid-19-diagnostic-laboratory-testing-pcr-testing-time-series
- COVID-19 Estimated Patient Impact and Hospital Capacity by State: https://healthdata.gov/dataset/covid-19-estimated-patient-impact-and-hospital-capacity-state (3 files)

Note that these files are saved as they are released, with the filename being generated by HHS (not by us) - it generally reflects the time of release. These files are all getting backed up to the [HHS subdirectory here](https://github.com/COVID19Tracking/covid-tracking-data/tree/master/data/hhs).

### CDC

The following files are getting stored under the same file in this repo, so to see changes, you will need to view the history:
- COVID-19 Cases and Deaths by State Over Time: https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36, saved to [this file](https://github.com/COVID19Tracking/covid-tracking-data/blob/master/data/cdc_cases_deaths.csv)
- COVID-19 County-level data: https://covid.cdc.gov/covid-data-tracker/#county-view, saved to [this file](https://github.com/COVID19Tracking/covid-tracking-data/blob/master/data/cdc_counties.csv)

We have saved, but are no longer updating, older CDC case, testing and deaths data. To see how these files had changed in the past, see the GitHub history as follows:
- https://github.com/COVID19Tracking/covid-tracking-data/commits/master/data/cdc.csv
- https://github.com/COVID19Tracking/covid-tracking-data/commits/master/data/cdc_testing.json
- https://github.com/COVID19Tracking/covid-tracking-data/commits/master/data/cdc_trend.json

### FDA

- FDA's reported EUA information about In Vitro Diagnostic Products:
  https://www.fda.gov/emergency-preparedness-and-response/mcm-legal-regulatory-and-policy-framework/emergency-use-authorization#covidinvitrodev,
  saved each day to [this file](https://github.com/COVID19Tracking/covid-tracking-data/blob/master/data/fda-covid-ivd-euas.csv)

### LTC
- Nevada long-term care facility data, scraped from 
[their dashboard](https://app.powerbigov.us/view?r=eyJrIjoiNDMwMDI0YmQtNmUyYS00ZmFjLWI0MGItZDM0OTY1Y2Y0YzNhIiwidCI6ImU0YTM0MGU2LWI4OWUtNGU2OC04ZWFhLTE1NDRkMjcwMzk4MCJ9) 
and saved to [ltc_nv.csv](https://github.com/COVID19Tracking/covid-tracking-data/blob/master/data/ltc_nv.csv)

- West Virginia long-term care facility data, scraped from 
[their dashboard](https://dhhr.wv.gov/COVID-19/Pages/default.aspx) (Long-Term Care tab)
and saved to [ltc_wv.csv](https://github.com/COVID19Tracking/covid-tracking-data/blob/master/data/ltc_wv.csv)
