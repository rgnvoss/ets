<p>Usage: ets &lt;options&gt;<br>
<br>
Generate and send emails for testing.<br>
<br>
Miscellaneous Options:<br>
&nbsp;&nbsp;-h, --help                             Display this help text.<br>
&nbsp;&nbsp;-v, --version                          Display version information.<br>
<br>
Connection Options:<br>
&nbsp;&nbsp;-s, --server, --target                 Receiving mail server (required to send).<br>
&nbsp;&nbsp;-p, --port                             Target port.<br>
&nbsp;&nbsp;--ssl, --tls                           Use SSL/TLS.<br>
<br>
Envelope Options:<br>
&nbsp;&nbsp;-t, --to, --recipient                  Envelope recipient (required to send).<br>
&nbsp;&nbsp;-f, --from, --sender                   Envelope sender.<br>
<br>
Header Options:<br>
&nbsp;&nbsp;-x, --xm, --x-mailer                   X-Mailer header<br>
&nbsp;&nbsp;--to-header                            to: header (if different from recipient).<br>
&nbsp;&nbsp;--from-header                          from: header (if different from sender).<br>
&nbsp;&nbsp;--reply-to                             Reply-To: header (if different from sender).<br>
&nbsp;&nbsp;--return-path                          Return-PATH: header (if different from sender).<br>
&nbsp;&nbsp;--high, --low                          Message importance (default is medium).<br>
<br>
Email Content Options:<br>
&nbsp;&nbsp;--mix, --mixed                         Use multipart/mixed instead of multipart/alternative.<br>
&nbsp;&nbsp;--body-text                            Text body string.<br>
&nbsp;&nbsp;--body-html                            HTML body string.<br>
&nbsp;&nbsp;--text-encode, --text-charset          Text section character encoding.<br>
&nbsp;&nbsp;--html-encode, --html-charset          HTML section character encoding.<br>
&nbsp;&nbsp;--encode, --charset                    Character encoding for both text and html sections (overrides  --text-encode, --text-charset, --html-encode, & --html-charset).<br>
&nbsp;&nbsp;--url                                  Include malicious URL in email.<br>
&nbsp;&nbsp;--ssn                                  Include SSN numbers in email.<br>
&nbsp;&nbsp;--av, --virus                          Attach eicar test virus to email.<br>
&nbsp;&nbsp;--zip                                  Attach password protected zip file to email.<br>
&nbsp;&nbsp;--no-text                              No text body in email.<br>
&nbsp;&nbsp;--no-html                              No html body in email.<br>
&nbsp;&nbsp;--spam                                 Include spam content.<br>
&nbsp;&nbsp;--adult                                Include adult spam content (overrides --spam).<br>
&nbsp;&nbsp;--text-body                            Use specified file as text body.<br>
&nbsp;&nbsp;--html-body                            Use specified file as HTML body.<br>
&nbsp;&nbsp;--attach                               Attach specified file.<br>
<br>
Email Generation Options:<br>
&nbsp;&nbsp;-l, --loop                             Generate specified number of emails.<br>
&nbsp;&nbsp;--eml, --write                         Write email to eml file.<br>
&nbsp;&nbsp;--no-send                              Do not send email (implies --eml/--write).<br>
&nbsp;&nbsp;--eml-name                             write eml file to specified file name (implies --eml/--write).<br>
<br>
Logging Options:<br>
&nbsp;&nbsp;--log                                  Enable logging.<br>
&nbsp;&nbsp;--log-level                            Set logging level (implies --log). Valid values are:   debug   info   warning (default)   error   critical<br>
&nbsp;&nbsp;--log-file                             Set name of log file (defaults to ets.log, implies --log)<br>
