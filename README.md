# Testing Personal-Events
 Testing a new feature on the schedule

<b>New calendar item:</b> `Personal events` <br>
<b>Client:</b> `Skyeng Company` <br>
<b>Website:</b> `https://skyeng.ru/` <br>

<b>Basic Requirements:</b> The teacher can use personal events for their own meetings. They serve as a reminder that the teacher has something planned for this time.
<ul>
<li> Adding personal events. </li>
<li> Deleting personal events. </li>
<li> Editing personal events. </li>
<li> Combining a personal event and a lesson. </li>
</ul>

<br>

<details><summary>Project documentation</summary><br>

We have added a new element to the calendar — `personal events`. <br>
The teacher can use personal events for their own meetings. <br>
They serve as a reminder that the teacher has something planned for this time. <br>

 ![image](https://user-images.githubusercontent.com/115921753/202154586-f287e898-00e2-4a54-8666-169fb0e6ca4c.png)

<h3><b>Operations with personal events:</b></h3><br>
<ins>Adding personal events.</ins><br>
The teacher can add a personal event in two ways:
 
<ul>
 <li> click into the slot, </li>
 <li> click on the plus sign. </li>
</ul>
 
When adding a personal event:
 
<ul>
 <li> The name is a required parameter, but no more than 40 characters. </li>
 <li> Date and time are required parameters. </li>
 <li> Description — optional to fill in, there is no limit on characters. You can't insert pictures at this stage. Markdowns and links are available. </li>
 <li> The event color is gray by default. </li>
</ul>

![image](https://user-images.githubusercontent.com/115921753/202159943-37ccfc58-cfc0-41dc-af64-7b7e858ebb5b.png)

<ins> Deleting personal events. </ins> <br>
To delete a personal event, click on it and click the "Delete" button.
 
 ![image](https://user-images.githubusercontent.com/115921753/202161387-3b834857-8f9e-4bd8-ac55-ea9ff0600eff.png)

<ins> Editing personal events. </ins> <br>
In order to edit a personal event, you need to click on it and click "Edit". <br>
When editing, you can change:

<ul>
 <li> title, </li>
 <li> colour, </li>
 <li> description, </li>
 <li> time. </li>
</ul>
 
![image](https://user-images.githubusercontent.com/115921753/202164925-5d37694b-33d0-41bf-a41d-30d23ec97515.png)

<ins> Combining a personal event and a lesson. </ins><br>
If the event and the lesson coincide in time, the lesson is always displayed above everything. <br>
If two events occur at the same time, the one that was created last is displayed above. <br>
 
![image](https://user-images.githubusercontent.com/115921753/202165484-fab20d20-7d75-47f1-b192-67f7fd6ddd6a.png)
 
</details>

<br>

<details><summary>Requirements testing</summary><br>

| Requirement | Question to requirement |
| ----------- | ----------- |
| The teacher can add a personal event in two ways:<br> - click on the slot, <br> - click on the plus. | The description of the location of the “slot” and “plus" is missing. |
| When editing, you can change: <br> - name, <br> - color, <br> - description, <br> - time. | The possibility of changing the date is missing from the list. |
| When adding a personal event: <br> - The name is a mandatory parameter, but no more than 40 characters. | What are the limitations on the validity/invalidity of the accepted values. |
| Combining a personal event and a lesson. <br> If the event and the lesson coincide in time, the lesson is always displayed above everything. | There is not enough layout to illustrate the correct overlay of the event on the lesson. |
| Deleting personal events. <br> To delete a personal event, click on it and click the "Delete" button. | On the layout, the format of the lesson duration is displayed in minutes. For the convenience of perception, it is worth changing the format to hh:mm. |
| When adding a personal event: <br> - Date and time are required parameters. | There is not enough layout displaying the correct implementation of the date and time selection. |
 
</details>

<br>

<h3>The following types of testing will be introduced:</h3><br>
<ul>
<li> Functional (at the system level, at the integration level, at the component level) </li>
<li> UX/UI </li>
<li> API Testing </li>
</ul><br>
 
<h3> Functional and non-functional testing: </h3>
<details><summary> 1. Testing personal events: </summary><br>
 
<details><summary>Test case: Qase.io screenshots</summary><br>
 
![image](https://user-images.githubusercontent.com/115921753/202199663-248d023a-8ab8-49d6-8c7c-d73408516cb5.png)

![image](https://user-images.githubusercontent.com/115921753/202199808-2f162d9c-5eab-4d68-9d2e-1ddbfde8f06e.png)

![image](https://user-images.githubusercontent.com/115921753/202199884-8a3267d4-b489-4680-b5b3-1ad473af495d.png)

</details>
 
- Check-list: [GoogleForms](https://docs.google.com/spreadsheets/d/1enX6mXvP5Iyqux22HUFBBASAZLnSvlqmW2QBrSLgYHU/edit?usp=sharing)
  
<details><summary> Postman collections: screenshots </summary><br>
 
![Снимок экрана (21)](https://user-images.githubusercontent.com/115921753/202204698-aec6248a-8498-4569-8a49-57747204095f.png)

![Снимок экрана (22)](https://user-images.githubusercontent.com/115921753/202204724-59f371fc-51eb-4c49-acf1-ad8c0fa04d52.png)
 
![Снимок экрана (25)](https://user-images.githubusercontent.com/115921753/202205151-a153bf9c-1555-4d3c-9679-a1f99fd51131.png)

![Снимок экрана (23)](https://user-images.githubusercontent.com/115921753/202205170-19c5fc97-95b3-4dd8-a02e-5d5bba017ee3.png)

![Снимок экрана (26)](https://user-images.githubusercontent.com/115921753/202205231-1d1a6724-04d6-4149-bdf9-53de94f2871f.png)
 
![Снимок экрана (27)](https://user-images.githubusercontent.com/115921753/202205504-852eb1c1-fa90-4f77-9d5f-1c8f0b5e0407.png)

![Снимок экрана (28)](https://user-images.githubusercontent.com/115921753/202205541-1069e7d3-74e3-4476-8228-638889cb9878.png)

![Снимок экрана (29)](https://user-images.githubusercontent.com/115921753/202205607-f8aa0e7c-bb95-4f3b-9bae-1bdabb545549.png)

![Снимок экрана (30)](https://user-images.githubusercontent.com/115921753/202205635-bf48cf68-96fd-4a0b-9116-79e05cfd249e.png)

</details>
 
<details><summary> Postman testrun: screenshots </summary><br>
 
![Снимок экрана (32)](https://user-images.githubusercontent.com/115921753/202204111-2a4bb77b-b46f-42c7-a33e-4e2884118bc1.png)

![Снимок экрана (33)](https://user-images.githubusercontent.com/115921753/202204121-d546b915-6138-4ff0-8523-736ae6ac3599.png)

</details>
  
</details>

2. Regression testing: Check-list: [GoogleForms](https://docs.google.com/spreadsheets/d/11lGdAUcPdgT6_QC5UakRav8jw0p9qTYpEZXBPFVAcd8/edit?usp=sharing)

<details><summary> 3. Smoke testing </summary><br>
 
<details><summary> Test case </summary><br>

![image](https://user-images.githubusercontent.com/115921753/202216191-f27a9591-e02d-4902-b9b3-36f6855f7b14.png)

![image](https://user-images.githubusercontent.com/115921753/202216392-a1697d1d-a979-4115-aea9-cb4bff62a53d.png)

![image](https://user-images.githubusercontent.com/115921753/202216488-6468e6b0-c052-4604-aa10-92777d2084c9.png)
 
</details>
 
<details><summary> Test run </summary><br>

![image](https://user-images.githubusercontent.com/115921753/202216614-058c5dc0-9d57-412d-9f21-8b4ee9a2f1b3.png)

</details>

</details>

<details><summary> 4. Acceptance testing: </summary><br>
 
![image](https://user-images.githubusercontent.com/115921753/202217490-94eca83a-da1a-4864-ad3c-47b18a4d74ac.png)

</details>

<br>
 
<h3> Product decomposition: </h3>

<b> Mindmap: </b> [Miro](https://miro.com/app/board/uXjVOynerHE=/?share_link_id=275660923440) 

<br>
 
<h3> Test schedule </h3>
 
| Types of testing | Testing dates |
| ----------- | ----------- |
| Functional testing | 22.05-29.05 |
| UI/UX | 22.05-29.05 |
| API Testing | 29.05-1.06 |

<br>

<h3> Test results </h3>

<details><summary> Bug reports on new functionality: </summary><br>
 
![image](https://user-images.githubusercontent.com/115921753/202223196-bdbeab79-3a13-4e58-98d1-542498598472.png)

![image](https://user-images.githubusercontent.com/115921753/202223307-f75d1c99-4e27-4c7a-9b8d-c6e585dfb27f.png)

![image](https://user-images.githubusercontent.com/115921753/202223400-0e6d4dc6-b231-4ab4-bae0-a90548f57d67.png)
 
</details>

<br>

<h3> Final Project Testing Report </h3>

A total of 28 hours were spent on testing the new calendar element “Personal Events“, developing a text plan, test cases and creating a report. Two bugs were found, one of which needs to be fixed as soon as possible to ensure the convenience of using the new calendar functionality.

When testing the API, no critical errors were detected, all events are created, edited and deleted correctly. There is a minor bug when deleting a non-existent event - the status 200 is returned.

The new functionality is ready for release, subject to the prompt elimination of the existing bug with the transfer of a personal event. It does not affect the functionality, because it remains possible to delete an existing personal event and create it again on the required date, it only affects the usability of the new function. You should also replace the date selection from the drop-down list with the date selection from the drop-down calendar.
