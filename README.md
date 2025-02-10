1. Pull the project from the repo.
2. Create the virtual environment using below commands
     1. python -m venv {name}
     2. Source {venv-name}/bin/activate
3. Run the command to install dependence for Django project.
     pip install -r requirements.txt

4. Please find the below commands to check and run project.
     1. django-admin --version (To check django version)
     2. python manage.py runserver (To run the python django project)
  
     3. python manage.py makemigrations (To create migration file for the updated model file)
     4. python manage.py migrate (To updated migration file in the DB)
  
     5. pip install faker (To generate the demo data in the DB)
