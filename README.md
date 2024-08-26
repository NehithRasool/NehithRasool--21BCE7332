Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python (version 3.6 or higher)
- Node.js and npm (for Socket.IO installation)

### Cloning the Repository

To clone the project to your local machine, run the following command in your terminal:

```bash
git clone https://github.com/NehithRasool/chess_game.git
```

Replace `yourusername` with your actual GitHub username.

### Installation

Navigate to the project directory:

```bash
cd chess_game
```

Create a virtual environment (recommended):

```bash
python3 -m venv venv
```

Activate the virtual environment:

- On Windows:

    ```bash
    venv\Scripts\activate
    ```

- On macOS/Linux:

    ```bash
    source venv/bin/activate
    ```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Install Socket.IO:

First, install `node` and `npm` if not already installed. Then, install Socket.IO:

```bash
npm install socket.io
```

### Running the Server

To run the Python server, execute the following command:

```bash
python server.py
```

Open your web browser and navigate to `http://localhost:5000` to start playing.

