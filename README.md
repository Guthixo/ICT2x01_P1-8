<p align="center">
  <img src="https://thumbs.gfycat.com/IdenticalFarawayAfricangoldencat-size_restricted.gif" alt="Car" />
</p>

# ICT2x01 Intro. to Software Engineering
Singapore Institute of Technology
## Meet the Team
- Crystal Choo Jia Xian (BS006)
- Koh Jia Cheng (BS005)
- Lee Wei Jie (BS005)
- Mohammad Shahmizan Bin Sham Affandi (BS006)

# Getting Started
### Car

### Webpage

# Workflow
1. `master` branch will be our *baseline* branch for pull request of both `mastercar` and `masterwebpage`
2. `mastercar` branch and `masterwebpage` branch are the *baseline* branches for both the car development and web development
3. Any developments to either the `mastercar` or `masterwebpage` will mean that you need to first branch off from them respectively. Then when your branch is working, you can merge it into the `mastercar` or `masterwebpage`.
   1. Every member shall branch off of each parent from both `devcar` and `devwebpage` respectively (illustrated below)
   2. Off the branch, the any development of code and project shall branched if necessary
4. At any time, the latest commit to `mastercar` and `masterwebpage` will be the baseline of the branch. Both of which shall only be the working copies and same iteration
5. Hierarchy breakdown are as such:
   1. `master`
      1. `mastercar`
            1. `devcar`
      2. `masterwebpage`
         1. `devwebpage`

### Branches

1. Branch Naming Conventions
The branch name must follow hierarchical branch that the team have already worked out on in the WORKFLOW.md

2. Branching Conventions
New features / fixes should be **branched off** the respective development branches if needed

1. Merging Conventions
*Code committed -> Code reviewed -> Code merged into `master` branch -> Baseline* 
Committed code should be properly reviewed by another party of the team. 
Request for a pull, before merging from the new branch to the respective development branches.

# Testing
- Black Box Testing
   - UAT
   - Login
      - No Pin Specified
      - Wrong PIN Specified
      - Maximum Limit Exhausted (PIN Lockout)
      - Login Attempt After Maximum Limit Exhausted (PIN Lockout)
      - Clear Field
      - Successfully Logged-in


- White Box Testing
   - A full test suite using pytest library testing for 
     - Accessing 
       - Home page
       - Play page
         - Splitline function
         - Splitline adapter design function
         - With wrong instructions
         - With correct instructions
         - Witn no instructions
       - Challenge page
       - Design page
       - List page

- Car Demonstration


## Black Box Testing

### USER ACCEPTANCE TESTING
---
<table>
  <tr>
    <td><img src="/img/tests/ST1.jpg"/></td>
    <td><img src="/img/tests/ST1.gif"/></td>
  </tr><tr>
    <td><img src="/"/></td>
    <td><img src="/"/></td>
  </tr><tr>
    <td><img src="/"/></td>
    <td><img src="/"/></td>
  </tr><tr>
    <td><img src="/"/></td>
    <td><img src="/"/></td>
  </tr><tr>
    <td><img src="/img/tests/ST5.jpg"/></td>
    <td><img src="/img/tests/ST5.gif"/></td>
  </tr><tr>
    <td><img src="/img/tests/ST6.jpg"/></td>
    <td><img src="/img/tests/ST6.gif"/></td>
  </tr><tr>
    <td><img src="/img/tests/ST7.jpg"/></td>
    <td><img src="/img/tests/ST7.gif"/></td>
  </tr><tr>
    <td><img src="/img/tests/ST8.jpg"/></td>
    <td><img src="/img/tests/ST8.gif"/></td>
  </tr><tr>
    <td><img src="/img/tests/ST9.jpg"/></td>
    <td><img src="/img/tests/ST9.gif"/></td>
  </tr>
</table>

### System Test Case 1
![ST1 - Starting the Webpage](/img/tests/ST1.jpg)
- ST1 tests if user are able to access the localhost webpage.

![ST1 - Starting the Webpage](/img/tests/ST1.gif)

### System Test Case 5
- ST5 test for page redirection after a user enters the webpage and click on the play button, the page will redirct user to the play state, which should show the game screen.

![ST5 - Redirect Page to Play](/img/tests/ST5.gif)

### System Test Case 6
- ST6 test for the ability to drag and drop commands to a provided dropbox to send to the car on the webpage. Once user hits 'Send!', commands in the dropbox would be sent to the car.

![ST6 - Drag & Drop Commands to send to Car](/img/tests/ST6.gif)

### System Test Case 7
- ST7 test for user setting up instructions to send to the car. When the user press 'Sent!', the screen is suppose to be the commands sending through.

![ST7 - Set Instructions to send to the Car](/img/tests/ST7.gif)

### System Test Case 8
- ST8 test if user is able to enter the homapage using dedicated home button.

![ST9 - Terminated the web application](/img/tests/ST8.gif)

### System Test Case 9
- ST9 test if user is able to exit the app.

![ST9 - Terminated the web application](/img/tests/ST9.gif)

### LOGIN
---

- No PIN Specified

![Login Test - No PIN](/img/tests/login-no-pin.gif)

- Wrong PIN Specified

![Login Test - Wrong PIN](/img/tests/login-wrong-pin.gif)

- Maximum Limit Exhausted (PIN Lockout)

![Login Test - Max Attempts](/img/tests/login-max-attempts.gif)

- Login Attempt After Maximum Limit Exhausted (PIN Lockout)

![Login Test - Post Max Attempts](/img/tests/login-post-limit-attempt.gif)

- Clear Field

![Login Test - Clearing Field](/img/tests/login-clear-fields.gif)

- Successfully Logged-in

![Login Test - Success](/img/tests/login-success.gif)


## White-box Testing

First, ensure that you are in the ```Webpage``` folder.

Ensure that the virtual environment is activated to be used as pytest is saved in venv.

You can run the test using this command:
```
pytest -v
```
Alternatively, you can use to get the coverage:
```
pytest-cov
```
You can refer to the library documentation 

The file that does the testing can be found [documentation](https://docs.pytest.org/en/6.2.x/contents.html "here"):

```Webpage/test_fullsuite.py```



### Full Test Suite testing all endpoints and functions

![Whitebox Testing - Success](/img/tests/whitebox-testing-allfunctions.gif)



<p align="center">
  <img src="https://thumbs.gfycat.com/UltimateBlandCrane-size_restricted.gif" alt="Car" />
</p>

## Car Demonstration
![Car Demo](/img/tests/P2_P7_Demo(New))

# Reflections
## Crystal Choo Jia Xian (BS006)
<to do>
  
## Koh Jia Cheng (BS005)
<to do>
  
## Lee Wei Jie (BS005)
<to do>
  
## Mohammad Shahmizan Bin Sham Affandi (BS006)
<to do>

