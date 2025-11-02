<!-- suite
id: @Sf0e4a93b
emoji: 
-->
# Zapper



<!-- test
id: @Te9902b45
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Trigger During Live Event Playback

### Description:
Validate that the Zapper is triggered instantly with no latency or animation when pressing UP or DOWN during live event playback.

### Steps:
1. Open any **Live TV channel** and start playback.  
2. Wait until the player UI fades out.  
3. Press the **UP** or **DOWN** button on the remote control (RCU).  

### Verifications:
- The **Zapper** appears immediately with **no latency**, **no animation**, and **no spinner**.  
- The Zapper raises **instantly** (zero delay) even on **low-tier devices**.  

### Expected Result:
- The Zapper is raised instantly during live event playback with no visible delay or animation.

<!-- test
id: @T0982d52d
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Trigger During Catchup Event Playback

### Description:
Validate that the Zapper is triggered instantly when pressing UP or DOWN during catchup event playback.

### Steps:
1. Open any **Catchup event** and start playback.  
2. Wait until the player UI fades out.  
3. Press the **UP** or **DOWN** button on the remote control (RCU).  

### Verifications:
- The **Zapper** appears instantly with no latency, animation, or spinner.  
- The Zapper raises immediately (zero delay), showing the current catchup event information.  

### Expected Result:
- The Zapper is raised instantly during catchup event playback with no delay or animation.

<!-- test
id: @T1c2b82e4
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Trigger Using CH± Buttons

### Description:
Validate that pressing the CH± button raises the Zapper instantly and focuses on the next or previous channel.

### Steps:
1. Open any **Live** or **Catchup** event and start playback.  
2. Press the **CH±** button on the remote control.  
3. Observe the Zapper behavior.  

### Verifications:
- The **Zapper** appears immediately with no latency, animation, or spinner.  
- Focus moves to the **next channel** when pressing **CH+** or to the **previous channel** when pressing **CH–**.  
- The currently focused channel is visually highlighted in the Zapper carousel.  

### Expected Result:
- The Zapper is raised instantly when pressing CH± and correctly focuses on the next or previous channel.

<!-- test
id: @T732f39cc
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Switch After Delay When Using CH± Buttons

### Description:
Validate that when the Zapper is raised using CH±, the player automatically switches to the newly focused channel after 5 seconds of inactivity.

### Steps:
1. Open any **Live** or **Catchup** event and start playback.  
2. Press the **CH±** button once to raise the Zapper.  
3. Do not perform any further action.  
4. Wait for **5 seconds** and observe playback behavior.  

### Verifications:
- The Zapper remains visible during the 5-second period.  
- After **5 seconds**, the player automatically switches playback to the newly focused channel.

### Expected Result:
- When raising the Zapper with CH±, playback automatically switches to the focused channel after 5 seconds of inactivity.

<!-- test
id: @T57878ec9
priority: normal
creator: boris103@gmail.com
-->
# Verify Focus Change Behavior When Repeatedly Pressing CH± Buttons

### Description:
Validate that pressing the CH± buttons repeatedly while the Zapper is raised changes the focus between channels without triggering immediate playback.

### Steps:
1. Open any **Live** or **Catchup** event and start playback.  
2. Press **CH±** once to raise the Zapper.  
3. Before 5 seconds pass, press **CH±** again several times.  
4. Observe the focus and playback behavior.  

### Verifications:
- Each press updates the focus to the next or previous channel in the Zapper carousel.  
- Playback does **not** change while navigating between channels.  
- The Zapper remains open and responsive during navigation.  

### Expected Result:
- Repeated presses of CH± only move the channel focus within the Zapper without changing playback until the 5-second timeout or user confirmation.

<!-- test
id: @Tbdf7300f
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback Behavior After Pressing CH± Followed By UP/DOWN

### Description:
Validate that when pressing the CH± buttons several times and then pressing the UP or DOWN button, playback starts from the last focused channel before pressing UP/DOWN.

### Steps:
1. Open any **Live** or **Catchup** event and start playback.  
2. Press the **CH±** buttons several times to navigate between channels in the Zapper.  
3. Do not wait 5 seconds for auto-switch.  
4. Press the **UP** or **DOWN** button on the remote control.  

### Verifications:
- The Zapper remains open and responsive during CH± navigation.  
- After pressing **UP** or **DOWN**, playback starts from the **last focused channel** (the one highlighted before pressing UP/DOWN).  
- No intermediate channels start playing during the CH± navigation.  

### Expected Result:
- When pressing CH± multiple times and then UP/DOWN, playback begins from the last channel that was focused before the UP/DOWN input.

<!-- test
id: @Ted6d9bb6
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Trigger From Channels Button During Live Event

### Description:
Validate that the Zapper is triggered instantly from the Channels (ערוצים) button in the Player UI during a live event.

### Steps:
1. Open any **Live TV** event and start playback.  
2. Press **OK** on the remote to raise the **Player UI**.  
3. Navigate to the **Channels (ערוצים)** button.  
4. Press **OK** to open the Zapper.  

### Verifications:
- The Zapper appears instantly with **no latency**, **no animation**, and **no spinner**.  
- The Zapper displays the **current live event** program information.  
- The Player UI fades out automatically once the Zapper appears.  

### Expected Result:
- When the Channels button is selected from the Player UI during a live event, the Zapper appears instantly showing the current live program.

<!-- test
id: @T83b24373
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Trigger From Channels Button During Catchup Event

### Description:
Validate that the Zapper is triggered instantly from the Channels (ערוצים) button in the Player UI during a catchup event.

### Steps:
1. Open any **Catchup** event and start playback.  
2. Press **OK** on the remote to raise the **Player UI**.  
3. Navigate to the **Channels (ערוצים)** button.  
4. Press **OK** to open the Zapper.  

### Verifications:
- The Zapper appears instantly with **no latency**, **no animation**, and **no spinner**.  
- The Zapper displays the **current catchup** program information.  
- The Player UI fades out automatically once the Zapper appears.  

### Expected Result:
- When the Channels button is selected from the Player UI during a catchup event, the Zapper appears instantly showing the current catchup program.

<!-- test
id: @T9f25bb78
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Fade-Out After Inactivity

### Description:
Validate that the Zapper automatically fades out after 10 seconds of inactivity.

### Steps:
1. Open any **Live** or **Catchup** event and start playback.  
2. Raise the **Zapper** using any supported method.
3. Do not perform any additional actions.  
4. Wait for **10 seconds**.  

### Verifications:
- The Zapper remains visible during the inactivity period.  
- After **10 seconds**, the Zapper automatically fades out.  
- Playback continues seamlessly in the background.  
- No user interaction is required for the Zapper to fade.  

### Expected Result:
- The Zapper automatically fades out after 10 seconds of inactivity while playback continues normally.

<!-- test
id: @Tc4aaa5ad
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Close Using Back Button

### Description:
Validate that pressing the Back button on the remote closes the Zapper instantly and returns to full-screen playback.

### Steps:
1. Open any **Live** or **Catchup** event and start playback.  
2. Raise the **Zapper** using any supported method.
3. Press the **Back** button on the remote control.  

### Verifications:
- The Zapper closes immediately when the **Back** button is pressed.  
- Playback continues in full-screen mode without interruption.  
- No delay, animation, or spinner occurs during the closing action.  

### Expected Result:
- Pressing the Back button instantly closes the Zapper and returns to smooth, uninterrupted full-screen playback.

<!-- test
id: @T8266e2ab
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Navigation Inside Zapper Using UP/DOWN Buttons

### Description:
Validate that pressing UP or DOWN while the Zapper is open navigates between channels without changing the current playback.

### Steps:
1. While the **Zapper** is open, press the **UP** or **DOWN** button on the remote control.  
2. Observe the channel list and info bar updates.  

### Verifications:
- Pressing **UP** moves focus to the **next channel**, and pressing **DOWN** moves to the **previous channel**.  
- The **channel logo** and **program metadata** update according to the focused channel.  
- **Playback does not change** while browsing between channels.  
- Navigation is smooth with no delay, spinner, or animation.  

### Expected Result:
- The user can browse between channels inside the Zapper using UP and DOWN without interrupting current playback.

<!-- test
id: @T6574a530
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Navigation Inside Zapper Using Long Press On UP/DOWN Buttons

### Description:
Validate that long-pressing the UP or DOWN button scrolls continuously through the channel list inside the Zapper without changing playback.

### Steps:
1. While the **Zapper** is open, **long-press** the **UP** or **DOWN** button on the remote control.  
2. Observe how the focus moves between channels.  

### Verifications:
- Long-pressing **UP** scrolls continuously through higher channels.  
- Long-pressing **DOWN** scrolls continuously through lower channels.  
- The **channel logo** and **program metadata** update dynamically as focus changes.  
- **Playback does not change** during long-press scrolling.  
- Scrolling stops immediately once the button is released.  
- Navigation is smooth with no lag, spinner, or animation.  

### Expected Result:
- Long-pressing UP or DOWN scrolls smoothly through the channel list in the Zapper without interrupting playback and stops immediately when released.

<!-- test
id: @T76592576
priority: normal
creator: boris103@gmail.com
-->
# Verify Program Navigation Inside Zapper Using LEFT/RIGHT Buttons

### Description:
Validate that pressing the LEFT or RIGHT button while the Zapper is open navigates between past and upcoming programs of the focused channel without changing playback.

### Steps:
1. While the **Zapper** is open, press the **LEFT** or **RIGHT** button on the remote control.  

### Verifications:
- Pressing **LEFT** navigates to **future programs** (up to 48 hours ahead).  
- Pressing **RIGHT** navigates to **past programs** (up to 1 week back).  
- The program details update according to the selected program.  
- **Playback does not change** while navigating between programs.  

### Expected Result:
- LEFT and RIGHT navigation inside the Zapper switches between past and future programs of the focused channel without affecting playback.

<!-- test
id: @Tec55c375
priority: normal
creator: boris103@gmail.com
-->
# Verify Program Navigation Inside Zapper Using Long Press On LEFT/RIGHT Buttons

### Description:
Validate that long-pressing the LEFT or RIGHT button scrolls continuously between past and upcoming programs of the focused channel without changing playback.

### Steps:
1. While the **Zapper** is open, **long-press** the **LEFT** or **RIGHT** button on the remote control.  

### Verifications:
- Long-pressing **LEFT** scrolls continuously through **future programs** (up to 48 hours ahead).  
- Long-pressing **RIGHT** scrolls continuously through **past programs** (up to 1 week back).  
- Program details update dynamically as focus moves between programs.  
- **Playback does not change** during long-press scrolling.  
- Scrolling stops immediately when the button is released.  

### Expected Result:
- Long-pressing LEFT or RIGHT scrolls smoothly between past and future programs of the focused channel, and playback remains unchanged.

<!-- test
id: @T25786d62
priority: normal
creator: boris103@gmail.com
-->
# Verify No Action When Pressing OK On Current Live Channel

### Description:
Validate that pressing OK on the current live channel does not trigger any action or playback change.

### Steps:
1. While the **Zapper** is open, focus on the **current live channel**.  
2. Press the **OK** button on the remote control.  

### Verifications:
- Playback continues on the same channel with no change.  
- No loading, switching, or interruption occurs.  

### Expected Result:
- Pressing OK on the current live channel performs no action other than closing the Zapper.

<!-- test
id: @T17156f69
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback Starts When Pressing OK On Past Show Of Current Channel

### Description:
Validate that pressing OK on a past program from the current channel starts playback of that catchup event.

### Steps:
1. While the **Zapper** is open, focus on a **past program** from the **current channel**.  
2. Press the **OK** button on the remote control.  

### Verifications:
- The selected **catchup event** starts playing from the beginning.  
- Playback switches seamlessly to the selected program.

### Expected Result:
- Pressing OK on a past program of the current channel starts playback of that catchup event and closes the Zapper.

<!-- test
id: @T842b4757
priority: normal
creator: boris103@gmail.com
-->
# Verify No Action When Pressing OK On Future Program Of Current Channel

### Description:
Validate that pressing OK on a future program of the current channel does not start playback or trigger any action.

### Steps:
1. While the **Zapper** is open, focus on a **future program** of the **current channel**.  
2. Press the **OK** button on the remote control.  

### Verifications:
- No playback starts for the future program.  
- The current live playback continues without interruption.  
- The Zapper remains open until closed manually or fades out automatically.  

### Expected Result:
- Pressing OK on a future program of the current channel does nothing; the current live playback continues as normal.

<!-- test
id: @T9704eb5f
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Change When Pressing OK On Live Program Of Any Other Channel

### Description:
Validate that pressing OK on a live program from any other channel switches playback to that channel.

### Steps:
1. While the **Zapper** is open, navigate to **any other channel** that is currently airing a live program.  
2. Press the **OK** button on the remote control.  

### Verifications:
- The current playback stops immediately.  
- Playback switches to the selected live channel.  

### Expected Result:
- Pressing OK on a live program of any other channel switches playback to that channel and closes the Zapper automatically.

<!-- test
id: @T9dcd17a4
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback Starts When Pressing OK On Past Program Of Any Other Channel

### Description:
Validate that pressing OK on a past program from any other channel starts playback of that catchup event.

### Steps:
1. While the **Zapper** is open, navigate to **any other channel**.  
2. Focus on a **past program** in that channel’s timeline.  
3. Press the **OK** button on the remote control.  

### Verifications:
- The selected catchup program starts playing from the beginning.  
- Playback switches to the selected channel and program.  

### Expected Result:
- Pressing OK on a past program of any other channel starts playback of that catchup event.

<!-- test
id: @T0bc18e55
priority: normal
creator: boris103@gmail.com
-->
# Verify No Action When Pressing OK On Future Program Of Any Other Channel

### Description:
Validate that pressing OK on a future program from any other channel does not start playback or trigger any action.

### Steps:
1. While the **Zapper** is open, navigate to **any other channel**.  
2. Focus on a **future program** in that channel’s timeline.  
3. Press the **OK** button on the remote control.  

### Verifications:
- No playback starts for the future program.  
- The current playback continues without interruption.  
- The Zapper remains open until closed manually or fades out automatically.  

### Expected Result:
- Pressing OK on a future program of any other channel performs no action and keeps the current playback running.

<!-- test
id: @T730e547b
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Is Not Raised During VOD Playback

### Description:
Validate that the Zapper cannot be triggered while watching any VOD movie or episode, since it is disabled during VOD playback.

### Steps:
1. Open any **VOD movie** or **VOD series episode**.  
2. Start playback and wait until the player UI fades out.  
3. Press the **UP** and **DOWN** buttons on the remote control.  
4. Observe the screen.  

### Verifications:
- Pressing **UP** or **DOWN** does **not** raise the Zapper.  
- Instead, the **Player UI** appears with the standard playback controls.  
- No channel metadata, carousel, or info bar is displayed.  

### Expected Result:
- The Zapper does not appear during VOD playback; pressing UP or DOWN only brings up the Player UI.
