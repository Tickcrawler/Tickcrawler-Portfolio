**PortSwigger Web Security Academy: Authentication**
**Defenition:** The difference between authorization and authentication? Authentication is verifying who you claim to be. Authorization is verifying wheather a user is allowed to do something. Example, authentication is If I log in as Carlos123 I will be have to prove that im Carlos123. Authorization is when Carlos123 is authenticated the permision of that user has authorization to specifit things. Like having authorization to delete a user.

**Brute-Force Attack:** A brute-force attack is when an attacker uses a system of trial and errors to guess valid user credentials. These attacks typically are automated using wordlists of usernames and passwds. With dedicaited tools it potentially enables an attacker to make a vast number of attacks at high speed. Brute-forcing is not always just a case of making completely random guesses at usernames and passwords. By also using basic logic or publicly available knowledge, attackers can fine-tune brute-force attacks to make much more educated guesses.

**Brute Force Username:** Its easy to guess usernames if they conform to a recognizable pattern. Emails usually include a `usersname` in the email like `firstname.lastname@companyname.com`. Some times a `username` could also be easy and predictable like admin or administrator. When doing recon check if the user names is on the web site or check the URL to see if it disclose the email of an admin or IT support.

**Brute Force Passwd:**  `Passwds` can similarly be brute-forced, with the difficulty varying based on the strength of the `passwds`. Many websites adopt some form of `passwd` policy, which forces users to create high-entropy `passwds` that are, theoretically at least, harder to crack using brute-force alone. This typically involves enforcing `passwds` with:

 - A minimum number of characters
 - A mixture of lower and uppercase letters
 - At least one special character

**Username enumeration:** `Username` enumeration is when an attacker is able to observe changes in the website's behavior in order to identify whether a given username is valid. `Username` enumeration occurs on the log in page like when putting the correct `username` but wrong `passwd` or registration forms when you enter a `username` thats already taken.

**THE LAB:** Yes yes I know im not clearing these labs quick enough....but come on im a self learning person with zero EXP. But I did clear this one...with help of course because I didnt know how to use intruder so I googled it. So I had to use intruder to find the `username` and `passwd`. I learned that if everything is `200` for `username` you look at the length and the odd one out is your hit. For the `passwd` I learned that you can look at the length and the code it gives. So if the code is giving `200` you look for `302` and thats your hit and for length its the same as the `username`. Maybe I can use this tool more often some how in a ethical way of course.

**Bypassing Two-Factor Authentication:** 
