#streamlit_11_food

[TeachableMachine](https://teachablemachine.withgoogle.com/train/image ,'티쳐블 머신') 으로 학습한, 11개의 음식이미지를 예측하는 앱<br/>

데이터셋은 : [kaggle](https://www.kaggle.com/datasets/trolukovich/food11-image-dataset ,'캐글')에서 내려받아 진행하였음<br/><br/>

진행과정은 캐글에서 내려받은 데이터를 티쳐블머신에 집어넣어 학습시킨 모델을 저장<br/>
그리고 스트림릿을 이용하여 웹페이지를 만들고<br/>
st.file_uploader를 이용하여 유저에게 입력받은 이미지파일을<br/>
그 이미지 파일이 맞는지 유저에게 보여줌과 동시에,<br/>
티처블머신이 학습한 모델로 11개의 음식종류를 판별후<br/>
11개의 종류중 가장 확률이 높은 음식종류를 유저에게 보여주며<br/>
몇 퍼센트의 확률로 이 음식일거다 라는 문구를 유저에게 알림<br/><br/>
