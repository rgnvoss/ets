<p>Usage: ets &lt;options&gt;<br>
<br>
Generate and send emails for testing.<br>
<br>
Miscellaneous Options:<br>
&nbsp;&nbsp;-h, --help&nbsp;&nbsp;:&nbsp;&nbsp;Display this help text.<br>
&nbsp;&nbsp;-v, --version&nbsp;&nbsp;:&nbsp;&nbsp;Display version information.<br>
<br>
Connection Options:<br>
&nbsp;&nbsp;-s, --server, --target&nbsp;&nbsp;:&nbsp;&nbsp;Receiving mail server (required to send).<br>
&nbsp;&nbsp;-p, --port&nbsp;&nbsp;:&nbsp;&nbsp;Target port.<br>
&nbsp;&nbsp;--ssl, --tls&nbsp;&nbsp;:&nbsp;&nbsp;Use SSL/TLS.<br>
<br>
Envelope Options:<br>
&nbsp;&nbsp;-t, --to, --recipient&nbsp;&nbsp;:&nbsp;&nbsp;Envelope recipient (required to send).<br>
&nbsp;&nbsp;-f, --from, --sender&nbsp;&nbsp;:&nbsp;&nbsp;Envelope sender.<br>
<br>
Header Options:<br>
&nbsp;&nbsp;-x, --xm, --x-mailer&nbsp;&nbsp;:&nbsp;&nbsp;X-Mailer header<br>
&nbsp;&nbsp;--to-header&nbsp;&nbsp;:&nbsp;&nbsp;to: header (if different from recipient).<br>
&nbsp;&nbsp;--from-header&nbsp;&nbsp;:&nbsp;&nbsp;from: header (if different from sender).<br>
&nbsp;&nbsp;--reply-to&nbsp;&nbsp;:&nbsp;&nbsp;Reply-To: header (if different from sender).<br>
&nbsp;&nbsp;--return-path&nbsp;&nbsp;:&nbsp;&nbsp;Return-PATH: header (if different from sender).<br>
&nbsp;&nbsp;--high, --low&nbsp;&nbsp;:&nbsp;&nbsp;Message importance (default is medium).<br>
<br>
Email Content Options:<br>
&nbsp;&nbsp;--mix, --mixed&nbsp;&nbsp;:&nbsp;&nbsp;Use multipart/mixed instead of multipart/alternative.<br>
&nbsp;&nbsp;--body-text&nbsp;&nbsp;:&nbsp;&nbsp;Text body string.<br>
&nbsp;&nbsp;--body-html&nbsp;&nbsp;:&nbsp;&nbsp;HTML body string.<br>
&nbsp;&nbsp;--text-encode, --text-charset&nbsp;&nbsp;:&nbsp;&nbsp;Text section character encoding.<br>
&nbsp;&nbsp;--html-encode, --html-charset&nbsp;&nbsp;:&nbsp;&nbsp;HTML section character encoding.<br>
&nbsp;&nbsp;--encode, --charset&nbsp;&nbsp;:&nbsp;&nbsp;Character encoding text and HTML sections (overrides  --text-encode, --text-charset, --html-encode, & --html-charset).<br>
&nbsp;&nbsp;--url&nbsp;&nbsp;:&nbsp;&nbsp;Include malicious URL in email.<br>
&nbsp;&nbsp;--ssn&nbsp;&nbsp;:&nbsp;&nbsp;Include SSN numbers in email.<br>
&nbsp;&nbsp;--av, --virus&nbsp;&nbsp;:&nbsp;&nbsp;Attach eicar test virus to email.<br>
&nbsp;&nbsp;--zip&nbsp;&nbsp;:&nbsp;&nbsp;Attach password protected zip file to email.<br>
&nbsp;&nbsp;--no-text&nbsp;&nbsp;:&nbsp;&nbsp;No text body in email.<br>
&nbsp;&nbsp;--no-html&nbsp;&nbsp;:&nbsp;&nbsp;No html body in email.<br>
&nbsp;&nbsp;--spam&nbsp;&nbsp;:&nbsp;&nbsp;Include spam content.<br>
&nbsp;&nbsp;--adult&nbsp;&nbsp;:&nbsp;&nbsp;Include adult spam content (overrides --spam).<br>
&nbsp;&nbsp;--text-body&nbsp;&nbsp;:&nbsp;&nbsp;Use specified file as text body.<br>
&nbsp;&nbsp;--html-body&nbsp;&nbsp;:&nbsp;&nbsp;Use specified file as HTML body.<br>
&nbsp;&nbsp;--attach&nbsp;&nbsp;:&nbsp;&nbsp;Attach specified file.<br>
<br>
Email Generation Options:<br>
&nbsp;&nbsp;-l, --loop&nbsp;&nbsp;:&nbsp;&nbsp;Generate specified number of emails.<br>
&nbsp;&nbsp;--eml, --write&nbsp;&nbsp;:&nbsp;&nbsp;Write email to eml file.<br>
&nbsp;&nbsp;--no-send&nbsp;&nbsp;:&nbsp;&nbsp;Do not send email (implies --eml/--write).<br>
&nbsp;&nbsp;--eml-name&nbsp;&nbsp;:&nbsp;&nbsp;write eml file to specified file name (implies --eml/--write).<br>
<br>
Logging Options:<br>
&nbsp;&nbsp;--log&nbsp;&nbsp;:&nbsp;&nbsp;Enable logging.<br>
&nbsp;&nbsp;--log-level&nbsp;&nbsp;:&nbsp;&nbsp;Set logging level (implies --log). Valid values are: debug, info (default), warning, error, critical<br>
&nbsp;&nbsp;--log-file&nbsp;&nbsp;:&nbsp;&nbsp;Set name of log file (defaults to ets.log, implies --log)<br>
