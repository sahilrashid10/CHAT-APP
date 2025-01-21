# Chat Application

This is a simple chat application built using **Socket Programming** and **Flask**. It allows real-time communication between users over a network, with an interactive web interface.

## Features

- **Real-time Messaging**: Exchange messages instantly between users.
- **Dynamic UI**: HTML templates for home and chat room interfaces.
- **Socket Integration**: Real-time communication with WebSocket via Flask-SocketIO.
- **Scalable Design**: Easily extendable to add new features.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/chat-app.git
   cd chat-app
   ```

2. Set up a Python virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start the Flask server:
   ```bash
   python app.py
   ```

5. Open your browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

---

## Usage

1. Run the server as described above.
2. Navigate to the home page to:
   - Enter a username.
   - Join an existing chat room using a room code.
   - Create a new chat room.
3. Enter the chat room and start sending messages in real time.

---

## Folder Structure

```
chat-app/
├── app.py               # Main Flask application
├── static/              # Static files (CSS, JS, images)
├── templates/           # HTML templates
│   ├── base.html        # Base template with shared structure
│   ├── home.html        # Home page for room creation/joining
│   └── room.html        # Chat room interface
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## HTML Templates

### Base Template (base.html)
- Provides the foundational layout for all pages.
- Includes links to the CSS stylesheet and Socket.IO script.

### Home Page (home.html)
- Contains a form to join or create chat rooms.
- Displays error messages if any issue occurs while joining a room.

### Chat Room (room.html)
- Displays the chat room interface.
- Includes a text input for messages and a message display area.
- Uses JavaScript to handle message sending and rendering.

---

## Requirements

- Python 3.7+
- Flask
- Flask-SocketIO

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## Future Improvements

- User authentication and registration.
- Persistent chat history using a database.
- File sharing capabilities.
- Deployment on cloud platforms.

---

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch-name
   ```
5. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgements

- Flask for providing an easy-to-use web framework.
- Flask-SocketIO for enabling WebSocket communication.
- Open-source community for valuable resources and inspiration.

