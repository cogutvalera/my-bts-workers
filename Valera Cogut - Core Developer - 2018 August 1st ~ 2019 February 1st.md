BitShares Core Development Worker Proposal (1.14.xx)
====================================================

* Author: Valera Cogut
* Status: Draft
* Date: 19 July 2018

Background
----------

https://valeracogut.com/contacts

`Valera Cogut is an independent professional software and video game developer who has worked in the game industry since 2008 and 
has more than 12 years of programming experience. He is a passionate software and game developer with different areas of expertise. 
Before diving into the game industry many years ago, Valera created websites and applications with PHP, the Yii framework, 
the Zend framework, Relational Database Management Systems, Apache and Nginx, C#, C++, C, Objective-C, Java, Python, UML, 
and many other technologies. Having a mathematical background (analytical geometry, linear algebra, logic, statistics and probability, 
differential equations, graph theory, and mathematical analysis), he finally realized that game development was his mission. 
Reusable designs, optimized algorithms, clean code, and elaborated workflows—these things make him happy. 
Valera has had the opportunity to produce titles for multiple platforms, including Windows Phone, Android, iOS, PC, and Mac. 
Today, he continues to produce fun and original games, participate in game jams, and author books. 
He was a technical reviewer for Unity Android Game Development by Example Beginner's Guide, Packt Publishing.`

Now I want to be highly involved into only BitShares Core project full-time without trying to find another job for me to earn money for my family.

Currently I've researched a couple of months BitShares Core C++ project and fixed already some issues there, 
you can see my list of issues and my Pull Requests here https://github.com/cogutvalera/my-bts-issues/blob/master/README.md

I want to continuously contribute and not randomly !

Worker
------

I've created an account `valera-worker` (ID `"1.2.1037514"`). The account will be
changed to trusted community escrow multi-sig (3/4) schema with these members (subject to change so far):

- `valera-worker` (me)
- `abit`
- `xeroc`
- `fox`

I've created a worker `"Valera Cogut - Core Developer - 2018 August 1st ~ 2019 February 1st"` (ID `"1.14.xxx"`).

The worker will mainly focus on the bitshares-core repository, tasks include:

* code review
* issues fix
* bugs fix
* new features development
* documentation
* mentoring
* coordination

Duration and Pay
----------------

This proposal will last for 6 months, start from 1st August 2018 till 1st February 2019.

One-time cost reimbursement:
* Worker account lifetime fee: `694.70219 BTS`
* Worker creation fee: `xxx * 20% = yyy BTS`

This is a full time contract, 8 hours per day, 5 days a week, 160 hours per month of development.

Monthly pay:
* $12,000 per month, as 160 hours per month * $75 per hour

USD payment will be in bitUSD with method developed by @xeroc
([link](https://github.com/xeroc/worker-proposals/blob/master/2017-02.md#worker)):

* 4.38291 BTS/bitUSD = settlement price of bitUSD at the moment of writting (2018-07-19)
* 2.5 = multiplier to cover market fluctuations and borrow at 2.5x collateral if needed
* 12000 usd/month * 4.38291 bts/usd * 2.5 = 131,487.3  BTS/month
* 131,487.3 / 30 = 4,382.91 BTS/day

Note: I will be receiving 12,000 bitUSD per month, but not really 4,382.91 BTS per day.
The multi-sig scheme in worker account `valera-worker` will only send the correct exact
amount of funds to me. Rest of BTS will be burned back to the chain at a proper time.
