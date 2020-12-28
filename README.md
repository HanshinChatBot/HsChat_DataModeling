# 🏫HsChat DataModeling🏫



### 🖥DataModeling🖥

> 한신대학교 AI CHATBOT API 기반 유전 인공지능 대화 전처리 모델
>
> 해당 모델링은 한신대학교 정보관리팀 AI CHATBOT SYSTEM의 대화모델 전처리 모델링입니다.
> 모든 시스템은 해당 모델링안에 설정된 TASK, ENTITY, INTENT를 통해 작동되며 사용자의 발화내용을 분석해서 요청에 따른 응답을 제공합니다. 
> 사용자의 발화내용을 형태소 단위로 분석해 재학습하는 기능으로 정확한 질의응답이 가능합니다.
> 
> 🖐안녕하세요. 한신대학교 정보관리팀 CHATBOT 입니다.🖐

<br>

### 📊Task Graph

<img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/TaskGraph.png">

<br>

### 🤘All Entities

0. ❔What is Entity?
> 사용자의 말이나 문장 속에서 원하는 정보를 추출하여 적절하게 대화를 이끌어 나갈 수 있도록 설정하는 단어군
> 대화의도의 파라미터가 실제로 어떤 종류의 값을 가지게 될지 결정해 주는 역할



1. All tasks
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/1.png">

   

2. Inquery_Homepage
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/2.png"> 



3. Inquery_Iptime
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/3.png">
   


4. Inquery_Group
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/4.png">

   

5. Inquery_Arcon
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/5.png">

   

6. Inquery_Etc
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/6.png">

   

7. Inquery_Teacher
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/7.png">

   


8. Inquery_Cs  
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/8.png">
   
<br>

### 🙌All Intent

0. ❔What is Intent?
> 사용자가 챗봇에게 전달하는 목적(의도) 쉽게 풀어 사용자의 발화내용
> 자연어로 이야기했을 때, 말하는 사람의 발화 의도



1. All tasks
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/11.png">

   

2. Get_Inquery_Info
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/12.png"> 



3. Inquery_Homepage
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/13.png">
   


4. Inquery_Iptime
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/14.png">

   

5. Inquery_Group
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/15.png">

   

6. Inquery_Arcon
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/16.png">

   

7. Inquery_Etc
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/17.png">

   

8. Inquery_Teacher
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/18.png">

   
9. Inquery_Cs
   <img src="https://github.com/HanshinChatBot/HsChat_DataModeling/blob/master/pic/19.png">

<br>

### 📖References
- [공공 인공지능](https://aiopen.etri.re.kr/)
- [대화형 챗봇 설계 이론](https://gist.github.com/haje01/7fc9d1b1fc1b6c8c9b7918abf5407a86)
- [네이버 CHATBOT API](https://www.ncloud.com/product/aiService/chatbot)