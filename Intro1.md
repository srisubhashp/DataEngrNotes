# Data Vault Video1
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/4c3f6155-279e-4a51-993c-07792ffba2bc">
* We have hubs so that we can tie the data to the business process. (for example, to do a delta process we need a consisten business key).<br>
* We have a many to many rules for LINKS for a business process bcz rules change over time, The last thing we need to do is to re-engineer a data model because a rule changes. Data Warehouse should be rule agnostic.<br> 
- (We can test the source application's ability to enforce the business rule at the source system level.<br>
- Sataellites are descriptive information. 
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/426777fe-45e1-477d-b967-5096da3a50e5"> 
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/589e96fe-7241-4cab-ac8e-3b44e1083968">
- Hard rules dont change such as data type mapping, data normalization. <br>
- With this differentiation in rules we can create a Data Warehouse with rules that dont change over time and we can build BI Solutions ( one to many). As long as we backing up the version control of the rules we used earlier. 
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/fbb5b309-3f66-4fc6-bab7-d2a80aaa0706">
IN the above photo, once for a electronic health record. First if we have only one hub, later based on the updated business rule we can connect another hub with a link and build it up along the way. Without fundamentally designing it again from scratch, <br>
- This can potentially create many objects in your data warehouse layer, or many tables in our datawarehouse layer. Its mainly how we manage<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/5650ccee-4f53-4ff1-925a-75d6bec7add5">
 them and the cost of maintenance is and how agile we are.<br> 
- Thought process behind creation of data vault. <br>
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/866f09fb-8b86-4903-9228-01b8968683db">
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/a4bfe871-fcc9-4eaf-98d5-5024faf1059e">
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/61bb6071-57b0-4217-a428-57ad9d57726b">
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/157df2fa-da5b-4190-b5ea-8b359100cd15">
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/5dfd498f-442a-456f-bf4f-ebfdab70048f">
- Department of Defense and even in health records we can use it to identify records that are vulnerable. 
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/092f35b7-fe5f-4529-9b22-018047136e9a">
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/9511967f-d6fd-49cc-8ef8-8dfdf347f28c">
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/d70b00cb-9a8c-4ed3-a0b7-f37e10c86f28">
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/12bf0eba-61d7-480c-b8de-630a7d3234de">
- in the first story, the company could not handle more data incoming due to insufficient resources. We need to mature our data warehouse from batch to a real time solution. 
<img width="1080" alt="image" src="https://github.com/srisubhashp/DataEngrNotes/assets/55814483/fe9560f4-5a4c-464c-bd1b-8a0c3ed2cb6b">
- The second company was able to eliminate a landing zone and staging area. <br>
------













