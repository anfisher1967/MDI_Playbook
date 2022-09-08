# MDI_Playbook

Do NOT run this from a Microsoft machine or any machine that directly connects to Microsoft. It’s meant to be run in a test environment only.

Download the file from my github and rename it with a .bat extension.

Run it from an elevated cmd prompt.

This isn’t a real attack so I’m not trying to hide anything so you may get pop ups or other warnings.

I've added variables at the beginning so add the FQDN of your domain controller and the name of your PC in the declare variables section.

The cleanup doesn't work if the script errors out so I added a separate download named cleanup.txt that you can run if the clean up didn't work. Just rename it with a .bat extension.
