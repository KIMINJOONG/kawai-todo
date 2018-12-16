# kawai To Do
Kawai To Do App made with React Native
# 만났던 에러들
1. import "uuid" from "uuid/v1"
 - 이부분은 uuid 홈페이지를 가서 보니 변경이 되었나보다.
    홈페이지에서 직접사용법을 보고 변경함
    const uuidv = require('uuid/v1');
    const ID = uuidv();
    import를 해주지않고 위와같이 해줌

2. android빌드할때는 꼭 app.json 제일밑에
"android": {
      "package": "co.todo.kawai"
    }
    를 추가해주자!!

3. package.json을 건드렸을때 프로젝트 경로에서 npm start를 해주기! or package-lock.json을 삭제하고 해주기?
이부분은 해결은했지만 좀 더 찾아봐야겠다.

4. 'node_moudules' 디렉토리에서 'package.json'에 정의되지 않은 모듈을 모두 삭제하고 싶을때 npm prune를 하면됌

5. npm 혹은 yarn에서 필요한거 설치해놓고 계속 또 설치하면 당연히 설치가 안됀다. 정신똑바로 차리고 하자!
    
