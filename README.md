# snowman3

주제 : 실내와 실외의 미세먼지 농도를 비교한 인공지능 알림 챗봇 만들기.

프로젝트 목적
환경 문제 해결에 기여

현대인의 건강을 위협하는 미세먼지 문제에 대한 실질적인 해결책을 제시하고자 합니다.
실내와 실외 미세먼지 농도를 비교하여, 보다 깨끗한 환경을 유지하는 데 도움을 주기 위한 알림 시스템을 개발했습니다.
사용자 중심의 건강 관리

많은 사람들이 실외 미세먼지 농도는 인지하지만, 실내 공기질에 대한 관심은 부족합니다.
이 프로젝트는 실내외 공기질의 차이를 쉽게 이해할 수 있도록 돕고, 사용자에게 적합한 행동을 제안하여 건강 관리를 돕는 데 목표를 두었습니다.
인공지능과 IoT의 실용적 활용

이 프로젝트는 AI 기술과 IoT 센서를 결합하여, 데이터를 분석하고 효율적인 알림 시스템을 제공하는 기술적 가능성을 보여줍니다.
특히, 데이터 기반의 의사결정을 통해 보다 스마트한 환경 관리를 구현하고자 합니다.
의식 개선 및 생활 습관 변화 유도

미세먼지 문제는 단순히 외출을 자제하는 것에 그치지 않고, 공기질 관리에 대한 인식을 개선하는 것이 중요합니다.
이를 통해 더 많은 사람들이 실내외 공기질 관리의 중요성을 깨닫고 생활 습관을 개선할 수 있도록 돕고자 합니다.


사용센서 : cm1106 co2 센서, grove 미세먼지 센서

내용
1. 우리는 실외의 미세먼지 농도를 파악해야하기 때문에 대전의 미세먼지 농도를 파이썬으로 불러오는 작업을 진행하였다.
2. 에어코리아에서 제공하는 API를 사용하여 충남대학교와 가장 가까운 대기질 측정소인 월평동의 미세먼지 농도(PM10, PM2.5)를 불러오는 것을 성공하였다.
3. grove 센서를 이용, 실내( 충남대학교 공과대학 3호관 515호)의 미세먼지 농도를 측정하였다. 그리고 그 값을 주피터로 불러오는 것에 대해 성공하였다.
4. 코드를 사용, 실내와 실외의 미세먼지 차이를 계산하는 챗봇을 만들었다.
5. 미세먼지 차이에 대한 기준은 실내 미세먼지 기준 농도를 가져와서 결정하였으며 차이가 높을시 챗봇에서 환기, 창문 닫기 등의 제안이 가능하다.
6. 
![image](https://github.com/user-attachments/assets/0e154dde-9ce6-43cc-86a1-ab6574210c8b)
