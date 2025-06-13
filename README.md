# Farmbridge

This application was developed in collaboration with William Borruat, Nitin Satishbabu and Emily Rodden. 

The app that we have built is a supplier relationship management app called FarmBridge, which focuses on agriculture. The app makes it easy for businesses to keep track of supplier visits and tasks that are associated with those visits. 

Firebase Authentication manages user authentication and allows users to sign up or log in to an existing account. The primary interface of the app is a navigation bar that allows users to access pages, including the homepage, suppliers page, visits page, tasks page and settings page. The user is first greeted by the homepage, which provides a pie chart with a breakdown of completed, in progress and not started tasks. 

It also contains an overview of the number of tasks/visits and shows upcoming supplier visits. Users of the app can add new suppliers to the database (using Firestore) and view existing suppliers. They can then create new visits based on the list of suppliers and add information such as the date, type of visit and notes. When a new visit is created, it automatically creates a series of tasks associated with that supplier visit. The tasks can be viewed with different filters, such as the status of the task (e.g. completed, in progress) and can be edited if necessary. 

The application includes a notifications page, which will show upcoming tasks. Finally, there is a settings app which contains important information and allows the user to sign out and return to the signup/login page.
