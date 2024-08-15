# Documents
Once Created or Uploaded, manage revisions, collaborate on the document content, share with other document manager users, publish to libraries, add to personal collections, set reminders and activities and much more

## Managing Documents

### Action Bar
* **Comment**<br>Each Document comes with its own Timeline to allow users to discuss, plan, and collaborate. The Comment option in the Action Menu allows you to add a new comment to the Timeline discussion.
* **Share**<br>The Share option allows you to share your document with other users that are helping write or review the document.
* **Upload**<br>The Upload action lets you upload a new version of the document.
* **Change Owner**<br>Providing ownership ownership of a document helps ensure that the document is maintained and managed. Handover of documents can sometimes occur. For this the Change Owner option lets you assign the document to another owner.
* **Add to Collection**<br>Collections are used to help organize your documents and make them easier to find within your Document List. Use this Action Item to add this document to one of your existing Collections.
* **Review**<br>Create a review activity for the document
* **Change Status**<br>Three different statuses are available: Draft, Active, and Retired. Draft documents will normally indicate that they are still being worked on and are not ready for consumption by a user. Active documents are deemed ready for publishing to a Library. Once a document is active, the Publish option is made available. Retired documents will be hidden from any Library that it is currently associated with.
* **Publish**<br>The Publish action is only available on a document once the status of the document has been set to Active. Once a document is Active you can then publish it to one or more libraries.
* **More**<br>Under the More menu you have the ability to Delete a document or Lock/Unlock a document.

## Lifecycle Processes
Document Manager Progress Tracker.png
Invoke a lifecycle process to automate management of documents lifecycle events. Typical examples of document lifecycle processes include:

### Publishing a Document to a library
* Approvals
* Status Changes
* Publishing

### Document reviews
* Managing documents amends and approvals
* Retiring documents and removing them from libraries
* Managing review dates
* Lifecycle processes. This need to be enabled from settings in the admin console under the Document Manager tile:
webapp.documentmanager.bpmLifecyle.enabled - This is off by default

### Roles
* Lifecycle processes can be configured in the admin console under the Document Manager Tile and accessible to users who have the Business Process Manager role
* All users will need a User level Document Manager role in order to perform actions in the lifecycle process - DocManager User as an example
* Lifecycle processes can only be invoked by users who have the Can Modify Metadata Permissions for the document they want to invoke a lifecycle against

### Using Lifecycle Processes
Lifecycle processes can be manually invoked from the document view
If no lifecycle processes are created, the lifecyle option will not be visible on the document view
Once lifecycle processes are created and Active, users with the docmanager designer role will be able to configure which lifecycle processes to make available using the Design this button option
Document users will then be able to manually invoke available Active lifecycle processes
Only one lifecycle process can be running at any given time
Once a lifecycle process is started, it's progress tracker will be visible at the top of the document view
Once a lifecycle process has finished it's progress tracker will disappear from the document view

### Lifecycle History
Once a lifecycle process has completed, the Heads Up Display will disappear. It is possible to view all previous lifecycle processes which have run on the document from the Lifecycle Button drop down and Show History option

It is possible to view the heads up display for each and every lifecycle process which was run against the document.

### Configuring the Lifecycle Process button

Default Label: Provide the button with a display value (which will be visible when a lifecycle process is not in flow
Translated Label: Add additional language variants of the default label, which will be displayed to users viewing the document view in the language defined in the user settings
Button Styling: Choose a background color which will be used for the button when a lifecycle process is not in flow
Drop Down Options: Configure the lifecycle processes you wish to make available from the button
By Default this will show all Document Manager defined lifecycle processes defined in the admin console and marked as active
Use the trash bin icon to remove any lifecycle processes you do not want to make available from the button
Use the arrows to re-order the lifecycle processes in the drop down
Edit each drop down options to set the following:
Set the Default Label as it will appear in the drop down
Set any translated label values
Set Button Style and Image when the lifecycle process is running
Disabling Manual Options When a Lifecycle Process is Running
Optionally you may want to disable the ability for a user to perform certain manual actions whilst a lifecycle process is running. The following options can be disabled globally, from the settings tile under document manager in the admin console. These settings will then apply to any document which has a lifecycle process actively running against it.

Publishing: webapp.documentmanager.bpmLifecyle.whileLifecycleRunning.disableManual.publishing
Off by default so manual actions are permitted
Set Review Date: webapp.documentmanager.bpmLifecyle.whileLifecycleRunning.disableManual.setReview
Off by default so manual options are permitted
Status Change: webapp.documentmanager.bpmLifecyle.whileLifecycleRunning.disableManual.statusChange
Off by default so manual actions are permitted
Opening / Downloading / Checkout File for Editing
If the document you are viewing has been Uploaded you will see options to:

Open - This will download the current version of the document
Checkout for Editing - This will also download the current version of the document but will also lock the document preventing other users from checking the document out the current version of the document for editing
If checking out for editing, when finished you can upload a new version and Unlock the document from the More drop down option
If the document you are viewing has been created in document manager you will see the option to Open, this will open and display the document and provide the following options:

Edit - Open the document for editing. If you save changes to the document whilst editing, this will create a new version of the document and add the previous version of the document as a revision (if revision tracking was enabled for the document
Details - Switch back to the details view of the document
Full Screen - Display the document in full screen mode
Print - Allow for the printing of the document
Toggle View - Switch between the full screen mode and normal view mode

## Revisions
Version Tracking - for documents where revision tracking was enabled, a Revisions section will hold all previous versions of the document. Users who have rights to the document will be able to open / download any previous versions of the document

Revisions are added in two different ways depending on the type of document which has been created:
Uploaded Documents - Each time a new Upload is added to the document, the previous active version is added to the revisions history and the new upload becomes the live version
Created Documents - If a document has been created using Document Manager's text or drawing document options, each time you save changes to the document, this will create a new live version of the document, and the previous live version is added to the revisions history.
It is possible to view the changes between revisions from the revisions section of the document. This will show anything which has been removed (red) or added (green)

## Timeline
The Timeline (activity stream) on a document plays two roles, firstly it acts as an audit trail for changes to the document, such as new revisions added, or the ownership of the document has changed, as well as recording any changes of rights assigned to users the document has been shared with.

As well as acting as an audit trail it also provides an environment for users who have rights to the document to be able to collaborate on the content of the document, discuss changes or additions they would like to make. As with all activity streams all collaboration in the form of posts and comments is recorded and supports embedding rich media content like images, videos etc as well as supporting wiki mark up.

Follow - Use the follow option to see updates to the document timeline appear on your newsfeed
Mobile - Follow updates on your native mobile, as well as contribute to collaboration on the document via the documents timeline on the go

## Tags
Add tags to your document to help with searching and organizing.

Use the Global search to find documents based on Tags
Create self organizing collections of documents based on documents with specific Tags
Filter and find documents in Libraries based on Tags
View All Documents you have access to through a Tag Cloud View

## Activities
Create Activities relating to the management of the document.

View and receive notifications relating to document activities in your My Activities views, and on your mobile app.