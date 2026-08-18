PROJECT SUMMARY

This program was built for the Corner Grocer to track daily produce sales from a checkout file. It counts how often items are purchased to help store staff optimize store layout.

The program automatically backs up sales data on launch and provides a menu to:

Search the purchase count of a specific item.

View a list of all items sold and their frequencies.

Display a visual star chart to compare popular items.

Exit the program.

STRENGTHS AND ACCOMPLISHMENTS

Flexible Search: Added case-insensitive matching so searching "apples" or "APPLES" works the same.

Clean Input Handling: Built a custom trim function to strip hidden line breaks and extra spaces from file inputs.

Organized Structure: Grouped core data logic inside a GroceryTracker class to keep the code neat and modular.

AREAS FOR ENHANCEMENT

Prettier Display: The menu output could use formatted tables or borders to make lists easier to read.

Clearer Visuals: Replacing star asterisks with solid block characters or grid lines would make the chart easier to read.

Dynamic Files: Allowing users to type in custom input and output file names instead of using hardcoded paths.

CHALLENGES AND SOLUTIONS

The main challenge was using std map to count item frequencies without adding accidental entries or breaking string matches. Hidden carriage return characters from input files also caused lookup failures. This was fixed by using custom trimming functions and const-correct search logic found in zyBooks map references.

TRANSFERABLE SKILLS

STL Maps: Learning std map key-value pairs applies directly to working with Python dictionaries or Java HashMaps.

Input Validation: Using cin clear and cin ignore to handle bad menu inputs is essential for building safe software.

MAINTAINABILITY READABILITY AND ADAPTABILITY

Clean OOP Design: Kept data private in the class while providing clear public methods for menu actions.

Readable Code: Used descriptive variable names, camelCase conventions, and inline comments so others can easily update the code.
