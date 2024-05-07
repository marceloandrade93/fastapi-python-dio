
# FastAPI Directly from COLAB [DIO]

A script to run fastapi directly from Google Colab, getting an .xlsx from my drive to read it back directly in the browser via ngrok.

## Informations

The only thing you need to run directly from Colab, as it stands, is your own **authtoken** from [ngrok](https://ngrok.com/):


![App Screenshot](https://github.com/marceloandrade93/fastapi-python-dio/blob/main/files/screenshot_1.png?raw=true)


Once you have the authtoken, inside the colab, change the field indicated with your generated token.

![App Screenshot](https://github.com/marceloandrade93/fastapi-python-dio/blob/main/files/screenshot_2.png?raw=true)


If you want to use another .xlsx file from your drive, you can change the part after “&id[...]”, as it downloads the file directly from the driver and renames it to the default.

![App Screenshot](https://github.com/marceloandrade93/fastapi-python-dio/blob/main/files/screenshot_3.png?raw=true)


