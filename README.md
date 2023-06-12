# license_plate_recognition_using_yolo8_&_easyocr

## steps

### 1. git clone https://github.com/kiranpradeepk/license_plate_recognition_yolo8.git
### 2. cd into the repository
### 3. pip install -r .\requirements.txt
### 4. download the model: https://drive.google.com/file/d/136xPCImSitdkKiyc2hHmWOvbjkyRfSUQ/view?usp=sharing (train.pt --> repository folder)
### 5. execute the main program: python main.py model=train.pt source="test_pic.jpg" show=True

## troubleshooting

### yolo versions above 8.0.0 might not be compatible.
### if so..
###         pip uninstall ultralytics
###         pip install ultralytics==8.0.0
