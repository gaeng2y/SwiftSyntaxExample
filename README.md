## SwiftSyntaxExample

이 스위프트(Swift) 코드는 컴퓨터 프로그램의 한 부분으로, 특정 파일에서 'import' 구문을 찾아서 알파벳 순서대로 정렬해주는 역할을 합니다. import 구문은 다른 코드 파일들에서 작성된 코드를 현재 파일에서 사용할 수 있게 해줍니다. 코드를 설명하기 쉽게 나눠볼게요.

코드의 주요 부분들
main 함수:

이 부분은 프로그램이 시작할 때 가장 먼저 실행되는 곳입니다. 파일의 경로를 입력으로 받아서 그 파일이 실제로 존재하는지, 읽을 수 있는지 확인합니다. 파일이 문제없이 확인되면, 그 파일을 가져와서 formatImports 함수를 사용해 정렬합니다.
formatImports 함수:

이 함수는 주어진 파일에서 모든 'import' 구문을 찾아서 정리합니다. 'import' 구문과 다른 코드를 분류하고, 'import' 구문만 알파벳 순으로 정렬한 후, 원래 파일의 형태로 다시 조립합니다.
classifyItems 함수:

이 함수는 파일의 각 줄을 검사하여 'import'인지 아닌지를 확인합니다. 'import'이면 'import' 목록에 추가하고, 아니면 다른 목록에 추가합니다.
초등학생을 위한 설명
상상해 보세요, 우리가 도서관에 가서 여러 책들을 빌리려고 한다고 생각해봅시다. 도서관에는 정말 많은 책들이 있지만, 우리는 특별히 '과학' 책들만 골라서 알파벳 순서대로 책장에 정리하고 싶어요. 이 프로그램은 컴퓨터 파일을 도서관에 있는 책들처럼 생각할 수 있어요.

도서관 = 컴퓨터 파일
과학 책 = 'import' 구문
책장 정리 = 'import' 구문을 찾아서 알파벳 순서대로 정리
처음에는 모든 책들이 책장에 조금 뒤죽박죽이에요. 우리의 작업은 과학 책들만 골라내서 새로운 책장에 아름답게 알파벳 순서로 배열하는 거예요. 그리고 나머지 책들은 그대로 두면 돼요. 이렇게 하면 나중에 과학 책을 찾기 쉬워지겠죠?

이 코드는 바로 그런 일을 컴퓨터 파일에서 해주는 프로그램이에요. 'import'라고 적힌 줄들을 모두 찾아서, 그것들을 깔끔하게 정렬해줘요. 그래서 나중에 프로그래머가 이 파일을 볼 때, 필요한 'import'를 쉽게 찾을 수 있도록 해줍니다.
