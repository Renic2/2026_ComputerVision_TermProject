# SeoulTech 캠퍼스 CV 프로젝트 주제 200선 (지정주제 1·4·6·8번 제외)

- 기반 지정주제: **2번(AR), 3번(보행자 흐름), 5번(통행량), 7번(추적·예측), 9번(3D 복원), 10번(헬멧), 11번(인도 위반)**
- 제외: 1번(파노라마), 4번(주행 가능 영역), 6번(영상 안정화), 8번(장소 인식)
- 괄호는 가장 가까운 지정주제 번호입니다.

---

## A. AR 정보 시스템 (2번 계열)

1. **AR Pose Jitter Reduction** (2번): 마커 없는 평면 AR에서 가상 객체의 떨림을 줄이는 포즈 필터링 기법을 비교·개선한다.
2. **Planar Object AR with Tracking Recovery** (2번): 포스터·간판을 인식한 뒤 광학 흐름으로 추적하고, 끊기면 자동으로 재인식한다.
3. **AR Occlusion with Pedestrians** (2번): 사람이 지나가면 가상 객체가 사람 뒤로 가려지도록 표현한다.
4. **Notice-Board AR Translation Overlay** (2번): 게시판 글자를 인식해 영어·중국어 번역을 같은 위치에 겹쳐 표시한다.
5. **Time-Travel AR: Old Photo Overlay** (2번): 과거 캠퍼스 사진을 현재 뷰에 정합해 겹쳐 보여준다.
6. **AR Measurement Tool** (2·9번): 영상에서 문 높이·벤치 길이 등 실제 크기를 측정해 표시한다.
7. **Multi-Plane AR on Building Facades** (2번): 건물의 서로 다른 벽면에 각각 가상 콘텐츠를 올바른 원근으로 배치한다.
8. **Markerless Ground-Plane AR Arrows** (2·9번): 바닥 평면을 추정해 길 안내 화살표를 바닥에 붙여 표시한다.
9. **AR Under Illumination Change** (2번): 낮·저녁·흐린 날 조명 변화에서 평면 AR의 인식·오버레이 오차를 비교·개선한다.
10. **AR Shadow Rendering** (2·9번): 실제 그림자 방향을 추정해 가상 객체에 일치하는 그림자를 합성한다.
11. **AR Speed–Accuracy Trade-off** (2번): ORB·SIFT·광학 흐름 하이브리드의 FPS와 오버레이 오차 균형을 분석한다.
12. **Multi-User AR Anchor Sharing** (2번): 서로 다른 휴대폰 사진에서 같은 위치 앵커를 정합해 가상 객체를 공유한다.
13. **AR Signage Readability Check** (2번): 가상 안내판이 거리·각도·대비 조건에서 읽을 수 있는지 자동 평가한다.
14. **Viewpoint Robustness Study for AR Overlay** (2번): 촬영 각도별 오버레이 오차를 정량 분석하고 한계 각도를 찾는다.

## B. 보행자 흐름 분석 (3번 계열)

15. **Pedestrian Flow Direction Map** (3번): 구역별 주 이동 방향을 궤적 기반으로 화살표 지도로 시각화한다.
16. **Occlusion-Robust Pedestrian Tracking** (3번): 가림이 많은 상황에서도 ID를 유지하며 보행자를 추적한다.
17. **Lecture-Break Crowd Wave Analysis** (3번): 강의 종료 직후 인파의 이동 패턴과 피크 시점을 분석한다.
18. **Cafeteria Queue Length and Wait Time Estimation** (3·5번): 식당 줄 길이와 예상 대기 시간을 추정한다.
19. **Walking Speed Map of Campus Zones** (3번): 구역별 평균 보행 속도를 실제 단위로 환산해 지도로 만든다.
20. **Dwell-Time and Hotspot Analysis** (3번): 벤치·광장 등 사람들이 오래 머무는 지점을 추적 데이터로 찾는다.
21. **Group-Aware Pedestrian Analysis** (3번): 함께 이동하는 무리를 인식해 그룹 단위로 분석한다.
22. **Trajectory Anomaly Detection** (3·7번): 일반적인 이동 패턴과 다른 비정상 경로를 검출한다.
23. **Crowd Density: Detection vs Density Regression** (3번): 검출 합산 방식과 밀도 회귀 방식을 혼잡도별로 비교한다.
24. **Entrance Bottleneck Detection** (3번): 출입구에서 병목이 생기는 위치와 시간대를 자동으로 찾는다.
25. **Proximity Distribution Map** (3번): 보행자 간 근접 거리 분포를 구역별로 계산해 혼잡 위험을 지도화한다.
26. **Cross-Camera Pedestrian Re-Identification** (3번): 두 카메라 사이에서 같은 보행자를 다시 식별해 이동 경로를 잇는다.
27. **Bird's-Eye View Replay Generator** (3·7번): 영상 속 보행자·이동체를 탑뷰 지도에서 재생한다.
28. **Umbrella Pedestrian Detection Robustness** (3번): 우산·모자·가방으로 형태가 가려진 보행자의 검출·추적 성능을 개선한다.
29. **Night-Time Pedestrian Tracking Robustness** (3번): 저조도에서 보정 후 추적 성능이 얼마나 개선되는지 분석한다.

## C. 통행량 · 교통 모니터링 (5번 계열)

30. **Occlusion-Aware Entrance Counting** (5번): 출입구가 혼잡해도 방향별 출입 인원을 정확히 집계한다.
31. **Camera-Angle Normalized Counting** (5번): 탑뷰 변환으로 카메라 각도와 무관하게 일관된 통행량을 집계한다.
32. **Vehicle Type Counting on Campus Roads** (5번): 일반 차량·셔틀·배달 오토바이를 종류별로 집계한다.
33. **Bus Stop Waiting Crowd Analysis** (3·5번): 정류장 대기 인원과 탑승 인원을 분석한다.
34. **Bicycle Rack Occupancy Monitoring** (3·5번): 자전거 거치대의 점유 현황을 시간대별로 분석한다.
35. **Vehicle Speed Estimation via Homography** (5번): 탑뷰 변환으로 차량의 실제 속도를 추정한다.
36. **Direction-wise Traffic Flow Matrix** (5번): 교차 지점에서 방향별(직진·좌·우) 이동량을 행렬로 정리한다.
37. **Traffic Counting under Rain and Night** (5번): 비·야간 조건에서 집계 정확도 저하를 분석하고 개선한다.
38. **Shuttle Bus Arrival and Headway Analysis** (5번): 셔틀 도착을 검출해 배차 간격을 분석한다.
39. **Delivery Motorcycle Frequency Analysis** (5번): 배달 오토바이 진입 빈도를 시간대별로 분석한다.
40. **Counting Method Comparison** (5번): Line Crossing, Region 기반, 밀도 기반 집계 방식을 비교한다.
41. **Camera Height and Tilt Sensitivity Study** (5번): 카메라 설치 높이·기울기에 따른 집계 오차를 분석한다.
42. **Traffic Signal State Recognition and Flow Correlation** (5번): 신호 상태를 인식하고 통행량과의 상관을 분석한다.
43. **Stopped-Vehicle Duration Estimation** (5·11번): 정차 차량을 검출해 정차 시간을 추정한다.

## D. 목표 추적 · 단기 예측 (7번 계열)

44. **Crossing Intention Prediction** (3·7번): 횡단 직전 보행자가 건널지 말지 미리 예측한다.
45. **Scooter Path Prediction on Sidewalk** (7번): 킥보드의 가까운 미래 경로를 예측한다.
46. **Time-to-Collision Risk Map** (5·7번): 보행자와 이동체의 충돌 위험 구역을 지도로 만든다.
47. **Occlusion-Aware Short-Term Prediction** (7번): 가려진 동안 위치를 예측하고 재출현하면 복구한다.
48. **Pair-Avoidance Prediction** (7번): 두 보행자가 서로 피하는 행동을 반영해 경로를 예측한다.
49. **CPU Real-Time Prediction Trade-off** (7번): 정확도와 속도의 균형을 맞춘 경량 예측을 설계한다.
50. **Stop Prediction at Bus Stops** (7번): 정류장 접근 시 어디서 언제 멈출지 예측한다.
51. **Prediction Model Comparison by Horizon** (7번): 등속 모델·칼만·LSTM의 예측 시간별 ADE/FDE를 비교한다.
52. **Appearance-Based Re-Acquisition after Long Occlusion** (7번): 오래 가려진 뒤 외형 특징으로 같은 대상을 다시 찾는다.
53. **Tracker Failure Prediction** (7번): 추적이 실패할 구간을 미리 예측해 경고한다.
54. **Multi-Hypothesis Trajectory Prediction** (7번): 하나의 경로가 아니라 여러 가능 경로와 확률을 제시한다.
55. **Prediction Error vs Camera Viewpoint** (7번): 카메라 시점에 따라 예측 오차가 어떻게 달라지는지 분석한다.
56. **Tracking under Low Frame Rate** (7번): 프레임 속도가 낮을 때 추적이 끊기지 않게 보정한다.
57. **Appearance–Motion Fusion for Similar-Clothing Crowds** (3·7번): 비슷한 옷차림의 군중에서 ID 혼동을 줄이는 결합 추적을 만든다.
58. **Vehicle Short-Term Prediction at Intersections** (5·7번): 교차로 진입 차량의 가까운 미래 경로를 예측한다.

## E. 다시점 3D 복원 · 기하 (9번 계열)

59. **Keyframe Selection for Efficient SfM** (9번): 3D 복원에 유리한 프레임만 골라 속도와 정확도를 함께 높인다.
60. **Match Pruning for Faster Reconstruction** (9번): 불필요한 이미지 쌍을 미리 걸러 복원 속도를 높인다.
61. **Building Height from Shadow Geometry** (9번): 그림자 길이와 촬영 시간으로 건물 높이를 추정한다.
62. **Metric Scale Recovery for Monocular SfM** (9번): 캠퍼스 기준 물체로 3D 복원에 실제 스케일을 부여한다.
63. **Pedestrian-Robust Multi-View Reconstruction** (3·9번): 사람이 지나가도 정지 구조만 안정적으로 복원한다.
64. **Low-Texture Wall Reconstruction** (9번): 질감이 적은 벽·창문 구조에서 3D 복원 성능을 높인다.
65. **Smartphone Device Effect on 3D Reconstruction** (9번): 스마트폰 기종 차이가 복원 품질에 미치는 영향을 분석한다.
66. **Stair Counting and Height Estimation** (9번): 영상에서 계단 단수와 높이를 자동 추정한다.
67. **Vanishing-Point Camera Orientation** (9번): 소실점으로 카메라 자세를 추정하고 기울어진 사진을 보정한다.
68. **Two-View Depth for Corridors** (9번): 복도·계단을 두 장으로 촬영해 깊이를 추정한다.
69. **Minimum Overlap Study for SfM** (9번): 이미지 겹침 비율이 복원 성공에 미치는 영향을 분석한다.
70. **Reconstruction Failure Prediction** (9번): 복원을 돌리기 전에 실패할 이미지 세트를 미리 예측한다.
71. **Visual Odometry on Campus Walks** (9번): 걷는 영상으로 이동 궤적을 추정하고 정답 궤적과 비교한다.
72. **3D Reconstruction under Illumination Change** (9번): 낮·저녁 이미지를 섞었을 때 복원 품질 저하를 분석하고 개선한다.

## F. 헬멧 · 탑승자 안전 (10번 계열)

73. **Occlusion-Robust Rider–Helmet Association** (10번): 탑승자가 가려져도 헬멧 착용 여부를 올바른 탑승자와 연결해 판별한다.
74. **Distance-Adaptive Helmet Detection** (10번): 먼 거리에서도 헬멧을 잘 검출하도록 타일링 등으로 개선한다.
75. **Passenger Count Violation on Scooters** (10번): 킥보드 2인 이상 탑승을 검출한다.
76. **Helmet Detection under Night and Backlight** (10번): 야간·역광 조건에서 헬멧 검출 성능을 분석하고 개선한다.
77. **Helmet Wearing Correctness** (10번): 헬멧을 썼더라도 턱끈이 풀렸거나 비스듬히 걸친 경우를 구분한다.
78. **Rider Vehicle-Type Classification** (10번): 킥보드·자전거·오토바이를 구분해 종류별 안전장비 착용을 분석한다.
79. **Helmet Dataset Bias Study** (10번): 공개 데이터셋 학습 모델이 캠퍼스에서 얼마나 성능이 떨어지는지 분석한다.
80. **Per-Rider Violation Report with Tracking** (10번): 같은 탑승자의 반복 검출을 ID로 묶어 위반을 1건으로 집계한다.
81. **Helmet Detection under Motion Blur** (10번): 빠르게 지나가는 탑승자의 흐림에 강인한 검출을 만든다.
82. **Multi-Camera Violation Deduplication** (10번): 여러 카메라에 찍힌 같은 위반을 중복 없이 정리한다.
83. **Small-Head Detection via Super-Resolution Preprocessing** (10번): 작은 머리 영역을 확대·복원한 뒤 헬멧을 판별한다.
84. **Rider Phone-Use Detection** (10번): 주행 중 스마트폰을 사용하는 탑승자를 검출한다.
85. **Earphone-Wearing Rider Detection** (10번): 이어폰을 착용하고 주행하는 탑승자를 검출한다.
86. **Helmet Violation Rate Map by Time and Location** (10번): 시간대·장소별 헬멧 미착용 비율을 지도와 통계로 정리한다.

## G. 인도 위반 검출 (11번 계열)

87. **Scooter Designated-Zone Compliance** (11번): 킥보드가 지정 주차 구역 안에 있는지 바닥 접점 기준으로 판별한다.
88. **Pedestrian-Density Weighted Violation Risk** (3·11번): 인도 주행 위반을 보행자 밀도로 가중해 위험도를 산출한다.
89. **Sidewalk Scooter Speed Estimation** (5·11번): 인도 위 킥보드의 실제 속도를 추정한다.
90. **Emergency Access Blocking Detection** (11번): 소방 통로 등 긴급 통로를 막은 차량·구조물을 검출한다.
91. **Wrong-Way Riding on One-Way Paths** (5·11번): 일방통행 구간의 역주행 탑승자를 검출한다.
92. **Sidewalk Boundary Error Analysis** (11번): 인도 경계 분할 오차가 위반 판정에 미치는 영향을 분석하고 완화한다.
93. **Violation Evidence Clip Generator** (11번): 위반이 일어난 구간을 자동으로 잘라 증거 클립으로 만든다.
94. **Tactile Paving Blocking Detection** (11번): 점자블록 위에 정차·주차한 이동체를 검출한다.
95. **Illegal Parking Duration Estimation of Scooters** (11번): 불법 주차 킥보드의 방치 시간을 추정한다.
96. **Sidewalk vs Bike Lane Disambiguation** (11번): 보행 전용 구간과 자전거 허용 구간을 구분해 위반 기준을 달리 적용한다.
97. **Violation Detection Robustness to Camera Placement** (11번): 카메라 설치 위치·각도에 따른 위반 검출 성능 차이를 분석한다.
98. **Night-Time Sidewalk Riding Detection** (11번): 야간 영상에서 인도 위 주행을 검출하는 성능을 개선한다.
99. **Delivery Robot vs Scooter Disambiguation** (11번): 허용되는 배달 로봇과 위반 대상인 킥보드를 구분한다.
100. **Violation Heatmap of Campus Sidewalks** (11번): 인도 위 위반이 자주 일어나는 지점을 지도로 시각화한다.

---

# 추가 100선 (101~200)

## H. AR 확장 (2번 계열)

101. **AR Anchor Drift Analysis** (2번): 긴 영상에서 가상 객체가 서서히 밀리는 드리프트를 측정하고 보정한다.
102. **Keyframe-Based Relocalization for Planar AR** (2번): 추적이 끊겼을 때 저장해 둔 키프레임으로 평면 앵커를 빠르게 복구한다.
103. **Illumination Matching for AR Shading** (2·9번): 한 장의 영상에서 조명 색·세기를 추정해 가상 객체의 음영을 실제와 맞춘다.
104. **Reflection-Aware AR on Glass Facades** (2번): 유리창 반사 때문에 매칭이 흔들리는 벽면에서도 오버레이를 안정화한다.
105. **Monocular-Depth-Based AR Depth Ordering** (2번): 단안 깊이 추정으로 가상 객체와 실제 물체의 앞뒤 관계를 판단해 가림을 처리한다.
106. **Marker vs Natural-Feature Hybrid Anchoring** (2번): ArUco 마커와 자연 특징을 결합해 앵커 정확도와 강인성을 높인다.
107. **AR Content Placement Suggestion** (2번): 벽면 중 평탄하고 질감이 충분한 위치를 자동으로 찾아 콘텐츠 배치를 추천한다.
108. **AR Overlay Latency Compensation** (2번): 영상 처리 지연으로 생기는 오버레이 밀림을 움직임 예측으로 보상한다.
109. **Low-Light AR Robustness** (2번): 저조도에서 특징 부족으로 AR이 실패하는 구간을 분석하고 전처리로 개선한다.
110. **Checkerboard-Free Intrinsic Self-Calibration for AR** (2·9번): 체커보드 없이 일반 영상만으로 카메라 내부 파라미터를 추정한다.
111. **AR Occlusion by Static Structures** (2·9번): 기둥·나무처럼 고정된 구조물 뒤로 가상 객체가 자연스럽게 가려지게 한다.
112. **Distance-Adaptive AR Content Scaling** (2번): 관찰 거리에 따라 가상 글자·아이콘 크기를 자동 조절해 가독성을 유지한다.
113. **AR Registration Error Estimation without Ground Truth** (2번): 정답 없이도 오버레이 오차를 추정하는 자체 평가 지표를 설계한다.
114. **Multi-Camera AR Handoff** (2번): 두 카메라 사이에서 AR 콘텐츠가 끊김 없이 이어지도록 앵커를 전달한다.

## I. 보행자 흐름 확장 (3번 계열)

115. **Contraflow Detection in Narrow Passages** (3번): 좁은 통로에서 서로 반대 방향으로 흐르는 보행 흐름을 검출하고 충돌 구간을 찾는다.
116. **Pedestrian Lane Formation Analysis** (3번): 사람들이 자연스럽게 줄을 지어 걷는 현상(레인 형성)을 궤적에서 검출한다.
117. **Stop-and-Go Wave Detection in Crowds** (3번): 혼잡한 흐름에서 멈춤이 뒤로 전파되는 파동을 영상으로 검출한다.
118. **Group Size Distribution by Time of Day** (3번): 시간대별로 혼자·둘·무리 보행 비율이 어떻게 달라지는지 분석한다.
119. **Head-Direction Attention Map** (3번): 보행자의 머리 방향으로 사람들이 주로 바라보는 방향을 지도로 만든다.
120. **Notice-Board Attention Estimation** (3번): 게시판 앞 체류 시간과 머리 방향으로 게시물 관심도를 추정한다.
121. **Carried-Item Attribute Statistics** (3번): 우산·큰 가방 등 소지품 속성을 집계해 시간대·날씨와의 관계를 분석한다.
122. **Stair vs Ramp Choice Analysis** (3번): 계단과 경사로가 함께 있을 때 사람들이 어느 쪽을 택하는지 분석한다.
123. **Desire-Path Detection** (3번): 잔디밭을 가로지르는 지름길(비공식 길)을 궤적 누적으로 찾는다.
124. **Speed–Density Relationship Estimation** (3번): 보행 밀도와 평균 속도의 관계 곡선을 캠퍼스 데이터로 추정한다.
125. **Semi-Automatic Trajectory Annotation Tool** (3·7번): 추적 결과를 사람이 빠르게 수정할 수 있는 반자동 라벨링 도구를 만들고 효율을 측정한다.
126. **Two-Camera Fusion for Crowd Counting** (3번): 두 카메라의 영상을 융합해 가림으로 놓친 인원을 보완한다.
127. **Door Merging Flow Analysis** (3번): 좁은 출입문에서 흐름이 합쳐지는 방식과 병목 정도를 분석한다.
128. **Obstacle Avoidance Trajectory Analysis** (3번): 웅덩이·공사 콘 등 장애물 주변의 회피 궤적 패턴을 분석한다.
129. **Weather-Dependent Pedestrian Behavior** (3번): 비 오는 날과 맑은 날의 보행 속도·경로 차이를 비교한다.
130. **Social Force Model vs Observed Trajectories** (3·7번): 소셜 포스 모델 시뮬레이션과 실제 관측 궤적의 차이를 정량 비교한다.

## J. 통행량 · 교통 확장 (5번 계열)

131. **Pick-up and Drop-off Zone Analysis** (5번): 승하차 구역에서 정차 차량과 정차 시간을 분석한다.
132. **Gate Vehicle Queue Length Estimation** (5번): 정문 앞 차량 대기열 길이를 영상으로 추정한다.
133. **U-Turn Detection on Campus Roads** (5번): 도로에서 U턴하는 차량을 궤적으로 검출한다.
134. **Brake-Light-Based Deceleration Cue** (5·7번): 브레이크등 점등을 인식해 감속 신호로 활용한다.
135. **Pedestrian–Vehicle Conflict Count by Location** (5번): 보행자와 차량이 근접하는 사건을 위치별로 집계해 위험 지점을 찾는다.
136. **Automatic Counting-Line Placement** (5번): 카메라 설치 후 집계선 위치를 자동으로 제안한다.
137. **Counting Drift across Lighting Changes** (5번): 하루 동안 조명이 변하면서 집계 오차가 어떻게 달라지는지 분석한다.
138. **Counting with Low-Resolution CCTV** (5번): 저해상도 영상에서 집계 정확도 저하를 분석하고 개선한다.
139. **Fisheye Camera Counting** (5번): 어안 렌즈 왜곡을 보정한 뒤 통행량을 집계한다.
140. **Vehicle Dwell Time at Parking Entrances** (5번): 주차장 입구에서 차량이 머무는 시간을 추정한다.
141. **Mixed-Traffic Zone Classification** (5번): 보행자·자전거·차량이 섞여 다니는 구역을 자동으로 구분한다.
142. **Privacy-Preserving Counting** (5번): 얼굴을 가린 영상에서도 집계 정확도가 유지되는지 분석한다.
143. **Counting Error Budget Analysis** (5번): 집계 오차를 검출·추적·ID·기하 원인으로 분해해 분석한다.

## K. 추적 · 예측 확장 (7번 계열)

144. **Ego-Motion-Compensated Trajectory Prediction** (7번): 카메라가 움직일 때 카메라 이동을 보정한 뒤 대상의 경로를 예측한다.
145. **Trajectory Prediction Uncertainty Calibration** (7번): 예측 신뢰구간이 실제 위치를 얼마나 포함하는지 검증하고 보정한다.
146. **Long-Tail Behavior Prediction** (7번): 급정지·급회전처럼 드문 행동에서 예측이 얼마나 무너지는지 분석한다.
147. **Entrance-Aware Scene-Semantic Prediction** (7번): 건물 입구 방향 같은 장면 정보를 규칙으로 넣어 예측을 개선한다.
148. **Goal-Conditioned Prediction** (7번): 목적지를 가정해 경로를 예측하고 가정이 틀렸을 때의 영향을 분석한다.
149. **Detection-Based vs Single-Object Tracker under Occlusion** (7번): 검출 기반 추적과 단일 객체 추적기를 가림 상황에서 비교한다.
150. **Re-ID Embedding vs Color Histogram for Occlusion Recovery** (7번): 외형 특징 방식별로 가림 후 재획득 성능을 비교한다.
151. **Track Fragmentation Repair** (7번): 끊어진 궤적 조각들을 이어 붙여 하나의 궤적으로 복원한다.
152. **Small-Target Tracking at Long Distance** (7번): 멀리 있어 작게 보이는 대상의 추적 성능을 분석하고 개선한다.
153. **Campus-Specific Tracking Metrics Proposal** (7번): 일반 추적 지표(MOTA 등)를 보완하는 캠퍼스용 평가 지표를 제안한다.
154. **Speed-Adaptive Kalman Noise Tuning** (7번): 대상 속도에 따라 칼만 필터 잡음 설정을 자동으로 조정한다.
155. **Low-Cost Edge Device Tracking** (7번): 저사양 장치(라즈베리파이 등)에서 추적 속도와 정확도를 평가한다.
156. **Pedestrian Orientation from Motion and Appearance** (7번): 이동 방향과 외형을 결합해 보행자가 향하는 방향을 추정한다.
157. **Outlier Removal Effect on Prediction** (7번): 궤적 이상치 제거·스무딩이 예측 정확도에 미치는 영향을 분석한다.
158. **Vehicle–Pedestrian Joint Prediction at Crosswalks** (5·7번): 횡단보도에서 차량과 보행자를 함께 고려해 경로를 예측한다.

## L. 다시점 3D 복원 확장 (9번 계열)

159. **Feature Detector Effect on SfM Accuracy** (9번): SIFT·ORB·AKAZE 선택이 3D 복원 정확도와 속도에 미치는 영향을 분석한다.
160. **Bundle Adjustment Ablation Study** (9번): 번들 조정의 각 구성요소를 빼가며 복원 정확도 변화를 분석한다.
161. **Incremental vs Global SfM Comparison** (9번): 증분형과 전역형 SfM의 정확도·속도·실패율을 비교한다.
162. **Glass Facade Reconstruction Failure Analysis** (9번): 유리 외벽에서 복원이 실패하는 원인을 분석하고 완화 방법을 시험한다.
163. **Dense Reconstruction of a Campus Statue** (9번): 조형물을 다시점 스테레오로 조밀하게 복원하고 품질을 평가한다.
164. **Facade Plane Segmentation from Point Cloud** (9번): 복원된 포인트클라우드에서 건물 외벽 평면을 자동으로 분리한다.
165. **Stereo Baseline Length Study** (9번): 스테레오 기선 길이에 따른 거리 추정 정확도를 분석한다.
166. **Wide-Angle vs Standard Lens Reconstruction** (9번): 광각과 일반 렌즈로 찍은 이미지의 복원 품질을 비교한다.
167. **Photo Count vs Quality Curve** (9번): 조형물 복원에서 사진 수 증가에 따른 품질 곡선을 구해 최소 촬영량을 찾는다.
168. **Epipolar-Guided Matching Speed-up** (9번): 에피폴라 제약으로 매칭 탐색 범위를 줄여 속도를 높인다.
169. **Outlier Rejection Comparison for Fundamental Matrix** (9번): RANSAC·MAGSAC·PROSAC 등 이상치 제거 방식을 비교한다.
170. **EXIF-Based Self-Calibration** (9번): 사진 메타데이터로 초기 내부 파라미터를 추정하고 정확도를 평가한다.
171. **Scale Drift in Long Walking Odometry** (9번): 긴 보행 궤적에서 스케일이 누적해서 어긋나는 정도를 측정하고 보정한다.
172. **Two-View Obstacle Distance Estimation for Robots** (9번): 두 장의 영상으로 앞 장애물까지의 거리를 추정한다.

## M. 헬멧 · 탑승자 안전 확장 (10번 계열)

173. **Helmet Class Imbalance Handling** (10번): 미착용 샘플이 적은 불균형 상황에서 학습·평가 방식을 비교한다.
174. **Distance-Specific Threshold Calibration** (10번): 거리 구간마다 판정 임계값을 달리해 헬멧 판별 성능을 올린다.
175. **Rider vs Passenger Role Classification** (10번): 같은 차량의 운전자와 동승자를 구분해 각각의 헬멧 착용을 판별한다.
176. **Helmet Type Classification** (10번): 자전거용·오토바이용·기타 헬멧 종류를 구분한다.
177. **Pose-Guided Head Cropping** (10번): 자세 추정으로 머리 영역을 잘라 헬멧 판별 정확도를 높인다.
178. **Rider Detection under Rain Gear** (10번): 우비·후드를 쓴 탑승자의 검출·판별 성능을 분석하고 개선한다.
179. **Cap-Hood vs Helmet Confusion Analysis** (10번): 모자·후드를 헬멧으로 오인하는 사례를 분석하고 줄이는 방법을 시험한다.
180. **Temporal Voting for Helmet Decision** (10번): 여러 프레임의 판별을 투표로 합쳐 일시적 오판을 줄인다.
181. **Front vs Rear View Helmet Detection** (10번): 정면·후면 촬영에 따른 헬멧 판별 성능 차이를 분석한다.
182. **Lightweight Helmet Detector for Edge Devices** (10번): 경량 모델로 속도와 정확도의 균형을 맞춘다.
183. **Group Ride Rider Counting** (10번): 여러 대가 함께 지나갈 때 탑승자 수를 정확히 센다.
184. **Tracking-Based Label Propagation for Helmet Data** (10번): 추적으로 라벨을 이웃 프레임에 전파해 라벨링 시간을 줄인다.
185. **Failure Case Taxonomy for Helmet Detection** (10번): 헬멧 검출 실패 사례를 유형별로 분류하는 체계를 만들고 빈도를 분석한다.
186. **Helmet-Wearing Rate Time-Series Analysis** (10번): 일자·시간대별 헬멧 착용률 변화를 통계로 정리한다.

## N. 인도 위반 확장 (11번 계열)

187. **Wheel–Ground Contact Point Violation Judgment** (11번): 박스 중심이 아니라 바퀴 접지점 기준으로 인도 침범을 판정한다.
188. **Region Re-Registration for Slightly Moved Cameras** (11번): 카메라가 조금 움직여도 인도 영역을 다시 정합해 판정을 유지한다.
189. **Vehicle-Type-Specific Violation Rules** (11번): 킥보드·자전거·오토바이별로 다른 위반 기준을 적용해 판정한다.
190. **Multi-Frame Violation Confidence Scoring** (11번): 여러 프레임의 증거를 합쳐 위반 확신도를 점수로 산출한다.
191. **Pedestrian Safety Margin Violation** (3·11번): 보행자와 지나치게 가깝게 지나가는 주행을 검출한다.
192. **Sidewalk Width Reduction by Parked Bikes** (11번): 주차된 자전거·킥보드 때문에 줄어든 보도 유효 폭을 정량화한다.
193. **Riding vs Walking Across Crosswalks** (11번): 횡단보도를 타고 건너는 경우와 끌고 건너는 경우를 구분한다.
194. **Backlit and Shaded Sidewalk Robustness** (11번): 역광·그늘에서 인도 경계 인식과 위반 판정이 얼마나 흔들리는지 분석한다.
195. **Seasonal Boundary Change Handling** (11번): 낙엽·눈으로 인도 경계가 달라 보일 때 위반 판정 성능을 분석한다.
196. **Few-Click Sidewalk Mask Creation** (11번): 몇 번의 클릭만으로 인도 영역 마스크를 만드는 약지도 방법을 시험한다.
197. **Idle vs Moving State Classification** (11번): 이동체가 정지·이동 중인지 구분해 주차와 주행 위반을 달리 판정한다.
198. **Violation Event Retrieval by Metadata** (11번): 위반 이벤트를 시간·위치·종류로 검색할 수 있는 색인 체계를 만든다.
199. **Evidence Quality Check for Violation Clips** (10·11번): 증거 클립에서 번호·헬멧 등이 식별 가능한 품질인지 자동으로 평가한다.
200. **Cross-Location Generalization of Violation Detector** (11번): 한 장소에서 만든 위반 검출기가 다른 장소에서 얼마나 유지되는지 분석한다.
