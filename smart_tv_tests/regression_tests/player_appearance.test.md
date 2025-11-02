<!-- suite
id: @S757022c6
emoji: 
-->
# Player appearance

### Requirements

<!-- test
id: @T2af1ab88
priority: normal
creator: boris103@gmail.com
-->
# Verify Asset Metadata Display On Player UI For Live Channel

### Description:
Validate that the Player UI displays correct metadata, live playback status, and the "ערוצים" button when watching a live channel.

### Steps:
1. Start playback of any **live channel** currently airing.  
2. Press **OK** (this will also pause the video) **or** press **Left** on the remote to open the **Player UI** overlay.

### Verifications:
- Channel label shows **channel name + current program time range** (e.g., "ערוץ 11 14:00–15:00").  
- **Program title** is present and not empty.  
- **Date label** is displayed in the correct format for today.  
- **Scrubber** shows current playback position:
  - Scrubber knob is at the **right edge**, indicating live position.  
  - A **“עכשיו”** (“Now”) label appears near the scrubber.  
  - Timeline behind the knob is fully filled up to the right edge.  
- **Current time alignment**: playback corresponds to the device’s current time.  
- **Restart** button (e.g., “להתחיל מחדש”) is visible and enabled below the player.  
- **“ערוצים”** button is visible at the **top right corner** of the Player UI.

### Expected Result:
- Pressing **OK** (which pauses playback) or **Left** successfully opens the Player UI.  
- Player UI displays accurate channel and program metadata (name, time range, title, date).  
- The scrubber correctly indicates **live playback** with the knob at the right end and the **“עכשיו���** label.  
- Both **Restart** and **“ערוצים”** buttons are visible and functional.

<!-- test
id: @Tbf2eb0b4
priority: normal
creator: boris103@gmail.com
-->
# Verify Asset Metadata Display On Player UI For Time-Shift Playback

### Description:
Validate that the Player UI displays correct metadata during **Time-Shift playback** after restarting a live program.

### Steps:
1. Start playback of any **Live channel**.  
2. Select **Start Over** (“להתחיל מחדש”) to enter **Time-Shift mode**.  
3. Raise the **Player UI**.

### Verifications:
- The **channel name** is displayed correctly.  
- The **program title** appears and is not empty.  
- The **program time range** (e.g., 14:00–15:00) is shown.  
- The **date label** is displayed correctly.  
- The **Back to Live** (“חזרה לשידור החי”) button appears below the player.  
- The **scrubber** is visible and reflects the current playback position within the program timeline.  

### Expected Result:
- During Time-Shift playback, the Player UI displays the correct channel name, program title, time range, and date label, with the Back to Live button visible and an active scrubber showing the current playback position.

<!-- test
id: @Tfb0aa3cc
priority: normal
creator: boris103@gmail.com
-->
# Verify Asset Metadata Display On Player UI For Catchup Channel

### Description:
Validate that the Catchup Player UI displays correct asset metadata, playback timeline, and functional buttons including “להתחיל מחדש” (Start Over) and “חזרה לשידור החי” (Back to Live).

### Steps:
1. Start playback of any **Catchup channel program**.  
2. Press **OK** (this will also pause the video), **Left**, or **Right** on the remote for the **Player UI** to appear.

### Verifications:
- **Channel name** is displayed at the top of the Player UI.  
- **Program title** (e.g., “לאהוב אותי 2 - פרק 3”) is visible and not empty.  
- **Date label** appears correctly:
  - “מוקדם יותר היום” — if the program aired today.  
  - “אתמול” — if the program aired the previous day.  
  - **“יום בשבוע + תאריך”** — for earlier days (e.g., “יום שישי 17.10”).  
- **Scrubber** shows playback progress:
  - Current playback time displayed on the **left**.  
  - Total program duration displayed on the **right**.  
  - Knob position reflects current playback progress.  
- **Restart** button (“להתחיל מחדש”) is visible and enabled below the player.  
- **Back to Live** button (“חזרה לשידור החי”) is visible and enabled below the player.  
- **“ערוצים”** button appears at the **top right corner** of the Player UI.  

### Expected Result:
- Pressing **OK**, **Left**, or **Right** causes the **Player UI** to appear.  
- Catchup Player UI displays accurate asset metadata including title, channel name, and correct **date label** (“מוקדם יותר היום” / “אתמול” / “יום בשבוע + תאריך”).  
- Scrubber correctly reflects playback position and duration.  
- **Restart** and **Back to Live** buttons are visible and functional.  
- **“ערוצים”** button is displayed at the top right of the Player UI.

<!-- test
id: @T228004cb
priority: normal
creator: boris103@gmail.com
-->
# Verify Asset Metadata Display On Player UI For Movie



<!-- test
id: @T68a2f123
priority: normal
creator: boris103@gmail.com
-->
# Verify Asset Metadata Display On Player UI For Series Asset

### Description:
Validate that the Player UI displays correct metadata when watching a **series episode** (VOD).

### Steps:
1. Start playback of any **series episode**.  
2. Raise the **Player UI**.

### Verifications:
- **Series title** and **episode title** are displayed correctly.  
- **Season** and **episode number** appear in the format:  
  - “עונה [season number] · פרק [episode number]”.  
- **Short description** of the episode is visible and not empty.  
- **Category label** shows “סדרה”.  
- **Age rating** icon (e.g., 12+, 14+, 18+) is visible.  
- **Scrubber** displays current playback position and total duration.  
- **Start Over** button appears below the player.  

### Expected Result:
- Player UI for a series episode displays complete and accurate metadata, including series title, episode number, season, description, category, and age rating.

<!-- test
id: @T4b3d8da6
priority: normal
creator: boris103@gmail.com
-->
# Verify Scrubber Display On Live Playback

### Description:
Validate that the Player UI displays a visible and accurate scrubber during **Live playback**.

### Steps:
1. Start playback of any **Live channel** currently airing.
2. Raise the **Player UI**.

### Verifications:
- The **scrubber** is visible on the Player UI.
- The **program time range** (e.g., 14:00–15:00) is displayed.
- The **current playback time** appears on the **left side** of the scrubber.
- When at live, the **scrubber knob** is at the **right edge** and the label **“עכשיו”** (“Now”) is shown.
- Seeking **back** updates the scrubber position; attempting to seek **forward** does nothing.

### Expected Result:
- The scrubber shows the current program’s time range and position, displaying **“עכשיו”** at the live point and reflecting valid seek-back behavior only.

<!-- test
id: @T333450b1
priority: normal
creator: boris103@gmail.com
-->
# Verify Scrubber Display On Time-Shift Playback

### Description:
Validate that the Player UI displays a visible and functional scrubber during **Time-Shift playback** after starting over a live program.

### Steps:
1. Start playback of any **Live channel**.
2. Select **Start Over** (“להתחיל מחדש”) to enter **Time-Shift** mode.
3. Raise the **Player UI**.

### Verifications:
- The **scrubber** is visible and active.
- The **program time range** (e.g., 14:00–15:00) is displayed.
- The **current playback time** appears on the **left side**; **total duration** on the **right**.
- The **progress indicator** moves smoothly as playback continues.
- Seeking **back** and **forward** updates the scrubber position correctly within the program.
- Selecting **Back to Live** (“חזרה לשידור החי”) moves the knob to the **right edge** and replaces the right label with **“עכשיו”**.

### Expected Result:
- In Time-Shift, the scrubber accurately reflects position and duration, responds to seek in both directions, and correctly updates when returning to live.

<!-- test
id: @T45d29ef7
priority: normal
creator: boris103@gmail.com
-->
# Verify Scrubber Display On Catchup Playback

### Description:
Validate that the Player UI displays a visible and functional scrubber during **Catchup playback**.

### Steps:
1. Start playback of any **Catchup asset**.
2. Raise the **Player UI**.

### Verifications:
- The **scrubber** is visible and active.
- The **elapsed time** appears on the **left side** of the scrubber.
- The **total program duration** appears on the **right side**.
- The **progress indicator** moves smoothly during playback.
- Seeking **backward** or **forward** updates the scrubber position correctly.
- The scrubber disappears automatically when the Player UI fades out.

### Expected Result:
- The scrubber accurately shows playback progress, elapsed time, and total duration, updating dynamically during Catchup playback.

<!-- test
id: @T84afb992
priority: normal
creator: boris103@gmail.com
-->
# Verify Scrubber Display On Movie Playback

### Description:
Validate that the Player UI displays a visible and functional scrubber during **Movie playback**.

### Steps:
1. Start playback of any **Movie asset**.
2. Raise the **Player UI**.

### Verifications:
- The **scrubber** is visible on the Player UI.
- The **current playback time** appears on the **left side**.
- The **total movie duration** appears on the **right side**.
- The **progress bar** moves smoothly as playback continues.
- Seeking **backward** or **forward** updates the scrubber position accurately.
- The scrubber hides automatically when the Player UI fades out.

### Expected Result:
- The scrubber correctly displays elapsed and total time, updating dynamically during movie playback and responding accurately to seek actions.

<!-- test
id: @Te1a25431
priority: normal
creator: boris103@gmail.com
-->
# Verify Scrubber Display On Series Playback

### Description:
Validate that the Player UI displays a visible and functional scrubber during **Series episode playback**.

### Steps:
1. Start playback of any **Series episode**.
2. Raise the **Player UI**.

### Verifications:
- The **scrubber** is visible on the Player UI.
- The **current playback time** appears on the **left side**.
- The **total episode duration** appears on the **right side**.
- The **progress bar** moves smoothly during playback.
- Seeking **backward** or **forward** updates the scrubber position accurately.
- The scrubber disappears automatically when the Player UI fades out.

### Expected Result:
- The scrubber accurately displays elapsed and total time, updates dynamically during playback, and responds correctly to seek actions for a series episode.
