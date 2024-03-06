# JOB SEEKER

---

Behold our groundbreaking project, a masterpiece of technology that graciously offers to email recruiters and inquire if, by some miraculous chance, they might have a job opportunity available at their esteemed firms. Because who wouldn't want an algorithm to handle such delicate matters?

---

## Required Data

- **YOUR_MAIL**: Your mailId
- **YOUR_NAME**: Your name to send name with
- **PASSWORD**: Your Email password (keep it in local _or I might track your history_)
- **ATTACHMENT_LOCATION**: file path of your resume (_better to store in same folder_).
- **EXCEL_FILE_PATH**: file path to recruiter data (_please do follow the template Recruiter_data.xlsx_)
- **MAIL_TIME_INTERVAL**: After how many minutes you want to send the email (keeping this to ensure uninteruped smtp connection and I have a speculation that mail account might get blocked if sent in small time interval).
- **MAIL_PER_DAY**: No of mails you want to send per day (_It will read <=(less than equal to) top MAIL_PER_DAY entries from the xlsx where statussss is undefined_).
- **SMTP_HOST_ADDRESS**: Address of your smtp server, you need to turn it on as smtp is disabled by default.
---

## Message Body

You need to set your message body as per your format, I will not be able to do everything for you.

For example you want to send message body as:

```
Hello {Recruiter_name},
I am intrested to work for your {company_name}. Do let me know.

Regards,
Your Fellow Developer
```

Replace the new lines with '\n' inorder to satisfy sting data structure properties, else code turns yellow and terminal red. Now it will look like:

```
Hello {Recruiter_name},\nI am intrested to work for your {company_name}. Do let me know.\n\nRegards,\nYour Fellow Developer
```

Feel free to tweak the function parameters to change the email template accordingly.

---

## Email Subject

Set the message subject in **get_email_subject** function.

---

## Manual Work needed to do

Maintain the xlsx file with the given sample file given. It works as you need to provide name, email, company_name in the sheet and **Keep the status column cell empty**.

---

## Make It Globally Executable

For any command to run globally it has to be present in path variable.
I can also copy paste the same content but lazinesss kicked-in so refer this [link](https://gist.github.com/joshwyatt/a6e20d28818b5183258b) .

---

### Future Updates

- [ ] Add email tracker function.
- [ ]

---

### Getting Errors

Contact via: [Instagram](https://www.instagram.com/___you_day___/) [LinkedIn](https://www.linkedin.com/in/udaygaidhane/)


Suggestions and improvements are entertained....