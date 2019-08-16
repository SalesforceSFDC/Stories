## Notes
* `Interim_Onboarding__c` is a child of the `Onboarding_Application__c`, which is a child of `Account`
* Leverage 

Two options for generating dynamic templates in DocuSign templates:
1.  Leverage Conga Composer managed package with Conga Mail Merge and/or Conga QuickMerge add-on features
2.  Leverage the existing [DocuSign for Salesforce Apex Toolkit](https://developers.docusign.com/salesforce/apex-toolkit-reference/index.html).  We can create `Labels` in DocuSign.  Each label will store values which represent parametes of a row.  Then, we will call DocuSign API and pass the attributes of the 


### Conga Merge 
https://support.conga.com/Conga_Composer
### 
* Use code to send dynamic pdf to DocuSign
* Leverage third party tools: Conga Merge
* Include it as an appendix
* Have a regular template
* Label 1 = result 1
* Label 2 = result 2
* Apex output of what the label should be
* DocuSign Salesforce class
* mail merge tool
* Leverage [DocuSign for Salesforce Apex Toolkit](https://developers.docusign.com/salesforce/apex-toolkit-reference/index.html) to send dynamic `.pdf` files to DocuSign.

* get DocuSign permission to get an API key
* Bulk requests do not work with DocuSign API

* Add variables to the record
* Update the record
* Define variables and selection value
