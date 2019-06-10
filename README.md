# webcam-eye-tracker

# 起動

```
python webcam-eye-tracker.py
```

# TODO

- [ ] 目の位置を取得するように変更
- [ ] UDP通信をできるようにする
- [ ] 起動オプションでカメラを選択できるようにする
- [ ] 起動オプションでUDP通信を選択できるようにする

# 元になっているソースコード

https://pysource.com/2019/03/12/face-landmarks-detection-opencv-with-python/

# Dlibのインストール (for Windows)

1. CMakeのインストール https://cmake.org/download/
2. VS 2019のインストール https://visualstudio.microsoft.com/ja/vs/
3. https://sourceforge.net/projects/boost/files/boost-binaries/1.70.0/boost_1_70_0-msvc-14.0-64.exe/download
4. https://www.kunihikokaneko.com/tools/win/vs2019.html
5. x64 Native Tools コマンドプロンプトを開く
6. `git clone https://github.com/davisking/dlib.git`
7. `python setup.py install`
