# iaru-emergency-message-form

This is LibreOffice Calc (ods) spreadsheet table designed to enter IARU Emergency Service Message Form, process it and reformat it to predevined message format depending on use case.

It is just helper allowing operator to use human readable form and convert content into format that is prepared to be transmitted over radio. It should help redicing manual work and cutting oportunities to make errors in message formatting.

Base model for this tool is https://www.iaru-r1.org/wp-content/uploads/2019/09/IARU-msg1.pdf.

## Amateur Radio Emergency Service

Amateur radio prooved itself as valuable asset in emergencies. When natural or human initiated disasters struck some ara that often means shutting down conventional communications (telecommunication infrastrucutre and public broadcasts). 

Amateur radio operators are trained and equipped to be operative even in that environment. They are independant on public infrastructure.

If you want to learn more follow [Emergency Operating Procedures](https://www.iaru-r1.org/about-us/committees-and-working-groups/emcomm/emergency-operating-procedures/).

## File

There is just one file, named [IARU-EmergencyMessageForm.ods](https://github.com/pedjas/iaru-emergency-message-form/blob/main/IARU-EmergencyMessageForm.ods). It may be openned using LibreOffice and other software that can read format.

It does not use macros, just expressions, so it is safe to use, and should work on most platforms.

## Usage

- Download [IARU-EmergencyMessageForm.ods](https://github.com/pedjas/iaru-emergency-message-form/blob/main/IARU-EmergencyMessageForm.ods)
- Open File.
- Select mode. For now CW and PHONE are available choices.
- Fill in the fields. Pay attention that Word Count field is read only. It calculates number of words automatically as you type message text.
- If you want to save copy of message to be able to create new one, save it using option Save As...

There is area below form that contains formatted message according to selcted mode. Are is read only but you can select it and copy content to paste it into message sending software.

## Contribution

There is room for contribution of others:
- deciding what additional MODES are needed and implementing support for them
- making translated document in languages other than English.

If you are able to help, feel free to jump in.

## Copyright (absence of)

IARU-EmergencyMessageForm.ods is published under [CC BY licence](https://creativecommons.org/licenses/by/4.0/).
