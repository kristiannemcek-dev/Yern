# Privacy Policy for Yern

Effective date: January 3, 2026

**Yern** is a computer application operated by **Kristián Nemček**, trading as **Yern** ("we", "us", "our" or "Yern"). We may refer to you as **"user"**, **"you"**, or **"your"**. The purpose of this policy is to inform you about the personal information we collect, how we use and share that information, and the ways in which you can control that information. By using our app Yern, you agree to the terms of this policy and you expressly consent to the collection, use, and disclosure of your personal information in accordance with this policy. 

We may change this Privacy Policy from time to time. If we make changes, we will notify you by revising the date at the top of this policy. We encourage you to review this Privacy Policy regularly to stay informed about our information practices and the choices available to you. 

### 1. Data We Access and Process

To ensure privacy and accuracy, Yern uses a visibility threshold (**"visibility threshold"**) of 75%. This means an application is only considered "active" and subject to data recording if at least 75% of its window area is visible and not obscured by other windows on your screen. This threshold allows the app to distinguish between software you are actively using and software simply running in the background. This visibility threshold is checked for all window instances currently running on your system.

Yern runs a background process on your device to access the following information. 

**System Activity Data:** Yern automatically calculates and processes the total duration of your active computer session.
- **What is measured:** The time elapsed between login, or device unlock, and logout, system shutdown, or device lock.
- **Purpose:** This information is used to provide you with insights into your total computer usage time.
- **Storage:** This information is only stored in your local database. 

**App Focus Duration:** Yern automatically calculates the duration of your active interaction with other applications. 
- **What is measured:** The time elapsed between an application window exceeding the visibility threshold and when it is **minimized, closed, or obscured** by another window.
- **Purpose:** This information is used to provide you with insights into your application usage.
- **Storage:** This information is only stored in your local database. 

**Names of Applications:** The names of all applications currently maintaining an active window instance on your system, regardless of their visibility or focus.
- **Purpose:** To identify which applications are available for tracking and to determine their visibility status relative to your screen.
- **Storage:** Yern only records the name of an application into your local database if it meets the visibility threshold. Names of applications that are minimized, backgrounded, or obscured below the visibility threshold are processed in temporary memory only and are not saved to your disk.

**Logos of Applications:** Yern automatically collects a logo of an application if it meets the visibility threshold.
- **Storage:** Logos of applications that are minimized, backgrounded, or obscured below the visibility threshold are not saved to your disk.

**Icon File Paths:** Yern accesses the file system path of active applications to identify the software and extract its associated icon. 
- **Storage:** Yern does not store file paths of active applications. Yern only records file paths to an already collected icons so it can be used by the Yern application. The file path to an icon is securely stored in the local database.  
- **Personal Information Note:** File paths may contain your Windows Username. 
  
Any other information not mentioned above is not being collected by Yern. 

### 2. Where And How The Data Is Stored
Yern collects data to provide its core functionality. All tracking data is stored locally on your device. We do not have access to your screen time, app usage, or personal activity.

The following data is stored:
- **System Activity Data**
- **App Focus Duration**
- **Names of Applications** (see the above section on what application names we store)
- **Logos of Applications** (see the above section on what logos we store)
- **Logo File Paths** 

The above mentioned data are stored locally. The data we collect are:
- Never transmitted to external servers
- Never uploaded to the cloud
- Never shared with the publisher or any third party

All of the above data mentioned, except for **"Logos of Applications"**, is stored in a database. **"Logos of Applications"** are stored in a separate folder that is fully accessible. 

**Database Location:** Some of the data (see above for which) is stored in a local database file named **"DeviceData.db".** This file is located in your system's Local AppData folder within the following path:
  
    %LOCALAPPDATA%\Packages\[Your_Package_Identity]\LocalCache\Local\Yern\Database\DeviceData.db
    
**Database Security:** The local database is fully encrypted and requires a secure key for access. This ensures that your usage data is protected from unauthorized access by other users or software on your computer.

**Icons Location:** The icons are stored in a local folder named **"Icons"**. This folder is located in your system's Local AppData folder within the following path:

    %LOCALAPPDATA%\Packages\[Your_Package_Identity]\LocalCache\Local\Yern\Icons

**Data History:** The database contains data since installation of Yern.  

### 3. Data Deletion and Retention
Because Yern is a local-only application, you have full control over your data retention:

**Retention after Uninstallation:** All stored data is deleted on application uninstall. 

**Manual Deletion:** If you wish to permanently remove all data from your computer, you must manually delete the following folder:

    %LOCALAPPDATA%\Packages\[Your_Package_Identity]\LocalCache\Local\Yern

### 4. Children's Privacy
Because Yern is rated 3+, we are committed to the safety of young users. We do not knowingly collect, store, or share any personal information from children. If you are a parent or guardian and believe your child has provided us with personal data, please contact us so we can delete it.

Yern has been rated 3+ by the IARC. This means our content contains no violence, frightening elements, or inappropriate language.

### 5. Data Sharing
Yern does not share any data with any third parties.

Yern does not include any third-party analytics or tracking SDKs that transmit data.

Because all data remains on your device, no data is sold, transferred, or disclosed to external entities.

### 6. Your Privacy Rights (GDPR, CCPA, and Others)
Regardless of your location, we provide the same high standard of privacy rights to all users. Because your data is stored locally, you can exercise these rights directly: **Right to Access:** You can view all data collected by Yern directly within the application's interface. **Right to Portability:** You can manually copy the encrypted "DeviceData.db" file if you wish to move your data to another device. **Right to Erasure (Right to be Forgotten):** You can delete your data at any time by manually deleting the folder at location:

    %LOCALAPPDATA%\Packages\[Your_Package_Identity]\LocalCache\Local\Yern

**Right to Object/Restrict Processing:** You can stop all data collection by closing the Yern background process or uninstalling the app. 

### 7. Future Features
Future versions of Yern may introduce optional features such as cloud synchronization. 
If such features are added, this Privacy Policy will be updated before those features are enabled.

### 8. Contact Information
If you have any questions or concerns about this Privacy Policy or the data practices of Yern, please contact Kristián Nemček at: kristiannemcek.dev@gmail.com.
