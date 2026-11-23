# Problem statement

## Who uses it and when:

- This will be used at the shooting machine for shooting workouts
- Between sets at the gym for weight liftiing and plyo program
- On my phone
- By me to enter and track workouts
- Coaches don't use the app. I upload their plans: the shooting workout (Excel) and the lifting plan (PDF from THP, sent by email).

- For offline viewing:
  - The user should be able to view today's workout plan
  - Log their sets
  - Sets are saved offline to the users smartphone storage and then sync to the cloud database
- Works with 2 taps when hands are sweaty or dirty

## What's painful today:

- If the basketball workout sheet is updated while I am using homecourt we can't see (any coach/trainer using our app)
- HomeCourt locks the session: if I switch apps to check the plan, I lose my tracking progress, and I can't pause a workout.
- Shooting via homecourt doesn't show us our todo low intensity workout or high intensity workout
- Also when we have a long workout it can be hard to track what I am supposed to be doing
- Since homecourt just tracks made shots instead of forcing you to take the shots you need to work on you can just shoot catch and shoots rather than doing the harder workout plan

# Success looks like:

1. Today's full plan (lift and shooting) is on one screen
2. It tracks the sets and reps and we can mark it for completion
3. Each excercise has a demo video link
4. Log a set in 2 taps, in under 10 seconds, without leaving the page

# Not in v1:

1. No makes/misses tracking, manual or camera, because HomeCourt takes care of it for us
2. Video demonstrations that are directly connected to the google sheets
3. No multiple users or multi-person tracking, because v1 is just for me.
4. No apple health integration yet

## Open questions

- How do trainer updates reach the app: one-time import, a refresh button, or automatic sync from Google Sheets?
- What happens if the plan changes mid-workout?
- Offline: where is a logged set saved, and when does it sync?
