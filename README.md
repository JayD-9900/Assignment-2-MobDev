Assignment: Developing a Multi-Fragment App with Shared Preferences
Scenario
You are tasked with creating a mobile application that allows users to personalize their experience by storing their preferences. The app will have multiple fragments, and the data stored in one fragment should persist across sessions and be accessible in other fragments using SharedPreferences.
Assignment Objectives
•	Utilize SharedPreferences to save and retrieve data persistently.
•	Implement communication between fragments to ensure seamless data flow.
•	Enhance user experience by maintaining preferences even after the app is closed.
Requirements
1.	Fragment 1: User Settings
o	Create a fragment where users can input their preferences (e.g., username, email, password, theme color, or notification settings).
o	Save the input data in SharedPreferences when the user taps a "Save Preferences" button.
2.	Fragment 2: Profile View
o	Create a second fragment that retrieves and displays the user preferences stored in SharedPreferences.
o	The displayed data should be dynamically updated whenever the app is reopened or preferences are changed.
3.	Navigation
o	Use a FragmentManager or a ViewPager to switch between the two fragments.
o	Include a navigation bar or buttons for user-friendly fragment switching.
4.	Data Validation
o	Ensure the input data in Fragment 1 is validated before saving.
o	Display a confirmation message upon successful saving.
5.	Persistent Data
o	Use SharedPreferences to persist data so that it is available even after the app restarts.
Deliverables
1.	Application Code: Upload the complete codebase to a version control repository (e.g., GitHub).
2.	Demonstration Video: Record a short video (2-3 minutes) showing the functionality of the app.
3.	Documentation: Submit a brief report explaining: 
o	How you implemented SharedPreferences and fragments.
o	Key challenges and how you overcame them.
