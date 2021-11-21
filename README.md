# ROI HR Contacts App Tutorial
A React Native App for managing the contact information of people who works in the company.


## 1. All Contacts Screen (Home)

<img src="/tutorial/ROIApp_AllContacts_Home.jpg" width="200" align="left">
<img src="/tutorial/ROIApp_AllContacts_HomeFunctions.jpg" width="200">

- On start up, the app will display a list of all the contacts. Each record is displayed inside a card with the contact’s **name** and **phone number**.
- On top of the list you will see two text inputs. One allows you two search a user by **name** and the other by the employee's **Id** number.
- Bellow the two search inputs there is a drop-down list that will filter the list by the selected ROI department.
- In the right top corner of the screen, inside the header. There is a button to add a new contact to the list.

## 2.	Search by name
- To search for a user by her/his name, start typing the name in the text field, the app will automatically filter the contacts list as you type.

<img src="/tutorial/ROIApp_AllContacts_SearchByName.jpg" width="200">

## 3.	Search by Id
- If you know the **Employee Id Number** of a specific Contact, just type it in the **Id search field** and **press enter** in the keyboard.
- If a Contact with that Id exists, the app will take you to the details page or will display a message if the contact was not found.

<img src="/tutorial/ROIApp_AllContacts_SearchById.jpg" width="200">

## 4.	Filter by department
- To see all the contacts in a Department, select the department from the drop-down list and press the filter button(funnel).

<img src="/tutorial/ROIApp_AllContacts_FilterByDepartment.jpg" width="200" align="left">
<img src="/tutorial/ROIApp_Home_FilteredResults.jpg" width="200">

- After the filter is applied you will see only the contacts of the selected department. To reset the list to see all the contacts, select **All departments** from the dropdown and press the filter button again.

## 5.	Add Contact
- When the Add contact  button is pressed you will be taken to the **New Contact** page. Here you can add a new contact by filling the required fields. ***Note that all fields are required.*** If some field is missing, the app will display an error message.

<img src="/tutorial/ROIApp_NewContact_AddingNewContact.jpg" width="200">

- To save the contact simply press the **Add contact** button at the bottom of the screen. If everything went fine, a success message will be displayed. 
- In the unlikely event of a network failure a message will appear with details of the error.

## 6.	Contact details
- You can easily navigate from the **Home** screen to the contact’s details page by pressing the green arrow on the right side of the contact’s card.
<img src="/tutorial/ROIApp_AllContacts_DetailsButton.jpg" width="200">

## 7.	Details Screen
- This page displays all the details of the contact. From this page you can **edit** the contact information or **delete** the contact.

 <img src="/tutorial/ROIApp_Details_DetailsScreen.jpg" width="200">

## 8.	Deleting a Contact
- You can delete the contact displayed in the contact details screen by pressing the **trash bin** icon in the top right corner of the screen. A message will appear to confirm the operation. *Note that it might take a few moments for the contact to disappear from the contacts list in the home screen.*

<img src="/tutorial/ROIApp_Details_DeleteConfirmPrompt.jpg" width="200" align="left">
<img src="/tutorial/ROIApp_Details_DeleteSuccessMessage.jpg " width="200">

## 9.	Editing a Contact
- To edit the contact’s details simply press the **Edit contact** button bellow the contact’s info, this will take you to the **Edit contact** screen.

<img src="/tutorial/ROIApp_Details_DeleteConfirmPrompt.jpg" width="200">

## 10.	Edit Contact Screen
- When you navigate to this screen all the input fields will be prefilled with the contact’s current details. 
- You can modify any of the fields and then press the **Save changes** button.  Just *remember that all the fields are required* and if you try to save a contact with missing information the app will reject the operation and an error message will appear.
- If everything goes well a success message will be displayed.

<img src="/tutorial/ROIApp_EditContact_EditContactScreen.jpg" width="200" align="left">
<img src="/tutorial/ROIApp_EditContact_ErrorMessage.jpg" width="200" align="left">
<img src="/tutorial/ROIApp_EditContact_SuccessMessage.jpg" width="200">

## 11.	Going back
a.	Except for the home screen (All Contacts), at any point, you can **navigate** without saving any changes to the previous screen by pressing the left pointing arrow at the top left corner of the screen. 

And that's pretty much it, cruisy 🤘 :grin:
