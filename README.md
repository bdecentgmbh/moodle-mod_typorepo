# Description
The TYPO3 Repository and SSO Plugin was build for the Learning Content Management System LMS3 (www.lms3.de) which is a distribution of TYPO3 and created by LEARNTUBE GmbH (www.learntube.de). However, LMS3 is not needed as a complete solution to connect a TYPO3 installation with Moodle. Any TYPO3 Installation (Version 10.x) can be used as an authoring platform and content repository. With this Plugin it is possible to embed login protected TYPO3 pages inside Moodle.

Please note: Currently a paid extension for TYPO3 is needed to connect TYPO3 and Moodle. Please contact mail@learntube.de for an inquiry.

You can read more about the plugin on: https://www.lms3.de/moodle-connector (german only)

## The TYPO3 Repository and SSO Plugin:
- Connects a TYPO3 Installation with one or more Moodle Installations
- TYPO3 pages that are login protected can be displayed by the SSO
- Moodle Users will be identified in TYPO3 and added with a synonymous user account by using only the Moodle ID
- TYPO3 Pages can be shown inside an iFrame in Moodle or a new window

Note: For best practice it is recommended to build a Moodle embed friendly TYPO3 template, that will only display the content, not the general menu and footer section that is normally provided by a typical TYPO3 website.

## The TYPO3 Extension:
Note: Currently the TYPO3 extension, needed to connect to TYPO3 is not published yet. The extension will be available in first part of 2022. If you are interested in purchasing the extension as early bird, please contact via: mail@learntube.de.

## Roadmap
We monitor the plugin as well as the TYPO3 extension against each Moodle and TYPO3 minor and major update, so we will get aware about any problems in rather short time.

## Sponsors
The Plugin is sponsored by the Friedrich Ebert Stiftung (www.fes.de).

## Potential privacy issues
To grant user specific services in TYPO3 it is needed, that the Moodle user will have a synonymous user account in TYPO3. This happens on the fly while the user will access a TYPO3 Activity in Moodle. By default, we only pass the Moodle User ID to create a unique user that can be identified. So, there is no name or e-mail or any other personal information passed. However, it is possible to do so, by changing some parameter in the programming. The Plugin will not pass any user generated data from Moodle to TYPO3 either.

## Installation on Moodle
- Unzip the files locally and upload them to a folder called 'mod/typorepo' on the server. 
- Login as admin and visit the home page to trigger the upgrade 
- Set the dimensions of the iframe or new window 
- Set the TYPO3 server details 
- Save and return to any course

## Installation on TYPO3
- Install the Moodle SSO TYPO3 Extension in your TYPO3 Installation. 
- Install the Moodle Sitemap TYPO3 Extension in your TYPO3 Installation. 
- Create a page and add a Moodle Sitemap Plugin
- Create a sysfolder where you store the Moodle instances to connect to

## Adding a TYPO3 Repository activity in Moodle
- Click 'Turn editing on', in a course view. 
- Click on the add icon in the desired course section and choose Typo3 Repository 
- Give names to the activity 
- Choose TYPO3 Page to embed from the page tree
- Choose if the Page will be displayed in an iFrame or a new Window
- Save the activity. 
