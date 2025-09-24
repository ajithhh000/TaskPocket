💼 TaskPocket – Pocket Jobs Made Simple

TaskPocket is a React + Django + MongoDB platform that connects students and individuals with short-term, part-time jobs such as catering, loading/unloading, event staffing, and more.

It also empowers job coordinators/managers who can bring a group of workers for a job and earn commissions, making it easier for job providers to get reliable manpower on time.

🚀 Features

🧑‍🎓 For Individuals – Find flexible, part-time jobs and earn pocket money.

🧑‍💼 For Coordinators – Bring a group of workers to a job and earn commission.

🏢 For Job Providers – Post jobs and get manpower without hiring permanently.

🔍 Smart Matching – Search jobs by category, location, or duration.

📊 Dashboards – Separate dashboards for individuals, coordinators, and providers.

🔒 Secure Authentication – Role-based login for seekers, coordinators, and providers.

🛠 Tech Stack

Frontend: React + TailwindCSS
Backend: Django REST Framework (Python)
Database: MongoDB
Authentication: JWT-based role access
Deployment: Docker + (Heroku/Vercel/AWS planned)

📂 Project Structure
taskpocket/
│── backend/             # Django backend
│   ├── core/            # Main settings & config
│   ├── jobs/            # Job-related models & APIs
│   ├── users/           # Authentication & role management
│   └── requirements.txt
│
│── frontend/            # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/    # API calls
│   │   └── App.js
│   └── package.json
│
│── .gitignore
│── LICENSE
│── README.md

⚙️ Installation & Setup
1️⃣ Clone the repo
git clone https://github.com/<your-username>/taskpocket.git
cd taskpocket

2️⃣ Backend Setup (Django + MongoDB)
cd backend
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

3️⃣ Frontend Setup (React)
cd frontend
npm install
npm start


Runs at:

Frontend → http://localhost:3000

Backend → http://localhost:8000

📌 Roadmap

 User authentication with roles (Individual / Coordinator / Job Provider)

 Job posting & application system

 Commission-based workflow for coordinators

 Job categories & filters

 Notifications & reminders

 Payment integration (future)

 Admin dashboard for monitoring

🤝 Contributing

Contributions are welcome! 🎉

Fork the repo

Create a feature branch (git checkout -b feature-name)

Commit changes and push

Open a Pull Request

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details
