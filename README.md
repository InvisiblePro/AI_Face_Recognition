# AI_Face_Recognition    [![](https://img.shields.io/badge/Language-Python-blue?logo=python&style=for-the-badge)](https://www.python.org/)

### This is an AI based project which specifically on `Computer Vision` domain.
Must read [Security.MD](https://github.com/InvisiblePro/AI_Face_Recognition/blob/master/SECURITY.md) and [LICENSE](https://github.com/InvisiblePro/AI_Face_Recognition/blob/master/LICENSE)

#### _This Repository contains program which detects faces from its database and keeps record in "output_data" folder._

> Moudules reuired:
 
    -opencv-contrib-python
    -pillow
 <br/>
 
 
 
Just download the `Downloads.zip` file or `(https://github.com/InvisiblePro/AI_Face_Recognition.git)` and install all requirements from `startup.bat` file and get your model ready!..
<br/>

### Steps to follow:-

1. First install all pre-requirements using these command-- `pip install -r requirements.txt`.

2. After installing all modules, first run `data_collector.py` which ask `Face ID:` you can set it as 0,1,2,3.... then a pop-up window opens and starts capturing your face pictures.

3. Now run `modelTrainer.py` file to train your model.

4. Now get into the code of `face_recognition.py`, search for  
```python
names=['person1','person2'] # give these names as same array index as of Face ID:
```

5. Now, just run this file, you will see your face getting detected on screen.

6. After closing window by pressing `escape` key, you will get `output_data` folder in which you will find a recording of camera and 2 log files.

7. Great! If you haven't get any errors.....    You are done 👍🏻👍🏻

<br/>
<hr>

[<img src="https://img.shields.io/badge/GitHub-InvisiblePro-blue?logo=github&style=for-the-badge" alt="InvisiblePro">](https://github.com/InvisiblePro)
