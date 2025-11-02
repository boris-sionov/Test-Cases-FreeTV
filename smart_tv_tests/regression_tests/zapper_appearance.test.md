<!-- suite
id: @Sa89c3280
emoji: 
-->
# Zapper Appearance



<!-- test
id: @T7ae8a997
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Appearance And Metadata On Live Channel

### Description:
Ensure that when the Zapper is raised on a live channel, all key visual elements and metadata are displayed correctly.

### Steps:
1. Tune to any **live channel** and start playback.  
2. Raise the **Zapper**.  
3. Check that all expected information appears on the screen.  

### Verifications:
- A **green badge** labeled **“משודר כעת” (Live Now)** is displayed.  
- A **red badge** labeled **“שידור חי” (Real Time)** appears if the program is broadcast live.  
- The **program time range** is shown in the correct format (e.g., *15:30–16:20*).  
- The **program title** and **description** are both visible and not empty.  
- A **poster image** for the current program is displayed.  
- The **channel logo** is shown in **color** (not the white monochrome version).  
- **Navigation arrows** for UP, DOWN, LEFT, and RIGHT are visible for browsing.  

### Expected Result:
- All visual elements and metadata are displayed correctly when the Zapper is opened on a live channel, including Live Now and Real Time badges when applicable.

<!-- test
id: @T5068913b
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Appearance And Metadata On Catchup Event

### Description:
Ensure that when the Zapper is raised on a catchup event, all required visual elements and metadata are displayed correctly.

### Steps:
1. Open any **catchup event** and start playback.  
2. Raise the **Zapper**.  
3. Review the information shown on the screen.  

### Verifications:
- A **green badge** labeled **“שודר השבוע” (Catchup)** is displayed.  
- The **day label** of the program appears correctly (e.g., *מוקדם יותר היום*, *אתמול*, or *יום + תאריך*).  
- The **program time range** is shown in the correct format (e.g., *15:30–16:20*).  
- The **program title** and **description** are both visible and complete.  
- The **poster** for the selected program is displayed.  
- The **channel logo** appears in **color** (not the white monochrome version).  
- **Navigation arrows** for UP, DOWN, LEFT, and RIGHT are visible.  

### Expected Result:
- When opening the Zapper on a catchup event, all visual elements and metadata appear correctly, including the green catchup badge, program time range, title, description, and colored channel logo.

<!-- test
id: @Tb60eb116
priority: normal
creator: boris103@gmail.com
-->
# Verify Zapper Appearance And Metadata On Future Program

### Description:
Ensure that when the Zapper is raised and a future program is selected, all required metadata and visual elements are displayed correctly.

### Steps:
1. Open any **live or catchup** channel.  
2. Raise the **Zapper**.  
3. Navigate to any **future program** using the LEFT or RIGHT buttons.  
4. Review the information shown on the screen.  

### Verifications:
- If the future program is scheduled as **live**, a **red badge** labeled **“שידור חי” (Real Time)** is shown.  
- The **day label** of the program appears correctly (e.g., *בהמשך היום*, *מחר*, or *יום + תאריך*).  
- The **program time range** is shown in the correct format (e.g., *15:30–16:20*).  
- The **program title** and **description** are both visible and not empty.  
- A **poster image** for the selected program is displayed.  
- The **channel logo** appears in **color** (not the white monochrome version).  
- **Navigation arrows** for UP, DOWN, LEFT, and RIGHT are visible.  

### Expected Result:
- When navigating to a future program inside the Zapper, all metadata and visuals appear correctly. Standard programs have no badge, while future live broadcasts display the red “שידור חי” (Real Time) badge.
