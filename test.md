## Git 실습 - 문제풀기
> 아래에 있는 각각의 문제에 대해 답과 이유를 작성하시오.
> 함께 PR을 날리면서 집단지성을 통해 문제를 풀어 봅시다.

1. git은 무엇인가요?   
   - 답 : 분산 버전 관리 프로그램
  
2. Staging Area의 역할은 무엇일까요?
   - 답 :  커밋을 위한 파일 및 폴더가 추가되는 곳

3. 변경사항을 기록하는 과정을 아래 코드 블록에 작성해 주세요.
   - 답
   ```bash
   $ git add .
   $ git commit -m "change somthing" 
   ```

4. 아래와 같은 메시지가 발생했을 때, 무엇을 해야 할까요?
![image](https://user-images.githubusercontent.com/98133984/181182281-4d01a374-62fe-4957-9a07-1efc005e35d3.png)
   - 답
   ```bash
   $ git config --global user.name "이름"
   $ git config --global user.email "메일 주소"  

   ```
5. clone과 pull의 차이는 무엇인가요?
   - git clone은 원격 저장소의 커밋 내역을 모두 가져와 로컬 저장소를 생성하는 명령어로, 해당 명령어를 사용하면 원격 저장소를 통째로 복제해서 내 컴퓨터에 옮길 수 있다.
   - git pull은 원격 저장소의 변경사항을 가져와서, 로컬 저장소를 '업데이트'하는 명령어로, 로컬 저장소와 원격 저장소의 내용이 완전 일치하면 git pull을 해도 변화가 일어나지 않는다.
   
6. branch를 만드는 목적은 무엇인가요?
    - 답 : 

7. branch를 생성하는 동시에 이동하는 명령어는 무엇인가요?
    - 답 : git branch -c branch.name

8. 다음과 같은 상황이 나타났을 때 어떻게 해야 하나요?
   ![image](https://user-images.githubusercontent.com/98133984/181183354-df42d325-b839-48e1-a4c6-667c20b33d5c.png)
    - 답 : 원격저장소에 있는 폴더 또는 파일을 먼저 pull해서 로컬 저장소와 충돌하는 부분을 merge한 후에 다시 push한다.

9.  소유권이 없는 협업을 하기 위해서 가장 먼저 해야 할 것은 무엇일까요?
10. 소유권이 없는 협업의 경우, `git push origin master`로 원격 저장소에 변경사항을 반영할 수 있다.
    - 답 : O/X
    - 이유 :
 
11. git reset 명령어의 옵션 중, staging area 상태로 돌아가는 옵션은 ______이다.
    - 답 : 

12. 바로 직전 커밋을 수정하기 위해서 필요한 명령어를 작성하세요.
    - 답
    ```
    ```

13. merge와 rebase의 차이점은 무엇일까요? 
     - 답 : 
