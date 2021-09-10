# RPA - UiPath
- We do the demo on features of UiPath with UiStudio Comunity
- We are only have one main branch included many folder on each prject on one feature demo.

## I. BlankProcess project
- Open Website URL.
- Copy one text in this page.
- Pasted it on the notepad file
- And save it. 
[ ] Check if the file is existed and we halding with the confirm message box to override it.
[ ] If it is not, we will save it in the normal way.
- Refferal Links:
> [Basic process](https://docs.uipath.com/studio/docs/creating-basic-process)
> [Notepad processing](https://www.geeksforgeeks.org/robotic-process-automationrpa-notepad-automation-using-uipath/)
> [Checking file](https://docs.uipath.com/activities/docs/file-exists-x#section-studiox)

## II. Computer Vision (CV) 
* UiPath see the Remote Desktop as an Image. So this CV is one of the best tool to determine which is exactly our element working with.
* We have one workflow covering on 03 main tasks(sequences)
	** Open Remote Desktop(RDP)
	** Open [webform](https://formsmarts.com/html-form-example) in RDP, input data to text box and select on item in combobox.
	** Extract [table data in picture](https://dbbpm3ytedt1jhvea17qwiw1-wpengine.netdna-ssl.com/wp-content/uploads/www.displayr.com/wp-content/uploads/2017/10/ca1.png) and save it to excel file in RDP.
* Make sure those below packages installed:
[ ] UiPath.Excel.Activities
[ ] UiPath.System.Activities
[ ] UiPath.UIAtomation.Activities
* Refferal Links:
> [Input text to textbox and select one item in combobox in the webform](https://www.youtube.com/watch?v=WpyP021DhYA)
> [Extract image to table and write it to exel file](https://youtu.be/wjK870yhtqE?t=561)

## III. UIAutomation project
* Inspite on the [UiAutomation demo](https://docs.uipath.com/studiox/v2019/docs/tutorial-working-with-ui-automation) on StudioX with excelX on enterprise, we simulator it again on the community version with Excel feature.
* Make sure those below packages installed:
[ ] UiPath.Excel.Activities
[ ] UiPath.System.Activities
[ ] UiPath.UIAtomation.Activities
* Refferal Links:
> [UiAutoation in UI StudioX](https://docs.uipath.com/studiox/v2019/docs/tutorial-working-with-ui-automation)

## IV. UIAutomationRDP project
*Do the same job of project: UIAutomation which running in the Remote Desktop from machine running RPA.
* Make sure those below packages installed:
[ ] UiPath.Excel.Activities
[ ] UiPath.System.Activities
[ ] UiPath.UIAtomation.Activities
* Refferal Links:


## V. ComputerVisionFeatures project
* It handles 03 main task on below:
[ ] 1) Print 2 sheets from the Excel spreadsheet to PDF and merge the PDF
[ ] 2) Export another sheet to CSV file
[ ] 3) Send e-mail(on Gmail) to respondents with standardised text andattached csv inside.

* Make sure those below packages installed:
[ ] UiPath.Excel.Activities
[ ] UiPath.PDF.Activities
[ ] UiPath.Mail.Activities
[ ] UiPath.System.Activities
[ ] UiPath.UIAtomation.Activities
[ ] ExceltoPDFConversion.Activities

* Refferal Links:
> [User SMTP in UiPath](https://forum.uipath.com/t/send-smtp-mail-message-using-gmail/1256)
> [Config GMail to used in ton UiPath](https://docs.uipath.com/installation-and-upgrade/docs/studio-enabling-gmail-for-email-activities)
> [Enable 2 Steps Authorization in GMail](https://support.google.com/accounts/answer/185839)

## VI. AddDataToOrchestratorQueue project
* How to add data to the Orchestrator Queue
[ ] Create one Queue in Orchestrator
    Home/Orchestrator Services/Click on Talent Name/Click To Queue ==> Create as normal
[ ] Reading data in excel file.
[ ] Push all data to that quere

* Make sure those below packages installed:
[ ] UiPath.System.Activities
[ ] UiPath.UIAtomation.Activities
[ ] ExceltoPDFConversion.Activities

* Refferal Links:

