---
layout: page
title: Patch Logs
include_in_header: true
---
# 패치 내역


<br>


## ⚡3.3.2

**밸런싱**

1. 혁명가

	- 혁명가의 스킬 사용 조건이 64로 고정됩니다. (기존: 1레벨 - 256, 11레벨 - 32)
	- 1레벨: 64에 도달하면 4명의 영웅 숫자를 2배로 올립니다.
	- 4레벨: 64에 도달하면 6명의 영웅 숫자를 2배로 올립니다.
	- 7레벨: 64에 도달하면 8명의 영웅 숫자를 2배로 올립니다.
	- 11레벨: 64에 도달하면 모든 블럭의 숫자를 2배로 올립니다.
			
2. 저격수

	- 저격수에게 장전시간이 추가됩니다. 
	- 스킬을 사용하고 3초 이후 다시 스킬을 사용할 수 있습니다.


**버그수정**

1. iOS에서 튜토리얼 자막이 나오지 않던 버그가 수정되었습니다.
2. 메인보스 미사일의 사운드가 음소거인데도 출력되던 버그가 수정되었습니다.


<br>

## ⚡3.3.1

**버그수정**

1. PvP 매치메이킹 범위가 축소되었습니다.
2. 일부 기기에서 로그인이 안되는 현상을 수정하였습니다.
		

<br>

## ⚡3.3.0

**신규 종족: 프로젝트**

몰려오는 기계들의 비밀을 품고 있는 6명의 영웅들이 등장합니다. 
이 기계들은 에너지를 전략적으로 사용하는 테크니컬한 플레이가 요구됩니다.
		
	- 종족 시너지: 최대 보유 에너지량이 3명: 5 / 6명: 10 만큼 증가합니다.	
	
	- 터렛 (일반): 보드 위에 타워가 늘어날 때마다 강력해집니다.
	- 캐논 (일반): 보유한 에너지량에 따라 범위 공격이 강력해집니다.
	- 암살자 (일반): 에너지를 사용하여 일반 등급의 몹을 즉사시킵니다.
	- 저격수 (특수): 에너지를 사용하여 상대편의 영웅을 저격하여 없애버립니다.
	- 엔지니어 (특수): 14초마다 빈 블럭에 터렛을 생산합니다.
	- 기사 (전설): 특정 블럭 숫자에 도달하면 기지를 방어하는 방어막을 설치합니다.

<br>

**밸런싱**

2048 히어로즈는 경쾌한 조작감에 맞는 빠른 템포의 게임을 지향하고 있습니다.
이에 맞춰 아래의 내용들이 변경됩니다.

	- 각 웨이브 시작시 고정 대기 시간: 1초 -> 0.5초
	- 웨이브가 증가함에 따라 적 체력 증가분이 소폭 상향되었습니다.
	- 일반 영웅 등장 확률이 16% > 12%로 감소되었습니다.
	- 메인 보스가 더욱 강력해 집니다.

<br>

**메인 보스 "메두사" 리워크**

플레이어 분들의 피드백을 바탕으로 메두사가 리워크 되었습니다.

	- 영구적인 석화 효과가 제거되었습니다.
	- 모든 석화 효과(사슴 및 룬 효과 포함)의 지속시간이 3초 -> 5초로 증가하였습니다. 
	- 메두사가 자신의 위치에서 가까운 2개의 행/열의 영웅들(최대 8명)을 석화시킵니다.
	- 석화에 걸린 영웅들은 공격 및 스킬을 사용할 수 없습니다.
	- 석화에 걸린 영웅에 블럭을 합쳐 석화를 해제할 수 있습니다.

<br>

**시즌 변경점**

이제 매월 2회의 시즌이 운영됩니다.
		
	- 매월 1일과 15일에 새로운 시즌이 시작됩니다.
	- 시즌이 종료되면, 자신의 리그에 맞는 보상을 받게 됩니다.
	- 새로운 시즌에는 랭킹과 시즌 패스 보상이 초기화 됩니다.
	- 이전 시즌의 성적과 보유한 영웅들의 평균 레벨을 기반으로 
	  다음 시즌의 시작 리그가 결정됩니다.

<br>

**경제**

	PvP 핫 타임!
	
	- 12:00 ~ 13:00, 22:00 ~ 23:00에 PvP 승리시 50%의 추가 골드를 획득합니다.
	

	리그별 보상 차등
	
	- 높은 리그에 오를 수록 많은 기본 보상을 받게 됩니다.
	- 광고 시청 보상은 유지됩니다.
	- 골드: 10 ~ 50
	- 열쇠: 1개 ~ 5개
		
		
	상자 및 열쇠
	
	- 상자에서 획들할 수 있는 영웅의 종류가 1종 고정 추가 됩니다.
	- 변경 전: 최대 3종의 영웅(n명) -> 변경 후: 최대 4종의 영웅(n명)
	- PvP 승리시 획득할 수 있는 열쇠 수량이 일 단위 100개로 제한됩니다. 
	- 디펜스 모드, 퀘스트 및 룰렛에서 획득 할 수 있는 열쇠는 제한을 받지 않습니다.
	- 상자 당 얻을 수 있는 영웅 수가 고정 증가함에 따라, 디펜스 모드 보상의 열쇠 수량이 하향 조정되었습니다.

<br>

**편의성**

	초당 공격력 표시 (DPS)
	
	- 게임 플레이 중 보드 전체의 공격력이 표시됩니다.
	
	
	영웅 정보 인터페이스
	
	- 덱에 포함된 영웅을 누르면, 기존의 스킬 설명 팝업 대신 영웅의 상세 정보를 확인할 수 있습니다.


	덱 추천 및 자동 덱 설정
	
	- 배틀 메뉴 상단에 덱 추천 페이지가 추가되었습니다.
	- 초급 덱, 중급 덱, 전문가 덱을 확인할 수 있습니다.
	- 선택 버튼을 누르면 자동으로 현재 덱으로 설정됩니다.
	- 현재 구성된 덱들은 전략 컨셉을 추천하는 덱 입니다.


	종족 바로가기 인터페이스
	
	- 영웅 페이지에서 종족별 아이콘 버튼이 추가되었습니다.
	- 해당 버튼을 누르면 각 종족 영웅들을 바로 확인 할 수 있습니다.
	
<br>	
	
추가된 영웅들을 사용해서 2048을 만들어보세요.
그럼 다음 업데이트까지 함께 2048! 🔥


<br>


## ⚡3.2.0


1. 이제 5개의 덱을 저장할 수 있습니다.
		
2. 버그 수정
	
	- 선장이 만렙일 경우, 숙련도가 카운트 되지 않던 버그를 수정하였습니다.
	- 팝업 메뉴들의 UI 개선 및 번역 오류가 수정되었습니다.
	
커뮤니티에 참여해서 창의적인 전략을 공유해보세요!
그럼 다음 업데이트까지 함께 2048! 🔥


<br>
## ⚡3.1.9


1. 프로젝트 미사일
	
	- 이제 등장할 때 미사일을 발사합니다.
	- 이후 쿨타임이 시작됩니다.
	
2. 버그 수정
	
	- 정치가가 다른 전설 영웅들과 함께 사용될 경우, 레벨이 정상적으로 적용되지 않던 버그가 수정되었습니다.
	- 골든키 획득 이후, 다른 보상을 수령할 경우 보상이 골든키로 표시되던 버그가 수정되었습니다.
	
커뮤니티에 참여해서 창의적인 전략을 공유해보세요!
그럼 다음 업데이트까지 함께 2048! 🔥


<br>


## ⚡3.1.8 


1. 신규 상점 오픈
	
	- 상점 메뉴 상단의 "일반 상품"을 탭하면 확인할 수 있습니다.
	- 전설 영웅까지 고정으로 획득할 수 있습니다.
	- 각 상품을 골드를 사용하여 1일 1회 구매할 수 있습니다.
	- 영웅들을 매일 갱신 됩니다.
	- 구성품은 추후 업데이트에서 변경될 수 있습니다.



2. 버그 수정
	
	- 가끔 숙련도 수치가 적용되지 않던 버그가 수정되었습니다.
	- 번역 오류들이 수정되었습니다.
	

<br>

## ⚡3.1.7 


1. 크리스마스 & 신년 이벤트가 시작됩니다. (~1/2)
	
	- EVENT1: 접속 이벤트
	- EVENT 2: PvP 보상 2배!
	- EVENT 3: 프리미엄 패스 상품 할인



2. 신규 메인 보스: 프로젝트 미사일
	
	- 강력한 미사일을 발사하는 보스가 등장했습니다.
	- 8초 마다 보드 위에 미사일을 퍼붇습니다. 미사일에 맞은 블럭은 파괴됩니다.
	- 블럭을 다른 위치로 옮겨 날아오는 미사일을 피할 수 있습니다. 



3. 영웅 밸런싱

	- 숫자를 올리는 것이 데미지를 올려주기 때문에, 숫자를 올리는 스킬을 가진 영웅들의 공격속도가 감소합니다.
	- 딜러 역할을 하는 영웅들의 특색을 살리고, 딜러 중심의 전략이 버프를 받습니다.

	**개척자**
	공격속도 1초 > 2초
	
	**혁명가**	
	공격속도 1초 > 2초
	
	**연설가**
	공격속도 1초 > 2초



4. 웨이브 밸런싱

	- 에너지를 수급하는 영웅들의 가치가 낮아지고, 플레이어 마다 남는 에너지가 높습니다.	
	- 시작 에너지 및 웨이브 당 에너지: 8 > 7 
	- 메인 보스들의 체력이 20웨이브 이상부터 10% 추가



5. 영웅 설명 리워크

	- 모든 영웅들의 스킬 설명이 보다 직관적이고 상세하게 개선되었습니다.
	- 출시 및 리워크 예정인 영웅들 소식은 추후 업로드 됩니다.
	- 조련사의 숙련도가 올라가지 않는 문제가 수정되었습니다.
	- 각종 버그 및 번역 오류가 수정되었습니다.
	- 앱의 성능이 크게 향상되었습니다.
	
	
그럼 다음 업데이트까지 함께 2048! 🔥

<br>


## ⚡3.1.1 

1. 버그 수정
	- 영웅 정보가 정상적으로 표시되지 않던 버그 수정
	- 석화에 걸렸던 영웅이 석화가 풀리면서 즉시 스킬을 사용하던 버그 수정
	- 번역 오류 수정 및 데미지 시각 효과 개선
	- 연승 행진 퀘스트가 중복 달성되는 버그 수정
	- 웨이브당 에너지가 8이 아닌 7 증가하는 버그 수정
	- 다음 출진할 영웅 보스가 정상적으로 표시되지 않던 버그 수정


2. 메인 보스

	- 바드의 스킬 사용 후, 쿨타임이 돌지 않던 버그 수정
	- 바드의 공속 감소 효과(-20%)가 현재 공속에 비례하여 적용 됩니다.
	- 실드의 보호막 효과가 업그레이드 됩니다. 최대 체력의 5% > 2%



3. 영웅 

액티브 스킬을 사용하지 않는 일반 영웅들이 약세를 보이며, 일반 영웅의 선택이 필수적인 상황입니다. <br>
전략의 다양성을 높이기 위해 보드 위 영웅 등장확률이 상향됩니다.

	- 일반: 12 > 16%
	- 특수: 6 > 8%
	- 전설: 2 > 4%


4. 영웅 밸런싱

영웅들의 등장 확률의 증가로 영웅 대부분이 간접적인 버프 효과를 받습니다.
OP로 분류되는 영웅들의 스킬들이 조정됩니다.

	**영주**
	영주의 공격은 투사체가 아닌 즉시 발동형으로 월등히 높은 딜량을 기록하고 있습니다.
	기본 공격 속도가 감소합니다. (1 > 0.5 )

	**음악가**
	공속 증가량이 감소합니다.
	기존: 4 / 6 / 8 / 12 % > 변경: 2 / 4 / 6 / 8 %

	**조련사**
	공속 증가량이 감소합니다.
	기존: 2 / 4 / 6 / 10 % > 변경: 2 / 3 / 4 / 5 %

	**군인**
	공속 증가량이 감소합니다.
	기존: 8 / 12 / 16 / 24 % > 변경: 6 / 8 / 12 / 16 %



5. 웨이브 밸런싱

단일 데미지를 가하는 영웅 대비, 제어기를 가진 영웅 및 범위 데미지를 가하는 영웅들의 효율이 낮습니다.<br>
적들의 이동속도 및 개체수가 변경됩니다.

	- 메인 보스를 제외한 나머지 적들의 이동속도: 3 > 2.5 (-20%)
	- 적들의 개체수 증가: 8 > 9
	- 정복자 소환물 이동속도: 4.5 > 3.75
	- 적들의 기본 체력 배수: 50 > 40
	- 10 웨이브 이상: 적들의 이동속도 20% 증가
	- 10 웨이브마다 적들의 체력이 10% 추가로 증가합니다.
	- 30 웨이브 이상: 적들의 개체수 1 추가 증가



6. 경제

현재는 영웅을 획득 후, 방출하여 선택 영입하는 것의 효율이 지나치게 높습니다.<br>
영웅 선택 영입에 필요한 문스톤이 증가합니다.

	- 일반: 40 > 60
	- 특수: 60 > 180
	- 전설: 360 > 540



7. 모드

탐험모드가 리워크될 예정입니다. 이번 업데이트에서는 비활성화 됩니다.



8. 기타

	- 블럭을 합칠 때의 시각 효과가 추가됩니다.
	- 시즌 보상의 단위가 증가합니다. (20 > 40)



그럼 다음 업데이트까지 함께 2048! 🔥

<br>

## 3.0.6 - 3.0.7
메인 보스들이 등장합니다. 
메인 보스들은 주기적으로 강력한 스킬을 사용하기 때문에, 스킬을 확인하고 대응 전략이 필요합니다.

1. 메인 보스 
     - 5 웨이브마다 등장합니다. 
     - 게임 시작 및 보스를 처치하였을 경우, 다음 등장할 메인 보스가 결정됩니다.
        
	
2. 신규 모드: "디펜스 모드"
     - 2048을 만들어도 게임은 계속 됩니다.
     - 10 웨이브부터 50 웨이브까지 높은 웨이브를 달성할 수록 보상이 높아집니다.
     - 10 웨이브 이상일 경우에 랭킹이 기록됩니다.
     - 디펜스 모드 랭커 달성 퀘스트가 추가되었습니다.
     - 낮은 확률로 디펜스 모드에서만 등장하는 메인 보스가 등장합니다.
     - 골든키를 통해 입장가능하며, 1일 3개의 골든키가 주어집니다. (골든키 패스 적용시 5회)
        
	
3. 몬스터 및 웨이브 조정 
     - 웨이브 순서: "일반 웨이브 - 영웅 웨이브 - 일반 웨이브 - 영웅 웨이브 - 메인 보스 웨이브"
     
     
4. 시민
     - 3.0.5 패치에 적용된 웨이브당 에너지 양의 증가는 시민을 지나치게 강하게 만들었습니다.
     - 에너지 수급량 및 건축가와의 시너지를 고려하여, 스킬 확률이 조정되었습니다.       
     - 스킬 확률: 30/40/50/70 --> 30/35/40/50


5. 편의성
     - 설정 패널에서 블럭의 스타일을 결정할 수 있습니다. 
     - 몹에게 입히는 데미지량이 표시됩니다.
     - 덱 구성시 선택된 덱이 변경되는 버그를 수정하였습니다.


6. 상점 
     - 신규 상품 탭이 추가되었습니다.
     - 상품 구매 관련 버그가 수정되었습니다.
     
     
7. 기타
     - 실시간 대전 서버가 확대 되었습니다.
     - 앱이 보다 효율적으로 동작합니다.
     
     

## 3.0.5
저레벨 구간에서도 2048을 만드는 전략이 가능하도록 에너지 획득량이 증가하였습니다.
이에 따라 관련 수치들이 조정됩니다.

1. 에너지 기본 획득
     - 시작시: 5 --> 8
     - 웨이브 종료시: 5 --> 8

2. 블럭 위 영웅 등장 확률
     - 일반: 16 --> 12
     - 특수: 8 --> 6
     - 전설: 4 --> 2
        
3. 몬스터 및 웨이브 조정 
     - 웨이브당 몹 개체수: 7 --> 8
     - 3웨이브 마다 등장하는 영웅 몹 체력: 50% 상향
     - 일반/보스 몹 이동 속도: 3.2 -->3
     - 정복자가 소환한 몹: 4.8 --> 4.5

4. 시민
     - 스킬 확률: 60/70/80/100 --> 30/40/50/70


열쇠로 보상을 획득할 수 있는 상자의 보상이 대폭 상향하고, 열쇠 요구개수가 높아졌습니다.

1. 상자 
     - 골드, 영웅 보상 확대 (약 5배의 가치)
     - 전설 영웅: 1% --> 10%
     - 필요한 열쇠: 20 --> 40개    

2. 골드로 영웅을 얻는 상품 제거
     - 영웅 수량에 비해 레벨업에 필요한 골드가 많기 때문에, 상자에서 골드를 얻을 수 있는 가치를 높였습니다.
     - 영웅 레벨업 이외에 골드를 사용할 수 있는 추가 컨텐츠가 나올 계획입니다.


편의성 및 성능 개선

1. 배터리 소모 감소 및 성능 향상
2. UI 개편 및 버그 픽스  
3. PvP 대기 시간이 5초로 고정됩니다. 높은 리스에서는 최대 8초 입니다.
4. 채팅이 비활성화 되었습니다. 친구 추가 기능 등 사용성을 보완하여 다시 활성화될 예정입니다.

## 3.0.4
게임이 빠른 시점에 승부가 결판나는 경우가 많습니다. 2048 블럭을 달성하는 등 다양한 전략을 플레이 할 수 있도록 몬스터의 이동속도를 조정하였습니다.

1. 이동속도 변화
     - 일반 몬스터 : 3.5 --> 3.2
     - 보스 몬스터 : 3.5 --> 3.2
     - 정복자 소환 선봉대 : 5.25 --> 4.8
     - 정복자 소환 장군 : 5.25 --> 4.8

2. 적 생성 주기: 0.4초 --> 0.5초


## 3.0.1
새로 등장한 군대 그룹의 전설 영웅 '정복자'가 특별한 전략 없이도 강력한 모습을 보여주고 있어
전략적인 활용이 필요하도록 스킬을 밸런싱 하였습니다.

1. 정복자
     - 스킬 능력 : 100% 체력 3명의 군대를 보냄 
                    -> 이동속도가 50% 빠른 50% 체력의 선봉대 및 150% 체력의 장군을 보냄

## 2.0.9
1. 항해사 (스킬 리워크)
     - 맨 앞의 적들을 (1/1.5/2/3) 거리만큼 뒤로 밀어냄

2. 도박사
     - 블럭을 합치면 50%확률로 파란 카드(승)와 빨간 카드(패) 중 하나를 뽑습니다.
     - 블럭 숫자에 따른 성장치가 제거되었습니다.
     - 최대 (2/3/4/5) 에너지를 얻거나 -1 에너지

3. 점술가
     - 공격 중인 대상에 스킬을 사용합니다.
     - 위기 상황이나 플레이어가 전략적으로 활용할 수 있도록 모든 레벨에서 스킬 발동 확률이 100%가 되었습니다.
     - 스킬 데미지 수치가 조정되었습니다. (20%/30%/40%/50%)
     - 블럭 숫자에 따른 성장치(스킬데미지 5%)가 적용됩니다.

<br>
## 2.0.8
2048 히어로즈는 빠른 2048 블럭의 달성, 혹은 높은 공격력을 활용해 웨이브를 처리해 상대의 기지를 폭파시켜
승리할 수 있습니다.

하지만 현재의 블럭 성장방식에서는 2048을 달성하기 위해 숫자를 올리는 과정이 곧 공격력을 높이는 방향이 되어
2048 블럭을 달성하는 전략을 공격적인 덱 등을 활용하여 파훼하기 어려웠습니다.

이러한 문제점을 개선하기 위해 블럭을 합칠때 공격력의 증가량을 아래와 같이 수정하였습니다.
이를 통해 2048 블럭의 달성에 가까워 질 수록 전체 공격력을 낮추어 리스크를 높였습니다.
관련 사항은 설정의 튜토리얼에서 확인 가능합니다.

1. 블럭의 공격력 성장치
	 - 기존 : 블럭 결합시 공격력 50% 증가
	 - 수정 : 첫 블럭 결합시 공격력 90% 증가, 이후 80%, 70%...형식으로 증가폭 순차적 감소
	          
이에 따라 전체 보드의 공격력이 상향되어, 몬스터 및 기지의 체력도 증가하였습니다.

2. 웨이브 난이도 수정
	 - 단계별 몬스터 체력 증가량 : 25 -> 50
	 - 단계별 보스 몬스터 체력 증가량 : 50 -> 100
	 - 기지 체력 : 1024 -> 2048

이와 연관된 몬스터에 대한 고정 피해, 기지 체력 회복 스킬의 값이 조정되었습니다.

3. 구원자
     - 체력 회복량 : 12, 14, 16, 20 -> 32, 34, 36, 40
4. 요리사
     - 체력 회복량 : 8, 10, 12, 16 -> 24, 26, 28, 32
5. 농부
     - 추가 피해량 : 20 -> 40
6. 폭도
     - 추가 피해량 : 20 -> 40
7. 소총수
     - 추가 피해량 : 40, 60, 80, 120 -> 80, 120, 160, 240
8. 경계병
     - 추가 피해량 : 4, 8, 16, 32 -> 20, 30, 40, 60
     - 레벨 성장치 : 2 -> 10

또한 일부 캐릭터에 대한 밸런스 조정이 이루어졌습니다.

9. 혁명가 (1.2.2 버전 롤백)
     - 발동조건 조정 : 단계 별 128, 64, 32, 16 -> 256, 128, 64, 32 
10. 영주
     - 기존 :처치한 적의 수가 블록 합친 횟수x2 에 도달하면 숫자가 오름,  레벨 별 추가피해
     - 수정 : 처치한 적의 수가 12, 11, 10, 8에 도달하면 숫자가 오름, 추가 피해 삭제
11. 연금술사
     - 발동주기 조정 : 매 24, 22, 20, 16 -> 20, 18, 16, 12초 마다 에너지 1 획득 
     
이와 함께 신규 퀘스트 2종이 추가되었습니다.


## 2.0.7
현재 웨이브 정리보다 퍼즐 위주의 플레이가 PvP모드에서 강력함을 보여주고 있습니다.
전략의 다양성을 확보할 수 있도록 아래와 같은 변경이 적용됩니다.

1. 선장
     - 발동 확률 : 100%
     - 발동 대상 : 3/4/6/99 대상
     - 스킬 능력 : 2초간 스턴 및 스턴상태의 적 처치시 에너지 1 획득
     - 블럭 성장 : 블럭 숫자에 따라 스턴시간 0.5초 추가

## 2.0.5
현재 웨이브 정리보다 퍼즐 위주의 플레이가 PvP모드에서 강력함을 보여주고 있습니다.
전략의 다양성을 확보할 수 있도록 아래와 같은 변경이 적용됩니다.

1. 웨이브 수정
     - 웨이브 시작 딜레이 단축 : 1초 -> 0.3초

2. 스킬 메커니즘 수정
     - N 달성시 스킬을 가진 영웅들(정치가, 혁명가)이 더이상 혁명가, 연설가에 의해 스킬이 발동되지 않습니다.
     - 건축가가 빈블럭을 만들 때, 시민 등장이 가능해짐

## 2.0.0
이번 패치에서는 새로운 종족 '야생'의 등장과 함께 첫번째 시즌이 시작됩니다.

시즌의 시작을 앞두고 게임 내 일부 개편이 진행됩니다.

기존 '침묵'룬은 보스가 등장하면, 모든 영웅의 스킬을 제한하는 룬이었습니다.
하지만 부족한 시각적인 효과와 함께, 패시브, 액티브 스킬에 따라 룬을 적용함에 모호함이 있었습니다.
이를 개선하기 위하여 '침묵'룬을 '석화'룬으로 수정합니다.

1. '침묵'-->'석화'개편
     - '석화'의 대상은 3초간 스킬과 공격 모두 불가능 한 상대가 됩니다.
     - '석화'룬을 갖은 영웅이 등장하면, 상대 보드위의 적은 매 3초 마다 석화의 대상이 됩니다.

의사는 흔히 알려진 역병의사를 바탕으로 디자인되었습니다. 영웅의 모습에 잘 부합하며, 다른 영웅들과 시너지를 발휘할 수있는 스킬로 개편되었습니다.

2. 의사 스킬 개편     
     - N회 공격시 출혈을 유발하는 범위 공격을 합니다.

## 1.2.2
2048 heroes는 타워 디펜스를 기반으로, 다양한 영웅의 스킬들과 함께 퍼즐을 풀어나가며 자신만의 전략으로 상대를 제압하는 전략형 타워디펜스 게임입니다.

검객이나 폭도와 같은 공격력이 좋은 영웅을 기용해 웨이브를 빠르게 정리해 상대를 압박하거나, 
개척자, 연설가와 같이블럭의 숫자를 올리는 스킬을 통해 2048을 빠르게 달성하는 등
영웅들의 개성을 살려 다양한 전략을 플레이 할 수 있도록 기획되었습니다.

하지만 현재 웨이브 설계상 몬스터 체력이 낮아
타워 디펜스 플레이와 퍼즐 플레이중 퍼즐 플레이에 상대적으로 유리한 모습을 보여주고 있습니다.
이를 개선해 다양한 플레이가 가능하도록 웨이브 구성 및 영웅의 공격속도를 변경하였습니다.

1. 웨이브 난이도 수정
     - 이동속도 : 3.4 -> 3.5
     - 단계별 몬스터 체력 증가량 : 10 -> 25
     - 웨이브당 몬스터 등장 : 10 -> 7
2. 영웅 능력치 수정
     - 공격속도 : 초당 0.5회 -> 초당 1회

또한 전설 등급의 달성형 스킬을 사용하는 영웅들이 높은 스킬발동 요구치로 인해 활용도가 떨어지고 있습니다.
이를 개선하기 위하여 전설등급의 달성형 스킬도 정치가와 같은 수준으로 상향됩니다.

3. 혁명가
     - 발동조건 조정 : 단계 별 256, 128, 64, 32 -> 128, 64, 32, 16
4. 선장
     - 발동조건 조정 : 단계 별 256, 128, 64, 32 -> 128, 64, 32, 16

<br>


<br>

## 1.2.1
1. 웨이브 난이도 수정
     - 이동속도 : 3.5 -> 3.4
     - 생성주기 : 0.4 -> 0.35
2. 블럭 상승 성장치 수정
     - 발동확률 상승치 변경 : 10% -> 5% (탐색대, 점술가, 외교관, 잡상인, 건축가, 의사, 연설가)
     - 발동확률 상승치 변경 : 10% -> 3% (도박사, 선원, 항해사)
     - 발동확률 상승치 변경 : 10% -> 1% (목수)
     - 발동확률 상승치 변경 : 1% -> 2% (순찰대)
     - 발동범위 상승치 변경 : 10% -> 5% (농부, 폭도)
3. 연금술사
     - 발동시간 조정 : 단계 별 28, 26, 24, 20 -> 24, 22, 20, 16
4. 요리사
     - 계수 조정 : 단계 별 4, 5, 6, 8 -> 8, 10, 12, 16
5. 점술가
     - 발동확률 조정 : 단계 별 60, 80, 100, 100 -> 60, 70, 80, 100
     - 데미지 조정 : 단계 별 30, 30, 30, 50 -> 30 고정
6. 군인
     - 공격속도 조정 : 단계 별 8, 16, 24, 32 -> 8, 12, 16, 24
7. 영주
     - 추가 공격력 조정 : 단계 별 10, 20, 30, 50 -> 4, 8, 12, 20
8. 도박사
     - 발동확률 조정 : 단계 별 30, 40, 50, 50 -> 30, 35, 40, 50
     - 획득재화 조정 : 단계 별 최대 3, 3, 3, 4 -> 3 고정
9. 구원자
     - 계수 조정 : 단계 별 8, 10, 12, 16 -> 12, 14, 16, 20
10. 선원
     - 발동확률 조정 : 단계 별 60, 70, 80, 100 -> 30, 35, 40, 50
11. 목수
     - 발동확률 조정 : 단계 별 10, 20, 30, 50 -> 10, 12, 14, 16
12. 항해사
     - 발동확률 조정 : 단계 별 20, 30, 40, 50 -> 30, 35, 40, 50


<br>

## 1.2.0
1. 선장
     - 발동 확률 : 100%
     - 발동 대상 : 블럭 합친 수에 따라 1마리 씩 증가
     - 스킬 능력 : 256/128/64/32 이상 달성 시 기절한 적이 죽을때 마다 에너지 획득
2. 대법관
     - 발동 확률 : 10% 및 블럭 합친 수에 따라 1%씩 증가
3. 경계병
     - 블럭 합친 수에 따른 공격력 증가량 변동 (4->2)
     - 범위 공격 영역 감소
