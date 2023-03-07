
# Install 

## Windows

- pyenv-win [pyenv-win/pyenv-win: pyenv for Windows. pyenv is a simple python version management tool. It lets you easily switch between multiple versions of Python. It's simple, unobtrusive, and follows the UNIX tradition of single-purpose tools that do one thing well. (github.com)](https://github.com/pyenv-win/pyenv-win)

### Trouble shooting 

#### 경로가 적절하게 배치되어 있지 않을 때 
- 경로상 상위에 있는 것이 우선적인 폴더로 잡힌다. 따라서 아래 안내대로 경로 순서를 바꾸면 된다. 
	- [Home · pyenv-win/pyenv-win Wiki (github.com)](https://github.com/pyenv-win/pyenv-win/wiki)
- 다만 파워셸에서 경로가 자동으로 업데이트되지 않는 듯 싶다. 
- 확인하는 방법 

```
> $env:path
```

- 이렇게 확인해보면, `miniconda3`가 위에 올라와 있는 경우가 종종 있다. 
- 이를 때는 powershell의 path 환경을 업데이트해줘야 한다. 

https://stackoverflow.com/a/50758683

- 잘 설정되었는지 아래와 같이 확인한다. 

```
> where.exe python 

C:\Users\junsokhuhh\.pyenv\pyenv-win\shims\python
C:\Users\junsokhuhh\.pyenv\pyenv-win\shims\python.bat
C:\Users\junsokhuhh\Miniconda3\python.exe
C:\Users\junsokhuhh\AppData\Local\Microsoft\WindowsApps\python.exe
```

- 