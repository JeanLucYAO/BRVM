# 💰 BRVM DATA 💰
This short project is intented to get data about stocks exchanged at the `Bourse Régionale des Valeurs Mobilières (BRVM)`, and paste it in `Google Sheets` to power a dashboard giving metrics on my current portfolio. 
The BRVM is a regional stock exchange serving eight West African countries, where investors can buy and sell shares of companies based in the region.

## Structure
<pre> <code> 
  BRVM/ 
  ├── renv/ # Package environment (auto-generated)
  ├── scripts/ 
  │   └── analysis.Rmd # main report 
  ├── .Rprofile # auto-generated 
  ├── .gitignore # auto-generated
  ├── .Rproj # RStudio project file 
  ├── renv.lock # Dependency lockfile 
  └── README.md # This file
</code> </pre>

## How to reproduce?
1. Clone this repo: <pre> <code> git clone https://github.com/yourname/BRVM.git</code> </pre>
2. Open the `.Rproj` file in RStudio.
3. Restore the R environment: <pre> <code> renv::restore() </code> </pre>
4. Adjust the main report to suit your needs.

## Packages Used
- `BRVM` by Koffi Frederic SESSIE
- `Tidyverse`
- `renv`
