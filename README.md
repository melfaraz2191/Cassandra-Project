# Cassandra-Project
This project, part of the Udacity Data Engineering Nanodegree, involves building an Apache Cassandra database named sparkifydb for Sparkify, a music app.

Objective
The primary aim is to enable efficient querying of song play data. The database schema is designed to handle the following queries:

### 1. Artist, Song Title, and Length for Specific Session and Item
For sessionId=338 and itemInSession=4:

- Artist: Faithless <br>
- Song: Music Matters (Mark Knight Dub)  <br>
- Length: 495.31 seconds  <br>
### 2. Artist, Song, and User Details Sorted by Session and Item
For userId=10 and sessionId=182, Sylvie Cruz listened to:

- Keep on Keepin On by Down To The Bone <br>
- Greece 2000 by Three Drives  <br>
- Kilometer by Sebastien Tellier  <br>
- Catch You Baby by Lonnie Gordon  <br>
### 3. User Names for a Specific Song
Users who listened to All Hands Against His Own:

- Jacqueline Lynch  <br>
- Tegan Levine  <br>
- Sara Johnson  <br>
### Steps
- Model the NoSQL database using Apache Cassandra.  <br>
- Build an ETL pipeline to extract, transform, and load data.  <br>
