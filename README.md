# 💬 Chatterly

Chatterly is a simple real-time chat application built with **Django**.  
Users can join or create chat rooms by entering a room name and username, and chat instantly with others in real time.

---

##  Features
- Real-time messaging (no page reload)
- Create or join chat rooms easily
- Multiple users chatting at once
- Simple and clean user interface

---

##  Tech Stack
- **Backend:** Django
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** SQLite (default)  


---
##  How It Works

Enter your username and a room name.

If the room doesn’t exist, it’s created automatically.

Start chatting in real time with others in the same room.

---


##  Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/chatterly.git

# Go to project folder
cd chatterly

# Create virtual environment
python -m venv env
env\Scripts\activate       # On Windows
source env/bin/activate    # On Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate


# Start the server
python manage.py runserver
