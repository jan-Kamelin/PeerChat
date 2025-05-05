# PeerChat

PeerChat is a simple, peer-to-peer chat application that enables users to connect with each other directly using a unique 4-digit ID. It uses WebRTC for communication and PeerJS to establish connections between peers. The app allows for real-time messaging without needing a central server or account registration.

## Features

- **Peer-to-peer messaging**: Communicate directly with another user without relying on a central server.
- **4-digit ID generation**: Each user can create a unique 4-digit ID for connecting with others.
- **Real-time chat**: Send and receive messages instantly.
- **Copyable chat link**: Easily copy your chat link and share it with anyone you want to connect with.
- **Mobile responsive**: The app is designed to work smoothly on mobile devices.
- **No account required**: No need to sign up or create an account. Just generate an ID and start chatting!

## Technologies Used

- **WebRTC**: A set of APIs that enable peer-to-peer communication directly between browsers, without needing a server as an intermediary.
- **PeerJS**: A simple wrapper around WebRTC to handle peer-to-peer connections more easily.
- **HTML, CSS, JavaScript**: Core technologies for building the user interface and functionality.

## Getting Started

Follow these steps to get PeerChat up and running.

### Prerequisites

- A modern web browser that supports WebRTC (e.g., Google Chrome, Mozilla Firefox, Safari, or Microsoft Edge).
- A stable internet connection.

### Setup

1. **Clone the repository or use the app online**:
    - If you're hosting it yourself, clone the repository:
    ```bash
    git clone https://github.com/yourusername/PeerChat.git
    ```
    - Open the `index.html` file in your browser.

2. **Generating Your 4-Digit ID**:
    - Upon opening the app, you'll be prompted to create a 4-digit ID.
    - The ID should be numeric and 4 digits long. You’ll be asked to enter this ID once you load the page.

3. **Share Your ID**:
    - After generating your ID, you'll be provided with a unique URL link. Click the "Copy My Chat Link" button to copy the link to your clipboard.
    - Send this link to anyone you want to chat with. They can use the link to join your chat.

4. **Connecting to a Peer**:
    - Enter the 4-digit ID of the peer you want to connect with into the "Connect to ID" field.
    - Click "Connect" to initiate the connection. You’ll be able to chat once the connection is established.

5. **Start Messaging**:
    - Type your message in the "Message" input field and click the "Send" button to send your message.
    - Messages will appear in real-time in the message display area.

## How It Works

1. **Peer Generation**: When a user first opens the app, a unique 4-digit ID is generated via PeerJS. This ID allows others to connect to the user by using the ID in the connection form.
   
2. **Establishing Connection**: The connection is made using WebRTC. The user shares their link or ID with others, and they can input the ID to connect.
   
3. **Messaging**: Once the connection is made, users can exchange text messages in real time. Each message appears with a timestamp.

4. **WebRTC & PeerJS**: The app uses PeerJS to handle the complexities of WebRTC signaling, which helps establish and manage the peer-to-peer connection between users.

## Mobile Responsiveness

The application is optimized for both desktop and mobile devices. On smaller screens, the layout adjusts automatically for better usability. Buttons and input fields are responsive to different screen sizes.

## Troubleshooting

- **No connection**: Ensure both peers have entered valid 4-digit IDs. If one of the peers is not reachable, check if they have a stable internet connection.
- **Error handling**: PeerJS will display error messages if something goes wrong with the connection. If there is an issue, the app will show an alert with the error message.

## Potential Issues

- **Network Configuration**: WebRTC may not work well in all network environments. If either user is behind a restrictive firewall or NAT (Network Address Translation), WebRTC connections might fail.
- **Browser Support**: The app uses WebRTC, which is supported by most modern browsers but might not work in outdated versions or some lesser-known browsers.

## Contributing

If you want to contribute to the development of PeerChat, feel free to fork the repository and submit pull requests with your changes. If you find a bug or have an enhancement suggestion, please open an issue.

### How to Contribute:

1. Fork the repository on GitHub.
2. Clone your fork to your local machine:
    ```bash
    git clone https://github.com/yourusername/PeerChat.git
    ```
3. Make your changes in a new branch.
4. Commit your changes:
    ```bash
    git commit -am "Add new feature or fix bug"
    ```
5. Push your changes to your fork:
    ```bash
    git push origin your-branch
    ```
6. Open a pull request to the main repository.

## License

PeerChat is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- **PeerJS** for making WebRTC easier to implement.
- **WebRTC** for providing the underlying technology for peer-to-peer communication.
- **Font Awesome** for the icons used in the app.
