# MeetingMinutes
Meeting Minutes for 2/7/2024

DTT (Digital Triplet Test) 

Present 3 digits (2, 3, 7) [random] 

Subjects hears it over earphones. Replies or keys in the digits.

Presented in noise so it is not always discernable. 

The purpose is to try and get a signal to  noise ratio to where the patient will get 50% correct.
Then it is finished.

Short and quick diagnosis for someone who has hearing issues. 

Normally the test is given with headphones. [Headphone and speaker functionality]




Interested in a languaged called Setswana in Botswana. 

Student is from Botswana and wants to do research project in his lab. Develop something to take home and be useful. 

Example: English Test [principle of the test is the same]

https://www.medel.com/en-us/about-hearing/hearing-test/speech-in-noise




If you are correct, it will decrease the signal to noise ratio. Noise is fixed but the signal ratio decreases (to get harder) as success goes by.

SNR 0 = Speech and noise is at the same level. To calculate signal noise ratio you use 20*log_10((s)/n) or RMS(S) / RMS(N) in dB. 
s = speech
n = noise

Positive level is presented at a high positive ratio. With success the dB is dropped by a discrete amount (typically drops into the negative region).
What is the termination rules?
1. When you have 8 reversals [Agnostic to double positive or negative, just reversals]
- Take the mean of the last 5 reversals. This value is the desired number returned. (signal noise ratio where the patient gets 50% correct).
2. Escape at an overly high signal to noise ratio. 



Need to look up if there are other languages where there are syllabal issues. 

They need to collect data before they know a "normal range". 



Researcher needs the information stored. IRB issue. Keep it at the minimal. 

Time compression not a good idea.



Being given recordings. Given segments of noise. 
Would like a matlab version of this to be done in the lab. 
[Fundamental Ideal is the mobile version]



Parameters. 
1. Everything stops. "Digit is: 1, 2, 3" ex. 
2. What is the interval between one digit and the next. 
3. When the last digit ends there is xms of noise at the end of the language. 


What he wants deliverable by the end of the semester something that is workable and able to collect data.
** Functionality check, how to transfer the data to a stored program. Possibly look at being exported to excel??. 



nm110222@ohio.edu Nako [Grad student]. 

Some ideas that are needed to be done:
1. --AI voice for the language?-- (NOT needed 
2. Need to do matlab for the background noise. 20*log_10( RMS(S) / RMS(N) )



Design goal: 
VERY clear documentation in order to be passed along for future workers. 
Gender and blocks of age range. 
** Need to look into what are the appropriate legal methods of data collection. 
** Need to explore with IRB on the ethics of adding data collection. 
** Need to taks to Professor Linder about randomizing data collection. 
February 22nd meet again. 

