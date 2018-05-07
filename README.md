# cs50-exercise-and-work-


http://cs50.tv/2017/fall/


CS50 中文導讀
https://www.youtube.com/playlist?list=PLeWlPscCzV-emSo2phZqStPZ0UDKzKu8s


CS50 IDE Offline
https://manual.cs50.net/ide/offline

Windows

NOTE: If these system requirements are not met, skip to Docker Toolbox.
<ol>
<li>Install Docker for Windows.</li>
<li>Open up a command prompt window and run the following command to create a new CS50 IDE instance:</li>

<code>docker run --privileged -e "IP=127.0.0.1" -e "PORT=8080" --name ide50 -d -p 5050:5050 -p 8080-8082:8080-8082 cs50/ide</code>

<li>Visit http://localhost:5050/ in your favorite browser to access CS50 IDE.</li>
<ol>
