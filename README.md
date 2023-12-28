# NeoMeet
This is a QR code based digital business card app for easy contact info exchange. I made this app for both iOS and Android as a side project. It uses the Flutter cross-platform framework for the frontend (similar to component-based frameworks like React or Angular) and uses Google Firebase for backend services (i.e. authentication and NoSQL data storage). I've structured the project using the BLoC pattern (similar to MVC), but to further help navigate the project, I've described the subfolders below.

## Structure
- src
    - landing_page: determines if the app should send a user to sign-in page or directly to the home page based on cached auth token status
    - app: frontend files for the pages (describes how each page is laid out)
    - custom_widgets: a folder storing the custom components I made to encapsulate and standardize UI elements
    - models: data models used for parsing data before interacting with the backend
    - services: backend services (authentication and data storage/retrieval)
    - sign_in: sign in pages (separate from the app folder for my own sake during the development process)

## Images
If the images are not appearing in a viewer, please refer to the rest of the zipped folder for references.
![main](./main.webp)
![settings](./settings.webp)
![contact](./contact.webp)
![social](./social.webp)
