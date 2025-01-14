# level-2

프론트엔드스쿨 5조 level 2

이 문제는 https://github.com/bradtraversy/50projects50days?tab=readme-ov-file 를 참고해 만들었습니다.

<br>

[노션 링크 바로가기](https://www.notion.so/Level-2-977e3099cf0e41bbb2b02a8c70e15c2a)

[데모 보기](https://50projects50days.com/projects/drag-n-drop/)

<br>

## 프로젝트 시작 방법!!

1. clone level-1 repository

```
git clone https://github.com/tekit-school-five-member/level-2.git
```

<br>

2. 본인 이름의 branch 생성

```
git checkout -b <yourName>
```

<br>

3. 본인 이름 브랜치의 feature 브런치 생성

```
git checkout -b feature/<yourName>
```

<br>

&nbsp;&nbsp;&nbsp;&nbsp;어려우시면 깃허브에서 아래의 방법을 사용하세요. <br> <br>
&nbsp;&nbsp;&nbsp;&nbsp;<img width="600px" src="https://github.com/tekit-school-five-member/level-3/assets/60402888/494198c6-db3c-4429-a76c-3077929bf6fe"/>

<br>

4. feature/&lt;yourName&gt; 브랜치에서 수정한 내용 &lt;yourName&gt; 브랜치로 PullRequest

&nbsp;&nbsp;&nbsp;&nbsp;저장소 꼭 확인해주세요. <br> <br>
&nbsp;&nbsp;&nbsp;&nbsp;<img width="600px" src="https://github.com/tekit-school-five-member/level-3/assets/60402888/76d54486-3a57-43d3-96e3-bd6bb3f0ed61"/>

<br>

&nbsp;&nbsp;&nbsp;&nbsp;pull request 작성시 아래 이미지를 참고해주세요. <br> <br>
&nbsp;&nbsp;&nbsp;&nbsp;<img width="600px" src="https://github.com/tekit-school-five-member/level-3/assets/60402888/270e9372-7b61-42db-9045-0f58ce6c3408"/>

<br>
<br>

## 목표

- [ ] 드래그 시작시 <code>fill</code>엘리먼트에 hold 클래스 추가

```js
elem.className += " hold";
```

<br>

- [ ] <code>fill</code>엘리먼트 클래스를 <code>invisible</code>로 변경 (hint: setimeout 함수의 비동기 처리 기능 사용)

<br>

- [ ] 드래그가 끝나면 <code>empty</code>엘리먼트에 <code>fill</code>엘리먼트를 자식 노드로 넣기

```js
parentElem.appendChild(elem);
```

<br>

- [ ] 마우스가 호버되는 <code>empty</code>엘리먼트에 hovered 클래스 추가

```
 this.className += " hovered";
```

<br>

- [ ] 마우스가 호버가 끝나면 <code>empty</code>엘리먼트에 hovered 클래스 제거
