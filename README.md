# contact_search
This repo has two submodules
1) contact_search_fe: It contains UI part in React
This is a single page React app. Where we have an input field where we can search for the name or contact_number and we can also use a keypad. The typed value is searched for every change. 
A list of contacts is displayed depending upon the result given by our search. When we click on any contact the details of the contact are shown in the modal.

2) contact_search_be: It contains backend part in RubyOnRails
Created a table Contact with columns name, email and contact_number. The table is stored in 
SQLlite relational database and some dummy data is created in the table. 
In the Contact model we have validations for name, email and contact_number.
Then a search api is created which takes searchKey as the params and gives back the result where name or contact_number are like that searchkey.

I am using Rack-cors gem to establish cross origin api requests.

Here attaching some pictures.
Laptop view:
<img width="1431" alt="Screenshot 2023-12-06 at 10 14 45 AM" src="https://github.com/saurav00679/contact_search/assets/43717443/faa71b7b-b9ab-4cb7-a594-5621325331cb">
<img width="1440" alt="Screenshot 2023-12-06 at 10 15 05 AM" src="https://github.com/saurav00679/contact_search/assets/43717443/9e06ec21-b2a8-470a-b5d5-c9e3301512f5">
<img width="1433" alt="Screenshot 2023-12-06 at 10 16 30 AM" src="https://github.com/saurav00679/contact_search/assets/43717443/4539a720-c01b-454d-a256-b7fe3f2ef20c">

Mobile view


<img width="191" alt="Screenshot 2023-12-06 at 10 15 50 AM" src="https://github.com/saurav00679/contact_search/assets/43717443/7ba6b2b2-703f-4320-adbf-aa56c497897b"><img width="191" alt="Screenshot 2023-12-06 at 10 16 00 AM" src="https://github.com/saurav00679/contact_search/assets/43717443/fe9616e5-d643-48a8-bca2-b3ef11522cf2">

<img width="196" alt="Screenshot 2023-12-06 at 10 16 16 AM" src="https://github.com/saurav00679/contact_search/assets/43717443/582b329f-d56e-488e-ba17-5e61b6f65cea">
