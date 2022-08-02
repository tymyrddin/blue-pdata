# Secure file uploads from users

If your site allows users to upload a file: A file upload vulnerability can have a crucial impact because code can be executed on the server or the client. The uploaded file can be misused to exploit other vulnerable components of an application or trigger vulnerabilities in defective libraries while the file exists on the same machine. Uploaded files that threat actors can use could contain Command and control (C&C) server information, directions for harassment or violence or steganographic materials.

Only allow extensions that are required for the application's functionality. Check that it:
* Verifies the file type without trusting the Content-Type header, which can be spoofed.
* Enforces file name length and size limit, and changes the file name while hosting it on a server.
* If files are publicly available, check that it uses handler mapping to map ID to filename within the application.
* If possible, it runs files through a sandbox or antivirus.

