# Privacy Policy for Yern

Effective date: January 3, 2026

**Yern** is a computer application operated by **Kristián Nemček**, trading as **Yern** ("we", "us", "our" or "Yern"). We may refer to you as **"user"**, **"you"**, or **"your"**. The purpose of this policy is to inform you about the personal information we collect, how we use and share that information, and the ways in which you can control that information. By using our app Yern, you agree to the terms of this policy and you expressly consent to the collection, use, and disclosure of your personal information in accordance with this policy. 

We may change this Privacy Policy from time to time. If we make changes, we will notify you by revising the date at the top of this policy. We encourage you to review this Privacy Policy regularly to stay informed about our information practices and the choices available to you. 

### 1. Data We Access and Process
Yern runs a background process on your device to access the following information.

**System Activity Data:** Yern automatically calculates and processes the total duration of your active computer session.
- **What is measured:** The time elapsed between login, or device unlock, and logout, system shutdown, or device lock.
- **Purpose:** This information is used to provide you with insights into your total computer usage time.
- **Storage:** This information is only stored in your local database. 

**App Focus Duration:** Yern automatically calculates the duration of your active interaction with other applications. 
- **What is measured:** The time elapsed between an application window becoming **at least 75% visible** (at least 75% of the window's area is visible) and when it is **minimized, closed, or obscured** by another window.
- **Purpose:** This information is used to provide you with insights into your application usage.
- **Storage:** This information is only stored in your local database. 

**Names of Applications:** The names of all applications currently maintaining an active window instance on your system, regardless of their visibility or focus.
- **Purpose:** To identify which applications are available for tracking and to determine their visibility status relative to your screen.
- **Storage:** Yern only records the name of an application into your local database if it meets the 75% visibility threshold. Names of applications that are minimized, backgrounded, or obscured below this threshold are processed in temporary memory only and are not saved to your disk.

**Logos of Applications:** Yern automatically collects a logo of an application if it meets the 75% visibility threshold.
- **Storage:** Logos of applications that are minimized, backgrounded, or obscured below this threshold are not saved to your disk.

**Application File Paths:** Yern accesses the file system path of active applications to identify the software and extract its associated icon. 
- **Storage:** Yern only records file paths to an already collected icons so it can be used by the Yern application. 
- **Personal Information Note:** File paths may contain your Windows Username. 
  
Any other information not mentioned above is not being collected by Yern. 

### 2. Where And How The Data Is Stored
Yern stores only the minimum data necessary to provide its core functionality. 

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

All of the above data mentioned, except of **"Logos of Applications"**, are stored in a database. **"Logos of Applications"** are stored in a separate folder that is fully accessible. 

**Database Location:** Some of the data (see above for which) is stored in a local database file named **"DeviceData.db".** This file is located in your system's Local AppData folder within the following path:
  
    %LocalAppData%\Yern\Database\DeviceData.db
    
**Database Security:** The local database is fully encrypted and requires a secure key for access. This ensures that your usage data is protected from unauthorized access by other users or software on your computer.

**Icons Location:** The icons are stored in a local folder named **"Icons"**. This folder is located in your system's Local AppData folder within the following path:

    %LocalAppData%\Yern\Icons

### 3. Data Deletion and Retention
Because Yern is a local-only application, you have full control over your data retention:

**Retention after Uninstallation:** To prevent accidental data loss, uninstalling Yern does not automatically delete neither your local database (UserData.db) and icons stored. This allows you to retain your history if you choose to reinstall the application in the future.

**Manual Deletion:** If you wish to permanently remove all data from your computer, you must manually delete the following folder:

    %LocalAppData%\Yern

### 4. Data Sharing
Yern does not share any data with any third parties.

Because all data remains on your device, no data is sold, transferred, or disclosed to external entities.

### 5. Legal Basis for Processing (GDPR)
Under the General Data Protection Regulation (GDPR), Yern processes data based on:

- User consent, by choosing to install and use the App

- Legitimate interest, as the data processing is strictly necessary to provide the App’s functionality

- Because data never leaves your device, no international data transfers occur.

### 6. Future Features
Future versions of Yern may introduce optional features such as cloud synchronization. 
If such features are added, this Privacy Policy will be updated before those features are enabled.

### 7. Contact Information
If you have any questions or concerns about this Privacy Policy or the data practices of Yern, please contact Kristián Nemček at: kristiannemcek.dev@gmail.com.
