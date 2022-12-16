라즈베리파일을 이용한 이미지 러닝 훈련 소스코드



<박준하>-자료조사, 문서작업, 코딩

▶카메라가 인식하기 위한 이미지 찾기
-유리병, 플라스틱

▶얼굴 인식 Test 코드 학습
-얼굴인식 Test 코드 – OpenCV : https://stickode.tistory.com/197

![image](https://user-images.githubusercontent.com/84001817/208068098-24a616ce-f90c-45b7-975e-c53b7a4baed4.png)

▶직접 수집한 이미지를 이용하여 학습시키고 .tflite 파일 다운![image](https://user-images.githubusercontent.com/84001817/208068878-af5f4a98-2d72-44b1-bdff-3e3fffddc10c.png)
![image](https://user-images.githubusercontent.com/84001817/208068895-8412f5ec-8712-4029-873f-148d6bf7b998.png)
![image](https://user-images.githubusercontent.com/84001817/208068922-1348df2d-66b9-426d-abe9-cb8e1de120e1.png)
![image](https://user-images.githubusercontent.com/84001817/208068948-b2e6d235-f996-48a1-b4bd-3c8d676f2e40.png)
![image](https://user-images.githubusercontent.com/84001817/208068964-c978716f-c0d3-4a1e-93f5-3da8fd954267.png)
![image](https://user-images.githubusercontent.com/84001817/208068978-de4774f1-f03d-4eba-8b19-61b38a8d61bf.png)
![image](https://user-images.githubusercontent.com/84001817/208068999-c0c621b2-7996-47f0-b057-84ba21f6ecc9.png)


결과
![image](https://user-images.githubusercontent.com/84001817/208069011-20902254-a4b1-4dc3-94de-e029594e7cc8.png)


▶이미지 xml 파일 만들기
-유리병
gibhub에서 LabelImg를 다운받아 사용


<이환규>-자료조사, 디자인, 코딩

▶카메라가 인식하기 위한 이미지 찾기
-캔, 플라스틱

▶라즈베리파이 환경 구축
-라즈베리파이에 카메라와 Tensorflow 설치
:: 코드
~ $ git clone https://github.com/EdjeElectronics/TensorFlow-Lite-Object-Detection-
on-Android-and-Raspberry-Pi.git
-TFLite-webcam 실행

-사용환경 만들어주기
-source project_env/bin/activate
  (raspberrypi% -> (project_env)rasberryip%로 변한 것을 확인하면 됨)
-python으로 된 webcam을 미리 다운로드 한 모델을 이용하여 작동
 -python TFLite_detection_webcam.py --modeldir=test_model
  (해석: python으로 작성된 웹캠 파일을 "test_model(임시파일명)"을 사용하여 작동시킬 것이다.)
![image](https://user-images.githubusercontent.com/84001817/208068433-29ad1551-006b-4e2c-a593-0d248fe5fc01.png)
  
▶직접 수집한 이미지를 이용하여 학습시키고 .tflite 파일 다운


<임소정>-지료조사, 문서작업, 디자인

▶라즈베리파이 환경 구축
-프로그램을 설치하기 위해 카메라 모듈과 OpenCV 설치

-카메라 모듈 설정 및 변환

-OpenCV 설치 후 소스코드 받아 컴파일 작업

▶이미지 xml 파일 만들기
-캔
gibhub에서 LabelImg를 다운받아 사용
![image](https://user-images.githubusercontent.com/84001817/208068700-7b12705d-998b-413b-8b06-4acd6ac84c09.png)

▶직접 수집한 이미지를 이용하여 학습시키고 .tflite 파일 다운


<임은서>-자료조사, 디자인, 모형제작

▶컨베이어 벨트 제작
-레고마인드스톰 EV3로 'LEGO education'사이트에서 제공해주는 컨베이어 벨트 조립 설명서를 보고 제작
-컨베이어 벨트를 작동시키기 위한 레고마인드스톰 소프트웨어를 다운받아 로봇과 컴퓨터를 선으로 연결하여 코드 직접 실행
![image](https://user-images.githubusercontent.com/84001817/208067830-2309380e-a859-43cc-9105-59e0a1fc98f6.png)

▶이미지 xml 파일 만들기
-플라스틱
gibhub에서 LabelImg를 다운받아 사용

▶직접 수집한 이미지를 이용하여 학습시키고 .tflite 파일 다운

[응용사례]
시각장애인을 인식하는 모델 만들기
-지팡이 이미지와 휠체어 이미지를 구분한다
-이미지는 같은 방법으로 xml파일을 만든다

활용방안
-횡단보도에서 시각장애인용 신호버튼을 눌러주는 게 아닌 카메라로 시각장애인(지팡이, 휠체어)을 인식해 신호를 바꿔준다
