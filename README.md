# Tehran-noDST-timezeno
Due to probability of not changing DST on IRST since 2022, it's needed to change zonefile in linux OSes  

## Installation

1- Download Tehran-noDST file from repository.

```
git clone https://github.com/mhnmoa/Tehran-noDST-timezone.git
```

2- Copy Tehran-noDST file into /usr/share/zoneinfo/Asia/Tehran-noDST

```
cp Tehran-noDST-timezone/Tehran-noDST /usr/share/zoneinfo/Asia/Tehran-noDST
```

3- Set time zone

```
timedatectl set-timezone Asia/Tehran-noDST
```

4- Test new timezone

```
timedatectl
```
