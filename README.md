#Frontend Panel For Mailer App
*   This is the front end panel for the Mailer App ReST API Developed.  
  
*   The Basic Template is from [AdminLTE](https://almsaeedstudio.com/themes/AdminLTE/documentation).  

*   The Technology used is [Bootstrap UI](http://getbootstrap.com/getting-started/),which makes it responsive.  

*   For Form submisson [AngularJS](https://docs.angularjs.org/guide/introduction) and [jQuery.ajax()](http://api.jquery.com/jquery.ajax/) is used.  
 
*   A Dashboard(index.html) is provided which gives the basic help needed for user to understand. 

*   URL for form submission might be needed to change as per apache environment set up(apache port used is:8080).

    ###It contains mainly 3 functionality
    ####Send Mail
       *   The page url is pages/sendmail.html
       *   The main function of this page is to send mail to a list.
           
    ####Manage List  
       *   Create List
           *   The page url is pages/createlist.html
           *   The main function of this page is to create a new list.
       *   View Lists
           *   The page url is pages/viewlists.html
           *   The main function of this page is to view all created lists.
       *   Delete List
           *   The page url is pages/deletelist.html
           *   The main function of this page is to delete the list.
           
    ####Manage Member
       *   Add Member
           *   The page url is pages/addmember.html
           *   The main function of this page is to add a member to the specified list.
       *   View Members
           *   The page url is pages/viewmembers.html
           *   The main function of this page is to view all members of a specified list.
       *   Edit Member
           *   The page url is pages/editmember.html
           *   The main function of this page is to edit the specified member of specified list.
       *   Delete Member
           *   The page url is pages/deletemember.html
           *   The main function of this page is to delete the specified member of specified list.
