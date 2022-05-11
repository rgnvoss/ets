<p>Usage: ets &lt;options&gt;<br>
<br>
Generate and send emails for testing.<br>
<br>
Miscellaneous Options:<br>
  -h, --help                             Display this help text.<br>
  -v, --version                          Display version information.<br>
<br>
Connection Options:<br>
  -s, --server, --target                 Receiving mail server (required<br>
                                         to send).<br>
  -p, --port                             Target port.<br>
  --ssl, --tls                           Use SSL/TLS.<br>
<br>
Envelope Options:<br>
  -t, --to, --recipient                  Envelope recipient (required to<br>
                                         send).<br>
  -f, --from, --sender                   Envelope sender.<br>
<br>
Header Options:<br>
  -x, --xm, --x-mailer                   X-Mailer header<br>
  --to-header                            to: header (if different from<br>
                                         recipient).<br>
  --from-header                          from: header (if different from<br>
                                         sender).<br>
  --reply-to                             Reply-To: header (if different<br>
                                         from sender).<br>
  --return-path                          Return-PATH: header (if different<br>
                                         from sender).<br>
  --high, --low                          Message importance (default is<br>
                                         medium).<br>
<br>
Email Content Options:<br>
  --mix, --mixed                         Use multipart/mixed instead of<br>
                                         multipart/alternative.<br>
  --body-text                            Text body string.<br>
  --body-html                            HTML body string.<br>
  --text-encode, --text-charset          Text section character encoding.<br>
  --html-encode, --html-charset          HTML section character encoding.<br>
  --encode, --charset                    Character encoding for both text<br>
                                         and html sections (overrides <br>
                                         --text-encode, --text-charset,<br>
                                         --html-encode, & --html-charset).<br>
  --url                                  Include malicious URL in email.<br>
  --ssn                                  Include SSN numbers in email.<br>
  --av, --virus                          Attach eicar test virus to email.<br>
  --zip                                  Attach password protected zip<br>
                                         file to email.<br>
  --no-text                              No text body in email.<br>
  --no-html                              No html body in email.<br>
  --spam                                 Include spam content.<br>
  --adult                                Include adult spam content<br>
                                         (overrides --spam).<br>
  --text-body                            Use specified file as text body.<br>
  --html-body                            Use specified file as HTML body.<br>
  --attach                               Attach specified file.<br>
<br>
Email Generation Options:<br>
  -l, --loop                             Generate specified number of<br>
                                         emails.<br>
  --eml, --write                         Write email to eml file.<br>
  --no-send                              Do not send email (implies<br>
                                         --eml/--write).<br>
  --eml-name                             write eml file to specified file<br>
                                         name (implies --eml/--write).<br>
<br>
Logging Options:<br>
  --log                                  Enable logging.<br>
  --log-level                            Set logging level (implies<br>
                                         --log). Valid values are:<br>
                                           debug<br>
                                           info<br>
                                           warning (default)<br>
                                           error<br>
                                           critical<br>
  --log-file                             Set name of log file (defaults to<br>
                                         ets.log, implies --log)<br>
