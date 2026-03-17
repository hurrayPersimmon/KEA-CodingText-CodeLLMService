<div align="center">
    <img width="226" height="77" alt="codingText" src="https://github.com/user-attachments/assets/810ed9b2-930b-44e7-b5dc-b7ff662fd39b" />
    <br>
    <img src="https://img.shields.io/badge/프로젝트 기간-2024.09 ~ 2024.12-green?style=flat&logo=&logoColor=white" />    
</div>



### 배포 URL : [CodingText.com](http://172.16.211.54/)
</div> 

## 📝 소개
코딩테스트 사이트를 이용하며 겪었던 불편한 부분을 개선하기 위해 AI chatbot을 도입한 코딩테스트 블로그 프로젝트를 실시하였습니다.
**코딩테스트를 기록**하기 위해 **다른 창을 열어야**하고, **질문을 위해서**도 **다른 창**을 열어야 하는 번거로움을 한번에 해결하도록 했습니다.
<br>
또한 기능 이외로도 **MSA** 방식을 채택하여 아키텍처를 구성해 **서비스의 안정성**을 높였습니다. 백엔드 개발팀에서는 해당 서비스를 하나씩 담당하여 개발을 진행하였습니다.
저는 LLM 서비스를 담당하여 **spring AI 라이브러리를 학습**하고 이를 적용시켜 **OpenAI API를 연동**했습니다.
<br>

## 👨‍💻 역할
CDC 파이프라인을 설계하여 **질의 응답 데이터를 벡터화 하여 RedisVectorDB에 적재**하였습니다. 또한 **유사도를 검사**하여 사용자가 질문한 것 중에서 가장 유사한 질문과 응답을 prompt에 담아 전달하여 **LLM의 응답 품질을 향상시키도록 유도**하였습니다.
<img width="1573" height="678" alt="kafkaCDC" src="https://github.com/user-attachments/assets/b3688037-992f-47fd-b09b-3abce20d9eb9" />
<br />

### 화면 구성
|코딩 테스트 생성|
|:---:|
![KEA_5기_4조_Xeat_핵심기능시연영상 (2)](https://github.com/user-attachments/assets/cad590b3-0f18-44f1-a2f9-3aed6deaf3db)

|코딩 테스트 질문 with ChatGPT|
|:---:|
![KEA_5기_4조_Xeat_핵심기능시연영상 (1) (1)](https://github.com/user-attachments/assets/b97767dc-ac25-428f-a45e-6d7cd22f57db)

|오류 찾기 with ChatGPT|
|:---:|
![KEA_5기_4조_Xeat_핵심기능시연영상 (2) (1)](https://github.com/user-attachments/assets/b1f6221b-a076-4ab1-8e2a-480bbd93e71f)


<br />

## 🗂️ APIs
작성한 API는 아래에서 확인할 수 있습니다.

<br />

## ⚙ 기술 스택
### Back-end
<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 20px;">
    <img src="https://github.com/user-attachments/assets/ac4f3683-3a0c-4f50-a039-da804342aa4b?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Java.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/SpringBoot.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/SpringDataJPA.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Mysql.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    
</div>

### Infra
<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 20px;">
    <img src="https://github.com/user-attachments/assets/957c5ebe-90b4-4962-b159-eb86d233389c" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Docker.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Jenkins.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
</div>

### Tools
<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 20px;">
    <img src="https://github.com/user-attachments/assets/787d2d33-017c-488d-b016-193c3cf3dce0?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Github.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Notion.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Postman.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
    <img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Swagger.png?raw=true" style="width: 80px; height: 80px; object-fit: contain;">
</div>
<br />

## 🛠️ 프로젝트 아키텍쳐
<img src="https://github.com/user-attachments/assets/7aa2a484-ec80-40f0-9415-62f56801c148" width="800">



<br />

## 🤔 기술적 이슈와 해결 과정


<br />
