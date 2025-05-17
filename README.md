# 📹 Jitsi Meet Integration with Recording Feature

This project demonstrates how to integrate the open-source **Jitsi Meet** video conferencing app into a custom web page using an iframe. It also explores the **recording functionality** using Jitsi as a Service (JaaS).

## 💡 Objective

As part of an internship assignment, I was asked to:

- Embed the Jitsi video conferencing app into a web page.
- Allow users to join a meeting through the embedded interface.
- Enable **recording** of the meeting and save it on the cloud.
- Share a working meeting link for testing.

## ⚙️ How It Works

- The app uses the **JaaS API key and JWT token** to authenticate and embed the Jitsi Meet iframe securely.
- A simple webpage hosts the video call.
- Recording is supported via JaaS (cloud-based recording at $0.01/minute).

## 🛠️ Technologies Used

- HTML / JavaScript
- Jitsi Meet API (via iframe)
- JWT Authentication
- Jitsi as a Service (JaaS)

## 📼 Recording Note

Recording via JaaS is a **PAID feature**. It currently costs **$0.01 per minute**. If you're testing this locally and recording fails, it's likely due to:

- Not having billing enabled in JaaS.
- Using the free `meet.jit.si` service, which doesn’t allow full recording for embedded use.

You can alternatively use tools like **OBS Studio** or **Loom** to record your screen during a meeting.

## 🧪 How to Test

1. Clone this repo.
2. Open the `index.html` file in your browser.
3. Join the meeting.
4. Click on "Start Recording" (if billing is set up).
5. Share the meeting link with others to join.
   
## 🔐 Security

JWT is used to secure the Jitsi room and features like recording, transcription, etc. Please **do not share your JWT key publicly**.

## 🙋‍♂️ Author

**Abhishek Singh**  
Email: abhi211singh@gmail.com

