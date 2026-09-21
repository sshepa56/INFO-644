```python

data = [
    {
        "day": "Monday",
        "hours_slept": 14.5,
        "sick_day_rating": 5,
        "hours_not_at_home": 0
    },
    {
        "day": "Tuesday",
        "hours_slept": 6,
        "sick_day_rating": 5,
        "hours_not_at_home": 0
    },
    {
        "day": "Wednesday",
        "hours_slept": 6.5,
        "sick_day_rating": 3,
        "hours_not_at_home": 13
    },
    {
        "day": "Thursday",
        "hours_slept": 6.5,
        "sick_day_rating": 3,
        "hours_not_at_home": 13
    },
    {
        "day": "Friday",
        "hours_slept": 8,
        "sick_day_rating": 2,
        "hours_not_at_home": 1
    },
    {
        "day": "Saturday",
        "hours_slept": 13,
        "sick_day_rating": 3,
        "hours_not_at_home": 0.5
    },
    {
        "day": "Sunday",
        "hours_slept": 8,
        "sick_day_rating": 2,
        "hours_not_at_home": 2
    }
]

print(data)
```

    [{'day': 'Monday', 'hours_slept': 14.5, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Tuesday', 'hours_slept': 6, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Wednesday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Thursday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Friday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 1}, {'day': 'Saturday', 'hours_slept': 13, 'sick_day_rating': 3, 'hours_not_at_home': 0.5}, {'day': 'Sunday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 2}]



```python
sorted_by_sleep = sorted(data, key=lambda x: x["hours_slept"])

print("Sorted by hours slept:")
print(sorted_by_sleep)

sorted_by_time_away = sorted(data, key=lambda x: x["hours_not_at_home"])

print("\nSorted by hours not at home:")
print(sorted_by_time_away)
```

    Sorted by hours slept:
    [{'day': 'Tuesday', 'hours_slept': 6, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Wednesday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Thursday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Friday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 1}, {'day': 'Sunday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 2}, {'day': 'Saturday', 'hours_slept': 13, 'sick_day_rating': 3, 'hours_not_at_home': 0.5}, {'day': 'Monday', 'hours_slept': 14.5, 'sick_day_rating': 5, 'hours_not_at_home': 0}]
    
    Sorted by hours not at home:
    [{'day': 'Monday', 'hours_slept': 14.5, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Tuesday', 'hours_slept': 6, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Saturday', 'hours_slept': 13, 'sick_day_rating': 3, 'hours_not_at_home': 0.5}, {'day': 'Friday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 1}, {'day': 'Sunday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 2}, {'day': 'Wednesday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Thursday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}]



```python
sorted_by_sleep = sorted(
    data,
    key=lambda x: x["hours_slept"],
    reverse=True
)

print(sorted_by_sleep)
```

    [{'day': 'Monday', 'hours_slept': 14.5, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Saturday', 'hours_slept': 13, 'sick_day_rating': 3, 'hours_not_at_home': 0.5}, {'day': 'Friday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 1}, {'day': 'Sunday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 2}, {'day': 'Wednesday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Thursday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Tuesday', 'hours_slept': 6, 'sick_day_rating': 5, 'hours_not_at_home': 0}]



```python

new_day = {
    "day": "Monday (Week 2)",
    "hours_slept": 7.5,
    "sick_day_rating": 2,
    "hours_not_at_home": 4
}

data.append(new_day)

print(data)
```

    [{'day': 'Monday', 'hours_slept': 14.5, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Tuesday', 'hours_slept': 6, 'sick_day_rating': 5, 'hours_not_at_home': 0}, {'day': 'Wednesday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Thursday', 'hours_slept': 6.5, 'sick_day_rating': 3, 'hours_not_at_home': 13}, {'day': 'Friday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 1}, {'day': 'Saturday', 'hours_slept': 13, 'sick_day_rating': 3, 'hours_not_at_home': 0.5}, {'day': 'Sunday', 'hours_slept': 8, 'sick_day_rating': 2, 'hours_not_at_home': 2}, {'day': 'Monday (Week 2)', 'hours_slept': 7.5, 'sick_day_rating': 2, 'hours_not_at_home': 4}, {'day': 'Monday (Week 2)', 'hours_slept': 7.5, 'sick_day_rating': 2, 'hours_not_at_home': 4}]



```python

```
