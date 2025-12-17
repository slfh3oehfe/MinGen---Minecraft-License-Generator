MinGen is a program that leverages two highly vulnerable exploits: Gener7 and MCSploit.

Gener7 is an exploit discovered during the license key generation process. It works by generating a valid license key and transmitting it directly to the authentication server, bypassing standard validation checks.

MCSploit is a custom-built exploit that builds on Gener7, allowing full control over the generated key and enabling it to be exported for external use. By chaining these two exploits together, MinGen is able to reliably retrieve usable license keys.

The Gener7 exploit has existed unnoticed for years and has only recently been identified. However, due to MinGen being released publicly, it is unlikely that this vulnerability will remain unpatched for long.
