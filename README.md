# Plasticity-Evolution-Variable-Nutrients
This repository contains data CSVs and analysis code used to examine the association between phenotypic plasticity and genotypic frequency change for the Hobble &amp; Turcotte manuscript "Experimental evolution reveals nuanced selection dynamics on phenotypic plasticity under constant and variable environments in duckweed".

## Dataset Description
This dataset contains measurements used to quantify ecological and evolutionary consequences of trait plasticity in Spirodela polyrhiza. Data include relative growth rates, phenotypic trait measurements, and final genotypic frequencies for genotype pairs grown under contrasting environmental conditions.

### Directory Structure
```text
├── main/
│   ├── EvoData.csv                              # Evolutionary response data
│   ├── Summer2022_PhenoTraitData.csv            # Phenotypic trait measurements
│   ├── Summer2022_PLE_Solo_FinalFrondCount.csv  # Population growth data
│   ├── Cleaned_PLE2022_PlasticityAnalysis.Rmd   # R markdown used for analyses
│   └── README.md
```

#### CSV Column Explanations
#### EvoData.csv
- Index: Observation identifier
- Bottle_Type: Experimental bottle type
- Geno.Code: Numerical genotype code
- Pair.Code: Numerical genotype-pair code
- Unique_Geno_Media: Unique genotype × environment identifier
- Media: Environmental treatment
- GenoPair: Competing genotype pair
- Geno: Focal genotype
- Plast.Group: Plasticity classification
- Clone: Clone identifier
- Rep: Experimental replicate
- Rack: Rack location
- Cell: Cell position within rack
- Starting.Freq: Initial genotype frequency
- Expected.Freq: Expected final frequency
- Final.Freq: Observed final frequency
- Freq.Change: Change in genotype frequency
- Final.Frond.Freq: Final frond-based frequency
- Frond.Freq.Change: Change in frond frequency

#### Summer2022_PhenoTraitData.csv
- Date: Measurement date
- GenoPair: Genotype pair
- Plast.Pair: Plasticity-pair category
- Rep: Experimental replicate
- Rack: Rack location
- Cell: Cell position within rack
- Geno: Genotype
- Geno_Code: Numerical genotype code
- Media: Environmental treatment
- Unique_Geno_Media: Unique genotype × environment identifier
- Unique_Bot_Geno: Unique bottle × genotype identifier
- RxnNorm_Code: Reaction norm code
- RootNumber: Number of roots
- RootLength: Total root length
- SLA: Specific leaf area
- Chloro: Relative chlorophyll A content
- Antho: Relative anthocyanin content

#### Summer2022_PLE_Solo_FinalFrondCount.csv
- Index: Observation identifier
- Pair: Genotype pair
- Geno1: First genotype in pair
- Geno2: Second genotype in pair
- Treatment: Environmental treatment
- Rack: Rack location
- Cell: Cell position within rack
- Starting.Fronds: Initial frond count
- Final.Fronds: Final frond count
