# List Faskes BPJS Indonesia Dataset

This dataset contains information about healthcare facilities (Faskes) registered with BPJS in Indonesia, including location, type, and other essential details.

## Dataset Information

| Variable Name | Description                                          | Type        | Missing Values |
| ------------- | ---------------------------------------------------- | ----------- | -------------- |
| NoLink        | Unique identifier for each transaction               | Categorical | No             |
| Provinsi      | Province name                                        | Categorical | No             |
| KotaKab       | City or Regency name                                 | Categorical | No             |
| Link          | Information link count                               | Integer     | No             |
| TipeFaskes    | Type of healthcare facility (e.g., Clinic, Hospital) | Categorical | No             |
| No            | Another unique identifier                            | Continuous  | No             |
| KodeFaskes    | Unique code for each healthcare facility             | Categorical | No             |
| NamaFaskes    | Name of the healthcare facility                      | Categorical | No             |
| LatLongFaskes | Latitude and longitude of the healthcare facility    | Categorical | No             |
| AlamatFaskes  | Full address of the healthcare facility              | Categorical | No             |
| TelpFaskes    | Contact number of the healthcare facility            | Categorical | No             |

## Usage

- **Exploratory Data Analysis (EDA)**: Understand the distribution of healthcare facilities across Indonesia, including types and locations.
- **Prediction**: Forecast areas in need of additional facilities based on existing data.

## Source

- [Kaggle: List Faskes BPJS Indonesia](https://www.kaggle.com/datasets/israhabibi/list-faskes-bpjs-indonesia)
