# UNICEF-PoC

This app is used to capture the send and received messages from WhatsApp and
for children to ask their queries with a counselor.

For capturing the received messages we use notification listeners.
 So if the whatsapp notification comes, then only we can capture the received messages.
And also for this we need special notification access permission from the user.
And for capturing the WhatsApp send messages we use keylogger which detect the keyboard triggering from the device.
For this user has to enable the accessibility permission

For the counselling part child can click on speak button to start asking their queries.
If the query match with the queries in database it will populate the answer.
For matching the queries we use Levenshtein distance algorithm.
If the match is above 65% with the queries in database then only we will populate the result


![](https://github.com/sinergiamedialabs/UNICEF-PoC/blob/main/flow.gif)