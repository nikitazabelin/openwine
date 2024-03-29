# Openwine.co.il (2018-2019 version)

Openwine.co.il is an e-commerce store built using Python/Django engine for the backend. The main purpose of the project was to build a self-made backend solution. The core engine used for the project was taken from @CodingMedved, with the developer making their own improvements and additions. 

The main challenge for me was with the frontend, specifically with Javascript. Although the site is fully functional, the developers ultimately chose to take a WIX solution for the final product.

## Files and Folders

The following are the files and folders included in this Django project:

- `openwinetlv1/__pycache__`: Contains cached python files generated by the interpreter.
- `orders`: Contains files related to order processing.
- `products`: Contains files related to product management.
- `static`: Contains static files (CSS, JS, images, etc.).
- `templates`: Contains HTML templates used for rendering views.
- `utils`: Contains utility files used throughout the project.
- `.gitignore`: Specifies which files/folders to ignore when pushing changes to the repository.
- `README.md`: This README file.
- `db.sqlite3`: The SQLite database used by the project.
- `manage.py`: Django's command-line utility for administrative tasks.

## Getting Started

To deploy Openwine.co.il on your local server, follow these steps:

1. Clone the repository to your local machine using `git clone https://github.com/hebrewbug/openwine.git`.
2. Install the required packages by running `pip install -r requirements.txt`.
3. Create a superuser by running `python manage.py createsuperuser` and following the prompts.
4. Migrate the database schema by running `python manage.py migrate`.
5. Start the development server by running `python manage.py runserver`.
6. Open your web browser and navigate to `http://127.0.0.1:8000/admin` to access the admin dashboard, or `http://127.0.0.1:8000/` to access the site.

To run the project with a local web server, you can use a tool like XAMPP or WAMP. Here are the steps to follow with XAMPP:

1. Download and install XAMPP from the official website.
2. Navigate to the XAMPP installation folder and open the `htdocs` folder.
3. Copy the `openw` folder (the one you cloned from GitHub) to the `htdocs` folder.
4. Launch XAMPP and start the Apache and MySQL services.
5. Open your web browser and navigate to `http://localhost/openw/` to access the site.

Note: This project is intended for educational purposes only and is not suitable for production use without further development and security hardening.
