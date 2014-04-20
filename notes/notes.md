_NOTE: This is an exact copt of notes.docx_

##(8 - 9:30) Purescript workshop:
http://functorial.com/

https://github.com/paf31/lambdaconf

https://github.com/purescript/purescript

https://github.com/purescript/starter-kit

<br />
to import the array library:
```purescipt
:i Data.Array
```
<br />
ex1 solution:
```purescipt
let
  divBy3 0 = true
  divBy3 1 = false
  divBy3 2 = false
  divBy3 n = divBy3 (n-3)
```

<br />
ex2 solution:
```purescipt
let numDivBy3 n = length $ filter divBy3 $ upTo n
```

<br />
ex3 solution:
```purescipt
let
  sum [] = 0
  sum(h : t) = h + sum t

sum (range 1 10)
```
<br />
##(9:30 – 10:30) Scaling Gilt
http://www.yonigoldberg.com


<a href="mailto:jgoldberg@guilt.com">jgoldberg@guilt.com</a>

Gilt: 
e-commerce company

moved from monolithic Rails app to micro services

LOSA (Lots Of Small Apps)

####Data storage:
- H2 (for inventory service)
- Kafka
- Voldemort
- RabbitMQ

Zeus (for load balancing)

Docker (Linux containers; lighter than VM)
Zookeeper

OpenGrok

IonCannon

<br />
##(10:30 – 12) Building Web Apps w/ Clojure
https://github.com/rkneufeld/pedestal-workshop

https://speakerdeck.com/rkneufeld/web-apps-on-a-pedestal

Datomic

<br />
##(1 – 3) Intro to functional game programming
https://github.com/jdegoes/lambdaconf-2014-introgame

Recursion types: induction and co-induction

Mondas: functional programming design pattern.

<br />
##(3 – 4) Building web services w/ RedEyes & Scala
https://github.com/redeyes/redeyes

<br />
##(4 – 5) Rapture & Scala
http://rapture.io/

http://rapture.io/gettingStarted

https://github.com/propensive/rapture-io

