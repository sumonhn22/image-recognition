<p align="center">
   <b>Image Recognition App </b> <br/>
In this project, you can learn how to build an app for Image Recognition using FastAPI and Heroku.
</P>

## Installation
Run my Project

```bash
  git clone https://github.com/bhimrazy/Image-Recognition-App-using-FastAPI-and-PyTorch
  cd Image-Recognition-App-using-FastAPI-and-PyTorch
  python -m venv venv
  source venv/bin/activate
  pip install -r requirements.txt
  uvicorn main:app --reload
```
## Image Recognition App using FastAPI and PyTorch: TODO
- [x] Create a virtual environment
- [x] Create FastAPI App
    - Install fast API
    - Install Uvicorn
    - Install Pytest
    - Install Jinja2
    - Install python-multipart
    - Install requests
    - Create a main file with some routes
    - Create a main test file to test the home page route

- [x] Pytorch Setup
    - Install torch & torchvision (use cpu version for small size)

- [x] Prediction 
    - Create a predict post route
    - Create a file utils.py
    - Test predict route
    - Create some helper function
    - Put some test images inside static folder
    - Create a test to upload an image in predict route
    - Predict

- [x] Create a home page for prediction
    - Create an index.html file inside the templates directory
    - Setup template and static directory in the main app
    - Initial HTML for home page
    - Use Tailwind CSS cdn link for css
    - Google Fonts
    - Create a form to predict
    - update homepage route for prediction
    - Update UI of the page
    - Add Some javascript to autoload the image
    - Add logo and favicon
    - Add meta tags
    - Add response image for preview as base64 data

## 📚 RESOURCES:
◆ PyTorch: https://pytorch.org/tutorials/intermediate/flask_rest_api_tutorial.html <br/>
◆ FastAPI: https://fastapi.tiangolo.com

## Author
- [@sumon](https://www.github.com/sumonhn22)
