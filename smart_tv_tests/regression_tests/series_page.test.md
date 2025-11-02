<!-- suite
id: @S4b7255d1
emoji: 
-->
# Series Page



<!-- test
id: @Tb3bae7fc
priority: normal
creator: boris103@gmail.com
-->
# Verify Series Page Opened

### Description:
Validate that the Series page opens and displays the Hero banner and series rails.

### Steps:
1. Open the **Series** page from the side menu.  
2. Observe the Hero banner area.  
3. Observe the series rails below.  

### Verifications:
- Series page loads successfully.  
- Hero banner area is visible.  
- At least one rail of series is displayed below the Hero banner.  

### Expected Result:
- The Series page opens with a visible Hero banner and at least one rail of series displayed below it.

<!-- test
id: @T523e2733
priority: normal
creator: boris103@gmail.com
-->
# Verify Series Metadata Display on Series Asset Page

### Description:
Validate that the Series page Hero banner displays all mandatory metadata and optional metadata if available.

### Steps:
1. Open the **Series** page from the side menu.  
2. Focus on the Hero banner area.  

### Verifications:
- Mandatory metadata is displayed:  
  - Series **title/logo**.  
  - **Synopsis/description** text (not empty).  
  - **Primary action buttons** (e.g., “צפייה”, “עוד פרטים”) are visible and enabled.  
- Optional metadata (if available):  
  - Genre(s), year, HD/4K tag, age rating.  
- Layout is **RTL-aligned** with no clipping or overlap.  

### Expected Result:
- The Hero banner on the Series page displays all mandatory metadata, optional metadata if available, and a clean RTL-aligned layout.

<!-- test
id: @Tee3baf5b
priority: normal
creator: boris103@gmail.com
-->
# Verify Autoplay Trailer on Series Hero

### Description:
Validate that if a trailer is available for the Series page Hero, it autoplays on load with focus on the Watch button; otherwise a static poster is shown with no trailer option.

### Steps:
1. Open the Series page.
2. Observe the page.

### Verifications:
* If a trailer is available:
  - Trailer starts playing automatically in the Hero area as soon as the Series page loads.
  - Focus is on the **Watch** button while the trailer plays in the background.
* If no trailer is available:
  - A static poster image is displayed in the Hero area.
  - No trailer playback option is shown.

### Expected Result:
* When available, the trailer in the Hero plays automatically upon opening the Series page with focus on the **Watch** button.
* When unavailable, a static poster image is shown in the Hero with no trailer playback option.

<!-- test
id: @Tc8067850
priority: normal
creator: boris103@gmail.com
-->
# Verify Series Trailer Playing on Top Shelf

### Description:
Validate that when focusing on a series in a rail, its trailer automatically plays in the Top Shelf area if available.

### Steps:
1. Open the **Series** page.  
2. Navigate to any series in a rail.  
3. Observe the Top Shelf area.  

### Verifications:
* If a trailer is available:  
  - The trailer starts playing automatically in the Top Shelf area.  
  - Playback runs smoothly without stuttering or freezing.  
* If no trailer is available:  
  - A static poster image is shown in the Top Shelf area.  

### Expected Result:
* The selected series’ trailer plays automatically in the Top Shelf area when available.  
* If no trailer is available, a static poster image is displayed instead.

<!-- test
id: @Tb6404af6
priority: normal
creator: boris103@gmail.com
-->
# Verify Series Metadata and Trailer on Top Shelf

### Description:
Validate that when focusing on a series in a rail, the Top Shelf updates with its metadata and plays the trailer automatically if available.

### Steps:
1. Open the **Series** page.  
2. Navigate down to any series in any rail.  
3. Observe the Top Shelf area.  

### Verifications:
* Top Shelf updates to show the selected series’ metadata.  
  - **Mandatory metadata:**  
    - Series title is visible.  
    - Synopsis is present and not empty.  
    - Season/Episode information is displayed:  
      - If the series has 1 season → number of episodes is shown.  
      - If the series has 2 or more seasons → number of seasons is shown.  
  - **Optional metadata (if available):**  
    - Tags (e.g., genre, year, HD/4K) are displayed.  
    - Age rating is shown.  
* If a trailer is available:  
  - Trailer starts playing automatically in the Top Shelf area.  
* If no trailer is available:  
  - A static poster image is displayed in the Top Shelf area.  

### Expected Result:
* Selecting any series in a rail updates the Top Shelf with mandatory metadata (title, synopsis, and correct season/episode information based on series length).  
* If available, optional metadata is also displayed.  
* The trailer plays automatically when available; otherwise, a static poster image is shown.

<!-- test
id: @T064c3fc1
priority: normal
creator: boris103@gmail.com
-->
# Verify Series Asset Page Opens

### Description:
Validate that selecting a series tile opens the series asset page with all required metadata, action buttons, and episode rails.

### Steps:
1. Open the **Series** page from the side menu.  
2. Navigate to any series tile in a rail.  
3. Select the series tile to open its asset page.  

### Verifications:
- The **Series asset page** opens successfully.  
- **Hero area shows mandatory metadata:**  
  - Series **title/logo** is visible.  
  - **Synopsis/description** text is present and not empty.  
  - **Seasons/episodes information**:  
    - If the series has **1 season** → the **number of episodes** is displayed.  
    - If the series has **2 or more seasons** → the **number of seasons** is displayed.  
  - **Primary action buttons** are visible and enabled:  
    - “צפייה” (play first episode).  
    - “טריילר” (if trailer available).  
    - “+” (add to favorites).  
- **Hero area shows optional metadata (if available):**  
  - Tags such as genre(s), year, HD/4K.  
  - Age rating.  
- **Rails below Hero:**  
  - A **season selector** is displayed if multiple seasons exist.  
  - Episodes rail is visible with **episode tiles** including a **poster image** and **title**.  
- Layout and labels are **RTL-aligned** with no clipping or overlap.  

### Expected Result:
- Selecting any series tile opens the asset page.  
- The Hero area displays all mandatory metadata (title/logo, synopsis, seasons/episodes info, and primary action buttons).  
- Optional metadata (tags, age rating, trailer) appears if available.  
- Episodes are listed in rails with posters and titles, and layout is RTL-correct and stable.

<!-- test
id: @T7dfe4239
priority: normal
creator: boris103@gmail.com
-->
# Verify Seasons Rail on Series Asset Page

### Description:
Validate that the seasons rail/selector on the series asset page displays correctly and updates episodes when switching seasons.

### Steps:
1. Open the **Series** page from the side menu.  
2. Navigate to any series tile in a rail and select it to open the asset page.  
3. Observe the **seasons rail/selector** displayed below the Hero area.  

### Verifications:
- If the series has **only 1 season**:  
  - A single season chip (e.g., “עונה 1”) is displayed.  
- If the series has **multiple seasons**:  
  - A rail or selector with all available seasons is displayed (e.g., “עונה 1”, “עונה 2”, etc.).  
  - Each season is selectable.  
  - Switching seasons updates the **episodes rail** accordingly.  
- Layout and labels are **RTL-aligned** with no clipping or overlap.  

### Expected Result:
- The Series asset page displays a seasons rail/selector showing the correct number of seasons.  
- Single-season series display one season chip, while multi-season series show multiple selectable seasons.  
- Changing the season updates the episodes rail content.  
- Layout is stable, clean, and RTL-correct.

<!-- test
id: @Tff94f44c
priority: normal
creator: boris103@gmail.com
-->
# Verify Episodes Rail on Series Asset Page

### Description:
Validate that the episodes rail on the series asset page displays all episodes for the selected season with correct metadata and updates the Hero area when focusing on an episode.

### Steps:
1. Open the **Series** page from the side menu.  
2. Navigate to any series tile in a rail and select it to open the asset page.  
3. Scroll down to the **episodes rail** under the seasons selector (or directly below the Hero for single-season series).  
4. Focus on an episode tile.  

### Verifications:
- The episodes rail is visible for the selected season.  
- Each episode tile includes:  
  - A **poster/thumbnail image**.  
  - **Episode number** (e.g., “פרק 1”).  
  - **Episode duration** (e.g., “47m”).  
- When focusing on an episode tile, the **Hero area updates** to show:  
  - Episode **title** (if available).  
  - Episode **synopsis/description** (not empty).  
- All episodes of the season are present and displayed in sequential order.  
- If multiple seasons exist:  
  - Switching seasons updates the episodes rail to show the correct list of episodes.  
- Layout and labels are **RTL-aligned** with no clipping or overlap.  

### Expected Result:
- The episodes rail displays all episodes for the selected season with poster, number, and duration.  
- Focusing on an episode updates the Hero with that episode’s title and synopsis.  
- Episodes are listed in sequential order, and the layout is RTL-correct and stable.  

### Note:  
- When the episode synopsis exceeds the available display space, it is truncated gracefully with an ellipsis (“...”) to indicate continuation, ensuring layout stability without text overflow.

<!-- test
id: @Tc6077c36
priority: normal
creator: boris103@gmail.com
-->
# Verify Add to Favorites Button on Series Asset Page

### Description:
Validate that the Add to Favorites button on the series asset page is functional and toggles correctly between add and remove states.

### Steps:
1. Open the **Series** page from the side menu.  
2. Navigate to any series tile in a rail and select it to open the asset page.  
3. Locate the **Add to Favorites button (“+”)** in the Hero area.  
4. Select the **Add to Favorites** button.  
5. Observe the button state.  
6. Select the button again to remove from Favorites.  

### Verifications:
- On the series asset page:  
  - The **Add to Favorites button** is visible and enabled in its default “+” state.  
  - After selecting it:  
    - The button changes to a **green circle with a checkmark (✓)**.  
    - The state persists while on the asset page.  
  - Selecting the button again toggles it back to the “+” state.  
- No duplicate buttons, lag, or incorrect states are shown.  
- Layout and button labels remain **RTL-aligned** and stable.  

### Expected Result:
- The **Add to Favorites button** toggles correctly between “+” (not added) and “✓” (added) states on the series asset page.  
- Button behavior is immediate, reliable, and visually consistent.

<!-- test
id: @T268750b2
priority: normal
creator: boris103@gmail.com
-->
# Verify Trailer Button on Series Asset Page

### Description:
Validate that the Trailer button on the series asset page is visible, focusable, and starts trailer playback when available.

### Steps:
1. Navigate to a series asset page.  
2. Move focus to the **Trailer** button.  
3. Press the **Trailer** button.  

### Verifications:
- The **Trailer** button is visible on the series asset page.  
- The button is visually highlighted when in focus.  
- Pressing the button starts trailer playback.  

### Expected Result:
- The Trailer button on the series asset page is functional, responds to focus, and starts trailer playback when pressed.  

### Note:  
- Not all series assets include a Trailer button.

<!-- test
id: @T839f5bb9
priority: normal
creator: boris103@gmail.com
-->
# Verify Play Episode Button on Series Asset Page

### Description:
Validate that the Play button on the series asset page is functional and starts playback from the beginning for an episode that has never been watched.

### Precondition:
- The selected episode has never been watched.  

### Steps:
1. Navigate to a series asset page.  
2. Move focus to the **Play** button.  
3. Press the **Play** button.  

### Verifications:
- The **Play** button is visible on the series asset page.  
- The button is visually highlighted when in focus.  
- Pressing the button starts playback of the episode from the beginning.  

### Expected Result:
- The Play button on the series asset page is functional, responds to focus, and starts playback of the episode from the beginning when pressed.

<!-- test
id: @Tbabadc4d
priority: normal
creator: boris103@gmail.com
-->
# Verify Episode Playback Resumes from Bookmark

### Description:
Validate that a partially watched episode resumes playback from the last watched position when reopened.

### Steps:
1. Open any series asset page and start playback of an episode.  
2. Watch the episode for a few minutes or seek forward a few minutes.  
3. Exit playback and return to the series asset page.  
4. Move focus to the **Play** button.  
5. Press the **Play** button.  

### Verifications:
- The episode resumes playback from the last watched position where it was previously stopped.  

### Expected Result:
- When reopening a previously partially watched episode, playback resumes from the last watched (bookmarked) position instead of starting from the beginning.

<!-- test
id: @T43b03ed7
priority: normal
creator: boris103@gmail.com
-->
# Verify Skip Recap Button Skips Recap

### Description:
Validate that the Skip Recap button appears during episodes with a recap section and skips it when pressed.

### Steps:
1. Start playback of a series episode that includes a recap section (examples below).  
   ### Examples:  
   - בשבילה גיבורים עפים  
   - השוטרים  
2. Wait until the **Skip Recap** button (`דלג על התקציר`) appears on the screen.  
3. Move focus to the **Skip Recap** button.  
4. Press the button.  

### Verifications:
- The **Skip Recap** button is visible during the recap section.  
- The button is visually highlighted when in focus.  
- Pressing the button skips the recap section.  

### Expected Result:
- The recap section is skipped when the **Skip Recap** button is pressed.  

### Note:  
- Not all series episodes include a **Skip Recap** option.

<!-- test
id: @T76c8c66e
priority: normal
creator: boris103@gmail.com
-->
# Verify Recap Plays When Skip Recap Button Not Pressed

### Description:
Validate that if the Skip Recap button is not pressed, the recap section plays in full.

### Steps:
1. Start playback of a series episode that includes a recap section (examples below).  
   ### Examples:  
   - בשבילה גיבורים עפים  
   - השוטרים  
2. Wait until the **Skip Recap** button (`דלג על התקציר`) appears on the screen.  
3. Do not press the button.  

### Verifications:
- The **Skip Recap** button is visible during the recap section.  
- The recap section continues playing normally when the button is not pressed.  

### Expected Result:
- The recap section plays in full if the **Skip Recap** button is not pressed.  

### Note:  
- Not all series episodes include a **Skip Recap** option.

<!-- test
id: @T8619acbd
priority: normal
creator: boris103@gmail.com
-->
# Verify Skip Intro Button Skips Intro

### Description:
Validate that the Skip Intro button appears during episodes with an intro sequence and skips it when pressed.

### Steps:
1. Start playback of a series episode that includes an intro sequence (examples below).  
   ### Examples:  
   - בשבילה גיבורים עפים  
   - השוטרים  
2. Wait until the **Skip Intro** button (`דלג על הפתיח`) appears on the screen.  
3. Move focus to the **Skip Intro** button.  
4. Press the button.  

### Verifications:
- The **Skip Intro** button is visible during the intro sequence.  
- The button is visually highlighted when in focus.  
- Pressing the button skips the intro section.  

### Expected Result:
- The intro section is skipped when the **Skip Intro** button is pressed.  

### Note:  
- Not all series episodes include a **Skip Intro** option.

<!-- test
id: @T0a25d6d5
priority: normal
creator: boris103@gmail.com
-->
# Verify Intro Plays When Skip Intro Button Not Pressed

### Description:
Validate that if the Skip Intro button is not pressed, the intro sequence plays in full.

### Steps:
1. Start playback of a series episode that includes an intro sequence (examples below).  
   ### Examples:  
   - בשבילה גיבורים עפים  
   - השוטרים  
2. Wait until the **Skip Intro** button (`דלג על הפתיח`) appears on the screen.  
3. Do not press the button.  

### Verifications:
- The **Skip Intro** button is visible during the intro sequence.  
- The intro sequence continues playing normally when the button is not pressed.  

### Expected Result:
- The intro sequence plays in full if the **Skip Intro** button is not pressed.  

### Note:  
- Not all series episodes include a **Skip Intro** option.

<!-- test
id: @T98b2a6cc
priority: normal
creator: boris103@gmail.com
-->
# Verify Automatic Playback of Next Episode When No Button Pressed

### Description:
Validate that the next episode starts automatically after the countdown if no action is taken at the end of the current episode.

### Steps:
1. Start playback of a series episode and watch or seek until the credits start (examples below).  
   ### Examples:  
   - בשבילה גיבורים עפים  
   - השוטרים  
2. Wait for the **Next Episode** and **Watch Credits** buttons to appear.  
3. Do not press any button.  

### Verifications:
- The **Next Episode** and **Watch Credits** buttons are displayed at the start of the credits (or during the last 5 seconds if credits are not configured).  
- After ~5 seconds, the next episode starts playing automatically if no action is taken.  

### Expected Result:
- The next episode begins automatically after 5 seconds when no button is pressed.  

### Note:  
- Not all episodes are configured with a specific credits start time.  
  - If credits are configured → the buttons appear at the beginning of the credits (see examples above).  
  - If credits are not configured → the buttons appear during the last 5 seconds of the episode.

<!-- test
id: @T14c943fd
priority: normal
creator: boris103@gmail.com
-->
# Verify Next Episode Button Starts Next Episode

### Description:
Validate that pressing the Next Episode button at the end of an episode starts playback of the next episode.

### Steps:
1. Start playback of a series episode and watch or seek until the credits start (examples below).  
   ### Examples:  
   - בשבילה גיבורים עפים  
   - השוטרים  
2. Wait for the **Next Episode** and **Watch Credits** buttons to appear.  
3. Press the **Next Episode** button.  

### Verifications:
- The **Next Episode** and **Watch Credits** buttons are displayed at the start of the credits (or during the last 5 seconds if credits are not configured).  
- Pressing the **Next Episode** button starts playback of the next episode.  

### Expected Result:
- The next episode starts playing immediately when the **Next Episode** button is pressed.  

### Note:  
- Not all episodes are configured with a specific credits start time.  
  - If credits are configured → the buttons appear at the beginning of the credits (see examples above).  
  - If credits are not configured → the buttons appear during the last 5 seconds of the episode.

<!-- test
id: @Tba47b3da
priority: normal
creator: boris103@gmail.com
-->
# Verify Watch Credits Button Plays Credits

### Description:
Validate that pressing the Watch Credits button at the end of an episode plays the credits instead of skipping to the next episode.

### Steps:
1. Start playback of a series episode and watch or seek until the credits start (examples below).  
   ### Examples:  
   - בשבילה גיבורים עפים  
   - השוטרים  
2. Wait for the **Next Episode** and **Watch Credits** buttons to appear.  
3. Move focus to the **Watch Credits** button.  
4. Press the **Watch Credits** button.  

### Verifications:
- The **Next Episode** and **Watch Credits** buttons are displayed at the start of the credits (or during the last 5 seconds if credits are not configured).  
- Pressing the **Watch Credits** button plays the credits.  

### Expected Result:
- The credits are played when the **Watch Credits** button is pressed.  

### Note:  
- Not all episodes are configured with a specific credits start time.  
  - If credits are configured → the buttons appear at the beginning of the credits (see examples above).  
  - If credits are not configured → the buttons appear during the last 5 seconds of the episode.

<!-- test
id: @T0e544002
priority: normal
creator: boris103@gmail.com
-->
# Verify Next Episode Plays After Credits

### Description:
Validate that after watching the credits to the end, the next episode begins automatically.

### Steps:
1. Start playback of a series episode and watch or seek until the credits start (examples below).  
   ### Examples:  
   - בשבילה גיבורים עפים  
   - השוטרים  
2. Wait for the **Next Episode** and **Watch Credits** buttons to appear.  
3. Move focus to the **Watch Credits** button.  
4. Press the **Watch Credits** button.  
5. Let the credits play until they finish.  

### Verifications:
- The **Next Episode** and **Watch Credits** buttons are displayed at the start of the credits (or during the last 5 seconds if credits are not configured).  
- After the credits finish, the next episode starts automatically.  

### Expected Result:
- Once the credits finish, the next episode begins automatically.  

### Note:  
- Not all episodes are configured with a specific credits start time.  
  - If credits are configured → the buttons appear at the beginning of the credits (see examples above).  
  - If credits are not configured → the buttons appear during the last 5 seconds of the episode.

<!-- test
id: @T3e6b8353
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback Moves from Last Episode of a Season to First Episode of Next Season

### Description:
Validate that playback transitions correctly from the last episode of one season to the first episode of the next season.

### Steps:
1. Start playback of the last episode of a season.  
2. Watch or seek until the credits start.  
3. Wait for the **Next Episode** button to appear.  
4. Press the **Next Episode** button (or wait for automatic playback after countdown).  

### Verifications:
- The **Next Episode** button is displayed at the start of the credits (or during the last 5 seconds if credits are not configured).  
- The next episode that starts playing is the **first episode of the following season**.  

### Expected Result:
- Playback continues seamlessly from the last episode of a season to the first episode of the next season.  

### Note:  
- Not all episodes are configured with a specific credits start time.  
  - If credits are configured → the buttons appear at the beginning of the credits.  
  - If credits are not configured → the buttons appear during the last 5 seconds of the episode.

<!-- test
id: @T98a5267f
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback Ends After Last Available Episode

### Description:
Validate that playback ends normally after the last available episode of a series without transitioning to another episode.

### Steps:
1. Start playback of the last available episode of a series.  
2. Watch or seek until the credits start.  
3. Wait until the end of playback.  

### Verifications:
- The **Next Episode** and **Watch Credits** buttons are not displayed.  
- The episode continues playing with credits.  
- When credits finish, playback ends and the player is closed.  

### Expected Result:
- On the last available episode of a series, no buttons appear, credits play normally, and at the end the player is closed.  

### Note:  
- Not all episodes are configured with a specific credits start time.  
  - If credits are configured → credits play as expected until the end.  
  - If credits are not configured → the episode ends normally and the player is closed.
