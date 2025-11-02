<!-- suite
id: @S6ac15c82
emoji: 
-->
# Hero Banner



<!-- test
id: @Tc94122c9
priority: normal
creator: boris103@gmail.com
-->
# Verify Hero Banner Playback on App Launch

### Description:
Validate that upon launching the FreeTV app, the Hero banner starts playback automatically and streams both live channels and VOD trailers smoothly.

### Steps:
1. Open the app  
2. Observe the **Hero banner** playback immediately upon launch  

### Verifications:
* Hero banner plays a live channel smoothly without buffering or interruptions  
* Hero banner plays a VOD trailer smoothly without buffering or interruptions  

### Expected Result:
* Live channel in the Hero banner plays without issues  
* VOD trailer in the Hero banner plays without issues

<!-- test
id: @T6a46f956
priority: normal
creator: boris103@gmail.com
-->
# Verify No Playback on Hero Banner

### Description:
Validate that when a profile with an age limit lower than the asset restriction is active, the Hero banner does not play restricted content and focus shifts appropriately.

### Prerequisite:
* A VOD asset with an age restriction of 14+ or 18+ is configured in the Back Office (BO)

### Steps:
1. Open the app  
2. Log in to your account  
3. Switch to a profile with an age limit of 8+  
4. Observe the Hero banner  

### Verifications:
* Hero banner does not play any content  
* Focus is automatically set on the first channel in the rail to the right  

### Expected Result:
* Hero banner remains static without playback  
* Initial focus is positioned on the first channel in the rail to the right

<!-- test
id: @Tcacf454b
priority: normal
creator: boris103@gmail.com
-->
# Verify Hero Banner Metadata Display

### Description:
Validate that the Hero banner displays the correct metadata fields depending on the type of content (Movie, Series, or Live channel/event).

### Steps:
1. Open the app  
2. Navigate to any page that contains a Hero banner (e.g., Main, Movies, Series, Kids)  
3. Observe the Hero banner and note the type of content being displayed (Movie, Series, or Live)  

### Verifications:
* If a **Movie** is displayed:  
  - Title is shown  
  - Synopsis is visible  
  - Tags (e.g., Genre) are present  
  - Duration is displayed (if available)  
  - Year is shown (if available)  
  - Movie tag is visible  
  - Age rating is visible (if available)  
  - HD/4K label is visible (if applicable)  

* If a **Series** is displayed:  
  - Title is shown  
  - Synopsis is visible  
  - Tags (e.g., Genre) are present  
  - Number of seasons or episodes is displayed  
  - Year is shown (if available)  
  - Series tag is visible  
  - Age rating is visible (if available)  
  - HD/4K label is visible (if applicable)  

* If a **Live channel/event** is displayed:  
  - Channel or event name is shown  
  - Live tag is visible  
  - Current program name is displayed  
  - Age rating is visible (if available)  
  - HD/4K label is visible (if applicable)  

### Expected Result:
* Hero banner displays all required metadata fields for the content type shown, according to BO configuration.  
* Optional metadata fields (e.g., age rating, release year) are displayed when available.

<!-- test
id: @T612ec9fe
priority: normal
creator: boris103@gmail.com
-->
# Verify Hero Banner Playback on Movies Page

### Description:
Validate that the Hero banner on the Movies page plays a Movie VOD trailer smoothly and without interruptions.

### Steps:
1. Open the app  
2. From the side menu, navigate to the **Movies** page  
3. Observe the Hero banner  

### Verifications:
* A Movie VOD trailer plays smoothly without buffering or interruptions  

### Expected Result:
* Movie VOD trailer playback is smooth and uninterrupted on the Hero banner

<!-- test
id: @T5bbdd627
priority: normal
creator: boris103@gmail.com
-->
# Verify Hero Banner Playback on Series Page

### Description:
Validate that the Hero banner on the Series page plays a Series VOD trailer smoothly and without interruptions.

### Steps:
1. Open the app  
2. From the side menu, navigate to the **Series** page  
3. Observe the Hero banner  

### Verifications:
* A Series VOD trailer plays smoothly without buffering or interruptions  

### Expected Result:
* Series VOD trailer playback is smooth and uninterrupted on the Hero banner

<!-- test
id: @Te299b830
priority: normal
creator: boris103@gmail.com
-->
# Verify Sports Page Initial Focus and Top Shelf Playback

### Description:
Validate that on the Sports page, no Hero banner is present, the initial focus is on the channels rail, and the Top Shelf automatically plays the Sport5 channel.

### Steps:
1. Open the app  
2. From the side menu, navigate to the **Sports** page  
3. Observe the page layout and focus position  
4. Check the Top Shelf playback  

### Verifications:
* No Hero banner is displayed on the Sports page  
* Initial focus is set on the channels rail  
* Top Shelf starts playback of the Sport5 channel automatically  

### Expected Result:
* Sports page opens without a Hero banner, focus is on the channels rail, and Sport5 channel plays on the Top Shelf

<!-- test
id: @Tbbbf27c5
priority: normal
creator: boris103@gmail.com
-->
# Verify Hero Banner Playback on Kids Page

### Description:
Verify that the Hero banner on the Kids page plays a Kids VOD trailer smoothly and without interruptions after navigating from the side menu.

### Steps:
1. Open the app  
2. From the side menu, navigate to the **Kids** page  
3. Wait for the Hero banner to load  
4. Observe the playback of the Kids VOD trailer  

### Verifications:
* Hero banner content loads successfully  
* Kids VOD trailer starts playing automatically  
* Playback runs smoothly without buffering or interruptions  

### Expected Result:
* Kids VOD trailer on the Hero banner plays seamlessly and without performance issues
