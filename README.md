# journal-indexing-checker
Automated journal indexing checker: 
1. Extracts links to a national scientific research groups database GRUPLAC (Colombia) from an excel file saved in Google Drive.
2. Finds the published article for each research group in a given timeframe (default is 2019 to 2024)
3. Cross references the ISSN of the publishing journals to check the indexing of the articles in International (SCOPUS and WOS) and National (Publindex) databases.
4. Organizes information in a Pandas Dataframe and writes it onto a new sheet in the original Excel file.

Meant to be run in a Google Colab environment for ease of usage and distribution inside an academic institution.
