# Welcome to Hack Too Learn! ;)

<p> 
Help with getting started, been showed where to click, or what command to type in. It can be scary as an absolute beginner, so we are here to point out some of the basics to get you on your path. No harm in following along or even copying & pasting to get things moving forward. 
</p>

<br>

# Intro to Offensive Security ~ (TryHackMe)

<br>

### Commands / steps

- click green Start button
- read the task contents for Task 1
- open up terminal
- type the following command in terminal:
- `gobuster -u http://fakebank.com -w wordlist.txt dir`
- see 2 x directories found by gobuster
- /images & /bank-transfer
- go to the browser & tack the directories found onto the end to see what appears
- /images rerurns a 404 not found
- /bank-transfer returns an admin portal to transfer money / funds
- transfer from *2276*
- to account *8881*
- amount of *$2000*
- click send money
- should see -- transfer successful
- return to fakebank.com homepage -- delete /bank-transfer -- hit enter
- There is the _FLAG!_


# *Congratualtions*



