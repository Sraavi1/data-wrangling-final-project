# Data Dictionary
 
| **Field Name**    | **Data Type** | **Source** | **Description**                                                             |
|-------------------|---------------|------------|-----------------------------------------------------------------------------|
| Period            | Date          | All        | The month and year for pricing, GPR, and crisis data                       |
| Product           | String        | EIA        | The type of petroleum – WTI or Brent                                       |
| Price             | Numeric       | EIA        | Price of oil                                                               |
| GPR               | Numeric       | GPR        | The measure of geopolitical risk                                           |
| GPR_Threats       | Numeric       | GPR        | The measure of geopolitical threats                                        |
| GPR_Acts          | Numeric       | GPR        | The measure of geopolitical threats that escalated into acts              |
| Cat_1             | Numeric       | GPR        | Frequency of articles on War Threats                                      |
| Cat_2             | Numeric       | GPR        | Frequency of articles on Peace Threats                                    |
| Cat_3             | Numeric       | GPR        | Frequency of articles on Military Buildups                                |
| Cat_4             | Numeric       | GPR        | Frequency of articles on Nuclear Threats                                  |
| Cat_5             | Numeric       | GPR        | Frequency of articles on Terror Threats                                   |
| Cat_6             | Numeric       | GPR        | Frequency of articles on Beginning of War                                 |
| Cat_7             | Numeric       | GPR        | Frequency of articles on Escalation of War                                |
| Cat_8             | Numeric       | GPR        | Frequency of articles on Terror Acts                                      |
| GPR_Articles      | Numeric       | GPR        | Proportion of total articles that are categorized in the GPR index        |
| Total_Articles    | Numeric       | GPR        | Total number of articles published by the 10 major newspapers             |

