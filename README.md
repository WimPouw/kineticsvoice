# Kinetics Voice Project

This repository contains the analyses code for the project by Pouw, Werner, Burchardt, Selen, 'The human voice aligns with whole-body kinetics'.

## 📊 Notebook

View our analysis notebook online: [https://wimpouw.github.io/kineticsvoice/](https://wimpouw.github.io/kineticsvoice/)

## 📁 Repository Structure

- **dataset**: Contains a link to the Donders Repository where the full dataset can be downloaded, including:
  - Tracked videos
  - Audio files
  - Time series for balance board and EMG
  - Acoustic measurements

To go directly to the citable dataset download page: https://doi.org/10.34973/p9se-mq71

- **docs**: Contains HTML pages, such as the knitted R Markdown file

- **RMarkdown**: Contains the R Markdown script for generating the supporting information

- **pre_registration_copy**: Contains a timestamped copy of the pre-registration (with redacted names)

## 🔄 Reproducibility

This project uses `renv` to ensure computational reproducibility. To reproduce our exact analysis environment:

1. **Clone this repository**:
   ```
   git clone https://github.com/wimpouw/kineticsvoice.git
   cd kineticsvoice
   ```

2. **Install renv** (if not already installed):
   ```r
   install.packages("renv")
   ```

3. **Restore the environment** from our lockfile (this can be for example run in the console when opening the notebook):
   ```r
   renv::restore()
   ```
   This will install all packages at the exact versions we used.

### Additional Reproducibility Files

- `session_info_kinetics.txt`: Contains detailed information about the R session and packages (for manual checking mostly)
- `renv.lock`: Records the exact package versions that are machine-readable and easy to reuse

## 📊 Open Data
Access the complete dataset here: [https://webdav.data.ru.nl/dcc/DSC_2023.00002_259](https://webdav.data.ru.nl/dcc/DSC_2023.00002_259)

## 📧 Contact
For questions or collaborations, please contact: wim.pouw@donders.ru.nl