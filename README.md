
**Overview**

This project is a real-time collaborative whiteboard built using HTML, CSS, and vanilla JavaScript. It allows multiple users to draw, write, and interact on a shared canvas in real-time. Whether for brainstorming sessions, collaborative design work this whiteboard provides a seamless and interactive experience.

**Features**

Pencil Tool: Draw on the whiteboard with different colors, allowing for easy distinction of different elements.

Eraser Tool: Erase parts of your drawing with adjustable sizes for precision.

Sticky Notes: Add sticky notes to the board to jot down ideas or comments.

Sticky Images: Insert images onto the whiteboard to enhance your visual content.

Download Board: Save your whiteboard as an image file to keep a record of your work.

Undo/Redo Functionality: Easily correct mistakes or revisit previous actions with undo and redo features, implemented using an array stack to store drawing positions.

Real-Time Collaboration: Powered by Socket.io and Node.js events, the whiteboard reflects changes in real-time, ensuring all users see the same updates simultaneously.

**Technology Stack**

Frontend: HTML, CSS, Vanilla JavaScript

Backend: Node.js

Real-Time Communication: Socket.io

**Getting Started**

To run this project locally, follow these steps:

Prerequisites

Node.js installed on your machine

**Installation**

Clone the repository:

git clone https://github.com/Sanjana428/realtime-whiteboard.git

cd realtime-whiteboard

Install dependencies:

npm install

Start the server:

node server.js

Open the app:

Visit http://localhost:3000 in your web browser to start using the whiteboard.

**Usage**
Drawing and Erasing: Select the pencil tool to start drawing, and use the eraser tool to remove any unwanted marks. Adjust the colors and sizes as needed.

Sticky Notes and Images: Click on the respective buttons to add sticky notes or images to your whiteboard.

Undo/Redo: Use the undo and redo buttons to navigate through your drawing history.

Download: Click the download button to save your whiteboard as an image file.

**Contributing**
Contributions are welcome! If you have ideas for new features or improvements, feel free to submit issues or pull requests.

