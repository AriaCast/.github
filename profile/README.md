# Welcome to AriaCast 🎵✨

AriaCast is a high-performance, open-source casting protocol designed to deliver seamless audio (and video) streaming across devices, with a specialized focus on deep integration with **Music Assistant**.

Whether you're looking for an alternative to traditional casting protocols (like Chromecast or AirPlay) or want a highly customizable streaming solution, AriaCast is built with performance, low latency, and ease of use in mind.

## 🌟 What is AriaCast?

AriaCast operates on a client-server architecture to provide robust cast functionality over local networks. It uses a custom UDP discovery protocol and WebSockets to achieve high-performance streaming.

Our ecosystem consists of several interconnected pieces:
- **Zero-Config Discovery:** Clients automatically discover AriaCast receivers on the local network via UDP.
- **High-Performance Audio & Video:** Uses WebSockets for low-latency media and control streaming.
- **Music Assistant First:** Natively integrated with Music Assistant for a flawless smart home audio experience.

## 🛠️ Tech Stack

We love fast and reliable technologies:
- **Backend/Networking:** Go (Golang)
- **Smart Home Integration:** Python 
- **Mobile/Client:** Kotlin/Java (Android)

## 🚀 Getting Started

- If you want to run an AriaCast receiver on your Music Assistant just add it, and download the App
- The Go server can be cross-compiled for any platform (Windows, macOS, Linux, and Raspberry Pi ARM architectures).

## 🤝 Contributing

We welcome contributions from the community! Whether it's squashing bugs, improving audio/video synchronization, or adding support for new platforms, we'd love your help.

1. Fork the repository you want to work on.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.
