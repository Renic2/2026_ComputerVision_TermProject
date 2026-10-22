# SeoulTech 캠퍼스 컴퓨터 비전 프로젝트 주제 100선

- 지정주제와의 연결을 전제로 하지 않고, 캠퍼스 환경에서 직접 촬영한 데이터로 수행할 수 있는 주제를 구성하였다.
- 파노라마, 주행 가능 영역 분할, 영상 안정화, 장소 인식 계열은 제외하였다.
- 각 항목은 주제명과 간단한 설명으로 구성한다.

---

## A. 기하 · 측정

1. **Doorway Width Estimation from a Single Image**: 규격이 알려진 문틀과 소실점 정보를 이용하여 출입구 폭을 단일 영상에서 추정한다.
2. **Tile-Grid Based Ground Distance Measurement**: 보도블록 격자를 단위 길이로 삼아 영상 속 이동 거리와 물체 크기를 환산한다.
3. **Camera Pose Estimation from Paving Patterns**: 규칙적인 타일 패턴으로 지면 평면의 방향과 카메라 높이를 추정한다.
4. **Tree Height Estimation from Shadow and Horizon Cues**: 그림자 길이와 수평선 정보를 결합하여 가로수의 높이를 추정한다.
5. **Floor Count Estimation from Window Grids**: 건물 외벽의 창문 격자를 검출하여 층수를 자동으로 계산한다.
6. **Distance Estimation from Street-Light Spacing**: 일정 간격으로 배치된 가로등을 기준으로 원근 보정과 거리 추정을 수행한다.
7. **Handrail Slope Angle Measurement**: 계단 난간과 경사로의 기울기 각도를 영상에서 측정한다.
8. **Effect of Optical Stabilization on Calibration Stability**: 스마트폰 광학 손떨림 보정 기능이 카메라 캘리브레이션 결과의 안정성에 미치는 영향을 분석한다.
9. **Automatic Ground-Plane Coordinate Setup**: 보도 경계선과 타일 패턴을 이용하여 탑뷰 좌표계를 자동으로 설정한다.
10. **Glass Reflection Error Analysis in Stereo Depth**: 유리창 반사가 스테레오 깊이 추정 오차에 미치는 영향을 정량적으로 분석한다.

## B. 영상 품질 · 센서

11. **Backlight Compensation Comparison**: 건물 출입구 역광 영상에서 사람 가시성을 높이는 톤 매핑 기법을 비교한다.
12. **Lens Contamination Detection**: 렌즈에 묻은 지문이나 물방울을 영상만으로 자동 판별한다.
13. **Camera Defocus Diagnosis**: 초점 이상으로 선명도가 저하된 카메라를 자동으로 진단한다.
14. **Over/Under-Exposed Frame Screening**: 과노출과 저노출 프레임을 자동으로 선별하고 후속 검출 성능에 미치는 영향을 분석한다.
15. **Street-Light Flare Detection and Suppression**: 야간 영상에서 가로등 눈부심 영역을 검출하고 억제한다.
16. **Compression Bitrate vs Detection Performance Curve**: 영상 압축 비트레이트에 따른 검출 성능 저하 곡선을 작성한다.
17. **Sensor Noise Model Estimation by ISO**: ISO 설정별 노이즈 특성을 추정하고 디노이징 기법의 효과를 비교한다.
18. **Multi-Frame Low-Light Noise Reduction**: 여러 프레임을 정렬하여 저조도 영상의 노이즈를 저감하고 효과를 정량 평가한다.
19. **Dropped and Duplicate Frame Detection**: 영상에서 프레임 누락과 중복 프레임을 자동으로 검출한다.
20. **Cross-Device Color Consistency Correction**: 서로 다른 스마트폰으로 촬영한 영상의 색상 차이를 보정한다.

## C. 사람 · 행동 분석

21. **Walking Stride and Speed Estimation from Pose**: 자세 추정 결과로 보폭과 보행 속도를 추정한다.
22. **Bench Sitting Posture Classification**: 벤치 이용자의 착석 자세를 분류하고 점유 패턴을 분석한다.
23. **Cyclist Hand-Signal Recognition**: 자전거 탑승자의 좌회전·정지 수신호를 인식한다.
24. **Lecture-Room Seat Occupancy Estimation**: 강의실 좌석의 점유 여부를 영상으로 판별한다.
25. **Library Desk Utilization Estimation**: 열람석 사용 현황과 장시간 비워둔 좌석을 추정한다.
26. **Unattended Belongings Detection**: 사람 없이 방치된 가방·노트북 등 소지품을 검출한다.
27. **Crowd Activity Classification**: 군중 영상에서 걷기·달리기·서 있기·앉기 활동을 분류한다.
28. **Running vs Walking Discrimination**: 달리는 보행자와 걷는 보행자를 속도와 자세 특징으로 구분한다.
29. **Wheelchair User Detection and Path Analysis**: 휠체어 이용자를 검출하고 이동 경로를 접근성 관점에서 분석한다.
30. **White-Cane User Detection**: 흰 지팡이를 사용하는 보행자를 검출한다.

## D. 객체 인식 · 분류

31. **Trash Bin Type Classification and Fullness Estimation**: 쓰레기통의 종류를 분류하고 가득 찬 정도를 판별한다.
32. **Abandoned Bicycle Identification**: 장기간 같은 위치에 방치된 자전거를 시간 정보로 식별한다.
33. **Campus Plant Species Classification**: 잎 영상을 이용하여 교내 식물 종을 분류한다.
34. **Facade Material Classification**: 건물 외벽 재질(벽돌·유리·콘크리트)을 분류한다.
35. **Street Tree Leaf-Fall Level Classification**: 가로수의 낙엽 정도를 단계별로 분류한다.
36. **Safety Pictogram Recognition**: 피난·금연 등 안내 표지 아이콘을 인식한다.
37. **Parcel Delivery Vehicle Recognition**: 택배 차량을 인식하여 진입 빈도를 분석한다.
38. **Construction Material Recognition**: 공사 구간의 자재와 장비를 인식한다.
39. **Parcel Locker and Vending Machine State Detection**: 무인 택배함과 자판기의 사용 상태를 판별한다.
40. **Manhole and Drain Cover State Detection**: 맨홀 뚜껑과 배수구의 이상 상태를 검출한다.
41. **Notice Post Category Classification**: 게시물을 행사·모집·분실물 등 유형별로 분류한다.
42. **Reflective-Wear Pedestrian Detection at Night**: 야간 반사 조끼와 형광 의류 착용 보행자를 검출하여 가시성을 분석한다.

## E. 텍스트 · 표지

43. **Mixed Korean–English Signage OCR Analysis**: 한글과 영문이 혼합된 안내판의 문자 인식 성능을 폰트와 촬영 각도별로 분석한다.
44. **Timetable Notice Structure Recognition**: 시간표 게시물의 표 구조를 인식하여 데이터로 변환한다.
45. **Lost-and-Found Photo Matching**: 분실물 게시 사진과 신고 문구를 텍스트와 외형 특징으로 매칭한다.
46. **LED Signboard OCR at Night**: 야간 전광판의 문자를 인식한다.
47. **Speed-Limit Sign Digit Recognition**: 교내 도로의 속도 제한 표지 숫자를 인식한다.
48. **Handwritten Poster Text Detection**: 손글씨로 작성된 포스터의 문자 영역을 검출한다.

## F. 시간 · 환경 모니터링

49. **Lawn Condition Monitoring**: 잔디의 건조·생육 상태를 색상 변화로 모니터링한다.
50. **Snow Depth Estimation with Reference Objects**: 기준 물체를 이용하여 적설 두께를 추정한다.
51. **Rain Detection from Wet-Surface Reflection**: 노면 반사 변화로 강수 여부를 감지한다.
52. **Insolation Index Estimation from Sky Images**: 하늘 영상으로 일사량 지수를 추정한다.
53. **Bench Sunlight Duration Estimation**: 벤치별 일조 시간을 추정한다.
54. **Pond Surface State Monitoring**: 연못과 분수대의 수면 상태(결빙 등)를 모니터링한다.
55. **Construction Dust Visibility Estimation**: 공사 먼지로 인한 가시도 저하를 추정한다.
56. **Visibility Impact on Pedestrian Detectability**: 시정 감소가 보행자 검출 성능에 미치는 영향을 분석한다.
57. **Street-Light On/Off Time Logging**: 야간 조도 시계열로 가로등 점등·소등 시각을 자동 기록한다.
58. **Facade Soiling and Condensation Change Monitoring**: 건물 외벽 오염과 결로 변화를 시계열로 모니터링한다.

## G. 비디오 이해 · 이벤트

59. **Fall Event Detection**: 보행자의 넘어짐 사건을 검출한다.
60. **Sudden Braking Event Detection for Bikes and Scooters**: 자전거와 킥보드의 급제동 사건을 검출한다.
61. **Abrupt Crowd Motion Change Detection**: 군중이 갑자기 달리거나 흩어지는 이상 흐름을 감지한다.
62. **Static-Camera Event Clip Extraction**: 정지 카메라 영상에서 변화 없는 구간을 제거하고 사건 구간만 추출한다.
63. **Direction-Change Event Logging**: 보행자의 방향 전환 사건을 기록한다.
64. **Door Open/Close State Detection**: 문의 개폐 상태를 검출하고 출입 사건과 연동한다.
65. **Elevator Waiting Queue Assessment**: 엘리베이터 앞 대기 인원과 문 상태를 함께 판별한다.
66. **Multi-Camera Temporal Offset Alignment**: 여러 카메라 영상의 시간 오프셋을 자동으로 정렬한다.
67. **Anomalous Frame Detection**: 가림이나 카메라 이동으로 비정상이 된 프레임을 자동으로 검출한다.
68. **Camera View Obstruction Event Detection**: 카메라 시야가 가려지는 사건을 검출한다.

## H. 3D · 깊이

69. **Ground-Level Step Height Estimation**: 두 시점 영상으로 지면 단차의 높이를 추정한다.
70. **Object Volume Approximation from Handheld Sweep**: 스마트폰 이동 촬영으로 벤치 등 물체의 3D 부피를 근사한다.
71. **Tree Canopy Volume Approximation**: 다시점 영상으로 수관의 3D 부피를 근사한다.
72. **Facade Protrusion Depth Estimation**: 건물 외벽의 발코니 등 돌출부의 깊이를 추정한다.
73. **Occluded Region Completion with Multi-View Geometry**: 다시점 기하를 이용하여 가려진 영역을 복원한다.
74. **Mirror and Glass Plane Detection**: 거울과 유리 평면을 검출하여 오인식을 방지한다.
75. **Sign Plane Orientation Estimation**: 표지판의 3차원 기울기와 방향을 추정한다.
76. **Slope Estimation from Monocular Images**: 단일 영상으로 지면 경사를 추정한다.

## I. 합성 · 데이터 · 학습

77. **Synthetic Pedestrian Augmentation for Detection**: 합성 인물을 배경 영상에 삽입하여 보행자 검출 성능을 보강한다.
78. **Effect of Copy-Paste Augmentation on Small Objects**: 복사 붙여넣기 증강이 소형 객체 검출에 미치는 영향을 분석한다.
79. **Synthetic Weather Robustness Evaluation**: 비·안개 합성 영상으로 모델의 강건성을 평가한다.
80. **Day-to-Night Augmentation**: 주간 영상을 야간 영상으로 변환하는 증강 기법을 비교한다.
81. **Label Noise Sensitivity Analysis**: 잘못된 라벨의 비율에 따른 검출 성능 저하를 분석한다.
82. **Active Learning for Labeling Cost Reduction**: 능동 학습으로 라벨링 수량을 줄이면서 성능을 유지하는 방법을 시험한다.
83. **Semi-Supervised Detector Improvement**: 라벨 없는 영상을 활용한 준지도 학습으로 검출기를 개선한다.
84. **Near-Duplicate Frame Removal Effect**: 중복·유사 프레임 제거가 학습 효율과 성능에 미치는 영향을 분석한다.
85. **Day-to-Night Domain Adaptation**: 주간 데이터로 학습한 모델을 야간 영상에 적응시킨다.
86. **Inpainting Quality Evaluation for Object Removal**: 영상에서 객체를 제거한 후 복원 품질을 비교한다.

## J. 시스템 · 효율

87. **Quantization Effect on Lightweight Detectors**: INT8 양자화가 경량 검출기의 정확도와 속도에 미치는 영향을 분석한다.
88. **Resolution–Accuracy–Speed Trade-off Curve**: 입력 해상도에 따른 정확도와 속도의 균형 곡선을 작성한다.
89. **Frame-Skipping Strategy and Tracking Accuracy**: 프레임 건너뛰기 전략이 추적 정확도에 미치는 영향을 분석한다.
90. **On-Device Inference Benchmark on Smartphones**: 스마트폰에서 온디바이스 추론 성능을 측정하고 비교한다.
91. **Multi-Camera Load Distribution Architecture**: 여러 카메라 스트림을 효율적으로 분산 처리하는 구조를 설계한다.
92. **Stream Latency Measurement and Bottleneck Analysis**: 영상 스트림 처리 지연을 측정하고 병목 구간을 분석한다.
93. **Preprocessing Pipeline Search**: 전처리 조합을 체계적으로 탐색하여 효과적인 구성을 찾는다.
94. **Ensemble vs Single Model Cost-Performance**: 모델 앙상블과 단일 모델의 비용 대비 성능을 비교한다.

## K. 접근성 · 안전

95. **Protruding Obstacle Detection on Walking Routes**: 시각장애인의 보행 경로 상 돌출 장애물을 검출한다.
96. **Wheelchair Passable Width Assessment**: 문과 보도의 폭을 측정하여 휠체어 통행 가능성을 판단한다.
97. **Crosswalk Waiting Area Occupancy Analysis**: 횡단보도 신호 대기 구역의 점유 현황을 분석한다.
98. **Night Walkway Visibility Assessment**: 야간 보행로의 조도 분포로 가시성을 평가한다.
99. **Rest-Area Usage Analysis for Mobility-Impaired Users**: 보행 약자용 쉼터의 이용 현황을 분석한다.
100. **Staircase Handrail Presence Detection**: 계단 손잡이의 유무와 연속성을 검출한다.
