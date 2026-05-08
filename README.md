##Overview

This README accompanies an Excel datasheet (SLR methodology track, Safeguarding the skies the rise of machine learning approaches for cyberattack detection in unmanned aerial systems.xlsx) that documents all studies considered for a Systematic Literature Review (SLR) on Unmanned Aerial Systems (UAS) cybersecurity, focusing on datasets and machine learning (ML)-based approaches for cyberattack detection. The datasheet includes observations on inclusion or exclusion reasons to ensure transparency and reproducibility of the SLR methodology.

**********Datasheet Description*************************

The Excel file contains a comprehensive list of studies evaluated during the SLR process using PRISMA. Each entry includes details about the study and the rationale for its inclusion or exclusion based on predefined criteria.

Column names in the Datasheet:


***
ID: Unique identifier for each study.


***
Title: Title of the paper or dataset.


***
Authors: List of authors.


***
Year: Year the study was published.


***
journal: Publication venue or database (e.g., IEEE Xplore, Multimedia Tools and Applications, ..).


***
doi: the Digital Object Identifier of the study.


***
url: the URL where to find the study


***
Abstract: the abstract of the study, from scopus or Web of Science.


***
Decision: Indicates whether the study was included or excluded( in screening step, or after fullreading the paper), or included by snowballing.



****
Exclusion reason: Indicates the exclusion criteria used to exclude the study after full reading the paper (EC1, EC2,......, EC5).


****
OBS: Additional observations (e.g., rationnal behind inclusion or exclusion, some specifities of the study, type of attacks considered).


## Usage

1. Clone or download this repository.
2. Open `SLR methodology track, Safeguarding the skies the rise of machine learning approaches for cyberattack detection in unmanned aerial systems.xlsx` in Microsoft Excel, LibreOffice, or Google Sheets.
3. Use filters on the **Decision** and **Exclusion reason** columns to explore included vs. excluded studies.
4. The file is structured to facilitate reproducibility and secondary analyses.

## How the Screening Was Conducted

The process adopted in the SLR consists of three phases: identification, screening, and eligibility. First, we identified 680 papers from two bibliographic databases, namely Scopus and Web of Sciences. Then, the initial set of studies was examined for duplicates. After discarding 123 duplicated works, we systematically screened articles by evaluating their titles, abstracts, and author keywords against the inclusion and exclusion criteria. For example, the study titled "User-Agent as a Cyber Intrusion Artifact: Detection of APT Activity Using Minimal Anomalies in User-Agent String Traffic" was excluded (EC1) because it is not relevant to the research problem. This study was identified in bibliographic databases among the initial set of studies because of its use of the abbreviation "UAS" for User- Agent String. Thus, the preliminary assessment allowed the exclusion of 351 papers, most of which focused on drone detection, object detection by drones, or other topics unrelated to the research problem. Furthermore, three relevant studies that were not found in the databases were identified using a snowball search method and subsequently included in our study. Next, we performed an eligibility evaluation by full-reading 203 studies and verifying inclusion and exclusion criteria. The full-text assessment allowed the exclusion of half of these papers. For instance, the article titled "A Data Normalization Technique for Detecting Cyber Attacks on UAVs" was excluded because it did not employ ML techniques (EC3). Upon review, we determined that its methodology relied on probability theory and statistical methods. Similarly, the article titled "A Machine Learning Approach for Detecting and Classifying Jamming Attacks Against OFDM-Based UAVs" was excluded due to redundancy(EC5), as the results presented in this conference paper were similar to the results included in a journal article published by the same authors, which was already included in our SLR. Ultimately, 101 studies were retained for inclusion in our review. 
## Citation

If you use this datasheet in your research, please cite the original SLR paper:

> Mouatassim, T., Airaj, M. & El Guarmah, E.M. Safeguarding the skies: the rise of machine learning approaches for cyberattack detection in unmanned aerial systems. Cybersecurity 9, 62 (2026). https://doi.org/10.1186/s42400-025-00466-2
## License

This datasheet is released under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. You are free to use, adapt, and share the data as long as proper attribution is given.

## Contributing

Feel free to open an issue or submit a pull request if you find errors or have suggestions for improvement.

## Contact

- Email: tariq.mouatassim@usmba.ac.ma
