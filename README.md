# EOSCSP-test-vectors
There are 4 series of vectors:
1. Real problems
2. Highly conflict problems
3. Medium problems
4. Small problems

Each file name is composed of three fileds: <problem seriess>_<number of requests>_<random number>.json

Each file contains the following fields:
{
 "planningWindow": "<Integer>",
 "numOfSattelites": "<Integer>",
 "numOfUsers": "<Integer>",
 "numOfRequestsPerUser": "<Integer>",
 "numOfObservationsPerRequest": "<Integer>",
 "satellites": [
{
  "id": "<Integer>",
  "capacity": "<Integer>",
  "orbitStartTime": "<Integer>",
  "orbitEndTime": "<Integer>"
},
	.
	.
	.
],
 "users": [
{
  "id": "<Integer>",
 "requests": [
{
  "id": "<Integer>",
 "observations": [
{
  "id": "<Integer>",
  "reward": "<Integer>",
  "satellateId": "<Integer>",
  "startTime": "<Integer>",
  "endTime": "<Integer>"
},
	.
	.
	.
]
	.
	.
	.
]
	.
	.
	.
]
