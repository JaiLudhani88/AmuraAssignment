# AmuraAssignment
Provide rest service that will provide the coordinates of sub rectangle that have max area, for the provided 0-1 matrix

Provided Input will be like
[
  [1,0,0,0,0,1],
  [0,1,1,1,0,0],
  [0,1,1,1,0,0],
  [0,0,0,1,0,0]
]

response comes in json format:
{
  "x" : 1, "y" : 1, "length": 3, "height" : 2
}
