# google-tasks-bookmarklet
A quick way to add a task into Google Tasks.

A bookmarklet is a bookmark that you typically have
in your browser's links toolbar, that when clicked, will
take some action relating to the web page you are currently
viewing. 

Once the Google Tasks Bookmarklet is added to your browser,
clicking it will add a new task to your Google Tasks list,
and the initial task title and task notes fields will be
populated with the title and URL of the page you are viewing.
You will also be given an opportunitiy to set a date for
the task via a calendar picker, and the title and notes
can be edited before adding the task.

## How to Install

If you don't want to modify this script, and just want to
use it, or try it, please follow the instructions at:
http://geoffmobile.com/blog/contact/google-tasks-bookmarklet

The above link will allow you to install a bookmarklet which
will make use of my publicly deployed instance of the script. 
It will run under the permissions of your own Google account.

## How to Use

Click the bookmarklet from any page to create a Google Task
with the URL and page title (from your current page)
prepopulated into the task's title and notes fields.

## Video Demo

For a video demo of this bookmarklet in action, please visit
the following Youtube video:
https://www.youtube.com/watch?v=hUhI6mus8iA

## How to Modify the Source and Deploy your own Instance

If you would like to modify this script and deploy your own
version of it, here is what you need to know:

The script is based on code that is part of another Github
repo, called google-apps-script-samples. However that repo
is not required for the Bookmarklet to work.

The instructions on how to deploy the Bookmarklet's back
end are the same as the app called simple_tasks, of which
the instructions can be found at:
https://github.com/google/google-apps-script-samples/tree/master/simple_tasks

Once you have deployed the back end, to use the bookmarklet,
create a bookmark in your browser bookmark's toolbar
that contains the bookmark in bookmarklet.txt, replacing the
URL in the bookmarklet with the URL to your own deployed
instance.

## Supported Browsers

This has been tested in Google Chrome, Firefox, and IE.

## More Information

For more information, please see my blog at:
http://geoffmobile.com/blog/contact/google-tasks-bookmarklet

## Author

Geoff Peters http://twitter.com/gpeters
Vancouver, BC, Canada