<!-- suite
id: @S1d42de1d
emoji: 
-->
# Movies Page



<!-- test
id: @Tf63f4634
priority: normal
creator: boris103@gmail.com
-->
# Verify Movies Page Opened

### Description:
Validate that the Movies page opens and displays the Hero banner and movie rails.

### Steps:
1. Open the **Movies** page from the side menu.  
2. Observe the Hero banner area.  
3. Observe the movie rails below.  

### Verifications:
- Movies page loads successfully.  
- Hero banner area is visible.  
- At least one rail of movies is displayed below the Hero banner.  

### Expected Result:
- The Movies page opens with a visible Hero banner and at least one rail of movies displayed below it.

<!-- test
id: @T8db87087
priority: normal
creator: boris103@gmail.com
-->
# Verify Movies Metadata Display on Movies Page

### Description:
Validate that the Movies page Hero banner displays all mandatory metadata and optional metadata if available.

### Steps:
1. Open the **Movies** page from the side menu.  
2. Focus on the Hero banner area.  

### Verifications:
- Mandatory metadata is displayed:  
  - Movie **title**.  
  - **Synopsis/description** text (not empty).  
  - **Primary action buttons** (e.g., “צפייה”, “עוד פרטים”) are visible and enabled.  
- Optional metadata (if available):  
  - Tags such as genre(s), year, duration, HD/4K.  
  - Age rating.  
- Layout is **RTL-aligned** with no clipping or overlap.  

### Expected Result:
- The Hero banner on the Movies page displays all mandatory metadata, optional metadata if available, and a clean RTL-aligned layout.

<!-- test
id: @Ta5b2df93
priority: normal
creator: boris103@gmail.com
-->
# Verify Movie Trailer Autoplay on Hero

### Description:
Validate that the Hero area on the Movies page automatically plays a trailer if available, or shows a static poster if not.

### Steps:
1. Open the **Movies** page from the side menu.  
2. Observe the Hero area.  

### Verifications:
* If a trailer is available:  
  - Trailer starts playing automatically in the Hero area as soon as the Movies page loads.  
  - Focus is on the **Watch** button while the trailer plays in the background.  
* If no trailer is available:  
  - A static poster image is displayed in the Hero area.  
  - No trailer playback option is shown.  

### Expected Result:
* When available, the trailer in the Hero plays automatically upon opening the Movies page with focus on the Watch button.  
* When unavailable, a static poster image is shown in the Hero with no trailer playback option.

<!-- test
id: @T252e6d13
priority: normal
creator: boris103@gmail.com
-->
# Verify Movie Trailer Playing on Top Shelf

### Description:
Validate that when focusing on a movie in a rail, its trailer automatically plays in the Top Shelf area if available.

### Steps:
1. Open the **Movies** page from the side menu.  
2. Navigate down to any movie asset in a rail.  
3. Observe the Top Shelf area.  

### Verifications:
* If a trailer is available:  
  - Trailer starts playing automatically in the Top Shelf area.  
  - Playback runs smoothly without freezing or stuttering.  
* If no trailer is available:  
  - A static poster image is shown instead of a trailer.  

### Expected Result:
* When available, the trailer of the selected movie plays automatically in the Top Shelf area.  
* When unavailable, a static poster image is displayed instead.

<!-- test
id: @T88452794
priority: normal
creator: boris103@gmail.com
-->
# Verify Movie Asset Page Opened

### Description:
Validate that the movie asset page opens correctly and displays all mandatory metadata, with optional metadata shown if available.

### Steps:
1. Open any movie asset from the **Movies** page or from any other rail.  
2. Observe the movie asset page.  

### Verifications:
* **Mandatory fields:**  
  - Movie title is visible.  
  - Movie tag (e.g., "סרט") is displayed.  
  - Poster or trailer is shown in the background.  
  - Synopsis is present and not empty.  
  - Genre tag(s) are visible.  
  - Duration is displayed.  
* **Optional fields (if available):**  
  - Age rating is displayed.  
  - HD/4K label is shown.  
  - Year of release is shown.  

### Expected Result:
* The movie asset page loads successfully and displays all mandatory metadata, including title, movie tag, background trailer or poster, synopsis, genre tags, and duration.  
* Optional metadata (age rating, HD/4K label, year of release) is displayed when available.  
* If a trailer is available, it plays automatically in the background; if not, a static poster is displayed instead.

<!-- test
id: @T47273798
priority: normal
creator: boris103@gmail.com
-->
# Verify Add to Favorites from Movie Asset Page

### Description:
Validate that a movie can be added to Favorites from the movie asset page and appears correctly in the Favorites rail.

### Steps:
1. Open any **movie asset** from the Movies page or any other rail.  
2. Locate the **Add to Favorites button (“+”)** in the Hero area.  
3. Select the **Add to Favorites button**.  
4. Navigate to the **Main page**.  
5. Scroll to the **Favorites rail**.  

### Verifications:
- On the movie asset page:  
  - The **Add to Favorites button** is visible and enabled in its default “+” state.  
  - After selecting it:  
    - The button changes to a **green circle with a checkmark (✓)**.  
    - The updated state persists while on the asset page.  
- On the Main page:  
  - The selected movie appears as the **first asset on the left** in the Favorites rail.  
  - The poster and title in the Favorites rail match the selected movie.  
  - No duplicates of the same movie are present in the Favorites rail.  

### Expected Result:
- The **Add to Favorites button** toggles correctly between “+” (not added) and “✓” (added) on the movie asset page.  
- The selected movie appears in the Favorites rail on the Main page as the first asset on the left.  
- Poster and title match the selected movie, and no duplicate entries are displayed.

<!-- test
id: @T5f0df35a
priority: normal
creator: boris103@gmail.com
-->
# Verify Trailer Button on Movie Asset Page

### Description:
Validate that the Trailer button on the movie asset page is visible, focusable, and starts trailer playback when available.

### Steps:
1. Navigate to a movie asset page.  
2. Move focus to the **Trailer** button.  
3. Press the **Trailer** button.  

### Verifications:
- The **Trailer** button is visible on the movie asset page.  
- The button is visually highlighted when in focus.  
- Pressing the button starts trailer playback.  

### Expected Result:
- The Trailer button is functional, responds to focus, and starts trailer playback when pressed.  

### Note:  
- Not all movie assets include a Trailer button.

<!-- test
id: @T483724ee
priority: normal
creator: boris103@gmail.com
-->
# Verify Play Movie Button on Movie Asset Page

### Description:
Validate that the Play button on the movie asset page is functional and starts playback from the beginning for a movie that has never been watched.

### Precondition:
- The selected movie has never been watched.  

### Steps:
1. Navigate to a movie asset page.  
2. Move focus to the **Play** button.  
3. Press the **Play** button.  

### Verifications:
- The **Play** button is visible on the movie asset page.  
- The button is visually highlighted when in focus.  
- Pressing the button starts playback from the beginning.  

### Expected Result:
- The Play button is functional, responds to focus, and starts playback of the movie from the beginning when pressed.

<!-- test
id: @T476d3dd5
priority: normal
creator: boris103@gmail.com
-->
# Verify Movie Playback Resumes from Bookmark

### Description:
Validate that a partially watched movie resumes playback from the last watched position when reopened.

### Steps:
1. Open any movie asset from the Movies page or any other rail.  
2. Press the **Play** button to start the movie.  
3. Watch the movie for a few minutes or seek forward a few minutes.  
4. Exit playback and return to the previous page.  
5. Reopen the same movie asset.  
6. Press the **Play** button again.  

### Verifications:
- The movie resumes playback from the bookmarked position where it was previously stopped.  

### Expected Result:
- When reopening a previously partially watched movie, playback resumes from the last watched (bookmarked) position instead of starting from the beginning.

<!-- test
id: @T845ea0c8
priority: normal
creator: boris103@gmail.com
-->
# Verify Poster Appears After Hero Trailer Ends

### Description:
Validate that when the Hero trailer finishes, it is replaced by the movie’s static poster image while metadata remains unchanged.

### Steps:
1. Open the **Movies** page.  
2. Observe the Hero trailer playing automatically.  
3. Wait until the trailer finishes.  

### Verifications:
* After the trailer ends, a static poster image for the same movie appears in the Hero area.  
* Metadata in the Hero (title, synopsis, tags, etc.) remains visible and unchanged.  

### Expected Result:
* When the Hero trailer finishes, it is replaced by the static poster image for the same movie, and all Hero metadata remains visible and unchanged.

<!-- test
id: @T7886454d
priority: normal
creator: boris103@gmail.com
-->
# Verify Return to Asset Page After Movie Ends

### Description:
Validate that when a movie finishes playing, the player exits and returns to the movie asset page.

### Steps:
1. Open any movie asset from the Movies page or any other rail.  
2. Press the **Play** button to start the movie.  
3. Watch the movie until it ends or seek it to the end.  

### Verifications:
* Player closes after the movie ends.  
* The asset page for the same movie is displayed.  

### Expected Result:
* When a movie finishes, the player exits automatically and the movie’s asset page is shown.
