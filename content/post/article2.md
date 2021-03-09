---
title: "International Trade"
date: 2021-02-28
---

# US International Trade
International Trade time series plot. This graph shows US export and import from 1929 to 2020.

{{< figure src="/images/us/ei.svg">}}

# Nepal International Trade
International Trade time series plot. This graph shows export import from 2000 to 2020.
{{< figure src="/images/np/ei.svg">}}


{{< chart  >}}
{
    type: 'line',
    data: {
        labels: [2000, 2001, 2002, 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019],
        datasets: [{
            label: 'Export',
            data: [99.61019999999999, 81.4917, 77.2796, 89.5442, 85.958, 87.9521, 93.5673, 104.2072, 122.73689999999999, 114.298, 121.714, 153.86329999999998, 181.1803, 226.02179999999998, 247.56470000000002, 213.33848, 240.39237, 271.21705, 299.81853, 301.69018],
            borderWidth: 1,
            borderColor: "#3e95cd",
            fill: false
        },{
            label: 'Import',
            data: [146.7574, 130.9118, 140.5222, 158.1509, 173.7543, 204.828, 230.89329999999998, 271.2909, 342.5358, 434.19829999999996, 450.0585, 512.9476, 634.8993, 800.5523000000001, 883.4439, 885.1110699999999, 1133.3193, 1406.06823, 1599.95534, 1508.98228],
            borderWidth: 1,
            borderColor: "#8e5ea2",
            fill: false
        }
        ]
    },
   options: {
    title: {
      display: true,
      text: 'Export and Import in Rs. Billions'
    }
  }
}
{{< /chart >}}