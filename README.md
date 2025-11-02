# hey, i'm shubham 👋

backend engineer who likes making things fast and not break in production.

## what i'm doing rn

building microservices for a utility platform that processes ~25k transactions/day. mostly fighting with databases, optimizing queries, and making APIs go brrr.

just got APIs from 2000ms → 500ms by actually using indexes properly (shocking, i know). also migrated 450k records from ancient SAP system without burning everything down.

## my stack

```java
// backend stuff
Java 17, Spring Boot, REST APIs
Microservices (the good kind, not the buzzword kind)
JWT, OAuth, all that auth jazz

// databases
MongoDB (with actual indexes this time)
PostgreSQL, Redis
Query optimization is my cardio

// cloud & ops  
AWS: EC2, S3, SQS
Docker (containerize all the things)
CI/CD pipelines that actually work

// testing
JUnit, Mockito, JMeter
load testing until it breaks, then fix it
```

## stuff i've shipped

**200+ REST APIs** across billing, payments, auth modules  
handling 50k+ requests/day with <500ms latency

**payment integrations** for PhonePe & Cashdesk  
because processing money is slightly important (99.5%+ success rate)

**zero-downtime migration** of 450k records  
SAP → MongoDB without anyone noticing

**75% faster APIs** through:
- compound indexes (they're not just for show)
- Redis caching the right way
- query optimization that actually matters

**message queues** with AWS SQS  
async processing so servers don't die during peak load

**10k+ SMS/day** through third-party integrations  
real-time notifications that actually arrive

**PDF generation** for bills & receipts  
Apache PDFBox doing the heavy lifting

## how i work

if it's not tested, it doesn't work. wrote tests that caught 200+ bugs before they hit prod.

obsessed with performance metrics. if i can't measure it, i can't optimize it.

production issues get fixed fast. <2hr MTTR because nobody likes being paged at 3am.

code reviews are for learning, not ego battles.

## currently exploring

- distributed systems (CAP theorem is wild)
- kubernetes orchestration (yaml hell but worth it)
- system design patterns (trying to not reinvent wheels)
- better observability (logs are just the beginning)

## let's talk

- linkedin: [shubham-kumar-tripathi](https://linkedin.com/in/shubham-kumar-tripathi)
- email: shubham.tripathi68225@gmail.com
- location: noida, india (open to remote)

down to chat about:
- why your API is slow (probably missing indexes)
- microservices architecture (and when NOT to use them)
- scaling databases without crying
- production war stories
- that one bug you've been hunting for 3 days

---

**pro tip**: if your query takes >100ms, add an index. if it still takes >100ms, add a better index. if it STILL takes >100ms... maybe rethink your schema.

*currently caffeinated and debugging*
