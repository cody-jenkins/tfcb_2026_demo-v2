# Measuring Efficiency of CD24 lenti-CRISPR knockout by Flow Cytometry
2025-07-25, Flow cytometry on CD24ko cell lines https://github.com/cody-jenkins/tfcb_2026_demo-v2/issues/1

## Reagents 

| Reagent | Vendor | Catalog Number | Stock concentration | Final Concentration |
|---------|--------|----------------|---------------------|---------------------|
|10x PBS  | ThermoFisher | 14200075 | 10x | 1x|
|Fixable L/D Dye| ThermoFisher | L23105 | 1500x | 1x |
|Anti-CD24-PE | BioLegend | 101807 | 200x | 1x | 
| Rat IgG2b Isotype ctrl | Biolegend | 400635 | 200x | 1x | 

### Experimental Objective 
To determine what percentage of murine small cell lung cancer cells express the target protein CD24 after CRISPR knockout
Background: CD24 is a “Do not eat me signal” that prevents tumor cells from being attacked by immune phagocytes such as macrophages. We have conducted lenti-CRISPR assays using guides specifically targeted to knock out CD24 from our murine small cell lung cancer cell lines as well as a non-targeting guide in the same vector. We have confirmed that the knock-out cell line has negatively enriched levels of RNA expression relative to the control cell line. This experiment describes how we used flow cytometry to compare the level of protein expression of the knockout cell line to the control cell line. 

## Procedure 
1. Six Separate cell cultures from the knock-out and control murine cell line known as K7127 cell line were grown in tissue culture appropriate plastic-ware for 48 hours.
2. The replicates were harvested by centrifugation, washed with 1x PBS and labeled according to the table below.

| Cell line | Replicate | Antibody Stain |
|-----------|-----------|----------------|
|K7172-CD24KO| A | CD24 - PE |
|K7127-CD24KO| B | CD24 - PE | 
|K7127-CD24KO| C | CD24 - PE | 
|K7127-NT-ctrl|A | CD24 - PE | 
|K7127-NT-ctrl|B | CD24 - PE | 
|K7127-NT-ctrl|C | CD24 - PE | 
|K7172-CD24KO| A | Isotype ctrl - PE |
|K7127-CD24KO| B | Isotype ctrl - PE | 
|K7127-CD24KO| C | Isotype ctrl - PE | 
|K7127-NT-ctrl|A | Isotype ctrl - PE | 
|K7127-NT-ctrl|B | Isotype ctrl - PE | 
|K7127-NT-ctrl|C | Isotype ctrl - PE | 


3. After the wash was removed cell pellets were resuspended in 100µl of 1x fixable aqua live/dead dye (Thermo Fisher, cat# L23105) and incubated for 20 minutes at 4°C.
4. Cells were then washed with PBS and cell pellets were resuspended with 100µl of either anti-CD24 antibody (clone: M1/69) conjugated to PE (Biolegend cat# 101807) or a matching antibody isotype control (Biolegend cat #400635) and incubated for 20 minutes at 4°C.
5. After incubation, cells were washed and pellets were resuspended in 150µl of 1x PBS.
6. BD FACSymphony A3 Cell Analyzer was used to measure the percent positivity of each cell replicate. 

## Result
Flow cytometry confirmed that the control cell lines were ~95% positive for CD24 while the knockout cell lines each were completely negative. 
![Flow Cytometry Results](experiments/img/CD24-results.png) 


### Conclusion
The knockout cell line and its corresponding control cell line demonstrate differential CD24 protein expression making it a valid model for further interrogating the role of the marker in tumor biology. 

