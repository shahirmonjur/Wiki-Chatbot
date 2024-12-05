# Wiki-Chatbot Project


This project is a cross-platform web project me and my friend developed to interact with the Wikipedia API. This was in my 5th semester I believe, we were googling about these APIs as everyone was grabbing APIs left right and center and therefore we wanted to see what it was all about. Using the Electron Framework, we tinkered with the API from Wikipedia to try and see how those worked and the way they are integrated in the backend. We never hosted it for the web. 


![image](https://github.com/user-attachments/assets/f3d2e945-13c7-4514-9e70-abd2f82fac75)

What we worked on
   - Frontend Development:
        - Created the user interface using HTML, CSS, and JavaScript, focusing on simplicity and usability.
        - Added features like instant query submission and real-time response display.
        - Styled the application for a clean and modern appearance.

   - Backend Integration:
        - Developed the backend API using Flask to handle incoming user queries.
        - Implemented HTTP requests to fetch data from the Wikipedia API and process results for display.
        - Designed a preload script to facilitate communication between the Electron frontend and the Node.js backend.

   - Cross-Platform Support:
        - Used Electron to bundle the app for Windows, macOS, and Linux platforms.
        - Tested the app on multiple environments to ensure consistent performance.

   - Customization and Scalability:
        - Made the project modular by separating the frontend, backend, and API logic.
        - Included a framework for potential future features like offline mode or voice command support.

How to Use the Project

   Clone the repository:

      git clone https://github.com/your-username/wiki-chatbot-electron.git
      cd wiki-chatbot-electron

Install dependencies and start the application:

    npm install
    npm start

![image](https://github.com/user-attachments/assets/f5c605a6-c339-4cbd-bca2-0862b8d2b885)


Challenges and Solutions

   - Challenge: Managing communication between Electron’s frontend and backend.
        - Solution: I wrote a custom preload script to handle secure and efficient messaging between the two layers.
   - Challenge: Handling edge cases in API responses (e.g., incomplete or ambiguous queries).
        - Solution: Added logic in the Flask API to parse and handle such cases gracefully.

Future Improvements

While I’m happy with the current state of the app, there are a few enhancements I’d like to implement:

   - Offline Functionality: Cache previous queries and responses for offline access.
   - Advanced Features: Add support for voice commands and natural language processing to improve query handling.
   - UI Enhancements: Integrate animations and themes for a more engaging user experience.

Summary

This project gave me hands-on experience in building a full-stack application with Electron, Flask, and the Wikipedia API. It was a great opportunity to work on modular development, API integration, and creating a user-friendly interface. Feel free to explore the repository, try the app, or contribute to its development!
