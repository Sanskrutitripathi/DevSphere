# Devsphere - Developer Hub

Devsphere is a comprehensive developer hub built using Django, designed to help developers create professional profiles, showcase their skills, and network with others. The platform allows users to sign up, log in, and build detailed profiles similar to LinkedIn, adding skills, projects, and connecting with other developers. With seamless database integration and API support, Devsphere aims to foster collaboration and community among developers.

## Features

- **User Authentication:**
  - Sign up and log in to access the platform securely.
  
- **Profile Creation:**
  - Create a personalized profile with detailed information including skills, projects, and more.
  
- **Skill Management:**
  - Add, update, and remove skills to highlight your expertise.
  
- **Project Management:**
  - Add projects to showcase your work, including descriptions and links.
  
- **Developer Discovery:**
  - View profiles of other developers, find new opportunities, and collaborate.
  
- **Database Integration:**
  - All user data, profiles, and interactions are stored securely in a database.
  
- **API Support:**
  - Integration with APIs for enhanced functionality and seamless data exchange.

## Installation

To set up the Devsphere project locally, follow these steps:

### Prerequisites

- Python 3.x
- Django
- SQLite (or any other database of your choice)

### Steps to Install

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/devsphere.git

2. Navigate into the project directory:

   ```bash
   cd devsphere

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

4. Apply the migrations to set up the database:

   ```bash
   python manage.py migrate

5. Create a superuser to access the admin panel:

   ```bash
   python manage.py createsuperuser

6. Run the development server:

   ```bash
   python manage.py runserver
