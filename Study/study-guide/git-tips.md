## Git Manual

1. 해당 저장소를 clone 합니다.
```
$ git clone https://github.com/BCS-study/basic-computer-science.git
```

2. clone 한 디렉터리로 이동 후 본인 이름(github id)의 브랜치로 체크아웃 합니다.
```
$ git checkout -b {github_id}
ex) git checkout -b NewCodes7
```

3. 학습한 내용을 마크다운 형식(xx.md) 혹은 PDF와 같이 Github Preview로 바로 볼 수 있는 형태의 확장자로 작성합니다.

4. 작성한 자료를 주제에 맞는 디렉토리에 위치시킵니다.<br/>
(존재하지 않을 시 생성 후 이동)

5. 변경 사항을 add/commit/push 합니다.<br/>
📍 Commit convention : [대주제] 소주제 분류(발표자료 정리/면접질문&답변/ ...)
```
$ git add .
$ git commit -m "[대 주제] 소주제 분류"
ex) git commit -m "[네트워크] HTTP 프로토콜 발표자료 정리"
$ git push origin {본인 브랜치 명}
```

6. Github에서 Pull Request를 등록합니다.<br/>
6-1) 저장소 내 `Pull requests` 메뉴로 이동<br/>
6-2) `New pull request` 버튼 클릭<br/>
6-3) base 브랜치는 `main`, compare 브랜치를 `{본인 브랜츠 명}`으로 설정<br/>
6-4) 제목과 내용을 작성하고 `Create pull request` 를 클릭하여 PR 등록<br/>
(만약 잘 이해가 안갔거나, 의견을 나누고 싶은 부분이 있을 경우 내용에 작성)<br/>

<여기까지가 `발표전까지의 과정`입니다.>

7. 발표 진행 후 본인의 PR을 `Merge pull request` 버튼을 눌러 반영(merge)합니다.<br/>
(만약 질문을 받은 내용이 있을 경우 간단하게 코멘트를 남겨주세요.)

<7번은 `발표후의 과정`입니다.>

<br/>