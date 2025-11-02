<!-- suite
id: @S1c5a2692
emoji: 
-->
# Kids Page



<!-- test
id: @T0a80d1b9
priority: normal
creator: boris103@gmail.com
-->
# Verify Kids Page Opens Successfully

### Description:
Validate that the Kids page loads correctly and the hero trailer starts playing automatically when the page opens.

### Steps:
1. Open the **Kids** page.  
2. Observe the page layout and hero area.  

### Verifications:
- The Kids page opens successfully without errors.  
- The hero area is visible at the top of the page.  
- A **trailer** starts playing automatically in the hero area.  
- Video and audio playback start smoothly without delay or stutter.  

### Expected Result:
- The Kids page loads correctly, and the hero trailer begins playing automatically with smooth playback.

<!-- test
id: @T8b8a7962
priority: normal
creator: boris103@gmail.com
-->
# Verify Metadata Display On Hero Area Of Kids Page

### Description:
Validate that the Kids page Hero area displays all mandatory metadata and optional metadata if available, and that it can play either a movie or a series trailer.

### Steps:
1. Open the **Kids** page from the side menu.  
2. Focus on the **Hero area**.  

### Verifications:
- Mandatory metadata is displayed:  
  - Asset **title/logo**.  
  - **Synopsis/description** text.  
  - **Primary action buttons** (e.g., “צפייה עכשיו”, “עוד פרטים”) are visible.  
- Optional metadata (if available):  
  - Genre(s), year, HD/4K tag, and age rating.  
- Hero can play **either a movie or a series trailer** automatically.  
- Layout is **RTL-aligned** with no clipping, truncation, or overlap.  

### Expected Result:
- The Hero area on the Kids page displays all mandatory metadata, optional metadata if available, and maintains a clean RTL-aligned layout while playing a movie or series trailer.

<!-- test
id: @T28a1c43f
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback On Top Shelf When Focused On A Channel From Prescholl CHannels Rail

### Description:
Validate that when focusing on a channel in the “ערוצים לילדי הגן” (Preschool Channels) rail, the channel starts playing on the Top Shelf.

### Steps:
1. Open the **Kids** page.  
2. Scroll down to the **“ערוצים לילדי הגן” (Preschool Channels)** rail.  
3. Move focus between several channels in the rail.  
4. Observe the Top Shelf area while focusing on each channel.  

### Verifications:
- The Top Shelf updates when focus changes to a different channel.  
- The focused channel starts playing automatically in the Top Shelf.  
- The video and audio start smoothly without delay or stutter.  
- The displayed metadata on the Top Shelf matches the focused channel (logo, title, and current program info if available).  

### Expected Result:
- When focusing on any channel, the Top Shelf updates instantly and starts playing that channel smoothly with matching metadata.

<!-- test
id: @Tb02ebbdc
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback In Fullscreen From Preschool Channels Rail

### Description:
Validate that selecting a channel from the “ערוצים לילדי הגן” (Preschool Channels) rail starts playback in fullscreen mode.

### Steps:
1. Open the **Kids** page.  
2. Scroll down to the **“ערוצים לילדי הגן” (Preschool Channels)** rail.  
3. Select any channel tile from the rail.  
4. Observe playback behavior.  

### Verifications:
- Selecting a channel from the rail opens playback in **fullscreen mode**.  
- The video and audio start smoothly without delay or buffering.  
- Player controls (e.g., Back, Play/Pause) are available and responsive.  
- Exiting fullscreen returns to the Kids page at the same rail position and focused tile.  

### Expected Result:
- When selecting a channel from the “ערוצים לילדי הגן” (Preschool Channels) rail, playback starts in fullscreen mode with smooth video and audio, and exiting returns to the same position on the Kids page.

<!-- test
id: @T360171b6
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback On Top Shelf When Focused On A Channel From Kids And Teens Rail

### Description:
Validate that when focusing on a channel in the “ערוצים לילדים ונוער” (Kids and Teens Channels) rail, the channel starts playing on the Top Shelf.

### Steps:
1. Open the **Kids** page.  
2. Scroll down to the **“ערוצים לילדים ונוער” (Kids and Teens Channels)** rail.  
3. Move focus between several channels in the rail.  
4. Observe the Top Shelf area while focusing on each channel.  

### Verifications:
- The focused channel starts playing automatically in the Top Shelf.  
- Video and audio playback start smoothly without delay or stutter.  
- The displayed metadata on the Top Shelf matches the focused channel (logo, title, and current program info if available).  

### Expected Result:
- When focusing on any channel in the “ערוצים לילדים ונוער” (Kids and Teens Channels) rail, the Top Shelf updates instantly and starts playing that channel smoothly with matching metadata.

<!-- test
id: @T03032d86
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback In Fullscreen From Kids And Teens Channels Rail

### Description:
Validate that selecting a channel from the “ערוצים לילדים ונוער” (Kids and Teens Channels) rail starts playback in fullscreen mode.

### Steps:
1. Open the **Kids** page.  
2. Scroll down to the **“ערוצים לילדים ונוער” (Kids and Teens Channels)** rail.  
3. Select any channel tile from the rail.  
4. Observe playback behavior.  

### Verifications:
- Selecting a channel from the rail opens playback in **fullscreen mode**.  
- Video and audio start smoothly without delay or buffering.  
- Player controls (e.g., Back, Play/Pause) are visible and responsive.  
- Exiting fullscreen returns to the Kids page at the same rail position and focused tile.  

### Expected Result:
- When selecting a channel from the “ערוצים לילדים ונוער” (Kids and Teens Channels) rail, playback starts in fullscreen mode with smooth video and audio, and exiting returns to the same position on the Kids page.

<!-- test
id: @T110c410f
priority: normal
creator: boris103@gmail.com
-->
# Verify VOD Movie Playback From Kids Page

### Description:
Validate that selecting a movie from the Kids page starts VOD movie playback successfully.

### Steps:
1. Open the **Kids** page.  
2. Scroll to any rail containing **movie content**.  
3. Select a movie tile and start playback.  

### Verifications:
- The selected movie starts playing in fullscreen mode.  
- Video and audio playback begin smoothly without delay or buffering.  
- Player controls (e.g., Play/Pause, Back) are visible and responsive.  
- Exiting playback returns to the Kids page at the same tile position.  

### Expected Result:
- VOD movie playback starts successfully from the Kids page with smooth performance, and exiting returns to the same position.

<!-- test
id: @T1bf95273
priority: normal
creator: boris103@gmail.com
-->
# Verify VOD Series Asset Playback From Kids Page

### Description:
Validate that selecting a series from the Kids page starts the correct VOD series playback.

### Steps:
1. Open the **Kids** page.  
2. Scroll to any rail containing **series content**.  
3. Select a series tile and start playback.  

### Verifications:
- The selected series starts playback in fullscreen mode.  
- Video and audio playback begin smoothly without delay or buffering.  
- Player controls are visible and responsive.  
- Exiting playback returns to the same rail and focused tile.  

### Expected Result:
- VOD series playback starts correctly from the Kids page and functions smoothly with proper navigation back to the same position.

<!-- test
id: @T8df87c4e
priority: normal
creator: boris103@gmail.com
-->
# Verify VOD Movie Top Shelf Appearance On Kids Page

### Description:
Validate that when focusing on a VOD movie on the Kids page, the Top Shelf displays the correct movie information.

### Steps:
1. Open the **Kids** page.  
2. Scroll to a rail containing **movie content**.  
3. Focus on several movie tiles and observe the Top Shelf area.  

### Verifications:
- Displays correct metadata: movie **title**, **description**, **year**, and **tags** (if available).  
- The artwork or background updates to match the focused movie.  
- No visual glitches, truncation, or overlapping text.  

### Expected Result:
- The Top Shelf displays accurate and complete movie metadata with proper layout and visual updates when focusing on any movie tile.

<!-- test
id: @Tc33f6369
priority: normal
creator: boris103@gmail.com
-->
# Verify VOD Series Top Shelf Appearance On Kids Page

### Description:
Validate that when focusing on a VOD series on the Kids page, the Top Shelf displays the correct series information.

### Steps:
1. Open the **Kids** page.  
2. Scroll to a rail containing **series content**.  
3. Focus on several series tiles and observe the Top Shelf area.  

### Verifications:
- Displays correct metadata: series **title/logo**, **description**, **number of seasons**, and **tags** (if available).  
- Artwork and background update to match the focused series.  
- Layout is clean and **RTL-aligned** without text clipping or overlap.  

### Expected Result:
- The Top Shelf displays correct and updated series metadata and visuals for each focused series tile on the Kids page.

<!-- test
id: @T16fa434d
priority: normal
creator: boris103@gmail.com
-->
# Verify Back Navigation From Fullscreen To Kids Page

### Description:
Validate that after watching any VOD movie, series, or channel in fullscreen mode, the user can return to the Kids page correctly.

### Steps:
1. Open the **Kids** page.  
2. Select any movie, series, or channel and start playback in **fullscreen mode**.  
3. While the content is playing, press the **Back** button on the remote or controller.  

### Verifications:
- Playback stops and the app returns to the Kids page.  
- The focus returns to the same rail and tile from which playback was started.  

### Expected Result:
- Exiting fullscreen mode returns the user smoothly to the Kids page, maintaining the correct position and focus.
