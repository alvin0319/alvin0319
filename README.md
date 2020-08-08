:grinning: 안녕하세요, 저는 [PocketMine-MP](https://github.com/pmmp/PocketMine-MP) 소프트웨어의 플러그인을 개발하고 있는 한 고등학생 입니다.

현재 주로 하는 언어는 [PHP](https://www.php.net)이며 지속적으로 JavaScript, [Java](https://java.com), C 등을 병행하고 있습니다.
# 가능한 연락처 / Available contacts
![](https://img.shields.io/badge/chat%20on-Telegram-blue)
</a>
<a href="https://open.kakao.com/me/alvin0319"><br>
![](https://img.shields.io/badge/chat%20on-KakaoTalk-yellow)
</a>
<script>
function showRepos(){
            var xmlHttpRequest = new XMLHttpRequest();
            xmlHttpRequest.open("GET", "https://api.github.com/users/alvin0319/repos");

            xmlHttpRequest.onreadystatechange = function(){
                var decodedData = JSON.parse(xmlHttpRequest.responseText);
                //document.write(`${decodedData.length}`);
                for(var j = 0; j < decodedData.length; j++){
                    var repo = decodedData[j];

                    //document.write(`<br>${j}`);

                    document.writeIn("<br>Repo name: " + repo.name);
                }
            }
            xmlHttpRequest.send();
        }
</script>
<input type="button" value="click to load repos..." onclick="showRepos()">



<!--
**alvin0319/alvin0319** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
