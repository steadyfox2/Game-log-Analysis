# 🎮 Game-log-Analysis
## Predict Student Performance from Game Play kaggle 데이터를 활용한 EDA 및 모델링

게임 기반으로 된 학습 로그 데이터를 가지고 학생들이 성적을 분석하는 것이 본 대회의 목적이다. 

## 🎲데이터셋 설명

session_id - 이벤트가 발생한 세션의 ID

index - 세션에 대한 이벤트의 인덱스

apsed_time - 세션 시작과 이벤트가 기록된 시간 사이에 경과한 시간(밀리초)

event_name - 이벤트 유형의 이름

name - 이벤트 이름(예: 노트북_클릭이 노트북을 열거나 닫을 것인지 식별)

level - 이벤트가 발생한 게임의 레벨(0 ~ 22)

page - 이벤트의 페이지 번호(노트북 관련 이벤트에 한함)

room_coor_x - 게임 내 룸을 참조하는 클릭 좌표(클릭 이벤트에 한함)

room_coor_y - 게임 내 룸을 참조하는 클릭 좌표(클릭 이벤트에 한함)

screen_coor_x - 플레이어의 화면을 참조하는 클릭 좌표(클릭 이벤트에 한함)

screen_coor_y - 플레이어의 화면을 기준으로 한 클릭의 좌표(클릭 이벤트에만 해당)

hover_hover - 호버가 발생한 시간(밀리초)(호버 이벤트에만 해당)

text - 이벤트 중에 플레이어가 보는 텍스트

fqid - 이벤트의 정규화된 ID

room_fqid - 이벤트가 발생한 룸의 정규화된 ID

text_fqid - 의 정규화된 ID

전체 화면 - 플레이어가 전체 화면 모드인지 여부

hq - 게임이 고품질인지 여부

음악 - 게임 음악이 켜져 있든 꺼져 있든 간에

level_group - 수준 그룹 및 질문 그룹 - 이 행이 속하는 그룹(0-4, 5-12, 13-22)

## 🎲EDA
