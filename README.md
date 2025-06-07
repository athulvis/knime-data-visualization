 # [Download all files](https://github.com/athulvis/knime-data-visualization/archive/refs/tags/publish.zip)

# Knime Data Visualization - Course Materials

Course slides and knime workflow files created for Empowering Research and Training with AI and Data Tools conducted by ICFOSS and DAKF from June 6 - 8, 2025.


## Working with Knime Workflow

1. Open Knime > Local Space tab > Import Workflow. Choose location of workflow file.

2. Keep the `data` folder along with the workflow file. If it is not opening, choose the path of the csv / xlsx file. Make sure that `read from` opetion is set as `Local File System`.

3. Don't forget to untick `limit scanned rows` in the `Advanced` tab for CSV/Excel Reader.

4. Set appropriate paths in `CSV Writer`, `Report PDF Writer` and `Write HTML Writer` nodes where the output is written into file.

### Knime workflow files

There are two Knime workflows available in the repository here:

1. TVM_Weather_fulldata.knwf

    - Input data files: 
        - AQI_daily_2024_Plammoodu_Thiruvananthapuram_Kerala_PCB_2024.xlsx
        - Eastfort_rain.csv
        - Eastfort_humidity.csv
        - Eastfort_temperature.csv
2. TVM_Weather_simplified.knwf
    - Input data files
        - AQI_daily_2024_Plammoodu_Thiruvananthapuram_Kerala_PCB_2024.xlsx
        - combined_rain_temp_hum.csv

### Knime Resources
 - Download Knime Analytics Platform - [Link](https://www.knime.com/downloads)
 - Knime Documentation: Getting Started - [Link](https://www.knime.com/getting-started-guide)
 - Data Literacy with KNIME Analytics Platform: Basics Course - [Link](https://www.knime.com/learning) (Login needed)

 ## Attributions

 - Air Quality Index data source : 
    
    - [Central Control Room for Air Quality Management - All India](https://airquality.cpcb.gov.in/ccr/#/caaqm-dashboard-all/caaqm-landing/aqi-repository)
    
- Rain, Humidity and Temperature dataset
    - [LoRaWAN Kerala THiruvananthapuram district data by ICFOSS](https://visualize.openiot.in/d/V_9s5fOVzerea/lorawan-kerala-trivandrum-dist?orgId=2&refresh=5m)

- All the screenshots used in knime.pdf presentation is taken from [Knime website](https://www.knime.com/getting-started-guide). The usage is permitted in [Knime FAQ](https://www.knime.com/faq#q2_1).


