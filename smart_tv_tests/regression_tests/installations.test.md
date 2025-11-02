<!-- suite
id: @Sd01254ff
emoji: 
-->
# Installations



<!-- test
id: @T84ec5e05
priority: normal
creator: boris103@gmail.com
-->
# Verify Installation of FreeTV App on LG Smart TV

### Description:
Validate that the FreeTV app can be installed and launched successfully on an LG Smart TV running webOS in developer mode.

### Requirements:
* Access to the latest app build from [Releases - Smart TV](https://confluence.redge.com/display/KRS/Releases+Smart+TV)  
* LG TV with developer mode enabled (webOS)  
* Dev Manager Desktop tool: [webosbrew/dev-manager-desktop](https://github.com/webosbrew/dev-manager-desktop)  

### Steps:
1. Download the latest FreeTV build from the provided Confluence link  
2. Install the app on the LG TV using **Dev Manager Desktop**  

### Verifications:
* FreeTV app icon appears in the LG Smart TV launcher/home screen  
* App launches successfully on LG TV  

### Expected Result:
* FreeTV app installs and launches successfully on LG Smart TV  

### Remark:
* Block this test if testing is being performed on Samsung or VIDAA platforms

<!-- test
id: @Td4911577
priority: normal
creator: boris103@gmail.com
-->
# Verify Installation of FreeTV App on Samsung Smart TV

### Description:
Validate that the FreeTV app can be installed and launched successfully on a Samsung Smart TV using a flash drive.

### Requirements:
* Access to the latest app build from [Releases - Smart TV](https://confluence.redge.com/display/KRS/Releases+Smart+TV)  
* Samsung TV with USB port  
* Flash drive for installation  

### Steps:
1. Download the latest FreeTV build from the provided Confluence link  
2. Copy the build to a flash drive  
3. Install the app on the Samsung TV using the flash drive  

### Verifications:
* FreeTV app icon appears in the Samsung Smart TV launcher/home screen  
* App launches successfully on Samsung TV  

### Expected Result:
* FreeTV app installs and launches successfully on Samsung Smart TV  

### Remark:
* Block this test if testing is being performed on LG or VIDAA platforms

<!-- test
id: @T124987a4
priority: normal
creator: boris103@gmail.com
-->
# Verify FreeTV App Version in Settings

### Description:
Validate that the FreeTV app displays the correct version information in the Settings menu.

### Prerequisite:
* FreeTV app is installed and accessible

### Steps:
1. Open the FreeTV app  
2. Navigate to the **Settings** menu  
3. Locate and view the **App Version** information  

### Verifications:
* App version is displayed in the Settings menu  
* The displayed version matches the expected version from the release notes or build information  

### Expected Result:
* The displayed app version matches the expected version

<!-- test
id: @T3b67b194
priority: normal
creator: boris103@gmail.com
-->
# Verify Installation of FreeTV App on VIDAA Smart TV

### Description:
Validate that the FreeTV app can be installed and launched successfully on a VIDAA Smart TV using the official installation guide.

### Requirements:
* VIDAA installation instructions: [VIDAA Installation Guide](https://docs.google.com/document/d/1R8fCTB1KItffUl9fKeVrbVbBQPAgG9ibR9rABXXDMSs/edit?usp=sharing)  

### Steps:
1. Follow the VIDAA Installation Guide to install the FreeTV app  

### Verifications:
* FreeTV app appears in the **My Apps** screen  
* App launches successfully from the **My Apps** screen  

### Expected Result:
* FreeTV app installs successfully and launches without errors on VIDAA Smart TV  

### Remark:
* Block this test if testing is being performed on LG or Samsung platforms
