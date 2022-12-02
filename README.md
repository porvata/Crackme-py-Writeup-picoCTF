# Crackme-py-Writeup-picoCTF

**DESCRIPTION:**

crackme.py (File included in repository)

**SOLUTION:**

1. Open the Python program in a text editor
    >We can see that it contains two functions "def decode_secret(secret)" and def "choose_greatest()"
        
2. Only the choose_greatest() fucntion is called in the crackme.py program, but this function has nothing to do with finding our flag

3. I decided to separate the important function into it's own Python program for cleanliness sake

4. The secret password is given to us as:
    >A:4@r%uL`M-^M0c0AbcM-MFE067d3eh2bN

5. We set the secret password to the variable
    >bezos_cc_secret
    
5. Finally, we need to run this password through the decode_secret(secret) function to get our flag

6. Call the function in your code like so:
    `decode_secret(bezos_cc_secret)`
    
Feel free to use my crackedit.py file for reference
