# 고속도로 개별차량 통행데이터를 활용한 경로형 중장기 통행시간 예측

> 한국도로공사 고속도로 공공데이터포털 Dsrc 원시자료를 활용
> 경로별 통행량 및 통행패턴 분석
> 통행량 활용 주요 경로 선정

### 자료 설명

 - Seoul_dagu.csv : 서울에서 대구까지의 총 17개 경로(상행 12개, 하행5개)의 rse_id 가 정리된 csv파일
 - multiprocessing.py : 멀티프로세스를 이용해 하루치 대용량 csv 파일 전처리 코드
 - 가상obu_id별로전처리.ipynb : 가상 Obu_id 별로 지나는 rse_id 정리
 - 30개이하전처리.ipynb : 가상 obu_id를 기준으로 경로1을 지나는 rse id 30개 이하의 가상 obuid 제거 후 전처리
