# **Website Redesign Project:**
### 와일드 리프트 Wild Rift

<br/>

**박서영, Park seo young**    
김채연, Kim chae yeon     
엄지승, Eom Ji Seung      
조효희, Jo hyo hee    

<br/>
<br/>
<br/>

### **Schedule**
> 2025.06.17. - 2025.06.22. (5h - 6h, weekdays only)

</br>

> 1. Planning: 2025.06.17.
> 2. Design: 2025.06.17. - 2025.06.20.
> 3. Development: 2025.06.18. - 2025.06.22.

<br/>
<br/>
<br/>

<details>
<summary>🇺🇸 English</summary>

# Wild Rift
Wild Rift

</details>

<details>
<summary>🇯🇵 日本語</summary>

# Wild Rift
Wild Rift

</details>

<br/>
<br/>
<br/>

## 목차

1. [프로젝트 개요](#1-프로젝트-개요)   
2. [파일 구성](#2-파일-구성)   
3. [주요 기능 소개](#3-주요-기능-소개)    
4. [작업 환경](#4-작업-환경)   
5. [관련 링크](#5-관련-링크)
   
</br>
</br>
</br>

---

## 1. 프로젝트 개요

### 1.1. 작업 배경
와일드 리프트는 리그 오브 레전드의 모바일 버전으로, 빠른 게임성과 모바일에 최적화된 조작으로 인기를 얻었다. 하지만 공식 웹사이트 및 관련 홍보 페이지는 브랜드의 고유한 세계관, 캐릭터 개성, 플레이 방식 등을 충분히 전달하지 못하고 있으며, 시각적 몰입감과 정보 전달력 측면에서 개선의 여지가 있었다. 특히 신규 유저에게는 복잡한 정보 구조와 부족한 시각적 가이드로 인해 접근이 어렵고, 기존 유저에게도 콘텐츠 업데이트나 이벤트 정보 전달이 단편적이라는 문제가 있었다.

</br>

이 프로젝트의 목적은 다음과 같다

</br>

1. 리그 오브 레전드의 IP를 적극 활용해 세계관과 캐릭터의 개성을 시각적으로 강조한다.     
2. 게임 콘텐츠 정보를 명확하게 전달하는 구조를 설계한다.         
3. 신규 및 기존 유저 모두에게 몰입감 있는 사용자 경험을 제공하는 디자인을 구현한다.    

</br>
</br>
</br>

### 1.2. 키워드
1. **브랜드 아이덴티티**      
    1.1. 리그 오브 레전드 특유의 색상, 일러스트, UI 스타일을 적극적으로 반영          
    1.2. 챔피언의 음성, 음악, 영상 등 다양한 IP 콘텐츠를 활용해 감각적인 몰입감 부여          
    
</br>

2. **접근성**     
    2.1. 정보 계층의 재구성      
    
</br>

3. **유입 및 유지 유도**    
    3.1. 신규 챔피언, 시즌 이벤트 등의 최신 콘텐츠를 시각적으로 강조하여 유저의 관심을 유도          
    3.2. 기존 PC 플레이어에게 익숙한 요소(세계관, 챔피언 배경 등)를 접목시켜 유입을 자연스럽게 유도         
    

</br>
</br>
</br>

---

## 2. 파일 구성

```
🎮 WebRedesign-WildRift
 ┣ 📂 fonts
 ┣ 📂 images
 ┣ 📂 audios
 ┣ 📂 sounds
 ┣ 📂 videos
 ┣ 📂 include
 ┣ 📂 pages
 ┣ 📂 scss
 ┣ 📂 css
 ┗ 📂 js
   📄 index.html
```

</br>
</br>
</br>

---

## 3. 주요 기능 소개
### 3.0. 작업 분담
#### **👑 박서영**
1. 정보 전달 영역
2. 메인 페이지: 게임 설명 / 이벤트 / 푸터
3. 서브 페이지: 공지사항 / 공지사항 상세 페이지 (글 / 영상)

</br>
</br>
</br>

#### 김채연
1. 비주얼 및 사운드 콘텐츠 영역
2. 메인 페이지: 헤더 + 메인 비주얼 / 플레이 리스트
3. 서브 페이지: 몬스터 리스트 / 몬스터 상세 페이지 (내셔 남작)

</br>
</br>
</br>

#### 엄지승
1. 비주얼 및 정보 전달 영역
2. 메인 페이지: 신규 캐릭터 (시간의 수호자 질리언) / 게임 모드
3. 서브 페이지: 스킨

</br>
</br>
</br>

#### 조효희
1. 정보 전달 및 배너 영역
2. 메인 페이지: 캐릭터 리스트 / 패치 노트 / 라이엇 게임즈
3. 서브 페이지: 캐릭터 (다리우스)

</br>
</br>
</br>

---

### 3.1. 메인 페이지
### 3.1.1. 헤더 + 메인 비주얼 (김채연)
1. 가장 처음 접근시 로고 아래에 게임 트레일러 영상이 등장함으로 사용자의 궁금증을 유도했다.
2. 스크롤시 로고와 영상은 같이 확대되며 로고는 사라지며, 영상이 화면을 꽉 채우게 된다.
3. 와일드 리프트의 로고가 한 번 떠오르며, 이후에 다운로드 버튼이 떠오르도록 구성했다.
4. 헤더의 경우, 간단하게 서브 페이지로 이동할 수 있도록 제작하였다.

<br/>
<br/>
<br/>

### 3.1.2. 게임 설명 (박서영)
1. 좌측 하단의 아이콘 클릭시 탭 형태를 사용하여 내용이 변경되도록 하였다.
2. 휴대폰 프레임을 사용하여 와일드 리프트의 모바일 게임이라는 정체성을 강조하였다.
3. 강조 포인트에 컬러와 볼드를 주어 내용 흐름에 중요도를 주었다.

<br/>
<br/>
<br/>

### 3.1.3. 신규 캐릭터 (시간의 수호자 질리언) (엄지승)
1. 캐릭터 이름 및 스토리, 스킬 세팅을 소개하는 섹션이다.
2. 우측에는 챔피언 영상과 스킬 버튼이 존재하며, 스킬 버튼을 클릭하면 그에 맞는 설명이 등장하도록 하였다.

<br/>
<br/>
<br/>

### 3.1.4. 이벤트 (박서영)
1. 아코디언 형태를 활용하여, 카드 클릭시 flex의 너비값이 변경되게 하였다.
2. 아코디언 메뉴가 접혔을 때의 이미지와 펼쳐졌을 때의 이미지는 너비값이 다르도록 하였다.
3. 메인 페이지에서 필요한 핵심 정보만을 담아 내용이 사용자에게 보다 간결하게 읽히도록 구성하였다.

<br/>
<br/>
<br/>

### 3.1.5. 게임 모드 (엄지승)
1. 게임의 다양한 모드에 대해 소개하는 섹션이다.
2. 주 모드와 모험 모드, 두 가지로 나누어 구성하였으며 그에 맞는 영상과 설명이 등장하도록 구현하였다.
3. 모험 모드를 클릭했을 때에는 좌측에 여러 모드의 아이콘이 등장하며, 아이콘을 클릭하면 영상과 설명이 바뀌도록 하였다.

<br/>
<br/>
<br/>

### 3.1.6. 캐릭터 리스트 (조효희)
1. 캐릭터 소개 섹션이다. 각 라인별로 가장 인기 있는 캐릭터의 설명이 등장하도록 하였다.
2. 좌측에는 캐릭터의 이름과 설명이 쓰여 있으며, 자세히 보기 버튼 호버시 컬러가 변화하고 클릭시 서브 페이지로 이동하도록 하였다.
3. 좌측 아래 스킬 버튼 박스 호버시 박스 쉐도우가 등장한다.
4. 중앙 캐릭터는 우측에서 등장하는 AOS를 활용하여 동적으로 보이도록 제작했다. 또한, 캐릭터 변경시 각 캐릭터의 목소리가 재생되도록 구현하였다.
5. 우측에는 라인별 인기 캐릭터 다섯 가지를 보여주는 스와이퍼가 있으며, 자동 재생과 내비게이션이 존재한다.
6. 하단에는 라인 선택 버튼이 있으며, 버튼 호버시 컬러가 변경된다. 클릭시에는 해당 라인의 인기 캐릭터가 등장한다.

<br/>
<br/>
<br/>

### 3.1.7. 플레이 리스트 (김채연)
1. 리그 오브 레전드의 음악을 직접 들어볼 수 있는 섹션이다.
2. 제목은 음악의 장르와 리그 오브 레전드라는 게임의 다양성 · 획일화 되지 않은 개성넘치는 이미지를 표현 하기 위해 각기 다른 폰트로 구성되었다.
3. 중앙의 디스크들은 스와이퍼를 사용하여 슬라이드 형태로 제작했다.     
   3.1. 디스크는 호버시 스케일 값과 블러 값이 변경된다.        
   3.2. 중앙의 활성화된 디스크가 아닌 디스크를 호버할 경우, 스케일 값이 커지며 음악 제목과 가수명이 등장한다.        
   3.3. 플레이 버튼과 퍼즈 버튼을 클릭하여 활성화된 디스크의 음악의 재생을 제어할 수 있다.          
   3.4. 음악이 재생되면 중앙 디스크의 애니메이션이 재생되어 오디오 비주얼라이저의 효과를 내도록 하였다.        
   3.4. < > 모양의 내비게이션을 활용하여 다음 음반 디스크로 이동할 수 있도록 하였다.        
   3.5. 좌측의 햄버거 버튼 클릭시 디스크 목록이 좌측 사이드 메뉴로 등장하며, 음악을 클릭하면 해당 음악 디스크로 이동할 수 있도록 하였다.     
   3.6. 사이드 메뉴에서 현재 재생 중인 음악을 확인할 수 있다.     
   3.7. 디스크 이동시 무조건 음악 재생은 자동으로 멈추게 된다.     
   3.8. 디스크 이동시 배경이 변화되도록 하였다.      
   3.9. 우측의 링크 연결 버튼은 공식 뮤직비디오 등으로 이동하는 기능을 수행하게 된다. (구현 X)      

<br/>
<br/>
<br/>

### 3.1.8. 패치 노트 (조효희)
1. 와일드 리프트 패치 노트에 대한 배너이다.
2. 최근 업데이트 버전으로 제작하였으며, 좌측에는 타이틀을, 우측에는 로고를 넣어 디자인하였다.

<br/>
<br/>
<br/>

### 3.1.9. 라이엇 게임즈 (조효희)
1. 라이엇 게임즈와 관련된 게임을 소개하는 섹션이다.
2. 게임 카드 호버시 타이틀 박스의 길이가 길어지며 살펴보기 버튼이 등장한다.

<br/>
<br/>
<br/>

### 3.1.10. 푸터 (박서영)
1. 기존 푸터의 구조는 대체로 유지하되, SNS 항목은 필요성을 느끼지 않아 제외하는 형태로 구성하였다.
2. 탑 버튼은 일정 스크롤 이후에만 등장하며, 클릭시 부드럽게 상단으로 이동해 사용자에게 시각적 편의성을 제공하도록 하였다.
3. 또한, 탑 버튼에 마우스를 올리면 화살표 아래에 그림자 형태의 박스가 생겨 마우스 사용 여부를 직관적으로 인지할 수 있도록 하였다.

</br>
</br>
</br>

---

### 3.2. 서브 페이지 (총 7개)
### 3.2.1. 공지사항 (박서영)
1. 기존의 게시판 · 갤러리 형태의 공지사항 틀에서 벗어나, 카드의 플립 형태를 활용해 사용자에게 색다른 경험을 제공하고자 하였다.
2. 각 카드의 앞면에는 이미지, 제목, 요약 내용, 날짜를 포함해 앞면만으로도 핵심 정보를 사용자가 인지할 수 있도록 구성하였다.
3. 각 카드의 뒷면에는 제목, 날짜, 상세 내용 또는 이미지가 배치되었으며, '자세히 보기' 버튼을 통해 상세 페이지로의 자연스러운 이동을 유도하도록 하였다.
4. 마우스 호버시 카드를 뒤집는 듯한 애니메이션을 적용하였으며, 사용자가 클릭해야 한다는 인식을 시각적으로 전달하고자 하였다.

<br/>
<br/>
<br/>

### 3.2.2. 공지사항 상세 페이지 (글 / 영상) (박서영)
1. 상단에는 브레드 크럼을 배치해 사용자가 공지사항 페이지나 메인 페이지로 쉽게 이동할 수 있도록 하였다.
2. 진입 전 공지사항 페이지에서 배치되었던 대표 이미지를 상세 페이지 상단에 크게 노출해, 사용자가 해당 콘텐츠임을 직관적으로 인식할 수 있도록 하였다.
3. 글 기반 상세 페이지는 정보 전달에 집중할 수 있도록 레이아웃을 최대한 깔끔하게 구성하였다.
4. 영상 기반 상세 페이지는 페이지 내에 영상 콘텐츠를 포함해 기존의 단순한 링크 연결에서 확장하여 정보 전달력을 높였다.
5. '이전 글'과 '다음 글' 기능을 제공해 연속적인 콘텐츠 탐색이 가능하도록 하였으며, 다음 글이 없는 경우 컬러값이 달라 클릭 유도를 방지할 수 있도록 하였다.

<br/>
<br/>
<br/>

### 3.2.3. 몬스터 리스트 (김채연)
1. 탭 구조를 활용해 몬스터 카테고리를 나누도록 하였다.
2. 짤막한 카테고리의 설명을 배치하여 몬스터의 전체적인 컨셉을 알 수 있도록 하였다.
3. 스와이퍼를 사용해 몬스터의 정보를 스와이프로 보다 쉽고 빠르게 인지할 수 있도록 하였다.        
   3.1. 슬라이드에는 몬스터의 외형뿐만 아니라, 이름, 설명, 등장 위치까지 콘텐츠에 포함하여 상세 페이지로 접근하지 않아도 기초적인 정보를 바로 확인할 수 있도록 하였다.        
   3.2. 게임 이해와 플레이에 요구되는 내용은 TIP 태그를 달아 시선을 유도하도록 하였다.         
   3.3. 하단의 몬스터 아이콘을 클릭하면 해당 슬라이드로 이동하며, 아이콘은 불투명도를 조절하여 사용자가 '보고 있는' 정보와 '보고 싶은' 정보, '보지 않는' 정보의 계층을 뚜렷하게 나타내고자 하였다.        
4. 스와이퍼 하단의 세 가지 콘텐츠는 와일드 리프트의 정보성 글로 이동하는 이미지로, 구현은 하지 않았다.         

<br/>
<br/>
<br/>

### 3.2.4. 몬스터 상세 페이지 (내셔 남작) (김채연)
1. 몬스터 리스트 페이지의 '더보기' 버튼을 클릭했을 때 이동하는 페이지이다.
2. 몬스터의 배경과 3D 모델링, 크게 배치한 몬스터 이름 등으로 비주얼적인 요소를 강조하고자 하였다.
3. 각 정보로 이동할 수 있는 내비게이션을 이름 밑에 바로 배치함으로 사용자의 편의성을 높이고자 하였다.
4. 몬스터에 대한 간단한 설명과 맵 등장 위치를 지나면, 본격적인 몬스터의 정보를 확인 가능하며, 이때 리그 오브 레전드 게임 시리즈인 '전략적 팀 전투'를 참고하여 디자인하였다.
5. 각 정보는 특정 스크롤 값이 되면 사라지며, 비주얼적인 요소는 계속 강조되게 되도록 하였다.
6. 정보 섹션이 종료되면 페이지 내부에서 같은 카테고리의 다른 몬스터 페이지로 이동할 수 있는 스와이퍼가 바로 배치되도록 하였다.    
   6.1. 각 슬라이드마다 몬스터 이미지, 3D 모델링, 이름과 간단한 설명이 등장하도록 디자인하였다.    
   6.2. 활성화된 슬라이드를 마우스 호버하면 스케일 값이 변경되도록 하였다.      

<br/>
<br/>
<br/>

### 3.2.5. 캐릭터 (다리우스) (조효희)
1. 캐릭터의 이미지를 배경으로 사용하여 캐릭터의 이름, 특징, 로고를 배치해 메인 비주얼을 더욱 강조할 수 있도록 하였다.
2. 캐릭터 설명은 동적 구현을 위해 노력하였다.      
   2.1. 좌측은 AOS를 활용하여 캐릭터가 좌측에서부터 등장하도록 하였다.     
   2.2. 우측은 캐릭터 설명에 대한 부분으로 캐릭터 명대사, 설명, 특징 등으로 구성되었다. 스킬 이미지는 호버시 ↑ 방향으로 움직이는 애니메이션을 적용하였다.
3. 캐릭터 스킬 섹션에서는, 스킬 이미지 클릭시 해당 동영상이 우측에서 등장하며 아래는 설명이 배치되도록 하였다.
4. 가장 하단에는 와일드 리프트의 캐릭터들을 이어 애니메이션을 적용하였으며, 오버레이를 통해 어두운 분위기를 살릴 수 있도록 하였다.

<br/>
<br/>
<br/>

### 3.2.6. 스킨 (엄지승)
1. 캐릭터가 보유한 스킨을 확인할 수 있는 페이지이다.
2. 상단에 카테고리와 검색 칸을 두어 사용자 편의성을 높였다.
3. 캐릭터 카드 호버시 이미지가 커지며 동적인 느낌을 주도록 하였다.
4. 캐릭터 카드 선택시 캐릭터가 보유한 스킨들을 스와이퍼 형식으로 볼 수 있도록 하였다.



</br>
</br>
</br>

---

## 4. 작업 환경
### 4.1. 사용 프로그램
1. 노션: 작업 기록
2. 피그마: 기획, 디자인
3. 포토샵: 디자인
4. VS Code

</br>
</br>
</br>

### 4.2. 사용 언어
1. HTML
2. SCSS (CSS Preprocessor)
3. JavaScript

</br>
</br>
</br>

### 4.3. 작업 해상도
1. PC 기준 1920X1080
2. PC 기준 3440X1440
   
</br>
</br>
</br>

### 4.4. 윈도우 버전
1. Window 10
2. Window 11

</br>
</br>
</br>

---

## 5. 관련 링크

</br>
</br>
</br>

---
