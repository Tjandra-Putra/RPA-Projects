# Applicant Tracking System
Projects are completed and developed using Ui Path Studio

## Objective
```
This workflow automates and filters applicants' resume(.PDF) or any other documents(.PDF) based on "Key Words" 
from a specific folder and move successful applicants' file over to a new folder.

For this example, applicants' resumes are filtered based on key word:

1) Bootstrap
2) C#

Location File : Process Applicant
Destination File : Selected Applicant
```

## Usage
```
1) Specify location of where the applicants are stored
2) Specify destination of where the filtered applicants are to be stored
3) Impose constraints under "if" block. Optional to use "AND" / "OR"

true and false = false
true or false = true;

```

## Logic & Process Flow
```
1) Input - Directory path for location file
2) Input - Directory path for destination file
3) For each item in the location file 
4) Impose constraint, if TRUE : Counter++ and move file function

```
