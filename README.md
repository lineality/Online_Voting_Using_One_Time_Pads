# Online_Voting_Using_One_Time_Pads
Online Voting Using One Time Pads

# Clarifying the Question: Is secure online voting possible?

To focus on what goals to focus on and what questions to ask, below is a list of other questions we are not attempting to answer or resolve with this project. This clarification should help so that questions we are not asking do not get confused and mixed together with questions that we are asking:
1. Not: Can online voting be absolutely effortless and perfectly ecstatic as an experience? 
2. Not: Can a person outside of the voting process be provably safe from any voter intimidation, coercion, brainwashing, threats, harassment, discouragement, etc? 
3. Not: Can a person make no mistakes while filling out their ballot? (Though some additional safeguards from this have been successfully used in some states.) 
4. Not: Can the physical offices of staff be absolutely impenetrable to a physical breakin or loss of records due to causes such as fires. 

Questions we are focusing on include the following: 
1. Is secure over-a-network (online) voting possible? 
2. Is it possible for a voter to submit a vote securely over a network (online)?
3. Is it possible for a voter to securely receive a ballot from the voting office over a network (online)? 
4. Is it possible for the voting office to securely receive a completed ballot from the voter over a network (online)?


# Proposed Steps for Secure Online Voting

Rule 1: If there is a problem it must be solved in-person by the voter with proof of identification, in the same way that the person would register to vote and or cast their vote.  

Step 1: Before the election ends: A person, e.g. in person, with ID, goes to the voting office to register for the One Time Pad Vote Over Network (online voting) process. 

Step 2: During the in-person one-time-pad-voter-registration: two physical copies (e.g QR codes) of two one-time-pads are created, one set of the pads are stored (offline) by the gov., one is kept by the person themselves (physically, off line)
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


# Identifying Risks 
Especially from non-local agents such as foreign states / groups:

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
This is a proposed process for reasonably secure 'online (over a network) voting.' Part of secure design is that the entire process is not on-line. Rather, physical printed materials and off-line computers are used to reduce the 'online attack surface.' You can feasibly steal or tamper with a file in a network-connected computer from a remote location, but you cannot feasibly tamper with or steal documents in a filing cabinet from a computer connected to the internet. This particular solution is not a perfect-for-all-cases solution. E.g. This will not be easy to use for persons who cannot ever travel themselves to a gov. office or polling place. 

# Implementation Notes:
These are recommendations for a reasonably secure online voting system that should not be significantly more cumbersome than a physical paper voting system. 
To make accessibility easier, it is conceivable that some local voting systems would prefer to simplify some of the security step to allow broader accessibility:
- voters who have no access to a printer
- voters who cannot physically travel (e.g. elderly persons in retirement home or hospital), perhaps allowing a proxy to carry documents for that person. 

Additional steps could also be taken to increase the security further. 
For example: 

1. to reduce the possibility that local staff will accidentally connect to the internet or run the software on insecure or already compromised hardware, it should be possible to create a cost effective system where staff could run a custom made operating system (custom BSD or Linux or FreeDOS, etc) that lacks the ability to use the internet. It may also be possible to use cost effective hardware such as a $40 raspberrypi computer. 

2. Put safeguards into the software to at least try to prevent using the same one-time-pad more than once. 

Challenges:

One possible area that may cause issues is if the office or voter is 'unable' to scan or take a clear photo of the document.
It is also possible that OCR (optical character recognition) may not be good enough to read the ballot, but given the use of OCR to read more obscurely printed checks etc., this is probably not a terminal obstacle. 
namely, the task is not really subtle character recognition but binary check-box selection. An exception to this may be write-in ballots which do occur, where some other system may be needed.
Though even here, OCR and checking to see that the OCR is correct may be sufficient. 

