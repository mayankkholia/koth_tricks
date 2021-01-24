# koth_tricks


Throw random gibbresh at others terminal</br>
first check your tty number using ps command
<code>
cat /dev/urandom >/dev/pts/<num> &
</code>

Check suid binary for privelage escalation
<code>
find / -user root -perm /4000
</code>
Check cmd that do not require sudo <for privelage escalation>
<code>
sudo -l
</code>
