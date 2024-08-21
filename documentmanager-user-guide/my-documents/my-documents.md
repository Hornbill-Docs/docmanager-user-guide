# My Documents
My Documents is where you can upload, create, or manage documents that you can then share and collaborate on with other Hornbill users. This is a great alternative to storing files in network shares or passing documents around by email. Use My Documents to collaborate, schedule reviews, store revisions, and much more.


## Creating documents
You can use the **Create new** button and its adjoining down-arrow button to do the following:
* To create a new document, click **Create new**.
* To create an external link to a document, click the **Create new** button's down-arrow and select **External Link**.
* To upload an external document, click the **Create new** button's down-arrow and select **Upload Document**.

### About uploading documents
**Maximum upload size.** This is set by default to 10MB. This can be increased on your instance using this system setting in the admin console: `communications.maxfileUploadSize`

**File types.** By default, the following file types *cannot* be uploaded: `exe`, `bat`, `cmd`, `js`, and `vbs`. To allow these file types on your instance, use this system setting in the admin console: `security.fileUploadRestriction.webdav.types`

### About creating external links
When you click **Create new** > **External Link**, you are creating a document in Document Manager that opens an external link. This option only *links to* the document; there is no integration with the document repository. So, for example, permissions must be managed separately.

As with any other type of document, users can search for the externally linked document by its title or description and any tags it has been given.

## Navigating the My Documents views
Use the navigation options on the left side to view documents in the main panel.

### My Documents
In this section, you can view documents organized as follows:

* **Home View.** This option allows you to revert the document list view to that which you have set as your Home View.
* **All My Documents.** This option shows you all documents that you own or that have been shared with you.
* **Documents I Own.** This option shows you documents for which you are set as the owner.
* **Unorganized Documents.** This option shows you documents that you own or that have been shared with you and are not already added into a manual collection
* **Documents Due For Review.** This option shows you any documents for which the review date is due today or is overdue.

### Collections
In this section, you can view documents that you have grouped into collections, either using the Self-organizing or Manual add-to-collection option.
* Available collections will be listed
* Use the + New Collection to create a new personal document collection

### Libraries
In this section you can select to view documents which have been added to libraries which you have the rights to view.
* All libraries which you have the rights to view will be listed.

## Document List
The Document List displays the documents based on the chosen view from the right hand side

### Document Info and Options
Each document which is displayed will display the document name, description, who the document owner is, when it was created and last updated. You also have the option to perform the following actions from the document list:

* Open - Open the document
* Properties - Be taken to the properties of the document where you can manage and collaborate on the document
* Add To Collection - Choose to add the document to any Manual type collections you have (this option will not be displayed if you do not have any manually organized collections created)

### Filters, Views and Ordering
Use the following filters, views and sorting options to manage which documents will be displayed
* **Quick Search**<br>Use this option to filter the documents based on keywords in the document title or description.
* **Status**<br>Use this option to only display documents which are in Draft, Active, Retired or a combination of the three.
* **View**<br>Toggle between the List and Thumbnail options to display the documents in list or thumbnail views.
* **Order By**<br>Use this option to order the documents by, and sort these by ascending or descending order.
    * Title
    * Owner
    * File Type
    * Creation Date
    * Last Updated
* **Home View**<br>Use this option to Set or return to your Home View.
    * ***Set current view as my home***<br>Use the drop down option to set the current view as your home view.
    * ***Home***<br>Use the home icon to switch your current view to your home view.
    * ***Refresh***<br>Use this option to manually refresh the content of the current view.

### Library and Collection Specific Properties
When viewing documents from a library or collection an additional Cog option will be displayed on the tool bar options:

* **Collection view Cog**<br>This will allow you to view the properties of the collection view. In the case of a Self Organizing collection it will show you which tags are used to make up the view, and allow you to edit the collection properties.
* **Library view Cog**<br>This will allow you to view the properties of the library, it will show the library title and description as well as who the library has been shared with (users, roles, groups)
* **Tag Filtering**<br>When viewing a library of documents, you can filter the documents in this library to only those which carry specific tags by selecting the tags you wish to apply.

<!-- https://wiki.hornbill.com/index.php?title=My_Documents -->