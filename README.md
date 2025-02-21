# PeerChat

PeerChat is a simple peer-to-peer (P2P) chat application that allows users to communicate directly with each other without the need for a central server. This application uses the PeerJS library, which abstracts WebRTC for easy implementation of real-time data channels.

## Features

- **Direct P2P Communication**: Connect directly with another peer using their unique Peer ID.
- **Real-Time Messaging**: Send and receive messages instantly.
- **No Server Required**: After initial setup, communication occurs directly between peers.

## Getting Started

### Prerequisites

- A modern web browser that supports WebRTC (e.g., Chrome, Firefox).

### Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd peerchat
   ```

2. **Open `index.html`**:
   - Simply open the `index.html` file in your web browser to start the application.

### Usage

1. **Open the Application**:
   - Open the `index.html` file in two different browser windows or tabs to simulate two peers.

2. **Get Your Peer ID**:
   - Each peer will be assigned a unique Peer ID, which will be displayed at the top of the page.

3. **Connect to Another Peer**:
   - Enter the Peer ID of the other peer in the input field and click "Connect".

4. **Start Chatting**:
   - Once connected, you can start sending messages to the other peer.

## Technologies Used

- **PeerJS**: A library that simplifies WebRTC peer-to-peer data, video, and audio.
- **HTML/CSS/JavaScript**: Basic web technologies for building the user interface and handling interactions.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the PeerJS library for making WebRTC easier to implement.
