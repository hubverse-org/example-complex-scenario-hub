# Target data

This folder could be used to store target data (ground truth) relevant to the 
modeling efforts, following the recommended [target data guidelines in our documentation](https://hubdocs.readthedocs.io/en/latest/format/target-data.html).

In this repository, we use different examples files:

## US level target data (file name starting with `"US_"`)

We use the daily reports containing COVID-19 cases and deaths data from the 
[JHU CSSE group](https://coronavirus.jhu.edu/map.html) as reference data for 
cases and deaths in the US. We use the distribution of the JHU data as provided 
by the 
[COVIDcast Epidata API](https://cmu-delphi.github.io/delphi-epidata/api/covidcast-signals/jhu-csse.html)
maintained by the [Delphi Research Group](https://delphi.cmu.edu/about/)
at Carnegie Mellon University.

For hospitalization, we use the COVID-19 hospitalization data from the HHS for 
example the 
[HealthData.gov COVID-19 Reported Patient Impact and Hospital Capacity by State Timeseries](https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/g62h-syeh)
and 
[HealthData.gov COVID-19 Reported Patient Impact and Hospital Capacity byState](https://healthdata.gov/dataset/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/6xf2-c3ie).
We will use the distribution of the HHS data as provided by the
[COVIDcast Epidata API](https://cmu-delphi.github.io/delphi-epidata/api/covidcast-signals/hhs.html)
maintained by the [Delphi Research Group](https://delphi.cmu.edu/about/)
at Carnegie Mellon University

## European country level target data (file name starting with `"euro_"`)

We use the COVID-19 case and death incidence data from the 
[European COVID-19 Forecast Hub](https://github.com/covid19-forecast-hub-europe/covid19-forecast-hub-europe/tree/main/data-truth) and from the 
[JHU CSSE group](https://coronavirus.jhu.edu/map.html)

