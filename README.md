**Requirements**


Before running the Django app, you need to have the following installed:

    Python 3.x

    Django

You can install Django using pip if it's not installed yet:

pip install Django


**Setup &Installation**

Follow these steps to get the app running on your computer:

**"1.Clone the Repository"**


First, download the project to your computer by running this command:

git clone https://github.com/Pavan-KumarGaddam/Week5_SAD_Assignment.git

**2. Go to Your Project Folder**

Once the project is downloaded, go to the project directory by running:

cd hello_world_project

**3. Create a Virtual Environment (Optional but Recommended)**

It's a good idea to keep your project’s dependencies in a separate environment. Here's how to create one:

python -m venv venv

Now, activate the virtual environment:

    On Windows: venv\Scripts\activate

    On macOS/Linux: source venv/bin/activate

**4. Install Django**

Once the virtual environment is active, install Django using this command:

pip install django

**5. Run Migrations**

Before starting the server, ensure all necessary database migrations are applied. Run the following command:

python manage.py migrate

**6. Run the Server**

Now, you're ready to start the Django server. Run:

python manage.py runserver
![WhatsApp Image 2025-04-26 at 5 28 01 PM](https://github.com/user-attachments/assets/f71da825-4ce0-4d5c-8401-bcad330fb923)


**7. Access the App**

Open your browser and go to this URL:

http://127.0.0.1:8000/hello

You should see this message:

{
  "Message": "Hello World!"
}

![WhatsApp Image 2025-04-26 at 5 13 15 PM](https://github.com/user-attachments/assets/2cf97f7d-1c35-4e0e-8de8-7289c436dabb)
