# Use-Case Specification: Deleting a Category

# 1. Deleting a Category

## 1.1 Brief Description
When a category is no longer needed it should be deleted. With this the to delete category will disappear from the category list and the database. In the case of files still existing in this category, they will be moved to the enclosing category or the root.

## 1.2 Mockup
[//]: # (![OUCD](./Mock_ups/Clear%20Chat.PNG))

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
- The user created/joined a group
- The User is either one of the admins or has a role which authorizes him for the action

# 5. Postconditions
- The category is deleted from the database and all views
- Files still inside are moved accordingly

### 5.1 Save changes / Sync with server

# 6. Effort Estimation
4