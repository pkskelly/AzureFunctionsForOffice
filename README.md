# Azure Functions For Office
Helpful little functions for working with Office 365 and Microsoft Office documents.

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

Azure Functions For Office is a set of utility [Azure Functions](https://azure.microsoft.com/en-us/services/functions/) for working with Office documents and eventually Microsoft Graph. 
This initial version consists of three functions for working with Excel and Word documents:
* Excel Extract - reads rows and columns from an Excel file and returns easily consumed JSON
* Excel Merge - Merges data in JSON format with an Excel document given as a URL or as a Base64 encoded string
* Word Merge - Merges data in JSON format with an Word document given as a URL or as a Base64 encoded string

## Amazing Samples
* [Excel Extract](https://afodocs.blob.core.windows.net/docs/articles/ExcelExtract.html)
* [Excel Merge](https://afodocs.blob.core.windows.net/docs/articles/ExcelMerge.html)
* [Word Merge](https://afodocs.blob.core.windows.net/docs/articles/WordMerge.html)

## The rest of the documentation is here: [Azure Functions for Office](https://afodocs.blob.core.windows.net/docs/index.html)
