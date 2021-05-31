# Kickstarter Projects Analysis and Visualization

## Project Overview
<img src='https://github.com/unguyen14/Kickstarter_project_analysis/blob/main/media/crowdfunding.png'></img>
This project aims to provide Kickstarter enthusiasts, including backers, creators, or even inquisitors, a general perception about successful projects that met the funding goal, as well as a rough projection of the successful rate in 3 years from 2021 to 2023, detailing in geographical and categorical characteristics. 

**Methods:**
- Datasets Preparations: Python
- Visualization: Tableau

## Project Motivation
[Kickstarter](https://www.kickstarter.com/) is one of the leading crowdfunding platforms for exciting entrepreneurial ideas. Even though there are thousands of projects are uploaded to it every years, less than 40% of those projects had reached the intended money goal. 

Using the history data, I hope to deliver a general ideas over successful and failed projects along with their ability to draw funds. Furthermore, the existing data can also produce a estimated model for future projects. The dashboard filters data based on locations, which allows users to understand the unique local growth of projects better. 

Please click [here](https://public.tableau.com/app/profile/winnie.nguyenn/viz/Kickstarter_16104885900510/MainDashboard) to view the interactive dashboard on Tableau.

## Project Directory
```
| - Kickstarter_project_analysis        
|   -- dashboard                                            Includes an overview and link to the Tableau dashboard
|     --- Link_to_Dashboard.md
|   -- data                                                 Includes datasets link and a preprocessing script    
|     --- Kickstarter_2020_data_cleaning.ipynb              Python codes to merge and clean data, ready for dashboard
|     --- datasets_link.md                                  Link to datasets
|   -- media                                                Includes screenshots of the dashboard
|     --- crd00.png
|     --- crd000.png
|     --- crd01.png
|     --- crd011.png
|     --- crd02.png
|     --- crowdfunding.png
|   -- report                                               Includes a detailed report regarding the development
|     --- Kickstarter_dashboard_report.pdf
|   -- .gitignore                                           Ignores heavy files
|   -- LICENSE                                              MIT License
|   -- README.md                                            Project Overview
```

## Future Improvements
I want to incorporate this dataset with a Machine Learning model that can provide more accurate forcasting information for users. 
