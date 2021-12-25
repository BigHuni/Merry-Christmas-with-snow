# 🎄 눈 내리는 배경의 크리스마스 맞이하기
- https://bighuni.github.io/Merry-Christmas-with-snow/Merry-Christmas-with-snow/

## 🔸 목적
- 파이썬은 1989년 12월 크리스마스를 심심하지 않게 보내려고 네덜란드 귀도 반 로섬(Guido van Rossum)이 혼자 만들었다.
- 나 대훈 허(Daehun Heo)도 HTML, CSS, JavaScript 친구들과 함께 이번 2021년 12월 크리스마스가 심심하지 않게 보내려고 만들었다.

<br>

---

## 🔸 스타일
- body의 height 값으로 100vh 설정함으로써 웹 브라우저의 높이와 일치
- 단색의 배경의 단조로움을 피하기 위해 원형 그라이데이션(redial-gradient) 함수 사용
- 원형 그라이데이션(redial-gradient) 속성 값으로 중심 아래쪽이 원형의 중심이 되도록 'ellipse at bottom' 사용
- '애니메이션 snow' 지정으로 투명도, transform 값을 부여하여 위에서 아래로 이동하는 눈 표현(snow 10s linear infinite)
- 눈이 단조롭게 내리는 것을 피하기 위해 snow 클래스의 'nth-of-type()' 선택자를 이용하여 여러 개 눈들 각각 별도로 값 지정

---

## 🔸 주의사항
- 웹 브라우저 크기를 조정 시 눈이 화면 밖으로는 내리지 않는 것을 볼 수 있는데, 최초 화면일 때의 눈을 내리게 하는 랜덤 수치의 값이 유지되고 있기 때문에 새로고침을 하게 되면, 재계산하여 바뀐 화면 크기에서도 잘리지 않고 볼 수 있게 된다.
