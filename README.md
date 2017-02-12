# TensorFlow 기초 및 실습

본 강의에서는 가장 널리 사용되는 딥러닝 라이브러리 중 하나인 TensorFlow를 소개한다. TensorFlow는 추상화된 GPU 컴퓨팅, 자동 미분(Auto-Diff), 분산 컴퓨팅, 손쉬운 시각화(TensorBoard) 등 딥러닝 모델을 빠르게 학습시키고 모니터링하는데 필요한 기능들을 두루 갖추고 있다. 강의에서는 이러한 기능들의 기본적인 사용법을 코드레벨에서 설명하고, 관련하여 간단한 실습을 진행한다. 또한 Logistic Regression, Deep Neural Network 등의 모델을 TensorFlow를 이용하여 직접 구현해보고 실제 문제에서 어떻게 사용될 수 있는지 알아본다.

## 기초 이론

[슬라이드](https://preview.c9users.io/nzer0/tensorflow_tutorial/intro_to_tf_osia.pdf?_c9_id=livepreview1&_c9_host=https://ide.c9.io)

## 실습 

### 도움이 되는 자료들
* [TensorFlow 공식 API 문서](https://www.tensorflow.org/)
* [보다 편리한 API 검색 사이트](http://devdocs.io/)
* [Deep Learning 이론 교과서](http://www.deeplearningbook.org/)

### Jupyter Notebook 사용
* 켜기
`jupyter notebook`
* 접속
<https://workspacename-yourid.c9users.io:8080>

### TensorBoard 사용
* 켜기
`tensorboard --logdir=dirname --port=8081`
* 접속
<https://workspacename-yourid.c9users.io:8081>