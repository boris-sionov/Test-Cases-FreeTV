<!-- suite
id: @Se78bab9e
emoji: 
-->
# Catchup page



<!-- test
id: @T3d8c96d5
priority: normal
creator: boris103@gmail.com
-->
# Verify Catchup Page Opened

### Description:
Validate that the Catchup page opens correctly and displays all four expected rails.

### Steps:
1. Open the FreeTV app.  
2. Log in to your account.  
3. Open the side menu.  
4. Select the **Catchup** option.  

### Verifications:
* Catchup page is displayed successfully.  
* The following 4 rails are visible:  
  - Catchup All Channels  
  - Sports Channels Catchup  
  - All News Rail  
  - Catchup - The Best  

### Expected Result:
* Catchup page is opened successfully.  
* All 4 rails are displayed and labeled correctly.

<!-- test
id: @Tdc9b3e22
priority: normal
creator: boris103@gmail.com
-->
# Verify Top Shelf Metadata for Catchup Program

### Description:
Validate that the Top Shelf displays complete metadata when focusing on a catchup program.

### Steps:
1. Navigate to the page containing the Top Shelf.  
2. Focus on any catchup program.  
3. Observe the metadata displayed.  

### Verifications:
* **Mandatory fields:**  
  - Program name is shown.  
  - Channel number and name are visible.  
  - Date of the transaction is displayed.  
  - TV program tag is visible.  
  - Poster of the program is displayed.  
  - Synopsis is present and not empty.  

* **Optional fields (if available):**  
  - Age restriction is visible and matches the format (e.g., `8+`).  

### Expected Result:
* Top Shelf metadata for the focused catchup program displays all mandatory elements: program name, channel number/name, date of the transaction, TV program tag, poster, and synopsis.  
* Optional metadata (age restriction) appears when available.

<!-- test
id: @T6b9a974a
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Catchup Page from Catchup All Channels Rail

### Description:
Validate that opening a channel from the Catchup All Channels rail displays the correct channel catchup page with 14 daily rails.

### Steps:
1. Open the Catchup page.  
2. Focus on any channel in the **Catchup All Channels** rail.  
3. Open the selected channel.  

### Verifications:
* The channel catchup page opens with 14 rails.  
* Each rail corresponds to a specific day from the past 13 days, with programs listed for each day.  

### Expected Result:
* The channel catchup page opens and displays 14 rails, each representing programs from a specific day within the last two weeks.

<!-- test
id: @T514f6692
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Catchup Page from Sports Channels Rail

### Description:
Validate that opening a channel from the Sports Channels rail displays the correct channel catchup page with 14 daily rails.

### Steps:
1. Open the Catchup page.  
2. Focus on any channel in the **Sports Channels rail**.  
3. Open the selected channel.  

### Verifications:
* The channel catchup page opens with 14 rails.  
* Each rail corresponds to a specific day from the past 13 days, with programs listed for each day.  

### Expected Result:
* The channel catchup page opens and displays 14 rails, each representing programs from a specific day within the last two weeks.

<!-- test
id: @T8a5047d6
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Catchup Event Playback from All News Rail

### Description:
Validate that selecting a program from the All News Rail opens the catchup event page and starts playback.

### Steps:
1. Open the Catchup page.  
2. Focus on any program in the **All News Rail**.  
3. Open the selected catchup event.  

### Verifications:
* The channel catchup event page opens successfully.  
* The selected news program starts playing.  

### Expected Result:
* The channel catchup event page opens, and the selected news program plays without issues.

<!-- test
id: @T1510c794
priority: normal
creator: boris103@gmail.com
-->
# Verify Channel Catchup Event Playback from Catchup - The Best Rail

### Description:
Validate that selecting a program from the Catchup - The Best Rail opens the catchup event page and starts playback.

### Steps:
1. Open the Catchup page.  
2. Focus on any program in the **Catchup - The Best Rail**.  
3. Open the selected catchup event.  

### Verifications:
* The channel catchup event page opens successfully.  
* The selected program starts playing.  

### Expected Result:
* The channel catchup event page opens, and the selected program plays without issues.

<!-- test
id: @T85750da3
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback of First Available Program from 13 Days Ago in Catchup All Channels Rail

### Description:
Validate that the first available program from 13 days ago in the Catchup All Channels rail plays correctly.

### Steps:
1. Open the Catchup page.  
2. Open any channel from the **All Channels rail**.  
3. Navigate down to the programs from **13 days ago**.  
4. Navigate left to select the first available catchup event.  
5. Press OK to open the selected catchup event.  

### Verifications:
* The selected catchup event starts playing.  
* Playback proceeds without issues.  

### Expected Result:
* The first available program from **13 days ago** plays without any issues.

<!-- test
id: @Tb2b08834
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback of First Available Program from 13 Days Ago in Sports Channels Rail

### Description:
Validate that the first available program from 13 days ago in the Sports Channels rail plays correctly.

### Steps:
1. Open the Catchup page.  
2. Open any channel from the **Sports Channels rail**.  
3. Navigate down to the programs from **13 days ago**.  
4. Navigate left to select the first available catchup event.  
5. Press OK to open the selected catchup event.  

### Verifications:
* The selected catchup event starts playing.  
* Playback proceeds without issues.  

### Expected Result:
* The first available program from **13 days ago** in the **Sports Channels rail** plays without any issues.

<!-- test
id: @T30e19a83
priority: normal
creator: boris103@gmail.com
-->
# Verify Playback of Catchup Program Just Before Live Event and Transition to Live Program

### Description:
Validate that when finishing a catchup program just before the live event, playback transitions to the live program from the beginning.

### Steps:
1. Open the Catchup page.  
2. Open any channel from the **All Channels rail** or **Sports Channels rail**.  
3. Navigate to a catchup program that is one program before the live event.  
4. Play the selected catchup event, either by watching it till the end or seeking to the end.  

### Verifications:
* The live program starts from the beginning, not from the live moment.  

### Expected Result:
* The live program starts from the beginning after the catchup program ends.

<!-- test
id: @T3516c787
priority: normal
creator: boris103@gmail.com
-->
# Verify Transition to Next Catchup Program After Watching or Seeking to the End

### Description:
Validate that after finishing a catchup program (not just before the live event), playback transitions to the next catchup program.

### Steps:
1. Open the Catchup page.  
2. Open any channel from the **All Channels rail** or **Sports Channels rail**.  
3. Navigate to any catchup program except the one just before the live event.  
4. Watch the program till the end or seek to the end.  

### Verifications:
* The next catchup program starts playing.  

### Expected Result:
* The next catchup program plays successfully.

<!-- test
id: @T792e7167
priority: normal
creator: boris103@gmail.com
-->
# Verify Next Program Plays Automatically After Watching The Last Program From A Past Day

### Description:
Confirm that when finishing the last program on any past day’s rail in Catchup, the next day’s first program starts playing automatically.

### Steps:
1. Open the **Catchup** page.  
2. Select any channel from **Catchup All Channels**.  
3. Choose any **day rail except Today** (e.g., “לפני 3 ימים”).  
4. Play the **last program** in that rail.  
5. Watch until the end or seek to the end.  

### Verifications:
- The last program ends normally.  
- Playback automatically starts the first program from the **next day’s rail**.  

### Expected Result:
- After finishing the last program of a past day, the player automatically continues with the first program from the next day.
