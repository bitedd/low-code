

# provide context
import 라이브러리, 이해하기 쉬운 함수/파라미터 명, 인라인 코멘트, 만약에 라이브러리의버전에 따라서 동작이 달라진다면, 문서의 내용을 코멘트해주면 된다.

# be predictable
이 말은 웹 어플리케이션을 작성시에는 Mvc 와같은 형태를 따르는게 낫다는 의미이다. Copilot이 학습할 때 많이 사용된 코드형태를 따르는 것이 copilot이 많이 도와주게 될것이다.

# 다른 부분에 영향을 많이주는 부분을 먼저 작성
* MVC 모델에서는 보통 model이 view와 controller에 영향을 두기 때문에 model 작성을 먼저하는게 나을 것이다.
* api개발시에는 api schema를 작성하는데 나을 것이다.
