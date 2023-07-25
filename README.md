# PWA-TextEditor

Web Applications (PWA) Text Editor
This repository contains the code for a Progressive Web Application (PWA) Text Editor. The text editor is designed to work offline, provide a seamless user experience, and offer essential text editing capabilities.

Demo
A live demo of the PWA Text Editor can be accessed at https://pwa-veg-5a7fb18eae75.herokuapp.com/

Features
Offline Access: The PWA Text Editor can be accessed and used even when the user is offline, thanks to the service worker caching and offline capabilities.

Responsive Design: The text editor is fully responsive and works on various devices, including desktops, tablets, and mobile phones.

Text Editing: Users can create, edit, and format text using standard text editing features such as bold, italic, underline, bullet points, and more.

Save and Load: The text editor supports saving and loading documents, allowing users to continue their work from where they left off.

Technologies Used
The PWA Text Editor is built using the following technologies:

HTML5, CSS, and JavaScript: For the front-end user interface and interactivity.

Service Worker: To enable offline access and caching of critical resources.

IndexedDB: For local data storage and document persistence.

Installation and Usage
To use the PWA Text Editor, simply visit the provided live demo link https://pwa-veg-5a7fb18eae75.herokuapp.com/ in your web browser. You can also install the PWA to your device for quick access by following the browser's prompts to add it to the home screen.

Development
If you want to contribute to the development of the PWA Text Editor or set up your local development environment, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/Valliebby/PWA-TextEditor.git
Navigate to the project directory:

bash
Copy code
cd PWA-TextEditor
Start a local development server:

bash
Copy code
npm install
npm start
Open your web browser and visit http://localhost:3000 to access the PWA Text Editor.

Deployment
The PWA Text Editor can be deployed to any web hosting platform that supports static website hosting. Simply copy the contents of the build folder after running npm run build and upload them to your preferred hosting service.

Contributing
Contributions are welcome! If you find any issues or want to add new features, feel free to open a pull request.

License
This project is licensed under the MIT License. Feel free to use and modify the code as per the terms of the license.




https://github.com/Valliebby/PWA-TextEditor/assets/119483866/fdbe8695-8c80-4485-b583-eb768caa60f6


The following image shows the application's Manifest.json file:
![Screen Shot 2023-07-25 at 5 34 41 PM](https://github.com/Valliebby/PWA-TextEditor/assets/119483866/eaa51fbe-869c-4e49-a320-8d95ea3f0112)

The following image shows the application's registered service worker:

![Screen Shot 2023-07-25 at 5 33 47 PM](https://github.com/Valliebby/PWA-TextEditor/assets/119483866/654cea3b-93cf-4d63-a8e7-3f4dd29f1825)

The following image shows the application's IndexedDB storage:
![Screen Shot 2023-07-25 at 5 39 08 PM](https://github.com/Valliebby/PWA-TextEditor/assets/119483866/34e9cae4-291c-4623-a3b7-e81cfd9c8f21)


