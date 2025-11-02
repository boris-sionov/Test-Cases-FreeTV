<!-- suite
id: @Sb28822fb
emoji: 
-->
# 4K Movies assets tests

### Requirements

<!-- test
id: @T5d0007cb
priority: normal
creator: boris103@gmail.com
-->
# Verify 4K Badge on Movie Posters in 4K Ultra-HD Rail

### Description:
Validate that all movies in the 4K Ultra-HD rail display a 4K badge on their posters.

### Steps:
1. Navigate to the main **Movies page**.  
2. Scroll to the **4K Ultra-HD** rail.  
3. Locate movies that support 4K (examples below).  
   ### Examples:  
   - ג'מבו מותק  
   - Sing פסטיגל - תנו למוסיקה לחבר בינינו  
   - כסף טיפש  
   - בלתי נשכחים 4  
   - לומדת לעוף  
   - הכריש השחור  
   - גן עדן של טעויות  
   - קנדהאר  

### Verifications:
- A **4K badge** is displayed on the top right corner of each movie poster/thumbnail in the **4K Ultra-HD** rail.  
- The badge is consistent across all 4K movie posters in the rail.  

### Expected Result:
- The 4K badge is correctly displayed on the top right corner of all movie posters in the **4K Ultra-HD** rail, confirming that the movies are available in 4K quality.

<!-- test
id: @T9b4e2f4a
priority: normal
creator: boris103@gmail.com
-->
# Verify 4K Movie Asset Page Opened

### Description:
Validate that when opening a 4K movie asset page, all mandatory metadata fields are displayed, optional fields appear when available, and the 4K label is shown to indicate support for 4K quality.  

### Steps:
1. Open any **4K** movie asset from the Movies page or any other rail.  
2. Observe the movie asset page.  

### Verifications:
* **Mandatory fields:**  
  - Movie title is visible.  
  - Movie tag (e.g., "סרט") is displayed.  
  - Poster or trailer is playing in the background.  
  - Synopsis is present and not empty.  
  - Genre tag(s) are visible.  
  - Duration is displayed.  
* **Optional fields (if available):**  
  - Age rating is displayed.  
  - **4K label is shown.**  
  - Year of release is shown.  

### Expected Result:
* The 4K movie asset page opens successfully with all mandatory metadata displayed.  
* Optional metadata (age rating, year) is shown if available.  
* The **4K label** is present, confirming the movie supports 4K quality.

<!-- test
id: @T7bfde075
priority: normal
creator: boris103@gmail.com
-->
# Verify 4K Indicators on Movie Asset Page

### Description:
Validate that 4K movies display both the **4K logo** and the **4K tag** consistently on their asset pages, ensuring users can clearly identify 4K quality availability.  

### Steps:
1. Navigate to a **4K movie asset page**.  
2. Select a movie that supports 4K (examples below, can also be found in the **4K Ultra-HD** rail on the main page).  
   ### Examples:
   - ג'מבו מותק  
   - Sing פסטיגל - תנו למוסיקה לחבר בינינו  
   - כסף טיפש  
   - בלתי נשכחים 4  
   - לומדת לעוף  
   - הכריש השחור  
   - גן עדן של טעויות  
   - קנדהאר  
3. Observe the **top left corner** of the screen.  
4. Observe the **metadata area** under the movie title.  

### Verifications:
- A **4K logo** is displayed in the top left corner of the screen.  
- A **4K tag** is displayed in the metadata area under the movie title.  
- Both indicators are visible and consistent across all 4K movie asset pages.  

### Expected Result:
- The **4K logo** and **4K tag** are correctly displayed on movie asset pages that support 4K, clearly indicating the availability of 4K quality.

<!-- test
id: @T9f2df98e
priority: normal
creator: boris103@gmail.com
-->
# Verify Trailer Button on 4K Movie Asset Page

### Description:
Validate that the Trailer button on a 4K movie asset page is visible, responsive to focus, and starts trailer playback when pressed.  

### Steps:
1. Navigate to a 4K movie asset page (examples below, can also be found in the **4K Ultra-HD** rail on the main page).  
   ### Examples:
   - ג'מבו מותק  
   - Sing פסטיגל - תנו למוסיקה לחבר בינינו  
   - כסף טיפש  
   - בלתי נשכחים 4  
   - לומדת לעוף  
   - הכריש השחור  
   - גן עדן של טעויות  
   - קנדהאר  
2. Move focus to the **Trailer** button.  
3. Press on the **Trailer** button.  

### Verifications:
- The **Trailer** button is visible on the 4K movie asset page.  
- The button is visually highlighted when in focus.  
- Pressing the button starts trailer playback.  

### Expected Result:
- The Trailer button on the 4K movie asset page is functional, responds to focus, and starts trailer playback when pressed.  

**Note:** Not all 4K movie assets include a Trailer button.

<!-- test
id: @T298e2c91
priority: normal
creator: boris103@gmail.com
-->
# Verify Play Button on 4K Movie Asset Page (First Watch)

### Description:
Validate that the Play button on a 4K movie asset page is visible, responsive, and starts playback from the beginning when the movie has never been watched before.  

### Precondition:
The selected 4K movie has never been watched.  

### Steps:
1. Navigate to a 4K movie asset page (examples below, can also be found in the **4K Ultra-HD** rail on the main page).  
   ### Examples:
   - ג'מבו מותק  
   - Sing פסטיגל - תנו למוסיקה לחבר בינינו  
   - כסף טיפש  
   - בלתי נשכחים 4  
   - לומדת לעוף  
   - הכריש השחור  
   - גן עדן של טעויות  
   - קנדהאר  
2. Move focus to the **Play** button.  
3. Press on the **Play** button.  

### Verifications:
- The **Play** button is visible on the 4K movie asset page.  
- The button is visually highlighted when in focus.  
- Pressing the button starts playback of the movie from the beginning.  

### Expected Result:
- The Play button on the 4K movie asset page is functional, responds to focus, and starts playback of the movie from the beginning when pressed.

<!-- test
id: @T5177cdff
priority: normal
creator: boris103@gmail.com
-->
# Verify 4K Movie Playback Resumes from Bookmark

### Description:
Validate that reopening a previously partially watched 4K movie resumes playback from the last watched (bookmarked) position.  

### Steps:
1. Open any 4K movie asset from the Movies page or from the **4K Ultra-HD** rail.  
2. Press the **Play** button to start the movie.  
3. Watch the movie for a few minutes or seek forward a few minutes.  
4. Exit playback and return to the previous page.  
5. Reopen the same 4K movie asset.  
6. Press the **Play** button again.  

### Verifications:
- The movie resumes playback from the bookmarked position where it was previously stopped.  

### Expected Result:
- When reopening a previously partially watched 4K movie, playback resumes from the last watched (bookmarked) position instead of starting from the beginning.
