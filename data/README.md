# Korean Dataset 수집
- 모음별 Classification 및 Decoding에 집중


### 입모양 확인
### 한글 기본 모음의 입모양은 '입술 모양, 입벌림, 발음의 전후차이'의 차이로 식별

- ```ㅏ```: 긴입술, 큰 입벌림, 입안 소리
- ```ㅓ```: 길다란 입술, 중간 입벌림, 입안소리
- ```ㅗ```; 둥근입술, 중간 입벌림, 입안 소리
- ```ㅜ```: 둥근입술, 작은 입벌림, 입안 소리
- ```ㅡ```: 길다란 입술, 작은 입벌림, 입안의 어금니 소리
-```ㅣ```: 길다란 입술, 작은 입벌림, 혀끝나온 앞니 소리

## Dataset 수집 방법
- 5fps 3초동안 하나의 문자 촬영

## Output
- Video 저장
- Frame 별 전체 사진 저장
- Frame 별 Crop된 얼굴 사진 저장
- Frame 별 Crop된 입술 사진 저장
- Frame 별 입술의 landmark 값 Excel에 저장

### Datacollect
[데이터 수집](https://github.com/dnwjddl/LipReading_Korean/blob/master/data/DataCollect.ipynb)  

### Preprocessing
[데이터 전처리](https://github.com/dnwjddl/LipReading_Korean/blob/master/data/Preprocessing_dataset.ipynb)
