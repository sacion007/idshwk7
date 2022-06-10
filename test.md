通过PPT与Python文件中给出的。基于颜色的变换，来隐藏自己的学号、姓名在图片中
基于 LSBSteg.py
/usr/bin/python3 LSBSteg.py encode -i fourtwo.png -o practice13.png -f class.txt
通用代码：
python LSBSteg.py encode –i input.png -o output.png -f info.txt

信息的提取：
/usr/bin/python3 LSBSteg.py decode -i practice13.png -o what.txt
通用代码：
python LSBSteg.py decode –i output.png –o info.txt
