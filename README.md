# Healthcare Infrastructure Analysis Dashboard
![image](https://github.com/user-attachments/assets/dad6c960-924c-4c60-9a97-b048e1877f7d)



This dashboard offers comprehensive insights into healthcare infrastructure across major metropolitan areas, highlighting hospital counts, bed availability, and ratios critical for healthcare management.

## Key Metrics

- **Total Hospitals**: **1.86K** – indicating widespread healthcare facility coverage.
- **Total Beds**: **48.63K**, reflecting extensive healthcare capacity.
- **Hospital-to-Bed Ratio**: **3.82%**, showcasing facility density relative to bed availability.

## Metropolitan Area Breakdown

| Metropolitan Area                                    | Bed Count |
|------------------------------------------------------|-----------|
| Los Angeles-Long Beach-Anaheim, CA                   | 1.86K     |
| New York-Jersey City-White Plains, NY                | 2.7K      |
| Chicago-Naperville, IL-IN-WI                         | 2.5K      |
| Miami-Fort Lauderdale-West Palm Beach, FL            | 1.6K      |
| Atlanta-Sandy Springs-Roswell, GA                    | 1.2K      |
| Houston-The Woodlands-Sugar Land, TX                 | 1.2K      |
| Phoenix-Mesa-Scottsdale, AZ                          | 1.0K      |
| Dallas-Plano-Irving, TX                              | 0.9K      |
| St. Louis, MO                                        | 0.9K      |
| Riverside-San Bernardino-Ontario, CA                 | 0.8K      |

## Data Schema (Snowflake Schema)

### Fact Table
- **hospital_facts**: Contains metrics such as total hospitals, total beds, ICU beds, and calculated ratios.

### Dimension Tables
- **Dim_Hospital**: Information specific to hospitals.
- **Dim_Location**: Metropolitan areas and related geographic hierarchy.

These dimensions connect hierarchically, exemplifying a snowflake schema.

## Calculated Fields

- **Hospital-to-Bed Ratio**: Ratio of hospitals to total beds available, providing insights into capacity and facility utilization.

## Use Cases

- Evaluating healthcare coverage and efficiency.
- Identifying areas for potential infrastructure improvements.
- Strategic resource deployment, especially in crises.

## Applications

- Strategic planning for healthcare infrastructure.
- Emergency preparedness and response planning.
- Allocation of medical resources based on demand and coverage analysis.

This dashboard empowers healthcare professionals and policy makers to optimize healthcare services delivery and infrastructure planning.

