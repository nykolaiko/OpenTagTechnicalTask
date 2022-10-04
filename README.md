# OpenTagTechnicalTask

## Preconditions:
1. Assumed Postman is already installed.
2. Assumed the 'OpenTagTechnicalTask' folder is downloaded.

## Steps:

### Import folder in Postman
1. Open Postman.
2. Click on the 'Import' button.
3. Select 'Folder' tab in the 'Import' pop-up.
4. Click on the 'Choose folder from your computer' button.
5. Select the previously downloaded folder.
6. Click on the 'Open' button.
7. Click on the 'Import' button.

### Set-up environment
1. Click on the 'Environment' drop-down list.
2. Select the "graphql.org" option.
3. Click on the 'Environment quick look' icon on the sidebar.
4. Observe that all variables except the 'base_url' are not set.

### Run requests

#### Task 1
1. Click on the 'Working with GraphQL API' collection to expand it.
2. Select the '1.1 Query all Films "id", "title" and set value to "a_new_hope_id" variable' request.
3. Click on the 'Send' button.
4. Click on the 'Environment quick look' icon on the sidebar.
5. Observe the value of the 'a_new_hope_id' variable is set.
6. Select the '1.2 Query all Species in "A New Hope Movie" and store their names into "a_new_hope_all_species" variable' request.
7. Click on the 'Send' button.
8. Observe the response.
9. Click on the 'Environment quick look' icon on the sidebar.
10. Observe the value of the 'a_new_hope_all_species' variable is set.

#### Task 2
1. Select the '2.1 Query DroidID and set value to "droid_id" variable' request.
2. Click on the 'Send' button.
3. Click on the 'Environment quick look' icon on the sidebar.
4. Observe the value of the 'droid_id' variable is set.
5. Select the '2.2 Query “name”, “birthYear”, “homeWorld”, “eyeColor” for the person “Droid”' request.
6. Click on the 'Send' button.
7. Observe the response.

#### Task 3
1. Select the '3. Query "totalCount",  “id”,  “name” and  “gender” of all people that have participated in the movie' request.
2. Click on the 'Send' button.
3. Observe the response.

#### Task 4
1. Select the '4.1. Query "id" of all People and set value to "person_id_4" variable' request.
2. Click on the 'Send' button.
3. Click on the 'Environment quick look' icon on the sidebar.
4. Observe the value of the 'person_id_4' variable is set.
5. Select the '4.2 Query “name”, “birthYear”, “homeWorld”, “eyeColor”, "starshipName"  for the person with "id = 4" request.
6. Click on the 'Send' button.
7. Observe the response.
