CAR RENTAL APP

Django Car Rental Project
This is a Django-based Car Rental project with 3 User Groups: Customers, Car Owners, and Drivers. Car Owners can upload cars they want to get rented, view each car's rental history, change, update, read and delete their uploaded cars. They can also search for cars in their dashboard and the homepage, rent a car if it's not theirs, receive payments using Paynow with the price they specify, and get their car rented for the time below the number of days they specified after the rental is complete. Car owners get a late return fee per hour, which is a price they also specify. Chauffeurs can upload their details, their driving experience, get rated, get booked and get paid per hour by the customer. The number of hours they work on a certain rental will be calculated from the number of days the customer is renting a car. They get paid after the job is done, and the customer has confirmed it's indeed done. Customers have their own homepage and can view all the cars in the system, rent them, choose a chauffeur in their rental form if they want one, view their car rental history in their history dashboard, rate cars, and rate chauffeurs.

Installation
Clone the repository using git clone https://github.com/wadzamurombedzi/CarRentalApp.git.
Create a virtual environment using python -m venv env.
Activate the virtual environment using source env/bin/activate.
Install the dependencies using pip install -r requirements.txt.
Run migrations using python manage.py migrate.
Create a superuser using python manage.py createsuperuser.
Run the development server using python manage.py runserver.
Entities
Customers
Customers have their own homepage and the following permissions:

View all the cars in the system.
Rent cars (if they are not already rented).
Choose a chauffeur in their rental form if they want one.
View their car rental history in their history dashboard (if they have rented any).
Rate cars.
Rate chauffeurs.
Car Owners
Car owners have the following abilities:

Upload the cars they want to get rented.
View each of their car's rental history (customer and chauffeur (if there is one)).
Change, update, read and delete their uploaded cars.
Search cars in their dashboard and in the homepage.
Rent a car if it's not theirs.
Receive payment using Paynow with the price they specify and get their car rented for the time below the number of days the customer specified after the rental is complete.
Receive a late return fee per hour, which is a price they also specify.
Chauffeurs
Chauffeurs have the following abilities:

Upload their details and their driving experience.
Get rated.
Get booked and get paid per day by the customer. The number of hours they work on a certain rental will be calculated from the number of days the customer is renting a car.
Get paid after the job is done, and the customer has confirmed it's indeed done.
Payment
*On booking, the customer pays in full. *The payment for the car owner and that of the driver will be put to their respective accounts after the rental is done, for the min time, it will be in the account and under the supervision of the Platform Company or under capture. *If the number of rental days is over and the customer does not confirm, their money is refunded. *Completed rentals and payments will be saved as such in the database as well as uncompleted rentals. *The chauffeur and the car owners offer their bank account in their profiles. *This account is where the money will be sent after the rental process is complete, as mentioned in the above logic.

Images and Links
carrental (2) 
