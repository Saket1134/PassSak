# PassManager: A Secure MERN Stack Password Manager

PassManager is a modern, full-stack application designed to secure and simplify your digital life. It allows users to safely generate, store, and manage all their online credentials within an encrypted digital vault. By enforcing the use of strong, unique passwords for every service, this application significantly enhances the user's cybersecurity posture.

The project is built on the MERN stack, leveraging the power of JavaScript for seamless development across the entire application.
MERN=MongoDB,Express.js,React,Node.js.

**Frontend**=React.js with vite is uused to building Building the fast and interactive user interface (Navbar, Manager, Footer).  
**Backend**=Express.js / Node.js is used for The server-side framework and runtime environment for handling API requests and business logic.  
**Database**=MongoDB is A flexible, non-relational (NoSQL) database used for secure data storage.  
**Styling**=Tailwind CSS is A utility-first CSS framework for rapid and responsive UI development.   
**Security**=Bcrypt & AES-256 are the libraries for Master Password hashing and data encryption.   

# Key Features

Encrypted Digital Vault: All credentials are stored as unreadable ciphertext in the database.  
Secure Authentication: Access to the application is protected by a single, strong Master Password (which is stored as an irreversible hash).   
Unique Password Generation: A built-in feature to create highly complex and unique passwords for every new service.   
Seamless Management: The main <Manager /> component provides a user-friendly interface to add, view, edit, and delete stored credentials.   
Cross-Platform Access: Accessible from any device via the web browser.  
