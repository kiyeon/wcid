# wcid
wcid(What can i do?) is a help command line tool.

구상중인 아이디어다.
개인적으로 DevOps 환경을 만드려고 하다보니 사용해야하는 CLI툴들이 많다.  
매번 작업할때마다 레퍼런스를 참조하기도 번거롭고 펑션이나 alias로 만들어둬도 시간이 흐르면 까먹기 일수다.
그래서 README를 만들어 두기도 하지만 레퍼런스처럼 번거롭기는 마찬가지다.

wcid는 환경파일(like .bashrc)에 case별로 내가 어떤것을 할 수 있는지를 기술해놓는다.

hugo 작업을 하거나 도커 이미지를 빌드하거나 서버셋팅을 해야하거나 DB작업을 해야할때  
$ wcid
You can do these.
  * docker run --rm -d --name=[container name] -p8080:80 mywebserver


뭐 이런식으로 내가 할 수 있는 것들이 무엇인지를 사용자 스스로 기술해놓기만 하면 된다.
이제 프롬프트의 깜박이는 커서만 바라보며 멍한 기분이 들땐 'wcid'를 하면 답을 알려준다.
체계화하고 발전시키면 alias용 툴로도 쓸 수 있고 wcid 설정파일을 서로 공유하면서 사용할 수도 있을 것이다.
