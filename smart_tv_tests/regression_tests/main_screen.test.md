<!-- suite
id: @S2a95cbe0
emoji: 
-->
# Main Screen



<!-- test
id: @Tdf8bce6b
priority: normal
creator: boris103@gmail.com
-->
# Verify Main Page Opens After Login

### Description:
Validate that once the user logs in, the app automatically opens the Main page as the landing page.

### Steps:
1. Open the FreeTV app.  
2. Log in to your account.  

### Verifications:
* The Main page opens automatically after login.  
* Hero banner and content rails are displayed.  

### Expected Result:
* The Main page opens automatically as the first page after login.

<!-- test
id: @Tf11c50c4
priority: normal
creator: boris103@gmail.com
-->
# Verify Navigation to Main Page Without Requiring Login

### Description:
Validate that when the app is reopened after being closed, a logged-in user is taken directly to the Main page instead of the login screen.

### Precondition:
* User is already logged in  

### Steps:
1. Kill/close the FreeTV app.  
2. Reopen the FreeTV app.  

### Verifications:
* The app opens directly on the Main page.  
* The login screen is not shown.  

### Expected Result:
* The app automatically navigates to the Main page for a logged-in user.

<!-- test
id: @T9fb99f04
priority: normal
creator: boris103@gmail.com
-->
# Verify Live Channel Playback on Top Shelf

### Description:
Validate that when focusing on live channels on the Main page, the Top Shelf starts playback correctly for channels displayed in the Channels rail, the Sports channels rail.

### Steps:
1. Open the FreeTV app.  
2. Log in to your account.  
3. Navigate to the Main page.  
4. Focus on any live channel.  

### Verifications:
* A channel is displayed in the **Channels** rail.  
* A channel is displayed in the **Sports channels** rail.  

### Expected Result:
* All displayed channels start playing in the Top Shelf view.

<!-- test
id: @T33c22e92
priority: normal
creator: boris103@gmail.com
-->
# Verify Full Screen Playback for Channels from Top Shelf

### Description:
Validate that channels from the Channels and Sports channels rails can be played in full screen directly from the Top Shelf without latency.

### Steps:
1. Open the Main page.  
2. Focus on any channel in the **Channels** or **Sports channels** rail.  
3. Wait until the video starts playing in the Top Shelf.  
4. Press **OK** to play the channel in full screen.  

### Verifications:
* A channel from the **Channels** rail opens in full screen.  
* A channel from the **Sports channels** rail opens in full screen.  

### Expected Result:
* Selected channels open in full screen without any latency.

<!-- test
id: @T0c114fde
priority: normal
creator: boris103@gmail.com
-->
# Verify Auto Full Screen Playback on LG After Timeout

### Description:
Validate that a channel playing in the Top Shelf automatically switches to full screen mode after a timeout period without user interaction.

### Steps:
1. Open the Main page.  
2. Focus on any channel in the **Channels** or **Sports channels** rail.  
3. Wait until the video starts playing in the Top Shelf.  
4. Wait an additional 10 minutes without pressing any button.  

### Verifications:
* Channel automatically opens in full screen without any user interaction.  

### Expected Result:
* The channel switches to full screen mode automatically after the timeout period.  
* **Note**: This feature works only from webOS 6 and above.

<!-- test
id: @T9b5dd6d3
priority: normal
creator: boris103@gmail.com
-->
# Verify Sports Channels Rail Playback and Full Screen Behavior

### Description:
Validate that channels in the Sports channels rail play correctly on the Top Shelf, can be opened instantly in full screen, and on LG devices switch to full screen automatically after 5 minutes of focus.

### Steps:
1. Open the Main page.  
2. Focus on any channel in the **Sports channels** rail.  

### Verifications:
* Channel plays on the Top Shelf.  
* Pressing **OK** opens the channel in full screen without latency.  
* **LG only:** After focusing on a channel, waiting 5 minutes opens it in full screen automatically.  

### Expected Result:
* Channel plays on the Top Shelf without delay.  
* Channel opens in full screen instantly after pressing **OK**.  
* **LG only:** Channel switches to full screen automatically after 5 minutes of focus.

<!-- test
id: @Te7eca64b
priority: normal
creator: boris103@gmail.com
-->
# Verify Movie Asset Card Metadata and Trailer Playability

### Description:
Validate that when focusing on a Movie asset in the VOD rail, the Top Shelf automatically plays the trailer (if available) and displays all required metadata correctly.

### Steps:
1. Open the Main page.  
2. Navigate to the VOD assets rail.  
3. Select and focus on any Movie asset card.  

### Verifications:
* Trailer plays automatically on the Top Shelf (if available).  
* Metadata on the asset card includes:  
  - **Mandatory (must always appear):**  
    * Movie title  
    * Synopsis (brief description)  
    * Movie tag (e.g., “Movie”)  
    * Duration  
  - **Optional (shown if available):**  
    * Tags/Genres  
    * Release year  
    * Age rating  
    * Quality indicator (HD, 4K)  

### Expected Result:
* All mandatory metadata is always displayed.  
* Optional metadata is displayed when available.  
* Trailer plays automatically if one exists for the asset.  

> **Note:** Not all movies have a trailer or all optional metadata fields. This is expected and should not be considered a defect.

<!-- test
id: @T099152cb
priority: normal
creator: boris103@gmail.com
-->
# Verify Series Asset Card Metadata and Trailer Playability

### Description:
Validate that when focusing on a Series asset in the VOD rail, the Top Shelf automatically plays the trailer (if available) and displays all required metadata correctly.

### Steps:
1. Open the Main page.  
2. Navigate to the VOD assets rail.  
3. Select and focus on any Series asset card.  

### Verifications:
* Trailer plays automatically on the Top Shelf (if available).  
* Metadata on the asset card includes:  
  - **Mandatory (must always appear):**  
    * Series title  
    * Synopsis (brief description)  
    * Series tag (e.g., “Series”)  
    * Number of seasons or episodes  
  - **Optional (shown if available):**  
    * Tags/Genres  
    * Release year  
    * Age rating  
    * Quality indicator (HD, 4K)  

### Expected Result:
* All mandatory metadata is always displayed.  
* Optional metadata is displayed when available.  
* Trailer plays automatically if one exists for the asset.  

> **Note:** Not all series have a trailer or all optional metadata fields. This is expected and should not be considered a defect.

<!-- test
id: @T7bdb75b5
priority: normal
creator: boris103@gmail.com
-->
# Verify Continue Watching Rail Is Hidden When Empty

### Description:
Validate that the Continue Watching rail is not shown on the Main page when there are no assets available in it.

### Prerequisite:
* All assets have been removed from the Continue Watching rail.  

### Steps:
1. Open the Main page.  
2. Navigate down through the rails.  
3. Look for the **Continue Watching** rail.  

### Verifications:
* Continue Watching rail is not displayed.  

### Expected Result:
* Continue Watching rail is hidden when there are no assets to display.

<!-- test
id: @Tf3350231
priority: normal
creator: boris103@gmail.com
-->
# Continue watching rail added assets

### Description:
Validate that the Continue Watching rail appears on the Main page and lists all recently watched asset types (Catch-up, Movie, Episode) from the current session.

### Steps:
1. Open the Main page.  
2. Play each of the following asset types for a few minutes or seek within them:  
   - Catch-up  
   - Movie  
   - Episode  
3. Close the player after each playback.  
4. Navigate to a different page in the app.  
5. Return to the Main page.  

### Verifications:
* Continue Watching rail is visible.  
* Rail contains all asset types that were watched: Catch-up, Movie, Episode.  

### Expected Result:
* Continue Watching rail lists every watched asset type (Catch-up, Movie, Episode) from the current session.

<!-- test
id: @T9263066d
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback for Assets in Recently Broadcast Rail

### Description:
Validate that assets in the Recently Broadcast rail play correctly, with accurate titles and episodes starting upon selection.

### Steps:
1. Open the Main page.  
2. Scroll to the **Recently Broadcast** rail.  
3. Select any asset and press **OK**.  
4. Repeat for a few different assets in the rail.  

### Verifications:
* Selected asset starts playback.  
* Title in the player matches the selected asset.  
* If multiple episodes from the same series appear, each plays the correct episode.  

### Expected Result:
* Playback starts for each tested asset.  
* Player shows the correct title.  
* Correct episode plays for series assets.

<!-- test
id: @T55740f5f
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback for Assets in Catchup – The Best Rail

### Description:
Validate that assets in the **Catchup – The Best** rail do not autoplay in the Top Shelf and start playback only after being selected with OK.

### Steps:
1. Open the Main page.  
2. Scroll to the **Catchup – The Best** rail.  
3. Select any asset and press **OK**.  

### Verifications:
* Asset is not playing automatically in the Top Shelf (no trailer or full asset playback).  
* Asset opens and starts playback only after pressing **OK**.  
* Title in the player matches the selected asset.  

### Expected Result:
* Assets in the **Catchup – The Best** rail do not autoplay in the Top Shelf.  
* Playback starts only when **OK** is pressed, and the player shows the correct title.

<!-- test
id: @T6af6778e
priority: normal
creator: boris103@gmail.com
-->
# Verify Favorite Rail Is Hidden When Empty

### Description:
Validate that the Favorite rail is not shown on the Main page when no assets are added to it.

### Prerequisite:
* All assets have been removed from the Favorite rail.  

### Steps:
1. Open the Main page.  
2. Navigate down through the rails.  
3. Look for the **Favorite** rail.  

### Verifications:
* Favorite rail is not displayed.  

### Expected Result:
* Favorite rail is hidden when there are no assets to display.

<!-- test
id: @T79498c3b
priority: normal
creator: boris103@gmail.com
-->
# Verify Adding Assets to Favorite Rail

### Description:
Validate that the Favorite rail appears on the Main page with supported asset types (Movies and Series), while unsupported types (Episodes, Live channels, Catch-up) cannot be added.

### Steps:
1. Open the Main page.  
2. Add a Movie, Series, and Catch-up asset to Favorites.  
3. Check for the **Add to Favorite** option on an Episode, Live channel, and Catch-up asset.  
4. Navigate to another page, then return to the Main page.  

### Verifications:
* Favorite rail is visible.  
* Movie and Series appear in the Favorite rail.  
* Episode, Live, and Catch-up assets cannot be added to Favorites.  

### Expected Result:
* Movie and Series appear in the Favorite rail; other asset types cannot be added.

<!-- test
id: @T327bbbd5
priority: normal
creator: boris103@gmail.com
-->
# Verify Top 10 Rail Asset Count, Trailer Playback, and Metadata Accuracy

### Description:
Validate that the Top 10 rail displays exactly 10 assets for an adult profile, with correct metadata and trailer playback (if available).

### Steps:
1. Open the Main page.  
2. Navigate to and focus on the **Top 10** rail.  

### Verifications:
* For an adult profile, 10 assets are displayed in the **Top 10** rail.  
* Focusing on any asset plays the trailer (if available).  
* Metadata for each asset is displayed correctly.  

### Expected Result:
* The **Top 10** rail contains exactly 10 assets for an adult profile.  
* Trailer plays automatically when focusing on an asset (if available).  
* Metadata is accurate for each displayed asset.
