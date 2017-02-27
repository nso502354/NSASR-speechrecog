# nsasr-speechrecog

### 대외비라 Repository를 생성할 수 없었습니다.
* 소속 : NAVER Labs
* 내용 : SW 개발, NAVER x MS 이매진컵 연계 체험형 인턴십
* 기간 : 2016.07.04 ~ 2016.08.26 

### 내역
1.	Activity, Fragment : Activity 및 Fragment에 특징 및 사용처에 맞는 개발을 하려고 노력했습니다. Activity의 라이프사이클 준수, FragementManger FragmentTransaction을 통한 화면 재사용을 하며 개발하였습니다.
2.	appcompat_v7 : CardView, RecyclerView, GridLayout Library을 활용 및 매터리얼 디자인에 준수하여 개발하였습니다.
3.	BroadcastReceiver : 브로드캐스트 리시버를 통해 액티비티-프래그먼트에 알림 처리 (publish-subscribe design pattern)
4.	Thread, Looper, Handler, AsyncTask : 음성인식 API를 활용하면서 Looper와 Handler를 사용하여 개발하였고 Thread-Looper-Handler와 Message Queue에 대한 이해를 높였습니다. 메인 스레드(UI스레드)가 아닌 음성인식 파일 업로드(HTTP 통신) 및 데이터베이스의 DML(Data Manipulation Language) 작업을 AsyncTask를 활용하여 비동기식으로 개발하였습니다.
5.	NAVER Speech Recognition : Android Activity, Fragment LifeCycle과 NAVER Speech Recognition  State Diagram 각 상태에 맞는 루틴을 처리하였습니다.
6.	Database : SQLite를 활용하여 음성인식 상태를 테이블 컬럼에 맞게 CURD를 구현하였습니다.
7.	HTTP 통신 : HttpURLConnection을 통한 업로드를 AsynkTask와 함께 비동기식으로 처리하였습니다. 
8.	디자인 패턴 : MVC Pattern, Singleton Pattern
9.	소스 관리 : Fork, Pull Request를 통한 git 기술을 사용하여 개발에 참여하였습니다.
