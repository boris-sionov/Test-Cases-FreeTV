<!-- suite
id: @S68c63267
emoji: 
-->
# Clock



<!-- test
id: @T43901af2
priority: normal
creator: boris103@gmail.com
-->
# Verify Clock Display On Live Channel

### Description:
Validate that the clock appears in the Zapper during live channel playback and displays the correct Israel local time.

### Steps:
1. Open any **Live channel** and start playback.  
2. Raise the **Zapper**.  
3. Observe the clock displayed in the top-left corner.  

### Verifications:
- The **clock** is visible on the top-left corner of the Zapper.  
- The displayed time matches the **current Israel local time** (IL time).  

### Expected Result:
- When opening the Zapper on a live channel, the clock appears correctly and shows the current IL time.

<!-- test
id: @T3036375f
priority: normal
creator: boris103@gmail.com
-->
# Verify Clock Display On Catchup Event

### Description:
Validate that the clock appears in the Zapper during catchup event playback and displays the correct Israel local time.

### Steps:
1. Open any **Catchup event** and start playback.  
2. Raise the **Zapper**.  
3. Observe the clock displayed in the top-left corner.  

### Verifications:
- The **clock** is visible on the top-left corner of the Zapper.  
- The displayed time matches the **current Israel local time** (IL time).  

### Expected Result:
- When opening the Zapper on a catchup event, the clock appears correctly and shows the current IL time.

<!-- test
id: @T37c3745a
priority: normal
creator: boris103@gmail.com
-->
# Verify Clock Does Not Appear During VOD Playback

### Description:
Validate that during playback of a VOD movie or episode, the clock appears on the player UI and shows the correct Israel local time.

### Steps:
1. Open any **VOD movie** or **VOD series episode**.  
2. Start playback.  
3. Wait until the **player UI** fades out.  
4. Press the **OK** button to reopen the **player UI**.  
5. Observe the clock displayed on the screen.  

### Verifications:
- The **clock** is visible on the **top-left corner** of the player UI.  
- The clock shows the **current Israel local time (IL time)**.  
- The time is displayed in **24-hour format (HH:MM)**.  
- The clock remains visible while the player UI is active and disappears once the UI fades.  

### Expected Result:
- The clock appears correctly during VOD playback, showing the current Israel local time while the player UI is visible.
