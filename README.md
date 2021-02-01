# Online_Voting_Using_One_Time_Pads
Online Voting Using One Time Pads

# Clarifying the Question: Is secure online voting possible?

First let's try to focus on what exactly this question is asking:
1. Not: Can online voting be absolutely effortless and perfectly ecstatic as an experience? 
2. Not: Can a person outside of the voting process be provably safe from any voter intimidation, coercion, brainwashing, threats, harassment, discouragement, etc? 
3. Not: Can a person make no mistakes while filling out their ballot? (Though some additional safeguards from this have been successfully used in some states.) 

Those are important questions but they are not the same as the question of a secure online voting system. 

# Proposed Steps for Secure Online Voting

Rule 1: If there is a problem it must be solved in-person by the voter with proof of identification, in the same way that the person would register to vote and or vote.  

Step 1: Before the election ends: A person, e.g. in person, with ID, goes to the voting office to register for the One Time Pad Vote Over Network (online voting) process. 

Step 2: During the in-person one-time-pad-voter-registration: two physical copies (e.g QR codes) of two one time pads are created, one set of the pads are stored (offline) by the gov., one is kept by the person themselves (physically, off line)
the software will print and check the one-time pads, but will erase thoroughly from memory (e.g. physically overwrite) any record of what the now-printed one-time-pads were.

Step 3: During the election period, a one-time-pad 'encoded' ballot is sent by whatever agreed upon method (website, email, text, snapchat, S3, etc) in the form of another QR code
part of this process is an at-the-time randomized process of frame-shifting the ballot so that where exactly on the page each person's vote-choices appears is random. 

Step 4: the voter then off-line(enforced by software) 'decrypts' the ballot and physically prints it using one piece of software

step 5: the voter then, off-line(enforced by software), fills out the ballot and off-line scans (e.g. by taking a picture) the filled-out ballot 

step 6: the voter off-line(enforced by software), inspects and validates that their digital ballot is correct

step 7: the voter off-line(enforced by software) uses the one-time-pad to 'encrypt' the ballot, producing a new QR code.

~ step: an optional intermediate step here is to have a 3rd set of offline-only software that will check the ballot before and or after it is filled out by the voter, such that it can check for the "overvoting" (voting for both candidates) and "undervoting" (voting for neither candidate) issues as a safeguard and that perhaps Navada has used successfully. 

step 8: on-line: the voter sends (by whatever agreed upon method) that new QR code to the gov. office

step 9: the gov. office and prints the QR code for the 'encrypted' filled out ballot and deletes the digital record

step 10: offline, the gov. office prints the QR code for the 'encrypted' filled out ballot.

step 11: offline the gov. office decrypts the QR code for the 'encrypted' filled out ballot using the printed QR code for the one-time pad

step 12: The printed ballot is counted with the other paper ballots of various kinds during the normal election ballot count process.


# identifying the risks, 
especially from non-local agents such as foreign states / groups:

1. a bad-agent will intercept either one-time-pads
- the agent would need to be physically in the room during the QR code creation, to break into the gov. office, or to physically steam from the person, without anyone knowing the QR codes were stolen. 
- the one-time-pads are never stored digitally anywhere, but are only physically printed by an off-line computer.
	- if the voter loses the QR code the person should cancel the process


2. a bad-agent will send the voter a fake ballot
- additional step: there can be additional checks such as a passphrase chosen by the person which could not be electronically surveilled from any computer (e.g. written in pen on the QR pad) 


3. a bad-agent will send the gov. a fake filled-in ballot
	- the agent would need to have both stolen QR codes and a stolen ballot that was sent to the voter.
	- if the voter loses the QR code the person should cancel the process
	

4. a bad-agent will record a fake record of the vote from the ballot
	- while a possible risk, this process is the same as for any paper ballot


# Description Notes:
For maximum security, while the 'voting' is able to be done remotely, online, over a network, the entire process is not on-line, but rather involves physical printed materials and off-line computers. e.g. if there is no digital record to steal, a non-existent record cannot be stolen. This particular solution is not a perfect-for-all-cases solution. E.g. This will not be easy to use for persons who cannot ever travel themselves to a gov. office or polling place. 
