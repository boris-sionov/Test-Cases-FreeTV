<!-- suite
id: @S4d407b1b
emoji: 
-->
# Sports Page



<!-- test
id: @T78857cad
priority: normal
creator: boris103@gmail.com
-->
# Verify Sports Page Opened

### Description:
Validate that the Sports page opens, auto-plays the focused channel on the top shelf, and displays the two sports rails.

### Steps:
1. Open the **Sports** page from the side menu.  
2. Observe the top shelf playback.  

### Verifications:
- Sports page loads successfully without errors.  
- The first channel is focused and auto-plays on the top shelf.  
- "5 ערוצי ספורט" rail is displayed with correct posters and RTL alignment.  
- "One ערוצי "" rail is displayed with correct posters and RTL alignment.  

### Expected Result:
- The Sports page opens successfully, the top shelf starts auto-playing the first channel, and both "ערוצי ספורט" and "ערוצי one" rails are displayed with proper posters and RTL alignment.

<!-- test
id: @Td962431b
priority: normal
creator: boris103@gmail.com
-->
# Verify Top Shelf Channel Playback Appearance

### Description:
Validate that when focusing on a live channel card in the Sports page, the Top Shelf starts playback smoothly and displays correct video, audio, and metadata.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Focus on any live channel card.  
4. Observe the Top Shelf.  

### Verifications:
- The focused live channel starts playing in the Top Shelf.  
- Video and audio play smoothly without interruptions.  
- Channel logo appears in the top left corner.  
- Program title is displayed.  
- Channel name is displayed.  
- Broadcast start and end time are shown.  
- Program type (e.g., "תוכנית טלוויזיה") is displayed.  
- Short synopsis/description is shown under the metadata.  

### Expected Result:
- The Top Shelf plays the focused live channel smoothly with correct video, audio, and complete metadata including logo, program title, channel name, broadcast time, type, and synopsis.

<!-- test
id: @T51d9f1f5
priority: normal
creator: boris103@gmail.com
-->
# Verify One Channels Rail on Sports Page

### Description:
Validate that the One channels rail on the Sports page is displayed correctly and allows focusing on live channels to start Top Shelf playback with proper video, audio, and metadata.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate to the **ערוצי One** rail.  
4. Focus on any live channel card in the One rail.  
5. Observe the Top Shelf.  

### Verifications:
- "One ערוצי" rail is displayed on the Sports page.  
- The selected live channel from the One rail starts playing in the Top Shelf.  
- Video and audio play smoothly without interruptions.  
- Channel logo appears in the top left corner.  
- Program title is displayed.  
- Channel name is displayed.  
- Broadcast start and end time are shown.  
- Program type (e.g., "תוכנית טלוויזיה") is displayed.  
- Short synopsis/description is shown under the metadata.  

### Expected Result:
- The "One ערוצי" rail is displayed on the Sports page, and when a live channel is focused, it plays smoothly in the Top Shelf with correct video, audio, and complete metadata.

<!-- test
id: @Tc286d292
priority: normal
creator: boris103@gmail.com
-->
# Verify Full Screen Playback from Sports 5 Channels Rail

### Description:
Validate that selecting a channel from the "ערוצי ספורט 5" rail enters full screen playback.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate to the **ערוצי ספורט 5** rail.  
4. Select any channel card to start full screen playback.  

### Verifications:
- Selected channel opens in full screen mode.  
- Video and audio play smoothly in full screen.  

### Expected Result:
- The selected channel from the "ערוצי ספורט 5" rail plays in full screen with smooth video and audio.

<!-- test
id: @T34c67110
priority: normal
creator: boris103@gmail.com
-->
# Verify Full Screen Playback from One Channels Rail

### Description:
Validate that selecting a channel from the "ערוצי One" rail enters full screen playback.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate to the **ערוצי One** rail.  
4. Select any channel card to start full screen playback.  

### Verifications:
- Selected channel opens in full screen mode.  
- Video and audio play smoothly in full screen.  

### Expected Result:
- The selected channel from the "ערוצי One" rail plays in full screen with smooth video and audio.

<!-- test
id: @T71d554ec
priority: normal
creator: boris103@gmail.com
-->
# Verify Catchup Playback from "רגעי השיא של השבוע" Rail

### Description:
Validate that selecting any item from the "רגעי השיא של השבוע" rail on the Sports page starts catchup playback in full screen.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate down to the **"רגעי השיא של השבוע"** rail.  
4. Select any content card.  

### Verifications:
- Selected catchup item opens in full screen mode.  
- Video and audio play smoothly without interruptions.  

### Expected Result:
- The selected content from the "רגעי השיא של השבוע" rail plays in full screen with smooth video and audio.

<!-- test
id: @T030d3488
priority: normal
creator: boris103@gmail.com
-->
# Verify VOD Movie Playback from Sports Page

### Description:
Validate that selecting any movie asset from the Sports page starts playback in full screen.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate down to any VOD movie asset.  
4. Select the movie to start playback.  

### Verifications:
- Selected movie opens in full screen mode.  
- Video and audio play smoothly without interruptions.  

### Expected Result:
- The selected VOD movie from the Sports page plays in full screen with smooth video and audio.

<!-- test
id: @Td96d20c6
priority: normal
creator: boris103@gmail.com
-->
# Verify VOD Series Asset Playback from Sports Page

### Description:
Validate that selecting a series asset from the Sports page allows choosing an episode and starts playback in full screen.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate to any VOD series asset.  
4. Select the series asset to open its page.  
5. Choose any episode from the list.  
6. Play the selected episode.  

### Verifications:
- Series page opens successfully after selecting the asset.  
- Selected episode opens in full screen mode.  
- Video and audio play smoothly without interruptions.  

### Expected Result:
- The selected episode from the VOD series plays in full screen with smooth video and audio.

<!-- test
id: @T43cc51dd
priority: normal
creator: boris103@gmail.com
-->
# Verify Catchup Top Shelf Appearance on Sports Page

### Description:
Validate that when focusing on a catchup asset in the Sports page, the Top Shelf displays correct poster and metadata (without playback).

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate to the **"רגעי השיא של השבוע"** rail (catchup rail).  
4. Focus on any catchup asset.  
5. Observe the Top Shelf.  

### Verifications:
- Top Shelf displays the program poster (no playback starts).  
- Program title is shown on the right side.  
- Broadcast date is displayed.  
- Broadcast start and end time are displayed.  
- Program type (e.g., "תוכנית טלוויזיה") is displayed.  
- Program synopsis/description is shown under the metadata.  

### Expected Result:
- The Top Shelf correctly shows the focused catchup program poster and complete metadata including title, broadcast date, time, type, and synopsis, without playback.

<!-- test
id: @T6a0d5967
priority: normal
creator: boris103@gmail.com
-->
# Verify VOD Movie Top Shelf Appearance on Sports Page

### Description:
Validate that when focusing on a VOD movie asset in the Sports page, the Top Shelf displays correct poster/trailer and metadata.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate to any VOD movie asset.  
4. Focus on the movie and observe the Top Shelf.  

### Verifications:
**Mandatory metadata:**  
- Movie title is displayed.  
- Movie tag (e.g., "סרט") is displayed.  
- Synopsis/description is shown under the metadata.  

**Optional metadata (if configured):**  
- Trailer plays in the Top Shelf.  
- Movie duration is displayed.  
- Release year is displayed.  
- Quality indicator (HD/4K) is displayed.  
- Age limit is displayed.  
- Tags related to the movie are displayed.  

### Expected Result:
- The Top Shelf shows the focused VOD movie with mandatory metadata (title, type, synopsis) and, if configured, additional metadata such as trailer, duration, year, quality, age limit, and tags.

<!-- test
id: @Tbe81dbc6
priority: normal
creator: boris103@gmail.com
-->
# Verify VOD Series Top Shelf Appearance on Sports Page

### Description:
Validate that when focusing on a VOD series asset in the Sports page, the Top Shelf displays correct poster/trailer and metadata.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Navigate to any VOD series asset.  
4. Focus on the series and observe the Top Shelf.  

### Verifications:
**Mandatory metadata:**  
- Series title is displayed.  
- Series tag (e.g., "סדרה") is displayed.  
- Synopsis/description is shown under the metadata.  

**Optional metadata (if configured):**  
- Trailer plays in the Top Shelf.  
- Number of seasons or episodes is displayed.  
- Release year is displayed.  
- Quality indicator (HD/4K) is displayed.  
- Age limit is displayed.  
- Tags related to the series are displayed.  

### Expected Result:
- The Top Shelf shows the focused VOD series with mandatory metadata (title, type, synopsis) and, if configured, additional metadata such as trailer, seasons/episodes, year, quality, age limit, and tags.

<!-- test
id: @T064c3519
priority: normal
creator: boris103@gmail.com
-->
# Verify Back Navigation from Full Screen to Sports Page

### Description:
Validate that exiting full screen playback returns the user to the Sports page with the originating channel or asset still focused.

### Steps:
1. Open the app.  
2. Open the Sports page.  
3. Select any channel or VOD asset to start full screen playback.  
4. Press the Back button once on the remote.  

### Verifications:
- Full screen playback exits.  
- Sports page is displayed again.  
- The same channel or asset that was opened remains focused in the rail.  

### Expected Result:
- After pressing Back from full screen, the user is returned to the Sports page with the same channel or asset still focused.
