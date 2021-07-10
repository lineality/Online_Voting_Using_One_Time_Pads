# Online_Voting_Using_One_Time_Pads
Online Voting Using One Time Pads


# Clarifying Goals and Questions: 
- Main Goal: secure online voting
- Main Questions: 
#### 1. Is secure auditable online voting possible in principle?
#### 2. Is reliable online-vote-result-publishing possible in principle?
#### 3. Can election-processes and election-results-publishing be feasibly, sustainably, pragmatically, realistically, implemented given real world limitations on resources? 
#### 4. What are differences between ideal-maximum-security-systems and sufficiently-secure more-accessible or realistically-feasible systems?


To clarify goals and questions, below are two lists of questions. There is one list of questions that we are attempting to answer or resolve with this project, and there is another list of questions that we are NOT attempting to answer or resolve with this project. This clarification should help so that questions we are not asking do not get confused and mixed together with questions that we are asking.


## Questions we are focusing on include the following: 
1. Is secure over-a-network (online) voting possible? (Here 'secure' is defined as being 'as secure as a non-networked paper system.') 
2. Is it possible for a voter to securely receive a ballot from a voting office over a network (online)? 
3. Is it possible for a voter to submit a ballot securely over a network (online)?
4. Is it possible for a voting office to securely receive a completed ballot from the voter over a network (online)?

## Questions we are NOT the focus of this project include the following: 
1. Not: Can online voting be absolutely effortless and perfectly ecstatic as an experience? 
2. Not: Can a person outside of the voting process be provably safe from any voter intimidation, coercion, brainwashing, threats, harassment, discouragement, etc? 
3. Not: Can a person make no mistakes while filling out their ballot? (Though some additional safeguards from this have been successfully used in some states.) 
4. Not: Can the physical offices of staff be absolutely impenetrable to a physical breakin or loss of records due to causes such as fires. 
5. Not: Can hecklers and trolls be prevented from criticizing, slandering, and defaming, the election and election process when or where there is nothing legitimate to criticize?

## A debatably separate or peripherally related question may be:
1. Are there elements of the voting process that affect (encourage or discourage) participation in the voting process (from user interface to requirements for participation to schedules of participation)?

# Concept: Universal Procedures and Processes
The view taken here is that 'voting' is a science-like process. Voting is based on procedures, numbers, measurements, feedback, and data. Voting is not based on not-operationally-defined essences, reifications, fears, dramas, feelings, threats, wishes, trust, authorization, belief-ness, faith, tradition, habit, permission, labels, etc. A vote is like a physical piece of machined metal; A vote exists or does not exist with the measurable features that it has, and these measurable features are and must be measurable and confirm-able by anyone who measures it. Any group of people who carry out the math-science-data process of sound voting have performed voting in a way that can be audited and measured and published. No group of people can skip or shortcut required math-science-data processes without having skipped those required math-science-data processes. As with a surgeon washing their hands before surgery, "trust" is a term better used to mean that you trust the surgeon is following best practice, though even then probably it is best to simply verify without trust. But under no circumstances can 'trust' replace or permit the skipping of required processes for people or groups however much they demand and violently enforce their unfounded exemption from required best practice. In other words, if a person or group says "You MUST trust me, so I do NOT need to wash my hands before performing surgery on you or processing your vote in a best practice auditable way", you are by definition being subjected to violence, coercion, fraud, and classically defined tyranny.


# Proposed Steps for Secure Online Voting

Rule 1: If there is a problem it must be solved in-person by the voter with proof of identification, in the same way that the person would register to vote and/or cast their vote.  



Step 1: Before the election ends: A person, e.g. in person, with ID (identifiable as an eligible voter according to local rules), goes to the voting office to register for the Vote-Over-a-Network with One-Time-Pad (online voting) process. 

(Note: A choice is to allow registration for more than one election. This issue relates to the form of the submitted ballot, for example A. ballots that have been (or can have been) designed at the time of registration and B. standardized or truncated ballots containing just choices and not all the text of the ballot and C. whether whatever form of ballot is customized for each voter (e.g. with a custom-id, verifiable as going to and coming from that one voter) or whether the ballot is standardized (and verifiable as the standard ballot for that election or more standardized) )

Step 2: (During in-person registration) For a given single vote-ballot in a given single election there need to be four paper documents. which are two separate one-time-pads (or sets of a "pad," where a one-time-pad is two identical copies of one unique pad, with the two parties having one copy each of this unique pad. One pad is two identical paper documents, one for each party. Since there will be two "exchanges" (one where the blank-ballot is sent to the voter, and one where the filled-in-ballot is sent by the voter), there need to be two pads. (Alternately the system could be streamlined to one pad for submitting a standardized public ballot). 

The additional step of having two pads (one to send the voter a ballot) and not just one pad to inspect that ballot coming in has several advantages. 1. This allows the voter to verify that the ballot they are filling out comes from the voting office at which they registered, and that only someone with physical access to the physical one time pad created at their time and place of registration has sent them this ballot. This allow allows for a comparison by the voting office, likewise, of the ballot sent and the ballot received. The benchmark for success here is to be as secure as in-person all-paper voting. Just as it is possible (in theory) for a hostile group to physically take over a voting office and issue people fake ballots, or send people fake mail-in ballots in the mail, this one-time-pad-vote-by-network proposal does not prevent such physical attacks on physical paper voting infrastructure. It does however create an extra layer verifications that can be used during and after the vote takes place, which in theory could also be used to security-harden an all in-person all-paper voting process to make it more secure and auditable. (Note: Another additional or alternative method for some of these checks may be cryptographic signing (with optional multiple signatures) from trusted authorities (voting office, federal or state agency, universities, 3rd party certifiers, etc). 



During the in-person one-time-pad-voter-registration: Two physical copies (e.g QR codes) of two one-time-pads are created; one set of the two pads are stored (offline) by the local voting office, the other set (pair) of one time pads is kept by the voter themselves (physically, offline).
The software will print the one-time pads. The software will check (confirm, verify) the one-time pads. The software will erase thoroughly from memory (e.g. physically overwrite) any record of what the printed one-time-pads were.
(Note, if this process is done off-line using a dedicated machine, the risk (attack-surface) of someone being able to take (exfiltrate) the one-time-pads is reduced. Especially if the custom machine does not have enough memory to store any old pads but can only process and re-write-over one pad at a time.)

Step 3: (During in-person registration)  The election office, offline (enforced by software), uses the first 1:2 of the pair of printed QR codes to create an 'encrypted' version of the ballot for that one voter alone. 
Note: The ballot may be public, but it still needs to be verified. This illustrates the "verification" role sometimes lumped together with "security" and "encryption." The emphasis is not on 'hiding' the public ballot form, but on verifying that the specific ballot form that the voter is filling out is (identical to) the form that the local election office gave them.

Notes: It may be desirable to have a 'verified public ballot' as opposed to a 'private ballot' which in theory could vary from the standard public ballot (in a context of mapping out a potential attack space). 
In the case that a truncated-submitted ballot is used, some way may be desired to, e.g. make a short hash of the original ballot itself (e.g. to convert the ballot by OCR or perhaps have a QR code on the ballot (though a QR on a ballot received by a voter code could be forged, whereas a hash made by the voter of the whole ballot could not be). Perhaps having a multi-pass OCR hash of a public ballot submitted with the vote to indicate that the correct ballot was used (again, in the case of a truncated submission, for a full ballot return the whole ballot is there). 
It may be possible to have both a public verified 'open' ballot format and some unique element for the voter to check that the ballot comes from the voting office with the voters one-time-pad (such as a unique id code at the bottom or top of the ballot)

Step 4: During the election period (be that months, weeks, days, hours, etc.), a one-time-pad 'encoded' ballot is sent by whatever agreed upon method (website, email, SMS-text, mobile-app, S3, api-endpoint, etc.) in the form of another QR code.
Part of this process is an at-the-time randomized process of frame-shifting the ballot so that where exactly on the page each person's vote-choices appears is random. 

Step 5: Using one piece of software, the voter offline(enforced by software, possibly hardware) 'decrypts' the ballot and then physically prints the ballot.

(Note: There is a choice here between using a public standardized ballot or a per-person ballot (e.g. with a unique id number or such, to verify that the ballot-form sent was the same as that received, or a short-form vote which contains just the choices and not all the text of the ballot.)

Step 6: The voter off-line(enforced by software), inspects and validates that their digital scanned version of their not-yet-filled-out-ballot is the correct ballot-form intended for that election (e.g. not a tampered with or accidentally incorrect ballot). There are various and possibly multiple ways to check this (elaboration pending).

Step 7: The voter, off-line(using pen and paper), fills out the ballot (selecting their votes), (details here may be important in some way: filling in a circle, selecting an option number, multi-factor, non-over-under-voting checks, etc.)

Step 8: The voter, offline(enforced by software), scans (e.g. by taking a picture) the completed paper ballot, creating not a photo but a document or table of information (so that the one-time-pad can convert character by character). 

~ Step: an optional intermediate step here is to have a 3rd set of offline-only software that will check the ballot before and or after it is filled out by the voter, such that this additional set of software can check for the "overvoting" (voting for both candidates) and "undervoting" (voting for neither candidate) issues as a safeguard (against accidentally-incorrectly filled-out-and-submitted ballots) and that perhaps Nevada has used successfully. See: 
"Roll Off at the Top of the Ballot: Intentional Undervoting in American Presidential Elections"
December 2003 Politics & Policy 31(4):575 - 594
DOI:10.1111/j.1747-1346.2003.tb00163.x
Authors: Stephen Knack & Martha Kropf
University of North Carolina at Charlotte
https://www.researchgate.net/publication/227617394_Roll_Off_at_the_Top_of_the_Ballot_Intentional_Undervoting_in_American_Presidential_Elections 

Another 'multifactor' check may be to both indicate a choice and give some information about that choice, e.g. option 2 and the first letter of that candidate's last name. If these do not match, the voter should be alerted to check their ballot selections.
The voter, offline(enforced by software), scans (e.g. by taking a picture) the filled-out paper ballot. 

Step 9: The voter confirms that the information in their (the voter's)  electronic scanned ballot is the same as the paper version of their (the voter's) filled out ballot.

Step 10: The voter off-line(enforced by software) uses the one-time-pad to 'encrypt' the completed ballot, producing a new QR code. All digital files of the unencrypted ballot are removed and the memory physically over-written on the voter's device. The paper copy of the voter's ballot can be saved for evidence or destroyed for privacy based on the voter's choice.

Step 11: Online: The voter sends (by whatever agreed upon method (website, email, text, messaging software, shared storage (e.g. S3), api-endpoint, etc.)) the new QR code (containing the voter's encrypted filled-in and checked ballot) to the local election office.

Step 12: The local election office physically prints onto paper the QR code for the 'encrypted' filled out ballot, checks (compares) to confirm that the physical print is accurate, and (if printing is accurate) deletes the digital record and the memory is physically over-written.

Step 13: Offline, using a separate piece of software, the local election office"decrypts" the QR code for the 'encrypted' filled out ballot using second 2:2 of the pair of printed QR codes for the one-time pad, and physically prints on paper the voter's filled-in ballot. The voter's completed ballot is stored along with any completed paper ballot (e.g. mail-in ballots, or paper ballots delivered in person or filled out in person).

Step 14: The printed ballot is counted with the other paper ballots of various kinds during the normal election ballot count process.

Note: These steps are not intended to cover the publication of voting results though that is a relevant question. 

Note: Someone may wish to save a QR code as some form of record. There is no security need to carefully dispose of used QR codes after they is used because they are only used once; for example obtaining an old QR code (one time pad) will not in any possible way help to "decrypt" another future one-time-pad, one-time-pads are not similar to passwords in this way (leaking archived passwords would likely be considered some form of security breach, whereas accessing already disposed of QR codes is useless; literally a set of random  numbers that won't help anyone to do anything elicit, this is the point and function of a one-time-pad). 


# Identifying Risks from bad-actors or bad-agents
Especially from non-local agents such as foreign states / groups.
An 'agent' may be anything from a single person to a group to an AI-bot or software suit, malware, ransomware, thinktank, etc. (or something unclear and not simple to identify):

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

5. a bad-agent will act on the behalf of a participant without their participation


# Description Notes:
This is a proposed process for reasonably secure 'online (over a network) voting.' Part of secure design is that the entire process is not on-line. Rather, physical printed materials and off-line computers are used to reduce the 'online attack surface.' You can feasibly steal or tamper with a file in a network-connected computer from a remote location, but you cannot feasibly tamper with or steal documents in a filing cabinet from a computer connected to the internet. This particular solution is not a perfect-for-all-cases solution. E.g. This will not be easy to use for persons who cannot ever travel themselves to a gov. office or polling place. 

# Implementation Notes:
These are recommendations for a reasonably secure online voting system that should not be significantly more cumbersome than a physical paper voting system. 
To make accessibility easier, it is conceivable that some local voting systems would prefer to simplify some of the security step to allow broader accessibility:
- voters who have no access to a printer
- voters who cannot physically travel (e.g. elderly persons in retirement home or hospital), perhaps allowing a proxy to carry documents for that person. 

Additional steps could also be taken to increase the security further. 
For example: 

1. to reduce the possibility that local staff will accidentally connect to the internet or run the software on insecure or already compromised hardware, it should be possible to create a cost effective system where staff could run a custom made operating system (custom BSD or Linux or FreeDOS, etc) that lacks the ability to use the internet. It may also be possible to use cost effective hardware such as a $40 raspberry pi computer. 

2. Put safeguards into the software to at least try to prevent using the same one-time-pad more than once. 

## unique ballots:
At this time or at a later time (depending on choice, timing, etc. (e.g. if the ballot has been decided which is often not the case at the time of voter registration or if in terms of security level if the voter does not trust a physical breakin of the vote office and wants in advance a verifiable ballot) (offline) a printed copy of a unique ballot (e.g. containing if not the voter's name the equivalent of a sha256 hash of the unique ballot). Either a unique ballot or a unique ballot identification number will be used on both ends, by the voter to check that the ballot they receive is authentic and by the office that the ballot received completed and sent by the voters is authentic. 


## Challenges:

One possible area that may cause issues is if the office or voter is 'unable' to scan or take a clear photo of the document, in the same way that some people are 'unable' (which ranges from people having legitimate handicaps to people not bothering to try) to take a clear picture of their check for their bank (so a less secure non-printed option may be desired in some cases).
It is also possible that OCR (optical character recognition) may not be good enough to read the ballot, but given the use of OCR to read more obscurely printed checks etc., this is probably not a terminal obstacle. 
namely, the task is not really subtle character recognition but binary check-box selection. An exception to this may be write-in ballots which do occur, where some other system may be needed.
Though even here, OCR and having the vote double-check to see that the OCR is correct may be sufficient. 


# About One Time Pads
A one-time-pad is not the same as a re-use-able 'code' the 'encodes' a signal that can then also be 'decoded,' though the terminology can be a bit unclear in overlapping between the two. 

There is no pattern or system behind a one-time-code that can be outsmarted or 'cracked.' The only way to 'decode' a one time pad 'encrypted' message is with the pad, because it is a one-by-one, one-for-one, one character at a time, change of what the original text says.

One-time-pads codes are not as efficient and user friendly as 're-use-able' codes, but they are more secure and more simple. 

...

Q: Is there a lower-tech version with reasonable security for places with limited resources?

...

# A Low tech version of online voting for realistic implementation

1. For example. Some locations may not have: 
- a. printers ink and paper
- b. extra air-gapped computers
- c. a physical location to securely store paper files
But most locations should have basic mobile phones.

Write down the numbers and confirm with picture
- (no printers needed)
- Maybe separate air-gapped mobile device


# A revised thrifty-protocol for resource limited areas: (section under construction)

## Practical Voting
The goal here is more practical and less abstract. How can a local community organize and carry out a best practice audible vote and publish the results using widely available and accessible technology (such as mobile phones). 

Thrifty voting systems may make more use of available multi-factor authentication and less use of equipment-expensive methods (such as dedicated printing and scanning machines). 

Other methods such as chains-of-trust may be useful to harden thrifty online systems.


## Proposed Steps for Secure Online Voting (section under construction)

Rule 1: If there is a problem it must be solved in-person by the voter with proof of identification, in the same way that the person would register to vote and/or cast their vote.  

Step 1: Before the election ends: A person, e.g. in person, with ID (or a witness, however ID is confirmed in a given area), goes to the voting office to register for the One-Time-Pad Vote-Over-a-Network (online voting) process. 

Step 2: During the in-person one-time-pad-voter-registration: two physical copies (e.g QR codes) of two one-time-pads are created, one set of the two pads are stored (offline) by the local voting office, the other set (pair) of one time pads is kept by the voter themselves (physically, offline).
If there is no printer, a short-form ballot one time pad good for several ballots may be hand written and OCR-checked on a wallet-card sized card or paper.

A short-form or truncated ballot may contain, e.g., the number of the option-choice and perhaps a first/last letter in the candidates name (which could also serve as a check, similar to an empty choice check, if the name-letter does not agree with the number option). Two-factor-no-nul voting?
Note: Write-in may be an issue for the truncated ballot. 

The software will print the one-time pads, or hand written. The software will check the one-time pads (by OCR?). The software will erase thoroughly from memory (e.g. physically overwrite) any record of what the printed one-time-pads were.

Note: a log of already used one-time-pads to check against...?

Step 3: The election office, offline (enforced by software), uses the first 1:2 of the pair of "printed" (not on a screen) QR codes to create an 'encrypted' version of the ballot for that one voter alone. 
Note: The -ballot may be public, but it still needs to be verified. This illustrates the "verification" role sometimes lumped together with "security" and "encryption." The emphasis is not on 'hiding' the public ballot form, but on verifying that the specific ballot form that the voter is filling out is (identical to) the form that the local election office gave them.

Note: it may be desirable to have a 'verified public ballot' as opposed to a 'private ballot' which in theory could vary from the standard public ballot (in a context of mapping out a potential attack space). 

Step 4: During the election period (be that months, weeks, days, hours, etc.), a one-time-pad 'encoded' ballot is sent by whatever agreed upon method (website, email, text, snapchat, S3, api-endpoint, etc.) in the form of another QR code.
Part of this process is an at-the-time randomized process of frame-shifting the ballot so that where exactly on the page each person's vote-choices appears is random. 

Step 5: Using one piece of software, the voter offline(enforced by software, possibly hardware) 'decrypts' the ballot and then physically prints the ballot.

Step 6: The voter, off-line(using pen and paper), fills out the ballot (selecting their votes), 

Step 7: The voter, offline(enforced by software), scans (e.g. by taking a picture) the filled-out paper ballot. 

~ step: an optional intermediate step here is to have a 3rd set of offline-only software that will check the ballot before and or after it is filled out by the voter, such that this additional set of software can check for the "overvoting" (voting for both candidates) and "undervoting" (voting for neither candidate) issues as a safeguard (against accidentally-incorrectly filled-out-and-submitted ballots) and that perhaps Nevada has used successfully. See: 
"Roll Off at the Top of the Ballot: Intentional Undervoting in American Presidential Elections"
December 2003 Politics & Policy 31(4):575 - 594
DOI:10.1111/j.1747-1346.2003.tb00163.x
Authors: Stephen Knack & Martha Kropf
University of North Carolina at Charlotte
https://www.researchgate.net/publication/227617394_Roll_Off_at_the_Top_of_the_Ballot_Intentional_Undervoting_in_American_Presidential_Elections 

Step 8: The voter off-line(enforced by software) inspects and validates that their version of their ballot is correct and verified,  .

Step 9: The voter off-line(enforced by software) uses the one-time-pad to 'encrypt' the ballot, producing a new QR code. All digital files of the unencrypted ballot are removed and the memory physically over-written.

Step 10: Online: The voter sends (by whatever agreed upon method (website, email, text, snapchat, S3, api-endpoint, etc.)) the new QR code (containing their encrypted filled-in and checked ballot) to the local election office.

Step 11: The local election office physically prints onto paper the QR code for the 'encrypted' filled out ballot and deletes the digital record and the memory physically over-written.

Step 12: Offline, using a separate piece of software, the gov. office "decrypts" the QR code for the 'encrypted' filled out ballot using second 2:2 of the pair of printed QR codes for the one-time pad, and physically prints on paper the voter's filled-in ballot. The voter's completed ballot is stored along with any completed paper ballot (e.g. mail-in ballots, or paper ballots delivered in person or filled out in person).

Step 13: The printed ballot is counted with the other paper ballots of various kinds during the normal election ballot count process.

Note: It is not clear that saving the QR codes serves any function, nor is there any need to carefully dispose of a QR code after it is used. 


# (mitigation of insecure local voting headquarters)
2nd step of recording / publishing vote:
Uuid type random key-field
Fuzzy time stamp (month year?) unix epoch


2. Using a modified blockchain to store results:
- e.g. university trusted node anchors
- maybe full-chain so no retroactive?
- slower but more robust?
- smaller number of participants? (or pooled participants?)
- containing hash and voting record?





....

Possible Multi-factor Authentication Tools:
1. voice print
2. picture of hand (for fingerprints)
3. one time pad
4. specific device tracking
5. device gis location
7. ip / mac address details (vpn issues?)
6. separate confirmation login (to confirm vote record (device, voice, etc.) after it has been processed and recorded)
7. face-selfie (time GIS stamped picture of person casting vote)
8. video of person voting (more secure than static selfie?
or smaller-file 'encoding' (e.g. auto-encoder) of video of person voting


(plus)
1. public security log data/meta-data to be inspected by anyone about the system
 

Additional Questions:
1. What additional vote process transparency information should be included with vote results publishing? 
https://github.com/lineality/Auditable_Elections_Projects

...

## A Voting Rules And Procedures Statement

As part of an election, other publicly stated 'open' policy and procedure information is important in addition to the ballot itself.

- rules, policies, and procedures for how rules, policies, and procedures for voting are made, unmade, and changed
- time and data on opening and closing of poles for a given election
- times places methods for ways of voting allowed
- rules, policies, and procedures schedule for repeating elections
- specific schedule for repeating elections (e.g. this is a run-off vs. this election is held every 2 years)
- rules for calling elections
- Repeating or other type of election
- Place of election
- Government Structures and Levels
- Voting Office information (location, head?, contact, reporting?)
- Chain of Command within and above voting office
- rules, policies, and procedures contacting media or watchdogs about suspicious anything (emails, threats, voter intimidation, etc.)

- rules, policies, and procedures for eligibility
- rules, policies, and procedures for voter-registration
- rules, policies, and procedures for per way to vote
- rules, policies, and procedures for election audits (required audits, optional audits)
- rules, policies, and procedures for election-results-challenge
- rules, policies, and procedures for recount (automatic recounts, type of recount, etc.)
- ules, policies, and procedures for overruling-election-results e.g. by gov. branches, evidence requirements
- rules, policies, and procedures for chain of custody of election materials, equipment, etc., Provenance   
- rules, policies, and procedures for announcing and publishing results 
- rules, policies, and procedures for reporting information about the vote: procedures, voter enrollment and participation numbers, etc. 
- Should there be a 'log' of who makes changes to procedures and how?
- rules, policies, and procedures for election and ballot counting observation
- rules, policies, and procedures for exit polls (what collected, from whom, released when)
- rules, policies, and procedures for meetings and correspondence transparency around voloting infrastructure and offices and resources
- rules, policies, and procedures for foreign domestic local and internal interference with the attacks on the election process
- rules, policies, and procedures for voter registration
- rules, policies, and procedures for voter identification 
- For evaluation of best practice, performance, and ethics: standards, guidelines, benchmarks and audit materials
- rules, policies, and procedures for raw vote results (including ranked-choice etc.)
- rules, policies, and procedures for choosing vote calculation method
- rules, policies, and procedures for vote calculation method (e.g. how different numbers of candidates are handled, e.g. 2 vs. not-2)
- - rules, policies, and procedures for specific-used vote calculation method


