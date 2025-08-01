**AutoEngage: An Advanced Voice-to-Voice Chatbot**

https://www.loom.com/share/f54f4016a4df4bb3935d14a2054a6c54?sid=9dae9b21-e51a-457f-932e-7bf1a646bee2

This project allows you to interact with a powerful voice-driven chatbot named **AutoEngage**. 

## Project Setup

AutoEngage relies on several external libraries to function. To simplify the process, a handy `setup.sh` script automates the installation. Follow these steps to get AutoEngage up and running:

## Prerequisites

Before we begin, ensure you have the following software installed:

- **Conda:** This tool helps manage virtual environments, keeping autoengage's dependencies isolated from your system.
- **Bash:** The script utilizes bash commands, so having a bash shell available is crucial.
- **Git:** We'll use Git to clone the project code from a version control system.

## Setup Instructions

### Step 1: Clone the Repository

Use the following commands in your terminal to download the autoengage project files:

```bash
git clone https://github.com/sobersalman/autoengage.git
cd autoengage
```

### Step 2: Run the Setup Script

Next, execute the setup.sh script to install the necessary dependencies:

```bash
setup.sh
```

This script automates the installation process, saving you time and effort.

### Step 3: Start the Application

Once the setup is complete, you can launch autoengage by running the Flask application:

```bash
python app.py
```

This command starts the Flask web framework powering autoengage.
