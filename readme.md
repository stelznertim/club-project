This will be a project simulating a football club with his members, games etc.
It should be displayed on a homepage eventually but the order of implementation will be:
Frontend basic architecture -> backend basic functionality -> db -> higher backend functionality -> polished frontend
Functionality:

- Show Teams, Players in the right team, other roles ( member, coach, president etc) correctly
- Get the game schedules for each team and show the current placement in the table
- Simulate money transactions like salary ,membership fees etc
- Have a news-blog on the website

###### Frontend

Navbar: Home - History - Teams - Committee - Become a Member - Login

### Home

Display News like the latest results, media articles etc

### History

Relevant information regarding the history of the club (simple pictures with text)

### Teams

Dropdown with all teams and team pictures as well as the table and all players in the respective team

### Committee

Information about Important members with special roles and their socials to contact them

### Become a member

Link to a signup form and all information needed to become a member

### Login

Login for members

###### Backend

### Team

Create
Edit
Delete
Signup for League
Get/Create Schedule

### Member

Signup
Get status/role/membership time
Leave the club

### Table

Set start date
Create Schedule

### Notification

### Chatbot

###### Database

Table (Team ID*, Team Name, Current Standing, Points, Goal Differential)
Team (Team ID*, Member ID*, Player Name, Goals, minutes played, is_captain, is_team_committee_member)
Member (Member ID*, Age, Height, Club membership time, team name, committee_role)
