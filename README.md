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
Mobile View:


<img width="189" alt="Screenshot 2023-12-06 at 1 15 34 PM" src="https://github.com/saurav00679/contact_search/assets/43717443/69d653fd-15e5-44e9-8ed4-785c01a51a61">
<img width="192" alt="Screenshot 2023-12-06 at 1 16 19 PM" src="https://github.com/saurav00679/contact_search/assets/43717443/59d0470f-d5c4-4688-b845-14349a4cf7a4">
<img width="192" alt="Screenshot 2023-12-06 at 1 15 59 PM" src="https://github.com/saurav00679/contact_search/assets/43717443/15984466-677a-4f52-bec5-056247a23878">
<img width="193" alt="Screenshot 2023-12-06 at 1 16 33 PM" src="https://github.com/saurav00679/contact_search/assets/43717443/547d8c6e-c814-4199-b890-c0b944bf96b2">

