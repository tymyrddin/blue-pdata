# Introduction

* End-to-end encryption (E2EE) is a defence against MitM attacks.
* Most E2EE systems are secure against only the weakest passive adversaries, breakable not by cryptanalysis of underlying cryptographic algorithms but by flawed system designs and security assumptions. Unencrypted metadata and access patterns make these systems susceptible to inference attacks. And recently made laws seem to have been made to prepare the way for agencies to legitimately gather encrypted data via backdoors and ghost protocols.
* The [Infosec goals](../Infosec-goals.md) of E2EE are:
  * Confidentiality: Only  the  two  participants  of  pair-wise  messaging  or  legitimate group member of group messaging can see the message plaintext.
  * Integrity: If a message is received and successfully validated, then it was indeed sent by the given sender,  i.e., other users cannot plant messages into it, and they can not modify it.
* [Use a secure messaging service](messaging-apps.md).
