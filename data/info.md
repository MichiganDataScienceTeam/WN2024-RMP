## clean_prof_info.csv

| Column Name       | Data Type | Note                            |
| ----------------- | --------- | ------------------------------- |
| profID            | int       |                                 |
| firstName         | str       |                                 |
| lastName          | str       |                                 |
| fullName          | str       | Concatenate first and last name |
| department        | str       | Known defects, not reliable     |
| numRatings        | int       |                                 |
| wouldTakeAgainPct | float     | Ranges from 0 to 100, has Na    |
| avgDifficulty     | float     | Ranges from 1 to 5              |
| avgRating         | float     | Ranges from 1 to 5              |

## clean_ratings.csv

| Column Name         | Data Type   | Note                           |
| ------------------- | ----------- | ------------------------------ |
| profID              | int         |                                |
| class               | str         |                                |
| attendanceMandatory | bool        |                                |
| comment             | str         |                                |
| date                | pd.datetime | UTC format, accurate to second |
| difficutyRating     | float       | Range from 1 to 5              |
| grade               | str         | Letter grades, with +/-        |
| helpfulRating       | float       | Range from 1 to 5              |
| isForCredit         | bool        |                                |
| isForOnlineClass    | bool        |                                |
| ratingTags          | list        | List of up to 3 tags           |
| wouldTakeAgain      | bool        |                                |