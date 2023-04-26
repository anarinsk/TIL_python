# 기본 설정 

## BYGG (Before You Go Go)
- 콘다는 미니콘다를 포함해 모든 제품이 현재 200인 이상 사람들에게 유료화된 상태 
- 미니콘다의 경우 커뮤니티 버전이 콘다-포지 채널을 디폴트로 무료로 운영되고 있다. 
- [conda-forge/miniforge: A conda-forge distribution. (github.com)](https://github.com/conda-forge/miniforge)

## How to install 
- 링크에 설치 파일이 있으나, OS별 패키지 관리자의 도움을 얻는 것이 좋겠다. 
	- Windows: winget [Miniforge3 - winstall](https://winstall.app/apps/CondaForge.Miniforge3)
	- Macos: brew [miniforge — Homebrew Formulae](https://formulae.brew.sh/cask/miniforge)
	- Linux: apt 

>  **Note** 
> 일단 설치가 끝난 이후에는 miniconda와 사용법이 동일하다.

- 그냥 미니콘다를 쓰는 게 나을 듯 싶다. 

## conda update 

`conda update --all`
- 현재 환경의 패키지를 모두 업데이트 한다. 

`conda update -n base -c defaults conda`
- 콘다 패키지를 업데이트하는 명령어 

`conda install conda=4.12.0`
- 콘다 자치를 설치한다. 
- 콘다 패키지를 업데이트했음에도 하라고 나오면 위와 같이 설치한다. 

