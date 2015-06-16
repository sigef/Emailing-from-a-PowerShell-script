*Emailing from a PowerShell script*
=============


Send an email through your SMTP server using PowerShell
http://github.com/Automic-Community/Emailing-from-a-PowerShell-script

<!-- List of attached files -->
Contents of Solution Package:

						
								*Dollar_Universe-Email_through_PowerShell.zip
								
						


Documenation and Instructions
---

<p>The first&nbsp;file (PowerShell_Email_Script.txt)&nbsp;gives a PowerShell script that can be used to send an email through your SMTP server.&nbsp; There are extensions to the script to add attachments, that can be found online.&nbsp;<br /> &nbsp;<br /> We are using $U 6 on a Windows computer.&nbsp; We are using $U to execute SQL Agent jobs, and wanted an email notification when the SQL job started running.&nbsp; $U provides a email service for when the $U job completes, and this script allows us to have emails at other times.&nbsp;<br /> &nbsp;<br /> There are associated/node files that all $U to talk to and run SQL jobs.&nbsp; I inserted the script in one of those .ps1 files.&nbsp; Alternatively the script could be in a stand-alone .ps1 file and/or be called from the Uproc script or a .bat file.&nbsp; To call the .ps1 file from the Uproc script or .bat file, see the second file (ps1_call.txt).<br /> &nbsp;<br /> Variables passed to the file that the script is in can be used as part of the email as well, i.e. adding the SQL Agent job name to the subject line.&nbsp;</p><br />
<p>&nbsp;</p><br />
<p><strong class="title">Implementation:</strong> Add script to a PowerShell file. Add file to Uproc (associated file, node file). Call script.</p>

Copyright and License
---

Solutions, Templates, Actions and other content available on the Automic Marketplace subject to the Automic [Developers Distribution License] (http://automic.com/developers-distribution-license) as well as the Automic Community [Terms of Service] (http://automic.com/community-terms-of-service).
Automic does not support, maintain or warrant any content submitted by the Automic Community.



Questions or Need Help? 
---
Any questions or comments? Converse with your fellow Users in the [Automic Community] (https://community.automic.com).