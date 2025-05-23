# LAMAIS
A Library-Aided Approach for Efficient 1D 1H NMR Qualitative Analysis of Complex Mixtures

**Related publication:**
The methodology behind LAMAIS has been published in _Analytica Chimica Acta_.
DOI: [10.1016/j.aca.2024.343100](https://doi.org/10.1016/j.aca.2024.343100)

## How to Use 
Run `Window_LAMAIS.py` to open the interface.

**Step 01:** Select the input and output folders.

**Step 02:** Adjust the parameter values as needed. Typically, it is recommended to use the default values. Click the "Advanced mode" button to confirm and change the value of δr.

**Step 03:** Click the "Submit" button. LAMAIS will process all spectrum files in the input folder that meet the requirements one by one.

## About Output:
- **HTML file:** Interactive profiling results. 
- **Excel file:** Includes the chemical shifts of all successfully identified peaks and their similarity assessment results.
  
## Notes
- **Example Spectrum Files:** Stored in the `SampleData` folder. There are three files from standard compound mixtures and can be directly processed.
- **Template Folder:**  
  - Do **not** change the name of the `templates` folder.  
  - Make sure the `templates` folder and `Window_LAMAIS.py` are in the same root directory.  
  - The `templates` folder contains example template data for 10 compounds. Users can add their own templates by following this format.  
- **Executable File:**  
  - The executable version of LAMAIS2024 includes a built-in reference library of common plant primary metabolites.  
  - Please contact the author if needed.
  
