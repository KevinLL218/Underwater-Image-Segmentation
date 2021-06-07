RGB MASK to COCO  

# 基于DeepLab V1 的Image Segmentation项目  
# 数据集：水下管道（有光/无光）  
## 目标： 
  ### 探究Illumination对ImageSegmentation的影响，通过修改Loss，注意力模块，mask精度等方式进行测试  
# Label：RGB MASK 背景-管道-阀门  

Background  | Pipe  | Valve
 ---- | ----- | ------  
 (0,0,0) | (128,0,0) | (0,128,0)  
 
  ## 测试样例
  ![](output/test.png)
  ## 预测结果
  ![](output/mask.png)
