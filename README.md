# Issue Management

### Description
This web application will be used for issue tracking within an organization. It allows employees of metacube to easily create and track and update status of issues. Issues are related to the following department -
* Admin
* HR
* Network
* Finance
 

#### User Creation

1. Use Google Oauth 2.0 API or custom user management for user creation
2. Users may be assign themselves to any of these departments - HR, Networks, Admin, Finance. Users are member of the organization.
3. Admin of each department can add users in their department.  
4. User can update their profile


#### Create/Update an Issue

1. It should allow a user to create a issue.
2. Issue must have any of these priority - LOW, MEDIUM, HIGH
3. Issue can be assigned to multiple users within an organization
4. Issue can have multiple tags associated so that it can be searched easily
5. Issue may be assigned to any one of these department - HR, Networks, Admin, Finance
6. Issue details (tags, assigned members and status) can be updated by all the users assigned to an issue and issue owner
7. Issue can be closed by issue owner


#### View/Search Issues

1. An issue can be seen by its owner and all assigned members
2. Users can see count of open and resolved issues
3. Issues can be searchable by its title, status and associated tags
4. Admin can see all the issues that are not assigned to any of the department and can assign it to anyone


#### Comments on an Issue

1. All the users assigned to an issue and issue owner can add comment on it. Comment may not required to have a reply button.
2. Comment can be removed by comment owner and issue owne


#### Images

![Create Issue]
(https://github.com/gbohra/get-16-issues/blob/master/imageedit_5_8318581614.png)

![Issues Listing]
(https://github.com/gbohra/get-16-issues/blob/master/imageedit_11_3957937460.png)

#### Good to have features

1. Issues can be estimated in hours and the issue resolver can update the actual time (in hours) taken to resolve the issue
2. Email can be sent to the all the users assigned to an issue at the time of issue creation/updation
