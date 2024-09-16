# Media Snap Store

The **Media Snap Store** is a web application designed to showcase the use of browser APIs, particularly the **IndexedDB** database, along with **HTML**, **CSS**, and **JavaScript**. The app allows users to capture images, record videos, and store them locally in the browser using IndexedDB, ensuring they can access their media even after refreshing the page.

## Key Features

- **Media Recording and Storage**: Capture videos using the browser's MediaRecorder API and store them in IndexedDB for later retrieval.
- **Image Capture**: Take snapshots from the live video stream and store them as images in the IndexedDB.
- **Gallery Display**: A dedicated gallery to view stored videos and images.
- **Download Media**: Users can download their captured images or videos from the gallery.
- **Delete Media**: Users can delete specific media entries from the gallery, which removes them from both the UI and IndexedDB.
- **Filter Application**: Apply visual filters to images before capturing them.

## Highlights

- **Browser APIs**: Uses **MediaRecorder** and **getUserMedia** for real-time media capture.
- **IndexedDB Integration**: Media data is stored in IndexedDB, allowing the app to work with local storage for media retrieval even after page reloads.
- **Responsive Design**: The app is styled to work well across various devices using basic **CSS**.
- **Interactive UI**: Buttons for recording, capturing, and navigating to the media gallery provide an intuitive user experience.
- **Download and Delete Options**: Provides options to download or delete captured media directly from the gallery.

## Project Structure

- **index.html**: The main page where users can record or capture media.
- **gallery.html**: The gallery page where users can view, download, or delete their media.
- **db.js**: Handles the setup and interaction with the IndexedDB database.
- **script.js**: Contains the main logic for capturing and storing media.
- **gallery.js**: Contains the logic for displaying and managing media in the gallery.

## How to Use

1. Open the **Media Snap Store**.
2. Allow the browser to access your camera and microphone.
3. Use the record button to capture videos or the capture button to take snapshots.
4. Go to the gallery by clicking the media icon to view, download, or delete your media.

---

**Created by Trupti Yadav**
