
# Presentation Generator
발표 대본을 입력하면 문맥을 파악해 자동으로 시각적 발표 자료(PPT)를 생성하는 웹사이트로, LLM을 활용한 프레젠테이션 자동 생성 웹 서비스를 개발했습니다.

<div align=center> <img width="690" alt="스크린샷 2024-12-24 오후 4 16 26" src="https://github.com/user-attachments/assets/dd8f1532-94f1-42ff-9d72-833c4556c0e6" /></div>

## 👥 Contributors
|[안재현](https://github.com/Jaehyeonee)|[허예은](https://github.com/yyyeun)|[황정민](https://github.com/oxxsusu)|
|:-------:|:---------:|:----------:|
|DL&FE|DL&FE|BE&FE|
<img width="800" alt="스크린샷 2024-12-24 오후 4 18 31" src="https://github.com/user-attachments/assets/c78c8c08-0e00-4309-b1c7-04de46532ccc" />



###### Development period
```- 2023.03~2023.09```

## Service Goal
본 서비스의 목적은 발표 자료 제작을 자동화하여 제작 시간을 단축하고 업무의 효율성을 향상시키는 것이다. <br>
Presentation Generator는 발표 대본을 입력으로 받고 어울리는 ```템플릿-이미지 중심, 글 중심, 키워드 중심-``` 을 선택할 수 있도록 한다. <br>
핵심 내용을 담은 요약문을 생성하고 이에 맞는 이미지를 크롤링하는 프로세스를 통해 프레젠테이션을 자동으로 구성해주는 웹 서비스이다. 

## Method
서비스의 주요 기능인 요약 및 키워드 추출을 위해 ```KoBART```와 ```KeyBERT``` 딥러닝 모델을 사용하였다. 
또한 파일 저장 및 마이페이지 기능을 통해 사용자가 생성된 프레젠테이션 자료를 관리할 수 있도록 했다.

## Service WorkFlow
<img width="391" alt="스크린샷 2024-12-24 오후 4 15 32" src="https://github.com/user-attachments/assets/96532b93-8347-4b99-bcde-ace5f49032cf" />

## System Architecture
<img width="722" alt="스크린샷 2024-12-24 오후 1 58 33" src="https://github.com/user-attachments/assets/93149b89-abb8-44b0-9bcb-141460aab280" />

## Env(개발환경)
<img width="533" alt="스크린샷 2024-12-24 오후 2 00 45" src="https://github.com/user-attachments/assets/76d8bb34-83d3-400b-b19d-2a9c48fd479a" />
