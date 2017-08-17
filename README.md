# peer2peer
Peer2Peer is an iOS app that connects volunteer tutors to students in need of academic help based on subjects and physical proximity with a rapid, minimalist front-end and a powerful RESTful backend and database.  

## CAC 2016
Peer2Peer was submitted to the [2016 Congressional App Challenge](http://www.congressionalappchallenge.us/2016-winners/), won 1st in the 18th Congressional District of California, and received [recognition from Congresswoman Anna Eshoo](https://eshoo.house.gov/constituent-services/house-student-app-challenge/). Mentioned in an [article in The Mercury News](http://www.mercurynews.com/2017/08/14/app-challenge-open-to-district-18-high-school-students/).  
Watch the video submission [here](https://www.youtube.com/watch?v=PQ4SMc8Uc-E).


## components
Peer2Peer was made with two separate components: the iOS front-end and the RESTful backend.

 1. [iOS front-end](https://github.com/p2p-app/p2p-iOS)
    1. The client is written in Swift 3 and was created with Apple Xcode
 2. [RESTful backend](https://github.com/p2p-app/p2p-rest)
    1. The server is a combination of a couple subcomponents that interact with each other
        1. RESTful API written in PHP7
        2. MySQL database for storing user data
        3. WebSocket server written in PHP7 for realtime location streaming (under construction)

## authors
Peer2Peer was created by [Anuv Gupta](https://github.com/anuvgupta), [Arnav Gudibande](https://github.com/arnav-gudibande), and [Amar Ramachandran](https://github.com/amarjayr), members of [sfhacks](https://github.com/sfhacks).  
We were interviewed by the newspaper at our school, Saint Francis High School. Read the [article here](http://www.sfhs.com/page.cfm?p=815&newsid=6932).
