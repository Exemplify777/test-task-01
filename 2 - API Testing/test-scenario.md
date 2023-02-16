# API Testing
## Application
Rick and Morty API - https://rickandmortyapi.com/ 
## Testing Approach
Reactive approach where application already developed, blackbox end to end  functional API testing


## Test Cases
1. Check if the answer scheme with the list of characters is valid.
2. Check if the answer scheme with one character is valid.
3. Check if the first page of all characters has correct page information and if the first record belongs to 'Rick Sanchez'.
4. Check if the last page of all characters has correct page information and if the first record belongs to 'Gotron'.
5. Check if the response to the query of the specified one character has a response with that one character.
6. Check if the query for the specified multiple characters has a response with those characters.
7. Check if a search for 'Morty' character with 'Alive' status has a response with the correct paging information and that character in the results.
8. Check if a search character for a name containing 'Long' word, species as ‘human’, gender as ‘male’ and status a ‘unknown’ has a response with the correctpaging information and matching characters in the results.
9. Check if a search character for 'Unknown' value for ‘Invalid’ parameter, it ignores them and has a response with the correct paging information and allcharacters.
10. Check a search with a character name that does not exist, an error message should appear in the response.
11. Check the loading character with a non-existing ID number, and it should respond with an error message.
12. Check characters with an invalid ID number type, and it should respond with an error message.
13. Check a character with an invalid ID number format, and it should respond with an error message.
14. Check a character with an invalid page number, and it should respond with an error message.
