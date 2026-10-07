# legacy-2018-2020 (private)

2018~2020년 학부·공모전 시절 결과물 보관용 저장소. 각 폴더는 원래 별도 저장소였고, 커밋 히스토리를 유지한 채 합쳤습니다.

| 폴더 | 원래 저장소 | 내용 |
|---|---|---|
| `hanium-r/` | `Hanium_R` | 한이음 "그것이R고싶다" 크롤러 |
| `python/` | `python` | Hanium Dogs, 크롤러, Django, TensorFlow 등 잡동사니 |
| `dacon/` | `dacon` | DACON 천체 분류 |
| `airlinedelay/` | `airlinedelay` | 2019 빅콘테스트 항공 지연 예측 |
| `elk/` | `ELK` | Kibana 대시보드 설정 |
| `flask/` | `flask` | Flask REST 예제 |
| `curriculum/` | `curriculum` | 파이썬 커리큘럼 예제 (블랙잭, 챗봇) |
| `face-recognition/` | `face_recognition` | 얼굴 인식 API |
| `python-rest/` | `python_rest` | nGle API (Flask boilerplate) |

`archive/python-rest/webb` 브랜치에 `python_rest`의 `webb` 브랜치를 보존했습니다.

합치면서 제외한 것: `venv/`, `.idea/`, `.vs/`, `OpenCV/` 빌드 결과물, `*.exe|*.dll|*.pyd|*.pyc`, `bfg-*.jar`,
OAuth `client_secret*.json`, GCP 서비스 계정 키 JSON 2개, 50MB 초과 파일(`XGBoost_model.joblib.dat`).
Django `SECRET_KEY` 하드코딩 값은 `change-me`로 치환했습니다.
