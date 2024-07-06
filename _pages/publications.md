---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            font-family: Arial, sans-serif;
        }
        .stats-table {
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        .stats-table th, .stats-table td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: center;
        }
        .stats-table th {
            background-color: #f2f2f2;
        }
        .bar-chart {
            position: relative;
            width: 500px;
            height: 200px;
        }
        .bar {
            position: absolute;
            bottom: 0;
            width: 40px;
            background-color: gray;
        }
        .bar span {
            position: absolute;
            bottom: 100%;
            width: 100%;
            text-align: center;
            font-size: 12px;
        }
        .y-axis {
            position: absolute;
            left: 0;
            bottom: 0;
            height: 100%;
            width: 30px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .y-axis div {
            font-size: 12px;
            text-align: right;
        }
        .x-axis {
            position: absolute;
            bottom: -20px;
            width: 100%;
            display: flex;
            justify-content: space-between;
        }
        .x-axis div {
            font-size: 12px;
            text-align: center;
        }
    </style>
</head>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bar Chart with Chart.js</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        .container {
            width: 60%;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <canvas id="myChart"></canvas>
    </div>

    <script>
        const ctx = document.getElementById('myChart').getContext('2d');
        const myChart = new Chart(ctx, {
            type: 'bar',
            data: {
                labels: ['2018', '2019', '2020', '2021', '2022', '2023', '2024'],
                datasets: [{
                    label: 'Citations',
                    data: [44, 151, 2749, 2540, 2045, 2346, 1655],
                    backgroundColor: 'gray',
                    borderColor: 'gray',
                    borderWidth: 1
                }]
            },
            options: {
                scales: {
                    y: {
                        beginAtZero: true,
                        max: 2800,
                        ticks: {
                            stepSize: 700
                        }
                    }
                },
                plugins: {
                    legend: {
                        display: false
                    },
                    tooltip: {
                        callbacks: {
                            label: function(context) {
                                return context.raw;
                            }
                        }
                    }
                }
            }
        });
    </script>
</body>
</html>




### •  ***Peer-reviewed Journal Articles***

### 2024

- Son, J. Y., Heo, S., Byun, G., Foo, D., **Song, Y.**, Lewis, B.M., Stewart, R., Choi, H. M., Bell, M.L. (2024). A systematic review of animal feeding operations including concentrated animal feeding operations (CAFOs) for exposure, health outcomes, and environmental justice. <span style="color: darkblue;">*Environmental Research*</span>, 119550. <a href="https://doi.org/10.1016/j.envres.2024.119550" target="_blank">Link</a>
- **Song, Y.**<sup>\*</sup>, Wu, S., Chen, B., & Bell, M. L. (2024). Unraveling near real-time spatial dynamics of population using geographical ensemble learning. <span style="color: darkblue;">*International Journal of Applied Earth Observation and Geoinformation*</span>, *130*, 103882. <a href="https://doi.org/10.1016/j.jag.2024.103882" target="_blank">Link</a>
- Ferrari, A. J., Santomauro, D. F., Aali, A., ...**Song, Y.**, ... Vos, T., & Murray, C. J. L. (2024). Global incidence, prevalence, years lived with disability (YLDs), disability-adjusted life-years (DALYs), and healthy life expectancy (HALE) for 371 diseases and injuries in 204 countries and territories and 811 subnational locations, 1990–2021: a systematic analysis for the Global Burden of Disease Study 2021. <span style="color: darkblue;">*The Lancet*</span>, *403*(10440), 2133-2161. <a href="https://doi.org/10.1016/S0140-6736(24)00757-8" target="_blank">Link</a>
- Naghavi, M., Ong, K. L., Aali, A., ... **Song, Y.**, ... Wool, E. E. & Murray, C. J. L. (2024). Global burden of 288 causes of death and life expectancy decomposition in 204 countries and territories and 811 subnational locations, 1990–2021: a systematic analysis for the Global Burden of Disease Study 2021. <span style="color: darkblue;">*The Lancet*</span>, *403*(10440), 2100-2132. <a href="https://doi.org/10.1016/S0140-6736(24)00367-2" target="_blank">Link</a>
- Bhattacharjee, N. V., Schumacher, A. E., Aali, A., ... **Song, Y.**, ... Murray, C. J. L., Smith, A. E., & Vollset, S. E. (2024). Global fertility in 204 countries and territories, 1950–2021, with forecasts to 2100: a comprehensive demographic analysis for the Global Burden of Disease Study 2021. <span style="color: darkblue;">*The Lancet*</span>, *403*(10440), 2057-2099. <a href="https://doi.org/10.1016/S0140-6736(24)00550-6" target="_blank">Link</a>
- Schumacher, A. E., Kyu, H. H., Aali, A., ... **Song, Y.**, ... Lim, S. S. &, Murray, C. J. L. (2024). Global age-sex-specific mortality, life expectancy, and population estimates in 204 countries and territories and 811 subnational locations, 1950–2021, and the impact of the COVID-19 pandemic: a comprehensive demographic analysis for the Global Burden of Disease Study 2021. <span style="color: darkblue;">*The Lancet*</span>, *403*(10440), 1989-2056. <a href="https://doi.org/10.1016/S0140-6736(24)00476-8" target="_blank">Link</a>
- Wang, R., **Song, Y.**, Yang, L., & Browning, M. H. (2024). Neighbourhood green space and loneliness in middle-aged and older adults: Evidence from WHO Study on Global Ageing and Adult Health in China. <span style="color: darkblue;">*Urban Forestry & Urban Greening*</span>, *95*, 128324. <a href="https://doi.org/10.1016/j.ufug.2024.128324" target="_blank">Link</a>
- Steinmetz, J. D., Seeher, K. M., Schiess, N., ... **Song, Y.**, ... Ong, K. L., Valery L Feigin, V. L., Vos, T., & Dua, T. (2024). Global, regional, and national burden of disorders affecting the nervous system, 1990–2021: a systematic analysis for the Global Burden of Disease Study 2021. <span style="color: darkblue;">*The Lancet Neurology*</span>, *23*(4), 344-381. <a href="https://doi.org/10.1016/S1474-4422(24)00038-3" target="_blank">Link</a>
- Chen, B., Wu, S., Jin, Y., **Song, Y.**, Wu, C., Venevsky, S., Xu, B., Webster, C., & Gong P. (2024). Wildfire risk for global wildland–urban interface (WUI) areas. <span style="color: darkblue;">*Nature Sustainability*</span>, *7*, 474–484. <a href="https://doi.org/10.1038/s41893-024-01291-0" target="_blank">Link</a>

### 2023

- Foo, D., Heo, S., Dhamrait, G., Stewart, R., Choi, H. M., **Song, Y.**, & Bell, M. L. (2023). Wildfire smoke exposure during pregnancy and adverse perinatal, obstetric, and early childhood health outcom: a systematic review and meta-analysis. <span style="color: darkblue;">*Environmental Research*</span>, 117527. <a href="https://doi.org/10.1016/j.envres.2023.117527" target="_blank">Link</a>
- He, Q., Ye, T., Wang, W., Luo, M., **Song, Y.**, & Zhang, M. (2023). Spatiotemporally continuous estimates of daily 1-km PM2. 5 concentrations and their long-term exposure in China from 2000 to 2020. <span style="color: darkblue;">*Journal of Environmental Management*</span>, *342*, 118145. <a href="https://doi.org/10.1016/j.jenvman.2023.118145" target="_blank">Link</a>
- Liu, D., Kwan, M. P., Kan, Z., **Song, Y.**, & Li, X. (2022). Racial/Ethnic Inequity in Transit-Based Spatial Accessibility to COVID-19 Vaccination Sites. <span style="color: darkblue;">*Journal of Racial and Ethnic Health Disparities*</span>, *10*, 1533–1541. <a href="https://doi.org/10.1007/s40615-022-01339-x" target="_blank">Link</a>
- Tu, Y., Chen, B., Yu, L., **Song, Y.**, Wu, S., Li, M., Wei, H., Chen, T., Lang, W., Gong, P. & Xu, B. (2023). Raveling the nexus between urban expansion and cropland loss in China. <span style="color: darkblue;">*Landscape Ecology*</span>, *38*, 1869-1884. <a href="https://doi.org/10.1007/s10980-023-01653-7" target="_blank">Link</a>
- Ho, H.C., **Song, Y.**, Cheng, W., Liu, Y., Guo, Y., Lu, S., Lum, T., Chiu, R.L.H., & Webster. C. (2023). How do forms and characteristics of Asian public housing neighbourhoods affect dementia risk among senior population? A cross-sectional study in Hong Kong. <span style="color: darkblue;">*Public Health*</span>, *219*, 44-52. <a href="https://doi.org/10.1016/j.puhe.2023.03.014" target="_blank">Link</a>
- Liu, Y., Guo, Y., Lu, S., Chan, O. F., Chui, C., Ho, H. C., **Song, Y.**, Cheng, W., Chiu, R. L. H., Webster, C., & Lum, T. Y. (2023). Understanding the long-term effects of public open space on older adults’ functional ability and mental health. <span style="color: darkblue;">*Building and Environment*</span>, *234*, 110126. <a href="https://doi.org/10.1016/j.buildenv.2023.110126" target="_blank">Link</a>
- Chan, O. F., Liu, Y., Guo, Y., Lu, S., Chui, H. K,. Ho, H. C., **Song, Y.**, Cheng, W., Chiu, L. H., & Webster, C. (2022). Neighborhood built environments and cognition in later life. <span style="color: darkblue;">*Aging & Mental Health*</span>, *27*(3), 466-474. <a href="https://doi.org/10.1080/13607863.2022.2046697" target="_blank">Link</a>
- Jin, Y., So, H., Cerin, E., ... **Song, Y.**, Tam, L., & Wu, D. (2023). The temporal trend of disease burden attributable to metabolic risk factors in China, 1990–2019: An analysis of the Global Burden of Disease study. <span style="color: darkblue;">*Frontiers in Nutrition*</span>, *9*, 1035439. <a href="https://doi.org/10.1016/j.envres.2021.111974" target="_blank">Link</a>
- He, Q., Wang, W., **Song, Y.**, Zhang, M., & Huang, B. (2023). Spatiotemporal high-resolution imputation modeling of aerosol optical depth for investigating its full-coverage variation in China from 2003 to 2020. <span style="color: darkblue;">*Atmospheric Research*</span>, *281*, 106481. <a href="https://doi.org/10.1016/j.atmosres.2022.106481" target="_blank">Link</a>

### 2022

- Ikuta, K. S., Swetschinski, L. R., Aguilar, G. R., ... **Song, Y.**, ... Murray, C. J. L. N. & Mohsen N. (2022). Global mortality associated with 33 bacterial pathogens in 2019: a systematic analysis for the Global Burden of Disease Study 2019. <span style="color: darkblue;">*The Lancet*</span>, *400*(10369), 2221-2248. <a href="https://doi.org/10.1016/S0140-6736(22)02185-7" target="_blank">Link</a>
- **Song, Y.** <sup>\*</sup>, Xu Y., Chen, B., He, Q., Tu, Y., Wang, F., & Cai, C. (2022). Dynamic population mapping with AutoGluon. <span style="color: darkblue;">*Urban Informatics*</span>, *1*(1), 13. <a href="https://doi.org/10.1007/s44212-022-00017-x" target="_blank">Link</a>
- Kyu, H. H., Vongpradith, A., Sirota, S. B., ... **Song, Y.**, ... & Murray, C. J. L. (2022). Age–sex differences in the global burden of lower respiratory infections and risk factors, 1990–2019: results from the Global Burden of Disease Study 2019. <span style="color: darkblue;">*The Lancet Infectious Diseases*</span>, *22*(11), 1626-1647. <a href="https://doi.org/10.1016/S1473-3099(22)00510-2" target="_blank">Link</a>
- Tran, K. B., Lang, J. J., Compton, K., … **Song, Y.**, ... Force, L. M., & Murray, C. J. L. (2022). The global burden of cancer attributable to risk factors, 2010–19: a systematic analysis for the Global Burden of Disease Study 2019. <span style="color: darkblue;">*The Lancet*</span>, *400*(10352), 563-591. <a href="https://doi.org/10.1016/S0140-6736(22)01438-6" target="_blank">Link</a>
- Chen, B., Wu, S., **Song, Y.**, Webster, C., Xu, B., & Gong, P. (2022). Contrasting inequality in human exposure to greenspace between cities of Global North and Global South. <span style="color: darkblue;">*Nature Communications*</span>, *13*, 4636. <a href="https://doi.org/10.1038/s41467-022-32258-4" target="_blank">Link</a>
- Ho, H. C., Cheng, W., **Song, Y.**, Liu, Y., Guo, Y., Lu, S., Lum, T. Y., Chiu, R., & Webster, C. (2022). Spatial uncertainty and environment-health association: An empirical study of osteoporosis among “old residents” in public housing estates across a hilly environment. <span style="color: darkblue;">*Social Science & Medicine*</span>, *306*, 115155. <a href="https://doi.org/10.1016/j.socscimed.2022.115155" target="_blank">Link</a>
- Chen, B., Tu, Y., Wu, S., **Song, Y.**, Jin, Y., Webster, C., Xu, B., & Gong, P. (2022). Beyond green environments: multi-scale difference in human exposure to greenspace in China. <span style="color: darkblue;">*Environment International*</span>, *166*, 107348. <a href="https://doi.org/10.1016/j.envint.2022.107348" target="_blank">Link</a>
- Bryazka, D., Reitsma, M. B., Griswold, M. G., ... **Song, Y.**, ... & Gakidou, E. (2022). Population-level risks of alcohol consumption by amount, geography, age, sex, and year: a systematic analysis for the Global Burden of Disease Study 2020. <span style="color: darkblue;">*The Lancet*</span>, *400*(10347), 185-235. <a href="https://doi.org/10.1016/S0140-6736(22)00847-9" target="_blank">Link</a>
- Liu, D., Kwan, M. P., Kan, Z., **Song, Y.**, & Li, X. (2022). Inter- and intra-racial/ethnic disparities in walking accessibility to grocery stores. <span style="color: darkblue;">*Area*</span>, *54*(4), 627-637. <a href="https://doi.org/10.1111/area.12796" target="_blank">Link</a>
- He, D., Miao, J., Lu, Y., **Song, Y.**, Chen, L., & Liu, Y. (2022). Urban greenery mitigates the negative effect of urban density on older adults' life satisfaction: Evidence from Shanghai, China. <span style="color: darkblue;">*Cities*</span>, *124*, 103607. <a href="https://doi.org/10.1016/j.cities.2022.103607" target="_blank">Link</a>
- Liu, D., Kwan, M. P., Huang, J., Kan, Z., **Song, Y.**, & Li, X. (2022). Analyzing income-based inequality in transit nodal accessibility. <span style="color: darkblue;">*Travel Behaviour and Society*</span>, *27*, 57-64. <a href="https://doi.org/10.1016/j.tbs.2021.11.005" target="_blank">Link</a>
- Cong, J., Wang, L. B., Liu, F. J., Qian, Z., McMillin, S. E., Vaughn, M. G., **Song, Y.**, Wang, S., Chen, S., Xiong, S., Shen, X., Sun, X., Zhou, Y., Ho, H. C., & Dong. G. H. (2022). Associations between metabolic syndrome and anthropogenic heat emissions in northeastern China. <span style="color: darkblue;">*Environmental Research*</span>, *204*, 111974. <a href="https://doi.org/10.1016/j.envres.2021.111974" target="_blank">Link</a>
- Long, Y., **Song, Y.**<sup>\*</sup>, & Chen, L.<sup>\*</sup> (2022). Identifying subcenters with a nonparametric method and ubiquitous point-of-interest data: A case study of 284 Chinese cities. <span style="color: darkblue;">*Environment and Planning B: Urban Analytics and City Science*</span>, *49*(1), 58-75. <a href="https://doi.org/10.1177/2399808321996705" target="_blank">Link</a>

### **2021**

- Lu, S., Liu, Y., Guo, Y., Ho, H. C., **Song, Y.**, Cheng, W., Chui, C., Chan, O., Chiu, R. L. H., Webster, C., & Lum, T. Y. (2021). Neighborhood built environment and late-life depression: a multilevel path analysis in a Chinese society. <span style="color: darkblue;">*The Journals of Gerontology: Series B*</span>, *76*(10), 2143-2154. <a href="https://doi.org/10.1093/geronb/gbab037" target="_blank">Link</a>
- **Song, Y.**, Chen, B., Ho, C., H., Kwan, M. P., Liu, D., Wang, J., Cai, J., Li, X., Xu, Y., He, Q., Wang, H., Xu, Q., & Song, Y. (2021). Observed inequality in urban greenspace exposure in China. <span style="color: darkblue;">*Environment International*</span>, *156*, 106778. <a href="https://doi.org/10.1016/j.envint.2021.106778" target="_blank">Link</a>
- He, Q., Gao, K., Zhang, L., **Song, Y.**, & Zhang, M. (2021). Satellite-derived 1-km estimates and long-term trends of PMconcentrations in China from 2000 to 2018. <span style="color: darkblue;">*Environment International*</span>, *156,* 106726. <a href="https://doi.org/10.1016/j.envint.2021.106726" target="_blank">Link</a>
- Zhang, Y., Wei J., Shi Y., Quan C., Ho, H. C., **Song, Y.**, & Zhang, L. (2021). Early-life exposure to submicron particulate air pollution in relation to asthma development in Chinese preschool children. <span style="color: darkblue;">*Journal of Allergy and Clinical Immunology*</span>, *148(3)*, 771-782. <a href="https://doi.org/10.1016/j.jaci.2021.02.030" target="_blank">Link</a>
- Chen, B., Tu, Y., **Song, Y.**, Theobald, D., Zhang, T., Ren, Z., Li, X., Yang, J., Wang, J., Wang, X., Gong, P., Bai, Y., & Xu, B. (2021). Mapping essential urban land use categories with open big data: Results for five metropolitan areas in the United States of America. <span style="color: darkblue;">*ISPRS Journal of Photogrammetry and Remote Sensing*</span>, *178*, 203-218. <a href="https://doi.org/10.1016/j.isprsjprs.2021.06.010" target="_blank">Link</a>
- Liu, Y., Lu, S., Guo, Y., Ho, H. C., **Song, Y.**, Cheng, W., Hiu, C., Chui, K., Chan, O., Chiu, R. L. H., Webster, C., & Lum, T. Y. (2021). Longitudinal associations between neighbourhood physical environments and depressive symptoms of older adults in Hong Kong: The moderating effects of terrain slope and declining functional abilities. <span style="color: darkblue;">*Health & Place*</span>, *70*, 102585. <a href="https://doi.org/10.1016/j.healthplace.2021.102585" target="_blank">Link</a>
- Wu, W., Yao, Y., **Song, Y.**, He, D., & Wang, Y. (2021). Perceived influence of street-level visible greenness exposure in the work and residential environment on life satisfaction: Evidence from China. <span style="color: darkblue;">*Urban Forestry & Urban Greening*</span>, *62*, 127161. <a href="https://doi.org/10.1016/j.ufug.2021.127161" target="_blank">Link</a>
- Wang, X., Xu, Z., Su, H., Ho, H. C., **Song, Y.**, Zheng, H., Hossain, M., Z., Khan, M., F., Bogale, F., Wei, J., & Cheng, J. (2021). Ambient particulate matter (PM, PM, PM) and childhood pneumonia: The smaller particle, the greater short-term impact? <span style="color: darkblue;">*Science of the Total Environment*</span>, *772*, 145509. <a href="https://doi.org/10.1016/j.scitotenv.2021.145509" target="_blank">Link</a>
- Lu, S., Liu, Y., Guo, Y., Ho, H. C., **Song, Y.**, Cheng, W., Chui, C., Chan, O. F., Webster, C., Lai, R., Chiu, H., & Lum, T. Y. (2021). Neighbourhood physical environment, intrinsic capacity, and 4-year late-life functional ability trajectories of low-income Chinese older population: A longitudinal study with the parallel process of latent growth curve modelling. <span style="color: darkblue;">*EClinicalMedicine*</span>, *36*, 100927. <a href="https://doi.org/10.1016/j.eclinm.2021.100927" target="_blank">Link</a>
- Xu, Y., **Song, Y.**<sup>\*</sup>, Cai, J., & Zhu, H.<sup>\*</sup> (2021). Population mapping in China with social user and remote sensing data. <span style="color: darkblue;">*Applied Geography*</span>, *130*, 102450. <a href="https://doi.org/10.1016/j.apgeog.2021.102450" target="_blank">Link</a>
- He, Q., Zhang, M., **Song, Y.**, & Huang, B. (2021). Spatiotemporal assessment of PM2.5 concentrations and exposure in China from 2013 to 2017 using satellite-derived data. <span style="color: darkblue;">*Journal of Cleaner Production*</span>, *286*, 124965. <a href="https://doi.org/10.1016/j.jclepro.2020.124965" target="_blank">Link</a>
- Guo, H., Wei, J., Li. X., Ho, H. C., **Song, Y.**, Wu, J., & Li, W. (2021). Do socioeconomic factors modify the effects of PM and SO on lung cancer incidence in China? <span style="color: darkblue;">*Science of the Total Environment*</span>, *756*, 143998. <a href="https://doi.org/10.1016/j.scitotenv.2020.143998" target="_blank">Link</a>
- Liu, D., Kwan, M. P., Kan, Z. & **Song, Y.** (2021). An integrated analysis of housing and transit affordability in the Chicago metropolitan area. <span style="color: darkblue;">*The Geographical Journal*</span>, *187*(2), 110-126. <a href="https://doi.org/10.1111/geoj.12377" target="_blank">Link</a>
- Liu, L, Song, F., Fang, J., Wei, J., Ho, H. C., **Song, Y.**, Zhang, Y., Wang, L., Hu, C., & Zhang. Y. (2021). Intraday effects of ambient PM on emergency department visits in Guangzhou, China: a case-crossover study. <span style="color: darkblue;">*Science of the Total Environment*</span>, *750*, 142347. <a href="https://doi.org/10.1016/j.scitotenv.2020.142347" target="_blank">Link</a>

### **2020**

- Tian, H., Liu, Y., Li, Y., Wu, C., Chen, B., Kraemer, M., Li, B., Cai, J., Xu, B., Yang, Q., Wang, B., Yang, P., Cui, Y., **Song, Y.**, Zheng, P., Wang, Q., Bjornstad, O., Yang, R., Grenfell, B., Pybus, O., & Dye, C. (2020). An investigation of transmission control measures during the first 50 days of the COVID-19 epidemic in China. <span style="color: darkblue;">*Science*</span>, *368*(6491), 638-642. <a href="https://doi.org/10.1126/science.abb6105" target="_blank">Link</a>
- Chen, B.<sup>\#</sup>, **Song, Y.**<sup>\#</sup>, Huang, B., & Xu, B. (2020). A novel method to extract urban human settlements by integrating remote sensing and mobile phone locations. <span style="color: darkblue;">*Science of Remote Sensing*</span>, *1,* 100003. <a href="https://doi.org/10.1016/j.srs.2020.100003" target="_blank">Link</a>
- Li, R., Pei, S., Chen, B., **Song, Y.**, Zhang, T., Yang, W., & Shaman, J. (2020). Substantial undocumented infection facilitates the rapid dissemination of novel coronavirus (SARS-CoV-2). <span style="color: darkblue;">*Science*</span>, *368*(6490), 489-493. <a href="https://doi.org/10.1126/science.abb3221" target="_blank">Link</a>
- Li, R., Chen, B, Zhang, T., Ren, Z., **Song, Y.**, Xiao, Y., Hou, L., Cai, J., Xu, B., Chan, K. K. Y., Tu, Y., Yang, J., Liu, Z., Shen, C., Wang, C., Xu, L., Liu, Q., Bao, S., Zhang, J., Bai, Y., Deng, K., Zhang, W., Huang, W., Whittington, J. D., Stenseth, N. C., Guan, D., Gong, P., & Xu, B. (2020). Global COVID-19 pandemic demands joint interventions for the suppression of future waves. <span style="color: darkblue;">*Proceedings of the National Academy of Sciences*</span>, *117*(42), 26151-26157. <a href="https://doi.org/10.1073/pnas.2012002117" target="_blank">Link</a>
- Wei, J., Li, Z., Huang, W., Xue, W., Sun, L., Guo, J., Peng, Y., Li, J., Lyapustine, A, Liu, L., Wu, H., & **Song, Y.** (2020). Improved 1 km resolution PM2.5 estimates across China using enhanced space–time extremely randomized trees. <span style="color: darkblue;">*Atmospheric Chemistry and Physics*</span>, *20*(6), 3273-3289. <a href="https://doi.org/10.5194/acp-20-3273-2020" target="_blank">Link</a>
- Gong, P., Chen, B., Li, X., Liu, H., …, **Song, Y.**, …, & Xu, B. (2020). Mapping essential urban land use categories in China (EULUC-China): Preliminary results for 2018. <span style="color: darkblue;">*Science Bulletin*</span>, *65*(3), 182-187. <a href="https://doi.org/10.1016/j.scib.2019.12.007" target="_blank">Link</a>
- **Song, Y.**, Chen, B., & Kwan, M. P. (2020). How does urban expansion impact people's exposure to green environments? A comparative study of 290 Chinese cities. <span style="color: darkblue;">*Journal of Cleaner Production*</span>, *246*, 119018. <a href="https://doi.org/10.1016/j.jclepro.2019.119018" target="_blank">Link</a>
- Liu, Y., Wang, R., Lu, Y., Li, Z., Chen, H., Cao, M., Zhang, Y., & **Song, Y**. (2020). Natural outdoor environment, neighbourhood social cohesion and mental health: Using multilevel structural equation modelling, streetscape and remote-sensing metrics. <span style="color: darkblue;">*Urban Forestry & Urban Greening*</span>, *48*, 126576. <a href="https://doi.org/10.1016/j.ufug.2019.126576" target="_blank">Link</a>

### **2019**

- **Song, Y.**, Huang, B., He, Q., Chen, B., Wei, J., & Mahmood, R. (2019). Dynamic assessment of PM exposure and health risk using remote sensing and geo-spatial big data. <span style="color: darkblue;">*Environmental Pollution*</span>, *253*, 288-296. <a href="https://doi.org/10.1016/j.envpol.2019.06.057" target="_blank">Link</a>
- Huang, B., Zhou, Y., Li, Z., **Song, Y.**, Cai, J., & Tu, W. (2019). Evaluating and characterizing urban vibrancy using spatial big data: Shanghai as a case study. <span style="color: darkblue;">*Environment and Planning B: Urban Analytics and City Science*</span>, *47*(9), 1543-1559. <a href="https://doi.org/10.1177/2399808319828730" target="_blank">Link</a>

### **2018**

- Song, Y., Tan, Y., **Song, Y.**, Wu, P., Cheng, J. C., Kim, M. J., & Wang, X. (2018). Spatial and temporal variations of spatial population accessibility to public hospitals: A case study of rural-urban comparison. <span style="color: darkblue;">*GIScience & Remote Sensing*</span>, *55*(5), 718-744. <a href="https://doi.org/10.1080/15481603.2018.1446713" target="_blank">Link</a>
- Huang, B., Zhao, B., & **Song, Y.** (2018). Urban land-use mapping using a deep convolutional neural network with high spatial resolution multispectral remote sensing imagery. <span style="color: darkblue;">*Remote Sensing of Environment*</span>, *214*, 73-86. <a href="https://doi.org/10.1016/j.rse.2018.04.050" target="_blank">Link</a>
- **Song, Y.**, Huang, B., Cai, J., & Chen, B. (2018). Dynamic assessments of population exposure to urban greenspace using multi-source big data. <span style="color: darkblue;">*Science of the Total Environment*</span>, *634*, 1315-1325. <a href="https://doi.org/10.1016/j.scitotenv.2018.04.061" target="_blank">Link</a>
- Chen, B., **Song, Y.**, Kwan, M. P., Huang, B., & Xu, B. (2018). How do people in different places experience different levels of air pollution? Using worldwide Chinese as a lens. <span style="color: darkblue;">*Environmental Pollution*</span>, *238*, 874-883. <a href="https://doi.org/10.1016/j.envpol.2018.03.093" target="_blank">Link</a>
- Chen, B., **Song, Y.**, Jiang, T., Chen, Z., Huang, B., & Xu, B. (2018). Real-time estimation of population exposure to PM2. 5 using mobile-and station-based big data. <span style="color: darkblue;">*International Journal of Environmental Research and Public Health*</span>, *15*(4), 573. <a href="https://doi.org/10.3390/ijerph15040573" target="_blank">Link</a>

### **2017**

- Cai, J., Huang, B.<sup>\*</sup>, & **Song, Y**<sup>\*</sup>. (2017). Using multi-source geospatial big data to identify the structure of polycentric cities. <span style="color: darkblue;">*Remote Sensing of Environment*</span>, *202*, 210-221. <a href="https://doi.org/10.1016/j.rse.2017.06.039" target="_blank">Link</a>
