# Use-Case Specification: Clearing a message

# 1. Clearing a message

## 1.1 Brief Description
This is a functionality that most modern chat apps come with so we wanted to provide it as well. It should only be possible to clear
the entire chat with the appropriate role to avoid any misuse of the functionality. 

## 1.2 Mockup
![OUCD](./Mock_ups/Clear%20Chat.PNG)

## 1.3 Screenshots


# 2. Flow of Events

## 2.1 Basic Flow


### Activity Diagram


### .feature File
n/a

## 2.2 Alternative Flows


# 3. Special Requirements


# 4. Preconditions
- The user has an account
- The user created/joined a group and is the admin of the group
- There is at least one message in the chat

# 5. Postconditions
- The messages that were stored locally were deleted and can not be shown anymore


### 5.1 Save changes / Sync with server

# 6. Effort Estimation
2