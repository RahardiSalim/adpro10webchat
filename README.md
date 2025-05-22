## 1.1

We are now transitioning from a console-based chat system to a browser-based chat experience using WebSockets, Rust, and the Yew framework. This modern approach allows real-time messaging over the web, making it more accessible and user-friendly.

In this experiment, we focused on the client-side implementation of the webchat system. The code was cloned from the DevGenius blog tutorial, which provided a great starting point. After successfully cloning and running both the client and server projects, we tested the application locally.

The image below demonstrates two browser windows connected to localhost:8000/chat. As seen, both users ("Rahardi" and "Salim") can send and receive messages in real time, and the interface displays all connected users and their messages.

![desc](asset/overview.png)
This test confirms the original code runs successfully and supports real-time chat between multiple users via a graphical web interface.