<!-- suite
id: @Se789eda7
emoji: 
-->
# Profiles



<!-- test
id: @T167011a2
priority: normal
creator: boris103@gmail.com
-->
# Verify Profiles Page Load and Display

### Description:
Validate that the Profiles page opens correctly and displays all existing profiles (minimum 1, up to 5), including profile names, avatars, and the Add Profile button when applicable.

### Steps:
1. Launch the app and navigate to the **Profiles** page.  
2. Wait for the Profiles title (“מי צופה?”) to appear.  
3. Observe the list of visible profile tiles.  
4. Move focus between the available profiles using the remote or keyboard.  

### Verifications:
- At least **one profile** is displayed.  
- A maximum of **five profiles** can be visible.  
- Each profile tile includes:  
  - An **avatar** (image or icon).  
  - A **name label** below the avatar.  
- The **Add Profile** tile is visible and focusable **only when fewer than 5 profiles exist**.  
- The title “מי צופה?” is properly centered and supports **RTL alignment**.  
- The focus/selection indicator moves smoothly between profile tiles.  

### Expected Result:
- The Profiles page loads successfully, showing between 1 and 5 profiles with correct labels, focus navigation, and RTL-safe layout. The Add Profile tile appears only if fewer than 5 profiles exist.

<!-- test
id: @T6e4945bc
priority: normal
creator: boris103@gmail.com
-->
# Add New Profile

### Description:
Validate that a user can add a new profile when the total number of profiles is fewer than five, including entering a name, choosing an avatar, and saving the profile. Confirm age restriction options behavior on Smart TV.

### Steps:
1. Navigate to the **Profiles** page and confirm there are **fewer than 5** profiles.  
2. Select the **Add Profile** tile.  
3. In the **Add Profile** screen, focus the name field and enter a valid profile name.  
4. Choose an **avatar** from the available options.  
6. Select **Save** (שמירה) to create the profile.  


### Verifications:
- The **Add Profile** screen displays: page title, **name input**, **avatar chooser**, and **Save/Cancel** actions.  
- **Save** is **disabled** until a non-empty name is entered.  
- On Smart TV, only **18+** age restriction can be set; **8+ / 14+** are **not available** to configure here.  
- After saving, the new profile appears in the profiles list with the chosen **name** and **avatar**.  
- The profile **count increases by 1**.  
- If the count reaches **5**, the **Add Profile** tile is no longer visible/focusable.  
- Layout and labels are **RTL-aligned** with no clipping or overlap.

### Expected Result:
- The user successfully creates a new profile (name + avatar) when fewer than five profiles exist. The profile is visible on the Profiles page, count increases by one, and only the **18+** age restriction is configurable on Smart TV.

**Note:** Setting **8+** or **14+** age restrictions must be done on the **Web** interface; Smart TV supports setting to **18+** only.

<!-- test
id: @Taf2757ad
priority: normal
creator: boris103@gmail.com
-->
# Verify First-Open State for New Profile

### Description:
Validate that a newly created profile opens with no existing “Favorites” or “Continue Watching” items, and that 18+ assets are available for unrestricted profiles.

### Steps:
1. From the **Profiles** page, select the **newly created profile**.  
2. On the landing/home screen, scan the visible rails and sections.  
3. Navigate to the **Favorites** section (or open the Favorites tab, if available).  
4. Navigate to the **Continue Watching** section.  
5. Browse or search for an **18+** asset and open its details page.

### Verifications:
- **Favorites:**  
  - The Favorites rail is **empty** or not displayed.  
- **Continue Watching:**  
  - The Continue Watching rail is **empty** or not displayed.  
- **18+ content availability:**  
  - 18+ assets appear in browse/search results.  
  - Asset details page opens without parental control restrictions.  
  - Main playback buttons (e.g., “צפייה”) are visible and functional.  
- Layout is **RTL-aligned** with no clipping or visual overlap.

### Expected Result:
- The new profile opens in a clean state with no Favorites or Continue Watching items.  
- 18+ assets are visible and playable for unrestricted profiles on Smart TV.

<!-- test
id: @Taa8c51d8
priority: normal
creator: boris103@gmail.com
-->
# Open Change Profile Avatar

### Description:
Validate that the user can open the **Change Profile Avatar** (דמות פרופיל) screen from the Add Profile page and that available avatar options are displayed correctly.

### Steps:
1. Navigate to the **Profiles** page and select **Add Profile**.  
2. On the Add Profile screen, focus on the **Change Profile Avatar (דמות פרופיל)** section.  
3. Select the **Change Profile Avatar** option.  

### Verifications:
- The **Change Profile Avatar** screen opens successfully.  
- A list/grid of avatar options is displayed.  
- Each avatar is clearly visible, properly aligned, and selectable.  
- Navigation between avatars using remote/keyboard is smooth and responsive.  
- The layout is **RTL-aligned** and text labels (if any) are correctly displayed.  
- A **Back** or **Cancel** option is available to return to the Add Profile screen.  

### Expected Result:
- The **Change Profile Avatar** screen opens correctly from the Add Profile page, showing all available avatars with proper alignment, focus navigation, and an option to return to the previous screen.

<!-- test
id: @T878e76b2
priority: normal
creator: boris103@gmail.com
-->
# Save Selected Avatar and Create Profile

### Description:
Validate that after selecting a new avatar in the **Change Profile Avatar** screen, the user can save it along with the profile name, and that the profile is created successfully with the correct avatar and name.

### Steps:
1. Navigate to the **Profiles** page and select **Add Profile**.  
2. On the **Add Profile** screen, enter a valid **profile name** .  
3. Select Change Profile Avatar **(דמות פרופיל)**.  
4. Choose a new avatar from the available options.  
5. Confirm or exit back to the Add Profile screen.  
6. Select Save **(שמירה)** to create the profile.  
7. Return to the **Profiles** page and locate the newly created profile.

### Verifications:
- After selecting the avatar, it appears on the Add Profile screen before saving.  
- The **Save (**שמירה**)** button becomes enabled after entering a valid name and choosing an avatar.  
- The new profile appears in the profile list after saving.  
- The **profile name** matches the entered name.  
- The **avatar** displayed for the new profile matches the one selected.  
- Profile list layout remains **RTL-aligned**, and no visual overlap occurs.  

### Expected Result:
- The profile is created successfully with the selected avatar and entered name, both displayed correctly on the Profiles page after saving.
