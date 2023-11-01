# small object detection material
创新实践小组文档代码资料存放处

### 目录
- [实用工具](#实用工具)
- [开源资料](#开源资料)
- [开源代码](#开源代码)
- [参考文献](#参考文献)
- [数据集](#数据集)
- [项目结构](#项目结构)

### 实用工具
- [论文翻译工具仓库](https://github.com/rhouselyn/essay-translator-by-gpt)

### 开源资料
- [目标检测最全论文集锦(github)](https://github.com/amusi/awesome-object-detection)
- [hugging face - DETR](https://huggingface.co/docs/transformers/tasks/object_detection)

  
### 开源代码
- [DETR](https://github.com/facebookresearch/detr)
- [dinov2](https://github.com/facebookresearch/dinov2)
- [mmdetection](https://github.com/open-mmlab/mmdetection)
- [hugging face - DETR](https://huggingface.co/facebook/detr-resnet-50) (pretrain)
- [hugging face - Swin Transformer](https://huggingface.co/docs/transformers/model_doc/swin)

### 参考文献
- [dinoV2](https://arxiv.org/abs/2304.07193)

### 数据集
- 经典
  - [COCO](https://cocodataset.org/#download) 
- 超大型（10G-）
  - [AI-TOD航空图像数据集](https://www.cvmart.net/dataSets/detail?tabType=1&currentPage=7&pageSize=12&id=361&utm_campaign=zywang&utm_source=social&utm_medium=gongzhonghao)
    
- 大型（1-10G）
  - [TinyPerson数据集](https://www.cvmart.net/dataSets/detail?tabType=1&currentPage=7&pageSize=12&id=364&utm_campaign=zywang&utm_source=social&utm_medium=gongzhonghao)
  - [KITTI 道路数据集](https://www.cvmart.net/dataSets/detail/247)
    
- 小型（0-1G）
  - [密集行人检测数据集](https://www.cvmart.net/dataSets/detail?tabType=1&currentPage=7&pageSize=12&id=366&utm_campaign=zywang&utm_source=social&utm_medium=gongzhonghao)
  - [iSAID航空图像大规模数据集](https://www.cvmart.net/dataSets/detail?tabType=1&currentPage=7&pageSize=12&id=362&utm_campaign=zywang&utm_source=social&utm_medium=gongzhonghao)
  - [RSOD遥感图像数据集](https://www.cvmart.net/dataSets/detail?tabType=1&currentPage=7&pageSize=12&id=370&utm_campaign=zywang&utm_source=social&utm_medium=gongzhonghao)
  - [小目标检测数据集](https://www.cvmart.net/dataSets/detail/356)
    
  #### 注：以上分类仅考虑压缩包大小

### 项目结构
```
├── essay             # 存放应读的论文
│   ├── translated    # 论文的中文翻译
├── 会议纪要           # 每次会议纪要
│   ├── whl           # whl每周汇报
│   ├── zr            # zr
│   ├── lc            # lc
├── reports           # 存放报告，答辩内容
├── others            # 其他有用资料

```
