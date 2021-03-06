**Purpose:** Quick Tasks allow users to perform common actions directly from their dashboard.

There are four tasks that users can accomplish using the Quick Task menu on the right side of the "My Dashboard" page.
Each task bar can be collapsed so that the accompanying fields are hidden from view. The “Go to My Project” and
“Upload Files” tasks are open by default so that their required input fields are shown.

Go to My Project
------------
**Purpose:** "Go to My Project" allows users to search their own projects.

Instead of conducting a site-wide :doc:`search <../search/search_index>` that brings the user to a page of results,
"Go to My Project" allows the user to search only the :doc:`projects <../projects/projects_index>` and
:ref:`components` that they are a :ref:`contributor <contributors>` on.

If the user has no projects, no search bar appears. Instead, text fills the space and reads::

    You do not have any projects yet. Click below to create one!

Public projects that have been added to the user’s dashboard, but that they are not a contributor on, are not
included in the Go to My Project search.

Users can type in the empty field, using the keyboard arrow keys or their mouse to select a result from the dropdown.
Hitting enter or clicking “Go” sends the user to the project. If no results are returned, no dropdown appears. Users can
clear the field by clicking the ‘x’ on the right side of the text field.

After typing the name of a project, a second field appears where the user can enter the name of a component. Clicking
into the empty field and pressing the down key shows a dropdown with the project’s components listed as results—if any
exist. The user can select a component with their mouse or the arrow keys. This is an optional field. Entering a component
here and hitting enter or clicking “Go” will send the user to the component.

.. _quick-project:

Create a Project
-------------
**Purpose:** "Create a Project" is the only means of making a new OSF project.

To create a project, the user types a title into the Title field. Titles do not need to be unique. If a user enters HTML,
it will render as text. Unicode characters are accepted. No character limit is imposed.

The description is optional. Users can enter text here to briefly describe their project. If a user enters HTML, it will
render as text. Unicode characters are accepted. No character limit is imposed.

Users can select a :ref:`template <templates>` to use as a base for their project’s structure. This is optional. The user can select any
project of theirs from the dropdown, or can begin typing the name of one of their projects to narrow the dropdown results.

Clicking “Create” produces the project and brings the user to the :ref:`Project Overview <overview>`.

Register a Project
------------
**Purpose:** "Register a Project" allows the user to initiate the :ref:`registration <registrations>` of a project from their dashboard.

Users can search for a project or component of their own, in order to register it. Users enter text into the empty
field to begin a search, using the keyboard arrow keys or their mouse to select a result from the dropdown. Clicking
“Continue registration” or hitting enter brings the user to the registration template selection page. Users can clear the
field by clicking the ‘x’ on the right side of the text field. Any project or component that the user has admin permissions
on will show as a search result.

Public projects that were added to the Project Organizer, but that the user is not a contributor on do not get listed
in the search results.

Upload files
--------
**Purpose:** Allows users to upload a file or files to a project from the dashboard.

To upload a file to a project, users can select one or multiple files from their computer and drag and drop them onto the
dropzone in the "Upload Files" panel on the "My Dashboard" page. Alternatively, users can click on the dropzone. Clicking on the
dropzone will open a file selector that allows them to search their computer to select files for upload.

Any file type can be uploaded. Folders cannot be uploaded. If a user attempts to upload a folder through drag and drop,
a red text alert appears above the “Upload” button that reads::

    Cannot upload directories, applications, or packages.

Folders cannot be selected if the user chooses to use the file picker in order to select files—they can only be opened.

If one file is selected for upload, the dropzone shows the name of the file and an image representing the type of file.
When a file is selected for upload, an 'x' appears in the upper right corner of the dropzone. Clicking on the ‘x’ allows
the user to clear out the selected file.

If multiple files are selected for upload, the dropzone shows the number of files and an image representing multiple files.
Clicking on the ‘x’ in the upper right corner of the dropzone allows the user to clear out the selected file.

After selecting a file the user must select a project or create a new project.

If the user selects a file for upload and presses the "Upload" button without selecting a project to upload to, a red text
alert appears above the "Upload" button::

    Please select a project.

Clearing the selected file or selecting a project will remove the alert.

To select an existing project to upload to, the user can type
a search query into the "Select a project" field. This will search projects the user has :ref:`write permissions <permissions>`
on. Searching for a project that the user does not have access to or does not have the ability to upload files to will return no results.
Matching results are shown as items in a dropdown; as the user continues to type the results are narrowed. Results indicate the project
name and the date of the last modification. To select a project, the user can click on the appropriate result or use their
arrow keys to navigate to the result and press the return key to select it.

After selecting a project, the user can also search for a component. This will search the components of the project that the user has
write permissions to. This search field is shown even if no components exist.

.. todo:: Log the above as an error.

When a project has been selected, an 'x' appears in the upper right corner of the field. Clicking the 'x' clears the field.
After a project is selected, the "OR Upload to a new project" option is removed from the panel.

If the user selects an existing project to upload to but does not have a file selected, no error is returned but no action is taken.

.. todo:: Log the above as an error

To create a new project to upload to, the user can type the name they wish to give their new project into the "OR Upload to a new project"
field below the "Select a project" field.

.. todo:: After typing a new project name, the "Select a project" field should be gone.

If the user types the name of a new project into the "OR Upload to a new project" field and presses the "Upload" button but does not
have a file selected for upload, a red text alert appears above the "Upload" button::

    Please select at least one file to upload.

If the user correctly selects a file and indicates a project to upload to, the file uploads and a green text alert appears
above the "Upload" button:

    Success!

The page then automatically forwards to the "Files" page of the project that the file was uploaded to.