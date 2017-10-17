# 오토셋 8.0

## 설치 파일 다운로드(2013.09.27)

* [오토셋 8.0 패치3 (32비트 PC용) 설치 파일](http://sourceforge.net/projects/project-autoset/files/AutoSet8/AutoSet800Patch3_x32.exe/download) [용량: 147MB] via sourceforge
* [오토셋 8.0 패치3 (64비트 PC용) 설치 파일](http://sourceforge.net/projects/project-autoset/files/AutoSet8/AutoSet800Patch3_x64.exe/download) [용량: 160MB] via sourceforge

## 지원 운영체제
* 윈도우 시스템(윈도우 7/2008/8/8.1/10)에서 정상적으로 작동합니다.
* Visual Studio 2012 런타임 환경이 구성되어 있어야 합니다.
	* [Visual C++ Redistributable for Visual Studio 2012 Update 3 다운로드](http://www.microsoft.com/en-us/download/details.aspx?id=30679)
* 인터넷 익스플로러(Internet Explorer) 8.0 이상에서만 정상적으로 작동합니다.

## 구성 패키지 정보
* AutoSet Manager 8.0 (GUI Tool)
* Apache HTTPD Server 2.4.3
	* IPv6
    * Crypto enabled
    * apr-1.4.8
    * apr-util-1.5.2
    * apr-iconv-1.2.1
    * openssl-1.0.1e
    * zlib-1.2.8
    * pcre-8.33
    * libxml2-2.9.1
    * lua-5.1.5
    * expat-2.1.0
* PHP 5.5.3
* CUBRID Server 8.4.4
* CUBRID Manager 9.0.0 with JRE
* MySQL Community Server 5.6.13
* phpMyAdmin 4.0.5 All language
* Sendmail Version 32
* XpressEngine 1.7.3.4 + 게시판 모듈 1.7.1.1
* 그누보드(gnuboard4) 4.36.25 (utf-8)
* 킴스큐(KimsQ) RB 1.2.2
* 워드프레스(Wordpress) 3.6

## 오토셋 주요 기능

* GUI 를 이용한 Apache 및 PHP 설정 지원
* Apache 및 MySQL, SVN 백그라운드 실행 지원
* 가상호스트(VirtualHost) 관리/설정 지원
* 실시간 서버 모니터링 기능
* 센드메일 지원
* 프로그램 업데이트 기능 내장
* 직접 설치한 Apache 시스템도 GUI 관리 지원
* 트레이 아이콘으로 실행 하기 및 시작시 트레이바에서 실행하기 기능 지원
* RSS 리더 기능 내장
* 다이나믹 DNS 서비스 지원 (DNS에버, DNIP.net)
* MySQL 설정 및 데이터베이스 백업 및 복원 지원
* 홈 디렉토리 및 MySQL 데이터 폴더, 프로그램 설정 파일 백업 지원
* 리디렉트 설정 지원
* 서버 오류 페이지 설정 지원
* PHP 확장모듈 지능형 로드 설정 기능 내장

## 설치 시, 주의 사항

* 직접 설치한 Apache HTTP SERVER, MySQL 서버 또는 APM_SETUP, WAMPP, XAMPP 등의 패키지를 통해 설치한 서버 프로그램이 있다면, 삭제하거나 작동을 반드시 중지시켜주십시오.
* (기본 포트 충돌로 인해 동시에 사용 할 수 없습니다. 동시에 사용해야 하는 경우라면 오토셋 설치 후, 웹 서버와 MySQL 포트를 변경 후 오토셋을 사용하십시오.)

