## tensorflow GPU사용하기

1. visual studio 깔기 
   1.  유튜브에서 클릭하는거 똑같이 다 따라 클릭해서 설치 
   2.  cmd에서 c드라이브 > Program Files > Microsoft Visual Studio > 2022 > Community > VC > Auxiliary > Build 경로로 들어가기
      1. cd C:\Program Files\Microsoft Visual Studio\2022\Community\VC\Auxiliary\Build 
   3. 경로로 들어와서 vcvars64.bat 입력

2. 알맞은 버전의 CUDA 깔기
3. cuda와 맞는 버전의 cuDNN 깔기(zip)
3. cuDNN의 파일을 CUDA파일에 붙여넣기(이름 같은 곳 ex)bin 등)
3. 고급 설정에서 PATH 경로 설정
3. 아나콘다에서 pip install tensorflow 와 pip install tensorflow-gpu 인스톨하기



https://www.tensorflow.org/install/gpu

