# Rescue Squad US test build: privacy statement

*Applies to: the Rescue Squad **US test build** for invited testers in Virginia, distributed through Apple TestFlight.
Last updated: 2026-11-08.*

**This is a test build. It is not an emergency service, and it never calls 911 for you.** For a real emergency, call
911 yourself. The emergencies in it are pretend; the locations are real.

## What we collect

- **Your account:** your name, phone number, area (county or city) and role.
- **Your location:** where you are when you ask for help, and your position about every 30 seconds until the request
  ends (not if you have turned location sharing off); while you are on call as a responder, your position sampled
  over time.
- **Practice entries:** anything entered during a practice request (the patient's details, a complaint, vital signs,
  treatments given), and voice notes you record.
- **Your responder details:** the tier you choose, a display name and an ambulance number if you give one; and any
  defibrillator (AED) you add: its photo, location and who added it.
- **A push token:** a code from Apple or Google that lets the server wake your phone when a request is offered to you.
- **Study records:** answers to questionnaires you choose to fill in, your consent choices, and your enrolment in the
  test.
- **Practice triage records:** for each practice request, what the server's automatic triage would have advised: an
  alert level, the kinds of responder and the actions it would suggest (including "call 911"), and its reasons. It
  acts on nothing, calls no one and is shown to no tester; the test team reads it to check the triage.
- **An access log:** who on the test team opened which record, and when.

## Who sees it

- **Testers on call near you who are offered your request** see your first name, your area and roughly how far away
  you are, before anyone accepts.
- **The tester who accepts your request** also sees your exact location and phone number, and can call you in the
  app; while they come, you see their position, to within about 500 metres. Testers are invited by name; the app is
  not offered through a public link.
- **If you ask for help without an account**, the phone number you type (if any) is shown to the tester who accepts.
- **The test team** can read the test server. Team members acting as dispatchers or emergency-department staff see
  every on-call tester's position and the practice requests; these roles are given to named team members only, never
  to testers. Team members running a study can see a tester's one-time sign-in code, to help someone who cannot
  receive the text message; with it they could sign in as that tester.
- **Apple's app reviewer** may use a test account during review.
- **Nobody else.** No hospital or emergency service receives this data. The app sends nothing to analytics or
  advertising services, and no request details go through Apple's or Google's push services.
- **Apple and Google push services** (once the test server has its push keys; not yet): if you are on call and a
  practice request is offered to you while the app is closed, your phone gets the fixed alert "New help request.
  Open the app." through Apple or Google. They learn that your phone was woken at that time, nothing about the
  request. If your phone does not acknowledge the offer, one text message with the same words may follow, sent
  through Amazon Web Services (AWS End User Messaging SMS), which receives your phone number and those fixed words
  for that purpose and nothing else.

## Where it is kept, and for how long

- On the Rescue Squad test server, hosted by Amazon Web Services (Amazon Lightsail) in its US East (N. Virginia)
  region.
- Location history from being on call is reduced to 5-minute points after **14 days** and deleted after **30 days**.
  Voice notes are deleted after **14 days**. The access log is kept **30 days**.
- Encrypted backups on the server are deleted after **14 days**.
- **30 days after a practice request ends, your name and its exact location are removed from it.** Questionnaire
  answers, consent choices, practice triage records and records that a request was offered to your phone are kept, without your name once you
  delete your account, until the server is erased.
- **When US testing ends, the test server and its backups are erased.**

## Your choices

- You can stop sharing in Settings; what you already sent stays until the dates above.
- You can delete your account in Settings; it removes your name and phone from your account and signs you out.
  Copies on past practice requests are removed at the 30-day point.

## Contact

Questions: poet-rage-upturned@duck.com.
