Plugin: Add Photos to QGIS
This plugin allows you to quickly and easily add multiple photos to a QGIS attribute table. Unlike other tools, this plugin lets you add many files at once instead of doing it one by one. Although the plugin interface is in Catalan, here's a step-by-step explanation of how it works..


Plugin Interface Overview
The graphical interface of the plugin includes the following elements:

<img width="258" height="253" alt="image" src="https://github.com/user-attachments/assets/39f757c0-ac6a-4018-ada4-5808c86b9656" />

1. Seleccionar capa (Select Layer)
Choose the layer in your QGIS project where you want to add the photos.

2. Columna Join (Join Column)
This is the column in your attribute table that will be used to match photo filenames.
For example, if the column contains an ID like LL01, and you have a photo named LL01.jpeg or LL01.pdf, the plugin will match them and add the photo to that row.
Important: The photo filenames must exactly match the values in this column (except for the file extension).

3. Nom nou camp (Name of New Field)
Enter the name of the new field where the photo paths will be saved in the attribute table.

4. Seleccionar carpeta (Select Folder)
Choose the folder that contains your photo or document files.

5. Format de document (Document Format)
Select the file format of your documents. Currently supported formats are:

PDF

PNG

JPEG

