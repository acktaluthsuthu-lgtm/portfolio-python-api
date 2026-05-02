# portfolio-python-api

**Name:** Ackta  Luthsuthu
**Roll Number:** 25BAD002

This project is a personal portfolio website that shows my details (name, title, bio, skills, GitHub link, and profile image) in a clean and responsive layout.  
The data is stored in **Supabase**, fetched through a **Python FastAPI backend**, and displayed on the frontend using **HTML, CSS, and JavaScript**.  
Everything is deployed online — backend on **Render** and frontend on **Vercel** — so the site works live without any hardcoding.

---

## What this project does
- Stores portfolio data in a Supabase database  
- Fetches data through a Python API (`/portfolio` endpoint)  
- Displays the data dynamically on the webpage  
- Keeps the design responsive and user-friendly  

---

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** FastAPI (Python)  
- **Database:** Supabase  
- **Deployment:** Render (backend), Vercel (frontend)  
- **Version Control:** GitHub  

---

## How to run it
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio-python-api.git
   cd portfolio-python-api

2. Install backend dependencies:
   '''bash
   pip install -r requirements.txt

3. Run the backend locally:

   '''bash
   uvicorn main:app --reload
4. Update the frontend script.js with your Render API URL.

5. Deploy backend on Render and frontend on Vercel.
