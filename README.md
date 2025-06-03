# WPS for Mac JS for PPTsci  

一句话介绍该代码功能：**Mac版WPS软件实现ppt自动增加图片标签（ABCDEFG等）和图片下方增加图片标题**  

🧾 代码简介  

**你经常感觉做PPT吃力么？**    

制作PPT是每个研究生必须快速掌握的能力，而PPT又是排版实验图片中最方便快捷的工具  

而目前搜索到的资源中，在Windows系统中Powerpoint中存在PPT插件，给大家推荐小红书Achuan-2大佬  

而自己的电脑是Macbook，且以前使用频率最高的就是WPS，未能找到自己想要的插件  

因此写了这个代码  

该代码是WPS for Mac平台的 JavaScript 宏脚本  

🎯 核心功能  

1. **自动增加每一页PPT中图片标签**
   
   在每张图片的左上角自动增加图片标签ABCDEFG等。

   **SciAddTag**
   
3. **动态添加文本框**
   
   在每张图片的正下方生成一个文本框，内容标配是“图片内容”，可以进一步自定义修改。

   **SciPicID**

**📌 注意事项**。

1.相关代码说明内容，中文标注在代码中，如遇到标签位置不对、字体有特别需求等情况，调整代码中相应内容即可。  

  **尤其要注意标签位置，需要按照特定图片修改（未来想想怎么解决这个问题）**  
  
2. 确保系统安装 **微软雅黑** 和 **Arial** 字体，否则可能回退至默认字体（如“宋体”或“Times New Roman”）。
     
3. 文本框宽度默认与图片一致，高度固定为 20 像素。可根据需求动态调整。

 🚀 快速上手  
 
1. 打开 WPS for Mac，新建或打开一个 PPT 文件。
   
2. 插入图片并保存。
   
3. 打开宏编辑器（`开发工具` > `宏`），分别粘贴本脚本。
<img width="696" alt="截屏2025-06-03 23 28 16" src="https://github.com/user-attachments/assets/0954f133-b299-4516-b576-b25f65a45e2f" />
<img width="935" alt="截屏2025-06-03 23 37 22" src="https://github.com/user-attachments/assets/431522f8-94d0-4583-a1e3-e4c7102390f5" />

4.保存
<img width="244" alt="截屏2025-06-03 23 38 17" src="https://github.com/user-attachments/assets/bd255768-26ee-4b79-ac5f-d85f073d3b11" />
<img width="664" alt="截屏2025-06-03 23 38 49" src="https://github.com/user-attachments/assets/c0c189f1-bbba-4fd7-ab24-0ed0eba62e9d" />  

5. 运行宏
 <img width="696" alt="截屏2025-06-03 23 30 46" src="https://github.com/user-attachments/assets/3eb05c32-3487-46fe-a393-b8b650dd2457" />

6.观察每张图片左上角生成的标签和下方自动生成的文本框。  

7.将这个PPT保留在WPS中在其他PPT文件中也可实现该功能。  

8.🎯 **此项重点说明**

该代码对整个PPT文件每个页面一键生成标签或图片说明，推荐用于**仅有实验结果图**的PPT，或者可以新建一个PPT导入相关实验结果后生成标签和图片说明，再将该页复制进入展示PPT中，以防止研究背景的图片也被标识。  

本项目通过代码实现了WPS for Mac 中的PPT 图片标签和图片说明的自动化处理，若觉得有所帮助，欢迎 Star 或 Fork 本项目！
