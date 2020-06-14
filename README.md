# Settings for Dev

새로운 컴퓨터에 개발자 세팅을 하기 위한 안내서입니다.

[TOC]

## 01 Python

Backend 개발이나 알고리즘 풀이를 위해 선택한 언어



## 02 Visual Studio Code

코드작성을 위한 프로그램

- [VS Code homepage](https://code.visualstudio.com/) 에서 OS에 맞는 파일을 다운로드 및 설치(포함된 파일은 Windows 64bit) 



## 03 Git bash

Github 관리를 위한 프로그램

- [Git bash homepage](https://gitforwindows.org/) 에서 OS에 맞는 파일을 다운로드 및 설치
- 설치 후 config에 email과 name을 정의
  - `git config --global user.email "email address"`
  - `git config --global user.name "name"`
  - respository만의 이름, 이메일 설정은 `--global` 을 없애주면 된다. 
- 50MB가 넘는 파일을 올릴 경우 Git에서 LFS (Large File Storage)를 사용하길 권고
  - [Git LFS hompage]( https://git-lfs.github.com)
  - [간단한 사용 설명 Youtube](https://www.youtube.com/watch?v=uLR1RNqJ1Mw)
  - `git lfs track 'path/*.filetype'` : 해당 폴더 내의 지정한 파일 형식을 lfs로 관리하겠다
    - 현재 repo에서는 `git lfs track "Downloads/*.exe"` 로 다운로드 파일들을 관리
    - 폴더 전체를 관리하라 할 수도 있고, 해당 프로젝트의 특정 파일타입에 대해서 명령어를 실행할 수도 있다. 
    - `git lfs ls-files`: lfs로 관리하고 있는 파일 목록을 보여준다. 



## 04 Typora

문서작성을 위한 markdown 문서 프로그램

- 