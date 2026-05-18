# Huddle - Event Hosting Platform

A comprehensive website for hosting and managing gatherings with powerful features.

## ✨ Features

- **User Management** - Secure authentication and profile management
- **Event Management** - Create, update, and organize events
- **Booking System** - Complete booking lifecycle management
- **Online Payments** - Secure payment processing
- **Reviews & Ratings** - User feedback system
- **Advanced Search** - Powerful filtering and discovery
- **Notifications** - Reminders and confirmations
- **Recommendations** - Personalized event suggestions
- **Community Features**:
  - Chat Channels
  - Non-AI Chatbot
- **Gamification** - Rewards and engagement systems

## 🚀 Manual Setup (UNIX Systems)

```bash

# Frontend
# Run the automated setup script
bash setup.sh

# Install core React dependencies
npm install react@18.2.0 react-dom@18.2.0

# Install required packages
npm install axios react-router-dom @mui/material @emotion/react @emotion/styled \
@mui/icons-material @mui/lab react-bootstrap bootstrap react-chatbot-kit \
dayjs moment-timezone @mui/x-date-pickers react-credit-cards-2 \
react-infinite-scroll-component @kiwicom/orbit-components bad-words \
@fullcalendar/react @fullcalendar/daygrid @fullcalendar/timegrid \
@fullcalendar/interaction @fullcalendar/bootstrap @fortawesome/fontawesome-free \
card-validator react-qr-code

#Backend
# Create and activate virtual environment
python3 -m venv huddle_env
source huddle_env/bin/activate

# Install Python dependencies
pip install -r requirements.txt

# If psycopg2 installation fails:
sudo apt-get install python3-dev libpq-dev postgresql-client

#Database

# Install PostgreSQL (if not already installed)
sudo apt install postgresql postgresql-contrib
sudo service postgresql start

# Create database user (replace with your details)
sudo -u postgres createuser -P huddle_user
sudo -u postgres createdb -O huddle_user huddle_db

<img width="1200" height="1280" alt="image" src="https://github.com/user-attachments/assets/bcec2877-8d7f-4b9d-af9a-7eadfd49104c" />
<img width="1829" height="753" alt="image" src="https://github.com/user-attachments/assets/f5fe405d-9f34-4c84-b2d5-108d541f4c03" />
<img width="1830" height="1365" alt="image" src="https://github.com/user-attachments/assets/4e85b996-9730-42dc-9d28-04150c9cc31b" />
<img width="1864" height="1500" alt="image" src="https://github.com/user-attachments/assets/deb1ae35-1256-4152-8f5a-445899c09327" />
<img width="1200" height="958" alt="image" src="https://github.com/user-attachments/assets/83e26bea-c21e-4c6e-977e-341dccf68f57" />
<img width="1737" height="1086" alt="image" src="https://github.com/user-attachments/assets/3ce315dd-51eb-421f-96a3-893a287dc15e" />







