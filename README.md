                  Django Upload, View, and Delete Files Project
                  -----------------------------------------------
This project is a simple Django application for uploading, viewing, and deleting files. It demonstrates CRUD functionality with file handling in Django.

Features:
---------
File Upload: Users can upload files through a form, which are then stored on the server. The app checks if a file already exists to prevent duplicates.
File Display: Uploaded files are displayed on the home page, allowing users to view all files currently stored.
File Deletion: Users can delete specific files, with confirmation messages indicating successful deletion.

Technologies Used:
------------------
Django: Web framework for building the application.
HTML/CSS: Front-end form and display.
SQLite: Default database for storing file metadata.
Messages Framework: Provides user feedback on actions like upload success or deletion.

Code Overview:
---------------
Views: Includes home, uploadfile, and deletefile views. The home view displays the form and file list, uploadfile handles the upload logic, and deletefile removes files both from the server and database.
Models: Uses a model to store file metadata, such as the file name and path.
Forms: Utilizes Django forms for file upload.

Conclusion:
---------------
This project demonstrates essential file management features within a Django application, covering the full CRUD cycle with user-friendly feedback.
It is a helpful starting point for anyone looking to integrate file handling into a Django project, with the potential for further customization like adding user authentication, file type restrictions, or file previews.
This application provides a simple and efficient way to manage files on the server and can be expanded to fit more complex needs.
