# 模块介绍
  通过我们提供的脚本文件```Batch_Conversion.bat```来对LabelMe标注完成的json文件处理，以生成我们所需的数据集格式文件。此外通过python脚本```Extract_Image.py```对转换完
  成的文件进行批量提取所需的label.png文件，重命名为其对应的文件夹名称，以生成语义分割网络模型所需的数据集格式。
# 依赖环境
  python == 3.8
  opencv-python
  labelme
