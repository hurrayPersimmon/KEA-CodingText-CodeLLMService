<div align="center">
    <img width="226" height="77" alt="codingText" src="https://github.com/user-attachments/assets/810ed9b2-930b-44e7-b5dc-b7ff662fd39b" />
    <br>
    <img src="https://img.shields.io/badge/프로젝트 기간-2024.09 ~ 2024.12-green?style=flat&logo=&logoColor=white" />    
</div>



### 배포 URL : [CodingText.com](http://172.16.211.54/)
</div> 
<br>
<br>

## 📝 소개
코딩테스트 사이트를 이용하며 겪었던 불편한 부분을 개선하기 위해 AI chatbot을 도입한 코딩테스트 블로그 프로젝트를 실시하였습니다.
**코딩테스트를 기록**하기 위해 **다른 창을 열어야**하고, **질문을 위해서**도 **다른 창**을 열어야 하는 번거로움을 한번에 해결하도록 했습니다.
<br>
또한 기능 이외로도 **MSA** 방식을 채택하여 아키텍처를 구성해 **서비스의 안정성**을 높였습니다. 백엔드 개발팀에서는 해당 서비스를 하나씩 담당하여 개발을 진행하였습니다.
저는 LLM 서비스를 담당하여 **spring AI 라이브러리를 학습**하고 이를 적용시켜 **OpenAI API를 연동**했습니다.
<br>
<br>

## 👨‍💻 역할
CDC 파이프라인을 설계하여 **질의 응답 데이터를 벡터화 하여 RedisVectorDB에 적재**하였습니다. 또한 **유사도를 검사**하여 사용자가 질문한 것 중에서 가장 유사한 질문과 응답을 prompt에 담아 전달하여 **LLM의 응답 품질을 향상시키도록 유도**하였습니다.
<img width="1573" height="678" alt="kafkaCDC" src="https://github.com/user-attachments/assets/b3688037-992f-47fd-b09b-3abce20d9eb9" />
<br>
<br>

## 🖥️ 화면 구성
|코딩 테스트 생성|
|:---:|
![KEA_5기_4조_Xeat_핵심기능시연영상 (2)](https://github.com/user-attachments/assets/cad590b3-0f18-44f1-a2f9-3aed6deaf3db)

|코딩 테스트 질문 with ChatGPT|
|:---:|
![KEA_5기_4조_Xeat_핵심기능시연영상 (1) (1)](https://github.com/user-attachments/assets/b97767dc-ac25-428f-a45e-6d7cd22f57db)

|오류 찾기 with ChatGPT|
|:---:|
![KEA_5기_4조_Xeat_핵심기능시연영상 (2) (1)](https://github.com/user-attachments/assets/b1f6221b-a076-4ab1-8e2a-480bbd93e71f)

<br>
<br>

## 🪄 코드 소개
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_16" src="https://github.com/user-attachments/assets/cffc140a-ee99-454c-90ec-9b9ee2e0e827" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_17" src="https://github.com/user-attachments/assets/0258b79f-5ae1-4ec3-a278-074d81106af5" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_18" src="https://github.com/user-attachments/assets/21510a4d-3ff5-4c72-a3fb-ecdc61872f73" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_19" src="https://github.com/user-attachments/assets/cd8c21d2-2bbf-4695-b963-41e8d31753fa" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_20" src="https://github.com/user-attachments/assets/f11ffcd0-257c-420a-b47e-f8f2b20fb6a8" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_21" src="https://github.com/user-attachments/assets/129bb096-1d6a-423b-87b8-67f90dadeb34" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_22" src="https://github.com/user-attachments/assets/6da36889-a9d6-4da0-b8c2-3cb97c742bd6" />

<br>
<br>

## 🛠️ 프로젝트 아키텍쳐
<img src="https://github.com/user-attachments/assets/7aa2a484-ec80-40f0-9415-62f56801c148" width="800">


<br>
<br>

## 🤔 기술적 이슈와 해결 과정
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_5" src="https://github.com/user-attachments/assets/5e3bf2a6-1b92-48a9-99e7-67cd3f123b0f" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_6" src="https://github.com/user-attachments/assets/6f091b8e-f26b-4532-8983-5ceae3f60efe" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_7" src="https://github.com/user-attachments/assets/e9d8682b-d372-4f9d-b866-4fa8b7110382" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_8" src="https://github.com/user-attachments/assets/18f9b173-fd2c-4667-89c4-8c172b99bb0d" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_9" src="https://github.com/user-attachments/assets/1c78a96b-ce08-4adc-a919-07ea825cec5c" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_10" src="https://github.com/user-attachments/assets/4e28bd75-a49e-4f84-b8cf-d16e031bb8f6" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_11" src="https://github.com/user-attachments/assets/7e530b36-5a99-4723-9e01-4eb63ff6f481" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_12" src="https://github.com/user-attachments/assets/252a4468-eac9-46a6-ac52-393d91bd1e9f" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_13" src="https://github.com/user-attachments/assets/fe9495d4-e25a-4b31-8382-158de1966c10" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_14" src="https://github.com/user-attachments/assets/1f24647d-5914-4e93-b407-b32ccdf84b1e" />
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_15" src="https://github.com/user-attachments/assets/a0fb1731-355a-4e6b-a778-9cdfeef01344" />

<br>
<br>

## 최종 계획
<img width="1024" height="576" alt="1773754908860-21720793-da11-4769-b3d6-1764f60362f9_23" src="https://github.com/user-attachments/assets/70a68c93-b708-4e3c-973e-43862732e944" />

<br>
<br>

## 🗂️ APIs
작성한 API는 아래에서 확인할 수 있습니다.


