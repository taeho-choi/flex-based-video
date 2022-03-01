

# flex-based-video
flex 기반 동영상 웹페이지입니다.<br> flex를 활용하여 웹 레이아웃을 제작하고, JavaScript로 동영상을 제어하였습니다.<br>
- 참고 서적: `Do it! 인터랙티브 웹 페이지 만들기`
- 개발 환경: <img src="https://img.shields.io/badge/Windows-0078D6?style=flat&logo=Windows&logoColor=white"/> <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=VisualStudioCode&logoColor=white"/>
- 개발 언어: <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/>

## Preview
![10](https://user-images.githubusercontent.com/60216512/156146248-d816a2d6-c49b-4887-9203-380aa08492f2.png)
![20](https://user-images.githubusercontent.com/60216512/156146256-345021ab-35d3-4d45-8c1b-268f0cf1056f.png)

## Comments
'aside 패널에서 CLOSE 텍스트를 클릭했을 때 사라지는 코드'를 '모든 article 요소를 순회하는 for 문' 안에 넣으라는 책의 내용이 잘못된 것 같습니다. article 요소는 4개이므로 CLOSE 텍스트 클릭 시 똑같은 코드가 4번 실행되기 때문입니다. console.log 함수로 디버깅 한 결과 4번이 출력되는 것을 확인하였고, for문 바깥으로 해당 코드를 빼냈습니다.
