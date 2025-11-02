<!-- suite
id: @Sa3125ce8
emoji: 
-->
# EPG - TV guid page



<!-- test
id: @Te1df0928
priority: normal
creator: boris103@gmail.com
-->
# Verify EPG page opened

### Description:
Validate that the EPG page opens correctly and displays all expected UI elements.

### Steps:  
1. Open the EPG page.  
2. Observe the page layout.  

### Verifications:  
* Channels column with channel logos/numbers is visible.  
* Horizontal time grid with time labels is visible.  
* Program tiles are displayed per channel row.  
* Current time indicator is visible.  
* Details panel with program title, time range, channel, and synopsis area is visible.  

### Expected Result:  
* EPG page loads successfully, displaying the channels column, time grid, program tiles, current time indicator, and details panel.

<!-- test
id: @Tf76d4b63
priority: normal
creator: boris103@gmail.com
-->
# Verify navigation in EPG page

### Description:
Validate that navigation within the EPG page works correctly across time slots and channels.

### Steps:  
1. Open the EPG page.  
2. Navigate horizontally across the time grid.  
3. Navigate vertically through the channel list.  

### Verifications:  
* Horizontal navigation moves the focus between program tiles across different time slots.  
* Vertical navigation moves the focus between program tiles for different channels.  
* Navigation wraps correctly at the start/end of rows without skipping programs.  
* Current time indicator remains aligned with the correct position when returning to the current time slot.  

### Expected Result:  
* User can navigate horizontally between programs and vertically between channels in the EPG page smoothly, without skipping or losing focus, and the current time indicator remains correctly positioned.

<!-- test
id: @T86f517ce
priority: normal
creator: boris103@gmail.com
-->
# Verify Opening of Past Programs from EPG

### Description:
Validate that selecting a past program from the EPG opens its details or playback screen with correct information.

### Steps:  
1. Open the EPG page.  
2. Navigate to a program tile that has already aired.  
3. Press OK to open the program.  

### Verifications:  
* The selected past program opens its details or playback screen.  
* Program information matches the tile selected in the EPG (title, channel, time range, synopsis).  

### Expected Result:  
* Selecting a past program from the EPG successfully opens its details or playback screen with matching program information.  

### Note:  
* Playback may begin with the ending of the previous program if there was an overlap or schedule shift before the selected program started.

<!-- test
id: @T6b42bc3a
priority: normal
creator: boris103@gmail.com
-->
# Verify Opening of Live Programs from EPG

### Description:
Validate that selecting a live program from the EPG opens its playback screen with correct information and live broadcast.

### Steps:  
1. Open the EPG page.  
2. Navigate to a program tile that is currently airing (Live).  
3. Press OK to open the program.  

### Verifications:  
* The selected live program opens its playback screen.  
* Program information matches the tile selected in the EPG (title, channel, time range, synopsis).  
* Live indicator/tag is displayed in the EPG and in the playback screen.  

### Expected Result:  
* Selecting a live program from the EPG successfully opens its playback screen with matching program information and the live broadcast playing.

<!-- test
id: @Tc0c034b8
priority: normal
creator: boris103@gmail.com
-->
# Verify Opening of Past Program from Sport5 4K Channel in EPG

### Description:
Validate that selecting a past program from the Sport5 4K channel in the EPG opens its details or playback screen with correct information and 4K labeling.

### Steps:  
1. Open the EPG page.  
2. Navigate to the **Sport5 4K** channel row in the Sports Channels rail.  
3. Navigate to a program tile that has already aired.  
4. Press OK to open the program.  

### Verifications:  
* The selected past program from the **Sport5 4K** channel opens its details or playback screen.  
* Program information matches the tile selected in the EPG (title, channel, time range, synopsis).  
* 4K label is visible for the channel or program in the EPG and in the playback/details screen.  

### Expected Result:  
* Selecting a past program from the **Sport5 4K** channel in the EPG successfully opens its details or playback screen with matching program information, and the 4K label is displayed where applicable.  

### Note:  
* Playback may begin with the ending of the previous program if there was an overlap or schedule shift before the selected program started.

<!-- test
id: @T414fc577
priority: normal
creator: boris103@gmail.com
-->
# Verify Opening of Live Program from Sport5 4K Channel in EPG

### Description:
Validate that selecting a live program from the Sport5 4K channel in the EPG opens its playback screen with correct information, 4K labeling, and live broadcast.

### Steps:  
1. Open the EPG page.  
2. Navigate to the **Sport5 4K** channel row in the Sports Channels rail.  
3. Navigate to a program tile that is currently airing (Live).  
4. Press OK to open the program.  

### Verifications:  
* The selected live program from the **Sport5 4K** channel opens its playback screen.  
* Program information matches the tile selected in the EPG (title, channel, time range, synopsis).  
* 4K label is visible for the channel or program in the EPG and in the playback screen.  
* Live indicator/tag is displayed in the EPG and in the playback screen.  

### Expected Result:  
* Selecting a live program from the **Sport5 4K** channel in the EPG successfully opens its playback screen with matching program information, and both the 4K label and Live indicator are displayed where applicable.

<!-- test
id: @T578e0286
priority: normal
creator: boris103@gmail.com
-->
# Verify Metadata Information Appearance in EPG

### Description:
Validate that focusing on a program tile in the EPG displays the complete and correct metadata information panel.

### Steps:  
1. Open the EPG page.  
2. Navigate to any program tile (past, live, or future).  
3. Focus on the program tile and observe the metadata information panel.  

### Verifications:  
* Program title is visible.  
* Channel number and name are displayed.  
* Time range (start–end) is visible and correct.  
* Synopsis is present and not empty.  
* Tags (e.g., Live, TV program, 4K) appear when applicable.  

### Expected Result:  
* When focusing on a program tile in the EPG, the metadata information panel displays complete and correct details for the selected program, including title, channel, time range, synopsis, and any applicable tags.

<!-- test
id: @T8ceed68e
priority: normal
creator: boris103@gmail.com
-->
# Verify Future Program Metadata Display in EPG

### Description:
Validate that selecting a future program in the EPG shows its metadata details without starting playback.

### Steps:  
1. Open the EPG page.  
2. Navigate to a program tile scheduled for a future time.  
3. Press OK to open the program.  

### Verifications:  
* No playback starts for future programs.  
* Program title is visible in the details panel.  
* Channel number and name are displayed in the details panel.  
* Time range (start–end) is visible and correct.  
* Synopsis is present and not empty.  
* If available, tags (e.g., TV program, 4K, Live) are displayed in the details panel.  

### Expected Result:  
* Pressing OK on a future program tile in the EPG does not start playback but displays complete and correct metadata in the details panel.

<!-- test
id: @Ta3f65d04
priority: normal
creator: boris103@gmail.com
-->
# Verify Accuracy of Current Time Green Line in EPG

### Description:
Validate that the green current time indicator line in the EPG is visible and accurately reflects the current time.

### Steps:  
1. Open the EPG page.  
2. Identify the green current time indicator line on the grid.  
3. Check its position relative to the time labels and program tiles.  

### Verifications:  
* Green current time line is visible on the EPG grid.  
* Line position aligns accurately with the current time shown on the time labels.  
* The program tile intersected by the line is the currently airing program for that channel.  

### Expected Result:  
* The green current time line is visible, correctly positioned according to the actual time, and intersects the program that is currently airing.

<!-- test
id: @Tc6ed49d4
priority: normal
creator: boris103@gmail.com
-->
# Verify Channels Logo in EPG

### Description:
Validate that the channel logos in the EPG are displayed correctly, clearly, and match their corresponding channels.

### Steps:  
1. Open the EPG page.  
2. Observe the channel list on the left side of the grid.  

### Verifications:  
* Each channel row displays its correct logo.  
* Logos are clear, not distorted, and fully visible.  
* Logos match the correct channel number and name.  

### Expected Result:  
* All channels in the EPG display their correct, clear, and undistorted logos, matching the corresponding channel number and name.

<!-- test
id: @T2ad886af
priority: normal
creator: boris103@gmail.com
-->
# Verify Vertical Navigation Does Not Cycle in EPG

### Description:
Validate that vertical navigation in the EPG stops at the first and last channel rows without cycling.

### Steps:  
1. Open the EPG page.  
2. Navigate to the first channel row at the top of the list.  
3. Press the Up button on the remote.  
4. Navigate to the last channel row at the bottom of the list.  
5. Press the Down button on the remote.  

### Verifications:  
* Pressing Up on the first channel row does not move focus to the last channel row.  
* Pressing Down on the last channel row does not move focus to the first channel row.  

### Expected Result:  
* Vertical navigation in the EPG stops at the first and last channel rows without cycling to the opposite end of the list.

<!-- test
id: @T6604a689
priority: normal
creator: boris103@gmail.com
-->
# Verify Program Order and Absence of Gaps/Overlaps in Channel Row

### Description:
Validate that program tiles in a channel row are displayed in chronological order without gaps or overlaps.

### Steps:
1. Open the EPG page.  
2. Pick any single channel row.  
3. Read the start–end times of the first three visible program tiles.  
4. Scroll horizontally and read the start–end times of the next three program tiles for the same channel.  

### Verifications:
* Program tiles are ordered chronologically by start time.  
* There are no overlaps between consecutive tiles (`end_time ≤ next_start_time`).  
* There are no unintended gaps between consecutive tiles (preferably `end_time = next_start_time`, unless small gaps are expected by design).  
* For very short programs, the title may appear cut due to tile size but must still be correctly placed in order.  

### Expected Result:
* Programs in the selected channel row are displayed in chronological order with no overlaps and no unintended gaps across the visible timeline.  
* Short programs are still positioned correctly even if their titles appear cut.

<!-- test
id: @T8739c42e
priority: normal
creator: boris103@gmail.com
-->
# Verify EPG Program Info Loading During Navigation

### Description:
Validate that navigating within the EPG may temporarily show skeleton/loading states before metadata fully loads.

### Steps:  
1. Open the EPG page.  
2. Navigate between program tiles in any direction (up, down, left, right).  
3. Observe the program info/details panel during navigation.  

### Verifications:  
* Skeleton or placeholder may briefly appear while new program details are loading.  
* After loading, the correct program metadata (title, time range, channel, synopsis, tags) is displayed.  
* Navigation continues to work without freezes or crashes.  

### Expected Result:  
* Program details load correctly after navigation, even if a temporary skeleton or placeholder appears.  

### Note:  
* Do not raise issues for skeleton appearance or slight delays during navigation — this is expected behavior due to heavy data in the EPG.
