# Caffeine Metabolism Clearance Log
Log caffeine intake (coffee=95mg, espresso=63mg, tea=47mg, custom). Model pharmacokinetic clearance with 5h half-life. Chart shows caffeine level over next 24h. Predict time below 50mg threshold. localStorage history of today's intake.

## Features
- Preset drinks: Coffee (95mg), Espresso (63mg), Tea (47mg), or custom mg
- Time picker for logging exact intake time
- Pharmacokinetic model using 5-hour half-life exponential decay
- Real-time 24-hour clearance chart with canvas rendering
- 50mg threshold line with predicted time to fall below it
- Today's intake log list sorted by time
- Persistent localStorage storage keyed by date
- Clear today's log button
- Responsive canvas chart with device pixel ratio support
