## Intro to Table Joins
In this lecture we're going to start off with a challenge. Complete the Challenge before moving on to the video. You won't be able to complete the exercises in the video if you don't complete the challenge.

## Challenge No. 1
Create a `Phone` table with the following structure:

| Column Name | Data Type | Length | Nullable | Primary Key | Identity Seed |
| ----------- | --------- | ------ | -------- | ----------- | ------------- |
| Id | Numeric |  | No | Yes | Yes |
| PersonId | Numeric |  | No |    |   |
| AreaCode | Character | 3 | No |  | |
| Prefix | Character | 3 | No |   |  |
| Number | Character | 4 | No |   |  |
| Extension | Variable Character | 10 | Yes |   |  |
| Type | Variable Character | 25 | No |   |  |
| CreatedDate | DateTime |  | No |   |  |
| ModifiedDate | DateTime |  | No |   |  |

Hint:
* Review the [SQL Server Programming](https://www.youtube.com/watch?v=Av3JBPDg524&t=730) video

## Foreign Key Constraints
1. Watch the lecture on YouTube titled [Foreign Key Constraints](https://youtu.be/NcmbhIwpulE)
1. Follow along and do the execises
1. Complete this lecture before moving on (one lecture builds on top of another)

## Table Joins
1. Watch the lecture on YouTube title [SQL Server Table Joins](#)
1. Make sure you completed the [Foreign Key Constraints](#) before doing this lecture
1. Foreign Keys have to be in place prior to attempting Table Joins

## Challenge No. 2
Create an `Address` table with the following structure:

| Column Name | Data Type | Length | Nullable | Primary Key | Identity Seed |
| ----------- | --------- | ------ | -------- | ----------- | ------------- |
| Id | Numeric |  | No | Yes | Yes |
| PersonId | Numeric |  | No |   |   |
| Line1 | Variable Character | 100 | No |  |   |
| Line2 | Variable Character | 100 | Yes |   |   |
| City | Variable Character | 100 | No |   |   |
| State | Character | 2 | No |   |   |
| PostalCode | Character | 5 | No |   |   |
| Plus4 | Character | 4 | Yes |   |  |
| CreatedDate | DateTime |   | No |   |   |
| ModifiedDate | DateTime |   | No |   |   |

Hint:
* Review the [SQL Server Programming](https://www.youtube.com/watch?v=Av3JBPDg524&t=730) video

## Challenge No. 3
Alter the `Address` table and add a Foreign Key Contraint to the `Person` table just like we did in the [Foreign Key Constraints](https://youtu.be/NcmbhIwpulE) video.

Hint:
* Review the [Foreign Key Constraints](https://youtu.be/NcmbhIwpulE) Video

## Challenge No. 4
Write `SELECT` Statements with a `JOIN` to display several rows of data containing information from the `Person` and `Address` tables.

Hint:
* Review the [SQL Server Table Joins](https://www.youtube.com/watch?v=OqNirtQsz88) video

## Challenge No. 5
Whiteboard all the SQL Statements you created in either SSMS or Azure Data Studio.
1. Your goal is to them from memory
1. Pick at the code on the screen only momentarily to refresh your mind
