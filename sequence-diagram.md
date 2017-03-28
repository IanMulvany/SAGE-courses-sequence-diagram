title workflow A

Student->Sage.com: View homepage
note right of Sage.com: admin activates link
Sage.com->CoursePage: Link to Course Page
note right of CoursePage: info, link to LMS
CoursePage->LMS: Link to specific course
note right of LMS: open question, do we want login here?
LMS->LMS: Login / Create Account
LMS->Student: account details
Student->LMS: Pay for access
LMS->Payment Provider: card transaction
Payment Provider->LMS: send payment token/approval
note right of Payment Provider: Paypal and Stripe are supported in moodle
LMS->Student: notification of approval for specific course
note right of LMS: admin activates cohort
LMS->Student: notification of start of course
