Conduct Heuristic Evaluation on 3 designs:

1. Adam's design
2. Anthony's design
3. Ben's design

SEVERITY:
0 = I don't agree that this is a usability problem at all  
1 = Cosmetic problem only: fix if time is available  
2 = Minor usability problem: fixing this should be given low priority  
3 = Major usability problem: important to fix, given high priority  
4 = Usability catastrophe: fix this before product can be released  


## Nagare's Heuristic Evaluation on Adam's design

HEURISTICS: 1. Visibility of System Status
VIOLATION:
- No loading indicators when searching for routes or locations
(- Limited feedback on search progress in the map screen)
RECOMMENDATION:
- Add loading indicators when searching for routes or locations
- Provide feedback on search progress in the map screen
SEVERITY:
- 2
(Strengths:
- Journey duration and distance are clearly displayed
- Selected options show visual confirmation with a checkbox
- Selected options are highlighted
- Scroll indicators show the user where they are
(- Current time is visible in the status bar)
)

HEURISTICS: 2. Match between the System and the Real World
VIOLATION:
- "00:00" time format may not be familiar to all users
RECOMMENDATION:
- Use a more common time format (12-hour format with AM/PM)
SEVERITY: 1
(Strengths:
- Uses familiar icons (folder for saved, magnifying glass for search)
- Bus icon clearly indicates public transportation stops
- Uses natural language like "Origin" and "Destination" instead of technical terms
)

HEURISTICS: 3. User Control and Freedom
VIOLATION:
- No visible "back" button on some screens
- May be difficult to delete saved routes (from Edit icon??)
RECOMMENDATION:
- Add a "back" button to all screens for easy navigation
- Make the "delete" option more noticeable
SEVERITY: 3
(Strengths:
- "Undo Changes" button in settings provides an escape route
- Dropdown menu can be closed with same button
)

HEURISTICS: 4. Consistency and Standards
VIOLATION:
- Dropdown indicators vary in style across screens
(- Inconsistent capitalization ("in app language"))
RECOMMENDATION:
- Ensure consistent dropdown indicators across all screens
SEVERITY: 1
(Strengths:
- Consistent layout across screens
- Standard icons used throughout
- Button styles remain consistent
- Help button "?" is consistently placed
)

HEURISTICS: 5. Error Prevention
VIOLATION:
- No visible constraints on invalid inputs
- No confirmation when saving routes
RECOMMENDATION:
- Implement constraints on invalid inputs (Disable/hide invalid options)
- Add some default values to prevent empty inputs
- Add a confirmation dialog when saving routes or changing some settings
SEVERITY: 3
(Strengths:
- "Impared Mobility Mode" helps prevent accessibility-related issues proactively
- Time selection interface prevents invalid time inputs?
- Radio buttons prevent multiple selections
)

HEURISTICS: 6. Recognition Rather than Recall
VIOLATION:
- Some icons may not be universally intuitive ("Search")
- Could not tell what (...) under "stops" does
- Saved button in search screen required the moment to recognize (Icon is very clear, but did not expect it to be there)
RECOMMENDATION:
- Use more universally recognized icons (This is subjective, discuss with team)
- Provide labels for less intuitive icons
- Location of saved button or condition of the button to be appearing can be adjusted
SEVERITY: 2
(Strengths:
- The tab-bar has only 3 items
- Route details (time, distance) are visible without requiring user to remember them
- Familiar style for transportation applications
- Bottom navigation remains consistent, reducing memory load
)

HEURISTICS: 7. Flexibility and Efficiency of Use
VIOLATION:
- In route selection, not many route modification options are available (Which may require starting over)
- Customization options are limited (Settings allow customization of the app, but not many options are explicitly presented)
RECOMMENDATION:
- Provide more route modification options
- Allow users to tweak routes without starting over (in route selection)
- Add more customization options in settings/ route selection
SEVERITY: 3
(Strengths:
- "Saved" option allows quick access to frequent routes
- "Saved" option seems editable
- Multiple journey options simultaneously displayed
- Options to choose between "Closest Time" and "Shortest Commute"
- Settings allow customization of the app
)

HEURISTICS: 8. Aesthetic and Minimalist Design
VIOLATION:
RECOMMENDATION:
- Space between elements can be adjusted to improve aesthetics
SEVERITY: 0
(Strengths:
- Clean, grayscale interface with minimal distractions
- Information is grouped logically
- Only essential information is displayed
)

HEURISTICS: 9. Help Users Recognize, Diagnose, and Recover from Errors
VIOLATION:
- No error messages are explicitly presented
- No feedback on invalid inputs
RECOMMENDATION:
- Provide clear error messages when invalid inputs are made
- Use traditional error-message visuals, like bold, red text
- Tell users what went wrong in language they will understand
- Offer users a solution, like a shortcut that can solve the error immediately
SEVERITY: 3
(Strengths:)

HEURISTICS: 10. Help and Documentation
VIOLATION:
RECOMMENDATION:
- Provide tutorials for first-time users
SEVERITY: 0
(Strengths:
- Help button and settings are always visible and accessible
)



## Nagare's Heuristic Evaluation on Anthony's design

HEURISTICS: 1. Visibility of System Status
VIOLATION:
- No loading indicators when searching for routes or locations
- No scroll indicators to show the user where they are
RECOMMENDATION:
- Add loading indicators when searching for routes or locations
- Add scroll indicators show the user where they are
SEVERITY: 2
(Strengths:
- Shows the current location with a directional arrow
- Provides clear route options
- Displays waiting times
- Selected options are highlighted
)

HEURISTICS: 2. Match between the System and the Real World
VIOLATION: 0
RECOMMENDATION:
SEVERITY:
(Strengths:
- The map uses conventional colors
- Directional instructions use natural language
- Uses familiar icons
- Displaying each languaage in its own language
)

HEURISTICS: 3. User Control and Freedom
VIOLATION:
- No visible "back" button
- No "Undo" option (While not necessary for presented task)
RECOMMENDATION:
- Add a "back" button to all screens for easy navigation
- Add cancel/undo options
SEVERITY: 3
(Strengths:
- The search bar includes an "X" clear button
)

HEURISTICS: 4. Consistency and Standards
VIOLATION:
RECOMMENDATION:
SEVERITY: 0
(Strengths:
- Standard map navigation elements
- Familiar keyboard layout
- Consistent UI elements
)

HEURISTICS: 5. Error Prevention
VIOLATION:
- The search field doesn't appear to constrain invalid inputs
- Assuming the search field accepts name of the location, emojis are likely to be invalid
RECOMMENDATION:
- Improve the search field capabilities to prevent invalid inputs
- Implement functionality to suggest valid options from user input in the search field
- Disable or hide emoji option from the keyboard
SEVERITY: 3
(Strengths:
- Clear route options with distinct categories help prevent incorrect selections
)

HEURISTICS: 6. Recognition Rather than Recall
VIOLATION:
- User must know the name of the station to search for it
RECOMMENDATION:
- Favourite / recent history options to reduce memory load
- Destination suggestions based on user input
SEVERITY: 2
(Strengths:
- Visual map interface reduces cognitive load
- Transportation icons clearly communicate mode of transit
- Language options in each language reduce user's memory load
- Only search field is in home screen
)

HEURISTICS: 7. Flexibility and Efficiency of Use
VIOLATION:
- No favorite or saving routes functionality
- No personalization options (Dropdown menu in each preference might allow personalization, but not explicit)
- limited customization options (language only)
RECOMMENDATION:
- Provide saving / quick access functionality for frequently used routes
- Allow users to personalize their trip
- Allow user to search route from arrival time
- Allow users to search route from arbitrary location
- Provide more customization options
SEVERITY: 3
(Strengths:
- Multiple route preferences options accommodate different user priorities
)

HEURISTICS: 8. Aesthetic and Minimalist Design
VIOLATION:
- text for real time navigation information is dense, considering the component size
RECOMMENDATION:
- Adjust the text / component size to improve readability
SEVERITY: 1
(Strengths:
- Clean interface with good contrast
- Minimal clutter
- Focused information display
)

HEURISTICS: 9. Help Users Recognize, Diagnose, and Recover from Errors
VIOLATION:
- No error messages are explicitly presented
- No feedback on invalid inputs
- No feedback on no options available
RECOMMENDATION:
- Provide clear error messages when invalid inputs are made
- Use traditional error-message visuals, like bold, red text
- Tell users what went wrong in language they will understand
- Offer users a solution, like a shortcut that can solve the error immediately
SEVERITY: 3
(Strengths:
- Provide clear next steps in navigation
)

HEURISTICS: 10. Help and Documentation
VIOLATION:
- No visible help section
- No visible documentation or settings menu
RECOMMENDATION:
- Provide a help section or documentation access points in the interface
SEVERITY: 2
(Strengths:
- Step-by-step navigation instructions are clear and concise
)

## Nagare's Heuristic Evaluation on Ben's design

HEURISTICS: 1. Visibility of System Status
VIOLATION:
- No progress indicators when exporting to calendar (Assuming it will take time)
- Component size of the departure time is small, considering it is a key information
RECOMMENDATION:
- Add progress indicators when exporting to calendar
- Increase the component size / location of the departure time
SEVERITY: 1
(Strengths:
- toggle buttons clearly indicate user's selection
- Checkboxes are used to indicate selected options
- Scroll indicators show the user where they are
)

HEURISTICS: 2. Match between the System and the Real World
VIOLATION:
RECOMMENDATION:
- Use more intuitive icons to indicate systems / options
SEVERITY: 0
(Strengths:
- Terminology like "Filter Transport" is clear and familiar
- Uses familiar icons
)

HEURISTICS: 3. User Control and Freedom
VIOLATION:
- No "Undo" option (probably remove Saved Plans in this case)
RECOMMENDATION:
- Add an "Undo" option for removing saved plans
SEVERITY: 1
(Strengths:
- Consistent back button in the top left corner
- Home button is always visible / accessible
)

HEURISTICS: 4. Consistency and Standards
VIOLATION:
- Size and balance of some UI elements are inconsistent (toggle buttons, Text size)
- Language options only appear in the Plan Schedule screen
RECOMMENDATION:
- Ensure consistent size and balance of UI elements across application
- Ensure language options are available in all screens or move it to setting menu
SEVERITY: 1
(Strengths:
- Consistent back button in the top left corner
- Consistent setting button in the top right corner
- Use of standard icons / UI elements
)

HEURISTICS: 5. Error Prevention
VIOLATION:
- No visible constraints on invalid inputs for the To/From fields
- No confirmation when exporting to calendar
- No confirmation when toggling "Share with group"
RECOMMENDATION:
- Implement constraints on invalid inputs
- Add a confirmation dialog before exporting / sharing information
SEVERITY: 3
(Strengths:
- Some UI elements prevent invalid inputs
)

HEURISTICS: 6. Recognition Rather than Recall
VIOLATION:
- User must know the name of to/from location
- Grouping of UI elements may not be intuitive
- What Disability Mode toggle changes is not clear
- How to initiate a search / navigate from "Plan" is not clear
RECOMMENDATION:
- Provide suggestions based on user input
- Use more intuitive grouping of UI elements
- Provide Icons to help users recognize the purpose of each element
SEVERITY: 3
(Strengths:
- Checkboxes, toggle buttons making choices visible
)

HEURISTICS: 7. Flexibility and Efficiency of Use
VIOLATION:
- "Plan Schedule" does not provide route preferences options
- "Plan Schedule" does not allow users plan from arrival time
- Departure time does not allow users to select different dates
- limited customization options (Assuming more options in the settings, but not explicitly presented)
RECOMMENDATION:
- Provide route preferences options in "Plan Schedule"
- Allow users to plan from arrival time
- Allow users to select different dates in the departure time
- Provide more customization options
- Provide suggestions based on user input
SEVERITY: 3
(Strengths:
- Notification timing can be customized
- Disability setting provides customization / personalization options
)

HEURISTICS: 8. Aesthetic and Minimalist Design
VIOLATION:
- Share with group section take focus away from to/from and departure time
(Assuming the primary goal of "Plan Schedule" is to plan and search, not making the list of "Plan" which used in the future)
RECOMMENDATION:
- Adjust the text / component size to improve readability
SEVERITY: 2
(Strengths:
- Tool bar contains minimal components
)

HEURISTICS: 9. Help Users Recognize, Diagnose, and Recover from Errors
VIOLATION:
- No error messages are explicitly presented
- No feedback on invalid inputs
RECOMMENDATION:
- Provide clear error messages when invalid inputs are made
- Use traditional error-message visuals, like bold, red text
- Tell users what went wrong in language they will understand
- Offer users a solution, like a shortcut that can solve the error immediately
SEVERITY: 3
(Strengths:)

HEURISTICS: 10. Help and Documentation
VIOLATION:
- No visible help section
RECOMMENDATION:
- Provide a help section or documentation access points in the interface
SEVERITY: 2
(Strengths:
- Settings are always visible and accessible which may contain help information
)
