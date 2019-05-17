# birthday-kata

This kata emphasizes test-driven development, separation of concerns, and testing with I/O boundaries.

Credit: http://matteo.vaccari.name/blog/archives/154

### Need
Members of your team have decided to build a small application that will automatically send out birthday greeting emails whenever it is a team member's birthday.

### Requirements

Records for each member on the team are stored in a comma-separate values file like so:

```
last_name,first_name,date_of_birth,email
Doe,John,1982-10-08,john.doe@foobar.com
Ann,Mary,1975-09-11,mary.ann@foobar.com
```

If today is a person's birthday, the program will send out an email to the team member in the following format:

```
To: {email address}
Subject: Happy Birthday!

Have a happy birthday, {first name}!


- Your team
```
