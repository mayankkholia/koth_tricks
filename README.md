# koth_tricks


#Throw random gibbresh at others terminal
#first check your tty number using ps command
cat /dev/urandom >/dev/pts/<num> &


#Check suid binary for privelage escalation
find / -user root -perm /4000

#Check cmd that do not require sudo <for privelage escalation>
sudo -l
