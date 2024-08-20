# ADT List Specification

Linear collection of T elements allowing duplicates. Positions start from 1. 

## Methods

### add(T newEntry)
- Description: Adds newEntry to end of the list.
- Postcondition: newEntry added to end of the list.

### T remove(Integer givenPosition)
- Description: Removes entry at givenPosition from the list.
- Precondition: givenPosition is between 1 to total entries.
- Postcondition: Entry at givenPosition is removed from the list.
- Returns: Removed entry, or null if failed.

### T getEntry(Integer givenPosition)
- Description: Retrieves entry at givenPosition in the list.
- Precondition: givenPosition is between 1 to total entries.
- Postcondition: The list remains unchanged.
- Returns: Entry at givenPosition.

### boolean contains(T anEntry)
- Description: Checks if the list contains anEntry.
- Postcondition: The list remains unchanged.
- Returns: true if found, false if not.

### boolean isEmpty()
- Description: Checks if the list is empty.
- Postcondition: The list remains unchanged.
- Returns: true if empty, false if not.

### int getNumberOfEntries()
- Description: Gets number of entries in the list.
- Postcondition: The list remains unchanged.
- Returns: Number of entries.
