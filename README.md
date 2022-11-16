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

<b>The following types of testing will be introduced:</b><br>
<ul>
<li> Functional (at the system level, at the integration level, at the component level) </li>
<li> UX/UI </li>
<li> API Testing </li>
</ul>

<br>
 
<b> Functional and non-functional testing: </b>
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

2. Regression testing: <br>
Check-list: [GoogleForms](https://docs.google.com/spreadsheets/d/11lGdAUcPdgT6_QC5UakRav8jw0p9qTYpEZXBPFVAcd8/edit?usp=sharing)



