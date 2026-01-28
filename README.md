# STA540_CS1
Case Study 1 Final Deliverable

Raymond Sun

A. Study Overview: 
Social media sites, dating apps, and information search sites have been used to reach individuals at high risk for
HIV infection. However, it is not clear which platform is the most efficient in promoting home HIV self-testing, given that the
users of various platforms may have different characteristics that impact their readiness for HIV testing. 

This study's primary objective is to compare the relative effectiveness of social media sites, dating apps, and information search sites in promoting HIV self-testing among minority men who have sex with men (MSM) at an increased risk of HIV infection. Test kit order rates were used as a proxy to evaluate promotion effectiveness. In addition, a secondary objective is to assess differences in characteristics between participants who ordered and did not order an HIV test kit.

B. Table 1:                                
| Characteristic                                                | Value       |
| ------------------------------------------------------------- | ----------- |
| **Age, years, median (IQR)**                                  | 25 (21–27)  |
| **Ethnicity, n (%)**                                          |             |
| Hispanic/Latino                                               | 66 (26%)    |
| **Race, n (%)**                                               |             |
| American Indian or Alaskan Native                             | 1 (0.4%)    |
| Black or African American                                     | 196 (78.4%) |
| Multiracial                                                   | 11 (4.4%)   |
| Other                                                         | 14 (5.6%)   |
| White                                                         | 28 (11.2%)  |
| **History of PrEP uptake, n (%)**                             |             |
| In the past 6 months                                          | 22 (8.7%)   |
| Never taken PrEP                                              | 232 (91.3%) |
| **Number of male sex partners in past 90 days, median (IQR)** | 4 (3–6)     |
| **Condom use, n (%)**                                         |             |
| Never                                                         | 36 (14.2%)  |
| Sometimes                                                     | 108 (42.5%) |
| About half the time                                           | 37 (14.6%)  |
| Most of the time                                              | 68 (26.8%)  |
| Always                                                        | 5 (2.0%)    |
| **Condomless receptive anal sex in past 90 days, n (%)**      | 210 (82.7%) |
| **Ever tested for HIV during lifetime, n (%)**                | 191 (75.2%) |
| **Months since last HIV test (if tested), median (IQR)**      | 11 (6–21)   |
| **If not tested for HIV, n (%)**                              | 63 (24.8%)  |
| **Main reasons for not getting tested (n = 63), n (%)**       |             |
| Unlikely to be exposed to HIV                                 | 8 (12.7%)   |
| Afraid of testing HIV-positive                                | 26 (41.3%)  |
| Did not want to think about HIV/HIV-positive                  | 8 (12.7%)   |
| Worried about names being reported if positive                | 3 (4.8%)    |
| Dislike for needles                                           | 5 (7.9%)    |
| Unable to trust that the results will be confidential         | 3 (4.8%)    |
| Unaware of where to get tested                                | 7 (11.1%)   |

C. Primary/Secondary Results:

Rate of kits ordered: Jack’D - 3.29 kits/day, Instagram - 0.34 kits/day, Bing - 0 kits/day, 

Grindr - 0.13 kits/day, Facebook - 0.19 kits/day, Google - 0.24 kits/day.

Grindr-Facebook contrast adjusted p-value: 0.47

Grindr-Google contrast adjusted p-value: 0.37

Facebook-Google contrast adjusted p-value: 0.47

Jack'd - Instagram contrast adjusted p-value: <0.01

Jack'd - Bing contrast adjusted p-value: 1.00

Instagram - Bing contrast adjusted p-value: 1.00

Fisher's exact test for association between “People in my life would leave if I had HIV”: 0.035

D. Reflection: The participant recruited from Yahoo was tricky to identify, I think the manuscript should have given this information for better reproducibility. Some differences between published results and my results are due to rounding, but also some could be careless mistakes in the original study, such as listing 8.7% as 8.9%.

Wave 4 in the original data being included in wave 1 makes sense from the final results, but it would be better if the manuscript had mentioned this. The biggest disparity between reproduced results and manuscript results come in the contrast p-values for the primary analysis, the 0 rate for Bing causes trouble for emmeans and it's hard to replicate what they might have done in SAS to achieve similar p-values.

E. References: 

Study manuscript: https://pmc.ncbi.nlm.nih.gov/articles/PMC9591705/pdf/formative_v6i9e35648.pdf

NIDA page: https://datashare.nida.nih.gov/data/nida-ctn-0083

emmeans package: https://cran.r-project.org/web/packages/emmeans/vignettes/comparisons.html

ChatGPT was used primarily for code formatting and table constructing.


Wilcoxon test for “I think that new HIV/AIDS treatments can eradicate the virus from your body”: 0.029

Wilcoxon test for “I could not be friends with someone who has HIV/AIDS": 0.033

