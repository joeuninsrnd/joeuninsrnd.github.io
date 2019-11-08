## Welcome to Joeunins GitHub Pages

bxr_plover(민감정보 생명주기 관리프로그램)는 최근 정부에서 진행되는 개방형 OS 도입 및 확산 프로젝트의 한 부분으로 진행되는 연구 개발로써 개방형 OS 환경에서의 민감정보 검출 및 유출을 방지하기 위한 방향으로 진행할 것이며, RabbitMQ를 사용하여 Server와 Client 통신을 하고 MariaDB, Tomcat을 사용할 예정이다. 현재 GTK와 Glade로 개발한 UI를 통해 Server/Client 구조로 txt파일 형태의 민감정보(주민등록번호, 외국인등록번호, 운전면허번호, 여권번호) 검출이 가능하며 hwp, pdf 등과 같은 다양한 문서포맷을 검출하는 모듈을 개발중이다. 또한, 관리자 페이지도 개발 및 디자인 중이다.

### Process

Client <=> Server <=> Web <=> Administrator

#Client#<br>
Debian 10<br>
GTK+ 3.24.10<br>
RabbitMQ 3.7.17<br>

#Server#
Debian 10<br>
RabbitMQ 3.7.17<br>
MariaDB 10.4.7<br>

#Web#
Tomcat<br>
Web/WAS 9.0.21<br>

#Administrator#
Web Console<br>

For more details see [Joeunins BXR_Plover](https://github.com/joeuninsrnd/bxr_plover).<br>

### Support or Contact

[SLACK](https://joeunins.slack.com)<br>
[BLOG](https://joeuninsrnd.tistory.com)<br>
[GITHUB PAGE](https://joeuninsrnd.github.io)<br>
[GITHUB](https://github.com/joeuninsrnd/bxr_plover/blob/master/CONTRIBUTING.md)<br>
