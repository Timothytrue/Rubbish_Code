JPEGCODE.txt： 压缩系数为3的lena图像所得的二进制JPEG编码文件
	示例JPEGCODE.txt所选图片为lena，压缩系数为3

lena.bmp：512×512灰度图像。
GraySample.bmp：768×512灰度图像。

BMP2JPEG.m：编码主文件
code_category_AC.m：根据JPEG推荐的亮度直流霍夫曼编码表进行AC系数Huffman编码。

JPEGdecode.m：解码主文件
DCdecode.m: DC解码文件
ACdecode.m：AC解码文件
decode_category_AC.m：反求亮度直流霍夫曼编码表对应的AC系数Huffman编码
izigzag.m：反Zig-zag扫描