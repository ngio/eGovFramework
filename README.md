전자정부 프레임워크를 하면서. 1도 모르지만 정리를 한번 해보자. 

2019-05-15 아직 맥북에서 설치완료를 못하고 있다. 3.2 설치 중. 

윈도우에서는 유지보수 업무를 진행 중. 


====================================================================================================
맥북프로에 전자정부 프레임워크 셋팅 중 2019-04-26~
eclipse
tomcat7
Spring Core
UML2 extension 
Subversive SVN Team Provider
SVNKit 1.8.12 Implementation(5.0.3) 
eGovFrame 3.6.0 (필수) 
MyBatipse 1.0.23 (선택)    MyBatipse -> MyBatipse 설치
PMD 4.0.11 (선택)
Developer Tools 23.0.7 / Android Connector for M2E 1.4.0(안드로이드 개발 필수)
~~~ ing

====================================================================================================
맥북프로에 eGovFrame 셋팅 - 2019-04-30
Eclipse MARS.2
 - install New Software 로 쭉 설치 
   - SpringCore :  
Spring Core_e4.4 - https://download.springsource.com/release/TOOLS/update/e4.4/
Spring IDE -> Spring IDE Core

   - UML2 Extension 5.1.2 : http://download.eclipse.org/releases/mars/  Modeling > UML2 Extender SDK  

   - Subversive SVN Connector 6.0.1 :  http://download.eclipse.org/releases/mars/  Collaboration -> Subversive SVN Team Provider(3.0.4)
     http://community.polarion.com/projects/subversive/download/eclipse/5.0/mars-site/
    Subversive SVN Connectors -> Subversive SVN Connectors(5.0.3) 설치
    SVNKit 1.8.12 Implementation(5.0.3) 설치 

   - eGovFrame3.6.0 : http://maven.egovframe.kr:8080/update_3.6/ 전부 설치

   - JUnit 4.12 : 
   - MyBatipse 1.0.23 (선택) :   http://dl.bintray.com/harawata/eclipse
                                                    http://dl.bintray.com/harawata/eclipse/mybatipse/
                                                    MyBatipse -> MyBatipse 설치


• 참조 URL
 • https://jhlblue.tistory.com/4


====================================================================================================
2019-04-26
맥에서 전자정부프레임워크 구성하기   http://www.egovframe.go.kr/

[[egovframework:dev2:install_guide]] http://www.egovframe.go.kr/wiki/doku.php?id=egovframework:dev2:install_guide#install_guide

1. 이클립스 mars 버전 다운로드

http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/mars/2/eclipse-jee-mars-2-macosx-cocoa-x86_64.tar.gz


Eclipse downloads - Select a mirror
Eclipse is probably best known as a Java IDE, but it is more: it is an IDE framework, a tools framework, an open source project, ...
www.eclipse.org

2. Maven 설치 : brew install maven (저는 주로 Homebrew 를 이용해서 설치합니다.)

3. 자바는 8버전으로 설치함

4. 이클립스를 띄운 후 스프링 설치 : 마켓에서 sts(스프링 부트도 주로 이용함으로) 검색하셔서 설치하세요.

5. 인스톨 뉴 소프트웨어를 이용해서 전자정부프레임워크를 설치합니다.  

add -> egovframework - http://maven.egovframe.kr:8080/update/

6. 샘플프로젝트로 가볍게 egovframe web project 하나 만드시고 다음으로 가서 Generate Example 을 체크하시면 샘플소스를 셋팅하실 수 있습니다. (만일 예제파일이 보이지 않는 경우 Maven 설치가 제대로 안된 경우일 수 있으니 체크해 주세요.)

7. 톰캣을 brew로 설치 : 8버전은 8.5로 설치되서 7버전을 설치함 brew install tomcat7

8. 톰캣 위치 설정 : /usr/local/Cellar/tomcat@7/7.0.77/libexec 

9. 톰캣 스타트



http://localhost:8080/sample/ 또는 http://localhost:8080/sample/egovSampleList.do

====================================================================================================
2019-05-13

JDK 1.7 SE 지워버림.
Open JDK 1.8 이용
전자정부 프레임워크 3.7 설치
프로젝트 Build Automatically 꺼버림
Project –> Clean
Run As –> Maven clean
Maven –> Update Project
Build

---------
2019-09-03

맥북에서 설치는 보류하고 프로젝트 하나 완료.
JAVA, Mybatis, Mysql, jQuery, Android Studio를 이용한 WebApp



