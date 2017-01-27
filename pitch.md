### Title: A web application for reporting unintended computed tomography (CT) exposures

#### *or*

### Bringing Radiation Protection into the digital age

-----


##### User need:

I work for a radiation protection department, and sometimes, radiology departments need to ask us to calculate how much radiation dose a patient has received after a CT scan. This could be because the patient was never actually intended to receive a scan - maybe they were just on their way to the canteen (that's an exaggeration), or maybe they were pregnant at the time, and we need to know what's the risk of the exposure to the foetus.

In any case, right now our system is this: we send hospitals paper copies of a ropy old Word template which they print off, fill in and, if we're lucky, scan and email to someone in the section, or if we're not so lucky they fax it or post it etc.. We then transcribe the form, and, inevitably, have to chase the person who reported it for missing information. Finally we'll run the numbers through an Excel calculator, generate another report and send it off.

##### What we want:

So what we want is this:

- A way to assure the quality of the data coming to us, so we don't waste time chasing things up
- A way to easily issue updates to the reporting form so we don't receive requests using out of date forms.
- A way to track, record, and assign the requests coming in other than what's in our individual inboxes
- A way for our customers to view their outstanding requests, and
- A way to automatically pipe the data into our dose calculator

##### Where to start?

This project will need:

- It will have to able to be self-hosted by us, because of the necessity to hold confidential patient data
- A web framework with a secure database back end, with an API we can use to perform audits and quality control on the system
- A secure login and account system
- An ability to be easily updated by the section
