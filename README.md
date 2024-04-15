##### Online_Voting_Using_One_Time_Pads

# Decision Coordination: General and Specific
## Voting, Decision, & Consensus Systems in Networks and in General
#### Project-Context Decision-Making Involving Participants and Components

# Contents: 
## Part 1: Secure Online-Voting in-Principle
## Part 2: Practical-&-Secure Online-Voting
## Part 3: Whole-Election and Vote-Analysis Platforms
## Part 4: Generalized Decision Coordination
- https://github.com/lineality/object_relationship_spaces_ai_ml 
- https://github.com/lineality/definition_behavior_studies 
### Bibliography & Resources

# Clarifying Goals and Questions:  
- Main Goal: Systematize secure online voting.
- Main Questions: 
#### 1. Is secure-auditable online-voting possible in principle?
#### 2. Is reliable online-vote-result-publishing possible in principle?
#### 3. Can election-processes and election-results-publishing be feasibly, sustainably, pragmatically, realistically, implemented given real world limitations on resources? How is security measured? What specific measures are required for security to be sufficient?
#### 4. What are differences between ideal-maximum-security-systems on the one hand and on the other hand sufficiently-secure, realistically-accessible, and realistically-feasible / practical-to-implement systems? (e.g. a perfect system vs. a good system, or "not letting the perfect be the enemy of the good")


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


## Peripherally Related Questions:
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

- Rule/Assumption 3: Empirical tests, hypothetical tests, and security checks should be done to demonstrate how this (or any) voting system measurably succeeds or measurably fails to work. In some cases falsifiability may need to be a criteria for types of requirements for voting and coordination systems.
[E.g. "I just like it." or: "I just don't like it." or "It must (or must not) have undefineable_property_X." are not sufficient reasons to use or to not use a given voting process.]

- Rule/Assumption 4: Voting issues must be definable and defined in measurable and testable ways. E.g. If this system does work, disinformation will be used to prevent it from working. 

- Rule/Assumption 5: If the context is critiquing the mechanics of casting/submitting ballots and votes, then a failure to agree on design and rules for an election (e.g. doing a run-off or not doing a run-off, how proportional representation is, etc.) should not be considered relevant to the context of submitting a ballot. (E.g. complaints about how votes are counted (or ignored) should not be used as an argument against secure methods to (the context of the mechanics of) casting/submitting ballots and votes.)

Question: Design Questions: 
- printable-document format vs. .csv format?
- reading document
- storing document
- converting document
- character sets allowed...
- csv., dataframe, tensor
- rsv format? (rows of string values)
- file and directory delimited values
- 


## Steps (For Conceptual-Ideal Election)

#### Step 1: (During in-person Voter Registration: start registration [not-over-a-network/not-online]:) 
Before the election ends: A person, e.g. in-person, with ID (identifiable as an eligible voter according to local rules), goes to the Voting-Office to register for the vote-over-a-network (with One-Time-Pad) (online voting) process. 

(Note: There is a system-design-choice to allow (or not) registration for more than one election. This issue can be related to the format/type of the submitted ballot. For example: 
#### A. ballots that have been (or can have been) designed at the time of registration, and 
#### B. Standardized or truncated ballots containing just choices and not all the text of the ballot (possibly a choice (e.g. choice number) and the initials of the person's name as a second factor) and 
#### C. whether whatever form of ballot is customized for each voter (e.g. with a custom-id, verifiable as going to and coming from that one voter) or whether the ballot is standardized (and verifiable as the standard ballot for that election or more standardized) )

#### Step 2: (During in-person Registration: Make one-time-pads.) 
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

(Note: possibly the validity of the ballot could or should be checked during both steps)


#### Step 9: (Complete/Mark/Fill-in the Ballot with Vote-Choices [not-over-a-network/not-online]) 
The voter, not-over-a-network/not-online(using pen and paper), fills out the ballot (selecting their vote choices). (Details here may be important in some way: filling in a circle, selecting an option number, multi-factor, non-over-under-voting checks, etc.)


#### Step 10: (Digitize the Completed Ballot not-over-a-network/not-online] ) 
The voter, not-over-a-network/not-online (enforced by software), scans (e.g. by taking a picture) the completed-filled-in paper ballot, creating not a photo but a document or table of information (so that the one-time-pad can convert character by character). 
(Note: maybe some kind of mono-space font and dashes between lines to avoid spacing errors?) 


#### Step 11: (Check Completed-Ballot for Errors [not-over-a-network/not-online]) 
The voter confirms that the information in their (the voter's)  electronic scanned ballot is the same as the paper version of their (the voter's) filled out ballot. (Checking for errors.) (Note: Automated processes for checking ballots for standard mistakes.)

~ Step: An optional but recommended intermediate step here is to have a 3rd set of not-over-a-network/not-online-only software that will check the ballot before and or after it is filled out by the voter, such that this additional set of software can check for the "overvoting" (voting for both candidates) and "undervoting" (voting for neither candidate) issues as a safeguard (against accidentally-incorrectly filled-out-and-submitted ballots) and that perhaps Nevada has used successfully. 

Question: Is there a way to optimize OCR? e.g. letter per box format? Alternatives to OCR?
- various ocr applications that can be used
- open source
- safety, reliability issues

#### Reference: 
"Roll Off at the Top of the Ballot: Intentional Undervoting in American Presidential Elections"
December 2003 Politics & Policy 31(4):575 - 594
DOI:10.1111/j.1747-1346.2003.tb00163.x
Authors: Stephen Knack & Martha Kropf
University of North Carolina at Charlotte
https://www.researchgate.net/publication/227617394_Roll_Off_at_the_Top_of_the_Ballot_Intentional_Undervoting_in_American_Presidential_Elections 
(end of reference)

Another ~'multifactor' check may be to both mark a vote-choice on the ballot also and give some information about that choice, e.g. mark candidate 2 and in a second field enter the first letter of that candidate's last name. If these do not match, the voter should be alerted to check their ballot selections.
The voter, not-over-a-network/not-online(enforced by software), scans (e.g. by taking a picture) the filled-out paper ballot.  
(Question: ...print formats...)


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

Question: How much data can a QR code contain? 
Question: How redundant can a QR be for error-correction?

Question: Other pros and cons of qr codes?

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

21. A bad-agent will use disinformation.

22. A bad-agent will attempt to disrupt infrastructure that the election relies upon (electricity, post office, transportation, new-media, schools, etc.).

23. A bad-agent will attempt, or otherwise effect, the disruption or prevention of the study and communication of the security, data-hygiene, or safe-use, etc., of a feature, product, item, use, context, noun, verb, etc. 


(note: There are bad agents but there are also other cases and factors which at times should not be confused with bad agents. For example a tester/developer whose goal is to find and fix issues working with other developers is not a bad agent. There are various appropriate and inappropriate factors in different contexts, not everyone can be divided into bad agents and innocent users. And the details and edge cases can become tricky to manage clearly and optimally. )
see book references


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

- military overseas are another important group of voters who are both not physically able to travel overseas yet often close to bodies of administration and organization who can facilitate voting.  

# Security Section
### Additional steps can be taken to increase security. 
#### For example: 
1. To reduce the possibility that local staff will accidentally connect to the internet or run the software on insecure or already compromised hardware, it should be possible to create a cost effective system where staff will run a custom made operating system (custom BSD or Linux or FreeDOS, etc.) that lacks the ability to use the internet. It may also be possible to use cost effective hardware such as a raspberry pi or microcontrollers. There may be safety advantages to using micro-controllers that lack overall computer abilities and thereby lack security risks associated with those.

2. Put safeguards into the software to at least try to prevent using the same one-time-pad more than once. 

3. Known issues and areas:
- memory issues: use memory safe languages
- fonts: restrict and regulate character-set use
- communications and fishing: don't use insecure systems such as email, SMS texts, http, ftp, etc.


## Unique Ballots
At this time or at a later time [a printed copy of a unique ballot] (depending on choice, timing, etc. (e.g. if the ballot has been decided which is often not the case at the time of voter registration or if in terms of security level if the voter does not trust a physical breakin of the vote office and wants in advance a verifiable ballot) (not-over-a-network/not-online) a printed copy of a unique ballot (e.g. containing if not the voter's name the equivalent of a sha256 hash of the unique ballot). Either a unique ballot or a unique ballot identification number will be used on both ends, by the voter to check that the ballot they receive is authentic and by the office that the ballot received completed and sent by the voters is authentic. (Note: some combination of a 'signed' public ballot and a signed sender/recipient may also be possible)
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
Question: Is there a lower-tech version with reasonable security for geographic locations with limited resources?

Often fewer features and narrower footprint and attack-surface increase security, but in a system starting entirely with paper and pencil, in this case the meaning of 'less' may require more explanation. 

Details: The first part of this report is a more abstract proof-of-concept about whether one-time-pad voting over a network is any less secure than one-time-pad secured voting over-a-network. However, in reality actual voters and voting-offices may refuse to use an ideal secure voting system (for reasons legitimate or illegitimate). It is entirely within keeping with computer science that there are multiple possible solutions to a problem, and while one solution may be perfectly fine in theory it is simply not practical or feasible to implement (often: requiring too many resources (including time as a resources), either relatively too many (resources-required) compared to another solution or too many as in that requirement simply cannot be met with known technology (e.g. taking a length of time longer than the age of the universe to solve the problem: in principle: problem solved! in practical reality: problem not solved.)). There should be a discussion of what a good-enough solution is, and how a good-enough solution may meet the practical demands of users. 

- focusing on accessible technology

## Entropy randomness and pseudorandomness
- for security
- for parts of system
- security and Turing-entropy units
- standards for pseudo random numbers...given different mobile computer hardware. collecting entropy?
- version checks: a way for users to see what version of software is being used...
- decentralization and security: does distribution lack a middle for man-in-the-middle attacks?

### Fingerprinting
- how to give voters anonymity while also allowing them to connect



# Part 2: Practical Secure Online Voting
### Goal: Practical version of 'online voting' for realistic implementation
('online voting' is likely an easy to understand common term for a more general and abstract process of automated networked project decision coordination with broad applications.)

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

Q: double signed interaction, with public and private key from both parties...
from the 'election' to show you were allowed to vote (unless open to anyone)
and verified by voter...
...maybe during remote registration...
a swap of confirmed signatures..
Q: who is who over network...

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



#### Topic/idea: use of one time pads plus signing signatures
#### use and issues with signing certificates
#### feasibility of one time pads: attack surface of initial sharing

#### Notes:
- individual permission drop-off folders (cloud storage like S3)
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

(Question: How reliable is OCR? Is OCR reliability an issue? Is this a strong argument for all-digital and no-conversion process? (can still be printed or saved records etc.)

A short-form or truncated ballot may contain:
e.g.
- the number of the option-choice and perhaps 
- a first/last letter in the candidate's name (which could also serve as a check, similar to an empty choice check, if the name-letter does not agree with the number option). 
(also a check against a vote left empty?)
Note: Write-in may be an issue for the truncated ballot. 

#### Note: Ways to make sure a one-time-pad is not being used a 2nd time...a log of already used one-time-pads to check against...?...or a small hash?

The idea of a non-recoverable system, disposable, that you would restart if something went wrong, but no back-doors, side doors, etc.
voter...re-register...multiple registrations?

note: https://sqrl.grc.com/pages/getting_started_with_sqrl/ 

Question: one time pads vs. signing keys for transmitting ballots
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
Question: id such as biometric data?

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
- too few for multiple selections, possiby make vote choices clear so that one selection is required for each question.
- test-process errors (something breaks processing)


#### Step 8: (Encrypt the Completed-Ballot [done by voter]) 
Details depend on the file system being used.
Question: If an anonymized blockchain system is used, is there a need to encrypt the submitted ballot? e.g. could the ballot have an anonymized id?


#### Step 9: (Voter Submit encrypted-ballot over network) 
Question: recommended methods?
Some kind of MFA? 
immutable ledger system?
	- frozen ledger (duplicated with hash checks)
	- dynamic ledger 
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
- what to anonymize?

#### Step 13: (Publish Full Election Report)
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
#### Question: Background tests and checks during the whole process?

#### (election-results publishing...parts of process)
- for whom
- overview
- winners according to rules?
- types of analysis
- description of system
- open source code

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
1.  secure messages between office and voter? (one time pad?)
2.  secure voting platform (receive ballot)
2.1 voter registration
2.2 send or assign ballots
2.3 fill out ballot
2.4 submit ballot
3.  Processing votes
3.1 receive votes
3.2 validate votes
3.3 decrypt votes
5.  process votes
6.  produce results report
7.  schedule election
8.  publish results report
9.  automation of parts and all parts of elections
10. elections including/between non-human project elements (AI)


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

### Question: Known formatting issues that make voting more difficult for the voter?

### (mitigation of insecure local voting headquarters)
- lack of physical voting office
- lack of secure physical voting office
- lack of clarity about voting area or district
- 2nd step of recording / publishing vote:
- Uuid type random key-field
- Fuzzy time stamp (month year?) unix epoch
- decentered data storage
- decentered decision making
- decentered feedback and analytics

## holding elections in repressed areas not 'allowed' to hold their own elections
- distributed self-organization
- privacy and security
- auditable publication with private information not exposed
- it should be possible for an area to willingly hold an election and publish the results for them to be scrutinized as a fair and due process election without exposing security concerns or identities of any specific people involved
- diasporic communities
-"philes"?(sp?) (term Neal Stephenson term? distributed communities based on projects/interests/views?)
- 

## pros and cons of methods of vote tallying:
- decentralized vote handling...
- 


## Managing Elections vs. managing Open-Source Projects
- git
- book: "Working in Public" by Nadia Eghbal, Stripe Press
- studies of 'tragedy of commons'

## ...
2. Using a distributed ledgers (blockchains or modified blockchains) to store results:
- e.g. university trusted node anchors
- maybe full-chain so no retroactive?
- slower but more robust?
- smaller number of participants? (or pooled participants?)
- containing hash and voting record?
3. Using smart-contracts to manage processes through elections


#### Possible Multi-factor Authentication Tools:
(how much the system is data-slim... e.g. ascii cli vs. 
multi-media gui bloated)
1. voice print
2. picture of hand (for fingerprints)
3. one time pad
4. specific device tracking
5. device gis location
7. ip / mac address details (vpn issues?)
6. separate confirmation login (to confirm vote record (device, voice, etc.) after it has been processed and recorded)
7. face-selfie (time GIS stamped picture of person casting vote)
8. video of a participant(person) voting (more secure than static selfie?)
or smaller-file 'encoding' (e.g. auto-encoder) of video of person voting?
9. timestamps? (timestamp plus geolocation?)
10. finger prints
11. wearable bio-signatures?
12. language use metrics...(unique to person)


### Specific Deep-fake and NN-generated-photo detection
- deep-fakes / cheap-fakes
- fake account setup
- malicious files (fake or altered pictures for deception)
- user login protocols
- adversarial input to automated systems(in sense just like SQL injection attacks...but SQL never being used in particular)
- GPT LLM concerns (be specific)
- authentication topics:

(plus)
1. public security log data/meta-data to be inspected by anyone about the system


# Additional Questions:
1. What additional vote process transparency information should be included with vote results publishing? 
https://github.com/lineality/Auditable_Elections_Projects

### scale and decision making

## process indeterminacy and iteration in decision making

## Japanese vs. American decision making

## Case Studies:

#### Case Studies in Election Resilience to Disruption:
(related issue: geopolitical violence & cybercrime?)
(types of sources, books, articles, news...)
- Estonia?
#### Books: 
"we are all targets",
"sandworm"
"Fancy Bear Goes Phishing"
"people's history of computing"
"cult of the dead cow"





#### Case Studies in Disrupted and Problematic Elections:
(international?)
- 

#### Case Studies in Failing to agree locally on election rules:
-(Q: how far back in time?)

book: the fall and rise of democracy
- interesting group-organization models study

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
- rules, policies, and procedures for "stateless" voting machines (as in computer-state, memory-state, configuration-state (not political))
- rules, policies, and procedures for election observers
- rules, policies, and procedures for canvassing
- rules, policies, and procedures for advertising
- rules, policies, and procedures for auditing, vetting, and guarantors: items to be audited: ballot counting, whole voting system, audits themselves, security 
- rules, policies, and procedures on best practice
- rules, policies, and procedures on rules
- rules, policies, and procedures on disinformation & nihilism
- rules, policies, and procedures on interactions between separate or connected groups holding elections.
- rules, policies, and procedures for post-election analysis, challenges, and moving on. 
- rules, policies, and procedures for initiating an election
- rules, policies, and procedures for scheduling


# Best Practice Examples
- never record any private information in an internet or public exposed system, e.g. use a random id.

- managing open source development best practice

#### Question: A. What is the relationship between secure end-to-end messaging and voting systems? B. Provenance: What is the relationship between origin-verification of files (including media files) and voting systems?


### Issue/Task: user interface for setting up an election


Question: Standardized .csv ballot format (for decision coordination): ideal?
including information about the ballot
signing key information
possible vote customization information
vote choices
etc.
Question: ways to make sure the .csv ballot is not mis-read or garbled
e.g. maybe including item number, vote choice, and first letter/number of vote choice name in the vote, may prevent arbitrary misinterpretation of votes
Question: possible requiring of ballot being completely filled out
- digital signature etc.
- checksum etc.


## Data Formats Data Structures externalization serialization and read-able serialization
- it may be important for data structures such as dictionaries of lists (to use the python terms) to be able to be exteranlized,shared and loaded and stored in a read-able printable format.
- non-transparent, non-inspectable, none-step-trace-able formats may be optimized for computation but not suitable for a system where communication is the highest priority
- externalization without binary serialization
- maybe field length and type meta-data handling


## automating speaking time at debates?
- 

## types of bytes in coordination data
- pre-empting type conversion issues


## Practical Model 2:
Similar to baseline secure model with these changes.
1. allows registered phone number use:
- ballots can be exchanged by ~sms or 
- possible voice print ID: e.g. similar to online-voter 
- registration credentials

### Practical Model 3:
Use of block chain ledger

### Practical Model 4:

speculation: ways of using smart contracts as a framework for parts of the election?
Is technology mature enough?
Security issues?

### practical model 5:
Using existing online registration systems

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

## Data types, datatypes
- defining datatypes
- where data must be type specific
- where data must NOT be type specific
- the adjective-pejorative of 'objects' as "custom data-types"

# Advantages of an anonymized public ledgers of votes
-


## Different strategies for immutable data structures
- race conditions (term?)
-


## Coordinating Data and Data Structures in Systems for Decision Coordination:
- compatibility across:
-- storage formats
-- data types

- size-management 
- parallelism
- concurrency
- mutability
- secure by design
- graphs
- quantizing (of floats)
- externalization
- graphs (the data structure)
- 

Networks vs. Databases:
- Why is data-coordination solved for networks but seen as unsolvable in single databases?
- 
- GC garbage collection, database 
...

Design Factors and Compromises

...

General Participation & The Health of Systems
2024.01.06
The shift from a simple set of goals into a set of goals much more affirmatively focused on protecting participation, communication, and coordination among diverse participants in a society. 

This set goal could be stated as: Use STEM based methods and policies to help defend against disruption and collapse of communication and coordinated decisions in and across diverse groups and perspectives in project-complating societies with general participation of members. 

...

## Participation Rules
- 36 years as required age of person to be able to be elected
(issues around this)
- alternatives to age for fitness measures

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

## incentives and long term incentives
- 

...


# Whole Voting System
- cross-platform
- secure-by-design
- resource-thrifty
- scale-able
- open and audit-able

# Tool areas: whole voting system tools


#### Election Results Analysis

#### Election Inspection
- tools
- measures
- tests
- automation

#### Post-Election Audit

#### Specific Election Plan
- scope of included voters
- scale of data/geography
- hardware needs
- software needs
- level of security

## Open Systems
- FOSS
- MIT or other licensing for parts of system
- the topic of 'security by obscurity'
- organizing testing of system

#### Pre-Election Setup

#### Election

#### Post-Election

# Overall Discussion:

## Defining & Systematizing Elections as 'projects' with Agile and Six Sigma

## what are various either easily or not-easily measured goals and problems or errors for coordinated decisions?

### Why are specific technologies used for voting? 

### What is different about 'electronic,' 'network,' and data structure technologies? (making them appropriate or inappropriate for voting systems)

## Demand Distortion and General Coordinated-Decision (voting) Spaces
	- learning
	- collapse
	- compassion

- In the timeline of technologies, which technologies are appropriate and inappropriate and why?
- (e.g. complete census vs. statistical sampling)

## change state coordination signal STEM
- novelty in formal systems
- how new ideas enter into systems
- how disinformation destroys everything


## Tradeoffs in Voting:
- accessibility vs. security
- smaller attack space vs. fancy interface
- direct-vote vs. representational
- ease of vote vs. super-secure-vote
- direct participation by voters vs. time consuming processes

# History of Voting and Coordinated Decision Making
- (book, fall a and rise of democracy)


# Security & Data / Information Hygiene
Voting and principles of security (ease of use vs. security etc)

## General vs. Deployment

#### Note: RC4 used correctly (discarding early output)
- https://en.wikipedia.org/wiki/RC4 

## Improvised or ad-hoc Network in case of public internet disruptions:
- mesh?

# Fancy Bear goes Phishing, Broadband, People's Computing (sp?): Some kind of study of social-ecology and technology, or culture and technology, or 'upcode' or...how low level and high level have to merge in projects -> as relates to coordinated decision making and voting


# DNS policy:
- direct DNS with no lookup
- dns over https...

# Modes for server posted material that cannot be altered by any command on that server

# Backup signal transmission for areas with disturbances to telecommunications:
- the need for emergency ad hoc EM spectrum signal protocols


# measurements for disruption distortion and collapse


# Micro Signal Coordination
Cellular vs. Macro level for:
Conditional Expression and Signal Gaps: General Signal Processing And General Instruction Management
1. 'Artificial' Neural Networks and Neurons vs. Biological Signal Systems
1.1  History
1.2  Future
2. Chimeric Conditional Expression of Genetic Stored Instruction
2.1  Optional Genome Pathways
2.2  Optional Information-Signal Pathways

## Mandate Mixtures
How about a system where a candidate who get's less (or perhaps more too) than a given percentage is required to operate on a mandate system with mandates coming through a proportional consensus system kind of like a parliamentary coalition. 


## Layers of language and collective symbolism


# Whistleblowing


# is there a general space of process errors
for system of coordinated decisions on processes?
## discipline specific project-task contexts:
- six sigma
- systems engineering
- medical
- education
- 


# How much does a decision/Election Cost? 
Process Duration / Resource-Cost
How long can and should it take for an election to be organized, carried out and reported on, now including any arbitrary window allowed for extra voting (e.g. you could hold a vote open for 5 years, but that doesn't mean it takes 5 years to count the votes and publish).

How minimal and efficient can an election be?
How should this be measured?
Time window for setup
Time window for election
Time window for analysis and reporting
person-hours to set up
electricity cost
...computer cycles to computer per scale?



# On the operational definition of voting issue and voting choices:


# Applied-Algorithms: Efficient computation of ballot processing
- error checking
- parallel and concurrent processes
- security of process
- auditability of process

## short term and long term
### Detection of short term and long term problems
- short cycle bubbles (fewer than 5 years)
- indefinite embedded long term problems 



# Preempting issues with NLP (Natural Language Processing) and voting software
- interpretation and ambiguity
- spelling correction


# Ballot Fraud Detection
- Machine Learning and Fraud Detection 


## various kinds of disinformation relating to coordinated decisions:
- inability to tell what is computer generated vs. real (may not be a deliberate attack, e.g. misunderstanding of ~art found online)
- adversarial attacks on AI


## clear-enough definitions and feedback: ways to find out if a plan is practical or if it is overly chaotic and burdened by communication-failures.

## System failure and system collapse
- non-erronious-external-locus-of-control perspectives
- failures that obstruct or impede coordinated decisions
- learning and failure repair


## long term data storage
- sustainability and succession: long term data management
	- chain of future control
	- future cost structure
	- plan for updating an information going stale (e.g. Malissa co.)
	- managing archived historical data vs. current
	- historical data
- reasons for keeping historical data
- data about process

## Evaluation Types:
- Daniel Khanemann: Evaluate the process not the outcome.



## realistic efficiency:
- web applications are usually designed with very strange goals that make the overall process extremely brittle, expensive, and unsustainable, in order to chase fetich-goals with little or no real value (fancy UI, high speed)
- election system should be robust with no added features that are not absolutely needed: few dependencies, secure, 


## location: on edge, on premise, distributed, server, and cloud
- case studies for distributed systems?

# Data Hygiene and Voting


# Minimal Context Specific Design for production deployment, not a general broad scope solution. Reduced attack surface.

# Standardized .csv ballot formats
flat files with no header needed
first column: category
second column: vote item
third column: vote choice

## different uses of high and low resolution data and metrics, test, etc.

## decisions and disturbance regime management

voter id as first row

voter_id_number, voters_number, MY_NUMBER\n
voter_id_name, voters_id, MY_NAME\n
judges, judge_1, MY_CHOICE\n

(standards on documentation)

# Reducing a .csv file to a QR code...
- can a standard ballot sized csv file fit into a .csv file?

# input and clarity standard: a very long and vague story that needs to be very brief and clear: what are symbols and what gets printed?


# Privacy and anonymity: "When Hashes Collide"
uses of hashes for statistical usefulness for behavior patterns for statistically anonymous for identifying specific people. 
 Episode #940 | 19 Sep 2023 | 104 min.
https://www.grc.com/sn/sn-940.txt
https://www.grc.com/sn
Episode #940 | 19 Sep 2023 | 104 min.When Hashes Collide


# process and step definition across integrated sub-steps with break-down into smaller steps


## cost factors & sustainability
- low level costs
- database related costs
- server related costs
- managed-services related costs
- dev-time related costs
- future-replacement related costs
- time-planning costs
- high level costs
- incentives for participants: do any participants have an incentive to dismantle the entire system and or the providing of user-needed services? (e.g. upgrading the system to better meet the needs is not bad, but dismantling and upgrading can become ambiguous, as with the 1990's bank-mergers the closed down banks of the closing of local newspapers, was that optimal to meet user needs? (on the other hand, keeping an ineffective operation going for the sake of it (stalin's regime?) is also not a good option)


## details of confirming voter choice datatypes:
string check
float check
int check
boolean check 
none check

list check
	string check
	float check
	int check
	boolean check 
	none check


dict check
	string check
	float check
	int check
	boolean check 
	none check

set check?
tuple check?


# definitions of criteria in tests

## Empirical Tests for Voting Systems

## Empirical Process and Coordinated Decisions: 20203.09.25
1. applications of quantizing vs. infinite
derivation and integration of process modules
2. von Neumann's bifurcation of roles in self-replicating processes



# Participant and Rules based process for maintaining and publishing about voting system and election
-  

## universal requirements?
1. Externalize, Show work: show all your steps.
2. Be clear about your project-context.
3. check your work / peer checking
4. revise your work
5. match results to project-target (must fit)


# on productures, "trust", measures, standards, and ethics



## the importance of open-source for software testing

## Automation and Voting Systems

## automated testing to checking functioning of system
- 
- accurate processing tests
- security tests
- parts of system for testing:
- types of tests
- role of quality random and pseudo random numbers
- clock problems and clock accuracy in voting network

## Time Databases and Coordinated Decisions
- race conditions
- syn
- decentralized systems and time
- large scale systems
- affordable time sources
- type types: monotonic
- delayed source UTC
- Astronomical and off-planet time
- 


## Using Technology (including NLP-AI) to search and explain about voting topics, ballot initiatives, and issues connected. etc. e.g. All the issues related to a water-regulation change and what might be affected in the short and long term.


## priorities in coordinated decision networks and databases:
- atomicity
- 'linearity'
- serializability
- fault tolerance or fault reaction
- redundancy
- scale 
- speed

## architectural problem spaces 
- different types of problem-spaces with decentered coordinated decisions vs. centrally handled
- how many parties are coordinating
- synchronous, asynchronous
- state or stateless (as in memory, not gov) 

# risk and worst case scenarios

## standards for describing feasibility and clarity

## how are specific coordinated decision tasks and sub-tasks defined, so as to automatically evaluate if that task has been done correctly?

### What is a balanced architecture between various factors?
- centered decentered
- private vs. accessible
- public vs. ownership
- communication vs. encryption


## clarity on divergent project agendas

## Taboos and Prohibitions that may interfere with voting
- 

# Analysis Section
- reification and randomness in patterns, from 'elimination' contest artificiality to Kahneman business and market randomness illusions. 
- applications to fitness of persons
- applications to clear language used
- applications to issues and options
- applications to best practice operations (for voting and for what is voted on)

## Locus of Control
- psychology of external locus of control


## Learning from history: How mistakes can be learned from to improve voting

## Decision process task size:
- for breaking down and building up larger election processes


## Ascii vs. Diversity: balancing universal tools with universal users
- 

# Voting Statistic Package
- frequentist
- Baysian
- data analysis
- data visualization
- statistics and machine learning
- decision trees and statistics
- continuous functions vs. classification
- targets of analysis: participation, time-space, security, results, process efficiency, QC/QA reporting, 
(see Daniel Kahnemann's book on 'Noise')

# Defining "Technology" for coordinated decision making including elections


## Measurement and Modeling in Coordinated Decisions
- thinking fast and slow
- game theory
- NLP
- blockchain contracts

## Disagreement
- game theory
- Von Neumann vs. Nash

# The importance of setting properties of default empty states
- empty functions
- empty lists
- empty values
- empty signals

# technical debt and choice that increase difficulty

# System Health, System Coordination, System Voting

# functional categories of signals for decisions:
	- (see hofstedter-gap)

## Standardization:
- re-use of functions and modules
- read-ability, serialization, encryption,and anonymization of data

## Decisions elections and types of questions

## confronting antisocial behaviors, disinformation, and collapse 
- e.g. when it masquerades as 'culture' 'tradition' etc.

## forms and formats of data
- size
- redundancy
- anonymized
- statistically identifiable (when hashes collide) 

## signal-game spaces
	- where speed is needed
	- where speed is not needed
	- where retries are needed
	- inverse of need: prohibited


#  Records, versioning, documentations, testing standards


## operationally defining freedom for free elections: see
From Sin-obsessed-authoritarianism to Naive-rebellion-revolution to 1970's denial-ism, to 2020-Information-War from/in
The Spirit of The Code
From Science to STEM: The State of Nature, Natural Law, Montesquieu, and Edmund Burke: Edmund Burke, Jeffrey Hinton, and the Evolution of STEM in Culture and AI-Computer-Science in Practice
2024.02.20-22

## long term infrastructure costs

# platform and OS safety policies
- OS update policies
- choice of OS
- factors
- specific cases
- minimal
- secure
- specific standards and tests


## Time, stages, directions, models, perception:
- Where do problems occur?
- WHere do miscommunications occur?
- Where do some models or linear math have no time aspect?
- Is there schedule-indeterminacy?
- 


## interconnected decision events
- interaction and feedback


## contraction of systems
- cases
- measures
- models
- spread, contagion


## STEM and Coordinated Decision Making
- decisions and coordinations in:
-- networks
-- databases
-- instruction/data interactions and conflicts
-- cryptography
-- communication theory ('information theory')

## 
quantized or fractional(fractal) dimensional representation
of groups of participants in proportional representation
or in category or finite choice selection


## decisions, logic, and quantization(numbers)
- defining current-time outcomes
- defining future targets
- defining 'past' known data (states of being unknown etc)

# Ballot item interpretability:
- deterministic (given time as input)
- discrete responses
- issues with open ended 'write-in'


# Alternate Solutions

Equivalence and Non-Equivilance in representation of situations and choices.


# Factors in multipoint coordination problems, from signal mcu to project content
- distributed mcu
- network design
- resiliency
- security
- error correction
- 

## Data and Illusions:
coordination decision systems need to set up in such a way that data and a tether to reality are able to keep in check and prevail over the tendency towards illusions and coverups and in potemkin villages.
Literally or provebially software since 1970 has been a self-conspiracy among compacent developers who prioritize their won recreation and enterinament experience over reality and the effects of the software they create to result in a space-trash 'poluted' environment of hidden problems where the priority is lipstick-on-a-pig fads and pedantic distractions. Developers spend huge amounts of time entertaining themselves with the 'self-care' of beautifying their keyboard and beautifying their desk and beuatifying their beackgorund and beuatifying editor/IDE and beautifying their 'self commenting' code, and creating the fun-illusion of their own personal entertainment pleasure seeking experience, complete with the fun of being a bullying manager, the fun of randomizing other people'schedules, blaming interns for the problems of senior staff etc, enjoyably, defiantly defying basic Agile project management areas and being a coder cowboy bro rockstar. The result is very predictably ruin and toxification, which is predictably (potemkin village) hidden away and covered up with more lipstick and distraction beautification, blaming down hill, wasting more time on entertainment junkfood and 'self-care.' By analogy, coordinated decisions and elections may be able to work well or fail to work well around similar criteria. 


## tests, data, and diagnostics for functions and sets of functions and tasks
- testing coordination systems
- eligibility tests for human participation
- security tests for hardware and software
- performance tests and diagnostics
- design and process tests
- 'test' vs. feedback and use-able data

## meaning and multilingual elections
- automated translation
- merging on slightly differently translated voting options
- translation of instructions and procedures (automated options

## dimensionality and statistical representations
- in various cases what we want from decision data are 
lower dimensional representations of higher dimensional structures
represented by low-dimensional language data from the participants
this also may trace a distinction between vote/decisions that can 
be clearly defined as simple choices, that can elusively be defined,
or decisions that cannot be reduced to binary or classification
choices

# Distributed Servers and modularization of process
- time modules
- data size modules
- 


## Signal Coordination Ecology
https://www.amazon.com/Ecology-Collective-Behavior-Deborah-Gordon/dp/0691232156/ 
The Ecology of Collective Behavior Paperback – October 24, 2023
by Deborah M. Gordon 
- alternatives to whole-part contexts

## Case studies in ideas and literature

# direct programming: coordinated decisions and moving parts
- Time and Programming
- asynchronous systems
- parallel systems
- concurrent systems

# Clearweb infrastructure vs. Deepweb infrastructure
- 5% of tools and uses
- 95% tools and uses
(see https://medium.com/@GeoffreyGordonAshbrook/forecasting-ces-2024-clear-web-mega-ai-vs-local-ai-gpu-device-specs-may-keep-shaping-ai-software-3abaaa51931c )

# Aspects of system diversity or lack of diversity
- security
- redundancy


# passwords, devices, "fido," etc.
- 

# The Stakeholder Perspective:
- Would a person who relies upon the voting system as infrastructure for survival go along with decisions being made by people who may be indeterminately incompetent or malicious? 

# forms of encryption and trade-offs 

# memory management: 
- security
	- privacy
	(lower level: programming language used)
	
# character sets, flexibility and security, ascii, fonts

# conflict

# Automation and coordination

# Is there a way to standardize and automate statistical reporting on data throughout an 'election'?

## software, operating system, language, network resources for open, public, charity use:
- minimal
- secure

...

## Automated testing of question ambiguity
- see automated benchmarks
- decision coordination and STEM (see Online Voting Using One Time Pads github v76)


...

## meta-data layers: handling and interfacing multiple and changing data storage format: 2024.03.12
- when different sets of fields are used
- when different names are used for those fields
- the eternal length of array, length of string, length of number issue:
- e.g.
- election:
- candidates:
- choice:
- voted_for_choice_or_choices:
- write-in:
this overall same information can be expressed and in various specific situations will need to be expressed and externalized in significantly different ways, such that handling and comparing such structure is not automatically simple. 

## Decision-Net, Word-Net, Image-Net: 
= training sets and testing benchmarks for decisions and coordinated decisions

### general software sets vs. research and development sets vs. use-production sets, vs. specific use-case sets
- optimization
- "do one thing well"
- standardization

## Perception 
(2024.02.27)
- The danger of people worshiping something that they don't understand, for example in an incomprehensibly broken system that makes no sense, because of an internal need to reify something worshipful, be it (the seeking or attempted creation of) an external locus of control or otherwise.

## Design and deployment factors
- "do one thing well"

# login management

# Security: Type of attacks that cannot be entirely prevented:
- social engineering attacks
- physical site destruction
- distributed systems vs. centralized systems: e.g. social engineering attacks and the byzantine generals problem, smart contracts, etc.

## auditing and automated auditing, process and step problems in coordinated decision making:
- map of process-step-analysis applications
- 
- 

## Khanaman & Tversky, et al: effects on systems of decisions
- decision spaces
- behavior economics
- decision theory
- prospect theory
- how options are phrased


## categories of CS operations involved in coordinated decision making
- are there any undefined-behavior or non-analytic components that are unavoidable?


## Red Herrings
- Parasitic and Reified goals:
	- discriminatory goals
	- arbitrary fetish goals
	- goals no one can justify or explain at all 
- scope creep
- scope drift
- while true: processes stuck in loops


## schedule problems.


## data logic time and coordination
- time in databases


## timescales and coordinated decisions

## over-communication as a goal
- American vs. Japanese norms on re-covering discussed topics for agreement.

## Arts culture, communication and decisions

## ways of handling categories and topics, 
e.g. more and less quantifiable and defined topics.
- discipline-specific (medicine, physics) decisions


# measuring feedback: can failures of feedback (a lack of feedback channels) in organizations and institutions be detected


# sources of data: 
- questionnaires
- metadata
- votes
- skin in the game
- optional and mandatory participation
- abstraction and perception (secret, anonymous ballots)


# participation, populations, distillation

# anonymity and toxic behavior online
- incentives and feedback in behavior


## training and effective education
teaching how to participate in coordinated decision making
- agile
- elections
- direct and indirect education
- education learning perception


## dataframes and databases
- encrypted contents
- statistically anonymized content (e.g. Security now when hashes collide)

## Managing different specific large and small unknown values, variables, and geometries

## adversarial and stochastic
- adversarial and stochastic inputs to automated coordinated decision making (indeterminate incompetence and malice

## operationally defining cases for indeterminate-incompetence-and-malice as part of system collapse 
- reporting (sometimes reified) items that do not exist, and 
- denying reports of items that do exist)

## Analogies of Modularity
- types of modularity
- brittleness
- fix-ability
- move-ability

## Mirages and Siren Songs in System Design & Project-Space
- Social cohesion and inclusion
- 

## Types of Feedback (2024.01.17)
- decision systems
- coordination systems
- coordination and decisions
- code compilation type feedback
- agile project participant communication type feedback

## issues of copyright and fair-use on various levels of project, coordinated-decision-making, and the use of STEM processes therein.

## Access: Whitelisting and Blacklisting (e.g. network access) 
- Could some form of white-listing alleviate ddos attack surface?


## Election Data & RAG:
- from 1900's statistical analysis to 2000's Data Science
connecting Jan with open frameworks for
1. deep weight train & make new models
2. fine tune & transfer-learning with existing models
3. DPO type training
4. RAG and databases
	- specific epub, pdf, .odf, and .doc(x), sheets, .csv, etc., 
	databases?
	- the relational-S.Q.L. stored-data world
	- election data formats
5. project state
6. externalization
7. AI-open-office
8. coordinated decision making

## voting on disputed issues
- real and theoretical: 'not in my backyard' vs. 'boil 49% in oil'
- mediation
- 3rd party arbitration
- no-trust contracts


## means of objectively determining in a ballot measure is logically sound, e.g. declaring that all triangles have four sides, or some other tautologically false statement.


## strategies for managing sunset clauses

## precedent in modes of ruling vs. sunset limits on specific laws


## Topics in Election and Decision Coordination Data Management
- transparency
- non-potemkin-village
- externalization (as in Object Relationship Spaces & Projects)
- 


## Identifying goals that are hybrid-fragment-illusions and not related to:
- the project
- data
- evidence
- group agreed upon goals means methods
- best practice
- 


## No One Size Fits all system
- like databases

## Data flow in systems: externalization and formats
- 

## Avoiding the echo-chamber of infotainment and distracted-shallowness

# Security: Types of 'encryption' that cannot be broken:
- one time pads
- navigation-blind OS

## Automated testing of coordinated decision systems


### Voting Logistics and Ethics: Western Chasm
The odd paradox of people in the west believing that voting is inherently good, yet still with the old dark-age-curse never recovered from that views anything 'worldly' as being an evil monster to be destroyed, with the absurd compromise of being willing to live: "in the world but not of it" or some rubbish. Pay attention to what you are doing and do things properly so no one gets hurt, for heaven's sake that is not an evil plot for destruction; it is a definition of responsibility and at least attempting to do what one ought to do.


## Problem Identification & Classification
- e.g. AI problem vs. general problems & psychology of perception
- not ignoring, misdirecting, covering up, problems in ~voting system
- no 'blame down hill'
2023.11.02

## psychological distortions in perceptions of causality in building using and maintaining an architecture for coordinated decision making.
2023.11.02


## Related areas for coordinated decision making:
- math
- biology
- psychology
- linguistics

## timelines and schedules
- how quickly can an election system be built and used?


## social context in categories of configuration data for datastructures and databases (2024.04.07)
- 


## Resource Use
 	- Scaling and computational efficiency (big o)
- energy cost
	- human time
	- financial cost in areas

## Managing decentralized (or centralized) projects

## efficiency, modularity, svg, and line/curve plots (vs. 'media file' bloat), TUI vs. GUI

## ad-hoc systems

## Participation, representation, and ways to avoid some groups as being defined outside of the ability to participate:
- exclusion
- discrimination
#### individuals vs. groups: 
- balancing group responsibility vs. individual responsibility
#### rehabilitation and healing, learning

## long term data storage problems: paper computers

## Historians and Archives
- records
- accounts
- 

## objective criteria for voting system feedback and suggestion acceptance:
- bug reports
- feature requests
(lessons learned from past software systems)

## measuring the equivalence of processes

## Laws Policies, and Voting-Elections about each-other: 
	- a Matrix With Feedback
	- 

## design guidelines and standards

## input and output that are blobs or have distinct sections

## Participation and Motivation
- use-ability of system

## communication and translation between X and Y
- input output measures
- participants
- setting location areas
- animals
- participants
- pre-participants, post-participants

## DOTW, D.O.T.W., design tradeoffs and optimization, 
- Do One Thing Well
vs.
- general flexibility, etc.


## old code can work, new is not always better

## Formal and informal political 'parties':
	- do there need to be parties
	- how should party systems be defined?
	- parties in coalition vs. winner-takes-all systems
	- proportional representation

## Parties vs. Mandates
- 


## Individuals and institutions in voting and infrastructure
from decentered /decentralized elections and networks to centralized political parties, servers, and cloud resources, proportional representation, etc.

## Applications of Mandate-Based Systems
- 


## System design
- secure by design
- trust vs. trust-less
- permissions vs. no-permissions

## Potemkin Villages
- cases
- identification
- avoiding disasters

## trade offs and contexts for optimization

## data ~handling policy:
	- function-equation data 
vs.
	- values
	vs.
	- instructions? (separate from functions?)
	Types of 'state'? (as in values being odd in lambda-calc?)

## Votes from past generations who are no longer alive vs. sun-set clauses

## Forms of democracy and types and structures of elections:
- forms of decision making in history:
-- from 'the decline and rise of democracy' book

## Static questions vs. diversified questions with a data-root
- e.g. language translation versions
- simplification level versions
- ways of asking question to test which are obscure of mistunderstood
- the classic 'identification' step, where if what the question is asking can not be identified with a high percentage of the time, then the phrasing of the question is liability, effectively asking the wrong question, communicating the wrong thing, and causing confusion and miscommunication


## speed of voting, protest votes, and reactions to violent takeovers


## Computer Science issues relating directly to practical election system development and deployment into production at scale. 

book: Working in PUblic by Nadia Eghbal, making and maintaining open source software

## better defining roles in projects
- what do different kinds of participants 'look' like?

## Public Times, Public Places
when and where to coordinate on decisions

## Cyclic Condition Regimes
- seasons
- tides


## Time, Data & Choices
- memory safety and garbage collection
- parallelism and concurrency
- production vs. development (production-deployment vs. R&D)
- solo vs. group and open-group projects
- "trust"
- 'secure by design'
- defaults
- types of type
- time scales and processes from sunsets-clauses to campaign durations to security-attack surface, computation time, etc.


## tasks, processes, and system-abilities: five problem-space trees and system-state options; what does a decision coordination system need to be able to do, in terms of precise definitions of specific granular operations in a ~5x-tree+state context?
- how does this relate to the question of the 'intelligence' of a system?
- 

## production vs. development (production-deployment vs. R&D)
- resource efficiency
- 

## Communication, Instruction, Stories and Concepts
- procedures
- values


## standard task and behavior benchmarks
- coordination
- signals
- actions
- outcomes

Role and Sources of Stochasticity in decision coordination:
- pseudo random numbers
- analog random numbers
- anonymization
- cryptography
- stats in analysis after events

## Mythology and Coordinated Decisions

## Election design and goals: disinformation and distortion
- can feedback or other mechanisms steer the design and use of coodinated-decision-events (selections) to constructive tasks

## priorities and the psychology of system visibility: when noise overwhelms perception: Q: in reality, how often does noise overwhelm perception?
- types of noise and types of perception-distortion?
- is Khaneman Tversky perception analysis mostly time-invariant in terms of when people can or cannot see through various ebbing and flowing disturbance regimes of noise in a temporally and spatially heterogeneous landscape?

## evaluating agendas in a project-space of coordinated decisions

## Questions of defining technology


## STEM, fantasy, coordinated decisions, and system architecture:
- tethering to data, feedback, and reality
- 

## diverse-participant voting-coordination

## consequences on elections on culture see political theory

## bio coordination
- cell signaling
- inside-population-signaling
- signaling across species, across populations
- ecosystem signal patterns

## Quantifying elections, votes, decisions, agreement, choices

## Flow Chart Compiler
Flow chart to functions to compiled code

## Visualization of Election Data
- principles
- planning
- monitoring
- results
- reporting

## Data Visualization and communication:
- of issues
- of processes
- of results
- for transparency
- for feedback (the case of the norwegian electric meters)

## MCU Multipoint Conferencing Units, Modularized Signal-Response Protocols, Moderation virtual Decision-conference Mediation
- 

## Junkfood health short-term long-term in coordinated decisions

## defining participants and participation for coordinated decision making

## Potential disputes over 'ownership' of election parts or results

## voting, probability, statistics, modeling, census:

## logical consistency and coherence of a particular voting system and measures on the voting system

## The self-referential coordination-system test:
- can a coordination(voting) system be set up using its own structure?
(the idea being that if the system is dysfunctional you will find out before applying it to an election) 2024.02.12

## distortion, disruption, disinformation
- non-false disruption (where no rules are broken but nevertheless there is a campaign to disrupt 
(book)
How to Lose the Information War: Russia, Fake News, and the Future of Conflict Hardcover – July 9, 2020
by Nina Jankowicz 
https://www.amazon.com/How-Lose-Information-War-Conflict/dp/1838607684 


## contagion, spreading, disinformation and disturbances
- epidemiology
- ecology

## Portability

## Adams Franklin Jefferson, enlightenment common law constitutions:
- STEM, law, voting
- trial, juries, courts

## networked voting and network access
institutions such as libraries for areas with internet

## coordinated decision making and architecture tasks: distributed overlapping logic
- counting tasks
- overlapping effect tasks
- a model of overlapping counting counting tasks

## Data and Categories of Types of Systems in coordinated decision making architectures


## summarization
## reporting
### data visualization

## character-sets, language archeology, and the katakana (or romaji-katakana) approach for language approximation
- 
- 

## write-in options
- multiple choice vs. free response systems
- equivalence and deterministic handling of options

## Coordination and Leviathan Questions

## setup-time

## cross platform

## Rules for auditing instruction sets
- feedback loops
- project elements
- data hygiene
- 

## countability, metrics, and definitions

## Pattern, Protocol, and Process
- skill, ability, learning

## Is decision-coordination a special case of information-exchange, where fix-format, protocols, etc., modify a more general-communication theory?

## Self-Referential Cases:
- What issues are there when automating decisions about decisions, in perhaps a classic case where data and instructions are intermingled, but where which is which is prone to ambiguity?

## defining qualification for coordinated decision making

## the importance of an awareness of history for participating in coordinated decisions:
- What is important to know?
- Is anything required-knowledge, or just helpful?
- How can this be framed as a curriculum?
- How can this be taught?
- How can this be required or facilitated?


## Describing the difficulty of a project
- likelihood of mistakes
- costs of operations
- schedules, sequence-orders of operations, 
- modular-depth and scales of numbers of modular processes


## Definition Behaviors, Questions, and Signal Coordination

## Historical cases of breakdown

## Non-Homogenous Environments:
- "THe glass universe" America vs. Rober J Jordon's "Rise and fall of American Growth" America

## Rules for how elections get:
- called
- initiated
- audited
- closed

## System Explainability & System Reliability Standardization
...

## What needs to be in a decision-coordination database?
(2023.09.30)

...

## Thresholds of adoption for system to be practical

...


# Data & Decisions
- trade offs
- data permanence
- ad hoc systems
- scale
- byzantine fault problems
- fuzzy data
- flexibility
- quantum databases
- time and data

see: Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems 1st Edition, by Martin Kleppmann 

## relativity, time, decisions, and distance: scale and community
...

# Group Agreed Upon Goal Means Methods Statements for Coordinated Decision Making
- note: common areas of real or imagined dispute

...

## levels of architectural mechanics
- ranked choice, noise handling, and Shannon-Turing Unit-Communication
- ranked choice in accurate option selection as a form of signal error checking
- 

...

## scalability in the problem space of coordinated decision making

## political parties and institutionalization
- history
- case studies in handling run-offs and proportional representation
- uses and issues with parties


## R&D, Smithian Greed Self Interest, Infrastructure, Commons, and Short Term Profit Growth: Factors and outcomes in investing in coordination decision tools vs. not investing
- tragedy of the commons
- transparency vs. secret squirrel
- 


## Document Formats, Formatting, Processing:
- automated document processing
- handling formats
- uses of documents
- explanations of documents
- 'search' and 'retrieval' of documents (Search Augmented Tasks vs. RAG)
- 

## voting system logs and transparency
- network monitor logs
- 

## do one things well, limited functionality
- 'living off the land' attacks

## The need for a resource-thin framework

## Backend Production: server options, and "serverless" options

Note: https://www.grc.com/securitynow.htm 
SN Episode #873: australian digital driver's license as case study in similar system, not Gibson's certificate based solution 

## Different forms of consensus, representation, and contracts

## Succession

## Conflict, Mediation, Negotiation, and Coordinated Decisions

## Methods for Consensus

## Automation, Explanation, Testing

## Automated Decision Making & Hybrid-Participant (h.sapiens & machine)

## On-Edge vs. large tool / general & development vs. production-version

# Database security standards
(no standard "sql" versions)
...

# Elusive Project/Election Goals: meritocracy vs. kleptocracy
- Demand-distortion and the difference in practice between a meritocracy and a ~ Kakistocracy
https://en.wikipedia.org/wiki/Kakistocracy
- What are the details of process, decision, and outcome.
...

## Categories of Decisions
and specific task processes

...

# Decentralized Traffic and Cost Flow
- delayed start
- work for credit
- slim form: ascii
- not requiring a separate server system...
browser based...
app based...
	- Jefferson-Radio type
- 


...

project coordination standards
- for developers working on project

...

roles votes and definitions:
One person physically able to vote gets one vote is a very blunt way of deciding who should be voting on a topic, with assumptions that make (made) more sense in low-tech local elections where only local people within an age-range could physically vote. But with various technologies from transportation and translation to networks, that rough match becomes less clear.
There are a lot of factors and edge cases, with a possibly related topic of district-creation and gerrymandering which run up against challenges where the main problem may be people's refusal to confront the issues. 
'Make the design-choice go away." is not a good plan.

...


## Shannan/Turing information theory/communication theory and decision coordination problem spaces
- have we learned anything else about signals and information since Shannan?
- information in coordinated decision making?

## information collapse vs. signal collapse

## Systematizing, Ethics and Projects in Elections

## Contracts and Coordination

...

## topics in voter enrollment

## historical debates on voter participation
- John Adams

...

### Poverty Disinformation Non-Automatic Learning and Coordinated Decision Making

## Low-Bar-Enlightenment-Compassion Project Lifecycles and Coordinated Decision Making (2023.08.25)

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

### Protocols, resources, and tradeoffs:
- advantages and disadvantages of different frameworks

## Opinion Polls Vs. Elections: What is a vote?
- a history of incorrect pre-election polling
- factors in polling accuracy
- statistics of polling
- analysis of why post-internet polling has been so wrong


## Possible roles of language detection, e.g. election monitoring interference tools
- Can 'junk food language' Be Detected?

## OCR
Where optical character recognition is used, what standards can be optional and in place for how unclear handwriting is handled. Including the question of whether OCR should be avoided.


## Finite(?) Modular Question and Decision Definition
- selecting translating and connecting clearly defined units of question answer and decision

## General Voting System Study Links (appendix)
- https://www.youtube.com/greymatter/search?query=elections 

## Voting System Design Study Links (appendix)
- https://www.youtube.com/greymatter/search?query=elections 

#### Election Data Study Link
- 
note: page seems to no longer exist or merged into larger course...one fewer resouce on a needed topic...)
https://www.datacamp.com/courses/analyzing-election-and-polling-data-in-r?irclickid=TtWxHF0I7xyNUMqzKwUmBUEhUkD3QI3tIzmPW80&irgwc=1&utm_medium=affiliate&utm_source=impact&utm_campaign=2556128 
vs.
https://www.datacamp.com/courses/data-manipulation-with-dplyr 

https://www.r-bloggers.com/2018/11/new-course-analyzing-election-and-polling-data-in-r/



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
Question: Are there, in principle, systems that select qualified voters yet which have no 'test' for voter qualification? 
- age test
- local test
- stake-holder test
- 'citizenship' test
- land ownership test
- knowledge of ballot issues test

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


## Signal Questions and Disinformation in Coordination

## anticipating social-engineering attacks
- options for testing?

### Defining 'Disinformation'
Verification, stem-information, and disinformation
- resources:
- history
-

### election-space analysis / coordinated-decision space
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

#### Trade-off in UI user interface design: secure but use-able
- 

### Agile, Security, & Voting: General best practice vs. specific voting system best practice

Question: What do international election inspectors look for?

### Mandate-Based Representation
Perhaps as a form of least-trust architecture, which brings with it perhaps the same 'slow procedural processes' of enhanced verification checking, representation that is limited to specific approved mandates is a historical mode (and one which nearly became part of the US model). 
(see: https://www.amazon.com/Decline-Rise-Democracy-History-Antiquity/dp/B088ZKZDTY/ )
(history: 'fall and rise of democracy' book)

## Disinformation and Elections: Measuring and Modeling Information and Effects
- identifying disinformation
- preventing disinformation
- stopping spread of collapse including disinformation

## Main Topics in Decision System Architecture:
- first past the post
- proportional representation
- gerrymandering
- observing election polling


## History and comparative history
- looking at how various times and places viewed and used representation and participation, especially qualifications for participation (families, age, geography, tests, inherited status, etc.)

## Coordination as Formal Systems
- ~'game theory' and decisions
- 




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
Nate silver book signal noise
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
( Cult of the dead cow ) book 

#### 
( A people's history of Computing ) book 

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
https://www.amazon.com/Modern-Political-Tradition-Hobbes-Habermas/dp/B00KNLZWEA
- open source study book...title? (no starch?)

## Other Books
(Virtual Society)
(maybe book on data intensive systems)
https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321/   

## Books on Data & Databases:
Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems 1st Edition, by Martin Kleppmann 
https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321/ 

## Books on Project Management
( )


## Lectures and Papers on Political Philosophy and Political Traditions
- The Modern Political Tradition: Hobbes to Habermas
Lawrence Cahoone, Ph.D. Professor, College of the Holy Cross
https://www.thegreatcourses.com/courses/the-modern-political-tradition-hobbes-to-habermas 
https://www.amazon.com/Modern-Political-Tradition-Hobbes-Habermas/dp/B00KNLZWEA


## Web Resources:

#### C.G.P. Gray on Elections & Voting Systems 
- https://www.youtube.com/@CGPGrey/search?query=elections 
- https://www.youtube.com/@CGPGrey/search?query=voting 


#### Case study in password handling:
- https://twit.tv/shows/security-now/episodes/905 
- https://twit.tv/shows/security-now/episodes/904 
- alternate source episodes 904 or 905: https://www.grc.com/securitynow.htm 


### Counter-Example Books
- Optical Illusions

#### On Memory Safe Languages (note still actively evolving time-lag and shift to topic, google press release is old, action taken to adopt RUST is new). 
- https://twit.tv/shows/security-now/episodes/906 
- alternate source episode 906: https://www.grc.com/securitynow.htm 


### Election Case Studies (section not complete)
- eastern Europe and Russia
-- post wwii
-- post 1989


## Articles:
- https://www.wired.com/story/ranked-choice-voting-reveals-the-weird-math-of-elections/ 


