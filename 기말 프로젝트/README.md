# 1. 게임의 소개
>- 제목: ***리듬 오브 무싸트***   
>- 참고 사진   
![리듬세상](https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F2167355058D28A3E29 "리듬세상")   
![가짜사나이UDT](https://post-phinf.pstatic.net/MjAyMDA3MzFfMTA1/MDAxNTk2MTcyOTk0NjE3.EoxO_b_rfZJwmPiRqiG_402n0viE0RiGZq3SElra-Jsg.TOEdgbqMEIBMilpdBdVtNymk4VHVqSqBFDqjhDW35dog.JPEG/%EB%B3%B8%EB%AC%B81.jpg"가짜사나이")   

> ![image](https://user-images.githubusercontent.com/70631485/95734772-dada6f00-0cbe-11eb-8f81-e7c01c88c0ca.png)
   
>- 게임의 목적,방법: 리듬게임의 모방게임인데 요즘 제가 즐겨봤던 유튜브 영상인 가짜사나이와 무싸트를 접목시킨 게임입니다. 따라서 이 게임은 무싸트 훈련을 받게된 플레이어가 조교들의 구령에 맞춰 동작을 정확히 맞추어 마지막 훈련까지 체력을 남겨 무싸트 훈련과정을 수료하는것이 목표입니다. 

# 2. GameState의 수 및 각각의 이름
  - 메인화면(게임 제목)      
  - 난이도 선택화면    
  - level 1. pt체조   
  - level 2. 구보   
  - level 3. 팀원과 IBS 들기   
  - level 4. 생존 수영   
  - 벌칙 또는 기회 (열외)   
  - 게임 오버화면(종치기)   
  - 게임 클리어 (+점수판)   
  **총 9개씬**   
  
# 3. 게임 흐름
- 메인화면

![image](https://user-images.githubusercontent.com/70631485/95739450-d796b180-0cc5-11eb-867b-0734b2e1b8d8.png)
- 조교시범 관람

![image](https://user-images.githubusercontent.com/70631485/95734783-de6df600-0cbe-11eb-82ac-030ea9933b1e.png)
- 연습게임 3번 (후에 바로 같은 방식으로 본 게임)

![image](https://user-images.githubusercontent.com/70631485/95734800-e3cb4080-0cbe-11eb-870b-deb40e8d9817.png)
- 실수 패널티 (얼차려)

![image](https://user-images.githubusercontent.com/70631485/95734813-e75ec780-0cbe-11eb-8d88-cbe8cdfce101.png)
- 게임오버

![image](https://user-images.githubusercontent.com/70631485/95734891-0d846780-0cbf-11eb-8415-90552b9e09ec.png)
- 요약

![image](https://user-images.githubusercontent.com/70631485/95738864-e03ab800-0cc4-11eb-9767-b8733d70d25f.png)
# 4. 각 GameState 별 다음 항목
- 메인화면: 게임 메인화면이다.  
> 게임로고와 사진이 합쳐진 배경 1장   
> >[엔터키, esc키]  
> >=> 엔터시 난이도 선택으로 esc시 종료  
- 난이도 선택: 난이도 선택화면이다.   
> 3단계의 난이도 선택칸이 있는 배경 1장  
> >[마우스 클릭]  
> >=> 마우스 클릭으로 원하는 난이도 선택하고 level 1으로 이동   
- level 1: 게임 레벨1으로 pt체조이다. 먼저 모든 레벨에서 연습게임은 단 3번민 하고 바로 본게임으로 들어간다. 조교의 구령에 맞춰 알맞은 키를 누르면 된다.   
> 움직이지 않는 모래사장배경1장, 체조하는 플레이어, 서있는 조교 이미지(무표정,화냄,극대노) 총3장  
> >[키보드 입력(q,w,e,r)]  
> >=> 타이밍맞게 알맞은 키보드를 입력하면 박자가 점점 빨라지며 (이에 맞게 플레이어와 배경 그외 오브젝트의 반응들도 맞춰 움직인다.) 모든 동작을 해내면 level 2로 이동, 실패하면 체력이까이는 대신 벌칙화면으로 전환, 만약 체력이 없을시 게임오버화면으로 전환   
- level 2: 게임 레벨2로 구보이다. 조교의 구령에 발을맞춰 구보를 뛰는 것으로 구령에 알맞은 키를 누르면 된다.   
> 좌우중 한쪽으로 움직이는 모래사장배경1장, 구보뛰는 플레이어, 구보뛰는 조교   
> >[키보드 입력(q,w,e,r)]  
> >=> level 1의 과정과 동일       
- level 3: 게임 레벨3로 팀원들과 함께 IBS들기이다. 조장과 팀원들의 구령에 맞춰 IBS를 들면되는것으로 구령에 알맞은 키를 누르면 된다.   
> 움직이지않는 모래사장배경1장, 움직이는 플레이어, 움직이는 팀원 (플레이어의 성공여부에따라 변화하는 표정추가), 플레이어의 행동을 따르는 IBS  
> >[키보드 입력(q,w,e,r)]  
> >=> level 1의 과정과 동일 
- level 4: 게임 레벨4로 생존수영이다. 조교의 휫슬소리에 맞춰 알맞은 키를 입력하면 된다.    
> 좌우중 한쪽으로 움직이는 강배경1장, 수영하는 플레이어, IBS타고 움직이는 조교  
> >[키보드 입력(q,w,e,r)] 
> >=> 성공시 게임클리어화면 전환 나머지는 타 레벨과 동일 
- 벌칙: 실패하여 체력을 까이고 벌칙을 수행하는 것으로 입수하기, 업드려뻗쳐하기, 점찍고 오기가 있다. 이때 최대한 키를 빨리 눌러서 체력을 아껴야 후에도 체력이 남는다.   
> 뒤에 강이보이는 배경1장, 벌칙을 수행하는 플레이어, 조교, 같이 얼차려받는 동료들  
> >키보드 입력(space)  
> >=> 성공시 다시 실패한 게임화면으로 실패시 게임종료화면으로 전환   
- 게임 오버화면: 말그대로 게임오버화면    
> 종을 치는 플레이어가 나오는 배경1장  
> >엔터  
> >=> 엔터시 다시 메인화면으로 전환   
- 게임 클리어화면: 게임 클리어시 나오는 화면으로 점수를 메겨 보여준다.(D에서 A+까지)      
> 조교와 기념사진을 찍는 배경1장과 점수판이미지 한장  
> >엔터  
> >=> 엔터시 다시 메인화면으로 전환   

# 5. 필요할 기술
  - 이전 수업에서 잠깐 배웠던 시간을 정확히 다루기   
  - 게임 사운드 넣기   
  - 구보시 게임 백그라운드 움직이기
  - ***무엇보다도 리듬게임을 만들예정이다보니게임 입력시간과 출력시간의 반응속도가 가장 중요할것 같아서 이것을 어떻게하면 가장 효과적으로 구현할수있는지 배우고 싶습니다.*** 
  
# 6. 개발범위&일정
![image](https://user-images.githubusercontent.com/70631485/95734709-c8603580-0cbe-11eb-873b-6a7a11fcb156.png)
![image](https://user-images.githubusercontent.com/70631485/95734734-d0b87080-0cbe-11eb-96ef-b6502cdf08f6.png)
