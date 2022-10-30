# 콘다 환경 설정 

- 파이썬 작업을 오래간만에 할 때 확인할 수 있는 체크 리스트 

## 가상 환경 
- conda를 쓰자. 이 만한게 없다. 
- 파이썬 기본 환경은 조금 고통스러워~

### 기본 명령어 셋 

- 환경 생성 및 활성화
```bash
$ conda create --name(-n) {NAME-OF-ENV} python={3.10}
$ conda activate {NAME-OF-ENV}
$ conda deactivate # 현재 환경을 비활성화 
```
- 환경 복사 
```bash
$ conda create --name(-n) {NAME-OF-ENV} --clone {NAME-OF-ENV-COPIED}
```
- 환경 제거 
```bash
$ conda remove --name {NAME-OF-ENV}
```
- 패키지 인스톨 
```shell
$ conda install {NAME-OF-PACKAGE}
```
