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
	** Open webform in RDP, input data to text box and select on item in combobox.
	** Open webform in RDP, extract table data in picture and save it to excel file.
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
