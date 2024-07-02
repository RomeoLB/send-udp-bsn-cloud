# bsn.cloud Player Remote UDP Control

This simple HTML app can be used to communicate with a remote Brightsign player via bsn.cloud using REST API to send a UDP message. 

Make sure to enter in the relevant fields:

- Network Name
- Username
- Password
- client_id
- client_secret
- Device Serial number

Then click on the "Authenticate" button to obtain a token to allow communication with the bsn.cloud control server. If successful you should see an access_token displayed in the "Request Status" field. 

<img width="563" alt="image" src="https://github.com/RomeoLB/send-udp-bsn-cloud/assets/136584791/f0f45cc0-f084-42b9-b31c-c7269877dcc7">

After authenticating with the bsn.cloud control server, you can click on one of the Pre-programmed UDP button to send a UDP message (play1, play2 or play3) or enter a UDP command in the "Enter Custom UDP Command below" field then click on the "Send Custom UDP" button to send a UDP message to the target player (specified in Device Serial# field)

<img width="536" alt="image" src="https://github.com/RomeoLB/send-udp-bsn-cloud/assets/136584791/85814146-a15b-4155-8a04-54e912fdca44">


