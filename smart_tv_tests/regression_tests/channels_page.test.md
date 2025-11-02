<!-- suite
id: @S3cdfb1a6
emoji: 
-->
# Channels page



<!-- test
id: @T29ccfa64
priority: normal
creator: boris103@gmail.com
-->
# Verify Channels Page Opened

### Description:
Validate that the Channels page opens correctly and displays all five expected rails.

### Steps:
1. Open the FreeTV app.  
2. Log in to your account.  
3. Open the Channels page from the side menu.  
4. Verify the Channels page is opened.  

### Verifications:
* Channels page is opened.  
* 5 rails are visible:  
  - Israeli channels rail  
  - Sports channels rail  
  - Entertainment channels rail  
  - Kids channels rail  
  - Hearing channels rail  

### Expected Result:
* Channels page is opened successfully.  
* All 5 rails are displayed correctly.

<!-- test
id: @T60f933a6
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playing on Top Shelf When Focused

### Description:
Validate that when a channel is focused on the Channels page, it starts playing in the Top Shelf area.

### Steps:
1. Open the Channels page.  
2. Focus on any channel.  
3. Observe the Top Shelf.  

### Verifications:
* The focused channel is playing on the Top Shelf.  

### Expected Result:
* The selected channel starts playing on the Top Shelf.

<!-- test
id: @Tb67e5736
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Opened in Full Screen

### Description:
Validate that selecting a channel from the Channels page opens it in full screen.

### Steps:
1. Open the Channels page.  
2. Focus on any channel.  
3. Press OK to open the channel in full screen.  

### Verifications:
* Channel opens in full screen.  
* No latency appears.  
* Full screen opens without refreshing the player.  

### Expected Result:
* Channel opens in full screen immediately without latency or player refresh.

<!-- test
id: @T97414bed
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Opened in Full Screen Automatically on LG TV

### Description:
Validate that on LG TVs, a focused channel on the Channels page opens in full screen automatically after a few minutes.

### Prerequisite:
* Test only on LG TV.  

### Steps:
1. Open the Channels page.  
2. Focus on any channel.  
3. Wait for 10 minutes.  
4. Verify the channel is playing in full screen.  

### Verifications:
* The channel opens in full screen automatically after a few minutes.  

### Expected Result:
* After a couple of minutes, the channel plays in full screen automatically.  

### Note:
* If the test is conducted on a non-LG TV, this step should be blocked, as this functionality is only supported on LG TVs.

<!-- test
id: @T3b00a971
priority: normal
creator: boris103@gmail.com
-->
# Verify Closing Full Screen and Channel Playback on Top Shelf

### Description:
Validate that when closing a channel’s full screen view, playback continues on the Top Shelf.

### Steps:
1. Open the Channels page.  
2. Open any channel in full screen.  
3. Press the back button.  
4. Verify the full screen is closed and the channel continues playing in the Top Shelf.  

### Verifications:
* Channel is playing in the Top Shelf after exiting full screen.  

### Expected Result:
* The channel continues playing in the Top Shelf after closing full screen.

<!-- test
id: @T82c6b7bb
priority: normal
creator: boris103@gmail.com
-->
# Verify 4K Channel Playback

### Description:
Validate that a 4K channel plays correctly on the Top Shelf and in full screen.

### Prerequisite:
* TV supports 4K.  
* 4K channels: Sport 5 4K.  

### Steps:
1. Open the Channels page.  
2. Focus on the 4K channel (Sport 5 4K).  

### Verifications:
* Channel is playing on the Top Shelf when focused.  
* Channel plays in full screen when pressing OK.  

### Expected Result:
* The 4K channel plays without any issues, both on the Top Shelf and in full screen.

<!-- test
id: @Tb6ad7bba
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback from Israeli Channels Rail

### Description:
Validate that channels from the Israeli channels rail open and play successfully.

### Steps:
1. Open the Channels page.  
2. Open any channel from the Israeli channels rail.  
3. Verify the channel is playing.  

### Verifications:
* Channel from Israeli channels rail is playing.  

### Expected Result:
* Channel from Israeli channels rail opens and plays successfully.

<!-- test
id: @T4f4daa27
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback from Sports Channels Rail

### Description:
Validate that channels from the Sports channels rail open and play successfully.

### Steps:
1. Open the Channels page.  
2. Open any channel from the Sports channels rail.  
3. Verify the channel is playing.  

### Verifications:
* Channel from Sports channels rail is playing.  

### Expected Result:
* Channel from Sports channels rail opens and plays successfully.

<!-- test
id: @T875954cc
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback from Entertainment Channels Rail

### Description:
Validate that channels from the Entertainment channels rail open and play successfully.

### Steps:
1. Open the Channels page.  
2. Open any channel from the Entertainment channels rail.  
3. Verify the channel is playing.  

### Verifications:
* Channel from Entertainment channels rail is playing.  

### Expected Result:
* Channel from Entertainment channels rail opens and plays successfully.

<!-- test
id: @T2456f280
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback from Kids Channels Rail

### Description:
Validate that channels from the Kids channels rail open and play successfully.

### Steps:
1. Open the Channels page.  
2. Open any channel from the Kids channels rail.  
3. Verify the channel is playing.  

### Verifications:
* Channel from Kids channels rail is playing.  

### Expected Result:
* Channel from Kids channels rail opens and plays successfully.

<!-- test
id: @T2b708b12
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Playback from Hearing Channels Rail

### Description:
Validate that channels from the Hearing channels rail (ערוצי נגישות לשמיעה – ערוצים עם כתוביות) open and play successfully.

### Steps:
1. Open the Channels page.  
2. Open any channel from the Hearing channels rail.  
3. Verify the channel is playing.  

### Verifications:
* Channel from Hearing channels rail is playing.  

### Expected Result:
* Channel from Hearing channels rail opens and plays successfully.

<!-- test
id: @T08cb3486
priority: normal
creator: boris103@gmail.com
-->
# Verify Subtitles on Hearing Channels

### Description:
Validate that subtitles (כתוביות) are displayed during playback of channels from the Hearing channels rail.

### Steps:
1. Open the Channels page.  
2. Focus on a channel from the Hearing channels rail.  
3. Verify that subtitles appear during channel playback.  

### Verifications:
* Subtitles are displayed for the channel.  

### Expected Result:
* Subtitles appear during playback for the selected channel from the Hearing channels rail.  

### Note:
* The video quality of Hearing channels is lower compared to standard channels.  
* Subtitles are generated by live translation and may not be perfectly synchronized with the audio.

<!-- test
id: @Te118e3c5
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Metadata on Top Shelf

### Description:
Validate that channel metadata such as channel name and program details is displayed correctly on the Top Shelf when a channel is focused.

### Steps:
1. Open the Channels page.  
2. Focus on a channel from any rail.  
3. Observe the Top Shelf.  

### Verifications:
* Channel metadata is displayed on the Top Shelf (e.g., channel name, program details).  

### Expected Result:
* Channel metadata appears correctly on the Top Shelf when a channel is focused.
