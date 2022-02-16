# Welcome #

We're so glad you're thinking about contributing to the ICS Advisory open source project!  If you're unsure or afraid of anything, just ask or submit the issue.  The worst that can happen is that you'll be politely asked to change something.  We appreciate your willingness contribute.

Before contributing, we encourage you to read this CONTRIBUTING policy, our [LICENSE](LICENSE), and [README](README.md), all of which should be in this repository.

# Contributing Guidance #
When contributing to the ICS Advisory project we recommend starting with viewing the ICS-CERT_2022_Master.csv file to verify it last update date and comments. This CSV file will contain the complete list of ICS-CERT Advisories released since 2010. Any updates or edits made for specific ICS-CERT Advisory record data fields needs to be reflected in year of the ICS-CERT_ADV.cvs file containing that ICS-CERT Advisory record. For example, if you make changes to the "Products Affected" data field for "ICSMA-21-355-01" that should be reflected in that same ICS-CERT Advisory record in ICS-CERT_ADV_2021.csv to maintain continuity.

After checking the ICS-CERT_2022_Master.csv for recent update dates, it would be best to verify the list of Last revised [ICS-CERT Advisories] (https://docs.google.com/spreadsheets/d/1l8M1PdITIfUlL8r4weQ0PdPpOejccjp-r5kSuenceKs/edit?usp=sharing). The original CISA ICS-CERT Advisory can also be verified at [CISA ICS-CERT Advisories](https://www.cisa.gov/uscert/ics/advisories?items_per_page=All). CISA ICS-CERT will revised ICS-CERT Advisories and will indicate this by providing the "Last Revised:" information within the ICS-CERT Advisory as shown: "Original release date: February 10, 2022 | Last revised: February 15, 2022". From here you will have to investigate which section of the report has changed and update the respective data field for the specific ICS-CERT Advisory record in the ICS-CERT_2022_Master.csv.

Below is the list of default data fields and instruction on how to enter data in each field:

icsad_ID [Enter the next avaliable ID number]

hyperlink [Enter ICS-CERT Advisory URL]

Original_Release_Date [Enter Original Release date from the Advisory in the following format "02/15/2022"]

Last_Updated [Enter Last Revised date from the Advisory in the following format "02/16/2022]

Year	[Enter year of the Advisory was released in the following format: "2022"]

ICS-CERT_Number [Enter the ICS-CERT Advisory number: "ICSMA-21-355-01" or "ICSA-22-041-04"]

ICS-CERT_Advisory_Title	[Enter the ICS-CERT Advisory Title, this is provided at the top of the report: "Siemens SIMATIC Industrial Products"]

Vendor [Enter Vendor Name(s): "Siemens"]

Product [Enter Product which is provided in the Equipment field in the ICS-CERT Advisory: "Siemens SIMATIC Industrial Products"]

Products_Affected [Enter the entire list of affected products identified in the ICS-CERT Advisory: The following versions of Siemens Industrial Products with SIMATIC Firmware, a software platform, are affected: SIMATIC Drive Controller family: All versions prior to v2.9.4"]

CVE_Number [Enter the Common Vulnerabilities and Exposures (CVE Numbers provided in the ICS-CERT Advisory: "CVE-2021-37185"]

Cumulative_CVSS [Enter the Cumulative CVSS score that is provided at the top of the ICS-CERT Advisory, directly below "EXECUTIVE SUMMARY" and above "ATTENTION": "7.5"]

CVSS_Severity  - Calculate the CVSS Severity using the [NVD Vulnerability Metrics](https://nvd.nist.gov/vuln-metrics/cvss#)

CWE_Number [Enter the Common Weakness Enumeration (CWE) IDs identified in the ICS-CERT Advisory: "CWE-120". Do not to enter duplicate CWE ID numbers]

Critical_Infrastructure_Sector [Enter the list of identified Critical Infrastructure sectors identified under the "BACKGROUND" field of the ICS-CERT Advisory]

Product_Distribution [Enter the list of countries or geographical areas identified in the "COUNTRIES/AREAS DEPLOYED" field]

Company_Headquarters [Enter the Vendor Headquarters country location identified in the COMPANY HEADQUARTERS LOCATION: "Germany"]

While this process is very manual at this time, I hope to further automate this process with the help of contributors in the ICS Advisory Project. Since 2018, the data has been scraped using Microsoft Excel formulas and VBA scripts to parse the data into its current form as see in the ICS-CERT_ADV.csv files.

Another goal for this project would be to break out the Critical Infrastructures invidually for each vendor and product to enable clear trends of their use across multiple industries. The current way that ICS-CERT Advisory list Critical Infrastructure information per vendor and product is comma separated as one line.

Please feel free to propose better way to help maintain and share this data as it will also help support the ICS Advisory Project: ICS-CERT Advisory Dashboard current build and host for free on Google Data Studio.

If you have questions, please email: icsadvisoryproject@gmail.com

## Issues ##

If you want to report a bug or request a new feature, the most direct method is to [create an issue](https://github.com/icsadvprj/ICS-Advisory-Project/issues) in this
repository.  We recommend that you first search through existing issues (both open and closed) to check if your particular issue has already been reported.  If it has then you might want to add a comment to the existing issue.  If it hasn't then feel free to create a new one.
