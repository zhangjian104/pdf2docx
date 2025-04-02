# pdf2docx
图片型Pdf转docx应用。

**思路**
1.将pdf转为一张张的图片
2.paddlex将图片OCR，得到结构化描述JSON
3.简化结构化描述JSON为提示词，通过大模型判断布局信息
4.根据布局信息，将结构化描述JSON转化为真实的布局描述
5.根据布局描述，将图片转为docx

# pdf2docx
image_based pdf to docx application.


**idea**
1. Convert the PDF into individual images.
2.Use PaddleX to perform OCR on the images and generate structured JSON descriptions.
3.Simplify the structured JSON into prompts and use a large model to determine layout information.
4.Based on the layout information, transform the structured JSON into actual layout descriptions.
5.Convert the images into a DOCX file according to the layout descriptions.

