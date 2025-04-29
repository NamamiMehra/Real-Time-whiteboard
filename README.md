Realtime Whiteboard

1.)A collaborative, browser-based whiteboard application developed using Vanilla JavaScript, HTML, and CSS.

2.)Implemented core drawing tools including a pencil with multiple color options, an eraser with adjustable sizes, sticky notes, image attachments, and the ability to download the board as an image.

3.)Designed and developed an Undo-Redo functionality using arrays as stacks to store drawing positions and actions.

4.)Integrated real-time collaboration across multiple users using Socket.io and Node.js event handling.

5.)Optimized for seamless user interaction and low-latency updates



To set up and run the Realtime Whiteboard project locally, begin by ensuring that your system has Node.js (version 14 or higher), npm (Node Package Manager), and Git installed. First, clone the project repository using Git , and navigate into the project directory using cd. Once inside, install the necessary backend dependencies by running npm install, which will install packages such as express and socket.io as defined in the package.json file.

The project follows a simple structure where all client-side code—including HTML, CSS, and JavaScript—resides in the /public directory, while the server-side logic is contained in the server.js file. To start the application, run the command node server.js. This will launch the server on http://localhost:3000 by default. You can then open this URL in your web browser to access the whiteboard interface.

Once the application is running, users can draw on the canvas using a pencil tool with selectable colors and thicknesses, use an eraser, add sticky notes and images, undo and redo actions, and even download the board content. Real-time collaboration is supported via Socket.io, allowing multiple users to interact with the board simultaneously. 


An image highlighting the drawing and erasing tools, built with JavaScript to enable smooth, interactive sketching on the whiteboard.
![Screenshot 2025-04-29 225018](https://github.com/user-attachments/assets/a0ed542e-be61-4f7e-bd98-a5c999a76958)

A snapshot showcasing the sticky note and file upload features, allowing users to add notes and images directly onto the whiteboard.
![Screenshot 2025-04-29 224852](https://github.com/user-attachments/assets/e57616a3-ed00-4b15-b437-2150650878ad)

A visual demonstration of real-time collaboration, where multiple users interact with the whiteboard simultaneously with instant updates via Socket.io .
![Screenshot 2025-04-29 225228](https://github.com/user-attachments/assets/1b307956-62bd-41f8-9e8c-6f451dd1fff2)




