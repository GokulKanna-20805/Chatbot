# Chatbot
<!DOCTYPE html>
<html>
    <body>
        <script>
            !function(w, d, s, ...args){
              var div = d.createElement('div');
              div.id = 'aichatbot';
              d.body.appendChild(div);
              w.chatbotConfig = args;
              var f = d.getElementsByTagName(s)[0],
              j = d.createElement(s);
              j.defer = true;
              j.type = 'module';
              j.src = 'https://aichatbot.sendbird.com/index.js';
              f.parentNode.insertBefore(j, f);
            }(window, document, 'script', '29936CDF-395C-41B0-85AC-BADA2467C3F1', 'onboarding_bot', {
              apiHost: 'https://api-cf-ap-8.sendbird.com',
            });
            </script>
    </body>
</html>
