# Xenya

Xenya is a public free and open-source tool for Discord with lots of shit functions (useful and useless).
I released it because no one will buy it and every Discord bug and exploit need to be exposed to the public.

# Is Xenya a Token Grabber?

No, Xenya is a free and open source tool for Discord, this will be ridicolous to do. Somebody thought that Xenya is a grabber because of a file present in the "Resources" folder called "lol.exe". Lol.exe is an executable file that is used to make the executable token grabber in Xenya: it is a stub file, when you create the executable token grabber it prepend to this file the encrypted webhook with the various option that you put on the token grabber. If you try to execute this file in the "Resources" folder, the token will be not sent to nobody because the stub file can not correctly read its own content. Also, the file is obfuscated with a little (not heavy) obfuscation so it will be not easily decompiled by everybody (can be deobfuscated surely). So, what it does is reading its own content, sending the content (IP, token and tracking) to the specified webhook (if valid).
