# 콘다 환경 설정 

- 파이썬 작업을 오래간만에 할 때 확인할 수 있는 체크 리스트 

## 가상 환경 
- conda를 쓰자. 이 만한게 없다. 
- 파이썬 기본 환경은 조금 고통스러워~

## 기본 문법 

- `conda` 
- `env` - 환경에 관한 명령이 붙는다. 없으면 패키지 관리 
- `create`, `install`, `remove` 
	- `create` - env만 해당 
	- `install` - package만 해당 
- `--name`, `-n`
	- 해당 환경 명, 패키지 명을 적시하기 위해서 활용된다. 

### 기본 명령어 셋 

#### 환경 생성 및 활성화
```shell
$ conda create --name(-n) {NAME-OF-ENV} python={3.10}
$ conda activate {NAME-OF-ENV}
$ conda deactivate # 현재 환경을 비활성화 ```bash
$ conda create --name(-n) {NAME-OF-ENV} --clone {NAME-OF-ENV-COPIED} # 환경 복사 
$ conda remove --name {NAME-OF-ENV} #환경 제거 
```

 #### 패키지 인스톨 
```shell
$ conda install {NAME-OF-PACKAGE}
```
#### 업데이트 
```shell
$ conda update --all # base에서 치자 
```
