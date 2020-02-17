---
title: 'Crashing storage servers causing service distruptions'
date: '2020-02-07 00:00:00 +0100'
ticket:
  status: 'Investigating'
  scope: 'Mail, userdata, web services'
---

**Description:**

    An issue with our storage servers are causing them to crash and hang, requiring physical intervention.

**Impact:**

    The servers serve maildirs, userdata, userwww, as well as a few legacy virtual machines handling mail connections, userwww and more.

**Update:**

    * 20200207 00:00 UTC+1
    Userdata server starts crashing once a day.
    ---

    * 20171208 18:00 UTC+1
    Same symptom on gfs server serving VM data. Manual intervention required every time due to broken Out-of-bounds connection.
    ---
    
    * 20171217 12:00 UTC+1
    Crashing after server hardware changes, problem identified on 12-13 storage servers. Believed to be thermal issues OR kernel incompatability.
    ---
