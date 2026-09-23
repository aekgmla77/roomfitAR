# RoomFit AR

가구를 구매하기 전에 실제 공간에 배치해 보고, 공간 크기에 맞는 제품을 추천받을 수 있는 AR 가구 추천·배치 서비스입니다.
사용자는 카메라로 공간을 측정하고 가구를 선택한 뒤, AR 화면에서 위치·크기·방향을 조절하며 배치 결과를 확인할 수 있습니다.

## 주요 기능

- AR Ruler를 활용한 공간 및 벽면 길이 측정
- 측정한 공간 크기를 기준으로 한 가구 추천
- 3D 가구 모델(GLB) 로드 및 AR 평면 위 배치
- 가구의 크기 조절, 회전, 이동
- 제품 목록·상세 정보 조회 및 추천 결과 표시
- 조도에 맞춰 자연스럽게 보이도록 하는 AR Light Estimation
- 배치 결과 이미지 캡처 및 공유를 위한 Deep Link 처리

## 기술 스택

| 구분 | 사용 기술 |
| --- | --- |
| Engine | Unity 6, C# |
| AR | AR Foundation, ARCore, ARKit |
| Interaction | XR Interaction Toolkit, Input System |
| 3D Model | glTFast, GLB |
| Rendering | Universal Render Pipeline (URP) |
| Data / Network | UnityWebRequest, Newtonsoft Json |
