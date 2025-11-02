<!-- suite
id: @S5f223026
emoji: 
-->
# Player



<!-- test
id: @T5071c136
priority: normal
creator: boris103@gmail.com
-->
# Verify Start Over Button Functionality On Live Playback

### Description:
Validate that the **Start Over** (“להתחיל מחדש”) button on the Player UI restarts the current live program from the beginning.

### Steps:
1. Start playback of any **Live channel**.  
2. Raise the **Player UI**.  
3. Select the **Start Over** (“להתחיל מחדש”) button.

### Verifications:
- **Start Over** button is **visible** and **enabled** on the Player UI.  
- After selecting **Start Over**, playback restarts from the **beginning of the current program**.  
- The **scrubber position** updates to reflect the correct point within the program’s timeline (may appear in the middle depending on the program duration).  
- Audio and video playback are **stable** after restarting (no glitches or buffering issues).

### Expected Result:
- Selecting **Start Over** on a live channel restarts the current program from the beginning, with stable playback and an accurate scrubber position based on the program timeline.

<!-- test
id: @T2e4f48fd
priority: normal
creator: boris103@gmail.com
-->
# Verify Channels Button Functionality On Live Playback

### Description:
Validate that the **Channels** (“ערוצים”) button on the Player UI opens the channels panel while Live playback continues.

### Steps:
1. Start playback of any **Live channel**.  
2. Raise the **Player UI**.  
3. Select the **Channels** (“ערוצים”) button.

### Verifications:
- **Channels** button is **visible** and **enabled** on the Player UI.  
- Selecting **“ערוצים”** opens the **channels panel/overlay**.  
- **Live playback continues** in the background (not paused or stopped).  
- **Audio and video** remain smooth and uninterrupted while the panel is open.  
- Exiting the channels panel returns to the Player UI or live playback screen normally.

### Expected Result:
- Selecting the **Channels** button during Live playback opens the channels panel while live playback continues smoothly in the background.

<!-- test
id: @T6d5859fb
priority: normal
creator: boris103@gmail.com
-->
# Verify Back To Live Button Functionality On Live Playback

### Description:
Validate that selecting the **Back to Live** (“חזרה לשידור החי”) button during time-shift playback returns the user to the live position.

### Steps:
1. Start playback of any **Live channel**.  
2. Raise the **Player UI**.  
3. Select **Start Over** (“להתחיל מחדש”) to enter time-shift mode.  
4. Raise the **Player UI** again and select **Back to Live** (“חזרה לשידור החי”).

### Verifications:
- **Back to Live** button is visible and enabled.  
- Selecting it moves playback to the **current live position**.  
- Video and audio resume smoothly in **live mode**.

### Expected Result:
- Selecting **Back to Live** returns playback to the current live moment and resumes normal live streaming.

<!-- test
id: @T897d4807
priority: normal
creator: boris103@gmail.com
-->
# Verify Start Over Button Functionality On Catchup Playback

### Description:
Validate that the **Start Over** (“להתחיל מחדש”) button on the Player UI restarts the Catchup program from the beginning.

### Steps:
1. Start playback of any **Catchup asset**.  
2. Watch the program for a short time **or seek forward**.
3. Raise the **Player UI**.  
4. Select the **Start Over** (“להתחיל מחדש”) button.

### Verifications:
- **Start Over** button is visible and enabled on the Player UI.  
- Selecting it restarts playback from the **beginning of the program**.  
- Audio and video playback are **stable** and resume smoothly from the start.  

### Expected Result:
- Selecting **Start Over** during Catchup playback restarts the program from the beginning and resumes playback normally without interruptions.

<!-- test
id: @T0daaef30
priority: normal
creator: boris103@gmail.com
-->
# Verify Back To Live Button Functionality On Catchup Playback

### Description:
Validate that the **Back to Live** (“חזרה לשידור החי”) button on the Player UI moves playback to the current live moment.

### Steps:
1. Start playback of any **Catchup asset**.  
2. Watch the program for a short time **or seek backward** within the timeline.  
3. Raise the **Player UI**.  
4. Select the **Back to Live** (“חזרה לשידור החי”) button.

### Verifications:
- **Back to Live** button is visible and enabled on the Player UI.  
- Selecting it moves playback to the **current live broadcast point**.  
- The **scrubber** jumps to the **right edge**, showing the live position with the “עכשיו” (“Now”) label.  
- Audio and video resume smoothly in **live mode** without delay.

### Expected Result:
- Selecting **Back to Live** during Catchup playback immediately jumps to the current live moment and resumes continuous live playback.

<!-- test
id: @Tbee975ed
priority: normal
creator: boris103@gmail.com
-->
# Verify Channels Button Functionality On Catchup Playback

### Description:
Validate that the **Channels** (“ערוצים”) button on the Player UI opens the channels panel while Catchup playback continues.

### Steps:
1. Start playback of any **Catchup asset**.  
2. Raise the **Player UI**.  
3. Select the **Channels** (“ערוצים”) button.

### Verifications:
- **Channels** button is **visible** and **enabled** on the Player UI.  
- Selecting **“ערוצים”** opens the **channels panel/overlay**.  
- **Catchup playback continues** in the background (not paused or stopped).  
- **Audio and video** remain smooth and uninterrupted.  
- Exiting the channels panel returns to normal playback view.

### Expected Result:
- Selecting the **Channels** button during Catchup playback opens the channels panel while playback continues normally in the background.

<!-- test
id: @T447edc1e
priority: normal
creator: boris103@gmail.com
-->
# Verify Start Over Button Functionality On VOD Playback

### Description:
Validate that the **Start Over** (“להתחיל מחדש”) button on the Player UI restarts the VOD asset from the beginning.

### Steps:
1. Start playback of any **VOD asset** (movie or series episode).  
2. Watch the video for a short time **or seek forward**.  
3. Raise the **Player UI**.  
4. Select the **Start Over** (“להתחיל מחדש”) button.

### Verifications:
- **Start Over** button is **visible** and **enabled** on the Player UI.  
- Selecting it restarts playback from the **beginning of the asset**.  
- Audio and video playback resume smoothly from the start.  
- Program metadata (title, category, age rating) remain correct after restart.

### Expected Result:
- Selecting **Start Over** during VOD playback restarts the asset from the beginning and resumes playback without interruptions.

<!-- test
id: @T6091df99
priority: normal
creator: boris103@gmail.com
-->
# Verify Pause And Play Functionality On VOD Playback

### Description:
Validate that pressing the pause and play buttons on the remote correctly pauses and resumes VOD playback.

### Steps:
1. Start playback of any **VOD asset** (movie or series episode).  
2. Press **OK** to raise the Player UI.  
3. Press **Pause** on the remote.  
4. Wait a few seconds, then press **Play** to resume playback.

### Verifications:
- Pressing **Pause** stops playback immediately.  
- Pressing **Play** resumes playback from the same position.  
- Audio and video resume **smoothly** with no delay or glitches.  
- The **scrubber** resumes progress after playback continues.

### Expected Result:
- Pressing **Pause** halts playback, and pressing **Play** resumes it seamlessly from the same point.

<!-- test
id: @Tdfa2087e
priority: normal
creator: boris103@gmail.com
-->
# Verify Pause And Play Functionality

### Description:
Validate that pressing the pause and play buttons on the remote correctly pauses and resumes playback on all asset types (Live, time-shift, Catchup, and VOD).

### Steps:
1. Start playback of any asset (Live, time-shift, Catchup, or VOD).  
2. Press **OK** to raise the **Player UI**.  
3. Press **Pause** on the remote to pause playback.  
4. Wait a few seconds, then press **Play** to resume playback.

### Verifications:
- Pressing **Pause** stops playback immediately.  
- Pressing **Play** resumes playback from the same position.  
- **Audio and video** resume smoothly without delay or glitches.  
- **Scrubber** resumes progress correctly after playback continues.  

### Expected Result:
- Pressing **Pause** halts playback, and pressing **Play** resumes it seamlessly from the same position across all asset types.

<!-- test
id: @T449eda93
priority: normal
creator: boris103@gmail.com
-->
# Verify Play/Pause Dedicated Button Functionality On Remote

### Description:
Validate that pressing the **Play/Pause** dedicated button on the remote correctly pauses and resumes playback on all asset types (Live, time-shift, Catchup, and VOD).

### Steps:
1. Start playback of any asset (Live, time-shift, Catchup, or VOD).  
2. Press the **Play/Pause** button on the remote to pause playback.  
3. Wait a few seconds.  
4. Press the **Play/Pause** button again to resume playback.

### Verifications:
- Pressing the **Play/Pause** button once pauses playback immediately.  
- Pressing it again resumes playback from the same position.  
- **Audio and video** resume smoothly without delay or glitches.  
- **Scrubber** resumes progress correctly after playback continues.  

### Expected Result:
- The **Play/Pause** dedicated button on the remote correctly pauses and resumes playback, maintaining smooth and uninterrupted playback transitions.

<!-- test
id: @T57bce7a2
priority: normal
creator: boris103@gmail.com
-->
# Verify Pause Mode Display On All Asset Types

### Description:
Validate the Player UI appearance and behavior when playback is paused on any asset type (Live, time-shift, Catchup, or VOD).

### Steps:
1. Start playback of any asset (Live, time-shift, Catchup, or VOD).  
2. Press **Pause** on the remote or Player UI to pause playback.  
3. Wait for a few seconds without pressing any additional buttons.

### Verifications:
- The **Player UI fades out** after a few seconds of inactivity.  
- The **scrubber** also fades out.  
- The **Play button** remains visible on screen.  
- The **asset title**, **tags**, and **movie/series name** remain displayed.  
- The **video frame** stays visible in a paused state (no motion).  
- Audio remains muted (no playback sound).

### Expected Result:
- When paused, the Player UI and scrubber fade out, leaving only the play icon, asset title, and tags visible while the video frame remains frozen.

<!-- test
id: @T69ce0723
priority: normal
creator: boris103@gmail.com
-->
# Verify Seek Functionality On Live Playback

### Description:
Validate the seek behavior on **Live playback**, ensuring that seeking backward functions correctly while seeking forward is restricted.

### Steps:
1. Start playback of any **Live channel**.  
2. Raise the **Player UI**.  
3. Attempt to **seek backward** using the remote control.  
4. Attempt to **seek forward** using the remote control.

### Verifications:
- **Seek backward**:
  - Playback moves a few seconds/minutes **back in time**.  
  - The **scrubber position** updates accordingly.  
  - Audio and video resume smoothly from the new position.  
- **Seek forward**:
  - Playback remains at the **current position** (no forward seek is performed).  
  - The **scrubber** does not move forward.  
  - No error message or visual glitch appears.  

### Expected Result:
- On Live playback, **seek backward** works as expected, allowing time-shift playback.  
- **Seek forward** has no effect and playback continues normally without disruption.

<!-- test
id: @Ta62a08b5
priority: normal
creator: boris103@gmail.com
-->
# Verify Seek Functionality On Catchup Playback

### Description:
Validate that both seek forward and backward actions work correctly during **Catchup playback**.

### Steps:
1. Start playback of any **Catchup asset**.  
2. Raise the **Player UI**.  
3. Use the remote to **seek backward** within the timeline.  
4. Use the remote to **seek forward** within the timeline.

### Verifications:
- **Seek backward**:
  - Playback jumps a few seconds/minutes **back** in the timeline.  
  - The **scrubber position** updates correctly.  
  - Audio and video resume smoothly from the new position.  
- **Seek forward**:
  - Playback jumps **ahead** in the timeline as expected.  
  - The **scrubber position** moves forward accurately.  
  - Audio and video resume seamlessly after seeking.  
  - No delay, buffering, or synchronization issues occur.

### Expected Result:
- On Catchup playback, both **seek forward** and **seek backward** function as expected, updating the timeline accurately and resuming smooth playback.

<!-- test
id: @T12a4b7fd
priority: normal
creator: boris103@gmail.com
-->
# Verify Seek Functionality On VOD Playback

### Description:
Validate that both seek forward and backward actions work correctly during **VOD playback** (movie or series episode).

### Steps:
1. Start playback of any **VOD asset**.  
2. Raise the **Player UI**.  
3. Use the remote to **seek backward** within the timeline.  
4. Use the remote to **seek forward** within the timeline.

### Verifications:
- **Seek backward**:
  - Playback moves a few seconds/minutes **back** within the asset.  
  - The **scrubber** updates accurately to the new position.  
  - Playback resumes smoothly from the new point.  
- **Seek forward**:
  - Playback moves **ahead** in the timeline as expected.  
  - The **scrubber** reflects the updated position.  
  - Audio and video resume without delay or desynchronization.  

### Expected Result:
- On VOD playback, both **seek forward** and **seek backward** operate correctly, updating the timeline precisely and resuming playback smoothly.
