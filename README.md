# lukaswalch-website
A small and simple portfolio website. Does not use Cookies, Session Storage or
Local Storage. Runs on the Django Framework and Python.<br />
[Lukas Walch Website](https://lukaswalch.at)

### Requirenments
python-dotenv==0.15.0\

### Environment Variables
Application settings are stored in a .env file and imported to Django
settings.py

##### Content of the .env file
  * SECRET_KEY=Your Django Secret Key from the settings.py
  * DEBUG=False
  * ALLOWED_HOSTS=server IP and allowed domains (seperated with ',')
  * SECURE_SSL_REDIRECT=True