🛡️ Aegis – AI-Powered Shield Against NSFW Content

Aegis is a browser extension that uses Deep Learning (TensorFlow.js) to detect and filter NSFW content—including nudity, sexual content, gore, and blood—in real time while you browse.
Built for safer surfing, Aegis combines AI-driven computer vision with a lightweight web extension to protect users from harmful visuals on the internet.

✨ Features

🚫 Multi-category Detection → Detects nudity, sexual content, gore, and violent imagery.

⚡ Real-time Protection → Scans and filters images directly on webpages.

🛡️ Auto-blur/Hide → Instantly blurs or removes unsafe content.

🌐 Cross-Browser Support → Works on Chrome, Edge, and Firefox.

🎛️ Customizable → Adjustable sensitivity and filter preferences.

🛠️ Tech Stack

Python (TensorFlow/Keras) → Model training

TensorFlow.js → In-browser inference

JavaScript, HTML, CSS → Extension frontend + background scripts

WebExtension API → Cross-browser integration

🚀 Installation

Clone this repository:

git clone https://github.com/yourusername/aegis-nsfw-filter.git
cd aegis-nsfw-filter


Install dependencies for model training (optional if using pre-trained model):

pip install tensorflow keras numpy matplotlib


Build/convert trained TensorFlow model to TensorFlow.js:

tensorflowjs_converter --input_format=tf_saved_model ./model ./web_extension/model


Load the extension in your browser:

Open chrome://extensions/ → Enable Developer Mode → Load unpacked → Select web_extension/.

🖼️ Demo (Example)


(This will show a webpage before & after Aegis filters unsafe content)

📌 Future Enhancements

🎥 Extend support to videos & GIFs.

📊 Dashboard with detection statistics.

👤 User profiles with parental controls.

🌍 Multi-language support for global accessibility.

🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to improve.

📜 License

MIT

🌟 Acknowledgments

TensorFlow.js team for enabling in-browser deep learning.

Open-source NSFW datasets for model training.

👉 Aegis isn’t just another filter—it’s your AI-powered shield for a safer internet.
