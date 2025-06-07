📁 FileWithPin
A tiny .bat file that puts a PIN on your file — just for fun & light protection

💬 What's this?
I was messing around with some files and passwords after seeing a TikTok about security (you know the kind: “update your passwords or get hacked!”). It made me think — when was the last time I updated my own?

So after my exams, I sat down for a few hours and changed every single password. Then I backed up my new passwords, backup codes, and security questions in a single .txt file.

But then I thought...
“Wait, this is way too easy to open. Anyone who touches my computer could just double-click it.”

🔐 So I made this:
A super simple batch file that asks for a PIN before opening your file.
It’s not real security — any tech-savvy person could bypass it by editing the batch file — but it’s better than nothing, and hey, I wanted to build it myself instead of downloading something like BitLocker or 7-Zip.

🛠 How it works
You set a PIN in the batch file

When someone tries to open the protected file, they have to enter the correct PIN

If it’s wrong, it just says “Incorrect PIN”

If it’s right, it opens your file (in Notepad or whatever you want)

👻 Bonus: Hide your file
If you want to hide your file from a quick search or prying eyes, run this command in Command Prompt or PowerShell:

cmd
Copy
Edit
attrib +h "C:\Path\To\Your\SensitiveFile.txt"
That just hides it in File Explorer — it won’t be listed unless you turn on “show hidden files.”

⚠️ Disclaimers
This won't stop hackers, nerds, or even your little cousin who knows how to right-click → “Edit”.

It’s more like a digital "keep out" sign, not a vault.

If you want real protection: look into BitLocker, VeraCrypt, or password-protected archives with 7-Zip.

✅ Why I Did This
Honestly? For fun. I’ve been learning about cybersecurity at school and in my free time, and this was a neat little side project. It reminded me that basic protections are easy to set up — and that any improvement is better than none.

💡 Try it out
Feel free to clone this and modify it to suit your needs. Add features, make it harder to bypass, or just use it to play around with scripting.

This chat is chatgpt made since my original text was really boring and had shit grammar but u get the point
