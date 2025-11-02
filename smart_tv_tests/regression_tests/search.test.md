<!-- suite
id: @Sffc25bdf
emoji: 
-->
# Search



<!-- test
id: @T29103a51
priority: normal
creator: boris103@gmail.com
-->
# Verify Search Page Opened

### Description:
Validate that the Search page opens correctly, displaying the keyboard and instructional text.

### Steps:
1. Open the FreeTV app.  
2. Open the Search page.  

### Verifications:
* Search page is opened.  
* Keyboard appears on the right side.  
* Line with text appears:  
  * מצא תוכניות חיות, סדרות או סרטים  

### Expected Result:
* All verifications pass successfully.

<!-- test
id: @T6069a248
priority: normal
creator: boris103@gmail.com
-->
# Verify Search Page with Less Than 3 Characters

### Description:
Validate that entering fewer than 3 characters in the Search page does not trigger a search or display results.

### Steps:
1. Open the FreeTV app  
2. Open the Search page  
3. Enter less than 3 characters  
4. Observe the search results  

### Verifications:
* No search results appear on the screen  

### Expected Result:
* Search does not trigger and no content is shown in the results area

<!-- test
id: @Td68c62bd
priority: normal
creator: boris103@gmail.com
-->
# Verify Search Page with More Than 3 Characters

### Description:
Validate that entering more than 3 characters in the Search page triggers a search and displays relevant results.

### Steps:
1. Open the FreeTV app.  
2. Open the Search page.  
3. Enter more than 3 characters in the search bar.  
4. Observe the search results.  

### Verifications:
* Search results are displayed based on the entered text.  

### Expected Result:
* Relevant search results appear on the screen.

<!-- test
id: @T81ea4af9
priority: normal
creator: boris103@gmail.com
-->
# Verify Search Results Include All Relevant Content Types

### Description:
Validate that search results display all relevant content types (Catch-up events, Movies, Series, Live channels, and Live events) when available for a given search term.

### Steps:
1. Open the Search page in the app  
2. Enter a search term with existing programs  
3. Observe the search results  

### Verifications:
* Search results show all relevant types of content, including:  
  - Catch-up events  
  - Movies  
  - Series  
  - Live channels  
  - Live events  

### Expected Result:
* All content types relevant to the search term appear correctly.

<!-- test
id: @T91c67021
priority: normal
creator: boris103@gmail.com
-->
# Verify Search History Displays Previously Viewed Assets

### Description:
Validate that the Search page maintains a history of previously opened assets and displays them in the search history section.

### Steps:
1. Perform several searches in the app  
2. Open different types of assets from the search results  
3. Navigate to another page in the app  
4. Return to the Search page  
5. Observe the search history section  

### Verifications:
* Search history includes all assets that were previously opened  

### Expected Result:
* The search history displays all assets that were previously opened

<!-- test
id: @Td69d4dca
priority: normal
creator: boris103@gmail.com
-->
# Verify Deleting Search History Clears All Previous Searches

### Description:
Validate that using the **Delete History** option clears all previous search entries and leaves the search history empty.

### Prerequisite:
* Search history contains previous search entries  

### Steps:
1. Open the Search page  
2. Press the **Delete History** button  
3. Navigate to another page in the app  
4. Return to the Search page  
5. Observe the search history section  

### Verifications:
* Search history is cleared after deletion  
* No previous entries appear when returning to the Search page  

### Expected Result:
* The search history is empty with no previous entries displayed

<!-- test
id: @T66d53a55
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback of Various Asset Types from Search Results

### Description:
Validate that all asset types opened from the Search results play successfully, including Live channels, Live events, Catch-up events, Movies, Series, and Episodes.

### Steps:
1. Open the Search page  
2. Search for assets in different categories  
3. Open and play each asset  

### Verifications:
* Live channels appear and play  
* Live events appear and play  
* Catch-up events appear and play  
* Movies appear and play  
* Series appear and play  
* Episodes appear and play  

### Expected Result:
* All searched asset types open successfully and playback starts without errors

<!-- test
id: @Tc1bea172
priority: normal
creator: boris103@gmail.com
-->
# Verify Search Behavior for Non-Existing Assets

### Description:
Validate that when a user enters a search term with no matching assets, the Search page displays no results and shows an appropriate "No results found" message if available.

### Steps:
1. Open the Search page  
2. Enter a search term that does not match any asset  
3. Observe the search results or messages displayed  

### Verifications:
* No assets are displayed in the search results  
* An appropriate "No results found" message is shown (if applicable)  

### Expected Result:
* The search returns no assets and clearly indicates that no matches were found

<!-- test
id: @T939c2e9a
priority: normal
creator: boris103@gmail.com
-->
# Verify Search with Special Characters - Valid Symbols

### Description:
Validate that the Search page correctly handles search terms containing valid special characters and returns appropriate results without errors.

### Steps:
1. Open the Search page  
2. Enter search terms containing valid special characters (e.g., &amp;, %, @, #)  
3. Observe the search results  

### Verifications:
* Search executes without errors  
* Relevant assets matching the search term (if any) are displayed  

### Expected Result:
* Search handles valid special characters correctly and returns appropriate results or no results gracefully

<!-- test
id: @T2069b347
priority: normal
creator: boris103@gmail.com
-->
# Verify Search with Special Characters - Invalid or Unsupported Symbols

### Description:
Validate that the Search page handles invalid or unsupported special characters gracefully without crashes, and provides appropriate messaging or empty results.

### Steps:
1. Open the Search page  
2. Enter search terms containing invalid or unsupported special characters (e.g., `~`, `^`, `*`)  
3. Observe the search behavior and results  

### Verifications:
* No app crashes or freezes occur  
* User-friendly message is displayed if search cannot process the input  
* No irrelevant or erroneous results are shown  

### Expected Result:
* The app gracefully handles invalid special characters with proper messaging or empty results without crashing
