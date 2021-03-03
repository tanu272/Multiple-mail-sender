Python script to send personalized mails to various contacts.

How it works:
    1.Download the files.
    2.Create a CSVfile in the same directory with all mails-ids and personalised parts of the mail body for each recipient.  
    3.Create a virtual environment using the following command
       pythom3 -m venv env
    3. Activate the virtual environment
        source env/bin/activate
    4. install dotenv
        python3.8 -m pip install python-dotenv
    5. run the python file mail.py.
    6. (to schedule mails) install hickory library with the command
        pip install hickory
    7. Run the following command to schedule your mails:
        hickory schedule mail.py --every=day@09:00am(required time)
        
