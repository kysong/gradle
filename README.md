# gradle
gradle

<br />
<br />
D:\gradle-2.9\workspace\gradle-start>more build.gradle<br />
apply plugin: 'java'<br />
<br />
repositories { mavenCentral() }<br />
dependencies {<br />
  compile "joda-time:joda-time:2.2"<br />
  testCompile "junit:junit:4.11"<br />
}<br />
<br />
task wrapper(type: Wrapper) {<br />
    gradleVersion = '2.9'<br />
}<br />
<br />
<br />
D:\gradle-2.9\workspace\gradle-start>echo %PATH%<br />
C:\Program Files\Java\jdk1.8.0_65\bin;D:\gradle-2.9\bin;C:\ProgramData\Oracle\Java\javapath;C:\pytho<br />
n27_x64\;C:\python27_x64\Scripts;C:\Windows\system32;C:\Windows\system32;C:\Windows;C:\Windows\Syste<br />
m32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0\;C:\Program Files (x86)\Skype\Phone\;C:\Program<br />
Files (x86)\Google\Cloud SDK\google-cloud-sdk\bin;C:\Program Files\Bandizip\7z<br />
<br />
<br />
D:\gradle-2.9\workspace\gradle-start>gradle build<br />
:compileJava UP-TO-DATE<br />
:processResources UP-TO-DATE<br />
:classes UP-TO-DATE<br />
:jar UP-TO-DATE<br />
:assemble UP-TO-DATE<br />
:compileTestJava UP-TO-DATE<br />
:processTestResources UP-TO-DATE<br />
:testClasses UP-TO-DATE<br />
:test UP-TO-DATE<br />
:check UP-TO-DATE<br />
:build UP-TO-DATE<br />
<br />
BUILD SUCCESSFUL<br />
<br />
Total time: 4.456 secs<br />
<br />
<br />
D:\gradle-2.9\workspace\gradle-start>java -cp D:\gradle-2.9\lib\plugins\joda-time-2.8.2.jar;D:\gradl<br />
e-2.9\workspace\gradle-start\build\libs\gradle-start.jar hello.HelloWorld<br />
The current local time is: 14:17:18.888<br />
Hello world!<br />
