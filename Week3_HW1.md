```python

## Part 1 
dear_data = [
    {
        "day": "Monday",
        "hours_slept": 14.5,
        "sick_day_rating": 5,
        "hours_not_at_home": 0,
    },
    {
        "day": "Tuesday",
        "hours_slept": 6,
        "sick_day_rating": 5,
        "hours_not_at_home": 0,
    },
    {
        "day": "Wednesday",
        "hours_slept": 6.5,
        "sick_day_rating": 3,
        "hours_not_at_home": 13,
    },
    {
        "day": "Thursday",
        "hours_slept": 6.5,
        "sick_day_rating": 3,
        "hours_not_at_home": 13,
    },
    {
        "day": "Friday",
        "hours_slept": 8,
        "sick_day_rating": 2,
        "hours_not_at_home": 1,
    },
    {
        "day": "Saturday",
        "hours_slept": 13,
        "sick_day_rating": 3,
        "hours_not_at_home": 0.5,
    },
    {
        "day": "Sunday",
        "hours_slept": 8,
        "sick_day_rating": 2,
        "hours_not_at_home": 2,
    },
]

print(dear_data)
```

    [{'day': 'Monday', 'hours_slept': 14.5, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Tuesday', 'hours_slept': 6, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Wednesday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Thursday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Friday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 1}, {'day': 'Saturday', 'hours_slept': 13, 'sick_day_rating': 3, 'hours_not_at_home': 0.5}, {'day': 'Sunday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 2}]



```python
### Part 2 Sorting example 

hours_slept = [14.5, 6, 6.5, 6.5, 8, 13, 8]

sorted_hours_slept = sorted(hours_slept)

print(sorted_hours_slept)
```

    [6, 6.5, 6.5, 8, 8, 13, 14.5]



```python
hours_not_at_home = [0, 0, 13, 13, 1, 0.5, 2]

sorted_hours_not_at_home = sorted(hours_not_at_home)

print(sorted_hours_not_at_home)

```

    [0, 0, 0.5, 1, 2, 13, 13]



```python
### Part 3: adding in Monday
dear_data.append(
    {
        "day": "Monday",
        "hours_slept": 6,
        "sick_day_rating": 1,
        "hours_not_at_home": 13,
    }
)

print(dear_data)
```

    [{'day': 'Monday', 'hours_slept': 14.5, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Tuesday', 'hours_slept': 6, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Wednesday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Thursday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Friday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 1}, {'day': 'Saturday', 'hours_slept': 13, 'sick_day_rating': 3, 'hours_not_at_home': 0.5}, {'day': 'Sunday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 2}, {'day': 'Monday', 'hours_slept': 7.5, 'sick_day_rating': 2, 'hours_not_at_home': 4}, {'day': 'Monday', 'hours_slept': 6, 'sick_day_rating': 1, 'hours_not_at_home': 13}]



```python

```
