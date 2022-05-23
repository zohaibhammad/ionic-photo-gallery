Build Your First Ionic App: Photo Gallery (Ionic Angular and Capacitor)
Get started with Ionic by building a photo gallery app that runs on iOS, Android, and the web - with just one codebase. This is the complete project referenced in the "Your First App: Angular" guide. Follow along to create a complete CRUD (create-read-update-delete) experience.

Powered by Ionic Angular (web app) and Capacitor (native app runtime).

How It Works
After the user navigates to Tab 2 (Photos), they can tap/click on the camera button to open up the device's camera. After taking or selecting a photo, it's stored permanently into the device's filesystem. When the user reopens the app at a later time, the photo images are loaded from the filesystem and displayed again in the gallery. The user can tap on a photo to be presented with the option to remove the photo.

Feature Overview
App framework: Angular
UI components: Ionic Framework
Camera button: Floating Action Button (FAB)
Photo Gallery display: Grid
Delete Photo dialog: Action Sheet
Native runtime: Capacitor
Taking photos: Camera API
Writing photo to the filesystem: Filesystem API
Storing photo gallery metadata: Storage API
Project Structure
Tab2 (Photos) (src/app/tab2/): Photo Gallery UI and basic logic.
PhotoService (src/app/services/photo.service.ts): Logic encapsulating Capacitor APIs, including Camera, Filesystem, and Storage.
How to Run
Note: It's highly recommended to follow along with the tutorial guide, which goes into more depth, but this is the fastest way to run the app.

Install Ionic if needed: npm install -g @ionic/cli.
Clone this repository.
In a terminal, change directory into the repo: cd photo-gallery-capacitor-ng.
Install all packages: npm install.
Run on the web: ionic serve.
Run on iOS or Android: See here.
