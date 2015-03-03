
#UPDATE 13-02-2015
Version  0.2 of our module released

– Added field in Mail tab that lets you configure smtp account for sending mails independently from your store main email
– All emails from contact forms and notifications will be send to main store email

#OpenCart-SMTP-email-from-fix
This is a patch to fix problems with sending contact form in Opencart 1.5.x and 2.x

If you get the following or simillar message:

Notice: Error: RCPT TO not accepted from server! in system/library/mail.php on line 308

Than this vqmod will fix it.

#REQUIREMENTS
1. Opencart version 1.5 or higher (including OC 2.x series)
2. You need to have vqmod installed

#INSTALL
Just download file for your OpenCart version and upload it to vqmod/xml directory in your Opencart installation folder.
Note:
ose_email_oc1.xml is for Opencart 1.5 or higher
ose_mail_oc2.xml is for Opencart 2.0 or higher

#CONFIGURATION
Those modules will use SMTP Email Address as the FROM field. So make sure that this field is the same as the account you set in email tab in your shop settings.

The emails will be send TO your main shop email (set in Email field in Store tab).

#MORE INFO
For more info, detalied instructions, feedback and comments see here:
http://www.expertsos.net/blog/opencart-fixing-notice-error-rcpt-to-not-accepted-from-server-vqmod/
