# voice-bot-task4
This repository for voice bot. I have used three IBM Watson services which are Speech To Text (STT), Watson Assistant chatbot, and Text To Speech (TTS). There is only one version for voice bot which is English. There are three folders (STT and TTS task 4.1, STT and TTS task 4.2, STT and TTS task 4.3). For first one, I have built STT with save file as .txt which name is response.txt, TTS with save the file as .mp3 which name is speech.mp3, and there is a play sound of speech.mp3. For second one, I have added Watson Assistant chatbot between STT and TTS, so when someone speaks, it will send to STT. Then, after getting the text from STT, it will send to Watson Assistant chatbot. After that, it will send the response from Watson Assistant chatbot to TTS and play the file speech.mp3. For last one, I have customized the code to become faster for response compared to second folder, which is STT and TTS task 4.2. 
<br>
The dialog of chatbot has 8 intents as follow: 
<br>
1- Welcome: it shows welcome when someone open it. 
<br>
2- Greeting: when a person send greeting like hello, good morning, etc. 
<br>
3- Services: it provides services of chatbot when a person writes “what are services?” or similar question. Also, it has 3 entities. 
<br>
4- Building website: it provides how I have built the website when person writes “can you tell me how you build the website?”.
<br>
5- Time of tournament: it provides the time of tournament when a person writes “When will the tournament begin?”. 
<br>
6- Cost of tournament: it provides the cost of tournament when a person writes “Is there any fee for the tournament?”. 
<br>
7- Thanks, it provides the pleasure when a person writes “Thanks”, “Thank you”, etc. 
<br>
8- Anything else: if the chatbot cannot recognize what a person writes.  
<hr>
Note: to run the code, I recommend to open the folder watson-streaming-stt by visual studio code and write “python transcribe.py -t 5” (the number 5 represent the time to record the voice of person in seconds, so if want to record with more time, you should increase the number).
