# Rainbow-Road-PIN-Entry
You can **demo** the headphone variant of this Password entry method [HERE](https://ananthar20.github.io/Rainbow-Road-PIN-Entry/)

The original version of this game may be published as a demo at a later time, but the code is available in the 3_color_demo branch of this repository.

This is an implementation of an original PIN entry method designed by a team at the Indian Institute of Science in Bangalore in 2024. It is intended as a way to input a 4 digit password so that an adversarial on-looker (someone snooping over your shoulder) would find it difficult to figure out your password just from watching your inputs. Additionally, in the linked demo above, if a user is wearing headphones, it will offer additional security while entering a PIN.

# Instructions for the Demo

Pick any 4 digits you'd like to be your hypothetical password (could be any 4 numbers between 0-9).

1. Press 'Start Game'
You will see a keypad with the digits 0-9.
You will also see a lookup table above with flashing values associated with each digit.

2. Listen to the voice prompt. This will indicate the *letter* to look for in the lookup table. Then look at the cell associated with your *first digit* in the look-up table. The letter from the voice prompt will be next to a number in this cell. Type that number instead of your first digit. 
3. After you type the encrypted first digit you will hear another voice prompt. Repeat the process with the second, third and fourth digit.

4. At the end, press 'Toggle PIN Visibility' to see the 4 digit PIN that you entered. Hopefully it matches the password you chose at the beginning. If it does not, you may have made a mistake in entering your PIN.

# Example Play-Through

Say you want to input the PIN '2376'

Press 'Start Game'. Then imagine the voice prompt says "A". Look at the cell in the lookup table corresponding to your first digit (which is '2') and see the number next to "A". Type this number as your first digit.

Then imagine the voice prompt says "C". Look at the cell in the lookup table corresponding to your second digit (which is '3') and see the number next to "C". Type this number as your second digit

Then imagine the voice prompt says "C" again. Look at the cell in the lookup table corresponding to your third digit (which is '7') and see the number next to "C". Type this number as your third digit.

Lastly imagine the voice prompt says "B". Look at the cell in the lookup table corresponding to your fourth digit (which is '6') and see the number next to "B". Type this number as your fourth and last digit. Then press enter. 

Press 'Toggle PIN Visibility' at the end to see if you entered your password correctly.

# Motivation behind Trapdoor Games

For fun, ask a friend to watch you input a password (on your phone or computer). Explain the rules to them, and see
if they can guess your 'password' by watching you input your digits. Make sure they have a clear view of your screen.

This type of PIN Entry method has potential applications for phone-entered passwords, ATM Machines, or Point-of-Sale devices where you may have somebody looking over your shoulder to try to see private/sensitive passwords.

