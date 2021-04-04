# Chat-Box-Slack
I develop a small WebApp with following conditions:

Frontpage of app is an empty page with a button in the middle “open chat”
Press on button opens a modal window with a textarea and a “send” button. If you want you could animate the modal, e.g. by using https://animate.style/
The user can write something in the textarea and hit enter, which clears the textmessage
The written message gets send as a POST-Request to "" as JSON-format like this here
{"text":"test"} 
Message should then be visible in the slack channel
