# 💬 Real-Time Chat Application (Altura Chat)


## About The Project

This project is a **real-time chat application** developed to showcase my skills in fundamental web technologies. It's designed to allow users to engage in instant messaging across various channels, handle user authentication, and manage basic user profiles. This application serves as a **personal portfolio project**, demonstrating my proficiency in **pure HTML, CSS, and Vanilla JavaScript**, as well as my competence in integrating with **Google Firebase** services.

Inspired by my experience running the **Altura Finance Telegram community** for crypto market analysis, I built this project to highlight the importance of swift and effective information sharing from a technical perspective. The application is developed without reliance on external frameworks or libraries, emphasizing my deep understanding of core web development principles and my ability to write flexible, modular code.

---

## 🚀 Features

* **User Authentication:** Secure email/password-based sign-up and login using Firebase Authentication.
* **Real-Time Messaging:** Instant message exchange powered by Firebase Realtime Database.
* **Multi-Channel Support:** Users can easily switch between predefined chat rooms/channels (e.g., "General", "Investment Chat").
* **Dynamic Theme:** Toggle between light and dark modes based on user preference.
* **User Display Names:** Messages display the sender's username or email.
* **Responsive Design:** Utilizes basic CSS media queries to ensure compatibility across various screen sizes (mobile, tablet, desktop).

---

## 🛠 Tech Stack

This project is built with core web technologies and leverages Google Firebase for its backend-as-a-service (BaaS) capabilities:

* **Frontend:**
    * **HTML5:** The structural foundation of the application.
    * **CSS3 (Vanilla CSS):** Custom-written styles for a modern and responsive user interface.
    * **Vanilla JavaScript:** All application logic, DOM manipulation, and Firebase integration are written in pure JavaScript, without any external frameworks or libraries.
* **Backend as a Service (BaaS):**
    * **Google Firebase:**
        * **Authentication:** For user identity and access management.
        * **Realtime Database:** A NoSQL cloud database for real-time storage and synchronization of messages.

---

## 🔧 Installation and Setup

This project is a client-side web application dependent on Firebase services. It's straightforward to set up and run on your local machine.

1.  **Create and Configure a Firebase Project:**
    * Go to the Firebase console: [https://console.firebase.google.com/](https://console.firebase.google.com/)
    * Create a new Firebase project or select an existing one.
    * **Enable the following Firebase services** for your project:
        * **Authentication:** Navigate to "Build" > "Authentication" > "Get started." In the "Sign-in method" tab, enable the **"Email/Password"** provider.
        * **Realtime Database:** Navigate to "Build" > "Realtime Database" > "Create database." For development, you can start in **"Test mode."**
    * In your project's overview page (gear icon next to "Project overview"), click on "Add app" (the `</> Web` icon) to add a web application. Copy the **`firebaseConfig`** object provided (containing `apiKey`, `authDomain`, `databaseURL`, etc.).

2.  **Clone the Repository:**
    * Open your terminal or command prompt and clone the project repository to your local machine:
        ```bash
        git clone [https://github.com/omerfaruksolmaz/altura-chat.git](https://github.com/omerfaruksolmaz/altura-chat.git)
        cd altura-chat
        ```
        

3.  **Update `index.html` with Firebase Config:**
    * Open the **`index.html`** file located in the root directory of the cloned project using your preferred code editor.
    * Locate the `firebaseConfig` object within the `<script>` tags, below the Firebase library imports, and **replace the placeholder values with your actual Firebase project configuration** that you copied in Step 1:

        ```javascript
        const firebaseConfig = {
            apiKey: "YOUR_API_KEY",
            authDomain: "YOUR_AUTH_DOMAIN",
            databaseURL: "YOUR_DATABASE_URL",
            projectId: "YOUR_PROJECT_ID",
            storageBucket: "YOUR_STORAGE_BUCKET",
            messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
            appId: "YOUR_APP_ID"
        };
        ```

4.  **Run the Application:**
    * Simply open the `index.html` file directly in any modern web browser (e.g., Chrome, Firefox). You can do this by double-clicking the file or dragging it into your browser's address bar.
    * For a better development experience, if you are using an IDE like Visual Studio Code, it's recommended to install an extension like "Live Server" and open `index.html` through a local server (e.g., `http://127.0.0.1:5500/index.html`).

Once launched, the Firebase authentication screen will greet you, allowing you to sign up or log in.

---

## 🧪 Screenshots

![image](https://github.com/user-attachments/assets/a02d8397-abb6-46f4-96f8-8ce09cdc09e9)



---

## Contributing

This project is a part of my personal portfolio. However, I believe in the principles of open source and am open to improvements. Feel free to submit pull requests for bug fixes, feature suggestions, or performance enhancements.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact

* **Name:** Ömer Faruk Solmaz
* **Email:** [omerfaruksolmazzz@outlook.com](mailto:omerfaruksolmazzz@outlook.com)
* **GitHub Profile:** [https://github.com/omerfaruksolmaz](https://github.com/omerfaruksolmaz)
* **Project Link:** [https://github.com/omerfaruksolmaz/altura-chat](https://github.com/omerfaruksolmaz/altura-chat)
