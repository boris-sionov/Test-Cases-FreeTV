<!-- suite
id: @Sd2411780
emoji: 
-->
# 4K series assets tests



<!-- test
id: @Td5e04bc5
priority: normal
creator: boris103@gmail.com
-->
# Verify 4K Badge on Series Page

### Description:
Validate that 4K series on the Series page display a 4K badge on their posters/thumbnails.  

### Steps:
1. Navigate to the main **Series page** (not the asset page).  
2. Locate a series that supports 4K (examples below).  
   ### Examples:
   - 1883  
   - האפי פייס  
   - 1923  
   - ווטסון  
   - קונפליקט  
   - החיים בערבות לפלנד  
   - הנערים  
3. Observe the top right corner of the series poster/thumbnail.  

### Verifications:
- A **4K badge** is displayed on the top right corner of the series poster/thumbnail.  
- The badge is consistent across all 4K series on the Series page.  

### Expected Result:
- The 4K badge is correctly displayed on the top right corner of series posters/thumbnails on the Series page, indicating that the series is available in 4K quality.

<!-- test
id: @T8f1db9d0
priority: normal
creator: boris103@gmail.com
-->
# Verify 4K Indicators on Series Asset Page

### Description:
Validate that 4K-supported series asset pages display both a 4K logo on the screen and a 4K tag in the metadata area.  

### Steps:
1. Navigate to a 4K-supported series asset page (examples below).  
   ### Examples:  
   - 1883  
   - האפי פייס  
   - 1923  
   - ווטסון  
   - קונפליקט  
   - החיים בערבות לפלנד  
   - הנערים  
2. Observe the top left corner of the screen.  
3. Observe the metadata area under the series title.  

### Verifications:
- A **4K logo** is displayed in the top left corner of the screen.  
- A **4K tag** is displayed in the metadata area under the series title.  
- Both indicators are visible and consistent across all 4K series asset pages.  

### Expected Result:
- The 4K logo and tag are correctly displayed on series asset pages that support 4K, clearly indicating the availability of 4K quality.

<!-- test
id: @Tfea89f03
priority: normal
creator: boris103@gmail.com
-->
# Verify Trailer Button on 4K Series Asset Page

### Description:
Validate that the Trailer button on a 4K series asset page is visible, responsive to focus, and starts trailer playback when pressed.  

### Steps:
1. Navigate to a 4K series asset page (examples below).  
   ### Examples:  
   - 1883  
   - האפי פייס  
   - 1923  
   - ווטסון  
   - קונפליקט  
   - החיים בערבות לפלנד  
   - הנערים  
2. Move focus to the **Trailer** button.  
3. Press on the **Trailer** button.  

### Verifications:
- The **Trailer** button is visible on the 4K series asset page.  
- The button is visually highlighted when in focus.  
- Pressing the button starts trailer playback.  

### Expected Result:
- The Trailer button on the 4K series asset page is functional, responds to focus, and starts trailer playback when pressed.

<!-- test
id: @Tb9ee2612
priority: normal
creator: boris103@gmail.com
-->
# Verify Trailer Button on 4K Series Asset Page

### Description:
Validate that the Trailer button on a 4K series asset page is visible, responsive to focus, and starts trailer playback when pressed (if available).  

### Steps:
1. Navigate to a 4K series asset page (examples below).  
   ### Examples:  
   - 1883  
   - האפי פייס  
   - 1923  
   - ווטסון  
   - קונפליקט  
   - החיים בערבות לפלנד  
   - הנערים  
2. Move focus to the **Trailer** button.  
3. Press on the **Trailer** button.  

### Verifications:
- The **Trailer** button is visible on the 4K series asset page (if available).  
- The button is visually highlighted when in focus.  
- Pressing the button starts trailer playback.  

### Expected Result:
- The Trailer button on the 4K series asset page is functional, responds to focus, and starts trailer playback when pressed.  

**Note:** Not all 4K series assets include a Trailer button.

<!-- test
id: @T431e714c
priority: normal
creator: boris103@gmail.com
-->
# Verify Play Button on 4K Series Asset Page (First Watch Episode)

### Description:
Validate that the Play button on a 4K series asset page is visible, responsive to focus, and starts playback of the episode from the beginning when it has never been watched.  

### Precondition:
The selected 4K episode has never been watched.  

### Steps:
1. Navigate to a 4K series asset page (examples below).  
   ### Examples:  
   - 1883  
   - האפי פייס  
   - 1923  
   - ווטסון  
   - קונפליקט  
   - החיים בערבות לפלנד  
   - הנערים  
2. Move focus to the **Play** button.  
3. Press on the **Play** button.  

### Verifications:
- The **Play** button is visible on the 4K series asset page.  
- The button is visually highlighted when in focus.  
- Pressing the button starts playback of the episode from the beginning.  

### Expected Result:
- The Play button on the 4K series asset page is functional, responds to focus, and starts playback of the episode from the beginning when pressed.

<!-- test
id: @Ta2a41e38
priority: normal
creator: boris103@gmail.com
-->
# Verify 4K Episode Playback Resumes from Bookmark

### Description:
Validate that reopening a previously partially watched 4K series episode resumes playback from the last watched (bookmarked) position.  

### Steps:
1. Open any 4K series asset page and start playback of an episode (examples below).  
   ### Examples:  
   - 1883  
   - האפי פייס  
   - 1923  
   - ווטסון  
   - קונפליקט  
   - החיים בערבות לפלנד  
   - הנערים  
2. Watch the episode for a few minutes or seek forward a few minutes.  
3. Exit playback and return to the series asset page.  
4. Move focus to the **Play** button.  
5. Press on the **Play** button.  

### Verifications:
- The episode resumes playback from the last watched (bookmarked) position where it was previously stopped.  

### Expected Result:
- When reopening a previously partially watched 4K episode, playback resumes from the last watched (bookmarked) position instead of starting from the beginning.
