# Commit Hacking
[example](https://github.com/CalamityAdam?tab=overview&from=2020-12-01&to=2020-12-31)
(i use fish shell)

2020 - months with 31 days - 01 03 05 07 08 10 12
```bash
for i in 1 2 3 4 5; for m in 05; for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31; git commit -m 2020-$m-$d --date="2020-$m-$d 04:56:12" --allow-empty; end; end; end; git push;
```

2020 - months with 30 days
```bash
for i in 1 2; for m in 04 06 09 10 11; for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30; git commit -m 2020-$m-$d --date="2020-$m-$d 04:56:12" --allow-empty; end; end; end;
```

2020 - february
```bash
for i in 1 2 3 4 5; for m in 02; for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29; git commit -m 2020-$m-$d --date="2020-$m-$d 04:56:12" --allow-empty; end; end; end;
```

2021 - 30 days
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 01 03 04 05 ; for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31; git commit --m 2021-$m-$d --date="2021-$m-$d 04:56:12" --allow-empty; end; end; end;
```

2021 - 31 days
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 01 03 04 05 ; for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31; git commit -m 2021-$m-$d --date="2021-$m-$d 04:56:12" --allow-empty; end; end; end;
```

```bash
for i in 1 2 3 4 5 6 7 8 9 10; for i in 1 2 3 4 5 6 7 8 9 10; for m in 01; for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31; git commit -m 2021-$m-$d --date="2021-$m-$d 04:56:12" --allow-empty; end; end; end; end;
```

```bash
for i in 1 2 3 4 5 6 7 8 9 10; for i in 1 2 3 4 5 6 7 8 9 10; for m in 01 03 05 07; for d in 01 03 05 07 09 11 13 15 17 19 21 23 25 27 29 31; git commit -m 2019-$m-$d --date="2019-$m-$d 04:56:12" --allow-empty; end; end; end; end;
```

```bash
for i in 1 2 3 4 5 6 7 8 9 10; for i in 1 2 3 4 5 6 7 8 9 10; for m in 08 10 12; for d in 01 03 05 07 09 11 13 15 17 19 21 23 25 27 29 31; git commit -m 2019-$m-$d --date="2019-$m-$d 04:56:12" --allow-empty; end; end; end; end;
```

```bash
for i in 1 2 3 4 5 6 7 8 9 10; for i in 1 2 3 4 5 6 7 8 9 10; for m in 04 06 09 11; for d in 01 03 05 07 09 11 13 15 17 19 21 23 25 27 29; git commit -m 2019-$m-$d --date="2019-$m-$d 04:56:12" --allow-empty; end; end; end; end;
```




# ADAM
[example](https://github.com/CalamityAdam?tab=overview&from=2018-12-01&to=2018-12-31)
### january
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 01; for d in 01 02 03 04 05 06 07 14 21 28 10 17 24 31; git commit -m 2018-$m-$d --date="2018-$m-$d 04:56:12" --allow-empty; end; end; end;
```

### february
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 02; for d in 05 06 07 08 09 10 18 19 20 21 22 23 24 25; git commit -m 2018-$m-$d --date="2018-$m-$d 04:56:12" --allow-empty; end; end; end;
```

### march
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 03; for d in 04 11 18 26 27 28 29 30 24 17 10 03; git commit -m 2018-$m-$d --date="2018-$m-$d 04:56:12" --allow-empty; end; end; end;
```

### april
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 04; for d in 09 10 11 12 13 14 15 22 29 25 18; git commit -m 2018-$m-$d --date="2018-$m-$d 04:56:12" --allow-empty; end; end; end;
```

### may
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 05; for d in 02 09 14 15 16 17 18 19 06 27 28 29 30 31; git commit -m 2018-$m-$d --date="2018-$m-$d 04:56:12" --allow-empty; end; end; end;
```

### june
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 06; for d in 01 02 04 12 20 26; git commit -m 2018-$m-$d --date="2018-$m-$d 04:56:12" --allow-empty; end; end; end;
```

### july
```bash
for i in 1 2 3 4 5 6 7 8 9 10; for m in 07; for d in 02 08 09 10 11 12 13 14; git commit -m 2018-$m-$d --date="2018-$m-$d 04:56:12" --allow-empty; end; end; end;
```














# CHECKERS
[example](https://github.com/CalamityAdam?tab=overview&from=2017-12-01&to=2017-12-31)

do this 1 month at a time. after each month, check to see if the first day of the month should have commits or not. if the month should have commits, then use odds. if it should not have commits, then use evens. use the 3rd option for a month that should be odds and has 31 days.

```bash odds
for i in 1 2 3 4 5; for m in 01; for d in 01 03 05 07 09 11 13 15 17 19 21 23 25 27 29 31; git commit -m 2017-$m-$d --date="2017-$m-$d 04:56:12" --allow-empty; end; end; end;
```

```bash evens
for i in 1 2 3 4 5; for m in 01; for d in 02 04 06 08 10 12 14 16 18 20 22 24 26 28 30; git commit -m 2017-$m-$d --date="2017-$m-$d 04:56:12" --allow-empty; end; end; end;
```

```bash
for i in 1 2 3 4 5; for m in 12; for d in 01 03 05 07 09 11 13 15 17 19 21 23 25 27 29 31; git commit -m 2017-$m-$d --date="2017-$m-$d 04:56:12" --allow-empty; end; end; end;
```


# super mega script to fill up a full year with 20 commits each day
[do it for the lulz](https://github.com/CalamityAdam?tab=overview&from=2000-12-01&to=2000-12-31)
currently set for the year 2020, which is a leap year. the last loop is february, remove `29` from that loop for a non leap year. this takes about 6 minutes to run, and pushes the commits after every month to ensure all commits are counted. this is 7000+ commits, with over 200 individual pushes, so be patient!

```bash
# loop 20 times
for i in 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20;
  # for all months with 31 days
  for m in 01 03 05 07 08 10 12;
    for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31;
      # empty commit, manually set date and add commit message of that date. (replace 2000 in both places for different year)
      git commit -m 2020-$m-$d --date="2020-$m-$d 04:56:12" --allow-empty;
    end; git push;
  end;
  # for all months with 30 days
  for m in 04 06 09 11;
    for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30;
      git commit -m 2020-$m-$d --date="2020-$m-$d 04:56:12" --allow-empty;
    end; git push;
  end;
  # for february
  for m in 02;
    for d in 01 02 03 04 05 06 07 08 09 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29; # <- remove 29 for a non leap year
      git commit -m 2020-$m-$d --date="2020-$m-$d 04:56:12" --allow-empty;
    end; git push;
  end;
end;
```
