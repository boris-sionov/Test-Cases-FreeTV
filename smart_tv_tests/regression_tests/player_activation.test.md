<!-- suite
id: @S52836728
emoji: 
-->
# Player activation



<!-- test
id: @T3cb22e6c
priority: normal
creator: boris103@gmail.com
-->
# Verify Player UI Auto Display On Playback Start

### Description:
Validate that the Player UI appears automatically when playback starts and fades out after a few seconds.

### Steps:
1. Start playback of any content (Live, Catchup, or VOD).  
2. Observe the Player UI when playback begins.  

### Verifications:
- Player UI appears automatically upon playback start.  
- Player UI remains visible for approximately **3 seconds**.  
- After 3 seconds, the Player UI **fades out automatically** if no user action is taken.  

### Expected Result:
- The Player UI displays automatically at the start of playback and fades out after 3 seconds without user interaction.

<!-- test
id: @T6ce7a8f3
priority: normal
creator: boris103@gmail.com
-->
# Verify BACK Button Behavior When Player UI Is Visible

### Description:
Validate that pressing the BACK button hides the Player UI while playback continues.

### Steps:
1. Start playback of any content.
2. Raise the **Player UI**.
3. Press **BACK** on the remote while the Player UI is visible.

### Verifications:
- The **Player UI is immediately removed** from the screen.
- **Playback continues** seamlessly in full-screen (no pause or stop).
- Audio and video remain **stable** (no stutter, no mute).

### Expected Result:
- Pressing **BACK** when the Player UI is visible hides the UI and returns to uninterrupted full-frame playback.

<!-- test
id: @T0cc8ba2d
priority: normal
creator: boris103@gmail.com
-->
# Verify BACK Button Behavior When Player UI Is Not Visible

### Description:
Validate that pressing the BACK button when the Player UI is not visible stops playback and returns the user to the previous screen.

### Steps:
1. Start playback of any content.  
2. Wait for the **Player UI** to fade out automatically.  
3. Press **BACK** on the remote when the Player UI is not visible.

### Verifications:
- **Playback stops** immediately after pressing BACK.  
- The user is **returned to the previous screen** (e.g., content rail or details page).  
- No visual or audio glitches occur during the transition.

### Expected Result:
- Pressing **BACK** when the Player UI is not visible stops playback and returns the user to the previous screen.

<!-- test
id: @T16c12930
priority: normal
creator: boris103@gmail.com
-->
# Verify Player UI Auto Display On Playback Start

### Description:
Validate that the Player UI automatically appears when playback begins and fades out after a few seconds.

### Steps:
1. Start playback of any content.
2. Observe the **Player UI** behavior at the beginning of playback.

### Verifications:
- **Player UI appears automatically** when playback starts.  
- The Player UI remains visible for approximately **3 seconds**.  
- After 3 seconds, the **Player UI fades out automatically** if no user action is taken.  
- **Playback continues** smoothly during the entire process.

### Expected Result:
- The Player UI appears automatically for 3 seconds at playback start, then fades out while playback continues uninterrupted.

<!-- test
id: @T23ae3d3e
priority: normal
creator: boris103@gmail.com
-->
# Verify Player UI Reappears During Live Playback

### Description:
Validate that the Player UI can be raised correctly during Live playback using the supported remote buttons.

### Steps:
1. Start playback of any **Live channel**.  
2. Wait for the **Player UI** to fade out automatically.  
3. Press **OK** (this will also pause the video) or **Left** on the remote.

### Verifications:
- Pressing **OK** pauses playback and the **Player UI appears** on the screen.  
- Pressing **Left** displays the **Player UI** without pausing playback.  
- When no further action is taken, the **Player UI fades out automatically** after a few seconds.  
- **Playback continues** smoothly once the Player UI disappears.

### Expected Result:
- Pressing **OK** or **Left** during Live playback raises the Player UI (OK pauses, Left doesn’t).  
- The Player UI fades out automatically after a few seconds of inactivity while playback remains stable.

<!-- test
id: @Tb80d17f5
priority: normal
creator: boris103@gmail.com
-->
# Verify Player UI Reappears During Catchup Playback

### Description:
Validate that the Player UI can be raised correctly during Catchup playback using the supported remote buttons.

### Steps:
1. Start playback of any **Catchup asset**.  
2. Wait for the **Player UI** to fade out automatically.  
3. Press **OK**, **Left**, or **Right** on the remote.

### Verifications:
- Pressing **OK**, **Left**, or **Right** causes the **Player UI to appear**.  
- Playback is **paused** only when pressing **OK**.  
- When no further action is taken, the **Player UI fades out automatically** after a few seconds.  
- **Playback resumes or continues** smoothly after the Player UI disappears.

### Expected Result:
- During Catchup playback, pressing **OK**, **Left**, or **Right** raises the Player UI (only OK pauses playback).  
- The Player UI fades out automatically after a few seconds of inactivity while playback continues normally.

<!-- test
id: @T64cbbaf6
priority: normal
creator: boris103@gmail.com
-->
# Verify Player UI Reappears When Pressing UP or DOWN on VOD

### Description:
Validate that pressing the UP or DOWN button on the remote during VOD playback displays the Player UI without pausing playback.

### Steps:
1. Start playback of any **VOD asset** (movie or series episode).  
2. Wait for the **Player UI** to fade out automatically.  
3. Press **UP** or **DOWN** on the remote.

### Verifications:
- **Player UI reappears** on top of the video.  
- **Playback continues** normally without pausing or interruptions.  
- The Player UI **fades out automatically** again after a few seconds of inactivity.  

### Expected Result:
- Pressing **UP** or **DOWN** during VOD playback displays the Player UI momentarily while the video continues to play smoothly.

<!-- test
id: @T7393ecf9
priority: normal
creator: boris103@gmail.com
-->
# Verify Player UI Fade-Out Behavior After Inactivity

### Description:
Validate that the Player UI automatically fades out after a few seconds of inactivity once it has been raised.

### Steps:
1. Start playback of any content (Live, Catchup, or VOD).  
2. Raise the **Player UI** using the appropriate remote button (OK, Left, or Right depending on content type).  
3. Do not press any other button and observe the screen.

### Verifications:
- The **Player UI remains visible** for approximately **3 seconds** after the last user interaction.  
- After 3 seconds of inactivity, the **Player UI fades out automatically**.  
- **Playback continues** smoothly during and after the fade-out.  
- The screen returns to **full-screen playback** without any UI overlays.

### Expected Result:
- The Player UI disappears automatically after a few seconds of inactivity while playback continues without interruption.
