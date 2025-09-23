🌌 Aurora

A powerful Flutter-based AI assistant that blends ChatGPT, DALL·E, and voice control to help you stay organized, inspired, and hands-free. Speak naturally, and Aurora will answer your questions, generate images, or even talk back—all wrapped in a modern, minimalist interface.

🚀 Features

🤖 ChatGPT Conversations – Get intelligent, human-like responses in real time.
🎨 DALL·E Image Generation – Turn your prompts into stunning visuals instantly.
🎙 Voice Commands – Use speech-to-text to talk to Aurora effortlessly.
🔊 Text-to-Speech – Hear responses read aloud for hands-free convenience.
📱 Cross-Platform UI – Smooth performance and responsive design on Android and iOS.

🛠️ Tech Stack

| Component        | Details                                                                 |
|------------------|-------------------------------------------------------------------------|
| Language         | Dart                                                                    |
| UI Framework     | Flutter                                                                 |
| Architecture     | MVVM (with Provider/State Management as applicable)                     |
| Speech Input     | speech_to_text (real-time voice recognition)                            |
| Text To Speech   | flutter_tts (voice playback for AI responses)                           |
| AI Backend       | OpenAI API (ChatGPT for text, DALL·E for image generation)              |
| IDE              | Android Studio / VS Code                                                |
| Version Control  | Git & GitHub                                                            |
| Deployment Target| Android 13+, iOS 17+ (cross-platform support)                           |
| Networking       | HTTP package (for API calls and data fetching)                          |



📦 Installation

1.Clone the repository:

  git clone https://github.com/your-username/aurora.git

2.Navigate into the project folder:

  cd aurora

3.Install dependencies:

  flutter pub get

4.Add your OpenAI API key:

  Open openai_service.dart or your .env file and replace with your API key.

5.Run the app:

  flutter run

📸 Screenshots
Home Screen	Features
![Aurora Screenshot](ASSET/image.jpeg)

🧰 Troubleshooting

   Double-check API key and quota if requests fail.

   Ensure asset paths (pubspec.yaml) are correct.

   Verify internet connectivity for DALL·E image generation.

📝 License

   This project is licensed under the MIT License – feel free to fork, modify, and build upon Aurora.
