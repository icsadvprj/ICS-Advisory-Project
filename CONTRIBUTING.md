# Welcome #

We're so glad you're thinking about contributing to the ICS Advisory open source project! If you're unsure or afraid of anything, ask or submit the issue. The worst that can happen is that you'll be politely asked to change something. We appreciate your willingness contribute.

Before contributing, we encourage you to read this CONTRIBUTING policy, our [LICENSE](LICENSE), and [README](README.md), all of which should be in this repository.

# Contributing Guidance #
When contributing to the ICS Advisory project, we recommend viewing the ICS-CERT_2022_Master.csv file to verify its last update date and comments. This CSV file contains the complete list of ICS-CERT Advisories released since 2010. Any updates or edits made for specific ICS-CERT Advisory record data fields need to reflect in the year of the ICS-CERT_ADV.cvs file (e.g., ICS-CERT_ADV_2010) containing that ICS-CERT Advisory record as in the ICS-CERT_2022_Master file. For example, if you make changes to the "Products Affected" data field for "ICSMA-21-355-01" that should be reflected in that same ICS-CERT Advisory record in ICS-CERT_ADV_2021.csv to maintain continuity.

After checking the ICS-CERT_2022_Master.csv for recent update dates, it would be best to verify the list of Last revised [ICS-CERT Advisories](https://docs.google.com/spreadsheets/d/1l8M1PdITIfUlL8r4weQ0PdPpOejccjp-r5kSuenceKs/edit?usp=sharing). The original CISA ICS-CERT Advisory should be verified at [CISA ICS-CERT Advisories](https://www.cisa.gov/uscert/ics/advisories?items_per_page=All). CISA ICS-CERT will revise ICS-CERT Advisories periodically and is indicated by the "Last Revised:" information within the ICS-CERT Advisory as shown: "Original release date: February 10, 2022 | Last revised: February 15, 2022". From here, you will have to investigate which section of the report has changed and update the respective data field for the specific ICS-CERT Advisory record in the ICS-CERT_2022_Master.csv.

The ICS-CERT Advisory Contribution template and instructions on how to enter/update data in each field can be accessed at [ICS-CERT_ADV_Contrib_Template](https://docs.google.com/spreadsheets/d/1Kbl8tSuEKLYPJJRJS_XN9_5JL1hhzOdcxblT3io7ULM/edit?usp=sharing)

## Background ##
While this process is very manual, I hope to further automate it with the help of contributors in the ICS Advisory Project. Since 2018, the data has been scraped using Microsoft Excel formulas and VBA scripts to parse it into its current form, as seen in the ICS-CERT_ADV.csv files.

Please feel free to propose a better way to help maintain and share this data. Your support helps support the ICS Advisory Project: ICS-CERT Advisory Dashboard currently built and hosted for free on Google Data Studio.

If you have questions, please email: icsadvisoryproj@icsadvisoryproject.com

## Issues ##
If you want to report a bug or request a new feature, the most direct method is to [create an issue](https://github.com/icsadvprj/ICS-Advisory-Project/issues) in this
repository. We recommend that you first search through existing issues (both open and closed) to check if your particular issue has already been reported. You might want to add a comment to the existing issue if it has. If it hasn't, then feel free to create a new one.
