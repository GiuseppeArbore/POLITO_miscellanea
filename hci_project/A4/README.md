## Project name: MEOW

## Prototype selection

### List of Violations

#### Prototype 1 - Mobile

Evaluator 1: Francesca (E1)
Evaluator 2: Roya (E2)
Evaluator 3: Fakhriddin (E3)
Evaluator 4: Francesco (E4)

1. H1 Visibility of system status (E1)
   Where: Activity list (both map and list)
   What: Filters that have been applied are not visible.
   Why: Users need to be able to see the active filters to understand the current state of the system.
   Severity: 3

2. H1 Visibility of system status (E1)
   Where: Icebreaker game page (moderate task)
   What: The game ends with no feedback message indicating completion.
   Why: Users need to be informed when a task is completed.
   Severity: 3

3. H1 Visibility of system status (E1 - E2)
   Where: Bottom navbar
   What: The active section in the navbar is not highlighted.
   Why: Users need clear visual feedback on where they currently are within the app.
   Severity: 3

4. H1 Visibility of System Status (E4)
   Where: Bottom navigation icons
   What: Icons lack accompanying text labels (e.g., "World," "Backpack," or "User") to indicate their purpose.
   Why: Without text, users might struggle to understand the icons' functions, leading to usability issues.
   Severity: 3

5. H2 Match Between System and Real World (E4)
   Where: "Join Activity" page
   What: The "Local Legend" checkbox is present on the main page instead of being limited to filtering options.
   Why: Filtering controls are typically associated with search settings, not main interfaces, which can mislead users.
   Severity: 2

6. H3 User Control and Freedom (E4)
   Where: "You're [not] a local legend for [city]" screen
   What: The bottom "Exit" or "Go Back to Profile" button should replace the top-right "X" to improve navigation.
   Why: Users may find it confusing to use inconsistent methods to exit or navigate.
   Severity: 2

7. H3 User Control and Freedom (E4)
   Where: Accepting/Leaving an event
   What: Missing confirmation message when a user accepts or leaves an event.
   Why: Without a confirmation, users may make unintended changes without an option to review or cancel their actions.
   Severity: 3

8. H3 User control and freedom (E1)
   Where: Icebreaker game page
   What: After a round ends, users must manually restart the game if they want to play another round.
   Why: Users should be able to easily continue playing without having to manually restart the process. Returning to the pre-game page after the end of a round adds unnecessary steps.
   Severity: 3

9. H3 User control and freedom (E1)
   Where: Map page, event pop-up
   What: The event pop-up on the map doesn’t have a way to be closed.
   Why: There's no way for the user to exit this state when he’s done.
   Severity: 3

10. H3 User Control and Freedom (E1)
    Where: Navigation between activities
    What: There is no direct access to the activity list from the navbar. Users must go through the homepage form each time to view or search for activities.
    Why: This creates unnecessary steps for users who may want to quickly review or book new events.
    Severity: 3

11. H4 Consistency and Standards (E4)
    Where: Navigation arrows
    What: Inconsistent arrow colors (some are black, others white).
    Why: Users expect consistent visual cues; deviations can cause confusion and reduce interface clarity.
    Severity: 2

12. H4 Consistency and standards (E1-E2)
    Where: Map
    What: Sorting options can be selected from the map, but they only affect the list of activities, with no visible changes on the map.
    Why: The presence of a sorting icon on the map suggests that sorting will apply there as well.
    However, since no changes are visible, it creates confusion and misleads users into thinking the feature is broken or ineffective.
    Severity: 3

13. H4 Consistency and standards | H8 Aesthetic and minimalist design (E1)
    Where: Activity list page
    What: Each activity banner includes a play button icon, despite the entire banner already being clickable.
    Why: This creates confusion about where users should click to interact with the activity and introduces redundant elements.
    Severity: 2

14. H5 Error prevention (E1 - E4)
    Where: Activity page
    What: There is no confirmation pop-up when users click "Join" or "Leave" an event.
    Why: Lack of confirmation can lead to accidental actions because users might accidentally click the join/leave button without intending to.
    Severity: 3

15. H7: Flexibility and efficiency of use (E3)
    Where: filtering event page
    What: No way to filter events by type (e.g., cultural, adventure)
    Why: Users cannot filter events according to specific interests, which would make it easier to find relevant activities. You can filter only outdoor or indoor event and amount of people
    Severity: 2

16. H8 Aesthetic and minimalist design (E1)
    Where: Activity list page
    What: The activity list shows excessive information about each event without requiring the user to click on it.
    Why: Presenting too much information without the need for user interaction complicates the interface and can overwhelm users.
    Severity: 2

17. H8 Aesthetic and minimalist design (E1 - E4)
    Where: Sorting in the activity list
    What: Ascending/descending buttons appear unnecessarily next to the title "Sort", even though they are already placed beside each criterion.
    Why: Placing redundant buttons next to the title adds unnecessary elements, reducing clarity of the interface and potentially confusing users.
    Severity: 2

18. H8 Aesthetic and Minimalist Design (E4)
    Where: Profile page
    What: An unnecessary arrow is present, even though the bottom navigation icons already provide a way to go back.
    Why: Redundant elements clutter the interface unnecessarily.
    Severity: 2

#### Prototype 2 - Mobile with AR

Evaluator 5: Francesco Passiatore, s332821 (E5)
Evaluator 6: Marco Sportelli, s332224 (E6)

1. H1 Visibility of system status (E5)
   Where: Profile Page (Task: Become a local for a city)
   What: The score is missing, It’s unclear if the user becomes a “local legend” in every case
   Why: Users should be continuously informed of their current status in the system.
   Severity:2

2. H1 Visibility of system status (E5)
   Where: Page where you choose which game to play (Task: Do an icebreaker activity)
   What: It’s unclear how to start a game due to the lack of a “Play” button.
   Why: The system should clearly indicate the next steps and available actions.
   Severity: 2

3. H1 Visibility of system status (E5)
   Where: Page Joined Events
   What: Missing status of event
   Why: The user might want to decide which event to participate based on the number of participants at that moment
   Severity: 3

4. H1 Visibility of system status (E6)
   Where: Event selection screen.
   What: There is no clear feedback about the proximity required to access the event, leaving users uncertain about whether the event is available to them.
   Why: The lack of visibility regarding proximity creates confusion and prevents users from effectively planning their interaction with the event.
   Severity: 3

5. H2 Match between system and the real world (E5)
   Where: Home page
   What: The “Home” button is unnecessary on the home page and unclear as being a “Home” button
   Why: Using a clearer label or icon would make the button more understandable and align with common conventions
   Severity: 2

6. H2 Match between system and the real world (E5, E6)
   Where: Profile Page ( Task: Become a local for a city)
   What: “Became a local legend” is unclear in its purpose
   Why: The lanhuage should be more user-frinedly and clearly describe the action or benefit associated
   Severity : 2

7. H3 User control and freedom (E5, E6)
   Where: Page description of Event, Page Games, Page “Play Game /Leave the event”, Pages quiz
   What: Missing “Back” button
   Why: Users should always have a clear option to go back
   Severity: 4

8. H3 User control and freedom (E5)
   Where: Pages quiz
   What: It’s not possible to navigate through questions
   Why: Users should be allowed to go back or modify their responses.
   Severity: 3

9. H3 User control and freedom (E5)
   Where: Page “Play Game /Leave the event”
   What: If the user doesn’t want to play but doesn’t want to leave the event ether, they are forced into a binary choice
   Why: Users should have more options, such as staying in the event without playing.
   Severity: 2

10. H4 Consistency and standards (E5)
    Where: Page of games
    What: The “Rules” buttons are not clearly identifiable as buttons.
    Why: Buttons should be designed to be easily distinguishable from other content
    Severity: 3

11. H4 Consistency and standards (E5)
    Where: Page “Joined event”
    What: The “Leave the event” button implies that the user is already in the event, yet it asks “Are you at the event?” afterward.
    Why: This inconsistency in messaging can confuse users and make the system seem illogical.
    Severity: 3

12. H4 Consistency and standards (E6)
    Where: Final quiz screen.
    What: The button to return to the homepage differs from similar buttons used for the same action elsewhere in the interface.
    Why: Inconsistency in button design can disorient the user and create confusion.
    Severity: 2

13. H5 Error prevention (E5)
    Where: Page Game, Page “Joined event”, Page “Play Game /Leave the event”
    What: There is no confirmation prompt when attempting to leave game
    Why: Lack of confirmation prompt exposes users to unintentional errors.
    Severity: 2

14. H5 Error prevention (E6)
    Where: Quiz for becoming a Local Legend, at the city input step.
    What: The user is required to input a city to start the quiz, but there is no list of available cities, and no validation to prevent incorrect or irrelevant entries.
    Why: Without a list of predefined cities or input validation, users are allowed to enter any text, which can lead to incorrect or invalid city names, complicating the process and reducing the accuracy of the results.
    Severity: 3

15. H7 Flexibility and efficiency of use (E6)
    Where: After entering a code to confirm attendance at the event.
    What: The buttons for "play a game" and "leave the event" do not clearly explain what happens when each option is selected.
    Why: The lack of flexibility in offering a clear path for the different states of the user affects usability.
    Severity: 2

16. H7 Flexibility and efficiency of use (E6)
    Where: Roulette game.
    What: The game requires the phone to be held in hand to play, but this is neither practical not efficient.
    Why: This limits usability, especially in social settings where holding the phone may not be feasible.
    Severity: 3

17. H8 Aesthetic and Minimalist Design (E6)
    Where: Confirmation banner for event attendance.
    What: The "No" button, which indicates not attending the event, is placed outside the confirmation box.
    Why: The incorrect positioning of the button compromises clarity and the aesthetics of the design, confusing the user.
    Severity: 3

18. H9 Help Users Recognize, Diagnose, and Recover from Errors (E6)
    Where: Confirmation code entry screen.
    What: There is no error banner or feedback when an incorrect code is entered.
    Why: Without error messages, users cannot recognize that their input is invalid or understand how to correct the issue, leading to frustration and a poor user experience.
    Severity: 4

19. H10 Help and Documentation (E5, E6)
    Where: Home page
    What: Missing help button, for use of the app
    Why: A manual could help the user to understand how to use the app
    Severity: 3

### Selected Prototype, feature moved and why

We have decided to use the "mobile prototype" (prototype 1) as it is more suitable and intuitive for use and for completing tasks.
Additionally, some features of the "AR prototype" (prototype 2) will be integrated into the chosen one:

- Once a user joins an event, when the event begins, the creator will be notified with a code that participants must enter to confirm their presence at the event.
- The screen with the list of games has also been integrated.
- When the event starts and the "icebreakers" button is pressed, the screen with the list of games will be displayed instead of just one game, providing more options to choose from.
- Moreover, we have decided integrate the quiz mode from the "AR prototype" with the quiz already available for becoming a Local Legend in the chosen prototype.
  We have decided to integrate these features because they increase playfulness and user interaction with the app.

## Prototype

We have chosen to showcase the two following screens because they represent two important tasks while also highlighting several elements that we fixed:

- Map page, violations solved:

  - p1_v1: Filters are showed over the map
  - p1_v3: The active section in the navbar is highlighted
  - p1_v4: Icons have a label
  - p1_v9: The event-popup on the map has a button to close and one to go to the details.
  - p1_v10: The HomePage now show the events list or the map according to the segmented control above the page.
  - p1_v12: The sort option has been removed because useless
  - p1_v13: The entire banner is clickable, we've remove the "play game" button.
  - p1_v15: The possibility to filters events by type has been added in the filter module.

- Game list page, violations solved:
  - p1_v3: The active section in the navbar is highlighted
  - p1_v4: Icons have a label
  - p2_v2: Added a play button to start the icebreaker
  - p2_v10: An arrow is showed on each box

### Link to Figma

[Link to Figma Prototype](https://www.figma.com/design/1HE7wcEhvrRXW1zbDDHWrK/A4_MEOW)

## Plan for the hi-fi Prototype

The plan for the high-fidelity prototype is to sketch a paper prototype incorporating the improvements made to the chosen prototype and then start its implementation.
The main violations have been addressed and are now corrected in the screens shown above. The unresolved violations are as follows:

- Violations 2-7-14: We will add pop-ups for necessary confirmations and feedback.
- Violation 5: We will leave the Local Legend selection only as a filter
- Violation 6: We will replace the "x" button with a more appropriate and intuitive labeled button.
- Violation 8: Depending on the game, the user will play multiple rounds without exit the game.
- Violation 11: We'll make arrows more consistent
- Violation 16: We'll remove some informations as the number of people
- Violation 17: We will remove the sort feature entirely because useless.
- Violation 18: We'll remove the arrow from Profile page.
