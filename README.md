(1).安装dlib
1. 下载dlib18.16（或其他版本，此处用的是.16）
https://github.com/davisking/dlib/releases/download/v18.16/dlib-18.16.tar.bz2
2. 解压文件（用tar或者直接使用资源管理器解压）。
3. 终端中定位到dlib-18.16的python_examples文件夹内。
cd dlib-18.16/python_examples
4. 运行下面的命令：
mkdir build
cd build
cmake ../../tools/python
cmake --build . --config Release
cp dlib.so ..


(2).安装face_recognition
pip install face_recognition


(3) 人脸识别
python identify_and_draw_boxes_on_faces.py
# demo
