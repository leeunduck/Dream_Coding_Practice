# Position

Position 속성은 5개의 값을 갖습니다.


## static

>기본값, 다른 태그와의 관계에 의해 자동으로 배치되며 위치를 임의로 설정해 줄 수 없습니다.

 

## absolute & relative

>relative 인 컨테이너 내부에 absolute인 객체가 있으면 절대 좌표를 계산할 때 relative 컨테이너를 기준으로 잡게 됩니다.

```
<html>
<head>
	<style>
		#box-container{ position: relative; height: 90px; margin-top: 40px; border: 2px solid red; }
		#box-inner{ position: absolute; top: 30px; left: 20px; border: 2px solid blue; }
	</style>
</head>
<body>
	<div id="box-container">
		컨테이너
		<div id="box-inner">absolute 박스</div>
	</div>
</body>
</html>
```
**absolute 박스가 ralative 속성 안에 있음으로 기준은 relative기준이 됩니다.**

 

## fixed 

>스크롤과 상관없이 항상 문서 최 좌측상단을 기준으로 좌표를 고정합니다.

주로 네비개이션 바를 만들때는 바닥글 부분을 작업할떄 많이 사용합니다.

 

## inherit

부모 태그의 속성값을 상속 받습니다.
