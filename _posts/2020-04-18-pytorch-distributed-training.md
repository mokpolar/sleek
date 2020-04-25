---
layout: post
title: AWS상에서 PyTorch로 분산학습 해보기
featured-img: pytorch
mathjax: true
---

# AWS에서 PyTorch로 분산학습을 해보았다. 

아직 분산학습에 대한 개념도 제대로 서지 않아서, AWS상에서 이를 실행을 성공시키는데 중점을 두었다. 

```python
pip install pytorch 


```

## 환경
* EC2
    * p2.8xlarge(K80)
    * Deep Learning AMI