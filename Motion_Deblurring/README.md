#### Download the Datasets
- Gopro [[gdrive](https://drive.google.com/file/d/1y_wQ5G5B65HS_mdIjxKYTcnRys_AGh5v/view?usp=sharing), [Baidu](https://pan.baidu.com/s/1eNCvqewdUp15-0dD2MfJbg?pwd=ea0r)]
- HIDE [[gdrive](https://drive.google.com/file/d/13CoUG0YktPGzVagOipoo43NMZclOG7J2/view?usp=sharing), [Baidu](https://pan.baidu.com/s/1F70f040UWAaeofSie_zMow?pwd=c8lv)]

#### Download the model [here](https://drive.google.com/drive/folders/1Wr37_23o7zZIwmniE1IeE-cch9pBImRD?usp=sharing)

#### Testing on GoPro
~~~
python main.py --mode test --data_dir your_path/GOPRO --test_model path_to_gopro_model --save_image True
~~~
#### Training on GoPro
~~~
python main.py --mode train --data_dir your_path/GOPRO
~~~

