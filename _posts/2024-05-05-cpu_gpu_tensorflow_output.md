---
title: CPU, GPU 환경에서 Tensorflow 모델의 출력 차이
author: cotes
date: 2024-05-05 00:34:00 +0800
categories: [버그 리포트, Tensorflow,study]
tags: [favicon]
---



## CPU, GPU 환경에서 Tensorflow 모델이 다른 출력을 내보내는 이슈


kaggle 노트북 상에서 cpu 환경에서 gru 출력을 내보내는 코드

![cpu 환경에서 사진](assets/img/posts/20240505/CPU환경.png)

이상없이 잘 돌아간다.


![gpu 환경에서 사진](assets/img/posts/20240505/GPU환경.png)


하지만 GPU 환경에서는 출력 값이 cpu 환경과 달라 오류가 발생한다.

모든 코드와 변수도 동일한데 왜 이런 현상이 생길까?
