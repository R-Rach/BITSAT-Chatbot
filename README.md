An AI powered contextual Chatbot assistant using RASA Framework for answering the queries of user about BITS Pilani entrance exam (BITSAT)


#HOW TO RUN

1. Make a virtual  environment named "rasa-env" and install all packages from requirments.txt, using following command -> pip install -r requirements.txt

2. Open two instances of terminal and activate "rasa-env" environment on both instances.

3. Go to 'Code/English/' in FIRST terminal profile and run the command -> " rasa run -m models --enable-api --cors "*" --debug --port 5005 "
   {English bot running on port:5005}

4. Go to 'Code/Hindi/' in the SECOND terminal profile and run the command -> " rasa run -m models --enable-api --cors "*" --debug --port 5006 "
   {Hindi bot running on port:5006}


7. Now open 'index.html' in 'UI' folder on a browser (Chrome preferred) and use the bot as shown in video.

8. Bot offers the functionality to type or voice recognition by pressing mic button. 