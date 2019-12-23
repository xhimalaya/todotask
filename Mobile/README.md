# commands for run
#inside mobile folder
flutter pub get 
flutter doctor
flutter run

#inside api folder
#activate your virtualenv
python3 -m pip intall -r req.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
