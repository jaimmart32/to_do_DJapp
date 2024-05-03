# To do app
A django to do list app. Users can create tasks, update them, delete them and mark as completed.

# Steps to Deploy on Localhost:

Clone the Repository: Begin by cloning the repository containing your Django app onto your local machine. You can do this using Git with the following command:
bash

git clone <repository_url>
Navigate to the Project Directory: Use the terminal or command prompt to navigate to the directory of your Django project:
bash

cd <project_directory>
Create a Virtual Environment (Optional but Recommended): While not strictly necessary, it's a good practice to create a virtual environment for your Django project to isolate its dependencies. You can create a virtual environment using:

python -m venv myenv
Activate the Virtual Environment: Activate the virtual environment you just created. On Windows, you can do this with:

myenv\Scripts\activate

On Unix or MacOS, you can do this with:
source myenv/bin/activate

Install Dependencies: Once your virtual environment is activated, install the dependencies required by your Django project. You can typically do this by running:

pip install -r requirements.txt

Run Migrations: Before starting the server, apply any database migrations required by your Django app. You can do this with:

python manage.py migrate

Start the Development Server: Finally, start the Django development server to run your app locally. Run the following command:

python manage.py runserver

Access Your App: Once the server is running, you can access your Django app by opening a web browser and navigating to http://localhost:8000 or http://127.0.0.1:8000
