**# Django Poll Project**

**Features**
* User-friendly interface for adding custom poll questions
* Ability to vote for options in the poll
* Real-time display of the total votes for each option
* Interactive visualizations to represent the voting results

**Installation and Setup**
1. Clone the repository:
    
3. Create and activate a virtual environment:
    $python3 -m venv env
    $source env/bin/activate
    
3. Install the required dependencies:
    $pip install -r requirements.txt

4. Set up the database:
    $python manage.py migrate

5. Start the development server:
    python manage.py runserver

**Usage**

Adding a Custom Question: As an admin user, navigate to the admin panel and create a new poll question. Enter the question text and provide options for users to vote on.
Voting: Users can select their preferred option from the list of choices and submit their vote. The vote count for each option will be updated in real-time.
Viewing Results: After voting, users can see the updated results of the poll. The results are displayed as a percentage for each option, allowing users to understand the distribution of votes.