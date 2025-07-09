# Microgrid Resilience Calculator

This Excel-based tool helps quantify **microgrid resilience** by simulating random outages throughout the year and calculating the survivable duration based on DER (Distributed Energy Resource) performance, load profiles, and battery storage dynamics.

## 📦 What You Need

- `Reopt_dispatch.csv` — downloaded from [NREL's REopt Lite Web Tool](https://reopt.nrel.gov/tool)
- `Resilience_Calculator_github.xlsm` — this tool (with macros enabled)

## ✅ Getting Started

1. **Use the REopt Lite Tool**  
   Go to REopt (https://reopt.nrel.gov/tool) and:
   - Select DER technologies to consider (e.g., PV, battery storage, wind, prime generator).
   - Enter the location of your site and load information (e.g., upload your hourly load profile or use REopt defaults).
   - Run the simulation.

2. **Download the Dispatch Data**
   - On the results page, click **“Download All Dispatch Data.”**
   - Rename the downloaded file to:  
     ```
     Reopt_dispatch.csv
     ```

3. **Place the Files in the Same Folder**
   Ensure the following two files are in the **same folder**:
   - `Reopt_dispatch.csv`
   - `Resilience_Calculator_github.xlsm`

4. **Enable Macros**
   - When opening `Resilience_Calculator_github.xlsm`, make sure to **enable macros** when prompted.

5. **Follow In-Tool Instructions**
   - Once the setup is complete, open the tool and follow the step-by-step guidance in the workbook tabs to run the simulation and analyze results.

## 📘 Documentation

- No coding is required.
- All inputs are editable via the `2. Main Inputs` tab.
- Output metrics and seasonal/contour plots are automatically generated in the designated output tabs.

## 🛠 Requirements

- Excel for Windows or Mac with macro support.
- Internet access (only needed to access REopt).

---

**Disclaimer:** This tool is intended for research and educational purposes. Validate results independently before making real-world energy planning decisions.
