## Entities

-  gymnasiums : names, addresses and telephone number.
-  members : unique identifier, last name, first name, address, date of birth and gender.
-  session : a type of sport and a schedule and can accommodate a maximum of 20 members.
-  coach : last name, first name, age and specialty

## Relationships

-  member register-at gymnasium
-  member register-for session
-  coach leads session

## Cardinalities

-  Gymnasium to member (one to many)
-  member to session (one to many)
-  coach to session (many to many)
