# 2D
## What is 2D?
2D에서 D는 Dimension,차원을 뜻한다. 즉 2D는 이차원을 말하는데, 이것은 X축과 y축으로만 구성된 공간이다. 점,선,면의 위상을 띄고 있으며 입체적이지 않고 평면적이다.
### What is Dimension? 
차원/(次元) [기학학적 도형이나 물체 및 공간이 펼쳐져 있는 자유도를 나타내는 수. 직선은 1차원, 평면은 2차원, 보통의 공간은 3차원이지만 n차원이나 무한 차원의 공간도 생각할 수 있음.]
차원은 총 0차원,1차원,2차원,3차원 그리고 4차원으로 나누어진다. 0차원은 점으로, 1차원은 점과 선으로 이루어져 있다. 3차원은 점,선,면으로 이루어져 있다는 점은 2차원과 같지만 입체적으로 구성되어있다는 것이 차이점이다. 4차원은 3차원 세계에 사는 우리가 경험할 수 없다.

# Digital
디지털은 정보를 숫자로 변환하여 데이터를 한자리씩 끊어서 다루는 방식을 의미한다. 컴퓨터에서 보는 이미지 한장은 여러개의 픽셀로 이루어져 있으며 각각의 픽셀들은 고유한 번호가 붙어있다. 또한 보통의 이미지는 RGB 3개의 채널이 합쳐져 만들어지는데 각 색의 비율에 따라 다른 여러 색이 만들어진다.

# Compositting
컴포지팅은 두개 이상의 이미지가 결합하는 과정이다. 말 그대로 합성을 하는것을 말한다. 컴포지팅을 하는데는 여러가지 방법이 있으며 가장 흔히 알려진 방식은 그린스크린을 사용하는 것이다. 따고 싶은 물체나 사람을 그린스크린 앞에 두고 촬영한 뒤 후작업을 통해 스크린 부분을 원하는 이미지로 바꿀 수 있다.
     
# Color
## What is color? 
우리는 빛의 반사를 통해 색을 인지할 수 있다.
빛이 물체에 부딪치면 일부의 빛은 흡수되고 일부는 반사되는데, 이때 반사되는 빛에 따라 색이 표현된다. 즉,  어떤 물체의 표면이 빨간색으로 보이는 것은 파랑과 초록 빛깔은 흡수하고 빨간 빛깔만 반사시키기 때문이다. 
### RGB와 CMYK
RGB는 빛의 색의 조합으로 혼합 될 수록 밝아지는 방식을 이야기한다. 여기서 철자는 각각 빨강(RED), 초록(GREEN), 파랑(Blue)의 삼원색을 뜻하며 우리는 이 삼원색의 혼합으로 거의 모든색을 볼 수 있다. CMYK는 물감의 조합으로 혼합 될 수록 어두워지는 방식을 말한다. 잉크의 조합과 같기 때문에 인쇄를 할때는 이 방식을 쓴다. 철자는 차례로 시안(Cyan), 마젠타(Magenta), 노랑(Yellow) 그리고 검정(Black) 을 의미하며 CMYK는 나타낼 수 있는 색상에 한계가 있어 RGB보다 적은 색상 수를 가진다. 
     
## What is ALPHA?
알파 채널은 색상의 투명도 또는 불투명도를 제어한다.
이 채널에서 0은 적용 범위가 없거나 완전한 투명도를 나타내고 1은 전체 적용 범위 또는 100% 불투명도를 나타낸다. 0과 1 사이의 값은 부분 불투명도/투명도이다. 흰색은 완전히 불투명한 영역을 덮는 데 사용되며 검은색은 전체 투명도를 의미하고 회색은 부분적인 불투명도를 나타낸다. 흰색 -> 검은색의 단계로 표현되는 그레이 컬러는 모두 256가지이며, 알파채널은 흰색과 검은색 즉 그레이컬러의 256단계로 선택영역을 설정할 수 있기 때문에 정밀한 선택이 가능하다. 이렇게 만들어진 여러개의 알파채널을 만든 후 흰색의 농도를 조절하여 선택영역을 더하거나 빼면서 영역을 만들어 최종적으로는 RGB 색상채널에 효과를 적용한다.
<br/>(참고:https://www.actionvfx.com/blog/what-is-an-alpha-channel)

# Colorspace
색 공간 은 시각적 평면에서 해석되고 표시될 수 있는 스펙트럼의 색상 범위이다. 이러한 디스플레이의 대부분은 RGB(빨간색, 녹색, 파란색) 색도 다이어그램을 통해 해석된 다음 처리되어 디지털/아날로그 이미지에 표시된다. 이는 색 영역으로 세분화 되는데, 색 영역이란 HSL 또는 색조, 채도 및 밝기로 3차원 공간의 RGB 스펙트럼에 표시되는 인지 가능한 색상 공간의 하위 집합이다. 
![What-is-Color-Space-Gamut-•-Gamut-in-Color-Space](https://user-images.githubusercontent.com/112813981/194696581-dfb921ac-2f04-44a0-a0b3-65a452047606.jpg)
BENQ의 이 이미지는 특정 공간 내의 표준 색 영역을 보여준다. 각 영역은 색상이 지정된 삼각형으로 표시된다. 
(출처:https://www.studiobinder.com/blog/what-is-color-space-definition/)
## why does it matter?
## what are we using?
