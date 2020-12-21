--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

App Name = BookCub
Package Name = com.bookcub
VersionCode = 2
VersionName = "1.0.1"

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

Keystore  name : bookcub
Keystore Password : bookcub
Keystore Alias : bookcub


Key hash and SH1 commands for release :

KeyHash : 
keytool -exportcert -alias bookcub -keystore /Users/apple/Movies/bookcub.jks | openssl sha1 -binary | openssl base64
Key Hashes: ND0CmRH6pcH0AefaCJdn+lEtkPk=


SHA1 
keytool -list -v -keystore /Users/apple/Movies/bookcub.jks -alias bookcub
SHA1 key: 34:3d:02:99:11:fa:a5:c1:f4:01:e7:da:08:97:67:fa:51:2d:90:f9

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
Firebase Account:
Email: bookcubindia@gmail.com
Pwd: Book_cub_1710

Firebase server key : AAAACAWVdrY:APA91bGPAmZA3JnPtvMSw1JiQN_C02NRhLFHKS5UZ0osw8m6L-LlyiiWy-dAtHwQEkW88MCotkP4mZvdYk0oOcgIbhZKO4GUVha4kzW28IfajYLE-DykeHb0kq3yot7ftM9teLx6gWm_

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
FaceBook Account:
Email: prernasonavane@gmail.com
Pwd: Oct@2020

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
App signing key certificate

MD5 certificate fingerprint :  6A:F4:13:13:1C:23:BB:7E:71:79:62:C1:87:AE:E3:A2
SHA-1 certificate fingerprint : 5F:79:D9:01:56:3D:2D:60:1D:56:24:24:BD:BD:D7:22:10:10:AC:79
SHA-256 certificate fingerprint : FF:C2:60:F9:21:3A:C9:B3:3A:EC:D2:C0:0E:94:F4:9A:BA:E6:34:14:1E:28:DD:80:35:DD:D3:53:2E:16:F2:44

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
Upload key certificate

MD5 certificate fingerprint : 40:98:F6:D0:1C:F0:21:7C:34:7A:37:9F:07:8D:D2:04
SHA-1 certificate fingerprint : 34:3D:02:99:11:FA:A5:C1:F4:01:E7:DA:08:97:67:FA:51:2D:90:F9
SHA-256 certificate fingerprint : 36:85:D1:5B:D7:3C:C5:8D:EA:A9:D1:AC:63:62:D2:F9:25:2D:36:FD:85:11:46:93:E1:5B:84:7D:07:1F:84:03


--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

For future reference, if you already have your app on Play Store you can this:

1. Go to Release Management

2. select App Signing in Release Management

3. You can see SHA1 key in hex format App signing certificate.

4. Copy the SHA1 in hex format and convert it in to base64 format, you can use this link http://tomeko.net/online_tools/hex_to_base64.php to do that without the SHA1:  part of the hex.

5. Go to Facebook developer console and add the key(after convert to base 64) in the settings —> basic –> key hashes.
