<!-- suite
id: @Sae057f96
emoji: 
-->
# Navigation



<!-- test
id: @T4c48a71f
priority: normal
creator: boris103@gmail.com
-->
# Verify Horizontal Navigation on Main Page

### Description:
Validate that horizontal navigation using the remote works smoothly across the Main page.

### Steps:
1. Open the FreeTV app.  
2. Open the Main page.  
3. Navigate horizontally using the remote (left/right).  

### Verifications:
* Horizontal navigation works smoothly without issues.  

### Expected Result:
* Horizontal navigation works without issues.

<!-- test
id: @Tcaa75170
priority: normal
creator: boris103@gmail.com
-->
# Verify Vertical Navigation on Main Page

### Description:
Validate that vertical navigation using the remote works smoothly across the Main page.

### Steps:
1. Open the FreeTV app.  
2. Open the Main page.  
3. Navigate vertically using the remote (up/down).  

### Verifications:
* Vertical navigation works smoothly without issues.  

### Expected Result:
* Vertical navigation works without issues.

<!-- test
id: @Te588223b
priority: normal
creator: boris103@gmail.com
-->
# Verify Single Click Functionality on Main Page

### Description:
Validate that a single click on the remote selects an item on the Main page and moves it into focus.

### Steps:
1. Open the FreeTV app.  
2. Open the Main page.  
3. Perform a single click using the remote.  

### Verifications:
* Single click action works as expected.  

### Expected Result:
* The selected card/item moves into focus.

<!-- test
id: @Tc3f8b0a7
priority: normal
creator: boris103@gmail.com
-->
# Verify Long Click Functionality on Main Page

### Description:
Validate that a long click on the remote functions correctly on the Main page, allowing continuous navigation while the button is pressed.

### Steps:
1. Open the FreeTV app.  
2. Open the Main page.  
3. Perform a long click using the remote.  

### Verifications:
* Long click action works as expected – navigation works while pressing the button.  

### Expected Result:
* Long click works as intended.

<!-- test
id: @Tf8f4b1cc
priority: normal
creator: boris103@gmail.com
-->
# Verify Navigation on Channels Page

### Description:
Validate that both horizontal and vertical navigation using the remote works smoothly on the Channels page.

### Steps:
1. Open the FreeTV app.  
2. Open the Channels page.  
3. Navigate horizontally and vertically using the remote.  

### Verifications:
* Navigation (horizontal and vertical) works smoothly on the Channels page.  

### Expected Result:
* Navigation on the Channels page works without any issues.

<!-- test
id: @T3ea45b8f
priority: normal
creator: boris103@gmail.com
-->
# Verify Navigation on Catchup Page

### Description:
Validate that both horizontal and vertical navigation using the remote works smoothly on the Catchup page.

### Steps:
1. Open the FreeTV app.  
2. Open the Catchup page.  
3. Navigate horizontally and vertically using the remote.  

### Verifications:
* Navigation (horizontal and vertical) works smoothly on the Catchup page.  

### Expected Result:
* Navigation on the Catchup page works without any issues.

<!-- test
id: @Tc7d7127d
priority: normal
creator: boris103@gmail.com
-->
# Verify Navigation on EPG Page

### Description:
Validate that both horizontal and vertical navigation using the remote works correctly on the EPG page, even if navigation speed is slower.

### Steps:
1. Open the FreeTV app.  
2. Open the EPG page.  
3. Navigate horizontally and vertically using the remote.  

### Verifications:
* Navigation (horizontal and vertical) works on the EPG page, though it may be slow.  

### Expected Result:
* Navigation on the EPG page works without any functional issues.  
* **Note**: EPG navigation is slow.

<!-- test
id: @T2251a1db
priority: normal
creator: boris103@gmail.com
-->
# Verify Navigation on Movies Page

### Description:
Validate that both horizontal and vertical navigation using the remote works smoothly on the Movies page.

### Steps:
1. Open the FreeTV app.  
2. Open the Movies page.  
3. Navigate horizontally and vertically using the remote.  

### Verifications:
* Navigation (horizontal and vertical) works smoothly on the Movies page.  

### Expected Result:
* Navigation on the Movies page works without any issues.

<!-- test
id: @T75fda2a8
priority: normal
creator: boris103@gmail.com
-->
# Verify Navigation on Series Page

### Description:
Validate that both horizontal and vertical navigation using the remote works smoothly on the Series page.

### Steps:
1. Open the FreeTV app.  
2. Open the Series page.  
3. Navigate horizontally and vertically using the remote.  

### Verifications:
* Navigation (horizontal and vertical) works smoothly on the Series page.  

### Expected Result:
* Navigation on the Series page works without any issues.

<!-- test
id: @T3a105cb7
priority: normal
creator: boris103@gmail.com
-->
# Verify Navigation on Sports Page

### Description:
Validate that both horizontal and vertical navigation using the remote works smoothly on the Series page.

### Steps:
1. Open the FreeTV app.  
2. Open the Series page.  
3. Navigate horizontally and vertically using the remote.  

### Verifications:
* Navigation (horizontal and vertical) works smoothly on the Series page.  

### Expected Result:
* Navigation on the Series page works without any issues.

<!-- test
id: @T1ba2b5bc
priority: normal
creator: boris103@gmail.com
-->
# Verify Navigation on Kids Page

### Description:
Validate that both horizontal and vertical navigation using the remote works smoothly on the Kids page.

### Steps:
1. Open the FreeTV app.  
2. Open the Kids page.  
3. Navigate horizontally and vertically using the remote.  

### Verifications:
* Navigation (horizontal and vertical) works smoothly on the Kids page.  

### Expected Result:
* Navigation on the Kids page works without any issues.

<!-- test
id: @Ta5380453
priority: normal
creator: boris103@gmail.com
-->
# Verify Focus Behavior on Last Rail

### Description:
Validate that when navigating to the last rail on any page, pressing the down button does not move focus or cause unintended scrolling.

### Steps:
1. Open any page.  
2. Navigate down to the last rail.  
3. Press the down navigation button once.  

### Verifications:
* Focus remains on the last rail after pressing down.  
* No unintended scrolling or focus changes occur.  

### Expected Result:
* Pressing down when already on the last rail does not change focus or scroll the page.

<!-- test
id: @Tc8ea7e0d
priority: normal
creator: boris103@gmail.com
-->
# Verify Focus Behavior on Last Card in Rail

### Description:
Validate that when navigating to the first card on the left side of any rail, pressing the left button does not move focus, and this behavior is consistent across Channel and VOD rails.

### Steps:
1. Open any page.  
2. Navigate through a rail to the last card on the left side.  
3. Press the left navigation button again.  
4. Repeat the test for both Channel rails and VOD rails.  

### Verifications:
* Focus remains on the last card when pressing left at the end of the rail.  
* Behavior is consistent for both Channel rails and VOD rails.  

### Expected Result:
* Pressing left when already on the last card does not change focus in any rail type.

<!-- test
id: @Tb8bc5591
priority: normal
creator: boris103@gmail.com
-->
# Verify Pressing Right from First Card in Rail Opens Side Menu

### Steps:
1. Open the main page.
2. Focus on the first card in any rail.
3. Press the right navigation button.

### Verifications:
* Side menu opens.
* Focus appears on the main menu within the side menu.
* Rail navigation is paused while the side menu is open.

### Expected Result:
* Pressing right from the first card in a rail opens the side menu and sets focus on the main menu inside it.

<!-- test
id: @T7e9ec9b4
priority: normal
creator: boris103@gmail.com
-->
# Verify Focus Switch Updates Top Shelf

### Description:
Validate that switching focus between live channel cards updates the Top Shelf playback and metadata.

### Steps:
1. Open the app.  
2. Navigate to any page that contains live channel rails (e.g., Channels, Sports, Catchup).  
3. Focus on any live channel card.  
4. Observe the Top Shelf.  
5. Move focus to a different live channel card.  
6. Observe the Top Shelf again.  

### Verifications:
- The Top Shelf updates to play the newly focused channel.  
- Video and audio switch smoothly without errors.  
- Metadata (program title, channel name, broadcast time, type, and synopsis) updates to match the newly focused channel.  

### Expected Result:
- The Top Shelf always updates correctly to the currently focused channel, with smooth playback and accurate metadata.
