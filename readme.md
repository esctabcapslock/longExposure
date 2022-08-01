# 장노출 사진 만들기
- 시작
- pip 업데이트 python -m pip install --upgrade pip
- 시작 venv\Scripts\activate

pip install vidstab

- ( ax^2 + bxy + cy^2 + dx + ey + f - data(x,y) ) 꼴

-  a 에 대해 편미분


2ax + by + d = 0
2cy + bx + e = 0

2abx + bby + bd = 0
2abx + 4acy +  2ae = 0

-(bd-2ae)/(bb-4ac)
-(be-2cd)/(bb-4ac)


- 회전 이동 고려해야 함
    - 이미지를 나누자. 3*3


- 이런 알고리즘 어떨까
candy 적용
구역별로 나눠 1의 합이 가장 많은 곳 적당히 선택
노가다로 변위량 계산. 달팽이 모양으로 찾아가기.
너무 안 나오는곳 있으면 무시할 것.

각 점들의 광흐름으로 전체 뒤틀림 계산
반영


- 평행이동
- 회전이동(Z, x,y)
- 확대/축소