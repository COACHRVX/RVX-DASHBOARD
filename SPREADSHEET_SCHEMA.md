# Spreadsheet schema

## Athlete_Profile
`athlete_id`, `first_name`, `last_name`, `birth_date`, `sex`, `sport`, `team`, `position`, `hand_dominance`, `height_cm`, `weight_kg`, `photo_url`

## Testing_Sessions
`athlete_id`, `session_id`, `test_date`, `session_label`, `location`, `notes`

## Performance_Metrics
`athlete_id`, `session_id`, `test_date`, `metric_key`, `metric_name`, `category`, `value`, `unit`, `direction`

## Normative_Data
`sport`, `sex`, `age_min`, `age_max`, `metric_key`, `metric_name`, `mean`, `std_dev`, `unit`, `direction`, `source`

## Coach_Recommendations
`athlete_id`, `display_order`, `category`, `title`, `recommendation`

## Areas_of_Focus
`athlete_id`, `display_order`, `focus_area`

## Next_Steps
`athlete_id`, `display_order`, `next_step`

## Dashboard_Settings
`setting`, `value`, `description`

## Recommendation Matrix
`Metric ID`, `Metric`, `Direction`, `Norm Status`, `Status Logic`, `Primary Area of Focus`, `Secondary Areas of Focus`, `Coach Recommendation`, `Primary RVX App Program`, `Secondary RVX App Program`, `Suggested Coaching Cue`, `Retest Guidance`, `Template Metric Key`, `Lookup Key`

## Status Logic
`RVX NORMATIVE STATUS LOGIC`, `Unnamed: 1`, `Unnamed: 2`, `Unnamed: 3`, `Unnamed: 4`, `Unnamed: 5`

## RVX App Programs
`Program Name`, `Program Category`, `Primary Use`, `Suitable Norm Status`, `Suggested Duration`, `Suggested Frequency`, `Coach Notes`

## Dashboard Lookup Guide
`HOW TO USE THE RECOMMENDATION MATRIX IN THE DASHBOARD`, `Unnamed: 1`

## Dropdown_Lists
`Athlete IDs`, `Sex`, `Sport`, `Position`, `Hand Dominance`, `Session Labels`, `Locations`, `Metric Keys`, `Norm Status`, `Recommendation Overrides`, `Metric Key`, `Metric Name`, `Direction`, `Unit`

## Recommendation_Output
`Athlete ID`, `Sport`, `Sex`, `Metric Key`, `Metric Name`, `Direction`, `Latest Test Date`, `Latest Value`, `Normative Mean`, `Difference %`, `Norm Status`, `Primary Area of Focus`, `Secondary Areas of Focus`, `Auto Coach Recommendation`, `Primary RVX App Program`, `Secondary RVX App Program`, `Coaching Cue`, `Retest Guidance`, `Override Status`, `Override Focus`, `Override Recommendation`, `Override App Program`, `Final Status`, `Final Area of Focus`, `Final Coach Recommendation`, `Final RVX App Program`, `Coach Notes`

## Recommendation_Lookup
`Lookup Key`, `Primary Area of Focus`, `Secondary Areas of Focus`, `Coach Recommendation`, `Primary RVX App Program`, `Secondary RVX App Program`, `Coaching Cue`, `Retest Guidance`
