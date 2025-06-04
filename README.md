#Denoise App
#Overview
##The Denoise App is a MATLAB-based application designed to reduce noise in images while preserving important details. Utilizing advanced filtering techniques, this app provides an intuitive interface for users to enhance their images effectively.

##Features
##Wiener Filter: Implements the Wiener filter to adaptively reduce noise based on local statistical properties of the image.
User-Friendly Interface: Simple controls for loading images, applying denoising, and viewing results.
##Image Format Support: Supports various image formats for input and output.
##Real-Time Processing: Allows users to see the effects of denoising in real-time.
##Installation
Clone the repository:
bash

Copy Code
git clone https://github.com/papajo/denoise_app.git
Navigate to the project directory:
bash

Copy Code
cd denoise_app
Open the app in MATLAB:
matlab

Copy Code
run('denoise_app.m')
Usage
Load an image using the provided interface.
Adjust any necessary settings for the denoising process.
Click the "Denoise" button to apply the filter.
View the denoised image and save it if desired.
Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

##To run the application locally, you would typically follow these steps:

Ensure Python and pip are installed on your system.
Clone the repository (or ensure you have the denoise_app directory and requirements.txt from the solution).
Navigate to the project directory in your terminal (the directory containing requirements.txt and the denoise_app folder).
Create a virtual environment (recommended):
python -m venv venv
Activate it:
On Windows: venv\Scripts\activate
On macOS/Linux: source venv/bin/activate
Install the dependencies:
pip install -r requirements.txt
Run the Flask application:
python denoise_app/app.py
Open your web browser and go to the address shown in the terminal, which is usually http://127.0.0.1:5000/.
You should then see the image upload page.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

