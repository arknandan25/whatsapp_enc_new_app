# whatsapp_enc_new_app


1. Creating a public server:


---
2. Approach is to create a localhost Ejabberd:
* https://docs.ejabberd.im/admin/installation/#install-on-macos
* download page: https://www.process-one.net/en/ejabberd/archive/
* https://www.process-one.net/blog/how-to-move-the-office-to-real-time-im-on-ejabberd/
* https://docs.ejabberd.im/admin/configuration/
* Youtube video for ejabberd server: https://www.youtube.com/watch?v=hscthU8Cu3s
* Installation: https://www.process-one.net/blog/ejabberd-on-macos-with-homebrew-package-manager/
* Lite-setup: https://docs.ejabberd.im/developer/install-osx/

```
/usr/local/etc/ejabberd/ejabberd.yml
/usr/local/etc/ejabberd/ejabberdctl.cfg
```

---

3. Openfire xmpp server:
* https://www.programmersought.com/article/6185132360/

---
Trello board for project:
```
https://trello.com/b/ZFv7VQih/whatsapp-fyp
```
Firebase based e2ee apps:
* Abdriod app youtube tutorial AES E2EE- https://www.youtube.com/watch?v=bVXT_AkHIEQ
* WhatsApp CLone Youtube tutorial(free code camp)- https://www.youtube.com/watch?v=988UZFB0heA&t=5965s
* WhatsApp Clone + All the features in the world: https://www.youtube.com/watch?v=B2mGZtsh-qc&list=PLxefhmF0pcPmtdoud8f64EpgapkclCllj&index=60

---
WhatsApp Clone + All the features in the world: https://www.youtube.com/watch?v=B2mGZtsh-
* vid 17- add a grp to firebase
* vid 18- add grp and view on listview i.e retireve from firebase db all grp names
* vid 19- chat components of each grp
* vid 20- send msg to grp in firebase
* vid 21- tutorial of how manually entered users ->all viewing all the groups on firebase and send a messge and that msg is shown on their screens
* vid 22- scroll view and auto scroll to bottom i.e the latest group chat
* vid 29, 30- create layout for find/add friends circular profile pic + user name using recycler adapter
* vid 49 - custom chat layout https://www.youtube.com/watch?v=s01G12JAOFw&list=PLxefhmF0pcPmtdoud8f64EpgapkclCllj&index=49

---
SQLite Based login/register:
* Login/Register with SQLite- https://www.youtube.com/watch?v=8obgNNlj3Eo

E2EE:
* e2ee paper: https://www.researchgate.net/publication/342621891_Improving_Non-Experts%27_Understanding_of_End-to-End_Encryption_An_Exploratory_Study
* https://protonmail.com/blog/what-is-end-to-end-encryption/
* https://www.kaspersky.com/blog/what-is-end-to-end-encryption/37011/
* https://teamdrive.com/en/overview-of-end-to-end-encryption/
* forbes on e2e: https://www.forbes.com/sites/forbestechcouncil/2021/03/30/fully-secure-messaging-needs-more-than-end-to-end-encryption/?sh=6c4dd5c56158
* good article, good content: https://hackernoon.com/secure-instant-messaging-platform-the-importance-of-security-algorithm-in-chat-apps-dy3p36b7
* --------
* Generic encryption in java/android youtube tutorial(3 part series)- https://www.youtube.com/watch?v=M22O3q0-0WE&list=PL2cPYwzGtGnt4guyxpk6EYliDyhHvDgJ7
* Curve-25519-mobile-ecdh github- https://github.com/duerrfk/ecdh-curve25519-mobile
* Generic cryptogaphy java android(technolearning) youtube series - https://www.youtube.com/watch?v=g5q3EnBdfw8&list=PL2cPYwzGtGnsnQE_mfi7qWKHlUCEyCTYd

* Article on AES+GCM: https://proandroiddev.com/security-best-practices-symmetric-encryption-with-aes-in-java-7616beaaade9
* Article on AES-CBC+HMCA in android: https://proandroiddev.com/security-best-practices-symmetric-encryption-with-aes-in-java-and-android-part-2-b3b80e99ad36
* ENC Android: https://medium.com/@lucideus/secure-derivation-of-keys-in-android-pbkdf2-lucideus-371452cc29f7
* ECDH on android: https://nelenkov.blogspot.com/2011/12/using-ecdh-on-android.html
* Simple AES symmetric encryption on android: https://www.amarinfotech.com/how-to-do-aes-256-encryption-decryption-in-android.html
* AES Keys: https://kavaliro.com/wp-content/uploads/2014/03/AES.pdf
* Image Encryption : https://www.youtube.com/watch?v=kI2gfl4izAs
* File Encryption: https://www.coderzheaven.com/2013/03/19/encrypt-decrypt-file-aes-algorithm-android/
* More Material for paper:
* ECDH:https://asecuritysite.com/encryption/ecdh
* https://cryptobook.nakov.com/asymmetric-key-ciphers/ecdh-key-exchange
* MAC and Message Intergrity:https://www.pcmag.com/encyclopedia/term/message-integrity#:~:text=The%20validity%20of%20a%20transmitted,that%20is%20difficult%20to%20reverse.
* https://security.stackexchange.com/questions/14858/mac-vs-encryption
* https://security.stackexchange.com/questions/20129/how-and-when-do-i-use-hmac
* https://en.wikipedia.org/wiki/HMAC#Design_principles
* https://tools.ietf.org/html/rfc2104
* 

ECDH and curver 25519 theory:
* http://koclab.cs.ucsb.edu/teaching/ecc/project/2015Projects/Haakegaard+Lang.pdf
* https://billatnapier.medium.com/little-protects-you-on-line-like-ecdh-lets-go-create-it-a14188eabded
* https://medium.com/swlh/understanding-ec-diffie-hellman-9c07be338d4a
* https://www.cryptosys.net/pki/manpki/pki_eccsafecurves.html
* https://cr.yp.to/ecdh/curve25519-20060209.pdf
* https://www.intechopen.com/books/theorizing-stem-education-in-the-21st-century/implementation-of-elliptic-curve25519-in-cryptography
* https://en.wikipedia.org/wiki/Curve25519
* https://cryptobook.nakov.com/asymmetric-key-ciphers/ecdh-key-exchange#:~:text=The%20ECDH%20(Elliptic%20Curve%20Diffie,secret%20over%20an%20insecure%20channel.
* 

Forward Secrecy:
* RATCHET: https://nfil.dev/coding/encryption/python/double-ratchet-example/
* https://avinetworks.com/glossary/perfect-forward-secrecy/
* https://www.wired.com/2016/11/what-is-perfect-forward-secrecy/

Certificate and Android:
* https://support.google.com/pixelphone/answer/2844832?hl=en

AES,MAC, cryptography basics:
* https://russell.ballestrini.net/what-are-the-differences-between-message-confidentiality-and-message-integrity/#:~:text=integrity%20without%20confidentiality%3F-,message%20confidentiality,between%20trusted%20parties%20is%20confidential.
* https://crypto.stackexchange.com/questions/44967/properties-of-a-single-message-protocol-using-aes
* https://searchsecurity.techtarget.com/definition/Advanced-Encryption-Standard
* https://datalocker.com/what-is-the-difference-between-ecb-mode-versus-cbc-mode-aes-encryption/#:~:text=The%20Advanced%20Encryption%20Standard%20(AES,first%20generation%20of%20the%20AES.&text=CBC%20(Cipher%20Blocker%20Chaining)%20is,form%20of%20block%20cipher%20encryption.
* security level: https://en.wikipedia.org/wiki/Security_level#:~:text=In%20cryptography%2C%20security%20level%20is,cipher%20or%20hash%20function%20%E2%80%94%20achieves.
* key size:https://en.wikipedia.org/wiki/Key_size
 

Group Chat E2EE:
* https://security.stackexchange.com/questions/204295/end-to-end-encrypted-group-chat-considerations
* https://security.stackexchange.com/questions/119633/how-does-whatsapps-new-group-chat-protocol-work-and-what-security-properties-do
* https://www.reddit.com/r/cryptography/comments/j75ub8/how_group_chats_can_be_end_to_end_encrypted/
* https://stackoverflow.com/questions/48249900/end-to-end-encryption-for-a-chat-application
* https://blog.trailofbits.com/2019/08/06/better-encrypted-group-chat/
* [IMP]:https://ieeexplore-ieee-org.elib.tcd.ie/stamp/stamp.jsp?tp=&arnumber=8406614
* Paper on WA, Signal,Threema vulnerabilities: https://eprint.iacr.org/2017/713.pdf


Blockchain with certs:
* https://viquetur.medium.com/storing-and-verifying-documents-using-blockchain-technology-ba697921c4af#:~:text=Certificates%20are%20placed%20on%20a,form%20that%20cannot%20be%20altered.
* https://www.cyberbahnit.com/wp-content/uploads/2018/01/POC_for_Educational_Certificates_Cyberbahn.pdf
* https://lup.lub.lu.se/luur/download?func=downloadFile&recordOId=8969448&fileOId=8969449
* [IMP]|:http://www.tara.tcd.ie/bitstream/handle/2262/92581/X509Cloud_FinalSubmission.pdf;jsessionid=D148D6D40E83383E3E35B65004F10924?sequence=1

PKI
* X509 CLoud: http://www.tara.tcd.ie/bitstream/handle/2262/92581/X509Cloud_FinalSubmission.pdf;jsessionid=D148D6D40E83383E3E35B65004F10924?sequence=1
* https://medium.com/remme/why-next-generation-pki-will-reside-on-the-blockchain-44befcd2af3a
* https://isrdc.iitb.ac.in/blockchain/workshops/2017-iitb/papers/paper-11%20-%20Decentralized%20PKI%20in%20blockchain%20and%20Smart%20contract.pdf




Material for writing the report
* Latex:https://www.overleaf.com/learn/latex/Questions/How_do_I_adjust_the_font_size%3F
* https://www.overleaf.com/learn/latex/Paragraph_formatting#Starting_a_new_paragraph
* http://kb.mit.edu/confluence/pages/viewpage.action?pageId=3907092
* [IMP]: https://en.wikibooks.org/wiki/LaTeX/Fonts
* https://tex.stackexchange.com/questions/335990/is-there-a-command-to-make-first-letter-upper-case
* report guidelines: https://projects.scss.tcd.ie/information-for-students/report-and-dissertation-guidelines/

Biography:
*https://newcollege.asu.edu/sites/default/files/2017-2018_sample_student_bio_form.pdf


Android Technicalities:
* https://developer.android.com/studio/build/multidex
* https://stackoverflow.com/questions/60310873/execution-failed-for-task-appmergedexdebug-firestore-flutter
* https://stackoverflow.com/questions/6264185/image-button-is-not-displayed-in-linear-layout
* https://stackoverflow.com/questions/4123630/android-align-button-to-bottom-right-of-screen-using-framelayout
* https://stackoverflow.com/questions/29924145/how-to-sign-the-certificates-with-elliptic-curve-private-keys-and-ecdsa-algorith
* https://stackoverflow.com/questions/40572436/android-java-lang-noclassdeffounderror-org-bouncycastle-crypto-engines-aesengin
* https://stackoverflow.com/questions/42630190/error-including-bouncycastle-provider
* https://stackoverflow.com/questions/8454463/what-are-the-different-types-of-instances-for-keyfactory
* https://www.semicolonworld.com/question/49186/certificate-enrollment-process
* https://medium.com/@bouhady/self-sign-certificate-creation-using-spongy-castle-for-android-app-61f1545dd63
* Time in nano seconds java: https://mkyong.com/java/java-how-to-convert-system-nanotime-to-seconds/



---
## Non Technical Links
* Check common word errors: https://brians.wsu.edu/common-errors/
* Using latex for report writing: overleaf.com

