## Question 1 - Requirements

The following workflow describes a very basic navigation workflow on our corporate website.

1. In a browser navigate to http://www.glasslewis.com 

2. Navigate to the client login link on the top right of the page here:

3. From the dialog click on the Viewpoint Voting Platform link here:

4. That should bring you to the following page https://viewpoint.glasslewis.com/ 

5. On that page click on the “Sign In” button

6. An error message should be displayed: The fields USERNAME and PASSWORD are required.

Based on this workflow can you:

* Write up a clean user story including “description” and “acceptance criteria” to cover the sign in validation functionality on the login page. Please use whatever syntax for the acceptance criteria that you feel is most appropriate.

### User Story
#### Description:
As a Glass Lewis user, when I navigate to http://www.glasslewis.com, click on the login button & select the Viewpoint Voting Platform option I should be taken to a login page  
If I click "Sign In" without entering any details I should get an error displaying: "The fields USERNAME and PASSWORD are required."

#### Acceptance Criteria:
* Glass Lewis user should be able to navigate to the Viewpoint Voting Platform page
* Clicking "Sign In" without entering any details should display an error message

#### Acceptance Criteria as BDD:
GIVEN user is on the landing page for Glass Lewis site  
AND the user selects Viewpoint Voting Platform from the login options in the top right of the page  
WHEN clicks on the Sign In button without entering any credentials  
THEN the login page should display an error message stating: "The fields USERNAME and PASSWORD are required."