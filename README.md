This R Markdown pipeline quantifies protein concentration of HeLa, K-562, and CD34+ cell lines, from a microplate reader machine.


Bradford assay consists in the shift of absorbance of a chemical depending on the protein binding, 
in comparison to a standard curve generated alongside samples using defined BSA dilutions (2000–0 µg/mL). This standard curve has to be generated each time to each experiment 
All measurements (standards and samples) are performed in triplicate.

Key parameters to take into account for this assay:
    Absorbance wavelength: 595 nm
    Standard curve range: 2000, 1500, 1000, 750, 500, 250, 125, 25, 0 µg/mL
    Sample dilutions:
        HeLa and K-562; 1:30 in DPBS
        CD34+; 1:9 in DPBS (higher protein concentration required)

Input Requirements
    Exported .csv file from microplate reader.
