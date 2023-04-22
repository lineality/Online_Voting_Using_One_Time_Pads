##### Online_Voting_Using_One_Time_Pads

# Voting, Decision, & Consensus Systems in Networks and in General
#### Project-Context Decision-Making Involving Participants and Components


# Contents: 
## Part 1: Secure Online-Voting in-Principle
## Part 2: Practical-&-Secure Online-Voting
## Part 3: Whole-Election and Vote-Analysis Platforms


# Clarifying Goals and Questions:  
- Main Goal: Systematize secure online voting.
- Main Questions: 
#### 1. Is secure-auditable online-voting possible in principle?
#### 2. Is reliable online-vote-result-publishing possible in principle?
#### 3. Can election-processes and election-results-publishing be feasibly, sustainably, pragmatically, realistically, implemented given real world limitations on resources? How is security measured? What specific measures are required for security to be sufficient?
#### 4. What are differences between ideal-maximum-security-systems on the one hand and on the other hand sufficiently-secure, realistically-accessible, and realistically-feasible / practical-to-implement, systems? (e.g. a perfect system vs. a good system, or "not letting the perfect be the enemy of the good")


## Questions For Clarification
To clarify goals and questions, below are two lists of questions. Below is a list of questions that we ARE attempting to answer with this project, and below is another list of questions that we are NOT attempting to answer or resolve with this project. This clarification should help with focus, so that questions we are NOT asking do not become confused with questions that we ARE asking.


### Questions to answer and focus on include the following: 
1. Is secure over-a-network(online) voting possible? (Here 'secure' is defined as being 'as secure as a non-networked paper-ballot-voting-system.') 
2. Is it possible for a voter to securely receive a ballot from a Vote-Office over-a-network(online)? 
3. Is it possible for a voter to submit a ballot securely over-a-network(online)?
4. Is it possible for a voting-office to securely receive a completed ballot from the voter over-a-network(online)? [Including: verifying what ballot was used, verifying who submitted the ballot, checking for over errors in filling out the ballot]
5. Is there an effective equivalent of 'encryption' to allow non-tampering over-a-network?
6. Is there an effective equivalent of 'encryption' to allow privacy & security over-a-network?
7. Is a voting system practical and realistic to implement?
8. What is the best way, or what are the best ways, of concretely defining "over-a-network(online)"?
9. What specific instances are there of voting within systems and projects that share the same core processes of choice, voting, and decision making, coordination, etc., while covering applications beyond the single instance of, for example, US national presidential elections, and that cover more partially or entirely automated systems?


## Questions that we are NOT attempting to answer and that we are NOT focusing on in this project include the following: 
1. NOT: Can online voting be an absolutely effortless and perfectly ecstatic experience?
2. NOT: Can a person outside of the direct-voting-process be provably safe from any voter intimidation, coercion, brainwashing, threats, harassment, discouragement, etc? 
3. NOT: Can a person make no mistakes while filling out their ballot? (Though some additional safeguards from this have been successfully used in some states.See reference.) 
4. NOT: Can the physical offices of staff be absolutely impenetrable to a physical break-in or loss of records due to causes such as fires. 
5. NOT: Can hecklers and trolls be prevented from criticizing, slandering, and defaming, the election and election process even when or where there is nothing legitimate to criticize?
6. NOT: Can all disinformation campaigns be eliminated/precluded/etc.?


## Peripherally related questions:
1. Are there elements of the voting process that affect (encourage or discourage) participation in the voting process (from user interface to requirements for participation to schedules of voting)? An aspect or implication of this may be inadvertent or targeted discrimination against people for whom a given system of voting is more difficult or less likely to be used.

2. Is there a way to define voting as a more general operationally-defined process that leads to more timely and practical deployments of voting tools and features?


# Concept: Universality,Voting-Procedures and Voting-Processes
The view taken here is that 'voting' is a science-like process. Voting is based on procedures, numbers, measurements, feedback, and data. Voting is neither based on nor negated by not-operationally-defined essences, reifications, fears, dramas, feelings, threats, wishes, trust, authorization, belief-ness, faith, tradition, habits, permission, labels, declarations, blustering, doubts, etc. A vote is like a physical piece of machined metal; A vote exists or does not exist with the measurable features that it has, and these measurable features are and must be measurable and confirm-able by anyone who measures it. The behavior and functionality of a vote is equivalent to that vote's repeatedly measurable features. Any group of people who carry out the STEM-math-science-data process of best-practice-voting have performed voting in a way that can be audited, measured, repeated, clearly discussed, debugged, and results published. No group of people can skip or shortcut required STEM-math-science-data processes without having skipped those required STEM-math-science-data processes. As with a surgeon washing their hands before surgery, "trust" is a term better used to mean that you trust the surgeon IS following best practice, though even then it is best to verify without trust that best practice is being followed. Under no circumstances can (so called) 'trust' replace or permit the skipping of best-practice-processes for people or groups, however much disinformation may demand and violently seek to enforce exemptions from best-practice-processes. In other words, if a person or group says "You MUST trust me, so I do NOT need to wash my hands before performing surgery on you, or processing your vote, in a best practice auditable way", you are by definition being subjected to violence, coercion, fraud, disinformation, and classically-defined tyranny.

(General best practice, systems engineering?) 

# Conceptual Note on Identification & Verification
## Voter Identification, Voting-Office Identification, And One-Time-Pads
One way of looking at the use of one-time-pads when voting (entirely setting aside the topic of online or computer networks) is that having the voter (and the voting-office) produce a one-time pad during registration for use during an election the same as issuing a voter a form of voter-id (and also giving the voting-office a verification id that the voter can check). There are various advantages to using a one-time pad over a declaratory-seal-of-much-specialness or other fuzzy form of identification. Anyone can counterfeit a 'super-special-seal' (as on a coin, or a wax imprint), but you cannot counterfeit a matching one-time-pad. And the one-time-pad can be used with the same robustness whether it is in-person, a paper envelope in the mail, by telegraph or telephone, or over a network like the internet.

Like anything else, 'social engineering' and physical disruption are not prevented by a one-time-pad or a voter id. If the earth is destroyed by an asteroid, or a person is murdered or dies, or a voting office is hit by a tornado, or a persuasive neighbor influences and convinces the voter to not participate in the upcoming election by 'choice,' these issues cannot be solved as part of solving the solve-able problems of verification and identification.


# Proposed Steps for Secure Online Voting
This section is primarily a proof of concept, though it should be possible to implement. The emphasis here is on best-practice process, not on maximum convenience or maximum time-resource cost efficiency. So while this model may not be ideal to use directly in all situations, it may be seen (provided tests and audits) as an ideal to not stray too far from. 


## Rules & Assumptions (For Conceptual-Ideal Election)
- Rule/Assumption 1: There is a physical voting-office, just as there would be in the case of an all-paper election.

- Rule/Assumption 2: Problems must be solved in-person with the voter present and with that voter's proof of identification in the same way that the person would register to vote (and/or cast their vote in an in-person election).  

- Rule/Assumption 3: Empirical tests, hypothetical tests, and security checks should be done to demonstrate how this (or any) voting system measurably succeeds or measurably fails to work. [E.g. "I just like it." or: "I just don't like it." Are not sufficient reasons to use or to not use a given voting process.]

- Rule/Assumption 4: Voting issues must be definable and defined in measurable and testable ways. E.g. If this system does work, disinformation will be used to prevent it from working. 

- Rule/Assumption 5: If the context is critiquing the mechanics of casting/submitting ballots and votes, then a failure to agree on design and rules for an election (e.g. doing a run-off or not doing a run-off, how proportional representation is, etc.) should not be considered relevant to the context of submitting a ballot. (E.g. complaints about how votes are counted (or ignored) should not be used as an argument against secure methods to (the context of the mechanics of) casting/submitting ballots and votes.)

Q: Design question: printable-document format vs. .csv format
- reading document
- storing document
- converting document

## Steps (For Conceptual-Ideal Election)

#### Step 1: (During in-person voter registration: start registration [not-over-a-network/not-online]:) 
Before the election ends: A person, e.g. in-person, with ID (identifiable as an eligible voter according to local rules), goes to the Voting-Office to register for the vote-over-a-network (with One-Time-Pad) (online voting) process. 

(Note: There is a system-design-choice to allow (or not) registration for more than one election. This issue can be related to the format/type of the submitted ballot. For example: 
#### A. ballots that have been (or can have been) designed at the time of registration, and 
#### B. Standardized or truncated ballots containing just choices and not all the text of the ballot (possibly a choice (e.g. choice number) and the initials of the person's name as a second factor) and 
#### C. whether whatever form of ballot is customized for each voter (e.g. with a custom-id, verifiable as going to and coming from that one voter) or whether the ballot is standardized (and verifiable as the standard ballot for that election or more standardized) )

#### Step 2: (During in-person registration: Make one-time-pads.) 
For a given single vote-ballot in a given single-election (note: multiple is another design option) there need to be four physical paper documents. One "pad" (as defined here) is two identical paper documents, one for each party (two parties, in this case: 1. The Voter and 2. The Vote-Office). Since there will be two "exchanges (people sending things to each other)" (one (1) where the blank-ballot is sent to the voter, and another (2) where the filled-in-ballot is sent by the voter to the vote-office), there need to be two pads. E.g. If the voter obtains a ballot from a compromised public ballot website or a fake website (disinformation) then that vote could be disrupted unless the problem is detected and the danger avoided.

(Alternately the voting-system could be streamlined to use only one pad for submitting a standardized public ballot, but this shorter process does not include the step for the voter to confirm that the ballot was sent by the vote-office and it also prevents the office from confirming that the ballot used was the same ballot sent by the vote-office to the voter. See below for more details.) 

Using two one-time-pads has several advantages.
To recap: one pad is for sending the voter a blank ballot (from the voting office), the second pad is for the voter to send the completed ballot to the voting office. This allows the voter to verify that the ballot they are filling out comes from the Vote-Office at which they registered, and that only someone with physical access to the physical one-time-pad created at the time and place of their registration has sent them this ballot. And this allows for a comparison by the Vote-Office, likewise, of the ballot sent and the ballot received. The benchmark for success here is for an over-a-network(online) voting system to be as-secure-as an in-person, all-paper, voting system. Just as it is possible (in theory) for a hostile group to physically take over a Vote-Office and issue people fake ballots, or send people fake mail-in ballots in the mail, this one-time-pad-vote-by-network proposal does not prevent such physical attacks on physical paper voting infrastructure. It does however create an extra layer of verifications that can be used during and after the vote takes place, which in theory could also be used to security-harden an all-in-person all-paper voting process to make it more secure and auditable (this may also relate to the use of and questions about asymmetric keys which are different from one-time-pads). (Note: Another additional or alternative method for some of these checks may be cryptographic signing (with optional multiple signatures) from trusted authorities (Vote-Office, federal or state agency, universities, 3rd party certifiers, etc). 


During the in-person one-time-pad-voter-registration: Two physical copies (e.g. QR codes printed on paper) of two one-time-pads are created (2x2 = 4 printed paper items); one set of the two pads are stored (not-over-a-network/not-online) by the local Vote-Office, the other set (pair) of one time pads is kept by the voter themselves (physically, not-over-a-network/not-online).

The software will print the one-time pads. The software will check (confirm, verify) the one-time pads. The software will erase thoroughly from memory (e.g. physically overwrite) any record of what the printed one-time-pads were.
(Note, if this process is done not-over-a-network/not-online using a dedicated machine, the risk (attack-surface) of someone being able to take (exfiltrate) the one-time-pads is reduced. Especially if the custom machine does not have enough memory to store any old pads but can only process and re-write-over one pad at a time.)

#### Step 3: (During in-person Registration: Create Encrypted Ballot) 
For the voting-office to send one ballot to one voter:
The election office, not-over-a-network/not-online (enforced by software), uses the first 1:2 of the pair of printed QR codes to create an 'encrypted' version of the ballot for that one voter. 
Note: The ballot may be public, but it still needs to be verified. This illustrates the "verification" role sometimes lumped together with "security" and "encryption." The emphasis is not on 'hiding' the public ballot form, but on verifying that the specific ballot form that the voter is filling out is (identical to) the form that the local election office gave them.

Note: It may be desirable to have a 'verified public ballot' as opposed to a 'private ballot' which in theory could vary (for security and verification) from the standard public ballot (in a context of mapping out a potential attack space). 
In the case that a truncated-submitted ballot is used, some way may be desired to, e.g. make a short hash of the original ballot itself (e.g. to convert the ballot by OCR or perhaps have a QR code on the ballot (though a QR on a ballot received by a voter code could be forged, whereas a hash made by the voter of the whole ballot could not be). Perhaps having a multi-pass OCR hash of a public ballot submitted with the vote to indicate that the correct ballot was used (again, in the case of a truncated submission, for a full ballot return the whole ballot is there)(also see asymmetric signing keys). 
It may be possible to have both a public verified 'open' ballot format and some unique element for the voter to check that the ballot comes from the Vote-Office with the voters one-time-pad (such as a unique id code at the bottom or top of the ballot)


#### Step 4: (Voter Gets Not-Yet-Completed Ballot over-a-network) 
During the election period (be that months, weeks, days, hours, etc.), a one-time-pad 'encoded' ballot is sent [from the voting-office to the voter] by whatever agreed upon ("electronic" or non-paper) method (website, email, SMS-text, mobile-app, S3, api-endpoint, etc.) in the form of a QR code.
(note: document vs. .csv file format)

Note: As an example method for a 'personalized ballot,' a randomized process of frame-shifting the ballot so that where exactly on the page each person's vote-choices appears is random, increasing the entropy of the unique ballot (e.g. so that the voting-office can increase confidence that the ballot they receive back from the voter is the one they set). 

Note: Public Ballot vs. Private Ballot vs. Hybrid
1. Public 'open' ballots over a network and verifiable, maybe multi-factor verifiable. (Asymmetric signed by voting office, asymmetric signed by other trusted groups: ngo, university, sister cities, etc. The idea being that 'multi-factor' significantly increases the difficulty of attack; a public open-ledger ballot on a block-chain type system may also be either an alternative or another multi-factor. 
2. Send the vote (or allow them to download) a private ballot (or a public ballot)

Note: Another type of hybrid approach is to physically hand out general or unique ballots at the ballot office to the voter in-person, in the same process where the voter registers to vote.


#### Step 5: (Voter Receives the not-yet-completed ballot [over-a-network]) 
Voter Receives Ballot online.

(Note: There is a choice here between using a public standardized ballot or a per-person ballot (e.g. with a unique id number or such, to verify that the ballot-form sent was the same as that received, or a short-form vote which contains just the choices and not all the text of the ballot.)


#### Step 6: (Decrypt and print ballot [not-over-a-network/not-online])
Using one piece of software, the voter not-over-a-network/not-online (enforced by software, possibly hardware) 'decrypts' the ballot.


#### Step 7:(Print Ballot [not-over-a-network/not-online])
physically prints the decrypted ballot


#### Step 8: (Validate the not-yet-completed Ballot [not-over-a-network/not-online]) 
The voter not-over-a-network/not-online(enforced by software), inspects and validates that their digital scanned version of their not-yet-filled-out-ballot is the correct ballot-form intended for that election (e.g. not a tampered with or accidentally incorrect ballot). There are various and possibly multiple ways to check this (elaboration pending).

(Note on Steps 5 and 6: possibly the validity of the ballot could or should be checked during both steps)


#### Step 9: (Complete/Mark/Fill-in the Ballot with Vote-Choices [not-over-a-network/not-online]) 
The voter, not-over-a-network/not-online(using pen and paper), fills out the ballot (selecting their vote choices). (Details here may be important in some way: filling in a circle, selecting an option number, multi-factor, non-over-under-voting checks, etc.)


#### Step 10: (Digitize the Completed Ballot not-over-a-network/not-online] ) 
The voter, not-over-a-network/not-online (enforced by software), scans (e.g. by taking a picture) the completed-filled-in paper ballot, creating not a photo but a document or table of information (so that the one-time-pad can convert character by character). 
(Note: maybe some kind of mono-space font and dashes between lines to avoid spacing errors?) 


#### Step 11: (Check Completed-Ballot for Errors [not-over-a-network/not-online]) 
The voter confirms that the information in their (the voter's)  electronic scanned ballot is the same as the paper version of their (the voter's) filled out ballot. (Checking for errors.) (Note: Automated processes for checking ballots for standard mistakes.)

~ Step: An optional but recommended intermediate step here is to have a 3rd set of not-over-a-network/not-online-only software that will check the ballot before and or after it is filled out by the voter, such that this additional set of software can check for the "overvoting" (voting for both candidates) and "undervoting" (voting for neither candidate) issues as a safeguard (against accidentally-incorrectly filled-out-and-submitted ballots) and that perhaps Nevada has used successfully. 

Q: Is there a way to optimize OCR? e.g. letter per box format? Alternatives to OCR?
- various ocr applications that can be used
- open source
- safety, reliability issues

Reference: 
"Roll Off at the Top of the Ballot: Intentional Undervoting in American Presidential Elections"
December 2003 Politics & Policy 31(4):575 - 594
DOI:10.1111/j.1747-1346.2003.tb00163.x
Authors: Stephen Knack & Martha Kropf
University of North Carolina at Charlotte
https://www.researchgate.net/publication/227617394_Roll_Off_at_the_Top_of_the_Ballot_Intentional_Undervoting_in_American_Presidential_Elections 
(end of reference)

Another ~'multifactor' check may be to both mark a vote-choice on the ballot also and give some information about that choice, e.g. mark candidate 2 and in a second field enter the first letter of that candidate's last name. If these do not match, the voter should be alerted to check their ballot selections.
The voter, not-over-a-network/not-online(enforced by software), scans (e.g. by taking a picture) the filled-out paper ballot.  
(Q: ...print formats...)


#### Step 12: (Encrypt the Ballot [not-over-a-network/not-online]) 
The voter, not-over-a-network/not-online(enforced by software), uses the one-time-pad to 'encrypt' the completed ballot, producing a new QR code (which is then 'encrypted' ballot). All digital files of the unencrypted ballot are removed and the memory physically over-written on the voter's device. The paper copy of the voter's ballot can be saved for evidence or destroyed for privacy based on the voter's choice. (Note: signing signatures can be used with the printed ballot or QR-code to increase confidence that the ballot is authentic. This combines advantages of asymmetric encryption along with a physical printed paper trail for audits.)


#### Step 13: (Voter Submits Encrypted-ballot Over-a-Network) 
Online: The voter sends their completed-ballot-QR-code (containing the voter's encrypted filled-in and checked ballot) to the local election office (sent by whatever agreed upon method (website, email, text, messaging software, shared storage (e.g. S3), api-endpoint, etc.)).


#### Step 14: (Initial Handling of Voter's Encrypted Ballot [Over-a-Network])
The local election office physically prints onto paper the QR code for the 'encrypted' filled out ballot, and then (double) checks (compares) to confirm that the physical print (of the electronically-sent QR code) is accurate/identical (to the QR code submitted by the voter), and (if printing is accurate) deletes the digital record and the memory is physically over-written.
1. Print
2. Check
3. Delete
 
##### Note: This step will most likely be done on a "computer" that is connected to a "network."


#### Step 15: (Processing the Voter-Submitted Ballot [not-over-a-network / not-online])
not-over-a-network/not-online, using a separate piece of software, the local election office "decrypts" the QR code for the 'encrypted' completed(choices-filled-in) ballot using the second(2:2) of the pair of printed (pad)QR codes for the one-time pad, and physically prints on paper the voter's filled-in ballot. 
(Note: one choice in designing the software is to directly-print-to-paper or to decrypt and display on a screen or possible save as a computer file)
The voter's completed ballot is stored along with any completed paper ballot (e.g. mail-in ballots, or paper ballots delivered in person or filled out in person).
(Note: Depending on the details, an additional step may be needed to convert the format of the QR code (or abridged format) to the same format as an in-person ballot. For example, if only the vote choice data are recorded in the QR code (or abridged format) the exact placement of each printed character on paper may be needed or useful for manual or automated ballot counting).

Q: How much data can a QR code contain? 
Q: How redundant can a QR be for error-correction?

Note: If the ballot is processed on an not-over-a-network/not-online not-connected to a network computer then the chances of 'hacking' the vote are reduced (the 'attack surface' is reduced). 

Enter voter data into the election-results-data-set.


#### Step 16: (Process Election Data / Count The Votes)
The printed ballot is counted with the other paper ballots of various kinds during the normal election ballot count process.


#### Step 17: (Publish Election-Results Data)
The election results are processed and published.
(The publication of election results is perhaps not strictly part of the question of 'secure voting' but in practice it is likely often a requirement.)


# Information-Entropy, One time pads, old pads, and random number generation.
 
The neglected topic of entropy often comes back to byte us. If:
If someone wishes to save old one-time-pads(e.g. QR-codes). Or: If someone does not dispose of old one-time-pads(e.g. QR-codes). And: If one-time-pads(e.g. QR-codes) were not generated in a sufficiently random way, then by studying a collection of old one-time-pads(e.g. QR-codes) that were generated using a not-sufficiently-random process it could be possible (or even trivial) to 'hack' the one-time-pad(e.g. QR-code) generation process and thereby be able to disrupt many parts of the voting system.




# Risks, Attacks & Security

## Identifying Risks 
Here we look at risks from bad-actors or bad-agents. A bad-agent may be human or automated, may be local or non-local agents such as foreign states / groups. (As of 2022 ransomware is popular, and it is possible that an election system could be targeted e.g. for ransom, so designing a distributed and attack resistant framework may be important.)
An 'agent' may be anything from a single person to a group of people to an AI-bot, software suit, malware software, ransomware software, thinktank, etc. (or something unclear and not simple to identify) (note: other areas of risks should be explored, and may include: 
-1. Constant 'internet background radiation'
-2. Unintentional user-misuse
-3. Unintentional administrative bungling
-4. Oversights and biases (e.g. setting up a voting system and obsessing so much over absolutely obscure vote secrecy that vote auditing and best practice domestic and international observation of the vote process is impeded, impracticable, or impossible)
-5. practical feasibility vs. ideals in principle (possibly similar to "letting the perfect be the enemy of the good') 
-6. Software design problems that cause time, logistical, or reliability problems
-7. Etc.

Note: It may be important to consider both (unsuccessful) attempted-attacks and successful attacks. An unsuccessful attempted-attack should likely be considered important and not ignored simply because it was not entirely successful. E.g. possibly considering attack-attempts to be the unit in attack-space, not successful-attacks. 

## Bad-agents
1. A bad-agent will intercept one-time-pads:

1.1 - The agent would need to be physically in the room during the QR code creation, to break into the gov. office, or to physically steal from the person, without anyone knowing the QR codes were stolen. 

1.2 - The one-time-pads are never stored digitally anywhere, but are only physically printed by an not-over-a-network/not-online computer.

1.3 - If the voter loses the QR code the person should cancel the process.

2. A bad-agent will send the voter a fake blank-ballot:
- additional step: there can be additional checks such as a passphrase chosen by the person which could not be electronically surveilled from any computer (e.g. written in pen on the QR pad) 

3. A bad-agent will send the voting system a fake filled-in ballot (pretending to be the voter):

- 3.1  The bad-agent would need to have both stolen QR codes and a stolen ballot that was sent to the voter.

- 3.2  If a voter loses the QR code then that voter should cancel/restart the process.
	
4. A bad-agent will record a fake record of the vote from the ballot:
- while a possible risk, depending on the online-voting system this process (a fake record of the vote from the ballot) is the same as for any paper ballot.
Variants:
- change existing record
- corrupt original-record-creation process (bugs and loopholes in design)
- manually interfere physically in vote office during process putting in false information
- social engineering attack to the same end (e.g. impersonating a voter, pole worker, technician, etc.)


5. A bad-agent will act on the behalf of a participant without the voter's participation:
- cast a vote
- cancel or change registration
- try to register or get registration information

6. A bad-agent will act on the behalf of the voting office without the voting-office's participation.

7. A bad-agent will attempt to tamper with a public ballot (e.g. a ballot itself, e.g. downloading a ballot to use).

8. A bad-agent will attempt to tamper with public ballot-confirmation information (e.g. public information posted about the ballot by the voting office, describing and understanding the ballot and ballot issues).

9. A bad-agent will attempt to tamper with voting instructions and information about voting procedures.

10. A bad-agent will attempt to tamper with vote reporting including any information put out by a Vote-Office or similar authority.

11. A bad-agent will attempt to disrupt the sending and receiving of vote information (including but not restricted to blank and filled-in ballots (e.g. voting times, places, registration, ballot items, etc). 

12. A bad-agent will attempt general or specific disinformation attacks that negatively impact the overall voting and election processes and systems. 

13. A bad agent will attempt to disrupt or disperse the population or geography of a vote (creating a need for refugee voting). 

14. A bad agent will attempt to gain access to a system (network, server, etc.) as a goal in and of itself: e.g. to then sell or transfer that access to a separate attacker-agent.

15. A bad-agent will attempt to lurk undetected in the target system indefinitely, waiting and planning for a good time to act. (APT?) (see: canary; see: living off the land)

16. A bad-agent will attempt to re-purpose the voting system for their own uses.

17. A bad-agent will attempt to disrupt access to the voting tools and processes, from enrollment to voting to results reporting and verification.

18. A bad-agent will attempt to disrupt the network.

19. A bad agent may behave in ways that are indeterminately incompetent and malicious. 

20. A bad-agent will attempt social engineering attacks.



## Description & Overview of Process-in-Principle
This is a proposed process for reasonably secure 'online (over a network) voting.' Part of this design is that the entire process is not on-line. Rather, physical printed materials and not-over-a-network/not-online computers are used to reduce the online attack surface. A person or bad-agent can feasibly steal or tamper with a file in a network-connected computer from a remote location, but a person or bad-agent cannot feasibly/easily tamper with or steal documents in a filing cabinet or from a computer connected to the internet. This particular solution is not a perfect-for-all-cases solution. E.g. This will not be easy to use for persons who cannot ever travel themselves to a gov. office or polling place. 

The primary focus of this report is the question of whether casting a ballot/vote over-a-network(online) can in principle be done with sufficient security and soundness. Secondarily, this report explores 'practical and thrifty' variations which add in factors of feasibility, cost, equipment availability, and other real-world factors that communities around the world may face in actually holding an election (i.e. not everyone has ideal funding and resources with which to carry out the perfect election). Another way to look at this distinction is that we first look at an ideal voting system to aim for, and then look at realistic voting systems. 


## Implementation
(see practical implementation as separate after proof of concept implementation)
These are recommendations for a reasonably secure online voting system that should not be significantly more cumbersome than a physical paper voting system. 

To improve accessibility, it is conceivable that some local voting systems would prefer to simplify some of the security step to allow broader accessibility:
- voters who have no access to a printer
- voters who cannot physically travel (e.g. elderly persons in retirement home or hospital), perhaps allowing a proxy to carry documents for that person.

- institutions large or small such as retirement homes or other such community organizations are well placed to be involved where voters are not physically able to travel to poles. 

- Military overseas are another important group of voters who are both not physically able to travel overseas yet often close to bodies of administration and organization who can facilitate voting.  


### Additional steps can be taken to increase security. 
Security section
#### For example: 
1. To reduce the possibility that local staff will accidentally connect to the internet or run the software on insecure or already compromised hardware, it should be possible to create a cost effective system where staff will run a custom made operating system (custom BSD or Linux or FreeDOS, etc.) that lacks the ability to use the internet. It may also be possible to use cost effective hardware such as a raspberry pi or microcontrollers. There may be safety advantages to using micro-controllers that lack overall computer abilities and thereby lack security risks associated with those.


2. Put safeguards into the software to at least try to prevent using the same one-time-pad more than once. 

3. Known issues and areas:
- memory issues: use memory safe languages
- fonts: restrict and regulate character-set use
- communications and fishing: don't use insecure systems such as email, SMS texts, http, ftp, etc.


## Unique Ballots
At this time or at a later time (depending on choice, timing, etc. (e.g. if the ballot has been decided which is often not the case at the time of voter registration or if in terms of security level if the voter does not trust a physical breakin of the vote office and wants in advance a verifiable ballot) (not-over-a-network/not-online) a printed copy of a unique ballot (e.g. containing if not the voter's name the equivalent of a sha256 hash of the unique ballot). Either a unique ballot or a unique ballot identification number will be used on both ends, by the voter to check that the ballot they receive is authentic and by the office that the ballot received completed and sent by the voters is authentic. (Note: some combination of a 'signed' public ballot and a signed sender/recipient may also be possible)
(todo: list pros and cons of using unique ballots (per voter)

## Challenges:
One area that may cause issues is if the office or voter is 'unable' to scan or take a clear photo of the document, in the same way that some people are 'unable' (which ranges from people having legitimate physical or mental handicaps to people not bothering to try) to take a clear picture of their check for their bank (so a less secure non-printed option may be desired in some cases).
It is also possible that OCR (optical character recognition) may not be good enough to perform a computer-automated visual reading of a printed paper ballot, but given the use of OCR to read more obscurely printed checks, sloppily written mailing addresses on envelopes, etc., this is possibly not a terminal obstacle. 
#### (note: .csv files may have a standardizing role here) 
#### (note: writing characters in a grid may have a standardizing role here) 


Note: It might be possible to make a kind of hybrid document solution. There can be a QR code that gives template and instruction information as to what the fields are, then items selected (boxes filled, or circles filled in) can be identified without the use of OCR. In the case of write-in ballot areas, there may be various factors that make OCR 'good enough.' e.g. if any candidate receives enough write-in votes, that situation will make that popular name a more likely candidate for matching in the case of mostly illegible scrawling. And having one letter per box may also help legibility for write-in names. 

The task of automated ballot-reading perhaps should be steered away from subtle character recognition of natural-language phrases and towards clear, easily defined, targets such as a binary check-box selection. An exception to this may be write-in ballots which do occur, where some other system may be needed (binary as in: checked-box vs. not-checked-box).
Though even here, OCR and having the vote double-check to see that the OCR is correct may be sufficient. 
(Note: The direct use of .csv files may be ideal. CSV files can also account for write-in and other edge cases. Any 'field' to fill in can simply be included either as an item in the same row and or as a column heading).


## About One Time Pads
A one-time-pad is not the same as a re-use-able 'code.' A re-use-able code 'encodes' a signal and is re-used, such that 'breaking the code' will allow decrypting the document. A one-time-pad is different; a unique one-time-pad is used only one time. A one-time-pad is a one-for-one set of changes for every character in the document, each completely random, with no pattern, and each one-time-pad is used only one-time. Even in principle you cannot 'break' a one-time pad however much you examine the encrypted document (unless the one-time-pad itself is somehow defective: to be a real one time pad it must be used only once and it must be unique and random).  Unfortunately, the terminology can be overlapping and a bit unclear between the reusable codes and one-time-pads. For example, the terms 'encode' and 'decode' may be used in both cases, and the overall process and purpose is usually similar or the same. 

Historically, a 'one time pad' was literally a pair of identical physical paper note-pads, two notebooks, with the same set of characters on corresponding pages 1,2,3 etc. in both notebooks. By analogy this is like two copies of the same book (such as two identical copies and identical editions of Alice in Wonderland), with the same exact characters on the same numbered page of each book). Each code (e.g. each page) was used only one time, hence the term "one-time-pad". In summary: a pair of identical physical paper note-pads, each page of which was used only one time: a "one time pad."

With a one-time-pad, every character (letter, number, symbol, etc.) in the document that you are encrypting is individually changed using just one character in the [one time]pad. There is no predetermining pattern or system behind the sequence of changes resulting from using a one-time-pad that can be outsmarted or 'cracked.' The only way to 'decode' a one-time-pad 'encrypted' message is with that one-time-pad; a one-time-pad is a one-by-one, one-for-one, one character at a time, change of what the original text says. There is no key. There is no password. There is no equation. There is no shortcut. Every character or unit of the entire document is individually changed into something else in an independent way. 

One-time-pads are not as efficient and user-friendly as shorter and or 're-use-able' codes in some ways, but one-time-pads are more secure and more simple. Because there is no 'key,' there is no possibility in principle to 'guess the key.' The one-time-pad must be as long as the original text itself, unlike a 'password' or short 'key' that might be only eight characters long. 


#### Low-Tech Security & Limited-Resources
Q: Is there a lower-tech version with reasonable security for geographic locations with limited resources?

Details: The first part of this report is a more abstract proof-of-concept about whether one-time-pad voting over a network is any less secure than one-time-pad secured voting over-a-network. However, in reality actual voters and voting-offices may refuse to use an ideal secure voting system (for reasons legitimate or illegitimate). It is entirely within keeping with computer science that there are multiple possible solutions to a problem, and while one solution may be perfectly fine in theory it is simply not practical or feasible to implement (often: requiring too many resources (including time as a resources), either relatively too many (resources-required) compared to another solution or too many as in that requirement simply cannot be met with known technology (e.g. taking a length of time longer than the age of the universe to solve the problem: in principle: problem solved! in practical reality: problem not solved.)). There should be a discussion of what a good-enough solution is, and how a good-enough solution may meet the practical demands of users. 

- focusing on accessible technology?


# Part 2: Practical Secure Online Voting
### Goal: Practical version of 'online voting' for realistic implementation
('online voting' is likely an easy to understand common term for a more general and abstract process of automated networked project decision coordination with broad applications)

There is a difference between only the step of casting a vote being done online-over-a-network (to get the advantages of votes being cast from anywhere during a longer time-frame), and the entire election being held online, over-a-network. There are advantages and disadvantages to an online, de-centered, open-source, election-system. Advantages:
- open source
- audit-able
- test-able
- faster
- cheaper
- available to oppressed and under-represented groups
- modular: voting and election do not only happen during governmental elections, that is just one instance of a more general process. 

####  Some voting locations (or regions) may not have: 
1. printers, ink, and paper
2. extra air-gapped computers
3. a physical location to securely store paper files
4. broadband wireless internet
5. a find-able standardized address for voters to find
6. a safe location to vote

#### Most locations can be assumed to have and required to have:
1. basic mobile phones
2. basic (not high speed) internet access

Writing down the numbers and confirming with a photo (no printers needed) may be able to replace a printed QR code system while still having a paper-backup form, if only as an option (e.g. you cannot hack into and change a piece of paper). 

A separate air-gapped mobile device would be feasible, or perhaps a more decentralized system would be more secure.
(note: 'certificate' model)


# An alternative thrifty-protocol for resource-limited situations/geographies 
(section under construction)

## Practical Voting
The goal here (for this practical-tool section, vs. the above secure voting in principle) is more a practical-project and less abstract (proof of concept or standard-setting): How can a local community organize and carry out a best-practice auditible vote and publish the results using (widely available and) accessible technology (such as mobile phones)?

What are some of the factors that characterize a realistically resource-limited situation? Are there some general groups of common sets of constraints? E.g. Some groups may have a safe place for a voting office but no funds for extra equipment. Other groups may not have a safe place for any voting office or official positions (needing the management of the election to be virtual and decentralized). 

Question: Can virtual distributed elections be best carried out with or without support from institutions such as universities? Or more generally, what roles do 'institutions' including legal institutions, have with a fundamentally STEM/math/engineering process of carrying out and publishing the results of elections which have no reliance upon culture or belief and yet the results of which for practicality must be integrated with the 'social' system that is voting? (probably a bad analogy example: you do not need social institutions to measure the temperature of the (for example) the air, but without 'institutions' around standards and measures and even media of communication it would be infeasible to physically or intellectually communicate and use that measurement-data. (E.g. go back in time a million years: you could measure the temperature of the air just fine, but how would you usefully-communicate that temperature-information to STEM-institution-less-communities of people and how would they use that information?)

Thrifty voting systems may make more use of available multi-factor authentication and less use of equipment-expensive methods (such as dedicated printing and scanning machines). 

Depending on the details of the situation, there may be some option for physical printed documents, but there will most likely be more use of non-paper methods for a thrifty resource-slim and more user-friendly system, for example in cases where there is no possible way to use physical documents. 

Other methods such as chains-of-trust may be useful to harden thrifty online systems.?

#### General Revisions for Thrifty-Secure-Voting:
1. use-able with only standard mobile devices possessed by voters
2. no physical printed copies, so a change from OCR and paper documents to basic characters in a file. 
3. no separate air-gapped hardware
4. one pad per set of elections vs. two pads per single election (backup pads?)
5. more cryptographic signature use?


#### Topic: use of one time pads plus signing signatures



#### Notes:
- individual permission drop-off folders (like S3)
- anonymized ballots (storing data without direct connection to user information)
- face-picture when sending in vote
- vote by phone system, tied to that phone...(note: if you lose the phone)
- 'done by voter' means voter-side-software vs. vote-system/voting-office-side-software, not necessarily manually done. e.g. automated error checking. (better terms probably needed)

## Ballot format standardization?
- csv format: pads, ballots, votes
- data format / presentation format 
- character type...ascii?


# Proposed Steps for Practical Secure Online Voting (section under construction)

For a voting system to be practical, the requirements for implementation and assumptions about what resources voters have must align and align with reality. 

#### This thrifty-and-pragmatic (if not perfect) system does NOT assume:
- that there is a voting office either as a building or as human staff
- that voting-areas can afford any equipment beyond voters having mobile phones
- that a voting-area can afford a large staff to manage the election
- that there are institutions for safe and secure elections


#### Step 1: (Election-Setup: [over-a-network / online]) 
- scheduling
- enrollment
- standards protocols methods and procedures
- 

#### Step 2: (Voter-Setup: During online registration time period [over-a-network / online]) 
Before the election ends: A voter registers for the vote-over-a-network (with One-Time-Pad) (online voting) process. 
This may be done entirely online for most-practical voting, or other elements may be added.
(Note: setup questions for entirely online vote: How list of voters is selected or checked. Voter identification online... In theory the same online system as for current voter-registration may be used and considered sufficient.)

For entirely-online-voting there is the challenge of selecting who on the internet may participate. 
A kind of hybrid may involve e.g. sending snail-mailed to voters (or picked up with ID from an office) to use to authenticate their online connection. 
note: using signing-signatures

While the thrifty/pragmatic-protocol is designed to avoid extra printer hardware, the option still exists to hand-write one-time pads, which for an election with fewer than five or 10 choices on the ballot would be practical to write down on wallet sized note (and check electronically (OCR) to make sure it is correct). 
A short-form ballot one-time-pad good for several ballots may be hand written and OCR-checked on a wallet-card sized card or paper.

(Q: How reliable is OCR? Is OCR reliability an issue? Is this a strong argument for all-digital and no-conversion process? (can still be printed or saved records etc.)

A short-form or truncated ballot may contain, 
e.g., 
- the number of the option-choice and perhaps 
- a first/last letter in the candidate's name (which could also serve as a check, similar to an empty choice check, if the name-letter does not agree with the number option). 
(also a check against vote left empty?)
Note: Write-in may be an issue for the truncated ballot. 

#### Note: Ways to make sure a one-time-pad is not being used a 2nd time...a log of already used one-time-pads to check against...?...or a small hash?

The idea of a non-recoverable system, disposable, that you would restart if something went wrong, but no back-doors, side doors, etc.
voter...re-register...multiple registrations?

note: squirel grc.com 

Q: one time pads vs. signing keys for transmitting ballots
Also: multiple party signing keys?


#### Step 3: Voter Obtains Ballot Online
#### 3 options:
1. a publicly posted signed ballot (verifiable)
2. a ballot including a unique personal id sent only to that one person 
3. both
4. some kind of redundancy and checking between sources and agreement of online ballots. (e.g. .edu hosting, or distributed software held by voters?)

During the election period (be that months, weeks, days, hours, etc.), a one-time-pad 'encoded' ballot is sent by whatever agreed upon method (website, email, text, snapchat, S3, api-endpoint, etc.) in the form of another QR code.
Part of this process is an at-the-time randomized process of frame-shifting the ballot so that the location on the page where each person's vote-choices appear is random. 

  
#### Step 4: (Voter Gets the not-yet-completed Ballot)  
Optional ways to do this:
- A. posted on several public sites and signed and can be compared/verified
- B. collecting from (and perhaps compared across) various sources by voting software, e.g. a minimal and secure mobile device software application ("app")
(For the most-resource efficient system, individually sending personalized ballots should perhaps be avoided. Question: What are the factors around this? Does a ballot need to be individualized? How does it need to be individualized?)


#### Step 5: (Voter Validate the not-yet-completed Ballot) 
The voter on-line inspects and validates the ballot. Most likely by checking and comparing multiple sources,possibly signing keys, maybe multiple signing certificates. There could be both manual and automatic options to balance ease of use with manual thoroughness. 
(note: Finding universities to host copies of the final ballot may be a good option. But this step may not be feasible or necessary.) (Something like a blockchain (immutable ledger) for all users of the voting system may suffice as a good-enough decentered immutable portable verified storage system.)


#### Step 6: (Voter Completes the Ballot, Marks Votes) 
e.g. csv format of data (vs. pdf type doc)
Q: id such as biometric data?

~ step: an optional intermediate step here is to have a 3rd set of not-over-a-network/not-online-only software that will check the ballot before and or after it is filled out by the voter, such that this additional set of software can check for the "overvoting" (voting for both candidates) and "undervoting" (voting for neither candidate) issues as a safeguard (against accidentally-incorrectly filled-out-and-submitted ballots) and that perhaps Nevada has used successfully. 

#### See Article: 
"Roll Off at the Top of the Ballot: Intentional Undervoting in American Presidential Elections"
December 2003 Politics & Policy 31(4):575 - 594
DOI:10.1111/j.1747-1346.2003.tb00163.x
Authors: Stephen Knack & Martha Kropf
University of North Carolina at Charlotte
https://www.researchgate.net/publication/227617394_Roll_Off_at_the_Top_of_the_Ballot_Intentional_Undervoting_in_American_Presidential_Elections 


#### Step 7: (Check Completed-Ballot for Errors [done by voter]) 
- sanitizing inputs
- adversarial inputs
- impossible options (more than one option selected where only one can be)
- no-vote blanks 
- too few for multiple selections, possible make vote choices clear so that one selection is required for each question. )
- test-process errors (something breaks processing)


#### Step 8: (Encrypt the Completed-Ballot [done by voter]) 
Details depend on the file system being used.
Q: If an anonymized blockchain system is used, is there a need to encrypt the submitted ballot? e.g. could the ballot have an anonymized id?


#### Step 9: (Voter Submit encrypted-ballot over network) 
Q: recommended methods?
some kind of MFA or blockchain ledger system?

Online: The voter sends (by whatever agreed upon method (website, email, text, snapchat, S3, api-endpoint, etc.)) the new QR code (containing their encrypted filled-in-and-checked ballot) to the local election office.


#### Step 10: (Process the Encrypted Voter-Submitted Ballot)
- thrifty encryption choice?
Arguably this is a key area if one-time-pads are not being used, or not in the same way as the proof-of-concept. 
- format of ballot
(file format: csv?)
(voter checks on status?)
- decrypt
- data-entry: vote into system
- an advantage, possibly a significant one, is the ability to skip optical text recognition and keep all data in a stable digital format.


#### Step 11: (Process Election Data / Count The Votes)
(storage: distributed? immutable-ledger?)

#### Step 12: (Publish Election Vote-Results-Data)
- automated?

#### Step 13: (Publish Election Report)
- documentation on system architecture
- policies
- rules
- enrollment
- method of vote-counting
- security audit of system
- security audit of election
- questionnaires and poles
- rules for margins, recounts, challenges, runoffs, etc.
- open source system code
- anonymized election results
- election schedule



# Notes:
#### Q: Background tests and checks during the whole process?

#### (election results publishing...parts of process)

#### Note: It is not clear that saving the QR codes serves any function, nor is there any need to carefully dispose of a QR code after it is used (if each is only used once). 

#### What kind of software (singular or plural) would be needed to arrange a secure election?

#### Voting and the byzantine general problem

#### Immutable-Ledger Data-Structures (blockchains): 
- Could some form of blockchain constructed by election participants be used as a decentered election results platform? 
- General record and evidence chains. (admittance of observers, reports, events, etc.)
- Note: while 'blockchains' per-se have gotten a lot of bad press, there are various ways to accomplish the goal of having distributed redundancy. 

#### Resilience: 
One strategy: Part of an online system may be to increase the number of channels by which people can try to vote, and possibly have a backup-pad. Thereby, if bad-agents shut down the main channel for sending in votes (which may be a single point of failure) the process will not be disrupted.

Is there a formal way to map the attack-surface areas of, and to compare, different systems of voting?


# A Practical Election Management Package

#### Features of a practical voting software package:
1. secure messages between office and voter? (one time pad?)
2. secure voting platform (receive ballot)
2.1 voter registration
2.2 send or assign ballots
2.3 fill out ballot
2.4 submit ballot
3. Processing votes
3.1 receive votes
3.2 validate votes
3.3 decrypt votes
5. process votes
6. produce results report
7. schedule election
8. publish results report
9. Automation of parts and all parts of elections
10. Elections including/between non-human project elements (AI)


#### Mode of Voting Offices
- Mode 1: single physical vote office
- Mode 2: meta-population of physical vote offices
- Mode 3: remote vote office(s)
- Mode 4: decentralized vote office (distributed among voters)

Maybe each 'election' will have a different signing key to verify?

software platforms/languages:

(Project)
## "Pseudocode for voting infrastructure"
- including how to create randomized representative voting districts
- including how to do ranked choice voting
- including how to do (term) ? representational voting
- boundaries of population and geography of vote
- (make) rules for voter participation/qualification in an automated voter system

? known formatting issues that make voting more difficult for the voter?

### (mitigation of insecure local voting headquarters)
- lack of physical voting office
- lack of secure physical voting office
- lack of clarity about voting area or district
2nd step of recording / publishing vote:
Uuid type random key-field
Fuzzy time stamp (month year?) unix epoch

## holding elections in repressed areas not 'allowed' to hold their own elections
- distributed self-organization
- privacy and security
- auditable publication with private information not exposed
- it should be possible for an area to willingly hold an election and publish the results for them to be scrutinized as a fair and due process election without exposing security concerns or identities of any specific people involved
- diasporic communities
- philes? (distributed communities based on projects/interests/views?)
- 

## Managing Elections vs. managing Open-Source Projects
- git
- book ref...

# ?
2. Using a distributed ledgers (blockchains or modified blockchains) to store results:
- e.g. university trusted node anchors
- maybe full-chain so no retroactive?
- slower but more robust?
- smaller number of participants? (or pooled participants?)
- containing hash and voting record?
3. Using smart-contracts to manage processes through elections



#### Possible Multi-factor Authentication Tools:
1. voice print
2. picture of hand (for fingerprints)
3. one time pad
4. specific device tracking
5. device gis location
7. ip / mac address details (vpn issues?)
6. separate confirmation login (to confirm vote record (device, voice, etc.) after it has been processed and recorded)
7. face-selfie (time GIS stamped picture of person casting vote)
8. video of person voting (more secure than static selfie?)
or smaller-file 'encoding' (e.g. auto-encoder) of video of person voting?
9. timestamps? (timestamp plus geolocation?)
10. finger prints
11. wearable bio-signatures?



### Specific Deep-fake and NN-generated-photo detection
- fake account setup
- malicious files (fake or altered pictures for deception)
- user login protocols
- authentication topics:

(plus)
1. public security log data/meta-data to be inspected by anyone about the system
 


# Additional Questions:
1. What additional vote process transparency information should be included with vote results publishing? 
https://github.com/lineality/Auditable_Elections_Projects


#### Case Studies in Election Disruption and Resilience:
- (2020?)

#### Case Studies in Disrupted and Problematic Elections:
(international?)
- 

#### Case Studies in Failing to agree locally on election rules:
-

#### Case Studies in Long Term Technical Design Issues:
- SN https://www.grc.com/sn/sn-914-notes.pdf 


# Goals, Rules, Policies, Procedures, & Methods, Statements (etc.)
Rules-And-Procedures Statements-&-Documentation for Elections

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
- Vote-Office information (location, head?, contact, reporting?)
- Chain of Command within and above Vote-Office


# Rules, Policies, and Procedures
- rules, policies, and procedures for contacting media or watchdogs about suspicious anything (emails, threats, voter intimidation, etc.)
- rules, policies, and procedures for eligibility and voter enrollment
- rules, policies, and procedures for selecting election-staff
- rules, policies, and procedures for voter-registration
- rules, policies, and procedures for per way to vote
- rules, policies, and procedures for election audits (required audits, optional audits)
- rules, policies, and procedures for election-results-challenge
- rules, policies, and procedures for recount (automatic recounts, type of recount, etc.)
- rules, policies, and procedures for overruling-election-results e.g. by gov. branches, evidence requirements
- rules, policies, and procedures for chain of custody of election materials, equipment, etc., Provenance   
- rules, policies, and procedures for announcing and publishing results 
- rules, policies, and procedures for reporting information about the vote: procedures, voter enrollment and participation numbers, etc. 
- Should there be a 'log' of who makes changes to procedures and how?
- rules, policies, and procedures for open and transparent observation of election and ballot counting & processing
- rules, policies, and procedures for exit polls (what collected, from whom, released when)
- rules, policies, and procedures for meetings and correspondence transparency around voting infrastructure and offices and resources
- rules, policies, and procedures for foreign domestic local and internal interference with the attacks on the election process
- rules, policies, and procedures for voter registration
- rules, policies, and procedures for voter identification 
- rules, policies, and procedures for evaluation of best practice, performance, and ethics: standards, guidelines, benchmarks and audit materials
- rules, policies, and procedures for raw vote results (including ranked-choice etc.)
- rules, policies, and procedures for choosing vote calculation method
- rules, policies, and procedures for vote calculation method (e.g. how different numbers of candidates are handled, e.g. 2 vs. not-2)
- rules, policies, and procedures for specific-used vote calculation method
- rules, policies, and procedures for the storage of records from past elections
- rules, policies, and procedures for "stateless" voting machines
- rules, policies, and procedures for election observers
- rules, policies, and procedures for canvassing
- rules, policies, and procedures for advertising
- rules, policies, and procedures for auditing, vetting, and guarantors: items to be audited: ballot counting, whole voting system, audits themselves, security 
- rules, policies, and procedures on best practice
- rules, policies, and procedures on rules
- rules, policies, and procedures on disinformation & nihilism
- rules, policies, and procedures on interactions between separate or connected groups holding elections.
- rules, policies, and procedures for post-election analysis, challenges, and moving on. 




# Best Practice Examples
- never record any private information in an internet or public exposed system, e.g. use a random id.

#### Question: A. What is the relationship between secure end-to-end messaging and voting systems? B. Provenance: What is the relationship between origin-verification of files (including media files) and voting systems?


### Issue/Task: user interface for setting up an election


Q: a standardized .csv ballot format
including information about the ballot
signing key information
possible vote customization information
vote choices
etc.
Q: ways to make sure the .csv ballot is not mis-read or garbled
e.g. maybe including item number, vote choice, and first letter/number of vote choice name in the vote, may prevent arbitrary misinterpretation of votes
Q: possible requiring of ballot being completely filled out
- digital signature etc.
- checksum etc.

## Practical Model 2:
Similar to baseline secure model with these changes:
- allows registered phone number use:
	- ballots can be exchanged by ~sms or 
	- possible voice print ID: e.g. similar to online-voter registration credentials

### Practical Model 3:
Use of block chain ledger

### Practical Model 4:
using nft smart contracts as a framework for parts of the election

practical model 5:
using existing online registration systems

A note on election security and registration security: 
Does it make sense to have lower security standards around registration for voting than casting of votes? A similar or perhaps identical question is: Does it make sense to have a less security system for registration than for voting? E.g. in Pennsylvania in 2022 you can register to vote and change your party-registration, address, etc., on a simple website with no additional security, no MFA multi factor authentication, no personal in face verification, no biometrics, no mailing address sent verification, etc. And I have never heard anyone complain about the insecurity of this registration system, and a proposal to use the same system for voting immediately results in a vitriolic hyperbolic uproar of arm-waving indignation. Personally I think online registration should be more secure. My overall point here is that both registration and voting should be discussed and implemented as they relate to each-other, and not treated as if they are unrelated with inconsistent security considerations. If the standard for security is good enough for registration, that should be the same standard for voting.

# Voting, Contracts, and Smart Contracts:
What are the feasible properties of smart contracts that relate to elections, either for their use in a particular situation or as a discussion to elucidate needs and functions?

# voting office setup: Computer, OS, and Network security
What OS, what network architecture, and what cyber security strategies should/could voting offices use?
- topic: stateless machines
- topic: air-gapped machines
- topic: not-networked Operating Systems
- topic: memory throttling 


# Standards and Measures
- file types
- data types
- calculation methods
- statistical methods 
- disclosure of methods

# Advantages of an anonymized public ledgers of votes:
-

....

# Auditing Election Processes (vs. specific elections):
- operationally defining problems with election procedures
- processes for finding local consensus or agreement on areas of trade-off compromise, or ambiguity (identification, registration, voting age, duration of vote being open, campaign finance, etc.)
- cross regional and international audits
- basic election (not-computer) audit
- computer-electronics audit of election
- security audit
- long term data storage and records audit
- step by step audit of process?

...


# Whole Voting System
- cross-platform
- secure-by-design
- resource-thrifty
- scale-able
- open and audit-able

#### Election Results Analysis

#### Election Inspection

#### Post-Election Audit

#### Specific Vote Plan
- scope of included voters
- scale of data/geography
- hardware needs
- software needs
- level of security

#### Pre-Election Setup

#### Election

#### Post-Election

# Overall Discussion:

## Defining & Systematizing Elections as 'projects' with Agile and Six Sigma

### Why are specific technologies used for voting? 

### What is different about 'electronic,' 'network,' and data structure technologies? (making them appropriate or inappropriate for voting systems)

- In the timeline of technologies, which technologies are appropriate and inappropriate and why?
- (e.g. complete census vs. statistical sampling)

## Tradeoffs in Voting:
- accessibility vs. security
- smaller attack space vs. fancy interface
- direct-vote vs. representational
- ease of vote vs. super-secure-vote
- direct participation by voters vs. time consuming processes

## voting and principles of security (ease of use vs. security etc)
- 

note: RC4 used correctly (discarding early output)
https://en.wikipedia.org/wiki/RC4 


Improvised Network in case of public internet disruptions:
- 

# DNS policy:
- direct DNS with no lookup

# Modes for server posted material that cannot be altered by any command on that server

# Backup signal transmission for areas with disturbances to telecommunications:
- the need for emergency ad hoc EM spectrum signal protocols

# On the operational definition of voting issue and voting choices:

# Preempting issues with NLP (Natural Language Processing) and voting software
- interpretation and ambiguity
- spelling correction

# Ballot Fraud Detection
- Machine Learning and Fraud Detection 

# Minimal Context Specific Design for production deployment, not a general broad scope solution. Reduced attack surface.

# Standardized .csv ballot formats
flat files with no header needed
first column: category
second column: vote item
third column: vote choice

voter id as first row

voter_id_number, voters_number, MY_NUMBER\n
voter_id_name, voters_id, MY_NAME\n
judges, judge_1, MY_CHOICE\n

(standards on documentation)

# Reducing a .csv file to a QR code...
- can a standard ballot sized csv file fit into a .csv file?

# Participant and Rules based process for maintaining and publishing about voting system and election
-  

# on productures, "trust", measures, standards, and ethics


## the importance of open-source for software testing

## Automation and Voting Systems

# Voting Statistic Package
- frequentist
- Baysian
- data analysis
- data visualization
- statistics and machine learning
- decision trees and statistics
- continuous functions vs. classification
- targets of analysis: participation, time-space, security, results, process efficiency, QC/QA reporting, 


# System Health, System Coordination, System Voting

#  Records, versioning, documentations, testing standards

# platform and OS safety policies
- OS update policies
- choice of OS
- 

# passwords, devices, "fido," etc.
- 

# forms of encryption and trade-offs 

# memory management: security

# login management

# Security: Type of attacks that cannot be entirely prevented:
- social engineering attacks
- physical site destruction
- distributed systems vs. centralized systems: e.g. social engineering attacks and the byzantine generals problem, smart contracts, etc.


# Security: Types of 'encryption' that cannot be broken:
- one time pads
- navigation-blind OS
- 


### Voting Logistics and Ethics: Western Chasm
The odd paradox of people in the west believing that voting is inherently good, yet still with the old dark-age-curse never recovered from that views anything 'worldly' as being an evil monster to be destroyed, with the absurd compromise of being willing to live: "in the world but not of it" or some rubbish. Pay attention to what you are doing and do things properly so no one gets hurt, for heaven's sake that is not an evil plot for destruction; it is a definition of responsibility and at least attempting to do what one ought to do.

## Scaling and computational efficiency (big o)

## Managing decentralized (or centralized) projects

## Laws Policies, and Voting-Elections about each-other: 
	- a Matrix With Feedback
	- 


## Forms of democracy and types and structures of elections:
- forms of decision making in history from 'the decline and rise of democracy' book

## Computer Science issues relating directly to practical election system development and deployment into production at scale. 

## Quantifying elections, votes, decisions, agreement, choices

## Visualization of Election Data
- principles
- planning
- monitoring
- results
- reporting


## System Explainability & System Reliability Standardization

...

## The need for a resource-thin framework

Note: https://www.grc.com/securitynow.htm 
SN Episode #873: australian digital driver's license as case study in similar system, not Gibson's certificate based solution 

## Different forms of consensus, representation, and contracts

## Succession

## Methods for Consensus


## Automated Decision Making & Hybrid-Participant (h.sapiens & machine)



## Systematizing, Ethics and Projects in Elections

...

## topics in voter enrollment

## historical debates on voter participation
- John Adams

...

## proportional vs. first past the post

## runoff elections and contracts

## quantum computer challenges to block chains and smart contracts

## identifying issues candidates and choices clearly

## Statistical analysis in error checking of voting data
- Frequentism vs. Bayes
- Feature Comparison in Non-Parametric Models

## Voting systems, governance, and overall sustainability measures


## Election Types, Calculation of Results, next steps based on results

## Quantum Computing, Blockains, Smart Contracts, and Voting Systems: Security Planning
- Are aspects of smart contracts useful for issues such as a runoff where potentially two or more groups of participants are in conflict/competition?

## Voting systems in general:
1. high tech and low tech, voting and information
2. voting in governmental elections vs. voting in any multi-person project
3. voting and definitions

#  languages, character-types(language character sets, UTF8 etc), and voting systems

## Opinion Polls Vs. Elections: What is a vote?
- a history of incorrect pre-election polling
- factors in polling accuracy
- statistics of polling
- analysis of why post-internet polling has been so wrong


## Possible roles of language detection, e.g. election monitoring interference tools
- Can 'junk food language' Be Detected?

## OCR
Where optical character recognition is used, what standards can be optional and in place for how unclear handwriting is handled. Including the question of whether OCR should be avoided.


## General Voting System Study Links (appendix)
- https://www.youtube.com/greymatter/search?query=elections 

## Voting System Design Study Links (appendix)
- https://www.youtube.com/greymatter/search?query=elections 

#### Election Data Study Link
- https://www.datacamp.com/courses/analyzing-election-and-polling-data-in-r?irclickid=TtWxHF0I7xyNUMqzKwUmBUEhUkD3QI3tIzmPW80&irgwc=1&utm_medium=affiliate&utm_source=impact&utm_campaign=2556128 


## Data Visualization & Elections
- https://plotly.com/python/v3/ipython-notebooks/ukelectionbbg/ 
- https://stackoverflow.com/questions/63092441/fast-way-to-visualize-huge-tables-with-dash-and-plotly-python 


# Who: Age Voting Tests and Voter Qualification

#### How should we think about what a ballot is, what it contains, and what it does?
- where it comes from
- id of who fills ballot out
- error checks against incorrect filling out
- disambiguation of content
- error check against incorrect reading
- sufficient identification and verification information
- practical use for size and processing


# Formalized General Processes:
- Is 'voting' parts of another more generalized set of processes?

### coordination disinformation and the byzantine generals problem

Include pre-election polling?
- Voting vs. polling
- representation and statistical representation
- vote by proxy
- exit polls?

#### Ballot design issues:
- question phasing
- choice phrasing
- clarifications of language


# Enrollment, Qualification, Inclusion, Selection
## Variations on Enrollment and Voter-Tests
Q: Are there, in principle, systems that select qualified voters yet which have no 'test' for voter qualification? 
- age test
- local test
- stake-holder test
- 'citizenship' test
- land ownership test
- knowledge of ballot issues test
- 

### Election-Enrollment Edge-Cases:
- families
- institutions
- pre-participants (children)
- post-participants (elderly)


### Modes of Election
- first pass the post
- proportional representation
- run-off
- ranked-choice


### Software Requirements & Security Standards
- Memory Safe Languages: Rust vs. C
- ratio of security problems that are memory management problems


## anticipating hardware attacks
- not all security problems target problems with software


## anticipating social-engineering attacks
- 

### Defining 'Disinformation'
Verification, stem-information, and disinformation
- resources:
- history
-

### election space analysis
- NLP
- matrix formats of election data

#  System Architecture
(see: grc, security-now)
### Trustless Architecture / System design
### Secure by design
### provably secure

### scaling needs for larger elections
scale factors and elections:
- 

### Specific AI-ML issues for voting and coordinated decision making:
- NLP
- disinformation?

### minimal and non-minal software for voting
- is there such a thing as a simple micro-election that can be quick and secure?

#### trade-off in user interface design: secure but use-able
0

### Agile, Security, & Voting: General best practice vs. specific voting system best practice

Q: What do international election inspectors look for?

### Mandate-Based Representation
Perhaps as a form of least-trust architecture, which brings with it perhaps the same 'slow procedural processes' of enhanced verification checking, representation that is limited to specific approved mandates is a historical mode (and one which nearly became part of the US model). 
(see: https://www.amazon.com/Decline-Rise-Democracy-History-Antiquity/dp/B088ZKZDTY/ )
(history: 'fall and rise of democracy' book)

## Disinformation and Elections: Measuring and Modeling Information and Effects
- identifying disinformation
- preventing disinformation
- stopping spread of collapse including disinformation



# Bibliography & Resources

## Books on Elections
#### The Decline and Rise of Democracy: A Global History from Antiquity to Today (The Princeton Economic History of the Western World, 80)
Part of: The Princeton Economic History of the Western World (49 books) | by David Stasavage | Aug 24, 2021
- https://www.amazon.com/Decline-Rise-Democracy-Antiquity-Princeton/dp/0691228973 

#### What You Need to Know About Voting and Why (Legal Expert Series) 
June 16, 2020, 
by Kim Wehle (Author)
- https://www.amazon.com/What-Need-Know-About-Voting/dp/0062974785 

## Books on Analysis & Statistics
#### 
(Maybe Nate silver book signal noise)
https://www.amazon.com/Signal-Noise-Many-Predictions-Fail-but-ebook/dp/B007V65R54
 
#### Escape from Model Land: How Mathematical Models Can Lead Us Astray and What We Can Do About It
by Erica Thompson (Author)
Publisher ‏ : ‎ Basic Books (December 6, 2022)
https://www.amazon.com/Escape-Model-Land-Mathematical-Models/dp/1541600983/
note: comments on nate silver, comments on election results, but not a rigorous analysis.

## Modeling and Elections
- tests vs. models
- representation and region of vote (jerimandering or not)
- election observation and inspection
- election prediction

## Data Diversity Modeling and representation
Invisible Women: Data Bias in a World Designed for Men
by Caroline Criado Perez | Mar 2, 2021
https://www.amazon.com/Invisible-Women-Data-World-Designed/dp/1419735217

## Books on Secure Computer Systems & Networks
#### [case study] Sandworm 
Sandworm: A New Era of Cyberwar and the Hunt for the Kremlin's Most Dangerous Hackers
by Andy Greenberg, Mark Bramhall, et al. 
Hardcover – November 5, 2019
- https://www.amazon.com/Sandworm-Andy-Greenberg-audiobook/dp/B07RGRTZM6/ 

#### [excellent history of early internet] We Are All Targets: 
How Renegade Hackers Invented Cyber War and Unleashed an Age of Global Chaos
by Matt Potter, Matthew Waterson, et al.
https://www.amazon.com/We-Are-All-Targets-Unleashed/dp/0306925737 

#### 
( Cult of the dead cow )

#### 
( A people's history of Computing )

####
( Enigma, while ostensibly this is a biography of Alan Turing, it is one of the best books on applied history of signal security and computers)

####
NLP in action 1st ed

####
NLP in action 2nd ed

Deep Learning with Python, Second Edition
by Francois Chollet | Dec 21, 2021
https://www.amazon.com/Learning-Python-Second-Fran%C3%A7ois-Chollet/dp/1617296864/

## Books on Product Development
The History of the Future 
by Blake J. Harris, Stephen Graybill, et al.
https://www.amazon.com/History-Future-Facebook-Revolution-Virtual/dp/0062455974/

- open source study book...title? (no starch?)

## Other Books
(Virtual Society)
(maybe book on data intensive systems)

## Books on Project Management
( )

## Web Resources:

#### C.G.P. Gray on Elections & Voting Systems 
- https://www.youtube.com/@CGPGrey/search?query=elections 
- https://www.youtube.com/@CGPGrey/search?query=voting 


#### Case study in password handling:
- https://twit.tv/shows/security-now/episodes/905 
- https://twit.tv/shows/security-now/episodes/904 
- alternate source episodes 904 or 905: https://www.grc.com/securitynow.htm 


#### On Memory Safe Languages (note still actively evolving time-lag and shift to topic, google press release is old, action taken to adopt RUST is new). 
- https://twit.tv/shows/security-now/episodes/906 
- alternate source episode 906: https://www.grc.com/securitynow.htm 


### Election Case Studies (section not complete)
- eastern Europe and Russia
-- post wwii
-- post 1989


## Articles:
- https://www.wired.com/story/ranked-choice-voting-reveals-the-weird-math-of-elections/ 


