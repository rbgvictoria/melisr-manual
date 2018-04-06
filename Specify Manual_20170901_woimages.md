**MELISR MANUAL**

# <span style="font-variant:small-caps;">Introduction</span>

Specify is a database software application designed to support the efficient computerisation and management of biological collections. Specify is distributed by the Specify Software Project, based at the Biodiversity Institute at the University of Kansas. The Specify Software Project and its predecessor, the MUSE Project, have been supported by the US National Science Foundation since 1987.

Specify was designed to the specifications of the collection community data model. Installations can be configured with multiple taxonomic collections as separate databases, or data can be managed together as a single, multi-disciplinary database. Specify’s design and functions support botany, entomology, herpetology, ichthyology, invertebrate zoology, mammalogy, ornithology, palaeobotany, and vertebrate and invertebrate palaeontology.

The Specify Software Project website is located at <http://www.specifysoftware.org>.

## <span id="_Toc284178230" class="anchor"><span id="_Toc492047864" class="anchor"></span></span>Specify set-up

### <span id="_Toc492047865" class="anchor"><span id="_Toc284176748" class="anchor"><span id="_Toc284178231" class="anchor"><span id="_Toc283306484" class="anchor"></span></span></span></span>Installing Specify

To install Specify:

1.  Navigate to the following folder: Q:\\Applications\\Specify

2.  Copy the Specify\_windows.exe file to your Desktop (the version will be included in the file name)

3.  Double-click the Specify\_windows.exe file

4.  Click **Run** in the **Open File – Security Warning** window:

    &lt;&lt;image&gt;&gt;

-   If you receive an error message about Java, run the Java runtime environment update file in Q:\\SOE, and then try installing Specify again

1.  When prompted, click **OK** to select English as the language:

    &lt;&lt;image&gt;&gt;

2.  Click **Next** for all options in the Specify **Installer** window to accept the default installation settings

3.  Click **Done** to close the installer.

### Opening and closing Specify

#### Logging in

1.  Open Specify from the shortcut button or your programs list.

    If you are presented with a window asking about internet connection settings, click **Cancel**. Once you have edited your preferences (see below), you will no longer be presented with this window upon start-up.

> &lt;&lt;image&gt;&gt;
>
> If you are presented with an **Updater** window, click **Cancel** to prevent Specify from updating your current installation. Updates to new versions must only be done by database administrators so we can ensure that the new version works properly with our customisation of Specify.
>
> &lt;&lt;image&gt;&gt;

Click **Exit** when asked if you really want to exit (this will only exit you from the update installer, not from logging in to Specify):

> &lt;&lt;image&gt;&gt;

1.  Enter your user name and password in the login window

2.  Click **Login**

> &lt;&lt;image&gt;&gt;
>
> If your login fails, click on **More information** and check that the database settings match those below.
>
> &lt;&lt;image&gt;&gt;

##### Configuring the master key

If you have just installed Specify on your computer, or if you are using Specify on a computer other than your own, you will need to enter your master key before you can log in. The master key for your username will have been e-mailed to you by the database administrator.

1.  Click on the arrow next to **More Information** in the **Specify Login** window

2.  Click on the **Configure Master Key** symbol

3.  Enter your master key in the **Encrypted Username/Password** field

4.  Click **Continue**

5.  Click **Login** in the login window.

> <span id="_Toc283306485" class="anchor"></span>&lt;&lt;image&gt;&gt;
>
> If you are unsure of your master key, see a database administrator.

##### Choose a collection

There are seven different ‘collections’ within MELISR, which are used to catalogue different types of information and to manage data for curation tasks. All users have access to the main *National Herbarium of Victoria* collection. If you have access to other collections, you will be presented with a window prompting you to choose which collection you want to use.

-   ***Incoming exchange*** – a holding database used to manage and check data associated with incoming exchange, prior to adding the records to the *National Herbarium of Victoria* collection

-   ***MEL Census*** – holds the data from the old MEL Census, which contains information on MEL’s holdings

-   ***National Herbarium of Victoria*** – the principal collection in MELISR, used to catalogue specimens from the main component of the State Botanical Collection

-   ***Non-MEL loans*** – used to manage incoming loans

-   ***Photographs of specimens­*** – used to catalogue photographs or cibachromes of specimens held at other herbaria

-   ***Victorian Conservation Seed Bank­­*** – used to catalogue seed collections and associated seedlings from the Victorian Conservation Seed Bank

-   ***Victorian Reference Set*** – used to catalogue specimens stored in the Victorian Reference Set

-   ***deBRIs*** – a temporary collection used as a holding place for collecting data associated with the backlog of exchange material from BRI, prior to adding the records to the *National Herbarium of Victoria* collection.

##### Editing preferences

When you first log in to Specify on your computer, you should edit the system preferences to stop Specify checking for updates each time you open the database:

1.  Click on the **Edit** file menu, then select **Preferences**:

> &lt;&lt;image&gt;&gt;

1.  Under the **System** options, un-tick the **Check for updates at startup** box:

> &lt;&lt;image&gt;&gt;

1.  Click **OK** to save the changes.

#### Closing Specify

To close Specify, do one of the following:

-   Click on the **Close** symbol in the top right corner of the window

-   Select **Exit** from the **File** menu

-   Press **Alt+F4**.

## <span id="_Toc492047867" class="anchor"><span id="_Toc283306486" class="anchor"><span id="_Toc284176751" class="anchor"><span id="_Toc284178232" class="anchor"></span></span></span></span>Using Specify

### <span id="_Ref303847473" class="anchor"><span id="_Toc492047868" class="anchor"></span></span>Specify Help

Specify contains an inbuilt help system that can be opened from anywhere in the application by pressing the **F1** key. The help system is designed to provide an overview of the modules within Specify, as well as context-sensitive help for a given task. When performing a task in Specify, press **F1** to open the **Specify Help** page that corresponds to the current task. **Specify Help** includes a table of contents, and full-text search capabilities.

<span id="_Toc283306487" class="anchor"></span>&lt;&lt;image&gt;&gt;

<span id="_Toc284176752" class="anchor"><span id="_Toc284178233" class="anchor"></span></span>The most relevant information from the **Specify Help** pages has been incorporated into this manual.

### The Specify interface

The main sections of the Specify interface are described below.

&lt;&lt;image&gt;&gt;

#### Menu bar

The menu bar provides access to user preferences, system configuration settings and data entry settings.

##### File

The file menu contains the **Exit** command. Specify can also be closed by pressing **Alt+F4** or clicking the **Close** symbol in the upper right corner of the window.

&lt;&lt;image&gt;&gt;

##### Edit

Formatting preferences (including font and font size) can be edited under **Preferences** in the **Edit** menu. Note that the formatting prefernces will apply to all users, not just you, so please see a database administrator if you think the formatting settings should be changed.

&lt;&lt;image&gt;&gt;

##### Data

The **Data** menu contains options for data entry. Click on an item to activate it, or use the keyboard to select it from the menu and press **Enter**. A tick will appear next to active items. Note that you need to have a data entry form open in the Workspace before you can activate items in the **Data** menu.

**Carry forward** copies data from certain fields from one record to the next during data entry. See **Carry** **forward** (p. 20) for more information about this feature.

**Save and new** will automatically open a new data entry form once a record has been saved. If **Save and new** is activated, but you have finished databasing, close the **Collection object** tab to remove the unused open form. If you close a data form, and then open a new form in the workspace, **Save and new** will not automatically be activated, even if there is a tick next to the **Save and new** button. To re-activate it, deselect **Save and new** under the **Data** menu, then re-select it. To check if **Save and new** is activated, look at the Save button at the lower right-hand corner of the form: the button will read ‘Save/New’ when **Save and new** is active.

The **Auto numbering** function automatically increments numbers in fields that have been formatted with an auto numbering scheme. **Auto numbering** is turned on by default when a form is opened in the workspace. There are currently no auto-numbered fields in MELISR, so there is no need to turn **Auto numbering** on or off.

**Batch identify** allows you to add new determinations to multiple collection objects at the same time. See for **Batch identify** (p. 38) for instructions on how to use this feature.

##### System

The **System** menu contains system administration functions that can only be accessed by database administrators.

##### Tabs

The **Tabs** menu contains options for closing tabs, and for configuring the side bar.

Tabs that are open in the workspace can be closed under the **Tabs** menu. You can either close the current tab, all tabs, or all tabs except the current tab. Tabs can also be closed by clicking on the **Close** symbol in the **Tab bar**, or by pressing **Ctrl+W**.

The **Configure side bar** tool allows you to add or remove forms from the side bar. By default, the **Collection object**, **Taxon** and **Agent** forms are displayed in the **Data** module, and the **Collection object**, **Taxon**, **Agent** and **Loan** tables are displayed in the **Query** module. The side bar can also be configured by right-clicking the mouse in the side bar.

##### Help

The **Help** menu contains a link to the inbuilt **Specify Help**, plus a range of administrative functions, most of which can only be accessed by database administrators. The **Submit feedback** function allows users to send comments about particular aspects of the database to the Specify Software Project. To ensure that feedback is coordinated, and that bugs are properly documented, please provide feedback to the MELISR database administrators, rather than to Specify Software.

#### Task bar

The task bar contains buttons that are used to initiate database modules. Clicking on a button in the task bar will open a list of the components for that module in the side bar.

##### Welcome

The **Welcome** screen is viewed each time Specify is opened. It contains a summary of current loans and recent data entry activity.

##### Data

The **Data** module contains the forms that are used for entering, editing and viewing collection information. The main data forms used in MELISR are **Collection object**, **Taxon** and **Agent**.

##### Trees

The **Trees** module displays data in the **Geography**, **Taxon** and **Storage** tables as hierarchical trees. The data in these tables can also be viewed in forms.

##### Reports

Specify allows you to create reports that provide overviews of your collecting data. At MEL, we have programmed our reports outside of Specify, so we don’t use any customised **Reports** within Specify; however, the **Reports** module must be enabled in order to print summaries of query results.

##### Interactions

The **Interactions** module is used to create and manage loans, exchange and donations.

##### <span id="_Toc284176766" class="anchor"><span id="_Toc284176765" class="anchor"></span></span>Statistics

The **Statistics** module provides a summary of the holdings, loans and data entry activity in Specify. Three graphical reports are also available in the side bar when the **Statistics** module is active.

##### Query

The **Query** module allows you to retrieve data stored in MELISR in an organised way. The main forms that are queried in MELISR are the **Collection object**, **Taxon** and **Agent** forms.

##### Workbench

The **Workbench** module allows you to organise and validate data prior to permanently saving it in the database.

##### Plugins

The **Plugins** module contains web services that assist with georeferencing and visualising specimen records.

#### Side bar

The **Side bar** allows a list of components for each module to be activated in the workspace, such as data forms and record sets. The contents of the side bar will change to reflect the tools available within the active module.

The side bar can be resized by guiding the mouse over the line separating the side bar from the workspace until a crossbar appears, then clicking and dragging the side bar to the desired size.

#### Workspace

The **Workspace** is the area within which tasks are completed. Data entry forms, query forms, query results and reports all open in this space. Clicking a module component from the side bar list opens it in the workspace. Up to eleven workspace windows can be opened at one time.

#### Tab bar

The **Tab bar** indicates what tasks are open in the workspace. Tabs are labelled with an icon and module name. If the same module is opened in more than one window, the tab label will reflect the number of modules that are open. Click on the tabs to move between them. Click on the **Close** symbol or press **Ctrl+W** to close a tab. If you close a tab before saving data or saving changes to a query, you will be prompted to save your changes.

#### Status bar

The right-hand side of the **Status bar** displays the current collection database and user name. MELISR currently includes seven collections: *National Herbarium of Victoria*, *Victorian Reference Set, Non-MEL loans*, *Photographs of specimens*, *Incoming exchange*, *MEL Census* and *deBRIs*.

The left-hand side of the status bar displays status reports for tasks that are being performed in the database, such as warnings for invalid data entry.

#### Trash can

A saved item listed in the side bar (such as a record set, query or report) can be deleted by dragging and dropping it onto the image of the trash can, or by right-clicking the item and selecting ‘Delete’.

### <span id="_Toc283306488" class="anchor"><span id="_Toc284176772" class="anchor"><span id="_Toc284178234" class="anchor"><span id="_Toc492047870" class="anchor"></span></span></span></span>Related information

The names of the forms in Specify represent the category of information that is stored in the corresponding table: the **Collection object** table stores information about herbarium specimens; the **Taxon** table stores information about taxon names; the **Geography** table stores information about geographic places; and the **Agent** table stores information about people and organisations. However, much of the information in one type of table is linked to information in a related table. For example, a **Collection object** record contains information about taxon names, geographic places and people that is stored in the **Taxon**, **Geography** and **Agent** tables respectively.

These links, or relationships, between different tables prevent users from having to re-type the same information in different records, which increases the efficiency of data entry and reduces the incidence of errors. Separating data into fields within related tables also allows the data to be searched in a more precise way.

#### Relationships between tables

There are four types of relationships between tables in Specify: one-to-one, many-to-one, one-to-many and many-to-many.

##### One-to-one

A one-to-one relationship is a relationship between a primary and related table in which one record in the primary table can only be linked to a single record in the related table. For example, the collecting information for a single specimen is unique to that collection, thus a single record in the primary data table (in this case, **Collection object**) can only be linked to a single record in each related table that stores collecting information (such as the **Collecting event** table and the **Collection object attributes** table).

##### Many-to-one

A many-to-one relationship is a relationship involving a primary and related table in which many primary records are linked to a single related record in the related table. For example, many specimens are collected on a single collecting trip, thus there are many records in the primary data table (in this case, **Collection object** records) that are linked to a single record in the related table (in this case, the **Collecting trip** table).

Related tables with a many-to-one relationship to the primary table are represented on the form as a query combo box with buttons to edit, add and search for a record within the table:

&lt;&lt;image&gt;&gt;

##### One-to-many

A one-to-many relationship is a relationship involving a primary and related table in which a single primary record links to many related records in the related table. For example, there might be more than one determination on a specimen, thus a single record in a primary table (in this case, a **Collection object** record) is linked to many records in a related table (in this case, the **Determinations** table).

Related tables with a one-to-many relationship are represented on the form as a subform (in either a grid or form view) with navigation controls that allow records in the related table to be added to or deleted from the primary table:

&lt;&lt;image&gt;&gt;

##### Many-to-many

A many-to-many relationship exists where multiple records in one table can be linked to multiple records in a related table. For example, more than one agent can be a collector for a single collection object, and more than one collection object can be collected by the same agent. Many-to-many relationships between tables require an associative table to link the two tables. In this example, the **Collectors** table is the link between the **Collecting event** table and the **Agent** table.

<span id="_Toc283306489" class="anchor"><span id="_Toc284176777" class="anchor"><span id="_Toc284178235" class="anchor"><span id="_Ref303847651" class="anchor"></span></span></span></span>

### Form controls

The following controls are used to enter and display data in the forms. Unless otherwise noted, all actions can be performed by clicking on the symbol using the mouse or pressing the spacebar when the symbol is in focus. The **Tab** key can be used to navigate between fields and form controls.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**              **Definition**     **Action**
----------------------- ------------------ --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  &lt;&lt;image&gt;&gt;   **Incomplete **    Opens a dialogue box listing the required fields that are incomplete (this action cannot be performed using the keyboard)
​                                             
                                             *Note:* The shield only appears once a change has been made inside the form and will disappear once all required fields contain data

  &lt;&lt;image&gt;&gt;   **Warning **       Opens a dialogue box listing fields that contain incorrect data (this action cannot be performed using the keyboard)
​                                             
                                             *Note:* The shield will only display when the form contains errors

  &lt;&lt;image&gt;&gt;   **Collapse **      Hides the form or subform (this action cannot be performed using the keyboard)

  &lt;&lt;image&gt;&gt;   **Expand **        Opens the form or subform (this action cannot be performed using the keyboard)

  &lt;&lt;image&gt;&gt;   **Add **           Opens a new form or subform to add a new record

  &lt;&lt;image&gt;&gt;   **Delete **        Deletes the form or subform record. A record cannot be deleted if it is linked to any other records.

  &lt;&lt;image&gt;&gt;   **Edit **          Opens the related record in a subform for editing

  &lt;&lt;image&gt;&gt;   **Search **        Opens a search dialogue box to search for a record in the form or subform. The fields in the related form will be available to search
​                                             
                                             *Note:* This search treats all search criteria independently. For example, when searching for an agent ‘John Smith’, entering ‘John’ in the **First name** field and ‘Smith’ in the **Last name** field will return results for all agents with the last name ‘Smith’, as well as all agents with the first name ‘John’.

  &lt;&lt;image&gt;&gt;   **Information **   Opens the associated form in view mode

  &lt;&lt;image&gt;&gt;   **View form **     Displays the data in a table as a form in view mode

  &lt;&lt;image&gt;&gt;   **View grid **     Displays the data in a table as a grid in view mode

  &lt;&lt;image&gt;&gt;   **Edit form **     Displays the data in an editable table as a form in edit mode

  &lt;&lt;image&gt;&gt;   **Edit grid **     Displays the data in an editable table as a grid in edit mode

  &lt;&lt;image&gt;&gt;   **Close**          Closes the window or tab
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Navigating between records

Navigation control buttons are found at the bottom of each primary form (e.g. the **Collection object** form), and the bottom of each subform (e.g. the **Determinations** form) when viewed as a form:

&lt;&lt;image&gt;&gt;

Browse through the records by clicking on the appropriate arrow (first, previous, next or last) or press the spacebar when the appropriate button is in focus.

You can also use keyboard controls to navigate between different records (see **Keyboard functions**, p. 19).

### <span id="_Toc283306490" class="anchor"><span id="_Toc284176779" class="anchor"><span id="_Toc284178236" class="anchor"><span id="_Toc492047872" class="anchor"></span></span></span></span>Field types

#### Text box

Text boxes accept any input. The maximum length of text boxes varies between different fields.

&lt;&lt;image&gt;&gt;

#### Number box

Number boxes look the same as text boxes, but will only accept numeric characters.

&lt;&lt;image&gt;&gt;

#### Expandable fields

Expandable text fields allow longer strings of text to be entered. To save space, only the first one or two lines of an expandable text field are displayed on the form. In data entry or edit mode, expandable fields are indicated by an **Edit form** symbol to the right of the field:

&lt;&lt;image&gt;&gt;

In view mode, an **Information** symbol appears to the right of the field:

&lt;&lt;image&gt;&gt;

Clicking on the **Edit form** symbol or the **Information** symbol opens the field in a new window for editing or viewing, respectively:

&lt;&lt;image&gt;&gt;

#### Query combo box

A query combo box allows data to be searched and selected from a related table; information cannot be typed directly into the box.

&lt;&lt;image&gt;&gt;

You can select the data in the related table from a drop-down list, or by searching the related table. If there is no corresponding record in the table, a new record needs to be added to the related table before it can be entered in the primary form. Records in related tables can also be edited.

To select data from a list:

1.  Type the first few letters of the term you wish to use in the box, then either press the down-arrow key on the keyboard, or click on the arrow to the right of the combo box. A list of corresponding records in the related table will appear:

> &lt;&lt;image&gt;&gt;

If the list of matching records is long, it will appear in a separate window:

> &lt;&lt;image&gt;&gt;

You can also press the **Tab** key after entering text; if there is only one record in the table that corresponds to the text you entered, the matching record will be selected.

1.  Select a record from the results by clicking on it, or scroll through the list and press **Enter**.

    If a match cannot be found, ‘Add…’ will appear in the drop-down list. Either select ‘Add...’ or press **Enter** to add a new record to the related table. Pressing **Esc** will clear the list.

To search for data in the table:

1.  Click on the **Search** symbol to the right of the combo box. A search window will appear:

> &lt;&lt;image&gt;&gt;

1.  Type in either the entire name, or the first few letters followed by a wildcard (\*):

> &lt;&lt;image&gt;&gt;

1.  Select a record from the results by clicking on it or scrolling through the list and pressing **Enter**.

> If a match cannot be found, close the search window and click on the **Add** symbol to add a new record.

To edit an existing record:

1.  Select a record from the drop-down list or the search window

2.  Click on the **Edit** symbol to the right of the combo box. The record will open in a new window:

> &lt;&lt;image&gt;&gt;

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### **Caution!**

  When editing records, remember that the data changes in each related record that references that record. For example, if the spelling of a name in the **Last name** field is changed in an **Agent** record, the agent’s name will be changed in the **Collectors** field in all **Collection object** records that link to that **Agent** record, and not just in the **Collection object** that is currently open. If the wrong collector was entered, the link to the wrong agent record needs to be deleted and a link to the correct agent needs to be added.
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Pick lists

-   A pick list presents a restricted set of values for a field. The values in a pick list can only be edited by a database administrator.

> &lt;&lt;image&gt;&gt;

-   Select an entry from the pick list by clicking on it or pressing the down-arrow, scrolling to the appropriate entry, and pressing **Enter**:

> &lt;&lt;image&gt;&gt;

-   Alternatively, enter the first letter of the appropriate pick list entry to select it. If there is more than one value in the pick list that begins with the same letter, press the first letter of the word until the right value is selected.

-   Pick list fields can be cleared by pressing **Esc**.

#### Date fields

Date fields are formatted fields that only allow valid dates to be entered.

> &lt;&lt;image&gt;&gt;

-   Right-clicking inside a date field will allow you to either insert the current date, or clear the field:

    &lt;&lt;image&gt;&gt;

-   Date fields are preceded by a date type pick list, which allows you to choose from a full date, a month and year, or a year only. Use the mouse or press the down-arrow on the keyboard to open the pick list, scroll to the appropriate date type, then press **Enter** to select it:

> &lt;&lt;image&gt;&gt;

-   If an invalid date is entered, the date field will be highlighted in red, and you won’t be allowed to save the record:

> &lt;&lt;image&gt;&gt;

#### Check boxes

Check boxes are used to indicate the presence of an attribute. Click the check box to tick or un-tick the box, or press the space bar when the check box label is in focus. Note that there are three read-only check boxes on the top of the **Collection object** form that are automatically populated.

&lt;&lt;image&gt;&gt;

#### <span id="forms_field_uses" class="anchor"><span id="_Toc284176785" class="anchor"></span></span>Required fields

Fields that are required have a bold label and the text area is shaded blue:

&lt;&lt;image&gt;&gt;

Records cannot be saved until all required fields contain valid data. An **Incomplete** symbol will appear at the bottom of the form if required fields have not been completed.<span id="forms_tools" class="anchor"><span id="_Toc283306491" class="anchor"></span></span>

#### Read-only fields

Read-only fields are used either to display a field in a different form than the one that it is edited in (e.g. the **Geography** field in the **Collecting event** form), or to display data that is automatically filled in (e.g. the **Created by** and **Last edited by** fields).

There is no border around read-only fields:

&lt;&lt;image&gt;&gt;

### <span id="_Toc284176786" class="anchor"><span id="_Toc284178237" class="anchor"><span id="_Toc492047873" class="anchor"></span></span></span>Form tools

#### <span id="keyboard_functions" class="anchor"><span id="_Toc284176787" class="anchor"><span id="_Ref369165523" class="anchor"><span id="_Ref484511087" class="anchor"></span></span></span></span>Keyboard functions

Specify uses standard keyboard functions for filling out forms via keyboard entry. Keystrokes for the form controls are described in the **\
**

**Form** controls section. The following keyboard functions apply to data entry and editing in forms:

-   **Ctrl+W** will open a record in edit mode

-   **Tab** moves the focus to the next field

-   the spacebar activates a button or ticks a check box

-   the down-arrow key opens a query combo box or a pick list and moves focus to the next item in the list

-   **Esc** closes a query combo box or pick list

-   **Enter** selects a highlighted item within a list

-   **Ctrl+S** will save a record or a query

-   **Ctrl+C** will copy data within a field

-   **Ctrl+P** will paste data into a field

-   **Ctrl+X** will cut data from a field.

The following keyboard shortcuts can be used to navigate between different records in **Data** view:

-   **Alt+Up** will take you to the first record in the set

-   **Alt+Right** will take you to the previous record in the set

-   **Alt+Left** will take you to the next record in the set

-   **Alt+Down** will take you to the last record in the set.

You can also use keyboard shortcuts to close tabs in the workspace:

-   **Ctrl+W** will close the current tab

-   **Ctrl+Shift+W** will close all tabs.

#### <span id="carry_forward" class="anchor"><span id="_Toc284176788" class="anchor"><span id="_Ref303786625" class="anchor"><span id="_Ref484511042" class="anchor"></span></span></span></span>Carry forward

Specify allows you to carry forward data from certain fields into new **Collection object**, **Taxon** or **Agent** records during data entry. **Carry forward** needs to be configured before it can be selected from the **Data** menu.

To configure **Carry forward**:

1.  Click on the **Data** menu in the menu bar (or right-click the mouse within the form)

2.  Select **Configure carry forward**

> &lt;&lt;image&gt;&gt;

1.  Choose which fields you want to carry forward to the next record

2.  Click **OK**.

> &lt;&lt;image&gt;&gt;

**Carry forward** automatically turns on after it has been configured. When configuring **Carry forward**, bear in mind that, if **Carry forward** is enabled for **Determinations**, *all* determinations from the previous record will be carried forward, not just the current determination.

The list of items in the **Configure carry forward** list cannot be changed. It includes fields that you would never want to share between different records, such as **Catalogue number** and **Mixed collection notes**.

To turn **Carry forward** on:

1.  Click on the **Data** menu in the menu bar (or right-click the mouse within the form)

2.  Select **Carry forward**. A tick will appear next to **Carry forward** in the menu.

> &lt;&lt;image&gt;&gt;

To turn **Carry forward** off:

1.  Click on the **Data** menu in the menu bar (or right-click the mouse within the form)

2.  Select **Carry forward**. The tick next to **Carry forward** will disappear.

> &lt;&lt;image&gt;&gt;

**Carry forward** (or **Configure carry forward**) can only be selected from the **Data** menu when a form is being entered or edited in the **Data** module.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### **Caution!**

  When carrying forward locality data from one record to another, remember that if a **Locality** record is shared between two or more records, then subsequently edited, the locality will be changed in *all* **Collection object** records that share that locality, not just in the **Collection object** that is open when the **Locality** record is edited. You should only carry forward locality data if ALL of the details in the **Locality** form (and the associated **Locality details** and **Geocoordinate details**) are EXACTLY the same for the different collecting events, such as is the case for multisheet collections.
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Data entry forms

## <span id="_Toc283306492" class="anchor"><span id="_Toc284178238" class="anchor"><span id="_Toc492047875" class="anchor"></span></span></span>General conventions

-   Information added or interpreted by data entry staff should be entered in brackets \[ \], unless it is entered in the **Curation** **notes** field or the **Georeferencing notes** field.

-   Include a full stop after information in the following text fields: **Locality**, **Habitat**, **Associated taxa**, **Descriptive notes**, **Collecting notes**, **Miscellaneous notes**, **Ethnobotanical info.**, **Toxicity** and **Curation notes**.

-   Include a space between measurements and the unit of measurement (e.g. ‘4 km’, ‘1500 ft’).

-   Where it is necessary to abbreviate words, use only standard abbreviations (see **Appendix** **1. Abbreviations**).

## <span id="_Toc492047876" class="anchor"><span id="_Toc283306494" class="anchor"><span id="_Toc284178239" class="anchor"></span></span></span>Creating and editing records

#### Opening a form

To open a blank data entry form:

1.  Click on the **Data** button in the task bar:

> &lt;&lt;image&gt;&gt;

1.  Select the form that you want to use from the side bar:

> &lt;&lt;image&gt;&gt;
>
> To open a new **Collection object** form after saving a record, click on the **Add** symbol at the top of the **Collection object** form:
>
> &lt;&lt;image&gt;&gt;

#### Adding records to subforms

To add a record to subform of a primary form (e.g. to add a **Determination** record to a **Collection object** record), click on the **Add** symbol in the relevant subform:

&lt;&lt;image&gt;&gt;

If you accidentally add an extra record to a subform, you can delete it by clicking the **Delete** symbol in the relevant subform:

&lt;&lt;image&gt;&gt;

Note that, before you can delete a record in a subform, or add a new record to a subform, the form must contain data in at least one field, and any required fields must be completed.

#### Saving a record

To save a record, press **Ctrl+S**, or click the **Save** button at the lower right-hand corner of the form. The **Save** button will not be activated if there are errors in formatted fields or if any required fields have not been completed. Note that, although the record has been saved, it will remain in edit mode unless you click the **View** button, which makes the record read-only (the **View** button appears next to the **Save** button once a record has been saved).

#### Editing a record

To edit a record, click the **Edit** button at the lower right-hand corner of the form to change it from view (read-only) mode to edit mode. See **Querying Specify** (p. 153) for instructions on how to query for records and open them in form view.

## Collection object form

### <span id="_Toc284176789" class="anchor"><span id="_Toc284178240" class="anchor"><span id="_Toc492047878" class="anchor"><span id="_Toc283306495" class="anchor"></span></span></span></span>Collection object

A collection object refers to an individual item collected during a collecting event. At MEL, a collection object either comprises an entire sheet, packet etc. for non-mixed collections, or the individual component of the sheet, packet etc. for mixed collections. The **Collection object** form contains (or links to) all the collecting and curatorial information known about the herbarium specimen.

<span id="CatalogueNumber" class="anchor"><span id="_Toc284176792" class="anchor"><span id="_Toc284176790" class="anchor"></span></span></span>

##### Catalogue number

The **Catalogue number** is made up of the MEL number and part (see details below):

&lt;&lt;image&gt;&gt;

In order for the transactions to work in Specify, each record needs to have a **\
**

**Catalogue** number in a standard format consisting of seven digits and one letter. Because not all MEL numbers contain seven digits, MEL numbers less than 1 000 000 need to be padded with leading zeroes. For example, the **Catalogue number** for MEL 1234 A would be 0001234A:

&lt;&lt;image&gt;&gt;

###### MEL number

All specimens at the National Herbarium of Victoria should be assigned a unique identification number of up to seven digits. Older specimens often have a MEL number stamped on the sheet. If there is no MEL number assigned to the specimen, assign the next number from your batch of MEL numbers (see the **Numbers** section (p. 197) for details of how to get a new batch of MEL numbers).

MEL numbers are assigned to spirit collections as well as to dry material in sheets or packets. If you come across a spirit collection that has the same MEL number as its corresponding sheet or packet, allocate a new MEL number to the spirit collection (note that only one MEL number should be assigned to the spirit collection, regardless of how many spirit jars there are). Carpological collections, fungal cultures and photographs of specimens held at other institutions all receive a separate MEL number to any corresponding sheet, packet or spirit material.

Microscope slides only receive a unique MEL number if there is no corresponding dry material or spirit collection. Silica gel samples and photographic slides do not receive a MEL number, but are listed as additional preparations of the corresponding sheet, packet or spirit (see **Preparations**, p. 39).

  #### **Note**
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Do not reassign MEL numbers from deaccessioned specimens or from specimens that originally had more than one MEL number stamped on the sheet, just in case the specimen (or data associated with it) has been referenced in a publication or in someone's research notes. The only time we should re-use MEL numbers is if the specimen is still in the process of being accessioned into the collection when we decide to discard it, and the number hasn’t been published online or elsewhere.

###### Part

MEL accession numbers are appended by a letter, which is used to differentiate between different parts of mixed collections. The default for **Part** is ‘A’. The only instance where anything other than A is entered in this field is where there is more than one component on a herbarium sheet (or in a packet or spirit jar), such as more than one taxon on the sheet, or more than one set of collecting information (note that the host of a parasitic plant should not be entered as a separate record unless there is value in doing so, e.g. if it’s a rare taxon or a new record for an area). Thus, the MEL number always refers to the entire sheet, packet or spirit jar, and the part refers to the individual component.

Only one label is printed for a mixed collection. The MEL number, part and taxon name for parts B, C etc. will automatically be printed at the bottom of the label for part A. Where there is more than one set of collecting information on the sheet, the **Mixed collection notes** can be used to provide a brief indication of how parts B, C etc. differ from part A. If there is more than one taxon on the sheet, but the separate components share the one set of collecting information, there is no need to enter anything in the **Mixed collection notes** field.

When you have databased all components of a mixed collection, indicate in pencil on the specimen which component corresponds to part A, B, C etc. If it is unclear which parts of the specimen belong to which set of collecting information, only label the collecting information.

##### <span id="_Toc283306496" class="anchor"><span id="_Toc284176793" class="anchor"><span id="_Toc284178241" class="anchor"></span></span></span>Type

This is a read-only field. If the collection object is a type, the **Type** box will automatically be ticked.

##### Imaged

This read-only field is used to indicate that a high-quality image of the specimen has been generated at MEL, in accordance with the standards of the GPI project. This field will be populated as soon as practicable after the specimen has been imaged.

##### GPI

This read-only field is used to indicate that a high-resolution image of the specimen has been delivered to JSTOR and is available to be viewed on the [Global Plants](https://plants.jstor.org/) website.

##### Multisheet

This is a read-only field. If the collection object is part of a multisheet relationship, the **Multisheet** box will automatically be ticked.

##### Parts

This is a read-only field. If the collection object is part of a mixed collection, the total number of parts in the mixed collection will be displayed in the **Parts** field.

<span id="_Toc284176819" class="anchor"></span>

### Other identifier

The **Other identifier** table is used to record the institution from which incoming exchange specimens were received, and the accession or catalogue number applied to the specimen at the source institution, if known. This table is also used to record the catalogue numbers of duplicates held at other herbaria, where known, and the original herbarium and catalogue number in situations where we have received a duplicate from one herbarium, but they received the original specimen (and duplicate material) from another herbarium.

##### Type

The type of other identifier that is being recorded. The options are:

-   Ex herbarium – where the specimen is known to have been received as a duplicate or donation from another herbarium

-   Duplicate – where the specimen Is known (or has been inferred) to be a duplicate held at another herbarium based on collector, collecting number and collecting date.

-   Original herbarium – the original herbarium and catalogue number where we have received a duplicate from one herbarium, but they received the original specimen (and duplicate material) from another herbarium. If no catalogue number is provided – or if the herbarium is not registered on Index Herbariorum – the original herbarium should be recorded in the **Original collection** field in the **Collection object attribute** table.

##### Institution 

The Index Herbariorum code of the institution from which the specimen was received, for contemporary exchange and donations. If the institution’s accession number is provided, enter it in the **Catalogue no.** field in the **Other identifier** table. If the specimen has come from the private herbarium of an individual collector, or if it is an older specimen that has been purchased or donated rather than received via contemporary exchange, enter that information in the **Original collection** field in the **Collection object attributes** table. Please use the code that the issuing herbarium is using on the specimen. For example, for a specimen from CANB that has the barcode ‘CBG 025665’, enter ‘CBG’ in the **Institution** field and ‘025665’ in the **Catalogue no.** field (or scan the entire barcode in the **Institution** field – see below).

##### Catalogue no.

The catalogue or accession number that was assigned to a specimen (or its duplicate) at the herbarium from which it was received. For example, a duplicate of ‘BRI AQ 814849' would have ‘BRI’ entered in the **Institution** field, and ‘AQ 814849’ entered in the **Catalogue no.** field.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Barcodes on exchange specimen labels

  You can populate the **Institution** and **Catalogue no.** fields by scanning the barcode on most exchange specimen labels into the **Institution** field:

  &lt;&lt;image&gt;&gt;

  When you save the **Collection object** record, the herbarium code will be saved in the **Institution** field and the accession or catalogue number will be saved in the **Catalogue no.** field:

  &lt;&lt;image&gt;&gt;

  Note that DNA barcodes do not include the herbarium code, so you need to scan the barcode directly into the **Catalogue no.** field and type the herbarium code into the **Institution** field. Also, the MEL barcode scanners don’t read the older NT barcodes, so these have to be entered by hand.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Determinations

Specify supports multiple determinations, which allows the determination history of a specimen to be accurately recorded. The same set of fields is used for all determination types, and the **Det. type** field is used to indicate what type of determination is being recorded.

Records that have a Conf. should always have a Det., even if the original determiner is unknown. For specimens that have a single determination covering both the type status and the current name, the information should be entered as a ‘Det.’ as well as a ‘Type status’ determination.

Older specimens often have handwritten labels bearing more than one name. These should all be treated as determinations, regardless of whether or not the determiner or date of determination is known. If there is more than one name on a single label, and the names are written in the same handwriting, they can be treated as a single determination. Unless there is reason to think otherwise, treat the first or most prominent name on the label as the name the specimen was determined to, and enter all the names that appear on the label in the **Det. notes** field.

Where a specimen of a parasitic plant or fungus bears a separate identification for the host taxon, you can just record the determination in the **Miscellaneous notes** field, instead of creating a separate collection object record.

See **Appendix** **2. Examples of determination records** for specific examples.

##### Det. type

The type of determination. The following values can be selected from the pick list:

-   Acc. name change – Accepted name change

-   AVH annot. – AVH annotation

-   Annot. ­– annotation

-   Conf. – confirmavit

-   Det. – determinavit

-   Type status – type status determination.

If there is an annotation on the specimen that is only there for curation purposes, or is only there to correct the spelling of a taxon name on a previous det. slip, there is no need to enter the annotation in the database. See **Taxon name** (p. 32) for instructions on how to deal with misspelt taxon names in determinations.

##### Determiner

The name of the person who made the determination. Enter the determiner’s name from the **Agent** drop-down list. If the determiner is not in the list, press the **Add** symbol to open the **Agent** form.

Where there is more than one determiner, the agent names will be separated by a semicolon, e.g. ‘Stajsic, V.; Klazenga, N.’. If the combination of determiners is not listed in the drop-down list, it will need to be added to the **Agent** table as a ‘Group agent’.

If the determiner is given as an institution code, e.g. BRI, select the relevant organisation agent from the list (e.g. ‘BRI -- Queensland Herbarium’).

If the determiner’s name is difficult to read and has been interpreted, you can enter details about how it has been interpreted in square brackets in the **Det. notes** field. For example, if the determiner is given as ‘Paul Wilson’, but you have inferred that it is ‘Paul G. Wilson’, select ‘Wilson, Paul G.’ from the **Determiner** drop-down list, and record in Det. notes that ‘\[The determiner is given as ‘Paul Wilson’.\]’:

&lt;&lt;image&gt;&gt;

If you are certain of the identity of the determiner, there is no need to enter a message in the **Det. notes** field.

##### Date

The date of the determination. The determination date can be a full date, a month and year, or just a year. Select the appropriate date type from the **Date** pick list, and then enter the date using the number keys. Note that if you enter a full date, then change the date type to ‘Mon/Year’ or ‘Year’, the month and/or date will revert to ‘01’ if you then change the date type back to ‘Full date’.

##### Current

<span id="_Toc284176798" class="anchor"></span>This field is used to indicate which of the determinations is current, for records that have more than one determination. Tick the **Current** box in the current determination. If there is no current determination, a warning will appear when you try to save the record:

&lt;&lt;image&gt;&gt;

The current determination should never be a ‘Type status’ determination; where a single determination covers both the type status and the current name, the information should be entered as a ‘Det.’ as well as a ‘Type status’ determination. If a specimen has a ‘Conf.’ that is more recent than a ‘Det.’ of the same name, the ‘Conf.’ is the current determination.

The **Current** check box is automatically ticked when you add a new determination. For this reason, it makes most sense to enter determinations in chronological order. If the determination you are adding is not the current determination, uncheck the **Current** box and use the navigation bar to scroll through the other determinations to find the current one:

&lt;&lt;image&gt;&gt;

##### Taxon name

<span id="_Toc284176799" class="anchor"></span>The name of the taxon that the specimen has been determined to. This field links to the **Taxon** table. To look up a name, start typing the taxon name and then press the down-arrow or the **Tab** key to see a list of names that start with the letters you just typed in. It may take several seconds to populate the list if there are a lot of matching names. If the name is not in the list, it will need to be added to the **Taxon** table using the **Taxon** form.

If the name on the label is an orthographic variant of a name already in the **Taxon** table (or is just misspelt), select the correctly spelt name from the **Taxon name** drop-down list, and enter the name as it appears on the sheet in the **Det. notes** field.

If an incorrect author is given, but it’s not clear whether the name is a homonym, an isonym or an error, select the valid name from the **Taxon name** list and enter the name and author combination given on the label in the **Det. notes** field.

##### Alternative name

The **Alternative name** field is used to record unpublished or unofficial names that have previously been applied to the specimen. This field should never be used for current determinations.

Before entering a name in this field, check to see if the name (or a variation of the name) is in the **Taxon** table. If the name is in the **Taxon** table, it should be entered in the **Taxon name** field (even if it is an unofficial or unpublished name). If the name is not in the **Taxon** table, check to see if it is listed in IPNI or Tropicos. If it is listed in either IPNI or Tropicos, add the name to the **Taxon** table. If you cannot find the name in IPNI or Tropicos, or if the name on the sheet has a different author, enter it in this field exactly as it appears on the label.

##### Qualifier

The determination qualifier, for uncertain determinations. The following values can be selected from the pick list:

-   ?

-   aff.

-   cf.

In the past ‘sp. aff.’ has often been used in this field. ‘sp. aff.’ is not a determination qualifier, but indicates a different entity. If a specimen has been determined to ‘*Somegenus* sp. aff. *someepithet*’, then ‘sp. aff. *someepithet*’ needs to be added as a species to the **Taxon** table. <span id="_Toc284176801" class="anchor"></span>

##### Qualifier rank

The rank at which the determination qualifier applies. Select the appropriate rank from the pick list. By default, the **Qualifier rank** will be set to the lowest rank to which the specimen has been determined. This happens in the background after the record is saved, so you will not be able to see it immediately. You only need to fill in the **Qualifier rank** field if the qualifier is applied to a rank higher than the lowest rank to which the specimen has been determined. For example:

-   ‘?*Eucalyptus camaldulensis*’ – the **Qualifier rank** should be set to ‘genus’

-   ‘*Chamaecrista nomame* var. ?*nomame*’ – the **Qualifier rank** will automatically be set to the lowest rank, so you don’t need to enter anything in this field.

##### Addendum

A suffix added after the name to indicate a concept for that name. The following values can be selected from the pick list:

-   s.l. – *sensu lato*: in a broad sense

-   s.str. – *sensu stricto*: in a narrow sense

-   group

-   intergrade

-   intermediate

-   complex

-   vel aff.

##### Type status

The type status of the specimen, as recorded in the determination. The following type statuses are recognised at MEL:

-   <span id="_Toc284176804" class="anchor"></span>Holotype – the one specimen or illustration used by the author or designated by the author as the nomenclatural type

-   Isotype – a duplicate specimen of the holotype

-   Syntype – any specimen cited in the protologue when there is no holotype, or any of two or more specimens simultaneously designated as types

-   Isosyntype – a duplicate of a syntype

-   Lectotype – a specimen or illustration designated from the original material as the nomenclatural type if no holotype was indicated at the time of publication, or if it is missing

-   Isolectotype – a duplicate specimen of the lectotype, if the lectotype has been chosen from among syntypes (if a lectotype has been chosen from among isotypes, the other isotypes just remain isotypes)

-   Neotype – a specimen or illustration selected to serve as the nomenclatural type if no original material is extant or as long as it is missing

-   Isoneotype – a duplicate specimen of the neotype (again only when the neotype was chosen from among syntypes; isotypes remain isotypes)

-   Paratype – a specimen cited in the protologue that is neither the holotype nor an isotype, nor one of the syntypes if two or more specimens were simultaneously designated as types (*Note:* paratypes need to be cited as paratypes in the protologue; not every specimen cited in a protologue that is not an isotype or a syntype is a paratype)

-   Residual syntype – used for the remaining syntypes when a lectotype has been selected from among syntypes (*Note:* in HISPID the term ‘Paralectotype’ is used for this and that is what goes into the database when ‘Residual syntype’ is selected from the pick list)

-   Paraneotype – used for the remaining syntypes when a neotype has been selected from among syntypes

-   Epitype – a specimen or illustration selected to serve as an interpretative type when the holotype, lectotype, or previously designated neotype, or all original material associated with a validly published name, cannot be identified for the purpose of precise application of the name of a taxon

-   Authentic specimen – the original specimen of an invalid name, i.e. any specimen cited in the protologue of an invalid name

-   Type – used when we know it is a type, but are uncertain of the type status.

##### Type qualifier

The uncertainty of the type status determination, if recorded by the determiner. The options for type status qualifier are ‘probable’, ‘possible’ and ‘?’. If the determiner has included an explanation of why the type status is uncertain, include this in the **Det. notes** field.

##### Stored under this name

<span id="_Toc284176806" class="anchor"></span>For type specimens, this field is used to indicate that the specimen is stored under the basionym. It does not need to be checked for non-type specimens. **Note that, contrary to prior herbarium procedure, if the specimen is a type of more than one name, it should be stored under the most recent basionym (the date of publication can be checked in the** Taxon **table).**

**Stored under this name** must only be ticked in one determination record; if there is more than one type status determination for the name that the specimen is stored under, only tick **Stored under this name** in the most recent (or the most authoritative) determination.

##### Basis

If the determination of a specimen is not based on examination of the actual specimen, but on a duplicate or an image, the basis of determination should be recorded here. The following values are currently in the pick list:

-   Duplicate – we either have the catalogue number of the specimen at the original herbarium in MELISR, or the catalogue number is not available, but the collector, collecting number and collecting date match

-   Image.

If additional values need to be added to the pick list, see the Digital Collections Advisor.

##### Extra information

The **Extra information** field should be used to record recognised form and variant names, or any other information that tells you something about the taxon or group concept, but is not part of the taxon name. For example:

-   ‘alpine form’

-   ‘broad phyllode variant’

-   ‘var. indet.’.

Information entered in the **Extra information** field will be printed on the label directly below the taxon name. Any nomenclatural notes relating to the taxon name (e.g. ‘nom. nud’, ‘nom. inval.’) should be entered in the **Nom. note** field in the taxon name record.

##### Flora

If the det. slip indicates that the specimen was viewed for a flora project, select the flora from the pick list. Do not enter any flora notes from the det. slip (e.g. ‘Seen for Flora of Australia’ or ‘Flora of Australia Project’) in the **Det. notes** field. The **Flora** pick list currently lists ‘Algae of Australia’, ‘Flora of Australia’ and ‘Flora Malesiana’. Additional flora projects can be added if needed. Make sure you only use this field in the determination record that corresponds to the relevant det. slip.

##### Det. notes

**Det. notes** should be used to record additional notes that relate to the determination or the particular specimen, and not to a taxon or group concept. For example:

-   ‘glabrous variant with atypically short phyllodes’

-   ‘form with more or less petalous flowers’

-   ‘primocane’

-   ‘fruit needed for identification to species level’

-   'Determination taken from NSW 574242, Australia's Virtual Herbarium, 30/10/14'.

Lichen chemistry should be recorded in the **Det. notes** field if it is part of a determination. If it was provided by the collector, it should be recorded in **Collecting notes**. For example:

-   ‘TLC in C: salazinic (major), consalazinic, norstictic (faint trace), protocetraric (trace) and usnic acids’

-   ‘P-, K+, yellow, C-, KC-’.

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Taxon names – what goes where?
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ###### Name usage

  Where an observation about the use of a name has been made by data entry staff, it should be recorded as an annotation in the **Determinations** table (i.e. a separate **Determination** record with the **Det. type** set as ‘Annot.’). Examples of observations about the use of a name include:

  -   ‘Incorrectly reported from Australia, Checklist of Australian Lichens, Aug 2003’

  -   ‘Listed under doubtful and excluded names, Checklist of Australian Lichens, August 2003’

  -   ‘Listed under excluded names, Fl. Aust. 55: 162 (1994)’.

  But, if an observation about the use of a name is written on a det. slip, then it should be recorded in the **Det. notes** field for that determination.

  ###### Source of name

  An indication of where the name comes from should be entered in the **Det. notes** field. For example:

  -   ‘species name taken from I.G. Stone’s red collecting book’.

  ###### Variants and forms

  Short, informal variant or form names should be entered in the **Extra information** field. For example:

  -   ‘Brisbane Range variant’

  -   ‘Daylesford form’

  -   ‘sessile-head variant’.

  But, if the variant or form has been listed in VicFlora or APNI, it should be entered in the **Taxon** tree. For example:

  -   ‘*Grevillea* aff. *oxyantha* (Mt Burrowa)’

  -   ‘*Betula* aff. *pubescens* (Mt Macedon)’.

  If the variant or form information is a short description, rather than a short, informal name, it should be entered in the **Det. notes** field. For example:

  -   ‘variant with pubescent calyces’

  -   ‘variant with short, ovate-obovate leaves’

  -   ‘small, dark and short-headed form’.

  If you are unsure whether something belongs in **Extra information** or **Det. notes**, enter the information in **Det. notes**.

  ###### Field names

  Field names for fungi that have not been identified to species level should be entered in **Extra information**. For example:

  -   *Elaphomyces* ‘yellow crusty’ – only enter ‘yellow crusty’ in the **Extra information** field.

  The formal part of the identification (in this example, ‘*Elaphomyces*’) should be entered in the **Taxon name** field as per usual.

  ###### Informal names

  Informal names for current determinations should be entered in the **Taxon** table. There is a CHAH-endorsed format for informal names, but any informal name that is used in a determination may be added to the **Taxon** table. There are many informal names already in the **Taxon** tree, VicFlora, FloraBase and APNI, so please check for variations of the same informal name in the **Taxon** tree and consult the nomenclatural sources before adding a new informal name to the **Taxon** table. If in doubt, enter the informal part of the name in the **Extra information** field.

  ###### Redeterminations of duplicates

  If the determination of a specimen is based on the redetermination of a duplicate specimen held at another herbarium, enter the name of the person who redetermined the duplicate in the **Determiner** field, and select ‘Duplicate’ in the **Basis** field.

  If the determination was taken from a duplicate, record an appropriate message in **Det. notes** to make it clear that the determiner hasn’t redetermined our specimen in person, e.g. ‘Determination taken from NSW 574242, Australia's Virtual Herbarium, 30/10/14’. Enter the herbarium code and catalogue number of the inferred duplicate in the **Other identifier** table, recording ‘Duplicate’ in the **Type** field.

  ###### Nomenclatural notes

  Any nomenclatural notes that need to be printed with the taxon name, such as ‘non. R.Br.’, ‘nom. nud.’, ‘nom. inval.’ etc. should be entered in the **Nom. note** field in the taxon name record, not in the determination record.
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Batch identify

  The **Batch identify** tool in Specify can be used to add new determination records to multiple collection objects at the same time. The newly added determination becomes the current determination, and the previous determinations are retained in the database.

  To add a new determination to a batch of records:

  1.  Create a record set of the collection objects that you want to redetermine. Make sure that the record set only contains collection objects for which the new determination details are identical, as all the records in the set will get the same details added for the new det.

  2.  Select **Batch identity** from the **Data** menu:

  > &lt;&lt;image&gt;&gt;

  1.  Select **Record Sets** from the **Choose** window

  2.  Select the appropriate record set from the list and click **OK**

      A window with all the determination fields and a summary of the collection objects in the record set will appear. Before redetermining your record set, scroll through the list of records to check for any collection objects that shouldn’t be there.

      &lt;&lt;image&gt;&gt;

  3.  Enter the details of the new determination and click **Identify**. All records will be redetermined, unless you select specific records from the list.

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### <span id="_Ref369163453" class="anchor"><span id="_Toc492047881" class="anchor"></span></span>Preparations

The **Preparations** form is a subform of the **Collection object** form. It is used to store information about what type of specimen the collection object relates to (sheet, packet, spirit etc.), where it is stored, and where duplicates are held.

##### Preparation type

The type of preparations belonging to the collection object. The following preparation types are used at MEL:

-   Sheet – a pressed and dried specimen mounted on archival paper and stored in a manila folder

-   Packet – a dried specimen stored in a packet. The majority of fungi, lichen and bryophyte specimens are packet preparations.

-   Spirit – material preserved in ethanol and stored in the Spirit Room

-   Carpological – dried fruiting material that is too bulky to be pressed and mounted as a sheet

-   Microscope slide – a glass slide prepared for microscopic examination of all or part of the specimen

-   Photographic slide – a photographic slide that accompanies the specimen. Photographic slides of entire specimens, with no accompanying herbarium material, should be treated as ‘Photograph of specimen’ preparations and entered in the *Photographs of specimens* collection.

-   Silica gel sample – plant material stored in silica gel to be used for molecular analysis

-   Fungal culture – a dried fungal culture. All fungal cultures are stored in packets within the fungi collection.

-   Display Set – a specimen that is stored in the Display Set on the first floor of the herbarium extension

-   Seed collection – a seed sample, which is stored in the basement and may be used for germination trials or revegetation work

-   Duplicate – duplicate material that is sent to another herbarium

-   Seed duplicate – a duplicate seed collection that is sent to another herbarium

-   Shipping material – a fragment of a specimen that is sent to another herbarium for analysis

-   Vic. Ref. Set – a duplicate specimen that is held in the Victorian Reference Set, and has been curated as part of the separate *Victorian Reference Set* collection

-   Vic. Ref. Set (old) – a duplicate specimen that is held in the Victorian Reference Set, but has not yet been curated in line with the new Vic. Ref. Set procedures

-   Photograph of specimen – a photograph of a specimen held at another institution. Within Specify, all ‘Photograph of specimen’ and ‘Cibachrome’ preparations are recorded in a separate *Photographs of specimens* collection, and not in the main *National Herbarium of Victoria* collection. If a printed photograph accompanies a pressed plant specimen (i.e. a habitat photo), this should be flagged in the **Photograph** field in the **Collection object attributes** table instead.

-   Cibachrome – an image of a specimen from a colour slide that has been reproduced on photographic paper. Within Specify, all ‘Cibachrome’ and ‘Photograph of specimen’ preparations are recorded in a separate *Photographs of specimens* collection, and not in the main *National Herbarium of Victoria* collection.

A single collection object cannot have more than one of the following preparation types: ‘Sheet’, ‘Packet’, ‘Spirit’, ‘Carpological’, ‘Cibachrome’, ‘Photograph of specimen’, ‘Fungal culture’ or ‘Display Set’. The only preparation types that can occur with other preparation types in the one collection object record are ‘Microscope slide’, ‘Photographic slide’, ‘Silica gel sample’, ‘Vic. Ref. Set’, ‘Vic. Ref. Set (old)’, ‘Seed collection’, ‘Duplicate’, ‘Seed duplicate’ and ‘Shipping material’.

##### Quantity

The number of objects of a particular **Preparation type**. The default quantity is ‘1’. The value of this field should only ever be greater than one for those preparation types that do not receive individual numbers for each object (i.e. microscope slides and spirit jars).

For ‘Duplicate’ and ‘Seed duplicate’ preparations, the number in the **Quantity** field should match the number of institutions listed in the **MEL duplicates at** field.

For ‘Vic. Ref. Set’ specimens, the **Quantity** should always be ‘1’.

##### Number

The number assigned to the spirit jar, microscope slide, silica gel sample or Vic. Ref. Set specimen, or the library reference number for a photographic slide.

We have previously used the same numbering scheme for spirit and slide material. From now on, we will use a separate series of numbers for each type of preparation. The next available storage number for a preparation type is automatically generated when you save the record.

If there are multiple photographic slides with a specimen and they have each been assigned a Library reference number, they should be entered as separate preparations with the relevant Library reference number entered in the **Number** field for each preparation record.

Note that only one number is assigned for each spirit collection, regardless of whether or not there is more than one spirit jar in the collection. Likewise, only one number is assigned to microscope slides that belong to the same collection. Where there is more than one spirit jar or microscope slide for the one collection, use the **Quantity** field to indicate how many items there are.

For Vic. Ref. Set specimens, a six-digit number will be assigned when the record is saved. This number will become the **Catalogue number** in the corresponding **Collection object** record in the *Victorian Reference Set* collection.

##### Jar size

The size of the spirit jar (A, B, C or D). A is the smallest jar size, B is the medium jar size and C is the largest jar size. D is used to indicate that the specimen is an algal collection, irrespective of the jar size.

<span id="_Toc284176814" class="anchor"></span>

##### On loan

The **On loan** check box will automatically be ticked if a preparation is on loan.

##### Loans

The **Loans** button is a link to the entry in the **Loan** table that relates to the preparation. If a preparation is currently on loan, clicking on the **Loans** button will open the details of the **Loan** in a new tab.

##### Multisheets

Information about multisheet relationships between different specimens. The multisheet message must include the part (A, B, C etc.) after the MEL number to indicate which parts of a mixed collection are involved in the multisheet relationship. All numbers should be spelt out in full, and there should not be a space between the number and the part. For example:

-   ‘Sheet 1 of 3 (MEL 12345A, MEL 12346A)’.

For non-sheet collections or non-packet collections, include the preparation type before the MEL number, followed by a colon. For example:

-   ‘Sheet 1 of 2 (MEL 2142735A, Carpological: MEL 269770A)’

-   ‘Sheet 1 of 3 (MEL 691579A, Spirit: MEL 2040692A)’.

##### MEL duplicates at

The Index Herbariorum codes of the herbaria that duplicates of a MEL specimen were sent to. Institution codes should be separated by a comma and a space, e.g. ‘AD, CANB, HO’; do not enter a full stop at the end of the string.

This field should only be completed for ‘Duplicate’ or ‘Seed duplicate’ preparations. Institutions that hold duplicates of specimens sent to MEL as exchange or donations should be listed in the **Other duplicates at** field in the record for the primary MEL preparation (i.e. ‘Sheet’, ‘Spirit’, ‘Carpological’, ‘Fungal culture’ or ‘Display Set’).

##### Other duplicates at

The Index Herbariorum codes of the herbaria (or the name of other institutions) that also hold duplicates of specimens sent to MEL as exchange or donations. The **Other dupl. at** field should never be filled in for ‘Duplicate’ or ‘Seed duplicate’ preparations. Herbaria that hold duplicates of specimens sent by MEL should be listed in the **MEL duplicates sent to** field for the ‘Duplicate’ preparation type.

<span id="_Toc284176821" class="anchor"><span id="_Toc284176817" class="anchor"></span></span>

##### Orig. herb. (Photographs of specimens collection)

The Index Herbariorum code of the institution where the actual specimen is held, where we have received a photograph or cibachrome of the specimen from a different herbarium. For example, if we receive an image of a type specimen from CANB, but the image is of a specimen held at K, ‘CANB’ would be entered in the **Ex herbarium** field, and ‘K’ would be entered here.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Databasing MEL duplicates

  ###### Duplicate preparations

  In Specify, ‘gifts’ (outgoing exchange and donations) are linked to preparations. When a new gift transaction is created, preparations are added to the **Gift** record, creating a register of what duplicates have been sent where. To distinguish between preparations that are held at MEL and those that have been sent to other institutions, any specimen that has duplicates must have a ‘Duplicate’ preparation entry in the **Preparations** table, in addition to the preparation type(s) held at MEL (‘Sheet’, ‘Spirit’ etc.).

  A single **Collection object** record should only ever have one ‘Duplicate’ preparation record in the **Preparations** table, regardless of the number of duplicate specimens that have been sent out. The **Quantity** field should be used to indicate the number of herbaria to which a duplicate has been sent. (There is no need to record that more than one ‘sheet’ has been sent to a single herbarium, as we have no guarantee that they will retain all the material.)

  The **MEL duplicates at** field is used to list the herbaria that duplicate material has been sent to, and should only be populated for ‘Duplicate’ or ‘Seed duplicate’ (see below) preparation types. Institution codes should be separated by a comma and a space, and full stops should not be used. Do not enter anything in the **MEL duplicates at** field for preparations that are retained at MEL.

  ###### Duplicates of multisheet collections

  Where a duplicate of a multisheet collection has been sent to one or more herbaria, a ‘Duplicate’ preparation should only be added to the **Collection object** record for one component of the multisheet. This will generally be Sheet 1, but in rare cases, it may be Sheet 2 (e.g. if duplicate spirit material is sent of a multisheet collection comprising dry material and a spirit collection).

  ###### Victorian Conservation Seedbank duplicates

  Victorian Conservation Seedbank specimens generally have duplicate herbarium material as well as a duplicate seed collection, which need to be entered as separate ‘Duplicate’ and ‘Seed duplicate’ preparations. Because the duplicate seed sample and duplicate herbarium material are not always sent to the same institutions, the information in the **MEL duplicates at** field for the ‘Duplicate’ and ‘Seed duplicate’ will usually be different.

  ###### Printing duplicate labels

  The number of duplicate labels that need to be printed will be calculated from the **Quantity** fields for preparation types that require duplicate labels.

  ###### Victorian Reference Set specimens

  Specimens in the Vic. Ref. Set are databased in their own collection and also recorded as a ‘Vic. Ref. Set’ preparation in the corresponding MEL specimen record. Each Vic. Ref. Set specimen will be assigned a six-digit VRS catalogue number, which will be stored in the **Number** field when the record is saved. The Vic. Ref. Set specimens all need to have unique VRS catalogue numbers so, if there is more than one Vic. Ref. Set duplicate of a MEL specimen, the MEL record will need to have a separate ‘Vic. Ref. Set’ preparation for each Vic. Ref. Set sheet; the value of the **Quantity** field in a ‘Vic. Ref. Set’ preparation must always be ‘1’.

  Once the ‘Vic. Ref. Set’ preparation has been saved in the *National Herbarium of Victoria* collection, a collection object record will be automatically created in the *Victorian Reference Set* collection, with the VRS number as the **Catalogue number**. The *Victorian Reference Set* record will include the most recent determination and all other data (except the preparation records and links to transactions) from the corresponding *National Herbarium of Victoria* record. The *Victorian Reference Set* record should be edited to include any annotations on the Vic. Ref. Set sheet, or to delete any annotations from the *National Herbarium of Victoria* record that don’t relate to the Vic. Ref. Set specimen.

  Given that all Vic. Ref. Set specimens are duplicates of specimens in the main collection, they should always be databased via the *National Herbarium of Victoria* collection; records can be edited in, but should not be directly added to, the *Victorian Reference Set* collection.

  Vic. Ref. Set specimens will be labelled with distinct labels, and ‘Vic. Ref. Set’ will still appear in the ‘Dupl:’ string on the corresponding MEL label.
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##### Storage

The storage system at MEL is quite outdated, and doesn’t reflect current taxonomic knowledge. In Specify, taxon names have been decoupled from the storage system, which allows us to query MELISR by up-to-date higher level taxonomy.

The **Storage** field provides a link to the **Storage** tree, so that changes in taxonomic classification in the **Taxon** tree do not necessarily have to lead to changes in storage. When you add a new taxon record for ranks above species, you also need to define its storage location; see **Adding new genus and higher taxon names** (p. 87) for instructions.

The **Storage** field will be populated when the record is saved. The storage location will be automatically printed on labels, regardless of whether or not the script that populates the **Storage** field has run.

##### Hort. Ref. Set

This field is used to indicate that the specimen is in the Horticultural Reference Set. It is legacy data from MELISR, and probably won’t be used in future. When the rest of the Hort. Ref. Set is databased, it will probably be entered as a separate collection in Specify.

### Collecting event

The **Collecting event** table stores information about when and where the specimen was collected, and who it was collected by.

### <span id="_Toc284176834" class="anchor"><span id="_Toc284178245" class="anchor"><span id="_Toc492047883" class="anchor"><span id="_Toc284176824" class="anchor"></span></span></span></span>Collectors

All collectors associated with the collecting event should be entered here. Click on the **Add** symbol to open the **Collectors** subform.

&lt;&lt;image&gt;&gt;

If there is no collector’s name on the specimen, do not enter anything in the **Collectors** field. Instead, tick the **Colector unknown** check box in the **Collecting event attributes** form. If the label actually states that the collector is unknown, enter ‘Unknown’ (i.e. without brackets) in the **Verbatim collectors** field. If the collector(s) name is illegible, tick the **Collector illegible** check box in the **Collecting event attributes** form and, if the collector’s name is not on the label but has been inferred from their handwriting or the collecting information, tick the **Collector inferred** check box.

##### Agent

To look up a name, start typing the collector’s last name and then press the down-arrow or the **Tab** key to see a list of matching names. What you type in the field is only matched against the **Last name** field, so don’t type a comma or any initials when you are looking up a collector’s name. Scroll the list of matching names, then press **Enter** or click **OK** when you have found the right agent.

When adding multiple collectors, make sure that the primary collector is listed first (although the order of the collectors doesn’t really matter from a database point of view, entering them in a consistent way will help us detect potential errors in the database). If you need to change the order of collectors, click on the collector’s name that you want to move, then use the up and down arrows at the right-hand side of the **Collectors** grid:

&lt;&lt;image&gt;&gt;

If you have selected the wrong name, press **Esc** to clear the field, then search again.

If the collector’s name does not appear in the list, select ‘Add’ from the drop-down list, or click the **Add** symbol next to the field to add a new agent record.

##### Comments

The **Comments** field can either be used to record collecting numbers assigned by one of the additional collectors, or uncertainty about the interpretation of the collector’s name.

The collecting number for the primary collector(s) (see **Is primary** below) should be entered in the **Collecting no.** field. For example:

-   ‘A.C. Beauglehole 58278 & E.G. Errey 1978’ – ‘1978’ should be entered in **Comments** for E.G. Errey. **Comments** should be left blank for A.C. Beauglehole, and ‘58278’ should be entered in the **Collecting no.** field.

If you are unsure that the collector is the person you have selected from the drop-down list, enter a question mark in this field.

##### Is primary

Where there is more than one collector, the **Is primary** check box is used to indicate which of the collectors are the primary collectors. The **Is primary** check box is ticked by default, so it only needs to be un-ticked for collectors who are not considered to be primary collectors.

The primary collector is the collector whose name appears before the collecting number or ‘s.n.’ (if ‘s.n.’ is recorded in the collecting information). If more than one collector’s name appears before the collecting number (or ‘s.n.’), they can all be considered as primary collectors. If there is more than one collector, but no collecting number or ‘s.n.’, all collectors should all be considered as primary collectors. For example:

-   ‘N.G. Walsh 4901 & F. Anderson’ – N.G. Walsh is the primary collector

-   ‘L.A. Craven & C.R. Dunlop 6663’ – both collectors are primary collectors

-   ‘J.G. & M.H. Simmons s.n. & K.C. Rogers’ – J.G. Simmons and M.H. Simmons are the primary collectors

-   ‘D. Rouse \[JAJ 1301\] & M. Duncan’ – D. Rouse is the primary collector.

Note that these examples are only a guide; feel free to apply your own knowledge of the collectors when assessing which are the primary collectors and which are the additional collectors. For example, Nigel Sinnott labels are sometimes formatted with two collectors listed before the collecting number (e.g. ‘A.E.M. & N.H. Sinnott 2989’), even though the collecting number is from his sequence and he should be considered the only primary collector.

### Collecting event (continued) 

##### Collecting no.

The collecting number of the primary collector(s). If there is no collecting number, type ‘s.n.’ (*sine numero*) in the **Collecting no.** field. The **Collection object** form cannot be saved if this field is left blank.

If the collecting number is prefixed with the collector’s initials, there is no need to enter their initials in the **Collecting no.** field.

If someone other than the listed collectors has assigned a collecting number to an unnumbered collection, enter the number in square brackets in the **Collecting no.** field, preceded by the initials of the person assigning the number. A note explaining who assigned the number should also be entered in **Miscellaneous notes**. For example:

-   ‘D. Rouse \[JAJ 1301\] & M. Duncan’ – ‘\[JAJ 1301\]’ would be entered in the **Collecting no.** field and ‘\[Collecting number assigned by J.A. Jeanes\]’ should be entered in **Miscellaneous notes**.

If someone other than the listed collectors has assigned a collecting number to a specimen that already has a number, enter the primary collector’s number in **Collecting no.**, and record the additional number in **Miscellaneous notes**. For example:

-   ‘F. Robbins 106 (ACB 17097)’ – ‘106’ would be entered in the **Collecting no.** field, and ‘\[A.C. Beauglehole assigned collecting number 17097 to this specimen.\]’ would be entered in **Miscellaneous notes**.

##### Start date

The collecting date, or the earliest date if the collecting date is given as a range. The collecting date can be entered as a full date (day, month and year), a month and year, or a year only. Select the date type from the date drop-down list, then enter the date using the number keys.

If the collecting date is unknown but the collector is known, check that there are biographical notes indicating the collector’s lifespan or period of activity in the **Agent** table.

##### End date

The end date of collection, if the collecting date is given as a range. The collecting date can be entered as a full date (day, month and year), a month and year, or a year only. Select the date type from the date drop-down list, then enter the date using the number keys.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Flowering and fruiting dates
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ###### Specimens with a flowering date OR a fruiting date 

  If the collecting notes mention a flowering (or fruiting) date, and the specimen is in flower (or fruit), it is safe to assume that the date corresponds to the date of collection. If the specimen is not in flower (or fruit), enter the flowering (or fruiting) date in the **Collecting notes** field.

  ###### Specimens with a flowering date AND a fruiting date

  If the specimen is in flower, but not in fruit, enter the flowering date as the date of collection, and the fruiting date in **Collecting notes** (or vice versa). You can also add a note in the **Miscellaneous notes** field to explain that a fruiting date is given, but the specimen only bears flowers.

  If the sheet contains separate plant specimens, one of which is bearing flowers and one of which is bearing fruit, assume that the flowering and fruiting dates represent the collecting dates of the separate plant specimens, and treat them as a mixed collection.

  If the specimen has both flowers and fruits, but it doesn’t appear to be a mixed collection, enter the flowering and fruiting dates in **Collecting notes**.

  ###### Flowering and fruiting dates without years

  If the flowering and/or fruiting dates have been interpreted as collecting dates but do not include the year, enter them in the **Verbatim collecting date** field.
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##### Collecting trip

The collecting trip or expedition on which the specimen was collected, e.g. ‘Victorian Exploring Expedition’, ‘Mueller Commemorative Expedition’. Select the relevant collecting trip from the drop-down list. To see a list of all the collecting trips in the **Collecting trip** table, enter a wildcard (\*) in the query combo box and press the down-arrow:

&lt;&lt;image&gt;&gt;

If the collecting trip is not there, add it in the **Collecting trip** form.

##### Geography

This is a read-only field that displays the **Geography** full name string, if it has been entered in the **Locality** form. The geography details will not display in this field until the record has been saved.

##### Locality

The locality description, as provided by the collector. Click on the **Add** icon to open the **Locality** form.

&lt;&lt;image&gt;&gt;

You will see that the locality field has a drop-down list that allows you to select a locality that has already been entered, but this must be used with great caution. Only use an existing locality record if ALL of the details in the **Locality** form (and the associated **Locality details** and **Geocoordinate details**) are EXACTLY the same. If a **Locality** record is shared between two or more **Collection object** records then subsequently edited, the locality will be edited in *all* the **Collection object** records that share that locality, not just in the **Collection object** record that is open when the **Locality** record is edited. If the locality is similar to a previous record, use the **Clone** feature outlined below.

If there are no locality details provided, DO NOT select ‘No details given’ from the drop-down list, as many of the records with ‘No details given’ in the **Locality** field have data in other fields in the **Locality** and **Geography** tables that will not correspond to the specimen you are databasing.

If you use **Carry forward** for the **Collecting event** information, the **Locality** query box in the new record will contain the locality of the previous record. Do not **Edit** this **Locality** record unless to correct an error, as it will change the locality for all records you entered before that use the same **Locality** record. If the specimen you are databasing was collected in the exact same spot (including at the same altitude) as the specimen you databased previously, you can use the same **Locality** record and don’t have to do anything. If some, but not all, of the locality information is the same as in the previous record, you can use the **Clone** button – the stamp symbol just to the right of the **Add** icon. This will create a new **Locality** record with all the locality information from the previous record, so you can just change in the **Locality** form what needs to be changed. It will almost always be safer to **Clone** an existing **Locality** record than to **Edit** it.

&lt;&lt;image&gt;&gt;

##### Habitat

A general description of the habitat that the plant, alga or fungus was growing in. Lists of associated taxa should be entered in the **Associated taxa** field in the **Collecting event attributes** table if they are given as a distinct list prefixed by ‘associated species’, ‘in association with’, or similar text.

#####  Collecting notes

Any notes provided by the collector that do not belong in other fields (e.g. information about distribution or abundance). Annotations made by someone other than the collector and notes made by data entry staff should be entered in either the **Miscellaneous notes** or **Curation notes** fields.

Annotations made by people other than the collector, such as Nancy Burbidge or Jim Willis, should be entered in the **Curation notes**, **Miscellaneous notes** or the **Georeferencing notes** field. For example:

-   ‘Field label removed to handwriting file J.H. Willis 15/5/1961.’ should be entered in **Curation notes**

-   ‘No. 88 from J.H. Willis to G.O.K. Sainsbury.’ should be entered in **Miscellaneous notes**

-   A comment about the collecting locality by J.H. Willis, e.g. ‘Not Kallista, but could be Monbulk’, should be entered in **Georeferencing notes**

-   ‘Common in lawns of Melbourne Botanic Gardens. J.H. Willis.’ should be entered in **Miscellaneous notes**.

Notes on the sheet by curators of personal herbaria (such as Steetz or Sonder) should be entered in the **Miscellaneous notes** field.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Habitat or Associated taxa?
  ###### Collecting information
  Growing in a dry creek bed in dry sclerophyll forest on the property of Bush Hide-a-way Log Cabins, in association with *Poa sieberiana* var. *sieberiana*.
  Growing in creek bed with rather coarse sand and broken shells on surface. In association with \**Asphodelus fistulosus*, etc.
  Growing on sand in association with *Ecdeiocolea monostachya*, amongst mallee eucalypts of a yellow sand-plain.
  Interdunal low-reddish, loamy, non-calcareous sands with *Eucalyptus oleosa*, mallee, *Casuarina*, *Heterodendrum* open woodland and sparse shrubs and Spinifex.
  Button grass plain, head of Melaleuca Inlet. Grows on recently burnt areas of plain. In Jungle thicket in Horizontal Scrub areas. Usually in association with *Bauera*.
  ###### Collecting information
  In deep sand in association with *Casuarina paludosa*.
  Growing in association with \[MGC\] 5547.
  Located in dry sclerophyll forest, by the roadside. In association with *Eucalyptus sieberi* and other eucalypts which are dominant.
  Below the south facing cliffs of the wall of a large gully on the west side of a large hill. Soil: red-brown pebbly-rocky loam amongst boulders. *Eucalyptus leucophloia*, *Acacia rhodophloia*, *A. aneura* low woodland over *Eremophila* sp. high open shrubland over *Ptilotus obovatus* low shrubland over *Polectrachne* sp. Mt Ella, *Triodia pungens* open hummock grassland. Associated species: *Rhodanthe margarethae*, *Taplinia saxatilis*, *Sida* aff. *filiformis*, *Chenopodium saxatile*, *Oxalis* aff. *corniculata*, *Canthium latifolium*, *Astrotricha hamptonii* (on the cliffs), *Lobelia* sp., *Eriachne mucronata*, *Cheilanthes humilus*?.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##### Collecting event attributes

The **Collecting event attributes** subform is used to enter additional information about the collecting event, including plant origin, host and substrate.

&lt;&lt;image&gt;&gt;

##### Collecting event attachments

Any attachments that relate to the collecting event, such as habitat photos or a photo of the plant at the collecting site.

&lt;&lt;image&gt;&gt;

### <span id="_Toc284176852" class="anchor"><span id="_Toc284178247" class="anchor"><span id="_Toc492047885" class="anchor"><span id="_Toc283306501" class="anchor"><span id="_Toc284176838" class="anchor"><span id="_Toc284178246" class="anchor"></span></span></span></span></span></span>Collecting trip

##### Trip name

The name of the collecting trip, or expedition.

##### Start date

<span id="_Toc284176855" class="anchor"></span>The start date of the collecting trip or expedition, or the earliest date if a range is given. The collecting trip start date can be entered as a full date (day, month and year), a month and year, or a year only. Select the date type from the drop-down list, then enter the date using the number keys.

##### End date

<span id="_Toc284176856" class="anchor"></span>The end date of the collecting trip or expedition if the date is given as a range. The collecting trip end date can be entered as a full date (day, month and year), a month and year, or a year only. Select the date type from the date drop-down list, then enter the date using the number keys.

##### Verbatim start date

<span id="_Toc284176857" class="anchor"></span>If the collecting trip start date is given in a format that cannot be entered in the **Start date** field, it should be entered here (e.g. ‘late March’, ‘Spring’, ‘Christmas 1912’). If the collecting trip start date is given in a non-standard form but includes a year, or a year and a month, the date should also be entered in the collecting trip **Start date** field.

##### Verbatim end date

<span id="_Toc284176858" class="anchor"></span>If the collecting trip end date is given in a format that cannot be entered in the **End date** field, it should be entered here (e.g. ‘late March’, ‘Spring’, ‘Christmas 1912’). If the collecting trip end date is given in a non-standard form but includes a year, or a year and a month, the date should also be entered in the collecting trip **End date** field.

##### Sponsor

The sponsor of the collecting trip or expedition, e.g. ‘Australian Geographic’, ‘Churchill Fellowship Trust’.

##### Comments

Any additional information about the collecting trip that does not fit in the above fields.

### Collecting event attributes

#### <span id="_Toc283306502" class="anchor"><span id="_Toc284176839" class="anchor"></span></span>Label data

##### Verbatim collectors

The collector(s) name(s) exactly as they appear on the label, without interpretation. If the label contains a collector’s name, you only need to complete this field if the names entered in the **Collectors** field have been interpreted, or if the name on the label is spelt differently or provides additional information, including honorifics (Miss, Mrs, Prof., Dr, Mr etc.). By recording the collector(s) name(s) verbatim, it is much easier to correct this information where the original interpretation of a name was incorrect, and it’s also enormously useful for historical research. Do not include collecting numbers in the **Verbatim collector** field.

If there is no collector’s name on the specimen, tick the **Collector unknown** box, but if the label actually states that the collector is unknown, enter ‘Unknown’ in the **Verbatim collector** field.

If there is more than one collector, but only one of the collectors’ names has been interpreted, you should still enter them both in the **Verbatim collector** field. For example, if the collectors were given as ‘Mr & Mrs T.P. Richards’, you would enter the collectors as ‘T.P. Richards’ and ‘A.F. Richards’, and the verbatim collectors would be recorded as ‘Mr & Mrs T.P. Richards’, not just ‘Mrs T.P. Richards’.

A guide to when the name on the label should be recorded in the **Verbatim collectors** field is provided below:

  **Name on label**   > **Collectors**     > **Record verbatim collector(s)?**
------------------- -------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------
  Chas. Walter        > Walter, C.         > No – there is no interpretation, and the additional information on the label is not particularly important
  Mrs T.P. Richards   > Richards, A.F.     > Yes – the name in the **Collector** field has been interpreted
  O. Tepper           > Tepper, J.G.O.     > Yes – the name in the **Collector** field has been interpreted
  Sir W. McGregor     > MacGregor, W.      > Yes – the name on the label is spelt differently to the interpreted name in the **Collector** field, and includes an honorific
  Rev. J. Chalmers    > Chalmers, J.       > No – there is not really any interpretation of the name here. ‘Rev.’ will be recorded as the **Title** in the **Agent** record for James Chalmers.
  Th. Kotschy         > Kotschy, C.G.T.    > Yes – the name in the **Collector** field has been interpreted
  Dr Hooker           > Hooker, J.D.       > Yes – the name in the **Collector** field has been interpreted
  Bowm.               > Bowman, E.         > Yes – the name in the **Collector** field has been interpreted
  Fr. Nicolas         > Nicolas, G.        > Yes – ‘Fr.’ has been interpreted as a title, rather than an abbreviated first name
  Thwaites            > Thwaites, G.H.K.   > Yes – the initials have been inferred

##### Collector inferred

If the collector has been inferred, tick the **Collector inferred** check box. Information about how the collector has been inferred can be entered in the **Miscellaneous notes** field, along with any relevant sources.

##### Collector unknown

If there is no collector’s name on the sheet, and the collector cannot be inferred, tick the **Collector unknown** check box. ‘However, if the collecting label says ‘Unknown’, enter ‘Unknown’ in the **Verbatim collectors** field.

##### Collector illegible

If the collector’s name is on the sheet, but is illegible, tick the **Illegible** check box.

##### Verbatim collecting date

If the collecting date is given in a format that cannot be entered in the date field, it should be entered here (e.g. ‘late March’, ‘Spring’, ‘Christmas 1912’). If the collecting date is given in a non-standard form but includes a year, or a year and a month, the date should also be entered in the collecting date fields (**Start date** and **End date**).

#### Date inferred

If the collecting date has been inferred, tick the **Date inferred** check box. Do not infer collecting dates from other database records; collecting dates should only be inferred from published sources, such as expedition journals, exsiccata lists or other publications.

Information about the source of an inferred date can be entered in the **Miscellaneous notes** field; however, if the date has been inferred from the collector’s lifespan or known period of activity, enter that information in the **Agent** table instead.

#### Plant origin

##### Introduced status

The introduced status of the specimen at the collecting locality. This information will either be provided by the collector, in the exchange data, or assessed by a botanist at a later date. Data entry staff do not need to assess introduced status. Where this information is provided by the collector or in the exchange data, enter the exact wording in the **Collecting notes** field, and select the corresponding category from the pick list. The following values can be selected from the pick list:

-   Native – the taxon is native to the collecting locality

-   Not native – the taxon is not native at the collecting locality

-   Unknown – the introduced status of the taxon at the collecting locality is unknown.

If the **Introduced status** field is filled in, the introduced **Source** field must also be completed.

##### Introduced source

The source of the introduced status. The following values can be selected from the pick list:

-   Collector – the introduced status was provided by the collector

-   Exchange data – the introduced status was provided in the exchange data

-   JCR – the introduced status was assessed by John Reid

-   Label data – the introduced status appears on the original label, but it’s not clear that it was provided by the collector

-   NGW – the introduced status was assessed by Neville Walsh

-   VS – the introduced status was assessed by Val Stajsic.

If other values need to be added to the pick list, please see the Digital Collections Advisor.

##### Introduced status date

The date that the introduced status was assessed, if known.

<span id="_Toc284176845" class="anchor"></span>

##### Cultivated status

The cultivated status of the specimen at the collecting locality. This information will either be provided by the collector, in the exchange data, or assessed by a botanist at a later date. Data entry staff may also make an assessment of whether the specimen was ‘Presumably cultivated’ or ‘Possibly cultivated’ if the collecting information is ambiguous, but do not need to assess the cultivated status otherwise. Where this information is provided by the collector or in the exchange data, enter the exact wording in the **Collecting notes** field, and select the corresponding category from the pick list. The following values can be selected from the pick list:

-   Cultivated – the specimen is known to have been grown in cultivation at the collecting site

-   Presumably cultivated – the specimen is presumed to have been cultivated, based species distribution, collecting information (e.g. ‘Ex. horto bot. Berolinensi’) or other information

-   Possibly cultivated – the specimen is thought to have possibly been cultivated, based on species distribution or collecting information

-   Not cultivated – the specimen is known to have not been cultivated

-   Unknown – the cultivated status of the specimen is unknown.

If the **Cultivated status** field is filled in, the cultivated **Source** field must also be completed.

Note that if a plant was collected from the wild and grown on for a brief period of time until it developed features needed for identification, then it should not be considered cultivated. For example, if a liverwort is collected and then left on a windowsill for a week until it has formed antheridia, or if a flowering plant is left in water for a week until its flowers open, then they should not be considered cultivated. Details about how the specimen was treated after being collected from the wild should be entered in the **Collecting notes** field, if provided by the collector, or in the **Miscellaneous notes** field if inferred by the data entry person.

##### Cultivated source

The source of the cultivated status. The following values can be selected from the pick list:

-   Collector – the cultivated status was provided by the collector

-   Data entry person – the cultivated status was assessed by the data entry person

-   Exchange data – the cultivated status was provided in the exchange data

-   Label data – the cultivated status appears on the original label, but it’s not clear that it was provided by the collector

-   Other – the cultivated status was assessed by someone else.

##### Cultivated status date

The date that the cultivated status was assessed, if known.

##### Provenance

The provenance details for cultivated specimens, if provided by the collector. Always enter the site of cultivation as the collecting locality for records of cultivated plants.

#### <span id="_Toc283306504" class="anchor"><span id="_Toc284176848" class="anchor"></span></span>Habitat

##### Associated taxa

A list of other plants, algae or fungi growing in association with the specimen. If the collector has provided a distinct list of associated taxa, enter it in the **Associated taxa** field, rather than in the **Habitat** field; if the associated taxa are listed as part of the general habitat description, they can be entered in **Associated taxa**, but should also be included in the full habitat description to avoid losing meaning or context. Where genus names have been abbreviated, and it is clear which genus is being abbreviated, spell them out in full in order to facilitate querying. Any associated species that are included as part of the general habitat description should not be listed in this field. If in doubt, only enter associated taxa if the collector has prefaced the list with ‘associated species’, ‘growing in association with’ or similar wording. Examples of what should be entered in the **Habitat** and **Associated taxa** fields are provided on page 49.

##### Host taxon

The taxon name of the host of the specimen, if known. The **Host taxon** field will eventually be linked to the **Taxon** table, but, for now, simply enter the taxon name as a string of text. If the collector has only provided a common name, only add the taxon name if it is unambiguous and easy to determine.

*Note:* If the specimen bears a separate identification for the host taxon of a parasitic plant or fungus, you can just record the determination in the **Miscellaneous notes** field, instead of creating a separate collection object record.

##### Common name

The common name of the host, if provided by the collector. Sometimes a brief description of the host will be provided (e.g. ‘some sort of caterpillar’); this information can also be entered in the host **Common name** field.

##### Substrate

Information about what the specimen is growing on, if provided by the collector. This field should only be used to record the microhabitat that a cryptogam is growing in; descriptions of the soil or underlying geology of the collecting locality should be included in the habitat description. Examples of what should be entered in the **Habitat**, **Host** and **Substrate** fields are provided below.

---------------------------------------------------------------------------------------- ----------------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Habitat, Host or Substrate?
  ###### Collecting information
  On moss on granite outcrop in scrub.
  On old bark at base of tree in eucalypt woodland.
  Beneath leaf litter under *Quercus*.
  On the ground amongst litter.
  In *Eucalyptus* woodland, fruiting body growing out of roots of *Eucalyptus baxteri*.
  Growing out of Witchety Grub in *Acacia* root.
  Growing on *Eucalyptus polyanthemos* in open eucalypt woodland with grassy understory.
  Growing on sandy soil derived from granite.
---------------------------------------------------------------------------------------- ----------------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 

### <span id="_Toc284176860" class="anchor"><span id="_Toc284178248" class="anchor"><span id="_Toc492047887" class="anchor"><span id="_Toc283306520" class="anchor"><span id="_Toc283306513" class="anchor"></span></span></span></span></span>Collection object (continued)

##### Descriptive notes

A description of the specimen provided by the collector. **Descriptive notes** includes information about the habit of the specimen, as well as information such as flower colour, the shape and size of leaves, and other features.

Descriptive notes that were written by someone other than the collector should generally be entered in the **Det. notes** field in the **Determination** form. As an exception, if the descriptive notes have been written by an Identifications Botanist, who has seen the fresh material and clearly indicates that this should be databased as a descriptive note, not a det. note, it can be added in this field, but the author and date of the descriptive notes should be provided in brackets. For example:

-   ‘Skin very thin, egg very soft, gleba jelly-like, phallus firmer textured. Eggs to 35 x 20 mm, mature phalli to 70 x 24 mm, generally cylindrical, straight or often curved to some degree. White rhizomorphs. Smell is similar to rotting bananas. \[Description by V. Stajsic, 15/6/2012.\]’.

##### Miscellaneous notes

Any notes relating to the specimen or collecting event that are not provided by the collector. Notes provided by the collector should not be entered here, but should go in **Collecting notes**. This field can be used for any annotations or curatorial comments about the specimen that may be of interest to anyone using the specimen data. This includes comments about how specimen information has been interpreted, and notes authored by curators of personal herbaria (such as Steetz or Sonder). If the annotation appears on the specimen, it doesn’t need to be enclosed in brackets, but if it’s entered at the time of data entry, it should be enclosed in brackets (this will help us distinguish one annotation from the next). For example:

-   ‘\[There are two labels on the sheet but only one specimen.\]’

-   ‘\[Extract from letter from H.I. Ashton to R.O. Belcher, 6 July 1981 which explains collecting information is attached to sheet.\]’

-   ‘Donated by Miss Lecky, May 1931. ‘

-   ‘misit amicus Dr. Short, 1843’.

-   ‘\[Collecting no. above represents Whinray's despatch no. to MEL. Duplicates of this collection sent to other herbaria may have different despatch nos.\]’

-   ‘\[The original label says 'Portland V. May 1931 (Miss Lecky) ... Miss M. Wise Sept. 1895'. Miss May Wise collected in 1895, but not at Portland. Miss Lecky did collect at Portland. It's probable that either Miss Wise did not collect the specimen, or the specimen is not from Portland. It's also possible that there are two separate collections represented on the sheet. -- A.C. Vaughan, Oct. 2013\]’.

-   ‘Collected under the auspices of the Maude Gibson Trust of the Melbourne Botanic Gardens and National Herbarium’.

-   ‘\[Collecting number assigned by A.C. Beauglehole.\]’.

Where annotations involve matters of interpretation, they should always include the author of the annotation and the date, and any relevant sources. Preface the name of the person who authored the annotation with a double hyphen and space (as in the last example above).

Information about projects that the specimen has been used or collected for should also be entered in **Miscellaneous notes**. For example:

-   ‘Sampled for the Victorian Conservation Seedbank’

-   ‘Seen by Bentham’.

Note that information on exchange labels that relates to the curation or use of a duplicate specimen held at another herbarium (e.g. ‘Spirit material at BRI’; ‘Voucher for DNA sample’, ‘Voucher for essential oils analysis…’) should not be entered in the MEL collections database.

In future, details of projects for which the MEL specimen is a voucher will be recorded in a separate table. In the meantime, information about projects should be entered in the **Miscellaneous notes** field (and never in **Collecting notes**). Note that information about destructive sampling should be entered in the **Conservator description** table.

##### Collection object attributes

The **Collection object attributes** table records additional information that is specific to the **Collection object**, including phenology, label data, curation notes and other information.

&lt;&lt;image&gt;&gt;

##### Conservator description

The **Conservator description** table is used to record information about damage to specimens.

&lt;&lt;image&gt;&gt;

##### Collection object attachments

Any attachments that relate to the collection object, such as images of letters or illustrations associated with the specimen, or a digital image of the specimen.

&lt;&lt;image&gt;&gt;

#### Label printing information

##### Label code

This field can be used to flag records that you want to print labels for, in order to make it easier to query for them when making record sets for label printing (but the field does not need to be populated in order to print labels for that record). It is purely an administrative field, and there are no restrictions on what can be entered.

##### Mixed collection notes

The **Mixed collection notes** field allows you to enter brief details of the different parts of a mixed collection, so that they appear on the printed MEL label. You only need to use this field for new collections that don’t have original collecting labels.

Only one label is printed for a mixed collection. The **MEL number**, **Part** and **Taxon name** for parts B, C etc. will automatically be printed at the bottom of the label for part A. If there is more than one taxon on the sheet, but the separate components share the one set of collecting information, there is no need to enter anything in the **Mixed collection notes** field. Where there is more than one set of collecting information on the sheet, the **Mixed collection notes** can be used to provide a brief indication of how parts B, C etc. differ from part A, as follows:

-   If there is more than one collector on the sheet, enter the collector’s name (initials and last name), preceded by ‘Leg.’, e.g. ‘Leg. C. Stuart’

<!-- -->

-   If there is more than one collecting locality, enter a very brief description of the locality, e.g. ‘Mt Buffalo’, ‘near Halls Gap’

-   If there is more than one collecting date on the sheet, enter the date

-   If there is more than one collecting number on the sheet, enter the collecting number preceded by the collector’s name or initials. Never enter a collecting number in this field without including the collector’s name or initials.

Only enter locality or date information if there is more than one specimen from <span id="_Toc284176869" class="anchor"><span id="_Toc284178249" class="anchor"></span></span>the same collector on the sheet:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

### Collection object attributes

The **Collection object attributes** table records additional information that is specific to the **Collection object**, including phenology, label data, curation notes and other information.

##### Phenology

If the specimen has flowers, fruits, buds, or is leafless, fertile or sterile, enter a ‘1’ in the appropriate boxes. Note that the ‘1’ is only used to indicate the presence of features; it is not used to indicate how many flowers, fruit etc. there are on the sheet. Only enter a ‘1’ if you are absolutely sure of the presence or absence of these features.

#### <span id="_Toc283306515" class="anchor"><span id="_Toc284176871" class="anchor"></span></span>Label data

##### Ethnobotanical info.

Notes about the ethnobotanical usage of the plant, alga or fungus, if provided by the collector. For example:

-   ‘Bark and roots used as fish poison’

-   ‘Incolis medicamentum \[?=used as medicine\]’

-   ‘Before the introduction of cats natives used a piece of the root – squeezing sap into food & placing it near their feet to be eaten by rats & mice & in the morning these would be found dead. The mice have a particular liking for the soles of the feet – hence their placing the poison near their feet’.

Data entered in this field will be printed on MEL labels, so do not repeat any ethnobotanica<span id="_Toc284176873" class="anchor"></span>l information in other fields.

##### Toxicity

Information about the toxicity of the specimen, if provided by the collector. For example:

-   ‘When fed to horses, produces fatal results’

-   ‘Poisonous to cattle’.

Longer descriptions about a poisoning case should also be entered here, rather than in **Collecting notes**. For example:

-   ‘Dog from this locality very sick and thought to have ingested this fungus. Dog from same locality died same time last year. Severe gastro-intestinal irritation, damage to wall of bowel. Specimen of fungus brought in by vet.’

Data entered in this field will be printed on MEL labels, so do not repeat any toxicity information in other fields.

##### Common name

Any vernacular name for the plant, alga or fungus, if provided by the collector. For example:

-   ‘Common Broom’

-   ‘Kodhiro’

-   ‘Sikat’.

This field has a limit of 50 characters (including spaces).

##### Usage

Any remarks about the usage of the common name, such as the language in which the common name is given, or the ethnic group who uses the name. This field can also be used to record information about the appearance of the common name on the collecting label. For example:

-   ‘Enga language’

-   ‘This is called the Cardwell plum here’

-   ‘Name followed by a word in non-Latin script’

-   ‘Local name’.

In the second example, ‘Cardwell plum’ would also be entered in the **Common name** field. This field has a limit of 64 characters (including spaces).

<span id="_Toc284176876" class="anchor"></span>

##### Label language

This field is used to record the language(s) that the original specimen data is written in. Recording this information allows records to be queried by label language for the purpose of translating collecting information. Separate multiple languages with a comma and a space, e.g. ‘Spanish, German, English’.<span id="_Toc284176877" class="anchor"></span>

##### Translation confidence

This field is used to indicate the level of confidence applied to the translation of collecting information into English. The following values can be selected from the pick list:

-   Native or bilingual proficiency – translated by someone whose speaks, reads and writes the language with a proficiency equivalent to that of an educated native speaker

-   Full proficiency – translated by someone who is able to use the language fluently for most purposes

-   Limited proficiency – translated by someone who has enough knowledge of the language to translate collecting information without the aid of a dictionary or translation service

-   Bilingual dictionary – translated with the aid of a bilingual dictionary (printed or electronic)

-   Online translation service – translated using an online translation service (such as Google Translate).

##### Translated by

The person who provided the translation and the date provided, if known. Enter names and dates in the following format:

\[initials\] \[preposition\] \[last name\] \[suffix\], \[dd\] \[mmm\] \[yyyy\]

For example:

-   ‘D. Sinkora, 12 Dec 1977’

-   ‘B. Meurer-Grimes, Feb 2001’.

#### <span id="_Toc283306516" class="anchor"><span id="_Toc284176879" class="anchor"></span></span>Data entry notes

##### Curation notes

Notes about the specimen that are only of relevance for internal curation purposes, e.g. missing specimens, notes about MEL numbers being reassigned. Data in this field will not be delivered to the Australasian Virtual Herbarium (AVH).

-   ‘Specimen could not be located, April 2014.’

-   ‘Extracted from Victorian Reference Set and returned to the main collection, 12/11/2013.’

Annotations made by people other than the collector or data entry staff, such as Nancy Burbidge or Jim Willis, should be entered in the **Miscellaneous** **notes** (unless they relate to the collecting locality, in which case they should be entered in **Georeferencing notes**). For example:

-   ‘Field label removed to handwriting file J.H. Willis 15/5/1961.’ should be entered in **Curation notes**

-   ‘No. 88 from J.H. Willis to G.O.K. Sainsbury.’ should be entered in **Miscellaneous notes**

-   A comment about the collecting locality by J.H. Willis, e.g. ‘Not Kallista, but could be Monbulk’, should be entered in **Georeferencing notes**

-   ‘Common in lawns of Melbourne Botanic Gardens. J.H. Willis.’ should be entered in **Miscellaneous notes**.

##### Curation sponsor

The organisation or individual who sponsored the curation of the specimen, e.g. CASS Foundation. Only the sponsor’s name should be entered in this field; a script will prefix the sponsor’s name with ‘The curation of this specimen was generously sponsored by’ when printed on the specimen label.

#### <span id="_Toc283306517" class="anchor"><span id="_Toc284176882" class="anchor"></span></span>Other

##### Original collection

Information about the personal herbarium, exsiccata series or other collection from which the specimen originates. For example:

-   ‘Herbarium O.W. Sonder (1812–1881)’

-   ‘Lichenes Rariores et Critici Exsiccati’

-   ‘Plantes des Tunisie’

-   ‘Plantae Mexicanae’

-   ‘Plantes d’Espagne’.

If the specimen has come from more than one collection (e.g. via both Steetz’s and Sonder’s personal herbaria), enter all the information in this field, and use a pipe (‘|’) to separate the different collection names. If it does not all fit, it can be abbreviated to ‘Ex Herbarium Steetz, Ex Herbarium Sonder’, etc.

If there is more than one original collection, and one or more of them has a number, enter the number next to the collection name in the **Original collection** field instead of the **Number** field, to avoid confusion:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

##### Fascicle

The fascicle number in an exsiccata series.

&lt;&lt;image&gt;&gt;

##### Number

The specimen number in an exsiccata series or a number within a personal herbarium. For example:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

If there is more than one original collection, and one or more of them has a number, enter the number next to the collection name in the **Original collection** field instead of the **Number** field, to avoid confusion:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

##### Illustration

This field is used to indicate that there is an illustration associated with the specimen.

##### Photograph

This field is used to indicate that there is a printed photograph accompanying a specimen, such as a habitat photo. If the specimen is a photograph of a specimen held at another institution, it should be databased as a ‘Photograph of specimen’ preparation in the *Photographs of specimens* collection, and not in the *National Herbarium of Victoria* collection.

The existence of high-resolution digital images created for the GPI project will be flagged in the **GPI** field, and does not need to be recorded here; high-res digital images (of GPI quality) that are taken for other purposes will be flagged in the **Imaged** field. Other digital images relating to the specimen should be attached the relevant table (see **Attachments**, p. 98).

##### Spore print

This field is used to indicate that there is a spore print with a fungi specimen.

<span id="_Toc283306523" class="anchor"><span id="_Toc284176903" class="anchor"></span></span>

### Conservator description

The **Conservator description** table is used to record information about destructive sampling and damage occurring to specimens.

##### Preparation

Select the preparation type that has been damaged or destructively sampled. If more than one preparation type of a specimen has been damaged or sampled from, a separate **Conservator description** will need to be entered for each preparation.

##### Event type

Select the event type; the following values are currently available in the pick list:

-   Destructive sampling

-   Damage to specimen.

If a specimen has been subjected to more than one event type (i.e. has been both destructively sampled from *and* damage has occurred), a separate **Conservator description** record will need to be entered for each event.

### Events

The **Events** section of the **Conservator description** form is used to record the details of a single instance of damage or destructive sampling of a preparation. If the preparation has been damaged or sampled more than once (and if it is possible to distinguish between the different damage events), each instance of damage or destructive sampling should be treated as a separate event. The form is split into three sections: fields relevant to ‘Destructive sampling’ events, fields relevant to ‘Damage to specimen’ events, and fields relevant to both event types.

##### Researcher

The name of the person who has carried out the destructive sampling or on whose behalf destructive sampling was undertaken by a staff member.

##### Sampling date

The date the destructive sampling occurred. The sampling date can be entered as a full date (day, month and year), a month and year, or a year only. Select the date type from the date drop-down list, then enter the date using the number keys.

##### Purpose

The intended purpose of the destructive sampling (e.g. DNA sequencing, pollen sample, leaf cuticle analysis).

##### Results

A statement of the results of destructive sampling (e.g. whether DNA was successfully extracted). Information about DNA sequences (e.g. GenBank accession numbers) will be recorded in the **DNA sequence** table.

##### Cause of damage

The organism or event that damaged the specimen. The following values are currently available in the pick list (if another value needs to be added, see the Digital Collections Advisor):

-   beetle

-   cigarette beetle

-   fire

-   human

-   inadequate packaging

-   insect

-   mould

-   psocid

-   silverfish

-   unknown

-   water.

Where more than one option applies, always choose the most descriptive term, e.g. ‘silverfish’ rather than ‘insect’.

##### Severity

The severity of the damage to the specimen. The following values are available in the pick list:

-   minor

-   moderate

-   severe.

If different parts of the specimen have received different levels of damage (e.g. minor damage to stem and moderate damage to leaves), only enter the most severe category of damage present. If additional information about the severity of damage needs to be recorded, enter it in the **Comments** field.

##### Verbatim date noticed

If the date damage was noticed is given in a format that cannot be entered in the date field, it should be entered here (e.g. ‘late October’, ‘summer of 1964’). If the date noticed is given in a non-standard format but includes a year or a year and a month, the date should also be entered in the **Date noticed** field.

##### Date noticed

The date damage to the specimen was noticed. The date can be entered as a full date (day, month and year), a month and year, or a year only. Select the date type from the date drop-down list, then enter the date using the number keys.

##### Assessed by

The staff member who assessed the damage to a specimen.

##### Date assessed

The date on which damage to a specimen was assessed by a staff member. The date assessed can be entered as a full date (day, month and year), a month and year, or a year only. Select the date type from the date drop-down list, then enter the date using the number keys.

##### Treatment report

Information about the treatment provided to the specimen, such as the names of the agents or organisations providing the treatment, when the treatment occurred, a description of the treatment, and any notes about how the damage to the specimen has been documented.

##### Part of specimen

The part/s of the specimen that have been destructively sampled from or damaged. The value of the field can be one or more of the following (if more values need to be added, please see the Digital Collections Advisor):

-   alga

-   fungus

-   lichen

-   liverwort

-   moss

-   buds

-   inflorescence

-   fruit

-   cone

-   leaves

-   rhizome

-   roots

-   stem

-   bark

-   label

-   seeds

-   sori.

If more than one part of the specimen has been damaged, separate each part with a comma and a space, e.g. ‘stem, leaves’.

##### Comments

Any additional information about destructive sampling or damage to the specimen.

##### Conservator event attachments

Any attachments documenting the damage to the preparation.

&lt;&lt;image&gt;&gt;<span id="_Toc283306507" class="anchor"><span id="_Toc284178252" class="anchor"></span></span>

## Locality form

### <span id="_Toc284176909" class="anchor"><span id="_Toc284178253" class="anchor"><span id="_Toc492047892" class="anchor"></span></span></span>Locality

The **Locality** form contains all the details of the collecting locality. It contains two subforms: **Locality details** and **Geocoordinate details**.

##### Geography

The higher level geography for the collecting locality. If the geography is unknown, enter ‘Earth’ in this field (this will allow us to tell the difference between records where the geography is unknown, and where it has been accidentally omitted). There are four levels of geography in the **Geography** table: **Continent**, **Country**, **State** and **County**.

Start typing the country, state or county name, then press the down-arrow to see a list of corresponding entries. Note that there are no county names for Australia in the **Geography** tree.

If any of the four levels is selected from the list, the parent geography will be automatically filled in, so enter the most specific information possible. For example, if you look up the state ‘Victoria’ in the query combo box, the full name will include the country (‘Australia’) and continent (‘Australasia’):

**&lt;&lt;image&gt;&gt;**

The continent number and name come from the *World Geographic System for Recording Plant Distributions* (WGS). The continent names and numbers are used in the storage system for specimens collected outside Australia

The country, state and county names in the **Geography** tree come from the International Organization for Standardization (ISO 3166 standard), and many may have unfamiliar spellings. If you can’t find the place name you are looking for in the drop-down menu, browse the **Geography** tree to see if you can find it. For example, Burma is listed by its official name, Myanmar, so a search for ‘Burma’ in the **Geography** drop-down list won’t return any results:

&lt;&lt;image&gt;&gt;

If you browse the **Geography** tree, you will see that it is listed as Myanmar:

&lt;&lt;image&gt;&gt;

Specify allows for entries in the **Geography** tree to be synonymised, which means that a query on either name in a **Collection object** query will return the same results. See **Search synonyms** (p. 158) for more information. If you would like a synonym of a place name to be added to the **Geography** tree, please see the Digital Collections Advisor.

Note that, in WGS, Russia occurs in Europe as well as in Asia – Temperate. If the collecting locality only gives ‘Russia’ as the collecting locality, select ‘Russia, Europe’ from the **Geography** drop-down list.

Be aware that countries that have dependencies in other continents will also be listed under more than one continent. For example, France is in Europe, but it also has a dependency in Southern America (Clipperton Island):

&lt;&lt;image&gt;&gt;

The option ‘France, Southern America’ should never need to be selected, because if the label has enough information for you to know that the specimen was collected in a French dependency in Southern America, then it probably also gives you enough information to select the relevant entry from the **State** level in the **Geography** tree.

Note that it is not possible to enter a combination of geographic place names. If the collecting locality traverses two or more regions, enter the next region in the hierarchy. For example, if the collecting locality is given as ‘Murray River’ (which borders New South Wales and Victoria, and flows through South Australia), ‘Australia, Australasia’ should be selected from the **Geography** drop-down list.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Cultivated plant records

  Cultivated plant specimens were previously databased with ‘Cultivated’ in the geography fields instead of the geographic place names. This practice is no longer used at MEL. Cultivated plant records should be databased with the geographic hierarchy entered in the **Geography** field, and other relevant details entered in the **Locality** form. The **Collecting event attributes** subform contains fields to record the **Cultivated status** and the **Source** of the cultivated status.
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##### Locality 

The description of where the specimen was collected, as provided by the collector. No punctuation is added to labels, so include a full stop after the locality, even if it is not a proper sentence.

If there are absolutely no locality details provided (and thus ‘Earth’ has been entered in the **Geography** field), enter ‘\[No details given\]’ in the **Locality** field. If the there is no description of the locality other than what has already been entered in the **Geography** field, repeat the lowest ranked place name in the **Geography** name in the **Locality** field. For example, if the collecting locality is only given as ‘Victoria’, ‘Victoria’ should be entered in the **Locality** field as well as in the **Geography** field:

&lt;&lt;image&gt;&gt;

If the only description of the collecting locality is UTM coordinates, a map reference, a botanical region or a Victorian grid reference, enter it in the **Locality** field, as well as in the field where it belongs:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

If only altitude or latitude and longitude have been provided, enter them in the relevant fields, and enter ‘\[No details given.\]’ in the **Locality** field:

&lt;&lt;image&gt;&gt;

Minor corrections to, or interpretations of, the locality description should be entered in brackets in this field. For example:

-   ‘Balarrat \[=Ballarat\].’

-   ‘6 m\[iles\] west of Horsham’.

Any comments about the locality description or an explanation of why the locality could not be georeferenced should be entered in the **Not geocoded because** and **Georeferencing notes** fields in the **Geocordinate details** form.

Locality information should be entered exactly as it appears on labels (unless the description exceeds the field size – see below). Do not convert miles to kilometres. If the unit of distance has been given as ‘m’ and you suspect that it refers to miles rather than metres, append the m with ‘\[iles\]’ to make it clear that only ‘m’ has been given on the label; do not write ‘miles’.

The **Locality** field has a limit of 255 characters (including spaces). If the locality description exceeds the field length, first check if there is information in the locality description that belongs in other fields, such as map references or original uncertainty values. If necessary, the locality description can be shortened by using standard abbreviations in place of whole words. Refer to the list of abbreviations in **Appendix** **1. Abbreviations** (p. 210) for the correct formatting.

If the locality description still exceeds 255 characters, if possible, ask the collector to shorten the description, or shorten it at your own discretion. Locality descriptions that are particularly long may need to be split between the **Locality** field and the **Collecting notes**. In this case, ensure that the most important locality information is in the **Locality** field.

##### Latitude and longitude

Geocodes can be entered in one of the following formats:

-   Decimal degrees – e.g. 37.8272°

-   Degrees and decimal minutes – e.g. 37° 49.629′

-   Degrees, minutes and decimal seconds – e.g. 37° 49′ 37.74″

Select the lat/long type from the drop-down list, and enter the latitude and longitude in the fields provided.

The lat/long type is set to default to ‘Degrees, minutes and decimal seconds’, and the hemisphere fields are set to default to ‘S’ and ‘E’. The default preferences can be changed by clicking on the **Information** symbol at the right of the lat/long form. Note that the changes will only come into effect after the current **Collection object** record has been saved. Changing the default preferences will only affect your own user account.

Once the geocode has been entered, you can convert it to the different lat/long types using the drop-down list. The original geocode format is recorded in the database (and is visible on the form), and is used as the source for conversions between geocode formats. Note that editing the geocode will overwrite the source geocode.

Geocode information can be entered as a point, line or polygon. For botanical specimens, latitude and longitude are generally provided for a single point, but if the collector has provided line data (i.e. two sets of latitude and longitude that define a line between two places), or polygon data (i.e. three or more points that define a polygon around a certain area), these can be entered by selecting the line or polygon button.

If the collector has only provided UTM coordinates, you can choose to leave the **Latitude and longitude** fields blank (but note that the record cannot be mapped unless the latitude and longitude are provided).

##### Datum

The geodetic datum of the geocode.

The datum refers to how the earth is modelled and affects where exactly lines of latitude and longitude occur on the ground. There are a number of different datums in use and each results in a slightly different latitude and longitude grid. **Datum** should be recorded where the geocode was determined by the data entry person, if the geocode was determined by GPS, or if the collector has indicated which datum was used. Note that MGA94 is a UTM projection of GDA94 coordinates; if the collecting label states ‘MGA94’, select ‘GDA94’ from the pick list.

Where the **Protocol** is ‘GEOLocate’, ‘GeoNames’ or ‘Google Earth’, the **Datum** will be automatically set to ‘WGS84’ when the record is saved. Where the **Protocol** is ‘GA gazetteer’, the **Datum** will be set to ‘GDA94’.

A guide to determining which datum was used is provided below.

###### GPS readings

> Most GPS units are set to use the WGS84 datum by default but, if the datum has not been recorded, check with the collector if possible.

###### Google Earth and Google Maps

> Google map products use the WGS84 datum.

###### Australian map references

> Maps could be based on any datum. Newer maps will probably be based on GDA94 and older maps will be AGD66 or AGD84. Check near the title of the map for the datum and/or coordinate system used. If the coordinate system is AMG66, then the datum is AGD66. If it is a newer map the coordinate system might be MGA94, in which case it the datum is GDA94. Most of the maps in the Royal Botanic Gardens Library use AGD66.

###### Reader’s Digest Atlas of Australia

> The Reader’s Digest *Atlas of Australia* (1994) is assumed to be in AGD66.

###### Melway

> *Melway* directories up to edition 30 use AGD66. From edition 31 (2004) onwards, the datum is GDA94.

###### VicRoads State Directory

> VicRoads used AGD66 up to edition 4. From edition 5 onwards, the datum is GDA94.

##### Source

The source of the geocode. The following values are available in the pick list:

-   Collector

<!-- -->

-   Data entry person

-   Exchange data.

##### Protocol

The method by which the geocode was determined. The following values are available in the pick list:

-   AMG conversion – the geocode was converted from an AMG reference that was provided by the collector

-   GA gazetteer – the geocode was found on the Geoscience Australia place names of Australia gazetteer

-   GEOLocate – the geocode was determined using GEOLocate

-   GeoNames – the geocode was found on the GeoNames website

-   Google Earth – the geocode was determined using Google Earth

-   GPS – the geocode was determined by GPS

-   Map or atlas.

If the **Source** is ‘Exchange data’, you don’t need to fill in **Protocol** unless it’s provided in the exchange data. Where GeoLocate is used to georeference the locality, **Protocol** and **Source** will be automatically filled in.

Note that *Melway* references should not be converted to latitude and longitude due to the differences in *Melway* references between editions.

##### Uncertainty

The level of uncertainty in the geocode. The following categories of geocode uncertainty apply:

-   1\. 0 – 50 m

-   2\. 50 m – 1 km

-   3\. 1 – 10 km

-   4\. 10 – 25 km

-   5\. &gt; 25 km.

##### Collector’s uncertainty

If the collector has provided an uncertainty value with the geocode, this should be entered here, along with the units in which the uncertainty is given.

##### Min. altitude

The altitude, if provided by the collector. If altitude is given as a range, enter the lower value here. If the altitude is provided in feet, enter it in feet, rather than converting it to metres.

If the altitude is given as a range, enter the lower value here. If the altitude is provided as less than a certain value, e.g. ‘&lt;1200 feet’, enter the measurement in **Max. altitude**, leave **Min. altitude** blank, and enter the verbatim text in **Verbatim altitude**.

##### Max. altitude

If the altitude is given as a range, enter the higher value here. If the altitude is provided as less than a certain value, e.g. ‘&lt;1200 feet’, enter the measurement here, leave **Min. altitude** blank, and enter the verbatim text in **Verbatim altitude**.

##### Unit

The units in which the altitude is provided (metres or feet).

##### Altitude method

The method by which the altitude was determined. The pick list contains the following values:

-   Altimeter

-   Altimeter (corrected)

-   DEM \[digital elevation model\]

-   Field estimate

-   Google Earth

-   GPS

-   Map

-   Unknown.

##### Verbatim altitude

<span id="_Toc284176919" class="anchor"></span>If the altitude is provided in a format that can’t be unambiguously recorded in the other altitude fields, enter it here as it appears on the label (but record relevant parts of the altitude in other fields as well). For example:

-   ‘&lt;500 ft’ (also enter ‘500’ in **Max. altitude** and ‘feet’ in **Unit**)

-   ‘c. 5 m’ (also enter ‘5’ in **Min. altitude** and ‘metres’ in **Unit**)

-   ‘about sea level’ (also enter ‘0’ in **Min. altitude**).

##### GEOLocate

Clicking the **GEOLocate** button launches the GEOLocate georeferencing service. GEOLocate uses the **Locality** description and geographic location to find latitude and longitude coordinate data for specimen records. See the **Plugins** section (p. 200) for more information.

##### Display in World Wind

Clicking the **Display in World Wind** button will open the World Wind application. The link to World Wind is available in the **Locality** form at any time. See the **Plugins** section (p. 200) for more information. <span id="_Toc284176921" class="anchor"></span>

##### Display in Google Earth

Clicking the **Display in Google Earth** button will map the current record in Google Earth. The record must have a latitude and longitude for the **Display in Google Earth** button to become active.

##### Locality attachments

Any attachments that relate specifically to the collecting locality (and not to the specimen itself), such as a map of the locality.

&lt;&lt;image&gt;&gt;

### Locality details

##### Island group

The name of the island group where the specimen was collected. For example:

-   ‘Furneaux Group’

-   ‘Cocos (Keeling) Islands’.

See the **Island group, Island and Water body** usage notes below for more information.

##### Island

The name of the island where the specimen was collected. For example:

-   ‘New Guinea’

-   ‘Flinders Island’

-   ‘Tierra del Fuego, Isla Grande de’.

See the **Island group, Island and Water body** usage notes below for more information.

##### Water body

The name of the water body the collecting site is in. Use for things collected on islands (especially small ones) or in the water. For example:

-   ‘Port Phillip Bay’

-   ‘Bass Strait’

-   ‘Indian Ocean’.

See the **Island group, Island and Water body** usage notes below for more information.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Island group, Island and Water body

  Please note that **Island group**, **Island** and **Water body** are interpreted fields, and that the entire verbatim location should still be entered in the **Locality** field. These fields will not be printed on labels, but are delivered to the AVH, where they will (at some point in the future) be able to be queried on. Use these fields if you think it adds information to the record. Good examples are:

  -   Specimens collected from Borneo or New Guinea where it is unknown in which part of the island (and in which country) the collection was made

  -   Specimens collected from Macquarie Island. or Lord Howe Island. – these cannot be queried in the AVH and they are often missed when querying by coordinates, as small errors in the coordinates could land the collecting location in the sea.

  When using these fields, please use names from a controlled vocabulary, such as the *Gazetteer of Australia* (<http://www.ga.gov.au/placename>) or *Getty Thesaurus of Geographic Names* (<http://www.getty.edu/research/tools/vocabularies/tgn/>). These fields can be quite easily populated retrospectively for places of interest from the **Locality** field, so don’t worry too much about filling in these fields if you are uncertain of what to fill in.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##### Min. depth

The depth that the specimen was collected at. If depth is given as a range, enter the shallower value here. Enter the depth in the units it was provided; do not convert depth values to metres.

##### Max. depth

If depth is given as a range, enter the deeper value here. Enter the depth in the units it was provided; do not convert depth values to metres.

##### Depth unit

The units of measurement in which the depth is given. The values in the pick list are:

-   fathoms

-   feet

-   metres.

##### UTM Grid

The grid system used for the UTM coordinates, if known. The pick list currently includes the following values:

-   AMG – Australian Map Grid

-   MGA – Map Grid of Australia

-   UTM – Universal Transverse Mercator.

If other entries need to be added to the pick list, please see the Digital Collections Advisor.

##### UTM Zone

The zone for UTM coordinates. In the UTM system, the world is divided into 60 zones (numbered 1–60), each of which is six degrees of longitude wide. UTM zones are sometimes followed by a letter that indicates the Military Grid Reference System (MGRS) Zone, e.g. ‘55H’. If provided, MGRS Zones should also be entered here.

##### UTM Easting

The easting is a measure of how far east the location is within the zone. Easting values should be six digits long.

##### UTM Northing

The northing is a measure of how far north the location is within the zone. Northing values should be seven digits long.

##### Map reference

If a map reference has been provided, such as the mapsheet on which the easting and northing are based, or a reference from a street directory, enter it here. For example:

-   ‘Melway ref. 211 K8’

-   ‘Eltham mapsheet’

-   ‘AMG – (Lerderderg 7722-1-2 map, 1:25000) 726-248’

-   ‘Wimmera Study Area Sector: f, Sub-block: 37f’.

Exchange labels from BRI often include a numerical map reference after the AMG coordinates (e.g. ‘7867-764725’), which can also be entered in this field.

If the edition of a street directory or the date of publication of a map is provided, make sure it is recorded in the database.<span id="_Toc284176932" class="anchor"></span>

##### Botanical region

The botanical region in which the specimen was collected, if provided by the collector or recorded on an exchange label. If the collector has recorded an IBRA region, there is no need to record it in this field.

##### Gazetteer

The place name in the gazetteer that is the source of the geocode. This information is useful when the locality provided on a label is quite detailed but, because the exact locality cannot be found on a map, the geocode assigned may be less precise than the locality description would lead you to think. Recording which gazetteer entry the geocode is based on will give an indication of the uncertainty of the geocode. For example:

-   ‘Sugarloaf Mountains, track from Tale River Valley, S of Wapenamanda’ – **Gazetteer**: Wapenamanda

-   ‘Cometville’ – **Gazetteer**: Comet

-   ‘King Leopold Range, Diamond Gorge Road, 15 km E of Fitzroy River, c. 170 km WNW of Halls Creek, c. 70 km NE of Fitzroy Crossing’– **Gazetteer**: Diamond Gorge.

In Texpress, this information was often entered as a note in the **Locality** field, for example, ‘Yandarlo via Wilcannia, Darling River. \[Lat/long is for Wilcannia.\]’.

### <span id="_Toc283306509" class="anchor"><span id="_Toc284176937" class="anchor"><span id="_Toc284178255" class="anchor"><span id="_Toc492047894" class="anchor"></span></span></span></span>Geocoordinate details

The **Geocoordinate details** form provides additional information about the locality, and how (or why) the geocode was (or was not) determined.

##### Georeference date

The date the specimen was georeferenced. This field will be automatically filled in when the record is saved. Where the geocode **Source** is ‘Collector’, the **Georeference date** will be the same as the date of collection. Where the geocode **Source** is ‘Data entry person’, the **Georeference date** will be the date of record creation. Where the geocode **Source** is ‘Exchange data’, the **Georeference date** will be left blank.

##### Geocode source

The source of the geocode, if it has been taken from an obscure source. For example:

1.  ‘Western Australian Phytogeographic Regions map, 1980’

2.  ‘Ampol Road Map, Queensland’

3.  ‘Uncommon locality index’.

This field has a limit of 64 characters (including spaces).

##### Georeferencing notes

Any notes about how the locality information has been interpreted, why a particular geocode was assigned, or any extra information about why a geocode was not assigned. For example:

-   ‘Lat/long taken for Cobar, as collector was in this area on this date.’

-   ‘Collector was known to be in Western Australia at this time.’

-   ‘There are several Bluff Mountains. Coordinates are for the Bluff Mountain closest to Tenterfield, as Stuart was known to be in that area on this date.’

-   ‘There are three Herbert Creeks in Queensland. It is unclear which Bowman collected at.’

-   ‘Locality not found on any maps or gazetteers.’

-   ‘There are several Mount Mitchells in New South Wales.’

Annotations about the collecting locality made by people other than the collector or data entry staff should also be entered in the **Georeferencing notes** field. For example:

-   A comment about the collecting locality by J.H. Willis, e.g. ‘Not Kallista, but could be Monbulk, J.H. Willis.’.

Notes that only indicate which locality has been selected, and not why it has been selected, (e.g. ‘Lat/long is for Rockingham’) should not be entered here. Instead, ‘Rockingham’ should be entered in the **Gazetteer** field.

##### Verified status 

**Verified status** is used to indicate whether the geocode of a record has been verified, or if it is awaiting verification. The values in the pick list are:

-   Requires verification

-   Verified by collector

-   Verified by curator.

This field has been populated with ‘Requires verification’ for specimen records that have been identified as outliers in the AVH. If anyone from MEL verifies or corrects a georeference, the value should be changed to ‘Verified by collector’ or ‘Verified by curator’, depending on who verified the georeference.

##### Not geocoded because

If you have attempted to assign a geocode to the locality, but were not able to, select one of the following values from the pick list:

-   Locality ambiguous – e.g. there multiple localities with the same name and it is unclear which one the collector was at

-   Locality not found – the locality name could not be located on maps or in gazetteers.

Any additional explanation of why the collecting locality could not be geocoded should be entered in the **Georeferencing notes** field.

If the locality is obviously vague (e.g. ‘South-eastern Australia’, ‘China’), it is not necessary to explain why a geocode was not assigned to the record.

### <span id="_Toc492047895" class="anchor"><span id="_Toc283306510" class="anchor"><span id="_Toc284178256" class="anchor"></span></span></span>Administrative fields

The following fields are automatically completed and cannot be edited.

##### Created by

The person who created the database record.

##### Created

The date the record was created.

##### Last edited by

The person who last edited the record.

##### Last edited

The date the record was last edited.

## Geography form

<span id="_Toc284176942" class="anchor"></span>The **Geography** form is used to enter geographical information at the continent, country, state and county levels. The data in the **Geography** table should be complete, so please see the Digital Collections Advisor before adding or editing any records in the **Geography** form.

##### Parent

To enter a new geographical area name, you need to indicate what place name the new name sits under in the **Geography** tree. For example, the parent of ‘Victoria’ is ‘Australia’, and the parent of ‘Australia’ is ‘Australasia’.

##### Geographic rank

The rank of the geographic place name. The rank must be one of the following:

-   Continent – the continent number and name from the World Geographic System for Recording Plant Distributions (WGS). The continent names and numbers are used in the storage system for specimens collected outside Australia.

-   Country – the ISO standard country name. There are also some WGS place names at this level, where the WGS name could not be mapped to an ISO country name (e.g. ‘Indian Subcontinent’, ‘Southwestern Pacific’).

-   State – the ISO standard state or province name

-   County – subdivisions of the state or province.

##### Name

The name of the continent, country, state or county.

<span id="_Toc284176945" class="anchor"></span>

##### Name on label

The geographic name, including diacritical marks. The name field (which does not include diacritical marks) will be used for querying and data entry, and this field will be used to record the geographic place name with diacritical marks, as it should appear on the label.

##### Comments

Any comments about the usage of the place name, or the history of the place. For example:

-   ‘Previously part of the Netherlands Antilles, which were dissolved in 2010.’

-   ‘Istria was part of Italy between 1919 and 1947.’

### <span id="_Toc283306511" class="anchor"><span id="_Toc284176947" class="anchor"><span id="_Toc492047897" class="anchor"></span></span></span>Subdivisions

The **Subdivisions** section lists the geographic place names that occur below the geographic place in the **Geography** tree.

##### Name

The name of the geographic subdivision.

## <span id="_Toc283306525" class="anchor"><span id="_Toc284178257" class="anchor"><span id="_Toc492047898" class="anchor"></span></span></span>Taxon form

<span id="_Toc284176949" class="anchor"></span>The **Taxon** form is used to enter new taxon names. In Specify, taxa or taxon names are stored in a taxon tree (or classification) with the genus, species, subspecies, variety and forma parts of the taxon name stored as individual records, which are linked through parent–child relationships.

##### Parent

The name of the parent taxon. For species names, this is a genus name; for genus names, a family name, etc. If a parent name is not in the drop-down list, it needs to be added using the **Taxon** form. If a parent of a family or higher rank is not in the drop-down list, it is probably easier to look up the lowest ranked ancestor in the **Taxon** tree and then open the **Taxon** form to enter the new names.

##### Rank

The rank of the taxon: genus, species, etc. Select the appropriate name from the drop-down list. Only ranks below the rank of the parent taxon to the next mandatory rank are available in the list.

##### Name

For names of taxa above the species level this is the taxon name; for species names it is the species epithet; and for names of infraspecific taxa, it is the infraspecific epithet. See **Formatting taxon** **names** (p. 88) for information on what to enter in this field for infraspecific names, hybrid names, cultivar names, and intergrades and intermediates.

##### Author

The author of the name, formatted according to the standard abbreviations listed in [IPNI](http://www.ipni.org/ipni/authorsearchpage.do). The **Author** field should be completed for genus and higher taxon names, as well as for species and infraspecific taxa.

Where the author of the taxon is different to the author of the publication in which the name is published, the author of the publication may be included in the **Protologue** field (see below).

##### Protologue

The original article the name was published in. This is compulsory for basionyms of which MEL holds a type, and is optional for other names.

The protologue string should include the following elements:

-   the standard abbreviation of the article or book in which the name was published

-   the volume of the book or journal, if relevant

-   the issue of the journal, in parentheses (note that the issue is only required if the page numbers are not contiguous between different issues in the same volume)

-   the page number separated by a colon and the year the name was published.

For publications whose author is different to that of the name, the author of the publication may be preceded by ‘in’. As this is the author of a publication rather than a name, author names should not be abbreviated here. The ‘in’ is important to make sure the protologue string prints correctly on labels.

&lt;&lt;image&gt;&gt;

##### Year

The year of publication of the protologue. This must be entered for taxon names for which MEL holds a type specimen, but can also be entered for other taxon names.

##### ms

If the taxon name has not yet been published, enter ‘ms’ in this field. Names flagged with ‘ms’ will be reported on periodically to check if the name has been published.

##### Full name

The full taxon name. This is a read-only field, and is automatically filled once the record is saved.

##### Nom. note

This field should be used to record nomenclatural notes that need to be printed with the taxon name, such as ‘non. R.Br.’, ‘nom. nud.’, ‘nom. inval.’ etc.

If the name is illegitimate, the preference is to indicate the correct authorship instead of using ‘nom. illeg.’, e.g. Acacia tenuifolia F.Muell. non (L.) Willd. (1806) would be entered as follows:

&lt;&lt;image&gt;&gt;

If the nomenclatural status has been filled in, it will be appended to the full name that appears in the **Taxon** name drop-down list, so that homonymous names can be distinguished.

&lt;&lt;image&gt;&gt;

If there are multiple homonyms for a name, include the author of the homonym in the **Nom. note** field so the different entities can be distinguished in the pick list:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

##### Is hybrid

This box needs to be ticked to indicate a hybrid or intergrade. Ticking this box will enable the **Hybrid parent** fields.

##### Hybrid category

This field is a pick list that lists the hybrid categories. The items in this list are:

-   Hybrid name

-   Hybrid formula

-   Intergrade or intermediate.

If ‘Hybrid name’ is selected, a multiplication sign (‘×’) will print in front of the name or epithet.

##### Hybrid rank

The rank at which the hybrid flag applies for hybrid names (e.g. ×*Glossadenia tutelata* vs. *Potamogeton* ×*sparganiifolius*). The items in this pick list are:

-   genus

-   species

-   infraspecific taxon.

##### Hybrid parent 1

<span id="_Toc284176957" class="anchor"></span>The first parent of a hybrid or intergrade. To avoid having more than one entry in the **Taxon** table for hybrids, intermediates or intergrades between the same taxa, hybrid parents should always be entered in alphabetical order, regardless of how they are listed on the det. slip. If the order of the names on the det. slip is deemed important, it can be recorded in the **Det. notes** field.

##### Hybrid parent 2

The second parent of a hybrid or intergrade.

##### Comments

Any additional comments about the taxon name.

### <span id="_Toc283306527" class="anchor"><span id="_Toc284176964" class="anchor"><span id="_Toc492047899" class="anchor"></span></span></span>Child taxa

This subform lists the child taxa of the current taxon. If the current taxon is a genus, for example, the child taxa are species.

##### Full name

The full name of the child taxon.

### <span id="_Ref369171315" class="anchor"><span id="_Toc492047900" class="anchor"></span></span>Attachments

##### Taxon attachments 

Any attachments that relate to a taxon name, such as PDFs of publications.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### <span id="_Ref303850986" class="anchor"><span id="_Toc284176966" class="anchor"><span id="_Toc283306528" class="anchor"></span></span></span>Adding new genus and higher taxon names

  Because the higher classification is decoupled from the MEL storage location in MELISR, when you add a new taxon record for ranks above species, you also need to define its storage location. The storage location is updated in the **Genus and higher taxon** **storage** page of the MELISR website: melisr.rbg.vic.gov.au/genusstorage. If you add a new genus or higher taxon name that will be used in a **Collection object** record, it’s best to define its storage location straight away, so that the storage location can be printed on the MEL label.

  To enter the storage location of a new genus or higher taxon:

    1.  Click **Add** next to the taxon name you just entered:

  > &lt;&lt;image&gt;&gt;

  The higher classification for the taxon name will be displayed:

  > &lt;&lt;image&gt;&gt;

    1.  In the **Stored under** drop-down list, select the MEL storage location (family or other grouping) for that taxon:

  > &lt;&lt;image&gt;&gt;

    1.  Click the **Insert** button:

  > &lt;&lt;image&gt;&gt;
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Formatting taxon names
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  In Specify taxa or taxon names are stored in a taxon tree (or classification) with the genus, species, subspecies, variety and forma parts of the taxon name stored as individual records, which are linked through parent–child relationships. Taxa at supra- and infrageneric ranks are stored the same way.

  One advantage of this is that taxa may be determined to any level in the **Taxon** tree, so if a specimen has only been identified to, say, order, you can just enter the name of the order in the **Determination** form.

  ###### Hybrid names

  Hybrid names are written with a multiplication sign (‘×’) in front of the name or epithet. In order for the name to show in the right position in the drop-down list in the **Determination** form, and to avoid duplication of the same name with and without the multiplication symbol, the multiplication symbol is not entered in the **Taxon** table, but will appear automatically on the label if ‘Hybrid name’ has been selected from the **Hybrid category** pick list. This allows us also to deal correctly with infraspecific hybrid names. Such names do not have multiplication symbols, but have ‘notho’ prefixed to the infraspecific rank prefix.

  ###### Hybrid formulae

  Hybrid formulae have the format *Parent 1* × *Parent* 2, e.g. *Eucalyptus baxteri* × *Eucalyptus obliqua*. In order to print the formula correctly on the label, ‘Hybrid formula’ has to be selected from the **Hybrid category** pick list and the **Hybrid parent 1** and **Hybrid parent 2** entered. Both parents need to be in the **Taxon** tree. In accordance with the recommendation in ICBN, we enter the parents in alphabetical order. In order for the hybrid formula to show in the drop-down list in the **Determination** form, the formula also needs to be entered correctly in the **Name** field. For ease of data entry and reliability of queries we use a lower case ‘x’ in the **Name** field.

  Hybrid formula are entered at the rank to which the first parent is identified, so the above example is entered as a species with parent *Eucalyptus* and ‘*baxteri* x *Eucalyptus obliqua*’ in the **Name** field. *Eucalyptus camaldulensis* var. *camaldulensis* × *Eucalyptus viminalis* will be entered as a variety with the **Name** ‘*camaldulensis* x *Eucalyptus viminalis*’ and **Parent** ‘*Eucalyptus camaldulensis*’. For clarity and unambiguity we do not abbreviate or leave out any parts of the parents’ names:

  ###### 

  &lt;&lt;image&gt;&gt;

  &lt;&lt;image&gt;&gt;We cannot deal with uncertainty in hybrid parents, so, if one of the parents is uncertain or unknown, only add **Hybrid parent 1** and write ‘&lt;Parent1&gt; hybrid’ in the **Name** field:

  &lt;&lt;image&gt;&gt;

  The full identification as written on the det. slip can be entered in **Det. notes**:

  &lt;&lt;image&gt;&gt;

  &lt;&lt;image&gt;&gt;

  ###### Cultivar names

  Registered cultivar names should be entered in quotation marks in the **Name** field, following the specific epithet. The **Author** field should be left blank.

  &lt;&lt;image&gt;&gt;

  If the species is not known, or not given, leave out the epithet:

  &lt;&lt;image&gt;&gt;

  If the specimen has only been identified to genus, but is recorded as a cultivar, e.g. ‘*Gaillardia* cv.’, the specimen should be databased with *Gaillardia* in the **Taxon name** field, and ‘cv.’ in **Extra information**.

  &lt;&lt;image&gt;&gt;

  You can check if a cultivar name has been registered on the Royal Horticultural Society website: (<http://apps.rhs.org.uk/horticulturaldatabase/>. If the name is not listed there, check with one of the Horticultural Botanists. Unregistered ‘cultivar’ names should be entered in **Det. notes**.

  When databasing cultivars, remember to flag the **Cultivated status** and/or **Introduced status** fields as appropriate.

  ###### Intergrades and intermediates

  Intergrades and intermediates are dealt with in a similar way to hybrid formulae and have the format *Taxon 1* – *Taxon 2*. ‘Intergrade/intermediate’ should be selected in the **Hybrid category** pick list and Taxon 1 and Taxon 2 are entered in the **Hybrid parent** fields. Like in hybrid formulae, the taxa between which the plant is intermediate are entered in alphabetical order (if considered important, the names of the taxa can be written in the order they are on the herbarium sheet or det. slip in the **Det. notes** field in the **Determination** form):

  &lt;&lt;image&gt;&gt;

  ‘Intergrade’ or ‘intermediate’ should be selected from the **Addendum** field in the **Determination** form to indicate which term was used by the determiner.

  &lt;&lt;image&gt;&gt;

  Intermediates between infraspecific taxa of the same species are far from uncommon (that’s why they’re infraspecific taxa, not species) and adding them to the taxon tree should be avoided. For such determinations the species name should be entered in the **Taxon name** field in the **Determination** form, while the information about the intergradedness between the infraspecies can be entered in the **Extra info.** field
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Administrative fields

The following fields are automatically completed and cannot be edited.

##### Created by

The person who created the database record.

##### Created

The date the record was created.

##### Last edited by

The person who last edited the record.

##### Last edited

The date the record was last edited.<span id="_Toc283306529" class="anchor"><span id="_Toc284178258" class="anchor"></span></span>

## Agent form

The **Agent** form is used to record information about people and organisations who are involved in the collection, determination or curation of specimens. Note that when the **Agent** form is opened from within the **Collection object** form (i.e. when adding a new collector), you may not be able to see the **Agent attachment** icon at the bottom of the form, depending on the size of your screen. If you wish to add (or view) an **Agent** attachment, click the **Collapse** symbol next to the **Agent geographies** heading to collapse that subform.

##### Agent type

The type of agent. **Agents** can be one of the following:

-   Person: an individual botanist, collector, student or data entry person

-   Organisation: an institution or organisation that acts as a collector (e.g. ‘Ballarat Field Naturalists Club’) or that is involved in transactions (e.g. ‘National Herbarium of New South Wales’)

-   Group: more than one individual who act together as, for example, determiners

-   Other: any other type of agent (it is unlikely that we will need to use this category).

##### <span id="_Toc284176969" class="anchor"><span id="_Toc284178259" class="anchor"></span></span>Institution/Last name

The last name (for a ‘Person’ agent), the organisation/institution name (for an ‘Organisation’ agent), or the combination of agent names (for a ‘Group’ agent). See **Formatting agent names** (below) for information on how to enter ‘Group’ agents, foreign names, name variants and names of registered herbaria.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Formatting agent names
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ###### ‘Group’ agents

  While the **Collector** table allows you to add multiple individuals as collectors, some tables in Specify only allow you to enter a single agent for a task that may have been performed by more than one person (e.g. **Determiner**, or **Prepared by**). In order to record all the people involved in the task, they will need to be entered as ‘Group’ agent. Note that, before creating a new ‘Group’ agent, each individual needs to have a ‘Person’ agent record in the **Agent** table.

  To create a new ‘Group’ agent, select ‘Group’ from the **Agent** type pick list, then enter the names of the people in the group in the **Last name** field. Names should be formatted as follows:

  \[last name\], \[initials (separated by full stops)\] \[preposition (where applicable)\]; last name\], \[initials (separated by full stops)\] \[preposition (where applicable)\] (etc)

  &lt;&lt;image&gt;&gt;

  Use the form controls under the **Groups** subform to add the individual agents to the group.

  ###### Names with prepositions 

  If the agent’s last name consists of a preposition and a substantive, as in many European names (e.g. C.G.G.J. van Steenis), then the preposition is in lower case and should be entered in the **Initials** field:

  &lt;&lt;image&gt;&gt;

  If the name has been anglicised the preposition is treated as part of the substantive, and should be entered in the **Last name** field:

  &lt;&lt;image&gt;&gt;

  ###### Arab names

  Arabic surnames prefixed by *al* or *el* (the) are alphabetised under the element following the article; the article is treated like *de* in French names:

  &lt;&lt;image&gt;&gt;

  Names beginning with *Abu*, *Abd* and *Ibn* \[or *Bin/bin*\], elements as integral to the names as *Mc* or *Fitz*, are alphabetised under those elements:

  &lt;&lt;image&gt;&gt;

  The following website is quite informative if you want to read more about Arab names: <https://duncanflfh.wordpress.com/2013/02/11/no-one-is-called-abdul-a-guide-to-arab-names/>.

  ###### Variants of agent names

  It is sometimes difficult to determine the correct format of an agent’s name, especially where variants exist on labels or in the literature. In these cases, it’s worth adding the variant name as a separate agent record, and cross-referencing it to the preferred name. For example, Ilias bin Paie (see example above) is listed in the Harvard Botanists Index – and potentially on some herbarium labels – as ‘Paie, Ilias bin’. Adding an entry for ‘Paie, Ilias bin’, with a note to use the ‘bin Paie, Ilias’ record will direct other database users to the preferred agent entry, ensuring that all specimens collected or identified by him can be retrieved in a single query:

  &lt;&lt;image&gt;&gt;

  ###### Names of registered herbaria

  If the agent is an organisation that is involved in loan or exchange transactions with MEL, prefix the organisation name with the Index Herbariorum acronym, and use two hyphens with a space either side to separate it from the institution name:

  &lt;&lt;image&gt;&gt;

  Prefixing the institution name with the herbarium code makes it much easier to look up an institution in the gift and loan forms. It is important that two hyphens are used as the separator, as that is what the transaction paperwork program uses to identify which part of the name to print on reports and labels.
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##### <span id="_Toc284176971" class="anchor"><span id="_Toc284178261" class="anchor"><span id="_Toc284176970" class="anchor"><span id="_Toc284178260" class="anchor"></span></span></span></span>Title

The agent’s salutation or honorary title (for a ‘Person’ agent). If a title is not in the pick list, see the Digital Collections Advisor.

##### <span id="_Toc284176972" class="anchor"><span id="_Toc284178262" class="anchor"></span></span>First name

The agent’s first name (for a ‘Person’ agent). Entering data in the **First name** field is not as important as entering data into the **Initials** field.

##### Initials

The agent’s first and middle initials. If the first name needs to be spelt out to avoid ambiguity, it should be repeated here (as well as being entered in the **First name** field). For example:

-   Paul G. \[Wilson\]

-   Peter G. \[Wilson\]

-   Stephen \[Johnson\]

-   Sidney \[Johnson\].

&lt;&lt;image&gt;&gt;

If a person’s name includes a preposition that has not been anglicised, e.g. ‘de’, ‘van’, ‘zu’, it should be entered after the initials:

&lt;&lt;image&gt;&gt;

If the preposition has been anglicised (and thus capitalised), it should be included as part of the **Last name**.

##### <span id="_Toc284176973" class="anchor"><span id="_Toc284178263" class="anchor"></span></span>Abbreviation

The Index Herbariorum code for the organisation agent, or for the institution that an agent works for.

##### <span id="_Toc284176974" class="anchor"><span id="_Toc284178264" class="anchor"></span></span>E-mail

The agent’s e-mail address.

##### <span id="_Toc284176975" class="anchor"><span id="_Toc284178265" class="anchor"></span></span>Job title

The agent’s job title (for a ‘Person’ agent).

##### <span id="_Toc284176976" class="anchor"><span id="_Toc284178266" class="anchor"></span></span>CITES no.

The CITES permit number of an organisation agent involved in transactions. Note that the **CITES no.** field is only activated when the **Agent type** is set to ‘Person’. If you need to edit an existing ‘Organisation’ record to add a CITES no., change the **Agent type** to ‘Person’ while you edit the form, then change it back to ‘Organisation’ once you’ve finished.

##### Date type

Different types of date ranges can be entered in the **Agent** record, depending on the type of agent and/or the information available. The following date types can be selected from the drop-down list:

-   **Birth/Death** – the birth and/or death dates of a person agent

-   **Collected** – the period of activity for a collector (either a person or an organisation)

-   **Received specimens** – the period during which an organisation agent received specimens on loan or exchange.

##### Start date

The earliest date corresponding to the date type, i.e. the agent’s date of birth (for a ‘Person’ agent), the earliest date of a period of collecting activity, or the earliest date that an organisation received specimens. The **Start date** can be entered as a full date, a month and year, or a year only.

##### End date

<span id="_Toc284176979" class="anchor"><span id="_Toc284178269" class="anchor"></span></span>The latest date corresponding to the date type, i.e. the agent’s date of death (for a ‘Person’ agent), the latest date of a period of collecting activity, or the latest date that an organisation received specimens. The **End date** can be entered as a full date, a month and year, or a year only.

##### Comments

Any comments about the agent, such as period of collecting activity (for people agents, if the date entered in the **Start date** and **End date** fields is ‘Birth/Death’) or history of the institution (for organisation agents).

##### <span id="_Toc284176980" class="anchor"><span id="_Toc284178270" class="anchor"></span></span>Web link

A link to a website about the agent (whether a ‘Person’ agent or an ‘Organisation’ agent). The web link must include the protocol (i.e. ‘http://’).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### <span id="_Toc283306530" class="anchor"><span id="_Toc284176981" class="anchor"></span></span>Recording incorrect or misinterpreted versions of agent names

  Sometimes collectors’ names have been recorded incorrectly on herbarium labels, or are frequently misinterpreted, for example, Jessie Spencer, who Mueller mostly referred to as Mrs F. Spencer (he mistook her initial for an F, and it can also be hard to tell the difference between Mueller’s capital I, T, J and F). Jessie was also incorrectly referred to as ‘Mrs G.L. Spencer’ in a 19th-century newspaper, and Jim Willis has pencilled those initials on some specimens. In cases such as this, it is useful to add the incorrect version of the name to the **Agent** table, with an indication of which name should be used instead. For example:

  &lt;&lt;image&gt;&gt;

  The correct version of the name should be recorded in the **Initials** field so it shows up in the agent list:

  &lt;&lt;image&gt;&gt;

  Make sure you include enough information to distinguish the name from other collectors with the same name: in the above example, the ‘Qld, 1880s’ is important in case we ever come across a collector whose initials and last name actually are ‘F. Spencer’.

  Please always include an explanation of why the name has been assumed to be incorrect or misinterpreted, and references to the evidence that backs up your interpretation.

  &lt;&lt;image&gt;&gt;

  ***Note:* You should never select one of these entries from the agent list; always use the entry it refers you to, and record the name as it appears on the label in the** Verbatim collector **field:**

  &lt;&lt;image&gt;&gt;

  &lt;&lt;image&gt;&gt;
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Addresses

Multiple addresses can be entered for a single agent. If more than one address is entered, use the **Is current** check box to indicate the primary (or current) address, which will be used on mailing labels.

##### <span id="_Toc284176983" class="anchor"><span id="_Toc284178272" class="anchor"></span></span>Attn:

The person or position to whom correspondence should be forwarded (for ‘Organisation’ agents).

##### Address

The organisation and/or street address of the agent.

##### <span id="_Toc284176984" class="anchor"><span id="_Toc284178273" class="anchor"></span></span>City

The city that the agent resides or works in.

##### <span id="_Toc284176985" class="anchor"><span id="_Toc284178274" class="anchor"></span></span>State

The state or province that the agent resides or works in.

##### <span id="_Toc284176986" class="anchor"><span id="_Toc284178275" class="anchor"></span></span>Post code

The postal code of the city that the agent resides or works in.

##### <span id="_Toc284176987" class="anchor"><span id="_Toc284178276" class="anchor"></span></span>Country

The country that the agent resides in.

##### <span id="_Toc284176989" class="anchor"><span id="_Toc284178278" class="anchor"></span></span>Phone

The agent’s primary telephone number.

##### <span id="_Toc284176991" class="anchor"><span id="_Toc284178280" class="anchor"></span></span>Fax

The agent’s fax number, if known.

##### <span id="_Toc284176982" class="anchor"><span id="_Toc284178271" class="anchor"></span></span>Is current 

The **Is current** field is used to record which of the agent’s addresses is current. An agent can only have one current address.

##### Start date

If an agent has more than one address, the date at which MEL started using a new address should be entered in the **Start date** field. The **Start date** will default to the date that a new address record was added.

##### Exchange

This is a read-only field that is used to indicate whether or not MEL has an exchange agreement with an institution agent. Changes to this field can only be made by a database administrator.

##### <span id="_Toc283306532" class="anchor"><span id="_Toc284176992" class="anchor"></span></span>Loan p’work

The e-mail address of the person to whom loans paperwork should be sent.

##### Exchange p’work

The e-mail address of the person to whom exchange paperwork should be sent.

##### Data format

The institution’s preferred format for exchange data.

### Agent geographies

##### <span id="_Toc284176993" class="anchor"><span id="_Toc284178281" class="anchor"></span></span>Region

The geographical region of interest to the agent, e.g. the region in which the agent collected or conducted research. This field links to the **Geography** tree, so only places listed in the **Geography** tree can be entered.

##### <span id="_Toc284176994" class="anchor"><span id="_Toc284178282" class="anchor"></span></span>Comments

Enter any comments about the agent’s interest in the geographic region (e.g. whether they collected in the region, or if it was a topic of research).

### <span id="_Toc284176995" class="anchor"><span id="_Ref484511581" class="anchor"><span id="_Toc492047905" class="anchor"><span id="_Toc283306533" class="anchor"></span></span></span></span>Attachments

##### <span id="_Toc284176996" class="anchor"><span id="_Toc284178283" class="anchor"></span></span>Agent attachments

Any attachments that relate to the agent, such as images of handwriting samples, letters, or PDFs of articles about the agent.

&lt;&lt;image&gt;&gt;

### <span id="_Toc492047906" class="anchor"><span id="_Toc283306534" class="anchor"><span id="_Toc284178284" class="anchor"></span></span></span>Administrative fields

The following fields are automatically completed and cannot be edited.

##### Created by

The person who created the database record.

##### Created

The date the record was created.

##### Last edited by

The person who last edited the record.

##### Last edited

The date the record was last edited.

## Attachment forms

Specify allows many types of files to be attached to various tables. It’s important that attachments are properly curated so they can be effectively queried and can be made available to external researchers and projects such as the Australasian Virtual Herbarium (AVH), and not just used internally by herbarium staff. The requirements for curating non-image attachments (such as Word documents, PDF files and spreadsheets) are fairly straightforward, but the metadata requirements for curating images are more complex.

**Images should be only attached to specimen records if they augment the specimen data and are of sufficient quality and relevance to be of interest to other data users.** Once the mechanisms are in place for delivering images to the AVH, certain categories of images attached to specimen records will be delivered to the AVH by default.

**Please ensure images have the correct orientation before importing them into MELISR; you cannot alter the orientation once they’ve been imported, and we don’t want to deliver sideways images to the AVH or other services.**

### Attachment file formats

The following file formats can be attached to records in Specify:

-   JPEG

-   GIF

-   PNG

-   TIFF

-   PDF

-   CSV

Do not attach Word or Excel files to records. Note that Specify will not generate a thumbnail image for TIFF files. Avoid creating new TIFF images to attach to MELISR records, but if you are provided with TIFF images by a collector, don’t change them to another format.

### Types of attachments

Attachments can be added to the following forms:

-   **Collection object** – attachments that relate to the collection object, e.g.

    -   images of the specimen in the field (but not general habitat photos)

    -   images of the specimen in the lab (e.g. prior to being curated)

    -   images of the pressed or dried specimen (whether or not it has been mounted or curated)

    -   letters associated with herbarium specimens

    -   illustrations associated with herbarium specimens

-   **Collecting event** ­– attachments that relate to the collecting event more broadly, rather than to the individual specimen (or specimen-to-be), e.g.

    -   general habitat images (as opposed to a photo focussing on the specimen-to-be in the field; if in doubt, add the image as a **Collection object attachment**)

    -   a photo of the collector/s in the field

-   **Locality** – attachments that relate specifically to the collecting locality (and not to the specimen itself), e.g.

    -   a map of the collecting locality

-   **Agent** – attachments that relate to an agent, e.g.

    -   images of handwriting samples

    -   portraits

    -   letters (if a letter is from a herbarium specimen, add it as a **Collection object attachment**)

    -   PDFs of papers about the agent

-   **Conservator event** – attachments that relate to a conservator event, e.g.

    -   images of damage to a preparation

    -   treatment reports

-   **Taxon** – attachments that relate to a taxon name, e.g.

    -   PDFs of publications

-   **Loan** – attachments that relate to a loan, e.g.

    -   preparation lists for loans of unaccessioned material

    -   import permits

-   **Exchange** – attachments that relate to an exchange transaction, e.g.

    -   species lists for consignments of shipping material without preparations

-   **Permits –** attachments that demonstrate permission to collect, e.g.

    -   official collecting permits

    -   copies of correspondence permitting collection on private land.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Collection object attachment or Collecting event attachment?

  An image of the habitat in which the specimen was growing, or of collectors at the collecting site, should be added as a **Collecting event attachment**. An image of the specimen, either before or after it was collected, should be added as a **Collection object attachment**. Sometimes an image of the plant, alga or fungus in the field will show habitat detail as well as the specimen itself. Use your own judgment to decide whether the main subject of the image is the specimen (or specimen-to-be), or the habitat. If in doubt, make the image a **Collection object attachment**.
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Attachment metadata

Two tables are used to record information about attachments. The first is the **Attachment** table, which is used to record some of the technical, content and curatorial metadata. A second table, **Additional metadata**, is used to record additional metadata that mostly relates to image attachments.

Attachment metadata can either be added and edited within Specify, or, for attachments that have already been uploaded into Specify, you can add or edit metadata using the **Attachment metadata workbench** (see p. 106).

### Attachment storage location

When you first install Specify, the attachment storage location will default to your local drive. Before adding any attachments in Specify, the attachment storage location needs to be set; if you don’t change it, your attachments won’t be available to anyone else, and you won’t be able to view attachments added by other users. To set the storage location:

1.  Go to **Preferences** under the **Edit** file menu:

> &lt;&lt;image&gt;&gt;

1.  Under the **Attachments** tab, set the attachment storage location as

    S:\\General\\Specify Attachments:

> &lt;&lt;image&gt;&gt;
>
> <span id="_Ref386641630" class="anchor"><span id="_Toc284176997" class="anchor"><span id="_Toc284178285" class="anchor"></span></span></span>Note that the file path is not case-sensitive on Windows computers.

### <span id="_Ref490554596" class="anchor"><span id="_Ref490554600" class="anchor"><span id="_Toc492047912" class="anchor"></span></span></span>Attachment

##### Original file name

The original file name of the attachment. The **Original file name** will be automatically taken from the file being uploaded.

##### <span id="_Toc284176998" class="anchor"><span id="_Toc284178286" class="anchor"></span></span>Title

The title of the attachment (the **Original file name** without the file path). The title will be automatically filled in from the **Original file name**; the **Title** does not have to be meaningful.

##### <span id="_Toc284176999" class="anchor"><span id="_Toc284178287" class="anchor"></span></span>Subject

The subject of the attachment. There is no need to repeat information that is elsewhere in the record, such as **Catalogue number**, **Taxon name** or **Collector**.

Examples of **Subject** for specimen-related images include:

-   ‘Part of inflorescence’

-   ‘Testa surface’

-   ‘Ascus with imm. spores’

-   ‘Whole plant’

-   ‘Internal view of spadix’

-   ‘Young fruit capsules’

-   ‘Flower’

-   ‘Fruiting body’.

If the attachment is a PDF of a published article, enter its title here. If a non-specimen-image attachment does not have a formal title, enter a brief description of it here. For example:

-   ‘Letter from McHard to Mueller, dated 1885’

-   ‘2014-0008 preparations list’.

##### Image creation date

The date an image attachment was created (creation date is not required for non-image attachments such as PDF or csv files).

##### Copyright holder

The person or organisation who owns copyright in an image. The **Copyright holder** will default to the photographer (in the **Image attributes** table), if left blank. Where the photographer was a member of staff at the time the photograph was taken, the **Copyright holder** should be entered as ‘RBG Victoria’.

##### Copyright date

The date that copyright in the image was asserted.

##### Restrictions on use

Any restrictions on use of the image instructed by the copyright holder or photographer (such as an embargo period). If a **Licence** has been provided and there are no restrictions on use entered, we will assume that we can use the image for any purpose that fits within the **Licence**.

##### Attribution

How the image should be attributed.

### <span id="_Ref490554603" class="anchor"><span id="_Ref490554606" class="anchor"><span id="_Toc492047913" class="anchor"></span></span></span>Additional metadata

The **Additional metadata** table contains additional metadata that is mostly only used for images, however, the **Category** field should be used for non-image attachments if there is a relevant category in the pick list (e.g. ‘Notes’ for a PDF of notes provided by the collector).

##### Photographer

The name of the person who took the photograph. There is currently no link within Specify between the attachment metadata tables and the **Agent** table, so the photographer’s name will need to be entered by hand. We will make our own link between the **Photographer** field and the **Agent** table so we can properly attribute images when used outside of MELISR. For this to work, photographers’ names need to be entered in a standard format, as follows:

\[last name\], \[initials (separated by full stops)\] \[preposition (where applicable)\]

e.g. ‘Ratkowsky, D.A.’, ‘Heul, T. van der’

Make sure that there’s an entry for the photographer in the **Agent** table, and check that their **First name** has been entered there, if known.

##### Image type

The method by which the image was produced. The values in the pick list are:

-   SEM

-   Light microscope image.

More terms can be added to the pick list as needed.

##### Category

The **Category** field is used to indicate the broader subject of the image (more detail must be provided in the **Subject** field). These categories will allow us to determine which attachments are appropriate for different uses (e.g. which are suitable for sending to the AVH, which could be used for VicFlora, which could be used in an online database of collectors). There is some overlap in the categories (e.g. ‘Label’ is part of a ‘Herbarium specimen’); where more than one **Category** option applies, always use the more specific term.

The values currently in the pick list are:

-   Habitat – an image of the general habitat in which the plant, alga or fungus was growing (as opposed to an image of the specimen while still in the field) (used for **Collecting event** **attachments**)

-   Handwriting – a handwriting sample attached to an agent record (used for **Agent attachments**)

-   Herbarium specimen – all or part of a dried or pickled specimen that is (or will become) a herbarium specimen, regardless of whether or not it has been mounted or curated yet (used for **Collection object** **attachments**)

-   Illustration – an illustration associated with a herbarium specimen (used for **Collection object attachments**)

-   Label – detail of one or more labels on a herbarium specimen (used for **Collection object** **attachments**)

-   Letter – a letter attached to a herbarium specimen (if a **Collection object** attachment), or a non-specimen-related letter (if attached to an **Agent** record) (used for **Collection object** **attachments** or **Agent attachments**)

-   Notes – an image of any notes accompanying the specimen, such as lengthy notes with fungi, descriptions by Mueller, or Sonder’s diagnoses (used for **Collection object** **attachments**)

-   Person/s – a photo of a person or persons involved in a collecting event (used for **Collecting event** **attachments**, if relevant, or **Agent attachments**)

-   Specimen in field – all or part of the specimen in the field (i.e. an image of the individual specimen taken in the field, as opposed to a general habitat photo) (used for **Collection object** **attachments**)

-   Specimen – an image of all or part of the specimen taken somewhere other than in the field or once it has been curated, e.g. in the lab prior to being pressed and/or dried; use this category if you are unsure where the image was taken or whether or not it has been preserved yet (used for **Collection object** **attachments**).

##### Magnification

The magnification of images taken under a microscope. Magnification should only be included for images that have a scale bar. You do not need to include the magnification symbol (×). Be careful not to confuse the size of the scale bar with the magnification.

##### Licence

The licence under which an image can be used. The pick list has the following values:

-   CC BY

-   CC BY-SA

-   CC BY-ND

-   CC BY-NC

-   CC BY-NC-SA

-   CC BY-NC-ND

-   Unknown.

If the licence is unknown, please select ‘Unknown’ in the pick list, rather than leaving this field blank.

##### Comments

Any additional remarks about the attachment.

#### Adding attachments

To add an attachment to a record:

1.  Click on the attachment symbol in the relevant form:

> &lt;&lt;image&gt;&gt;

1.  Click on the **Add** symbol at the bottom of the **Attachment** form:

> &lt;&lt;image&gt;&gt;

1.  Navigate to the file that you want to attach to the record (if the file browser window doesn’t open automatically, click the **Browse** button)

2.  Enter as much metadata as you can about the image (see field descriptions above)

3.  Click **Done** to save the **Attachment** record.

## <span id="_Ref387226721" class="anchor"><span id="_Toc492047914" class="anchor"><span id="_Toc419393126" class="anchor"></span></span></span>Attachment metadata workbench

The **Attachment metadata workbench** allows you to easily add and edit metadata for attachments without opening each attachment in Specify. You can download a metadata spreadsheet for a batch of attachments, add missing metadata and/or edit existing metadata, then upload the metadata into MELISR. Note that you cannot use the **Attachment metadata workbench** to add new attachments to MELISR; they must have already been uploaded.

&lt;&lt;image&gt;&gt;

The URL for the **Attachment metadata workbench** is http://melisr.rbg.vic.gov.au/imagemetadata.

### Downloading attachment metadata

To download metadata for a batch of attachments:

1.  Select your Specify user name from the drop-down list

2.  In the **Attachments added since** and **Attachments added before** fields, enter the date span in which the attachments requiring metadata were added to MELISR

-   You can limit your attachment records to those with insufficient metadata to be used for anything other than viewing in MELISR by ticking the **Check for all attachment records with insufficient metadata** box

-   Alternatively, you can limit your records to those missing certain pieces of metadata using the **Filter by attachment records with missing values in** option (selecting multiple fields will include records with no data in one or more of the fields selected)

-   You can include other fields from the specimen record in your metadata file for reference by selecting them in the **Extra fields** box. Hold the **Ctrl** key down to select more than one field. Note that these will all be ignored when the file is uploaded, so you can’t use the **Attachment metadata workbench** to edit data in these fields.

1.  Select the **Output format**. HTML table will provide a preview of the results in your browser.

2.  Click **Get attachment metadata** to download the metadata file.

### Editing attachment metadata

To edit the metadata file:

1.  Open the attachment metadata file from within Excel or another text editor; don’t open the file from the file manager. **If you open the file from the file manager, any special characters (umlauts, accents etc.) will be corrupted in Excel.**

-   If the file doesn’t appear in the file browser, check that it is looking for all files, not just Excel files:

    &lt;&lt;image&gt;&gt;

-   In the **Text Import Wizard**, ensure that ‘Delimited’ is selected, and change the **File origin** to UTF-8 (this will preserve any special characters in the metadata):&lt;&lt;image&gt;&gt;

1.  Add or edit the metadata fields. Refer to the instructions for entering metadata in the **Attachment** (p. 102) and **Additional metadata** (p. 103) tables, and take careful note of the following:

-   You can change an attachment from a **Collection object attachment** to a **Collecting event attachment** (and vice versa) by changing the table name in the **Table** column. Make sure you spell the table name correctly, and use maximal capitals, i.e. ‘Collection Object’, ‘Collecting Event’.

-   Do not edit the **GUID** column as it is used to match the rows in the spreadsheet to records in the database

-   Data in the **CatalogNumber**, **MimeType**, **AttachmentLocation**, **Title**, **Created** and **CreatedBy** columns will be ignored when the file is uploaded, so those columns should not be edited

-   The **Modified** and **ModifiedBy** values will be automatically updated when the metadata is uploaded, so there’s no need to edit those columns

<!-- -->

-   If you delete data from a field for an individual record, the value of that field will be cleared when the metadata file is uploaded.

1.  Save the file once you’ve finished editing the metadata.

### Uploading attachment metadata

To upload the edited metadata into MELISR:

1.  On the **Attachment metadata workbench** page, click on **Upload file with attachment metadata**. This will open the **Upload attachment metadata** page.

2.  Select your Specify user name from the drop-down list

3.  Click on **Choose file** and navigate to the metadata file you wish to upload

4.  Click **Submit** to load the file

-   A record set will be created for the records in the upload file (if you’re already logged in to Specify when you upload the file, you’ll need to log out and back in before you can see the record set).

## Attachment tools

The **Attachment tools** in Specify allow you to view all attachments in the workspace, open associated specimen records in form view, and import either single attachments or multiple attachments in a single action.

Open the **Attachment tools** by clicking the **Attachment** button on the task bar.

Four functions appear on the side bar:

-   Show all attachments

-   Show all images

-   Import attachments

-   Import attachment mapping file.

### <span id="attach_browser" class="anchor"><span id="_Toc492047919" class="anchor"></span></span>Show all attachments/Show all images

Click **Show all attachments** (or **Show all images**) in the side bar to browse thumbnail representations of all attachments (or just the image attachments) relevant to the current collection.

*Note:* Thumbnails are created for JPEG and PNG files and most PDFs. Other file types are represented by a default thumbnail based on their file type.

#### Image viewing controls

The following controls are available in the **Attachments** results view:

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Symbol**              **Location**          > **Action**
----------------------- --------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  &lt;&lt;image&gt;&gt;   next to thumbnail     > Displays information about the associated record, and allows the record to be opened in form view

  &lt;&lt;image&gt;&gt;   next to thumbnail     > Opens the associated record in form view. Also indicates the table to which the attachment is linked.

  &lt;&lt;image&gt;&gt;   bottom of workspace   > Displays some of the associated record information and displays the latitude and longitude from the associated **Locality** record on a map

  &lt;&lt;image&gt;&gt;   bottom of workspace   > Displays attachment metadata from the original file when available.
                                                >
                                                > *Note:* Metadata captured at the time a digital photo is taken may include the date, and latitude/longitude. The metadata information may be stripped from the file when the image is loaded into an outside program such as a web-based image storage facility. Some file types such as PNG, BMP and GIF contain little or no metadata.

  &lt;&lt;image&gt;&gt;   bottom of workspace   > Opens the Specify Help page for the **Attachment tools**
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Viewing attachments

To display a larger version of the image within Specify:

-   Double-click an individual image thumbnail to display it in a new tab in the workspace

To open an image in an image viewer :

1.  Double-click an individual image thumbnail to display it in a new tab in the workspace

2.  Right-click on the image and click **Open in external viewer**. The image will either open in your default image-viewing program, or you will have the option of selecting an external viewer from the file manager.

To open a non-image file in its native program:

-   Double-click a non-image file to open it in its native program.

#### Exporting attachments

<span id="import_attach" class="anchor"></span>To export an attachment:

1.  Right-click on the thumbnail and click **Export attachment**

2.  Navigate to the folder you want to export the attachment to, and click **Save**.

### Import attachments

The **Import attachments** tool allows multiple attachments to be associated to records by matching attachment names within a directory to a unique field within an existing record. For example, attachments can be linked to records within the **Collection object** table by giving the attachment files names that correspond to the **Catalogue number** or the **MEL number**. The **Import attachment** tool also gives you the option of linking files to records by ‘Field number’ (**Collecting number**), but these are not unique within MELISR, so cannot be used for this purpose. You can also link attachments to **Taxon** records by using the taxon **Full name**.

  > **Table **          > **Unique field value**   > **File name example**
--------------------- -------------------------- ----------------------------------------
  > Collection object   > Catalogue number         > 2374514A.jpg
  > Collection object   > MEL number               > 5142.jpg
  > Taxon               > Full name                > Crowea exalata subsp. magnifolia.png

Multiple attachments can be associated to the same record by adding a number to the end of the **Catalogue number** in the file name. Note that you can’t add multiple attachments to the same record if you are using **MEL number** as the unique field value.

  **Unique field value**   **Example of file names for multiple attachments**
------------------------ ----------------------------------------------------
  > Catalogue number       2374514A1.jpg, 2374514A2.jpg, 2374514A3.jpg

#### Importing attachments

To import attachments:

1.  Click **Import attachments** in the side bar

2.  Select the table that you want to link attachments to, and the unique field value that you’ve used for the file name, in the **Choose attachment destination** window:

    &lt;&lt;image&gt;&gt;

3.  Click **OK**

4.  In the **Choose attachment upload method** window, choose whether you want to upload an entire directory of attachment files, or if you want to select individual files:

    &lt;&lt;image&gt;&gt;

    Note that you can select more than one file if you choose ‘Individual files’.

5.  Navigate to the files or folder that you want to upload and click **Open**.

    Specify will display a message once the upload is complete, and details of any file upload issues will be reported in a browser window.

### Import attachment mapping file 

The **Import attachment mapping file** tool allows multiple files to be attached to **Collection object** records in Specify by associating the files with the **Catalogue number** or **MEL number**, or to **Taxon** records by associating the files with the taxon **Full name.** Unlike the **Import attachment** option described above, the file names don’t have to be meaningful, thus this method of importing of multiple attachments is the preferred option when the attachment files have not been pre-named with the **Catalogue number** or **MEL number**. The **Import attachment mapping file** tool also gives you the option of linking files to records by ‘Field number’ (**Collecting number**), but these are not unique within MELISR, so cannot be used for this purpose.

An image mapping file is used to create the association between the attachment file and the unique field value. Note that you can only map to one field in each mapping file (i.e. either **Catalogue number**, **MEL number** or taxon **Full name**), and not to a combination of fields. The file must first be created in a spreadsheet program, then saved as either a tab-delimited or CSV file.

The mapping file must contain two columns: the first column records the unique field value within a record (i.e. **Catalogue number** or **MEL number**), and the second column includes the name of the attachment file:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

The unique field value and file names must match the respective field values and file names exactly, and the mapping file must be located in the same directory as the attachment files. More than one attachment can be associated with the same unique identifier, and the same attachment can be added to more than one record.

#### Importing attachments via a mapping file

To import an attachment mapping file:

1.  Click **Import attachment mapping file** in the side bar

2.  Select the table that you want to link attachments to, and the unique field value that you’ve used for the file name, in the **Choose attachment destination** window:

    &lt;&lt;image&gt;&gt;

3.  Click **OK**

4.  Navigate to the attachment mapping file in the file manager and click **Open** (remember that the attachment files must be in the same directory as the mapping file). Specify will display a message once the upload is complete, and details of any file upload issues will be reported in a browser window.

# Transactions

Information about herbarium transactions is recorded in the **Interactions** module in Specify. Two separate collections are used to record details of MEL transactions: outgoing loans, donations and exchange are recorded in the *National Herbarium of Victoria* collection, and incoming loans are recorded in the *Non-MEL loans* collection.

## <span id="_Toc419393127" class="anchor"><span id="_Toc492047923" class="anchor"></span></span>Loans

In MELISR, loans of MEL specimens to other institutions are recorded in the **Loan** table. The Loan table has two views: **Loan** and **Loan w/o preps**. The **Loan w/o preps** table allows you to enter data about the loan before specifying which specimens will be part of the loan. See the **Databasing loans** (p. 120) section for more information on how to use the two loan views.

### <span id="_Toc419393128" class="anchor"><span id="_Toc492047924" class="anchor"></span></span>Loan form

#### Loan

##### Loan number

The MEL loan number comprises two parts, separated by a forward slash:

-   Year – the year the loan was prepared

-   Number – a sequential, four-digit number. The sequence restarts at 0001 each year.

Old loan numbers have been converted to this format based on the year they were sent out (e.g. MEL loan 210 = 1974/0210).

This field fills automatically when the loan record is saved; however, the loan number needs to be entered manually for the first loan in each calendar year and for transferred loans.

Note that the abbreviation for the recipient institution (e.g. CANB) appears after the loan number but is not part of the loan number. The abbreviation is taken from the institution in the **Sent to** field when the record is saved.

##### Loan status

The current status of the loan. The following values can be selected from the pick list:

-   Awaiting acknowledgement – loan has been sent, but the yellow acknowledgement form has not been received at MEL

-   Complete – all loan preparations have been returned to MEL (or transferred to another institution)

-   Current – all or some preparations are still on loan

-   New – the loan is being prepared

-   Not serviced – the loan request was received but not serviced

-   Written off – the loan has been closed because the specimens have been lost or destroyed.

##### Quantity on loan

The number of preparations that are on loan. This field fills automatically when loan preparations are added or returned.

##### Date requested

The date the recipient institution requested the loan (i.e. date of formal loan request).

##### Current due date

The date by which the loan is due to be returned to MEL. For loans where an extension has been granted, the **Current due date** should be updated.

##### Extension granted

A check box indicating if an extension has been granted. The new due date should be recorded in **Current due date**. Details of who granted the extension and the date are recorded in the **Description** field, and should be prefixed by a double pipe (||).

##### Original due date

The date by which the loan was originally due to be returned to MEL. For loans where no extension has been granted, the **Original due date** will be the same as the **Current due date**.

##### Description

A short summary of the contents of loan. For example:

-   *‘Utricularia* specimens set aside during visit to MEL on 13 Sep 2010’

-   ‘Selected Victorian specimens of *Epacris impressa’*.

This description appears on the loan paperwork. Subsequent comments should be prefixed by a double pipe ( ‘||’), for example:

-   ‘Selected Victorian specimens of *Epacris impressa.* || Extension granted by J.Smith, 4/4/2011.’

##### Project

This field is used to indicate if a loan was requested for a particular project. ‘Flora of Australia Project’ is currently the only project in the pick list.

##### Destructive sampling permitted

A check box to indicate if destructive sampling has been approved (either at the time the loan was prepared, or subsequently). Details of destructive sampling permission should be included in **Conditions**.

##### Conditions

Any conditions other than the standard MEL loan conditions, such as details of permission for destructive sampling to be undertaken.

##### Acknowledged

The date of receipt of the loan at the receiving institution (as recorded on the yellow acknowledgement slip).

##### Received comments

Comments noted by the receiving institution on the yellow acknowledgement slip (e.g. damage to specimen(s), discrepancies between specimens sent and loan list).

##### Loan notice

Details of the most recent notice sent to the receiving institution regarding the loan. Details of previous notices are recorded in the **Description** field, prefixed by a double pipe (‘||’). The following values can be selected from the pick list:

-   Acknowledgement request

-   Extension

-   Overdue

-   Recall

-   Reminder.

##### Notice sent

The date on which the most recent notice was sent to the receiving institution.

##### Loan closed

The date on which all loaned specimens are processed as returned. For full loan transfers, this is the date on which the loan is acknowledged as received by the institution to which it was transferred.

##### Loan transfer no. 

For transferred loans (full or partial), the loan number to which the loan has been transferred. For loan transfers, the year and number components stay the same, but the institution code changes to that of the institution to which the loan has been transferred. For example, if loan 1974/0210 CANB is transferred to AD, the transferred loan number is 1974/0210 AD.

#### Loan agents

##### Name

The botanist(s) and/or student(s) on behalf of whom the loan was requested. A loan may have multiple loan agents (e.g. student and supervisor(s)).

##### Role

The role of the agent in the loan. The following values can be selected from the pick list:

-   Botanist

-   Other

-   Student

-   Supervisor.

#### Shipments

##### Sent to

The institution to which the loan was sent. This corresponds to **Last name** in the **Agent** table and is formatted as the herbarium code followed by ‘ -- ‘ then the title of the institution (e.g. CANB -- Australian National Herbarium). If the institution is in the **Agent** table, but is not formatted as above, please edit the **Agent** record first.

##### Shipment number

An auto-generated identifier for the shipment.

##### Date sent

The date the loan was prepared for dispatch. This date prints on the loan paperwork.

##### Prepared by

The Curation Officer(s) who prepared the loan. This prints on the loan paperwork. If the consignment was prepared by more than one Curation Officer, they should be entered as a ‘Group’ agent (see ‘**Group’ agents**, p. 92).

##### Method

The method by which the loan was shipped. The pick list values relevant to loans are:

-   Air Mail – Customs Insured (loans to overseas institutions)

-   Collected from MEL

-   Courier

-   Express Post

-   Hand delivered

-   Registered Post (loans to Australian institutions)

-   Sea Mail – Customs Insured (very large or heavy loans to overseas institutions)

-   Transfer.

##### Reference no(s) 

Tracking numbers for each parcel in the shipment (from the Registered Post or Customs Insured label).

##### Number of parcels

The number of parcels in the shipment.

##### Weight

The total weight of the parcels in the shipment, in kilograms (e.g. 450 g = 0.45).

##### Postage

The total postage cost for the consignment, as calculated using the [Australia Post postage calculator](http://auspost.com.au/apps/postage-calculator.html).

##### Comments

Any comments relevant to the shipment, for example:

-   ‘sent with exchange MEL ref. 1987’.

#### Loan preparations

The **Loan** preparations subform is used to record the details of the preparations in the loan. Only loans sent after 1 January 1996 are linked to loan preparations. Specimens sent on loan prior to 1996 were not databased.

##### Catalogue no.

The catalogue number of the specimen.

##### Preparation type

The preparation type of the specimen that is being sent on loan. Preparations that can be sent on loan are:

-   Sheet

-   Packet

-   Spirit collection

-   Microscope slide

-   Fungal culture

-   Carpological

-   Display set.

##### Is resolved

This field indicates whether the loan of an individual preparation has been resolved. ‘Yes’ indicates that the preparation has been returned to MEL (or otherwise accounted for). ‘No’ indicates that the preparation is on loan.

##### Quantity

The number of preparations relating to a single collection object that have been sent on loan. For example, if there are three microscope slides for a given specimen, and all are sent on loan, the quantity will be ‘3’.

##### Outgoing comments

Comments specific to the preparation at the time the loan is sent (e.g. permission for destructive sampling; specimen not scanned when loan sent).

##### Borrower’s comments

Specific comments noted by the receiving institution (e.g. that the specimen was damaged on receipt of the loan).

##### Incoming comments

Comments specific to the preparation when it is returned to MEL (e.g. damage to specimen; notes about updates required when the specimen is returned).

##### Status

The status of a preparation that is resolved, but not returned. The following values are available in the pick list:

-   Destroyed

-   Lost

-   Transferred

-   Written off.

##### Loan return preparations

The preparation type and quantity returned.

### <span id="_Toc419393129" class="anchor"><span id="_Toc492047925" class="anchor"></span></span>Loan return preparations

The **Loan return preparations** table is used to record details relating to the return of individual specimens from loan.

##### Processed by (agent) 

The Curation Officer who processed the loan return.

##### Date returned

The date on which the preparation is processed as returned.

##### Quantity returned

The number of preparations returned from loan. When all components of a given preparation are returned, the quantity returned will equal the quantity sent. In cases where preparations are lost, destroyed or written off, the quantity returned will not be equal to the quantity sent.

##### Quantity resolved

The number of preparations resolved. When all components of a given preparation are returned, the quantity resolved will equal both the quantity returned and quantity sent. In cases where preparations are lost, destroyed or written off, the quantity resolved will not be equal to the quantity returned.

*Note:* all preparations for a given loan must be resolved before a loan can be closed.

#### Loan return

##### Returned comments

A summary of the material returned, including the number of specimens, date returned and comments. For example:

-   ‘5 returned, 3/3/2010. Quarantined material VM10002535.’.

This information must be entered for all pre-1996 loans. It is not required for post-1996 loans; details of previous partial returns can be deleted if all information correlates with the loan information summary in the loan returner.

##### Quarantine

A check box to indicate if the loan was quarantined when it was returned to MEL. The Quarantine Entry Number is entered in **Returned comments**.

#### Administrative fields

The following fields are automatically completed and cannot be edited.

##### Created by

The person who created the database record.

##### Created

The date the record was created.

##### Last edited by

The person who last edited the record.

##### Last edited

The date the record was last edited.

### <span id="_Toc419393130" class="anchor"><span id="_Ref484511852" class="anchor"><span id="_Toc492047926" class="anchor"></span></span></span>Databasing loans

#### Entering a new MEL loan

New loans are entered by the Team Leader Collections Curation once approved by the Manager Collections and Executive Director Science.

To enter a new **Loan** record:

1.  Open the **Interactions** module

2.  Click **Loan w/o preps** in the side bar

3.  Enter details in the following fields:

-   **Loan status** – i.e. ‘New’

-   **Date requested**

-   **Description**

-   **Destructive sampling permitted**

-   **Conditions** – e.g. details of destructive sampling permitted; quarantine message for all loans to overseas institutions

-   **Loan agent(s)** **Name** and **Role** – check that a first name is recorded for each agent involved in a loan

-   **Sent to** – check and/or add or all agent details, including Index Herbariorum code, title, address and CITES or Department of the Environment registration code

-   **Prepared by**.

1.  Save the loan record. The **Loan number** will be automatically completed when the record is saved.

#### Adding preparations to a loan 

Preparations are added to a loan by a Curation Officer. Note that it’s not possible to add a preparation to a loan while databasing a specimen.

To add preparations to an existing **Loan** record:

1.  Create a record set using one of the following methods:

-   Open the **Record set creator** and scan barcodes into the **MEL barcodes** text box. Select **Create record set** and name the record set with the loan number (e.g. 2011/0011 NSW). Note that you’ll need to exit and log back into MELISR to access the record set.

-   Open the **Record set creator** and scan barcodes into the **MEL barcodes** text box. Select **Create barcode string**. Copy and paste the barcode string into the **Barcode** field in the **Collection object** table in the **Query builder**. Select ‘In’ as the **Operator** and run the query. Save the results as a record set by clicking on the **Record set** symbol in the results bar. Name the record set with the loan number – note that ‘/’ must be replaced with ‘-‘ (e.g. 2011-0011 NSW), because record set names can’t include a forward slash.

-   Scan barcodes directly into the **Barcode** field in the **Collection object** table in the **Query builder**. Use a comma after each barcode. Select ‘In’ as the **Operator** and run the query. Save the results as a record set by clicking on the **Record set** symbol in the results bar. Name the record set with the loan number – note that ‘/’ must be replaced with ‘-‘ (e.g. 2011-0011 NSW), because record set names can’t include a forward slash.

-   For spirit or microscope slide preparations, create a record set by querying on the spirit/slide number in the **Preparation** table.

> *Note:* more than one record set can be added to a loan record.

1.  In MELISR, find the loan by searching for the loan number in either the **Simple search** (e.g. ‘2011/0001\*’) or the **Loan number** field (in the **Loan** table) in the **Query builder**

2.  Open the **Loan** form and click **Edit**

3.  Click the **Add** symbol in the **Loan preparations** form

4.  Select **Record sets and information requests** when prompted to choose the source of the preparations

5.  Select the relevant record set from the list and click **OK**

6.  In the **Create loan from preparations** window, click **Select all**, scan through the list and deselect any preparations that are not part of the loan (e.g. microscope slides). Note that duplicate preparations don’t need to be deselected at this point (see step 10).

7.  Click **OK**

8.  Save the **Loan** record

9.  Open the [Herbarium transaction paperwork](http://melisr.rbg.vic.gov.au/transactions) and, in the **Loans** section, select the loan from the drop-down list and click **Delete ‘duplicate’ loan preparations**.

#### Deleting preparations from a loan 

The Team Leader Collections Curation and Curation Officers can delete preparations from a loan. A loan preparation should only be deleted if it was erroneously added (e.g. if the wrong MEL number was entered), and only before the loan is dispatched. See the Team Leader Collections Curation if a preparation needs to deleted after the loan has been sent.

#### Adding shipment details to a loan

Shipment details are added to a loan by a Curation Officer once the specimens have been checked, scanned and packed.

1.  Add details to the following fields:

-   **Date sent**

<!-- -->

-   **Method** – the postal category used to send the shipment

-   **Reference no(s)** – the tracking reference number(s) for parcels (e.g. Registered Post, Customs Insured). Scan labels directly into this field, using a comma to separate entries. Ensure that the shipment method matches the label type.

-   **Number of parcels**

-   **Weight** – total weight of all parcels in the consignment

-   **Postage** – total cost of postage (calculate the postage using the online [Australia Post calculator](https://auspost.com.au/parcels-mail/calculate-postage-delivery-times/#/))

-   **Comments** – e.g. notable damage to a specimen.

1.  Change the **Loan status** from ‘New’ to ‘Awaiting acknowledgement’

2.  Save the **Loan** record.

#### Printing loan paperwork

1.  Go to the [Herbarium transaction paperwork](http://melisr.rbg.vic.gov.au/transactions) page

2.  Select the relevant loan from the list. The list is sorted in descending order by loan number; greyed-out numbers are loans without preparations.

3.  Print paperwork as follows:

  ---------------------------------------------------------------------------------------------------------------------
  **White copy: send with loan**                       **Yellow copy: send with loan**   **Pink copy: retain at MEL**
  ---------------------------------------------------- --------------------------------- ------------------------------
  -   Loan paperwork                                   -   Loan paperwork                -   Loan paperwork

  -   List of preparations                                                               -   List of preparations

  -   Loan conditions (on reverse of loan paperwork)                                     
      ​                                                                                     
      ​                                                                                     
  ---------------------------------------------------------------------------------------------------------------------

4.  Print the required number of **Parcel labels** and an **Envelope**.

#### Returning a databased MEL loan 

1.  Open the [Loan returner](http://melisr.rbg.vic.gov.au/loanreturn)

2.  Select the relevant loan from the drop-down list

3.  Scan the returned specimens into the loan returner one by one (or scan into a Word or Excel document and copy and paste list of MEL numbers with each on a separate line)

4.  Select **Update batch**

5.  If necessary, adjust the **Quantity returned** (e.g. if multiple spirit or microscope slide preparations were sent, but not all have been returned)

6.  Select the **Curation Officer**

7.  Enter the **Date returned**

8.  If necessary, enter the quarantine reference number in **Quarantine message**

9.  Click **Return batch**

10.  Open the relevant loan in MELISR and check that the **Loan preparation** table, **Quantity on loan**, **Loan status** and **Loan closed** are correct

11.  Update **Returned comments** if details of previous returns have been entered

12.  **Save** the loan form.

#### Returning an undatabased MEL loan (pre-1996 loans) 

1.  Open the **Loan form** for the relevant loan and select **Edit**

2.  Enter the number of specimens returned and the date in **Returned comments**, along with any relevant comments (quarantine reference number, discrepancies in number of specimens, etc). For example:

-   ‘5 returned, 3/3/2010.’

    Use a full stop between each entry.

1.  Update the **Quantity on loan** (in the top right-hand corner of the form). The quantity needs to be calculated manually.

2.  For complete returns:

-   change the **Loan status** to ‘Complete’

-   enter the date in **Loan closed**

-   flag the **Closed** check-box (in the bottom right-hand corner of the form)

1.  **Save** the loan form.

#### Transferring a databased MEL loan

Loan transfers are entered by the Team Leader Collections Curation. Loan transfers must be formally requested by the institution to which they are to be transferred.

1.  Create a record set and barcode string for the loan preparations to be transferred

2.  Open the **Loan returner** (<http://melisr.rbg.vic.gov.au/loanreturn>)

3.  Select the relevant loan from the list and enter the barcode string

4.  Select the **Curation Officer**

5.  Enter the **Date returned**

6.  Select the **Transferred** checkbox

7.  Click **Return batch**

8.  In MELISR, open the **Loan form** for the relevant loan and select **Edit**

9.  Enter the **Transfer loan no** (the existing MEL loan number, but with the institution code for the institution to which the loan is being transferred)

10.  Check that the relevant loan preparations are flagged as returned, resolved and transferred in the **Loan preparations** table

11.  Check that the **Loan status** and **Quantity on loan** are correct

12.  **Save** the loan record

13.  Create a new **Loan record**, add the relevant record set and add loan details:

-   **Loan status** – i.e. ‘Awaiting acknowledgement’

-   **Date requested**

-   **Description**

-   **Destructive sampling permitted**

-   **Conditions** – e.g. if destructive sampling permitted

-   **Loan agent(s)** and **Role(s)**

-   **Institution** – enter or check all details, including title, Index Herbariorum code, address and CITES or Department of the Environment registration code

-   **Date sent** – i.e. date of transfer

-   **Prepared by**

-   **Method** – i.e. ‘Transfer’

-   **Comments** – i.e. ‘\[Quantity\] transferred from \[original institution\].’

1.  **Save** the loan record.

#### Transferring an undatabased MEL loan (pre-1996 loans) 

Loan transfers are entered by the Team Leader Collections Curation. Loan transfers must be formally requested by the institution to which they are to be transferred.

1.  Open the loan form for the loan to be transferred and select **Edit**

2.  Update the **Loan status** (if necessary) and **Quantity on loan**

3.  Enter the **Transfer loan no** (the existing MEL loan number, but with the institution code for the institution to which the loan is being transferred)

4.  Update **Returned comments**: ‘\[Quantity\] transferred, \[date\].’

5.  Enter **Loan closed** (the date on which the loan is acknowledged as received by the institution to which it was transferred)

<!-- -->

1.  **Save** the loan record

2.  Create a new **Loan record** and add loan details:

-   **Loan status** – i.e. ‘Awaiting acknowledgement’

-   **Date requested**

-   **Description**

-   **Destructive sampling permitted**

-   **Conditions** – e.g. if destructive sampling permitted

-   **Loan agent(s)** and **Role(s)**

-   **Institution** – enter or check all details, including title, Index Herbariorum code, address and CITES or Department of the Environment registration code

-   **Date sent** – i.e. date of transfer

-   **Prepared by**

-   **Method** – i.e. ‘Transfer’

-   **Comments** – i.e. ‘\[Quantity\] transferred from \[original institution\].’

1.  **Save** the loan record.

## <span id="_Toc419393131" class="anchor"><span id="_Toc492047927" class="anchor"></span></span>Outgoing exchange and donations

Outgoing consignments of exchange, donations and shipping material are recorded in the **Gift** table.

### <span id="_Toc419393132" class="anchor"><span id="_Toc492047928" class="anchor"></span></span>Gift form

#### Gift

##### Gift number

The MEL reference number for a consignment of outgoing exchange, donation or shipping material. The gift number is generated automatically when a record is saved. The same sequence is used for both incoming and outgoing consignments (i.e. gift numbers and exchange numbers are allocated sequentially).

##### Category

The category of material being sent. The following options are in the pick list:

-   Donation – duplicate specimens sent to an institution with which MEL does not have a formal exchange agreement

-   Exchange – duplicate specimens sent to an institution with which MEL has a formal exchange agreement

-   Shipping material – material other than duplicate specimens (e.g. samples for destructive analysis).

##### Quantity

The number of specimens (or samples) in the consignment. This field fills automatically once preparations are added.

##### File name

The file name for electronic data for the consignment.

##### Description

A summary of the contents of the consignment. For example:

-   ‘Miscellaneous vascular plants and cryptogams (incl. two types)’.

This description appears on the MEL paperwork. Subsequent comments should be prefixed by a double pipe (‘||’). For example:

-   ‘Miscellaneous vascular plants and cryptogams (incl. two types). || Request for acknowledgement of receipt sent 18 May 2011.’

##### Acknowledged

The date on which the recipient institution processed the consignment (as recorded on the yellow acknowledgement form).

##### Received comments

Any comments noted by the recipient institution on the yellow acknowledgement form (e.g. damage to specimen(s); discrepancies between specimens sent and specimen list).

#### Gift agents

##### Name

Usually the person to whom the electronic data was sent (for exchange or donations), or the botanist(s) and/or student(s) who requested the material (e.g. for shipping material). A consignment can have more than one agent.

##### Role

The role of the agent in the exchange, donation or shipping material transaction. The following values can be selected from the pick list:

-   Botanist

-   Other

-   Recipient of exchange file

-   Student

-   Supervisor.

#### Shipments

##### Sent to

The institution to which the consignment was sent. This corresponds to **Last name** in the **Agent** table and is formatted as the herbarium code followed by ‘ -- ‘ then the title of the institution (e.g. CANB -- Australian National Herbarium). If the institution is in the **Agent** table, but is not formatted as above, please edit the **Agent** record first.

##### Shipment number

The auto-generated identifier for the shipment.

##### Date sent

The date on which the consignment was dispatched. This date appears on the MEL paperwork.

##### Prepared by

The Curation Officer(s) who prepared the consignment. If the consignment was prepared by more than one Curation Officer, they should be entered as a ‘Group’ agent (see ‘**Group’ agents**, p. 92).

##### Method

The method by which the shipment was sent. The following options are available in the pick list:

-   Air Mail – Customs insured (no longer used)

-   Air Mail – Customs non-insured

-   Collected from MEL

-   Courier

-   Express Post

-   Express Post International

-   Hand delivered

-   Pack & Track International

-   Registered Post (within Australia only)

-   Sea Mail – Customs insured (no longer used)

-   Sea Mail – Customs non-insured (very large or heavy consignments).

##### Reference no(s) 

The tracking number for each parcel in the shipment. Tracking numbers should be scanned from the consignment note or label (e.g. Registered Post label, Pack & Track International consignment note), rather than entered manually. Multiple numbers should be separated by commas.

##### Number of parcels

The number of parcels in the shipment.

##### Weight

The total weight of the parcels in the shipment, in kilograms (e.g. 450 g = 0.45).

##### Postage

The total postage cost for the consignment, as calculated using the [Australia Post postage calculator](http://auspost.com.au/apps/postage-calculator.html).

##### Comments

Any comments relevant to the shipment, for example:

-   ‘Sent with MEL loan 2011/0006’.

#### Gift preparations

##### Catalogue no. 

The catalogue number of the gift preparation.

##### Quantity

The number of duplicate preparations for a given catalogue number that are included in the consignment. For exchange, donations and shipping material, the quantity will usually be ‘1’.

##### Preparation type

The following preparation types can be sent as exchange/donation/shipping material:

-   Duplicate

-   Seed duplicate

-   Silica gel sample

-   Shipping material.

##### Quantity

The total number of duplicate preparations for a given catalogue number (e.g. if a specimen has duplicates assigned to BRI, CANB and NSW, the quantity is ‘3’).

##### Description

A description specific to the individual duplicate or shipping material preparation (e.g. for shipping material, the description might denote the type of material (leaf material, anthers, etc.)).

##### Migration comments

This field is used to record any problems noted when data was imported into Specify from the Loans and Exchange database in April 2011. These comments generally relate to a discrepancy between the number of specimens noted in the Loans and Exchange database, and the number of records in the electronic file for the consignment.

#### Administrative fields

The following fields are automatically completed and cannot be edited.

##### Created by

The person who created the database record.

##### Created

The date the record was created.

##### Last edited by

The person who last edited the record.

##### Last edited

The date the record was last edited.

### <span id="_Toc419393133" class="anchor"><span id="_Toc492047929" class="anchor"></span></span>Databasing outgoing donations and exchange

#### How to process outgoing exchange, donation or shipping material

1.  Create a record set for the preparations in the consignment using one of the following methods:

    For large consignments (more than ten specimens):

-   Open the **Record set creator** (http://melisr.rbg.vic.gov.au/recordset) and scan barcodes into the **MEL barcodes** text box and select **Create record set**. You’ll need to exit and log back into MELISR to access the record set.

    OR

-   Open the **Record set creator** and scan barcodes into the **MEL barcodes** text box. Select **Create barcode string**. Copy and paste the barcode string into the **Barcode** field (in the **Collection object** table) in the **Query builder**. Select ‘In’ as the **Operator** and run the query. Save the results as a record set by clicking on the **Record set** symbol in the results bar.

> OR

For small consignments (fewer than ten specimens):

-   Open the **Query** **builder** and select the **Barcode** field from the **Collection object** table. Select ‘In’ as the **Operator** and scan the barcodes into the search box (use a comma between each barcode). Run the query and save the results as a record set by clicking on the **Record set** symbol in the results bar.

    *Note:* multiple record sets can be added to a gift record.

1.  In MELISR, click **Interactions** in the task bar

2.  Click **Gift** in the side bar

3.  Select **Record sets** when prompted to choose source of preparations

4.  Select the relevant record set

5.  Select the **Preparation type** and **Quantity** for each preparation by either:

-   Manually flagging each preparation

    OR

-   **Select all**, then **Save** the Gift record. Open the herbarium transactions page (http://melisr.rbg.vic.gov.au/transactions), select the relevant exchange consignment from the list and click on **Clever button thing**. This will remove any silica gel sample preparations as well as non-giftable preparations (sheet, packet, spirit, etc.). You will still have to check the **Gift** record and manually remove any other preparations that are not included in the consignment (e.g. Seed duplicates).

    *Note:* only ‘Duplicate’, ‘Seed duplicate’, ‘Silica gel sample’ and ‘Shipping material’ preparations should be added to Gift records.

1.  Enter details in the following fields:

-   **Category**

-   **Description**

-   **Gift agent(s) Name(s)** and **Role(s)**

-   **Sent to**

-   **Date sent**

-   **Prepared by**

-   **Method**

-   **Reference no(s)**

-   **Number of parcels**

-   **Weight**

-   **Postage**

-   **Comments** – e.g. notable damage to a specimen

1.  **Save** the form. Select **Exit** when prompted to print a Gift invoice

2.  Open the **Exchange metadata** page (http://melisr.rbg.vic.gov.au/exchangedata) and select the relevant exchange consignment from the **Exchange** drop-down list

3.  If the consignment contains records that have been created or edited on the day they’re being sent, click on the **Update BioCASe** button

4.  Select the **Output format** (refer to the agent record to check which file type to send) and press **Submit**

5.  Name the file using the gift number (e.g. MEL exchange 1602 PAL) and save it to the relevant folder in S:\\COLLECT\\Loans & exchange\\Exchange\\Outgoing exchange

6.  Add the **File name** to the **Gift** record in MELISR

7.  Open the herbarium transactions page (http://melisr.rbg.vic.gov.au/transactions) and select the relevant exchange consignment from the drop-down list

8.  Select ‘Exchange paperwork’ and print three copies – one each on white, yellow and pink paper. The white and yellow copies are sent with the consignment (box 1) and the pink copy is attached to the paperwork kept at MEL.

9.  Save a copy of the exchange paperwork as a PDF file to e-mail to the receiving institution

10.  Select ‘List of preparations’ and print two copies (one to send with the consignment and one to retain at MEL). Printed double-sided if necessary.

11.  Select ‘Parcel labels’ and print the required number

12.  Using the HerbMEL account, e-mail the exchange paperwork and data to the receiving institution (refer to the agent record for contact details). Record the file name in the subject line (e.g. MEL exchange 1602).

#### How to enter outgoing shipping material using a dummy record

MEL occasionally ships specimens, samples or other materials that are not linked to MEL specimens (e.g. recently collected non-MEL specimens, unvouchered pollen samples). In such cases, a dummy record needs to be used in order to create a **Gift** record:

1.  Open the dummy record MEL 999999A in MELISR and edit the preparation type and quantity in accordance with the type and quantity of material to be sent

2.  Open the **Interactions** module and click **Gift** in the side bar

3.  Select **Enter Catalogue Numbers** when prompted to choose source of preparations

4.  Enter 9999999A

5.  Select the **Preparation type** and **Quantity** and follow steps 7 and 14–19 as above

6.  Return to the **Gift** record, delete the dummy preparation and save the record.

#### Deleting preparations from a gift record

The Team Leader Collections Curation and Curation Officers can delete preparations from a gift. A preparation should only be deleted from a gift before the consignment is dispatched (except in the case of shipping material consignments created using a dummy record). See the Team Leader Collections Curation if a preparation needs to deleted after a consignment has been sent.

#### Sending silica gel samples as shipping material

Where material from a silica gel sample is sent to a researcher to be used for destructive sampling, the silica gel sample preparation should be added to the relevant **Gift** record (i.e. there is no need to create a separate shipping material preparation). When adding ‘Silica gel sample’ preparations to a **Gift** record, each preparation needs to be flagged manually. Do not ‘Select all’ and use the ‘Clever button thing’, as this will delete the silica gel sample preparations from the record.

If the entire silica gel sample is used, the quantity in the ‘Silica gel sample’ preparation should be changed to ‘0’ after the material is sent. If only part of the silica gel sample is used, the quantity will need to be adjusted retrospectively to reflect the number of consignments of shipping material that the silica gel sample preparation is linked to (e.g. if material from a single silica gel sample preparation is sent to two separate researchers, and there is still material at MEL, the quantity in the ‘Silica gel sample’ should be ‘3’).

Remember to follow the destructive sampling procedure when processing material, including filling in the **Destructive sampling** fields in the **Conservator event** table.

## <span id="_Toc419393134" class="anchor"><span id="_Toc492047930" class="anchor"></span></span>Incoming exchange

Incoming consignments of exchange, donations and shipping material are recorded in the **Exchange in** table.

### <span id="_Toc419393135" class="anchor"><span id="_Toc492047931" class="anchor"></span></span>Exchange in form

#### Exchange in

##### Exchange number

The MEL reference number for a given consignment of incoming exchange, donation or shipping material. The exchange number is generated automatically when a record is saved. The same sequence is used for both incoming and outgoing consignments (i.e. gift numbers and exchange numbers are allocated sequentially).

##### Date received

The date on which the consignment was checked and processed at MEL.

##### Category

The category of material received. The following options are in the pick list:

-   Donation – specimens received from an institution (or individual) with which MEL does not have a formal exchange agreement

-   Exchange – duplicate specimens received from an institution with which MEL has a formal exchange agreement

-   Shipping material – material that will not be accessioned at MEL (e.g. material for destructive sampling).

##### Processed by

The Curation Officer(s) who processed the consignment. If the consignment was prepared by more than one Curation Officer, they should be entered as a ‘Group agent’. *Note:* consignments received prior to May 2011 are all flagged as being processed by Alison Vaughan as this field was not recorded in the previous Loans and Exchange database.

##### Received from

The institution from which the consignment was received. This corresponds to **Last name** in the **Agent** table and is formatted as the herbarium code followed by ‘ -- ‘ then the title of the institution (e.g. CANB -- Australian National Herbarium). If the institution is in the **Agent** table, but is not formatted as above, please edit the **Agent** record first.

##### Date sent

The date on which the consignment was sent to MEL (as noted on the paperwork received with the material).

##### Quantity

The number of specimens (or samples) in the consignment.

##### Description

A short summary of the contents of the consignment. For example:

-   ‘Miscellaneous vascular plants and cryptogams’.

##### File name

The file name for electronic data for the specimens in the consignment.

#### Administrative fields

The following fields are automatically completed and cannot be edited.

##### Created by

The person who created the database record.

##### Created

The date the record was created.

##### Last edited by

The person who last edited the record.

##### Last edited

The date the record was last edited.

### <span id="_Toc419393136" class="anchor"><span id="_Toc492047932" class="anchor"></span></span>Databasing incoming exchange, donation or shipping material

1.  Open MELISR and click **Interactions** in the task bar

2.  Click on **Exchange In** in the side bar

3.  Enter details in the following fields:

-   **Exchange number**

-   **Date received**

-   **Category**

-   **Processed by**

-   **Received from**

-   **File name**

-   **Date sent**

-   **Quantity**

-   **Description**

1.  Save the form

2.  Record the exchange number (MEL ref. no.) in red pen on the top right-hand corner of the paperwork.

## <span id="_Toc419393137" class="anchor"><span id="_Toc492047933" class="anchor"></span></span>Non-MEL loans

The *Non-MEL loans* collection is in a separate collection in MELISR. To access it, log into MELISR and select *Non-MEL loans* in the **Choose a Collection** window.

### <span id="_Toc419393138" class="anchor"><span id="_Toc492047934" class="anchor"></span></span>Non-MEL loan form

#### Loan

##### MEL reference number

A four-digit reference number allocated when a loan is received at MEL. This field fills automatically when a new loan record is created.

##### Loan status

The current status of the loan. The following values are available in the pick list:

-   Requested – formal loan request sent but specimens not yet received at MEL

-   Current – all specimens still at MEL (or some returned and confirmed as received)

-   Returning – all or some specimens returned but not confirmed as received

-   Complete – all specimens returned and confirmed as received

-   Written off – all specimens lost or destroyed.

##### Quantity outstanding

The number of specimens currently on loan (i.e. the quantity borrowed minus the quantity returned). For loans with loan preparations, **Quantity outstanding** is calculated automatically when a new **Shipment** record is added (i.e. when a return or transfer is processed).

##### Loan number

The loan number allocated by the lending institution. The loan number is automatically prefixed with the abbreviation of the lending institution when the record is saved (e.g. BM 2626M).

##### Quantity borrowed

The number of specimens received in the loan.

##### Received

The date on which the loan was checked and acknowledged at MEL.

##### Current due date

The date by which the loan is to be returned. The loan period is generally 12 months from the date of receipt, unless specified otherwise. The **Current due date** will be the same as the **Original due date** unless the loan has been extended.

##### Original due date

The date by which the loan is to be returned. The loan period is generally 12 months from the date of receipt, unless specified otherwise.

##### Loan closed

A check box used to indicate that all specimens have been returned (or transferred) and acknowledged.

##### Taxa

The families and genera or taxa in the loan. Taxa should be entered in the following formats:

For loans containing multiple taxa:

-   MOSS: Aloina, Crossidium, Desmatodon, Tortula

-   ASTERACEAE: Abrotanella, Arrhenechthites, Bedfordia, Brachyglottis, Crassocephalum, Delairea, Emilia, Erechtites, Euryops, Gynura, Othonna, Roldana, Vernonia

For loans containing a single taxon:

-   MYRTACEAE: Eucalyptus globulus

-   MYRTACEAE: Isotype of Eucalyptus globulus.

##### Conditions

Any special conditions specified by the lending institution. For example:

-   ‘Six month loan period’

-   ‘Destructive sampling permitted subject to K destructive sampling policy’.

##### Comments

Any comments pertinent to the loan. For example:

-   ‘Released from quarantine NM12000784’

-   ‘44 received 02/07/2001. 3 received 12/02/2003.’

-   ‘1 packet and 32 spirit’

-   ‘41 packets and 108 sheets (306 specimens)’.

##### Loan transfer

Details of loan transfers, both to and from MEL. For example:

-   ‘Transferred from CANB’

-   ‘Transferred to AD’.

##### Extension

A summary of loan extensions requested and granted. For example:

-   ‘12 month extension granted 13/10/2005. 12 month extension requested 02/11/2007.’

##### Extension requested

The date of the most recent request to extend the loan.

##### Loan extended

A check box used to indicate that the most recent request for extension has been granted.

##### Old MEL ref. 

The MEL ref. no. for loans that pre-date the current MEL ref. sequence. For example:

-   ‘Page 15’.

#### Loan agents

##### Agent 

The institution from which the loan originated (lending institution) and the MEL botanist(s) and student(s) on behalf of whom the loan was requested.

##### Role

The role of the agent in the loan. The following values can be selected from the pick list:

-   Botanist

-   Lending institution

-   Student.

*Note:* The loan agents should ideally appear in the following order: Lending institution, Botanist, Student. The loan agents currently appear in random order, and the order changes every time the record is saved.

#### Shipments

The **Shipment** table provides a record of all returns and/or transfers for a given loan.

*Note:* Loans that have been returned or transferred in parts have multiple shipment records. It’s easiest to view these in grid form. Multiple shipment records should ideally appear in reverse chronological order, but they currently appear in random order.

##### Shipped to

The institution to which the loan was returned or transferred.

##### Shipment no. 

An auto-generated identifier for the shipment.

##### Date sent

The date on which the consignment was processed at MEL.

##### Prepared by

The Curation Officer(s) who processed the return of the loan.

##### Method

The method by which the loan was shipped. The pick list values relevant to loans are:

-   Air Mail – Customs Insured (loans to overseas institutions)

-   Collected from MEL

-   Courier

-   Express Post

-   Hand delivered

-   Registered Post (loans to Australian institutions)

-   Sea Mail – Customs Insured (very large or heavy loans to overseas institutions)

-   Transfer.

##### Reference no(s) 

The tracking number for each parcel in the shipment. Tracking numbers should be scanned from the consignment note or label (e.g. Registered Post label, Pack & Track International consignment note), rather than entered manually. Multiple numbers should be separated by commas.

##### Quantity sent

The number of specimens in the consignment.

##### Number of parcels

The number of parcels in the consignment. This number should correspond to the number of reference numbers.

##### Weight

The total weight of all the parcels in the consignment.

##### Postage

The total shipping cost for the consignment.

##### Comments

Any comments pertaining to the return of the loan. For example:

-   ‘Spirit material’

-   ‘Sent with MEL exchange 1234’

-   ‘Sent with H loan 12/07 (MEL ref. 1234)’.

##### Acknowledged

The date on which the consignment is confirmed as received. *Note:* this is a text field but dates should be entered in dd/mm/yyyy format.

#### Administrative fields

The following fields are automatically completed and cannot be edited.

##### Created by

The person who created the database record.

##### Created

The date the record was created.

##### Last edited by

The person who last edited the record.

##### Last edited

The date the record was last edited.

### <span id="_Toc419393139" class="anchor"><span id="_Toc492047935" class="anchor"></span></span>Creating and editing non-MEL loans

#### Entering a new non-MEL loan

New non-MEL loan records are created by the Team Leader Collections Curation when the Manager Collections requests a loan:

1.  Log in to MELISR and open the *Non-MEL loans* collection

2.  Open the **Interactions** module

3.  Click **Loan w/o Preps** in the side bar

4.  Enter the following details:

-   **Loan status** ­– ‘Requested’

-   **Taxa**

-   **Conditions**

-   **Comments**

1.  Add **Loan agents** (**Lending institution**, **Botanist(s)** and **Student**)

2.  Delete the blank **Shipment** record

3.  Save the **Loan** record.

#### Processing an incoming non-MEL loan

1.  Open the online **Loans** processing tool (http://melisr.rbg.vic.gov.au/loanreturn/loans)

2.  Find the relevant loan using the **Find loan** function

-   Select ‘Non-MEL loans’ the relevant Institution and ‘Requested loans’ and press **Submit**

-   Select the relevant loan based on the Botanist (and/or Student) and click on ‘Borrower’ to check that the taxa accord with the loan paperwork and specimens

1.  Log in to MELISR and open the *non-MEL loans* collection

2.  Find and open the loan record by entering the MEL ref. no. in the **Simple Search** box. (*Note:* **Simple search** needs to be configured for non-MEL loans – see **Configuring simple search**, p. 178.)

3.  Select **Edit** and enter the following details:

-   **Loan number**

-   **Current due date**

-   **Loan status** – ‘Current’

-   **Date received**

-   **Original due date**

-   **Quantity outstanding**

-   **Quantity borrowed**

-   **Taxa** – if different to what was recorded when loan was requested

-   **Conditions** ­ – e.g. permission for destructive sampling

-   **Comments** ­­– if required

1.  Save the record

2.  If the loan contains specimens with barcodes, scan them in via the **Borrower** (http://melisr.rbg.vic.gov.au/borrower):

-   Select the relevant **MEL reference number** from the drop-down list

-   Scan the specimens into the **Enter barcodes** box (one barcode per line)

-   In the **Add preparations** box, select the relevant **Preparation type** and **Curation Officer** (if the loan contains more than one type of preparation, you will need to scan them in multiple batches)

-   Click **Add to loan**

-   In lieu of marking off specimens on the loan list, annotate the paperwork with ‘\[no. specimens\] received via Borrower, \[date and initials\]’.

#### Returning a non-MEL loan without associated loan preparations

1.  Log in to MELISR and open the *Non-MEL loans* collection

2.  Find and open the loan record by entering the MEL ref. no. in the **Simple Search** box. (*Note:* **Simple Search** needs to be configured for non-MEL loans – see **Configuring simple search**, p. 178.)

3.  Select **Edit** and create a new **Shipment** record

4.  Enter the following details:

-   **Shipped to** – this should always be the lending institution unless the loan is being transferred

-   **Date sent**

-   **Prepared by**

-   **Method**

-   **Reference no(s)**

-   **Quantity sent**

-   **No. parcels**

-   **Weight**

-   **Postage**

-   **Comments**

1.  Edit the **Loan status** to ‘Returning’

2.  Save the record

3.  Check that **Quantity outstanding** has updated automatically and that it accords with the loan paperwork

4.  Create paperwork for the consignment using the **Herbarium transactions paperwork** page: http://melisr.rbg.vic.gov.au/transactions

5.  Create a PDF of the paperwork and e-mail it to the relevant Curator via the HerbMEL account

6.  Print three copies of the paperwork (pink copy to be retained at MEL, white and yellow copies to be sent with specimens).

#### Returning a non-MEL loan with associated loan preparations

1.  Open the **Borrower**: http://melisr.rbg.vic.gov.au/borrower

2.  Select the relevant **MEL reference number** from the drop-down list

3.  Scan the specimens into the **Enter barcodes** box (one barcode per line)

4.  In the **Return preparations** box, select the relevant **Curation Officer** and edit the **Return date** if necessary (default is the current date)

5.  Select **Prepare for return** and check that the relevant preparation and quantities are flagged in the loan preparation list

6.  Select **Return**. The **Borrower** automatically adds a new shipment record to the relevant non-MEL loan record. Several fields need to be updated in MELISR.

7.  Log in to MELISR and open the *Non-MEL loans* collection

8.  Find and open the loan record by entering the MEL ref. no. in the **Simple Search** box. (*Note:* **Simple Search** needs to be configured for non-MEL loans – see **Configuring simple search**, p. 178.)

9.  Select **Edit** and enter the following details in the relevant **Shipment** record:

-   **Method**

-   **Reference no(s)**

-   **No. parcels**

-   **Weight**

-   **Postage**

-   **Comments**

1.  Save the record

2.  Check that **Quantity outstanding** has updated automatically and that it accords with the loan paperwork

3.  In lieu of marking off specimens on the loan list, annotate the paperwork with ‘\[no. specimens\] returned via Borrower, \[date and initials\]’

4.  Create paperwork for the consignment using the **Herbarium transactions paperwork** page: http://melisr.rbg.vic.gov.au/transactions

5.  Create a PDF of the paperwork and e-mail it to the relevant Curator via the HerbMEL account

6.  Print three copies of the paperwork (pink copy to be retained at MEL, white and yellow copies to be sent with specimens).

# \
Attachments  {#attachments-2 .TOCHeading}

# <span id="attach_tools" class="anchor"><span id="_Toc492047936" class="anchor"></span></span>DNA sequences

## Uploading DNA sequences

DNA sequences for both MEL specimens and specimens from other herbaria can be uploaded into MELISR using a comma-delimited text (CSV) file by going to http://melisr.rbg.vic.gov.au/dnasequence in your browser.

The DNA sequence data is added to two tables: **Preparation** and **DNA sequence**.

### The CSV file

CSV files are most easily created and edited in a spreadsheet program like Microsoft Excel or LibreOffice/OpenOffice Calc. A CSV file for uploading sequences into MELISR at a minimum consists of a column with catalogue numbers, **Catalogue number**, and one or more columns (one column for each marker) with **GenBank accession numbers**.

#### Standard columns

If you want to include data in the following columns, the column headers have to exactly match those listed below. Any other column headers will be interpreted as markers (see below). Note that the **Catalogue number** column is mandatory, but the other columns are optional. If you need additional columns for your own use, please let the Biodiversity Informatics Developer know; additional columns can be added easily enough, but we need to make the upload script ignore them so they don’t add to the processing time.

##### CatalogNumber

The **Catalogue number** or barcode. For MEL specimens, use the MEL number – i.e. without the suffix for the part. Make sure you have a space between the ‘MEL’ prefix and the number, as it is needed to recognise it as a MEL collection (and not a MELU one, for example). For collections of other Australian herbaria, it is best to use the catalogue numbers used in the AVH.

##### SampleNumber 

The number of your DNA sample. If this has been filled in, a ‘Molecular isolate’ **Preparation** record will be created. You can already upload the **Preparation** record when you don’t have sequences yet by leaving the marker fields blank.

##### PreparedBy 

The name of the person who prepared the DNA sample. This is not a required field, but since the DNA samples are curated by yourself and the numbers are your own, it is strongly recommended for the benefit of other Specify users and the Collections Branch. You can enter a default value in the next step, so you don’t need to have it in your CSV file.

##### PreparedDate 

The date the DNA isolation was done.

##### Sequencer

The name of the agent responsible for the sequence. This is more important for records of GenBank accession numbers we receive with returned loans. For these records it is probably best to enter the name of the institution the loan is returned from, rather than the person who did the sequencing. Also for this field a default value can be entered in the next step and, as with all **Agent** fields, a group of names can be entered – see **‘Group’ agents** (p. 92).

##### Project

The name of the project for which the sequence was made. Sequences don’t have to belong to a project, but adding it to a project will be nice for future reference (and for other users) and will make it easier to retrieve your sequences from MELISR in a search. Projects need to be created in MELISR first before you can add sequences to them – see **Adding a new project** (p. 149).

##### BOLDSampleID

The identifier for the sample as used in the Barcode of Life Database (BOLD). This is your sample number with a suffix added by BOLD. This field will be useful mainly while we don’t have a BOLD barcode yet.

##### BOLDBarcodeID

The BOLD ID for the DNA barcode.

##### TaxonName

The taxon name. This is for your own use only.

#### Marker columns

Any column header that is different to those listed above will be considered a marker and the column will be expected to contain GenBank accession numbers.

You can have multiple columns with **GenBank accession numbers**, one column for each marker. You can also have an ‘unknown’ marker, if the marker has not been supplied – which will mostly be the case for GenBank accession numbers that come with returned loans. If there is more than one sequence for the same marker and the same specimen, just create a new row for each sequence. Multiple columns with the same header will create an upload error. You can also use multiple rows for the same **Catalogue number** if the data in any of the other columns is different.

When uploading the data from the CSV file, the content of the marker columns (or columns assumed to be markers) are tested against GenBank, and the data won’t be uploaded if they are not valid GenBank accession numbers.

#### Adding new data to the CSV file

**Preparation** and **DNA Sequence** records will only be created once, so you can keep re-uploading the same CSV file over and over when new information is added. This means you can add data as it becomes available, rather than waiting until it is all ready (e.g. you can add a **Sample number** before you have sequences, or a **GenBank accession number** before you have a **BOLD barcode**). Also, if you have made an error in one of the non-identifier columns (i.e. any column other than **Catalogue number**, **Sample number**, **BOLD sample ID** or **BOLD barcode ID**), you can just change it in the CSV file and upload the file again.

### Uploading DNA sequence data

The upload process consists of two steps.

#### Step 1

&lt;&lt;image&gt;&gt;

In the first upload step, apart from the CSV file, you also need to select a **Specify user**. Just select your username from the dropdown list. You do need a Specify user account to be able to upload sequences into MELISR, but you do not need editing privileges.

&lt;&lt;image&gt;&gt;

When both fields have been filled in, you can hit **Continue**.

#### Step 2

When a sequence file is uploaded, the first thing the script does is parse and analyse the first row of the spreadsheet to establish what information it should get from which columns. The results of this are given back to the user to verify in Step 2.

&lt;&lt;image&gt;&gt;

The table in the form at Step 2 indicates what information is found in which column (columns are numbered from 0).

As indicated above, any column header that is not recognised by the script is considered to be a marker. MELISR has a pick list with DNA markers. If a marker is not in the pick list, it will be indicated in the table. You can safely upload sequences with markers that are not in the pick list, as long as you have established that it is indeed a new marker, but a marker won’t display in the Specify form and you won’t be able to query for it unless it is in the pick list. You can add a new marker to the pick list on the [**Markers**](http://melisr.rbg.vic.gov.au/dnasequence/markers) page. See **Adding a new marker** (p. 148) for more details.

You can enter default values for the **Prepared by**, **Prepared date**, **Sequencer** and **Project** columns. Default values will be used when a column is not in the spreadsheet or when a cell in a column is empty. Agent names – **Prepared by** and **Sequencer** – need to be spelt exactly as in the **Agent** table. No special code has been written yet to convert dates, so the only dates that can be uploaded for **Prepared date** are complete dates in ISO date format (‘yyyy-mm-dd’).

Sequences – or the **Collection objects** sequences are derived from, rather – can be added to a sequencing **Project**. **Collection object** records can only be linked to a **Project** if the project is already in the database. You can check what projects are in the database and add new projects on the [**Projects**](http://203.55.15.78/melisr/index.php/dnasequence/projects) page. See **Adding a new project** (p. 149) for more details.

When you are satisfied that you are loading the correct data, hit **Continue**.

&lt;&lt;image&gt;&gt;

Now the real work starts for the upload script. The script will do the following for each row in the spreadsheet:

1.  First, the script will look up the **Catalogue number** in MELISR. If a MEL number can’t be found an error will be recorded and the script will move on to the next row. If a **Catalogue number** of a non-MEL collection can’t be found a new **Collection object** record will be created in the *Non-MEL loans* collection and a warning will be recorded.

2.  If a **Sample number** has been provided, the script will look for a **Preparation** with the same **Sample number** for the same **Collection object** (**Sample numbers** do not have to be unique across the database). If such a **Preparation** cannot be found, a new ‘Molecular isolate’ **Preparation** record will be created. If a **Preparation** already exists, the script will update the **Prepared by** and **Prepared date** fields if required.

3.  For each **GenBank accession number** the script will look if a **DNA sequence** record already exists. If it does, the script will check if any of the **Sequencer**, **BOLD sample ID** or **Bold barcode ID** fields need to be updated.

    If a **DNA Sequence** record does not already exist, the script will try to retrieve the sequence from GenBank, using one of the GenBank web services. A new **DNA sequence** record will only be created if a sequence can be retrieved from GenBank. If the sequence cannot be retrieved, a warning will be recorded.

4.  If a **Project** has been provided, the script will try to link the **Collection Object** record to a **Project**. The **Project** has to exist in MELISR. If the **Project** does not exist a warning will be recorded.

When the script has finished, a report of all the errors and warnings recorded during the running of the script and all the actions undertaken will be displayed on screen. For initial uploads of largish data sets this may take a while because of the GenBank requests.

&lt;&lt;image&gt;&gt;

### <span id="_Ref484511932" class="anchor"><span id="_Ref484511970" class="anchor"><span id="_Ref484511976" class="anchor"><span id="_Toc492047940" class="anchor"></span></span></span></span>Adding a new marker

New markers can be added to the pick list on the **[Markers](http://melisr.rbg.vic.gov.au/dnasequence/markers)** page, http://melisr.rbg.vic.gov.au/dnasequence/markers.

&lt;&lt;image&gt;&gt;

First on the page is a table showing how many sequences are in the database for each marker and whether the marker is in the pick list.

To add a new marker, just select a **Specify user** from the drop-down list and enter the name of a marker in the **Marker** field in the form under **Add a new marker**. Click **Add** when you are done. The new marker will show in the table immediately.

### <span id="_Ref484512021" class="anchor"><span id="_Ref484512023" class="anchor"><span id="_Ref490555342" class="anchor"><span id="_Ref490555347" class="anchor"><span id="_Toc492047941" class="anchor"></span></span></span></span></span>Adding a new project

New projects can be added to MELISR on the [**Projects**](http://melisr.rbg.vic.gov.au/dnasequence/projects) page, http://melisr.rbg.vic.gov.au/dnasequence/projects.

&lt;&lt;image&gt;&gt;

As on the **Markers** page, there is first a table with projects and the number of sequences belonging to each project. These numbers won’t be entirely accurate if the same specimen has been sequenced for multiple projects.

You can add a new project by filling in the fields in the form below and clicking **Add**. The new project will show in the table immediately.

## Working with sequences in Specify

### Finding sequences

#### Simple search

You can configure **Simple search** to find DNA sequences by **GenBank accession number** or **BOLD barcode ID**. To do so, open the **Simple search** configuration window by clicking on the down arrow in the **Simple search** box in the top right-hand corner of your screen and select ‘Simple Search Config’ from the list, as shown below.

&lt;&lt;image&gt;&gt;

In the window that appears (see below), select ‘DNA Sequence’ in the **Available Tables** pane, tick the fields you want the **Simple search** to be able to search on under **Search Fields** and additional fields you want to be displayed in the result under **Display Fields**. There are no **Related Searches** for **DNA Sequence**s, so if you want to find sequences by a particular person, or of a particular taxon or from a geographic region, you have to use the **Query builder**.

&lt;&lt;image&gt;&gt;

#### Query

The **Querying** section of the MELISR Manual (p. 153 onwards) details how to use the query in Specify. The best way to query for sequences in MELISR is as a **Collection object** query:

&lt;&lt;image&gt;&gt;

Things to look out for:

1.  Only include the **Project name** field if you want to query on a project. If you include the field and leave it blank you’ll still only get **Collection Objects** that have been assigned to a **Project** in your result.

2.  This query will return one row for each **Collection Object**, because an aggregator on the **DNA** **Sequence** table has been used. A potential drawback of this is that you cannot query for only **Collection Object**s that have sequences. You can get around this to some extent by, in the search result, ordering the rows on the aggregated *DNA sequences* field and selecting only those rows that have a value in this field before you open the **Collection Object** form. If you really want only records with sequences in your result set, you have to include one or more fields from the **DNA Sequence** table in your query, but as soon as you do that you’ll get a separate row for each sequence.

The results of the example query above are displayed below. You can view details of records in the results by clicking on the **Collection Object form** button.

&lt;&lt;image&gt;&gt;

You can’t query for MEL and non-MEL sequences at the same time, as they are stored in different collections in Specify, the MEL collections in the *National Herbarium of Victoria* collection and the non-MEL ones in *Non-MEL loans*. However, if you save a query in one collection, you can use the same query in the other. If you don’t have access to the *Non-MEL loans* collection, ask one of the MELISR administrators to give you access.

### The DNA sequence form

The **DNA Sequence form** can be opened from the **Collection Object form** by clicking on the *DNA* button in the group of buttons near the bottom of the form:&lt;&lt;image&gt;&gt;

In the **DNA Sequence** form you can link out to the information on the sequence in GenBank by clicking on the **Weblink** button:

&lt;&lt;image&gt;&gt;

Typically, you won’t need to do any editing in the **DNA Sequence** form, as everything can be done in the CSV file you upload, but, if you have updated a sequence in GenBank, and you want the updated sequence in MELISR, you can ask a MELISR administrator for access. Deletion of sequence records from MELISR is something that can only be done by a MELISR administrator.

# <span id="_Ref490556604" class="anchor"><span id="_Ref490556652" class="anchor"><span id="_Toc492047945" class="anchor"></span></span></span>Querying

## <span id="_Toc284178288" class="anchor"><span id="_Ref303848657" class="anchor"><span id="_Ref484511150" class="anchor"><span id="_Toc492047946" class="anchor"></span></span></span></span>Querying Specify

One of the benefits of databasing specimens is the ability to query for and retrieve specimen information efficiently and effectively. Specify has two search functions: a **Simple search**, which enables quick searches on pre-indexed fields, and a **Query builder**, which allows for more structured and comprehensive querying of specimen data. Query results can be viewed in the workspace, saved as a record set, printed or exported as a spreadsheet. The main tables that are used for querying are the **Collection object**, **Taxon** and **Agent** tables.

<span id="_Toc284177000" class="anchor"><span id="_Toc284178289" class="anchor"></span></span>When querying Specify, it is important to bear in mind that several records in some tables in the database (such as **Agent** and **Determinations**) may be linked to the one **Collection object** record, so the one specimen record may appear more than once in your results. If fields from the **Determinations** table are included in the query output, records that match the query terms – and which have more than one determination – will appear more than once in the results grid. For example, MEL 50834 has a det. for *Eucalyptus glaucescens* Maiden & Blakely by J.H. Willis, as well as a conf. by M.I.H. Brooker. A query for **Catalogue number** = ‘0050834A’ that includes the (Taxon) **Full name** in the query output will return two results for the same record in the results grid, because the collection object that matches the search criteria is linked to two records in the **Determinations** table:

**&lt;&lt;image&gt;&gt;**

**&lt;&lt;image&gt;&gt;**

If, however, the **Current** (determination) criteria is set to ‘Yes’, the record will only appear once in the results grid, as the query is only searching for the records where the current determination matches the search criteria:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

Similarly, if a **Collection object** query includes the collectors’ names in the query output, records for specimens with more than one collector will be duplicated in the results. For example, MEL 241014 was collected by A.C. Beauglehole with E.G. Errey as an additional collector. A query for **Catalogue number** = ‘0241014A’ that includes (Collector) **Last name** in the query output will return two results for the same record in the results grid, because the collection object that matches the search criteria is linked to two records in the **Agent** table:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

If the **Is primary** field is included in the query with the **Operator** set to ‘Yes’, the matching collection object record will only appear once in the results, because there is only one primary collector linked to the record:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

However, a record with more than one primary collector will always appear more than once in the query results if the (Collector) **Last name** field is in the query output. MEL 696791 was collected by L.A. Craven and C.R. Dunlop, who are both recorded as primary collectors. If (Collector) **Last name** is included in the query output, and **Is primary** is set to ‘Yes’, the record will be duplicated in the query results:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

If, however, the collectors are aggregated in the query output (by double-clicking on ‘Collectors’ instead of selecting fields from the **Agent** table), the record will only appear once in the query results:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

<span id="_Ref490558703" class="anchor"><span id="_Ref490558706" class="anchor"></span></span>

### Query terms

##### <span id="_Toc284177001" class="anchor"><span id="_Toc284178290" class="anchor"></span></span>Not

Checking the **Not** box will negate the **Operator**. For example, if the **Operator** is set to ‘=’, and the **Not** box is checked, the query will return records that do not equal the value in the **Criteria** field:

&lt;&lt;image&gt;&gt;

This query will not return records where the collector’s last name is Mueller, but the collector’s initials do not contain ‘F.’:

&lt;&lt;image&gt;&gt;

##### <span id="_Toc284177002" class="anchor"><span id="_Toc284178291" class="anchor"></span></span>Operator

The **Operator** defines how the value(s) in the **Criteria** field should be interpreted. The following operators can be selected (note that not all operators are available for all field types):

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  **Expression **    **Result**                                                                                                                                                                                                                                                                                                                                **Available for **
------------------ ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------
  **= **             Finds all records for which the value of the selected field is equal to the specified criterion                                                                                                                                                                                                                                           Number, date and text fields

  **&gt;**           Finds all records for which the value of the selected field is greater than the specified criterion                                                                                                                                                                                                                                       Number and date fields

  **&lt;**           Finds all records for which the value of the selected field is less than the specified criterion                                                                                                                                                                                                                                          Number and date fields

  **&gt; = **        Finds all records for which the value of the selected field is greater than or equal to the specified criterion                                                                                                                                                                                                                           Number and date fields

  **&lt; = **        Finds all records for which the value of the selected field is less than or equal to the specified criterion                                                                                                                                                                                                                              Number and date fields

  **Between **       Finds all records for which the value of the selected field is between the specified criteria                                                                                                                                                                                                                                             Number and date fields

  **In **            Finds all records for which the value of the selected field is included in the list of criteria. Criteria in a list should be separated by commas:                                                                                                                                                                                        Number and text fields
​                                                                                                                                                                                                                                                                                                                                                               
                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

  **Like **          Finds all records for which the value of the selected field contains the pattern specified in the query term. A wildcard character (\*) must be included in the query term to create the desired pattern. For example, the following query will return records for specimens where the collector’s last name begins with ‘adam’:          Text fields
​                                                                                                                                                                                                                                                                                                                                                               
                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

                     The following query will return records for taxa where the taxon name ends in ‘folia’:                                                                                                                                                                                                                                                    

                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

                     The following query will return records for all geographic place names that start with ‘I’ and end with ‘land’:                                                                                                                                                                                                                           

                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

  **Contains **      Finds all records for which the value of the selected field contains a specified string of characters. The position of the query term in the field is not important. For example, the following query will find records where the **Taxon name** field contains ‘rosa’ at the start, the middle or the end of the locality description:   Text fields
​                                                                                                                                                                                                                                                                                                                                                               
                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

  **Empty **         Finds all records for which the value of the selected field is empty. It is important to note that ‘Empty’ is a condition and not the same as leaving the **Criteria** field blank (if the **Criteria** field is left blank, the field will be included in the results, but not in the query).                                            Number fields, text fields and check boxes

  **Yes**            Finds all records for which the check box for the selected field has been ticked                                                                                                                                                                                                                                                          Check boxes

  **No**             ‘No’ is an option for check box fields, but it is not a very useful query term. If you wish to search for records for which a check box has not been ticked, use the ‘Not’ query term in combination with the ‘Yes’ operator. For example, the following query will return records for specimens that don’t have an illustration:         Check boxes
​                                                                                                                                                                                                                                                                                                                                                               
                     &lt;&lt;image&gt;&gt;                                                                                                                                                                                                                                                                                                                     

  **Yes or Empty**   Finds all records for which the check box for the selected field has either been ticked, or is empty                                                                                                                                                                                                                                      Check boxes

  **No or Empty**    Finds all records for which the check box has not been ticked, or is empty (i.e. it includes records that might previously have been ticked, but have since been un-ticked)                                                                                                                                                               Check boxes
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##### <span id="_Toc284177003" class="anchor"><span id="_Toc284178292" class="anchor"></span></span>Criteria

The **Criteria** box is used to enter the search terms for the field that is being queried.

Note that fields that are check boxes do not include **Criteria**, as all the possible values of the check box field are covered in the **Operator**.

##### Sort

The results of each field can be sorted in ascending or descending order, or left unsorted:

  **Symbol**              **Definition**        **Action**
----------------------- --------------------- ----------------------------------------------------------
  &lt;&lt;image&gt;&gt;   **Unsorted**          Query results are unsorted
  &lt;&lt;image&gt;&gt;   **Sort ascending**    Query results are sorted in ascending order (A→Z; 0→99)
  &lt;&lt;image&gt;&gt;   **Sort descending**   Query results are sorted in descending order (Z→A; 99→0)

The default for **Sort** is unsorted. Click the **Sort** button to change it to ascending or descending.

##### Show

You can choose whether or not to display a field in the query form in the results. By default, all fields in a new query form are displayed in the results. Un-tick the **Show** box next to a field to exclude it from the results.

Note that the **Show** button has been un-ticked for most fields in the **Basic record info.** and **Template** queries. Remember to tick the **Show** box next to those fields that you want to see in the results grid.

##### <span id="_Toc284177006" class="anchor"><span id="_Toc284178295" class="anchor"></span></span>Prompt

The **Prompt** command allows query terms to be customised when creating reports. It is not used for querying data.

##### <span id="_Toc284177007" class="anchor"><span id="_Toc284178296" class="anchor"></span></span>Always

The **Always** command relates to report creation and is not used for querying.

#### <span id="_Toc284177008" class="anchor"><span id="_Toc284178297" class="anchor"></span></span>Search controls

##### Search synonyms

If **Search synonyms** is ticked, synonyms of the taxon name or geographic area name will be included in the query and the query results. The **Search synonyms** box is ticked by default.

For example: ‘East Timor’ has been added to the **Geography** table and synonymised with Timor-Leste (the blue text indicates that East Timor is a synonym):

&lt;&lt;image&gt;&gt;

A query for either ‘East Timor’ or ‘Timor-Leste’ will return records for both:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

##### Distinct

If **Distinct** is ticked, only unique records are returned in the results. For example, the following query will produce a list of distinct years from the collecting date of specimens in MELISR collected by Ferdinand Mueller:

**<span style="font-variant:small-caps;">*&lt;&lt;image&gt;&gt;*</span>**

Because only distinct combinations of the values in the **Collector** and **Start date (Year)** fields are being returned, each year only appears once in the results:

&lt;&lt;image&gt;&gt;

If the **Distinct** box is not ticked, the same query returns a list of years from the collecting date of *all* specimens in MELISR collected by Mueller:

&lt;&lt;image&gt;&gt;

When the **Distinct** option is selected, the query results can only be viewed in the workspace; they cannot be used to create a record set, nor can the results be viewed in data entry forms.

<span id="_Toc284177011" class="anchor"><span id="_Toc284178300" class="anchor"></span></span>

##### Count

If **Count** is checked, a count of the matching records will appear in a separate window in the workspace. The results grid will not be displayed when the **Count** function is active.

&lt;&lt;image&gt;&gt;

##### <span id="_Toc284177012" class="anchor"><span id="_Toc284178301" class="anchor"></span></span>Search

The **Search** button activates the query. Pressing **Enter** will also activate the query.

### <span id="_Toc284177013" class="anchor"><span id="_Toc284178302" class="anchor"><span id="_Toc492047948" class="anchor"></span></span></span>Querying dates

Dates that have a date type pick list next to the **Date** field (such as the determination date and the collecting date) can be queried as a full date, or by any combination of day, month and year:

&lt;&lt;image&gt;&gt;

Dates that only allow a full date to be entered (such as the date the record was created) can only be searched as a full date:

&lt;&lt;image&gt;&gt;

If querying by full date, the date entered must be formatted as dd/mm/yyyy (the query will not run if an incomplete date is entered):

&lt;&lt;image&gt;&gt;

Note that partial dates (i.e. a year only, or a month and a year) need to be stored as complete dates in the back end of the database (i.e. as a day, month and year), even though only part of the date is displayed in the front end. ‘01’ is stored in the month and/or day field to complete partial dates. For example, a partial date that displays as ‘07/2007’ is stored in the database as ‘01/07/2007’ and a partial date of ‘2007’ is stored in the database as ‘01/01/2007’. Therefore, if an exact date of ‘01/01/2007’ is queried the partial date (2007) will be included in the results, but you will be able to see which are incomplete and which are complete dates:

&lt;&lt;image&gt;&gt;

### <span id="_Ref303961375" class="anchor"><span id="_Toc492047949" class="anchor"></span></span>Querying by barcode

Barcode scanners can be used to input MEL numbers into the query form. Multiple MEL numbers can be queried by selecting the ‘In’ operator, and listing the MEL numbers in the **Criteria** field, separated by commas. MEL’s barcode scanners are programmed to append a carriage return after the scanned data (which is equivalent to typing in a barcode and pressing **Enter**, which will activate the query). If you wish to enter more than one barcode in a search string, the barcode will need to be re-programmed to remove the carriage return.

Note that your query won’t work if you scan barcodes into the **Catalogue number** field in the query form; they must be entered in the **Barcode** field.

To stop appending a carriage return to scanned data, scan the following code:

> &lt;&lt;image&gt;&gt;

To append a carriage return to scanned data, scan the following codes in the order shown:

> &lt;&lt;image&gt;&gt;

### Standard query forms

Four standard **Collection object** query forms have been created. Note that, while the standard query forms are useful for users unfamiliar with the database structure, they can be slow to run because they contain a lot of fields. It will generally be more efficient to build your own query that contains the fields you want to search by.

#### Catalogue number

The **Catalogue number** query allows you to search for records based on **Catalogue number**. If the **Operator** is set to ‘Contains’, you can enter the MEL number in the field (i.e. the **Catalogue number** without any leading zeroes), but be aware that you may get extra records in your results. For an exact match, set the **Operator** to ‘=’ and enter the full **Catalogue number** (seven digits plus one letter).

&lt;&lt;image&gt;&gt;

#### Basic record info.

The **Basic record info.** query allows you to search and retrieve basic record information for collection objects.

&lt;&lt;image&gt;&gt;

Note that, to reduce the chance of getting more than one result for a single collection object record, the **Current** (determination) and the **Is primary** (collector) fields are set to ‘Yes’.

#### Created and Last edited

The **Created and Last edited** query is designed help you query for all the records you databased or edited on a single day, for quality control or label-printing purposes. **Created** and **Last edited** dates must be entered as full dates. You can use the ‘&lt;’, ‘&gt;’ or ‘Between’ operators to query for records databased or edited on more than one day. For example, to query for records that have been edited since the 1^st^ of January 2010, set the **Operator** to ‘&gt;’ and enter ‘01/01/2010’ in the **Criteria** box for the **Last edited** field:

&lt;&lt;image&gt;&gt;

To query for all records edited in January 2010, set the **Operator** to ‘Between’ and ‘01/01/2010’ and ‘31/01/2010’ in the **Criteria** boxes for the **Last edited** field:

&lt;&lt;image&gt;&gt;

#### Data request

The **Data request** query is useful for extracting data to send to visitors or external researchers. Note that the **Current** determination field is set to ‘Yes’, so you will need to change that if you want to include type status determinations in the results.

### Importing standard queries

The standard queries are saved in the S:\\MEL\\Science\\Specify\\Queries folder. To import the queries into Specify:

1.  Open the **Query** module by clicking on the button in the task bar:

> &lt;&lt;image&gt;&gt;

1.  Right-click in the side bar under ‘Saved Queries’, then select ‘Import Queries’:

> &lt;&lt;image&gt;&gt;

1.  Navigate to S:\\PS&B\\Specify\\Queries\\standard\_queries.xml and click **Open**:

> &lt;&lt;image&gt;&gt;

1.  Click **Select All** in the **Import Queries** window, then click **OK**:

> &lt;&lt;image&gt;&gt;

After being imported, the queries will appear in the side bar.

## Creating queries

Queries can be made using the Specify **Query builder**, or modified from the query template.

### Query builder

The **Query builder** allows you to select query fields from a primary table and its related tables.

To build a new query:

1.  Select the table that you want to query in the side bar. The **Collection object** table is the main table used for querying specimen information. A list of fields and related tables will appear at the top of the workspace:

> &lt;&lt;image&gt;&gt;
>
> Related tables are indicated by an arrow to the right of the table name. One dot after the arrow indicates a one-to-many relationship between the related table and the primary table; two dots indicates a many-to-one relationship between the related table and the primary table:
>
> &lt;&lt;image&gt;&gt;
>
> (Many collection objects can be created by the one person, and one collection object can have many determinations.)

1.  Double-click on the fields that you want to include in your query. The field name will appear below the table list(s) in the workspace:

> &lt;&lt;image&gt;&gt;

To display fields in other tables, single-click a table name in the field list:

> &lt;&lt;image&gt;&gt;

If you double-click on a table name, it will add an field containing aggregated data for that table to the query form. Search criteria cannot be entered for aggregated data fields, but the aggregated data will display in the results.

1.  Bear in mind that for a field to be displayed in the query results, it must be listed in the query

2.  There is no limit on the number of fields that can be added to a query, but larger, more complex queries involving fields from multiple tables will take much longer to run

3.  Modify the query as required – see **\
    **

4.  **Query** terms (p. 155) for a guide

5.  Click the **Search** button to activate the query.

#### Saving queries

You can save a query by clicking the **Save** button at the bottom right-hand corner of the query screen.

&lt;&lt;image&gt;&gt;

If you have modified a query you can choose to save it as a new query, rather than overwriting the existing query, by selecting **Save As**:

&lt;&lt;image&gt;&gt;

### Query template

To use the **Query builder** most effectively, you need to have a good knowledge of the Specify data model. Users who are less familiar with the data model may wish to modify the query template. The query template lists most of the fields available in the **Collection object** table and related tables that contain collecting data of most interest to most users.

To modify the query template:

1.  Click on **Template** in the side bar to open the query form

2.  Click on the delete symbol at the right of the field name to delete any unwanted fields:

> &lt;&lt;image&gt;&gt;

1.  Modify the query syntax as required.

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### Tips for querying

  ###### Querying for major storage groups

  Because not all the major storage groups (Fungi, Lichens, Dicots, Hepatics etc.) in the MEL collection are taxonomic groups, you can’t easily search for a major group using the **Taxon** table. Instead, use the **Major group** field in the **Storage** table to search for storage groups:

  &lt;&lt;image&gt;&gt;

  The major group names are:

  -----------------------------------------
    -   A. Algae        -   G. Gymnosperms
        ​                  
        ​                  
  ------------------- ---------------------
    -   B. Bryophytes   -   L. Lichens
        ​                  
        ​                  

    -   D. Dicots       -   LYC. Lycophytes
        ​                  
        ​                  

    -   FER. Ferns      -   M. Monocots
        ​                  
        ​                  

    -   F. Fungi        
        ​                  
        ​                  
  -----------------------------------------

  ###### Querying for type specimens

  The easiest way to query for types is to use the **Det. type** field. Query for the name in the (Taxon) **Full name** field, and set **Det. type** to ‘Type status’:

  &lt;&lt;image&gt;&gt;

  If the **Current** determination field is in your query form, make sure it isn’t set to ‘Yes’, as Type status dets are never set as the current determination.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Query results

Query results are limited to 20,000 records. A count of records matching the query term can exceed 20,000, but Specify can only display 20,000 result records at once. Use the **Count** function if you only want to know the number of records that match your query, otherwise break the query into smaller sections by adding more search terms. If you need to view more than 20,000 results, see a database administrator, who can perform a query in MySQL for you.

### <span id="_Toc284177021" class="anchor"><span id="_Toc284178311" class="anchor"><span id="_Toc492047956" class="anchor"></span></span></span>Viewing query results

Once a query is activated, the results are displayed in a grid in a separate query results tab. Only fields that were included in the query form are displayed in the results grid. The results can be sorted by clicking on the title bar of the field you wish to order by:

&lt;&lt;image&gt;&gt;

Clicking the column header once will sort the results in ascending order (A→Z; 0→99); clicking the title again will sort the results in descending order (Z→A; 99→0).

#### Selecting records

Records in the results grid can be selected by pressing and holding the **Ctrl** key while clicking on records in the list:

&lt;&lt;image&gt;&gt;

You can select or deselect records by clicking the **Select all** or **Deselect all** buttons at the bottom of the query results:

&lt;&lt;image&gt;&gt;

Once records have been selected, you can use the results controls to perform further actions.

#### Results controls

Query results can be viewed and utilised in a number of ways using the controls on the results bar:

  **Symbol**              **Definition**   **Action**
----------------------- ---------------- -------------------------------------------------------------------------------------------------------------------
  &lt;&lt;image&gt;&gt;   Record set       Creates a record set from the selected records
  &lt;&lt;image&gt;&gt;   Attachments      Displays any attachments for records in the query results that are linked to the table that the query is based on
  &lt;&lt;image&gt;&gt;   Form             Opens the selected records in the relevant data form
  &lt;&lt;image&gt;&gt;   Print            Prints the selected records
  &lt;&lt;image&gt;&gt;   Export           Exports the results as a spreadsheet

### <span id="_Ref303868345" class="anchor"><span id="_Toc492047957" class="anchor"></span></span>Record set

Query results can be saved as a record set in the side bar. To create a record set:

1.  Select the results that you want to save from the results grid. If you do not select any records, all records will be included in the record set.

2.  Click the **Record set** symbol in the results bar:

> &lt;&lt;image&gt;&gt;

1.  Enter a name for the record set and click **OK** or press **Enter**:

> &lt;&lt;image&gt;&gt;

To add new records to an existing record set:

1.  Select the results that you want to add to an existing record from the results grid

2.  Click the **Record set** symbol at the bottom of the form:

> &lt;&lt;image&gt;&gt;

1.  Click on the name of the record set that you want to add the records to and click **OK** or press **Enter**:

> &lt;&lt;image&gt;&gt;

See **Using Record sets** (p. 176) for more information about working with record sets.

### Attachments

You can view any attachments associated with the query results by clicking on the **Attachment** symbol:

1.  Select the results that you want to see attachments for from the results grid. If you do not select any records, all records will be included in the record set.

2.  Click the **Attachment** symbol in the results bar:

    &lt;&lt;image&gt;&gt;

3.  An overview of the attachments associated with the results will open in a new tab:

    &lt;&lt;image&gt;&gt;

4.  From here you can examine the attachment information within Specify in three ways:

> Double-clicking an image will open it in a new tab:
>
> &lt;&lt;image&gt;&gt;

Clicking on the form icon underneath the image will open the associated record (in this case, the **Collection object** form):

&lt;&lt;image&gt;&gt;

> Clicking on the **Information** symbol underneath the image will display a summary of the collecting information associated with the image:
>
> &lt;&lt;image&gt;&gt;
>
> From here you can click on ‘Show Collection Object’ to open the full record in the **Collection object** form.
>
> If the attachment is a PDF, Excel or Word file, double-clicking the attachment icon will open it in the relevant program.

### Form

Query results can be viewed in form mode by clicking on the **Form** symbol. The query results will open in the form that corresponds to the table that was queried (i.e. the results of a **Collection object** query will open in the **Collection object** form, and the results of an **Agent** query will open in the **Agent** form). To view results in a form:

1.  Select the results that you want to view from the results grid. If you do not select any records, all records will be included in the record set.

2.  Click the **Form** symbol in the results bar:

> &lt;&lt;image&gt;&gt;

### Print

Query results can be printed by clicking on the **Print** symbol. Note that all records in the results grid will be printed, regardless of whether or not certain records are selected. The results will be printed in the order they were retrieved; any subsequent sorting of the results in the grid will be ignored. To print results:

1.  Select the results that you want to print from the results grid. If you do not select any records, all records will be included in the record set.

2.  Click the **Print** symbol in the results bar:

> &lt;&lt;image&gt;&gt;

1.  In the **Page setup** window, enter a title, select the paper size and orientation, and click **OK**

> &lt;&lt;image&gt;&gt;

1.  A preview of the print file will open in the workspace. Only those fields included in the results grid will be printed.

> &lt;&lt;image&gt;&gt;

1.  Click the print icon to print the results to your local printer.

### Export 

Query results can be exported by clicking on the **Export** symbol. Note that all records in the results grid will be exported, regardless of whether or not certain records are selected. To export results:

1.  Click the **Export** symbol in the results bar:

    &lt;&lt;image&gt;&gt;

2.  Enter a title for the file in the **Title** field, then click the **Browse** button to navigate to the directory in which you want to save the file:

    &lt;&lt;image&gt;&gt;

3.  Name the file and click the **Save** button.

## <span id="_Ref303868150" class="anchor"><span id="_Toc492047962" class="anchor"></span></span>Using Record sets

Record sets can be saved from the results of both a **Simple search** and a **Query** by clicking the **Record set** symbol in the results grid:

&lt;&lt;image&gt;&gt;

See **Record set** (p. 171) for instructions on how to save results as a record set.

Once a record set has been saved, it can be dragged and dropped on to items in the side bar for different modules. If you slightly drag a record set in the side bar, the items in the side bar that can interact with the record set will be highlighted with a coloured outline. For example:

-   If you slightly drag a **Collection object** record set in the **Data** module, the **Collection object** form will be highlighted:

> &lt;&lt;image&gt;&gt;
>
> If you slightly drag an **Agent** record set in the **Data** module, the **Agent** form will be displayed:
>
> &lt;&lt;image&gt;&gt;

Dragging and dropping a record set on an item in the side bar will open the records in the record set in the relevant form, interaction or plugin. For example, dragging an **Agent** record set on to the **Agent** form in the **Data** module will open the agent records for the all the agents in the record set:

&lt;&lt;image&gt;&gt;

The number of records in the record set will match the number of records displayed in the navigation bar at the bottom of the form. You can scroll through the records using the navigation controls.

### Record set menu

The record set menu is accessed by right-clicking the record set in the side bar:

&lt;&lt;image&gt;&gt;

Three options are available:

-   Rename – activates a text field in which you can rename the record set. Type the new name into the text field and press **Enter** to save the record set under the new name.

-   Delete – deletes the record set. Record sets can also be deleted by dragging and dropping them on to the trash can.

-   View – opens the record set in a new results grid. Further actions can be taken by using the controls in the results grid.

<span id="_Toc284178308" class="anchor"></span>

## Simple search

The **Simple search** is designed to eliminate the need to build complex queries to perform commonly executed searches. All the actions that can be applied to query results are available in the **Simple search**.

### <span id="_Ref490554069" class="anchor"><span id="_Ref490554072" class="anchor"><span id="_Toc492047965" class="anchor"></span></span></span>Configuring simple search

**Simple search** can be configured to query on different fields. The fewer fields that are queried, the faster the search will run. To configure **Simple search**, click on the arrow next to the **Simple search** icon, then select ‘Simple Search Config’ from the menu:

> &lt;&lt;image&gt;&gt;

There are three configuration tabs: ‘Search fields’, ‘Related searches’ and ‘Results ordering’.

You can configure **Simple search** any way you like, but the following configuration is recommended to begin with.

1.  In the ‘Search fields’ tab, click on **Collecting information** in the ‘Available tables’ panel, and uncheck the **Start date** and **Collecting no.** in the ‘Search fields’ panel:

> &lt;&lt;image&gt;&gt;

1.  Click on **Determination** in the ‘Available tables’ panel and uncheck the **Date** field in the ‘Search fields’ panel:

> &lt;&lt;image&gt;&gt;

1.  Click on **Locality** in the ‘Available tables’ panel and un-tick **Locality** in the ‘Search fields’ panel.

> &lt;&lt;image&gt;&gt;

1.  Under the ‘Related searches’ tab, check that the following relationships are marked ‘Active’:

    -   Collection object ↔ Collectors

    -   Collection object ↔ Geography

    -   Collector ↔ Collecting event

    -   Collection object ↔ Taxon (there are two of these relationships – check that they are both active)

    -   Collection object ↔ Taxon (determined)

    -   Taxon ↔ Collection object

    -   Taxon ↔ Geography

> To activate (or deactivate) a relationship, click on the relationship description in the ‘Related searches’ panel, then tick (or un-tick) the **Activate** box to the right of the panel:
>
> &lt;&lt;image&gt;&gt;

1.  No changes need to be made in the ‘Results ordering’ tab.

**Simple search** is now configured to query on the following fields:

&lt;&lt;image&gt;&gt;

A query on one of these fields will return records from the primary table that the search term occurs in (e.g. the **Agent** table for a query on **Last name**) as well as from other tables that contain links to the field being queried (e.g. records from the **Collection object** table for specimens that were collected by the agent, or records from the **Taxon** table that link to determinations by the agent).

Curation staff might also wish to use **Simple search** to query for loan or gift transactions. To configure **Simple search** to query for loan and gift records:

1.  Click on **Loan** in the ‘Available tables’ panel and tick the **Loan number** field in the ‘Search fields’ panel:

> &lt;&lt;image&gt;&gt;

1.  Click on **Gift** in the ‘Available tables’ panel and tick the **Gift number** field in the ‘Search fields’ panel:

    &lt;&lt;image&gt;&gt;

#### Wildcards and delimiters

More than one term can be used in a search specification, but the results will vary depending on the use of wildcards and delimiters. For example, if the search string is ‘Lake Bolac’, the **Simple search** results will include records that have either ‘Lake’ OR ‘Bolac’ in any search field. Records that contain the phrase ‘Lake Bolac’ in one field will also be found.

Wildcards and delimiters can be used in the **Simple search** criteria to define queries more narrowly. A wildcard (\*) allows the criteria to be found as part of a string. Single or double quote delimiters (' or ") allow two or more words to be searched as a string rather than as separate criteria. The wildcard and delimiter can also be used together to further limit the search:

  **Query term**                             **Result**
------------------------------------------ ----------------------------------------------------------------------
  \*Clinton                                  Returns any string with Clinton at the end
  Clinton\*                                  Returns any string that begins with Clinton
  \*Clinton\*                                Returns any string that includes Clinton anywhere in the string
  \*Clinton Lake\*                           Returns any string that ends with Clinton or begins with Lake
  "Clinton Lake" or 'Clinton Lake'           Returns any string where Clinton Lake is the entire string
  \*"Clinton Lake"\* or \*'Clinton Lake'\*   Returns any string that includes Clinton Lake anywhere in the string

The search term is queried in all fields that have been selected in the **Simple search** configuration options, so a query for ‘Laur\*’ will return a list of agents whose last name starts with ‘Laur’ (Laurer, Laurie, Laury etc.), as well as a list of all taxon names that begin with ‘Laur’ (Lauraceae, Laurencia, Laurus etc.).

&lt;&lt;image&gt;&gt;

### Simple search examples

##### ‘Wakefield’

A search for ‘Wakefield’ will first return results for agents with the last name ‘Wakefield’, and will then return the results for records in the **Taxon** table and **Collection object** table that contain links to the ‘Wakefield’ entries in the **Agent** table:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

In this example there are:

-   eight records in the **Agent** table for agents with the last name Wakefield

-   167 records in the **Taxon** table that link to records in the **Collection object** table that have determinations by someone with the last name Wakefield

-   4083 records in the **Collection object** table where one of the collectors has the last name Wakefield.

##### ‘2145221a’

A search for a **Catalogue number** will return the results from the **Collection object** table where the **Catalogue number** matches the query term:

&lt;&lt;image&gt;&gt;

Because the **Simple search** is configured to display results from linked tables, a search for **Catalogue number** presents the same result in different ways:

&lt;&lt;image&gt;&gt;

In this example, the same result is described by five different relationships, but because catalogue numbers are unique, they don’t provide any additional information:

-   one record in the **Collection object** table contains the **Catalogue number** 2145221A

-   one record in the **Collection object** table with the **Catalogue number** 2145221A has a determination (either current or non-current) that links to a record in the **Taxon** table

-   one record in the **Collection object** table with the **Catalogue number** 2145221A is linked to one collector in the **Collectors** table

-   one record in the **Collection object** table with the **Catalogue number** 2145221A has a current determination that links to a record in the **Taxon** table

-   one record in the **Collection object** table with the **Catalogue number** 2145221A has a locality that links to a record in the **Geography** table.

#####  ‘China\*’

A search for ‘China\*’ will first return results for names in the **Geography** table that start with ‘China’, and will then return results for records in the **Taxon** table and **Collection object** table that contain links to the ‘China\*’ records in the **Geography** table:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

In this example there are:

-   four records in the **Geography** table that start with ‘China’

-   34 records in the **Taxon** table for taxa that have been collected in China

-   40 records in the **Collection object** table for specimens that were collected in China.

##### ‘Muehlen\*’

A search for a taxon name followed by a wildcard will return a list of all records in the **Taxon** table that begin with the search term, followed by records from the **Collection object** and **Geography** tables that contain links to the record in the **Taxon** table:

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

In this example there are:

-   24 records for taxon names in the **Taxon** table that start with ‘Muehlen’

-   474 records in the **Collection object** table that are currently determined to a taxon name that starts with ‘Muehlen’ (and where the determination agent is known)

-   708 records in the **Collection object** table that contain a determination (either current or non-current) that link to a name in the **Taxon** table that starts with ‘Muehlen’

-   59 records for place names in the **Geography** tree where taxa starting with ‘Muehlen’ have been collected

-   703 records in the **Collection object** table that are currently determined to a taxon name that starts with ‘Muehlen’ (and where the determination agent is either known or unknown)

-   721 **Determinations** in **Collection object** records that link to a name in the **Taxon** table that starts with ‘Muehlen’.

<span id="_Toc284178316" class="anchor"></span>

# Curation tools

## Labels

The **Labels** page in the MELISR website is used to produce specimen and barcode labels.

&lt;&lt;image&gt;&gt;

The URL for the label printing website is http://melisr.rbg.vic.gov.au/labels.

### Printing labels

Specimen labels and barcode labels can be printed for a record set created from a query in Specify, or you can nominate a single MEL number or a sequence of MEL numbers that you want to print labels for. For Vic. Ref. Set specimens, you can print labels by choosing a record set or MEL numbers for the specimen/s in the main collection that have Vic. Ref. Set duplicates, or you can enter the Vic. Ref. Set catalogue number.

To print labels for a set of specimens:

1.  In Specify, create a record set for the set of specimens you want labels for

2.  In the label interface, select your record set from the drop-down list:

> &lt;&lt;image&gt;&gt;
>
> The Specify user name of the person who created the record set appears in brackets next to the record set name.

1.  Select which type of labels you want to print:

> &lt;&lt;image&gt;&gt;

1.  Select which position on the page you want to start printing at:

> &lt;&lt;image&gt;&gt;

1.  Click the **Submit** button. A preview of your labels will appear in your browser.

2.  Press **Ctrl+P** to print your labels, or use the printing controls in your PDF viewer.

To print labels for a single record:

1.  In the label interface, enter a MEL number in the **MEL number (start)** field (or a Vic. Ref. Set number in the **Vic. Ref. Set number (start)** field)

2.  Select which type of labels you want to print

3.  Select which position on the page you want to start printing at

4.  Click the **Submit** button. A preview of your labels will appear in the browser window.

5.  Press **Ctrl+P** to print your labels, or use the printing controls in your PDF viewer.

To print a sequence of numbers:

1.  In the label interface, enter the first number in the sequence in the **MEL number (start)** field or the **Vic. Ref. Set number (start)** field

2.  Either enter the total number of MEL numbers or Vic. Ref. Set numbers in the sequence in the **Count** field, or enter the last number in the sequence in the **MEL number (end)** or **Vic. Ref. Set number (end)** field

3.  Select which type of labels you want to print

4.  Select which position on the page you want to start printing at

5.  Click the **Submit** button. A preview of your labels will appear in the browser window.

6.  Press **Ctrl+P** to print your labels, or use the printing controls in your PDF viewer.

### Type of label

#### Standard herbarium sheet label, 4 per page

Used for herbarium sheets.

&lt;&lt;image&gt;&gt;

#### Long label, 2 per page

Used for herbarium sheets where there is too much information to fit on a 4-per-page label.

&lt;&lt;image&gt;&gt;

#### Fungi and lichen packet label, 4 per page

Used for fungi and lichen packets. The difference between this label and the standard herbarium sheet label is that the ‘Storage’ section appears in a set position at the bottom of the label, instead of directly below the last piece of collecting information, ensuring that the labels are a standard length to fit on fungi and lichen packets.

&lt;&lt;image&gt;&gt;

#### Fungi and lichen packet label, 2 per page

Used for fungi and lichen packets where there is too much information to fit on a 4-per-page label.

&lt;&lt;image&gt;&gt;

#### Bryophyte label, 3 per page

Used for bryophyte packets.

&lt;&lt;image&gt;&gt;

#### Bryophyte label, 2 per page

Used for bryophyte packets where there is too much information to fit on a 3-per-page label.

&lt;&lt;image&gt;&gt;

#### Duplicate label, 4 per page

Used for duplicate specimens. The number of duplicate labels that will be printed Is determined by the **Quantity** field in the ‘Duplicate’ preparation.

&lt;&lt;image&gt;&gt;

#### Duplicate label, 2 per page

Used for duplicate specimens where there is too much information to fit on a 4-per-page label.

&lt;&lt;image&gt;&gt;

#### Duplicate label for seed collections, 4 per page

Used for duplicate seed collections, which need to be printed on adhesive paper.

#### Duplicate label for seed collections, 2 per page

Used for duplicate seed collections where there is too much information to fit on a 4-per-page label.

#### Spirit jar label

Used to label spirit jars.

&lt;&lt;image&gt;&gt;

Spirit jar labels should be printed on 30-per-page adhesive label sheets. You can select which position you want to start printing at by entering a number in the **Start printing at label** field in the web interface (the default position is 1).

#### Spirit collection card

Used for spirit collection cards (rather than printing a specimen label on paper and then gluing the label to a spirit card, you can print directly onto the card):

&lt;&lt;image&gt;&gt;

If the label contains more information than will fit on one side of the card, it will overflow to the other side of the card.

#### Spirit collection card (mail area printer)

As above, but formatted to print correctly on the mail area printer.

#### Carpological collection card

Used for carpological collection cards (rather than printing a specimen label on paper and then gluing the label to a carpological card, you can print directly onto the card):

&lt;&lt;image&gt;&gt;

#### Carpological collection card (mail area printer)

As above, but formatted to print correctly on the mail area printer.

#### Silica gel sample label

Used to label silica gel samples.

&lt;&lt;image&gt;&gt;

Silica gel sample labels should be printed on 30-per-page adhesive label sheets. You can select which position you want to start printing at by entering a number in the **Start printing at label** field in the web interface (the default position is 1).

#### Multisheet label

Used for multisheets where a full specimen label does not need to be printed.

&lt;&lt;image&gt;&gt;

Multisheet labels should be printed on 30-per-page adhesive label sheets. You can select which position you want to start printing at by entering a number in the **Start printing at label** field in the web interface (the default position is 1).

#### Type folder label

Used to label type folders.

&lt;&lt;image&gt;&gt;

Labels for Australian type specimens have an ‘A’ on the right-hand side of the label, and labels for foreign-collected type specimens have an ‘F’ on the right-hand side of the label. Twelve type folder labels will print on an A4 label page.

#### Barcode label 

Used to print barcode labels for a set of databased specimens or a sequence of unused MEL numbers:

&lt;&lt;image&gt;&gt;

Barcode labels should be printed on 30-per-page adhesive label sheets. You can select which position you want to start printing at by entering a number in the **Start printing at label** field in the web interface (the default position is 1).

#### Print labels for parts

By default, labels will only be printed for part ‘A’ of mixed collections. If you want to print separate labels for the different components of mixed collections, tick the ‘print labels for parts’ box:

&lt;&lt;image&gt;&gt;

### Annotation slips

#### Sticky labels, 30 per sheet

Annotation slips can be printed for the current determination for each record in a record set:

&lt;&lt;image&gt;&gt;

Annotation slips should be printed on 30-per-page adhesive label sheets. You can select which position you want to start printing at by entering a number in the **Start printing at label** field in the web interface (the default position is 1).

### Vic. Ref. Set

There are three input options for printing Vic. Ref. Set labels:

-   select a record set that includes collection object records in the *National Herbarium of Victoria* collection that have duplicates in the *Victorian Reference Set* collection

<!-- -->

-   enter a single MEL number or a sequence of MEL numbers for records that have Vic. Ref. Set duplicates

-   enter a single VRS number or a sequence of VRS numbers.

#### Vic. Ref. Set label, 4 per page

Used for Vic. Ref. Set specimens:

&lt;&lt;image&gt;&gt;

#### Vic. Ref. Set label, 2 per page

Used for Vic. Ref. Set specimens where there is too much information to fit on a 4-per-page label:

&lt;&lt;image&gt;&gt;

#### Vic. Ref. Set barcode

Use to print barcodes for specimens in the Vic. Ref. Set:

#### &lt;&lt;image&gt;&gt;

Barcode labels should be printed on 30-per-page adhesive label sheets. You can select which position you want to start printing at by entering a number in the **Start printing at label** field in the web interface (the default position is 1).

## <span id="_Ref303848752" class="anchor"><span id="_Ref303850827" class="anchor"><span id="_Toc492047973" class="anchor"></span></span></span>Numbers

The **Numbers** page in the MELISR website is used to generate sequences of MEL numbers to assign to undatabased specimens, as well as numbers for new loans and exchange records.

&lt;&lt;image&gt;&gt;

The URL for the **Numbers** website is http://melisr.rbg.vic.gov.au/numbers.

#### MEL numbers

To generate a batch of MEL numbers to assign to undatabased specimens:

1.  Enter the number of MEL numbers that you need in the box (the default is 100 numbers), and click the **MEL number** button. The assigned range of numbers will be displayed.

2.  Enter your name in the **Name** field (please enter both your first name and your last name), and click **Accept**

3.  Either print a list of the MEL numbers (in Excel format) by clicking **print list**, or use the **MELISR** **Labels** web page to print barcode labels for the MEL numbers.

To see a list of who has been assigned which MEL numbers, click on the **Overview of assigned MEL numbers** link. A table displaying the numbers assigned, who they have been assigned to, and the date they were assigned will be displayed:

&lt;&lt;image&gt;&gt;

You can click on the **usage** link at the end of a row to view which numbers from each batch of assigned numbers have been used in MELISR.

## Record set creator

The **Record set creator** page allows curation staff to create record sets by scanning specimen barcodes. You can also create a barcode string to use for querying the database, and check the taxon names of the records in the record set.

&lt;&lt;image&gt;&gt;

The URL for the **Record set creator** is http://melisr.rbg.vic.gov.au/recordset.

To create a record set:

1.  Select your Specify user name from the drop-down list

2.  Enter a name for your record set in the **Record set name** field

3.  Scan barcodes into the **MEL barcodes** text box. Note that each MEL number needs to be on a separate line. If your barcode scanner is not configured to append a carriage return after scanning, use the barcodes on page 162 to change the scanner settings.

4.  Click **Create record set**. When you next open Specify, your record set will be saved in the side bar.

To create a string of barcodes to use in the **Query builder**:

1.  Scan barcodes into the **MEL barcodes** text box. Note that each MEL number needs to be on a separate line. If your barcode scanner is not configured to append a carriage return after scanning, use the barcodes on page 162 to change the scanner settings.

2.  Click **Create barcode string**

3.  Copy and paste the barcode string into the **Barcode** field (in the **Collection object** table) in the **Query builder**. Remember to use the ‘In’ operator with your query.

To check the taxon names in your record set:

1.  Scan barcodes into the **MEL barcodes** box

2.  Click **Check taxon names**. A table displaying the MEL number and corresponding taxon name will appear on the page.

<span id="_Toc284177033" class="anchor"><span id="_Toc284178320" class="anchor"></span></span>

# <span id="_Toc316290790" class="anchor"><span id="_Ref383001454" class="anchor"><span id="_Ref383001475" class="anchor"><span id="_Ref419454300" class="anchor"><span id="_Ref484511714" class="anchor"><span id="_Toc492047975" class="anchor"></span></span></span></span></span></span>Plugins

Specify works with the GEOLocate and Google Earth web services to assist with georeferencing and visualising specimen records. GEOLocate and Google Earth can be accessed via the **Locality** form for individual records, or via the **Plugins** module for record sets.

## <span id="_Toc316290791" class="anchor"><span id="_Toc492047976" class="anchor"></span></span>GEOLocate

GEOLocate uses the **Locality** description and geography to find latitude and longitude coordinate data for specimen records.

### <span id="_Toc316290792" class="anchor"><span id="_Toc284177029" class="anchor"><span id="_Toc492047977" class="anchor"></span></span></span>Using GEOLocate in the Locality form

To georeference a specimen record in the **Locality** form:

1.  Complete the **Geography** and **Locality** fields:

> &lt;&lt;image&gt;&gt;
>
> Note that the **Geography** field must contain at least a country name; GEOLocate will not work if only a continent name is entered.

1.  Save the **Locality** form then re-open it by clicking on the Edit symbol &lt;&lt;image&gt;&gt;

2.  Click the **GEOLocate** button at the bottom of the **Locality** form:

> &lt;&lt;image&gt;&gt;
>
> A dialogue window will indicate whether or not GEOLocate has returned results:

&lt;&lt;image&gt;&gt;

1.  If there are no results, click **OK** to return to the **Locality** form. If there are results, click **Yes** to view them in the **GEOLocate results window** (p. 202).

### Using GEOLocate in the Plugins module

GEOLocate can be used to quickly georeference batches of records. To launch GEOLocate from the **Plugins** module:

1.  Open the **Plugins** module by clicking on the **Plugins** button in the task bar

2.  Click and drag a record set on to the **GEOLocate** icon in the side bar:

> &lt;&lt;image&gt;&gt;

If the record set contains records that do not have **Geography** information and/or records that already have latitude and longitude, a warning will be issued:

&lt;&lt;image&gt;&gt;

> Click **Continue** if you want to continue the georeferencing process regardless, or **Cancel** if you want to change the record set first. Do not click **Continue** unless you want to overwrite the existing latitude and longitude values, which is probably *not* what you want to do.
>
> The GEOLocate progress window will indicate how many of the records in the record set have been georeferenced:
>
> &lt;&lt;image&gt;&gt;
>
> A dialogue window will indicate whether or not GEOLocate has found any matching localities.

1.  If there are no results click **OK** to return to the **Plugins** screen. If there are matching records, click **Yes** to view them in the **GEOLocate results window** (below).

### <span id="_Ref369273624" class="anchor"><span id="_Toc492047979" class="anchor"></span></span>GEOLocate results window

&lt;&lt;image&gt;&gt;

-   If there is more than one result, you can scroll through the list of results to view their locations on the map. The first result in the list is not always the correct one: in the example above, the first result is on Sumatra, not Sulawesi.

-   You can zoom in and out to get a more detailed view or a better overview by clicking the + and – buttons, moving the pointer in the zoom scale, or scrolling your mouse wheel. It can be useful to zoom out until you see the place marks for all the results so you can compare them easily. You can also pan the map by holding the left-hand mouse button down and dragging the map into the desired position. The result that is highlighted in the list (the first result in the above example) will have a green place marker; the other results will have red place markers:

    &lt;&lt;image&gt;&gt;

<!-- -->

-   You can adjust the georeference by clicking on the place marker of the highlighted record (i.e. whichever one is green), holding the left mouse button down and dragging the marker to the desired position:

    &lt;&lt;image&gt;&gt;

-   The new latitude and longitude of the green dot will appear under **Position** in the **Correction (Green) Marker Properties** box (there is no need to click the **Apply** button):

> &lt;&lt;image&gt;&gt;
>
> (The latitude and longitude displayed under the map are the mouse position, not the position of the green marker.)

-   You can make the green marker jump back to its original position by clicking on the original red marker. The other fields in the **Correction (Green) Marker Properties** box have not been implemented in Specify, so any data entered in there won’t be stored in the database.

-   To save the geocode, click the **Accept** button at the bottom of the form. When using GEOLocate from the **Locality** form, the GEOLocate window will be closed; when using GEOLocate in the **Plugins** tab, the GEOLocate results window will display the results for the next record in the record set.

  --------------------------------------------------------------------------------------------------------------------
  #### **Caution!**

  If GEOLocate results are accepted, they will overwrite any existing data in the **Latitude and longitude** fields.
  --------------------------------------------------------------------------------------------------------------------
  --------------------------------------------------------------------------------------------------------------------

#### <span id="_Toc284178319" class="anchor"><span id="_Toc284177030" class="anchor"></span></span>Other controls

-   Clicking the **GEOLocate Web** button will transfer the result of the GEOLocate query to the GEOLocate website. The GEOLocate website will display exactly the same information as the plugin in Specify, but uses Google Maps as the base map, which might give more map detail. Changes you make on the GEOLocate website will not be stored in the database, so it is a safe option if you need to play around a bit to determine the correct geocode.

-   Clicking the **Help** button will open **Specify Help**

-   When GEOLocate is used in the **Locality** form, clicking **Skip** will close the GEOLocate window; when GEOLocate is used in the **Plugins** tab, clicking **Skip** will get you to the results of the next record in the record set

-   Clicking the **Quit** button closes the GEOLocate window.

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  #### **Note**

  When you georeferenced a specimen using GEOLocate, it will populate **Latitude and longitude, Datum**, **Source** and **Protocol**. **Uncertainty** still has to be entered in the **Locality** form.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## World Wind

World Wind is an open-source, 3D, interactive world viewer. It can be used in Specify to display the locality of **Collection object** records, or to map localities during data entry.

Clicking the **Display in World Wind** button will open the NASA World Wind application. A text box at the top of the World Wind window allows latitude and longitude or a locality name to be entered:

&lt;&lt;image&gt;&gt;

Press **Enter** after typing the locality name. The location is then displayed on a World Wind map:

&lt;&lt;image&gt;&gt;

If the **Collection object** has been georeferenced, or if there is a locality in the **Locality** form, World Wind will automatically plot the location on the map once the button is clicked. **Never close the window by clicking the** OK **button unless you want to change the geocode in the** Locality **record. **

The following mouse and keyboard controls operate in World Wind:

For a mouse with a scroll wheel:

----------------------------------------------------------------------------------------------------------------------------------
  **Pan **             Click and drag the left mouse button to pan in all directions
-------------------- -------------------------------------------------------------------------------------------------------------
  **Zoom **            Use the scroll wheel on the mouse or click and drag the left and right mouse buttons to zoom in and out

  **Tilt **            Click and drag the right mouse button up and down, or press the **PgUp** and **PgDn** keys to tilt the map.

  **Rotate **          Click and drag the right mouse button left and right to rotate the map.
​                       
                       *Note:* crossing the top and bottom half of the screen while rotating will change the rotation direction.

  **Stop **            Press the spacebar to stop the map

  **Reset heading **   Press **N** to reset the heading

  **Reset all **       Press **R** to reset all settings
  ----------------------------------------------------------------------------------------------------------------------------------

For a mouse with a single button:

  **Pan **             Click and drag the left mouse button to pan in all directions. Click the left mouse button once to center the view.
-------------------- -----------------------------------------------------------------------------------------------------------------------------
  **Zoom **            Press and hold the **Ctrl** key on the keyboard and click and drag the left mouse button up and down to zoom in and out
  **Tilt **            Press and hold the **Shift** key on the keyboard and click and drag the left mouse button up and down to tilt the map
  **Rotate **          Press and hold the **Shift** key on the keyboard and click and drag the left mouse button to rotate the map left and right.
  **Stop **            Press the spacebar to stop the map
  **Reset heading **   Press **N** to reset the heading
  **Reset all **       Press **R** to reset all settings

## Google Earth

The Google Earth plugin is used as a means of visualising **Collection object** records from Specify in Google Earth. The full version of Google Earth 4.3 (or higher) must be installed on the local computer for the Specify Google Earth plugin to work.

Specify plots **Collection object** records in Google Earth based on the latitude and longitude provided in the **Locality** form. Google Earth can either be launched in the **Locality** form, or by dragging and dropping a record set onto the Google Earth icon in the **Plugins** module.

Before plotting specimen records using **Google Earth**, make sure that all records in the record set contain latitude and longitude values.

### <span id="_Toc284177034" class="anchor"><span id="_Toc492047982" class="anchor"></span></span>Using Google Earth in the Locality form

To launch Google Earth from the **Locality** form:

1.  Open a **Collection object** record and click on the **Locality** information symbol to view the **Locality** form:

> &lt;&lt;image&gt;&gt;

1.  Click the **Display in Google Earth** button at the bottom of the **Locality** form:

> &lt;&lt;image&gt;&gt;

-   Google Earth will open, and the **Collection object** records in the record set will be mapped:

> &lt;&lt;image&gt;&gt;

### <span id="_Toc284177035" class="anchor"><span id="_Toc492047983" class="anchor"></span></span>Using Google Earth in the Plugins module

To launch Google Earth from the **Plugins** module:

1.  Open the **Plugins** module by clicking on the **Plugins** button in the task bar

2.  Click and drag a Record set on to the **Google Earth** icon in the side bar:

> &lt;&lt;image&gt;&gt;

-   Google Earth will open, and the **Collection object** records in the record set will be mapped:

> &lt;&lt;image&gt;&gt;

-   Collection object information is shown in the Google Earth information window:

> &lt;&lt;image&gt;&gt;

# <span style="font-variant:small-caps;">Appendices</span>

## <span id="_Ref303847908" class="anchor"><span id="_Ref303848508" class="anchor"><span id="_Ref303853723" class="anchor"><span id="_Toc492047985" class="anchor"></span></span></span></span>1. Abbreviations

  **Term**         **Abbreviation**
---------------- ------------------
  approximately    approx.
  avenue           ave
  boulevard        bvd
  circa            ca. *or* c.
  circuit          cct
  close            cl.
  court            ct
  crescent         cres.
  degrees          deg. *or* °
  drive            dr.
  east             E
  esplanade        esp.
  feet             ft *or* '
  freeway          fwy
  heights          hts
  highway          hwy
  inch             in. *or* ''
  Island/Islands   I./Is
  junction         jnc.
  kilometres       km
  metres           m
  mile             mi.
  minutes          min. *or* ′
  more or less     +/-
  Mount            Mt
  National Park    NP
  north            N
  parade           pde
  place            pl.
  point            pt
  reserve          res.
  road             rd
  seconds          sec., s *or* ″
  south            S
  street           st
  terrace          tce
  track            trk
  west             W
  yard             yd

Note that Road, Street, Track etc. should only be abbreviated for named places, and not for general use, e.g.:

-   5 km along the Daylesford–Malmsbury **Rd** …

> BUT

-   5 km along the **road** to Daylesford from Malmsbury …

## <span id="Appendix_2" class="anchor"><span id="_Ref303849161" class="anchor"><span id="_Toc492047986" class="anchor"></span></span></span>2. Examples of determination records

The following examples demonstrate how a range of determinations should be entered into MELISR. Because the **Current** check box is automatically ticked when you add a new determination, it is easier to enter the determinations in chronological order.

######## MEL 2088758

This sheet has one old label bearing a name and author combination that appears to be an error, plus one MEL annotation from the Foreign Fabaceae Project.

&lt;&lt;image&gt;&gt;

1.  The author of *Pongamia glabra* is Vent.; *Pongamia glabra* Lamarck is not listed in Tropicos, and it is not clear whether it is a homonym, an isonym or an error. Because we know that *Pongamia glabra* Vent. is a synonym of the name to which the specimen is currently determined, *Millettia pinnata*, it’s fairly safe to assume that ‘Lamark’ is just an error. *Pongamia glabra* Vent. can be entered as the **Taxon name**, and *Pongamia glabra* Lamark should be entered in **Det. notes** to record what is actually written on the label:

> &lt;&lt;image&gt;&gt;

1.  Existing annotations for special projects, such as the Foreign Fabaceae Project, should be entered with ‘Annot.’ in the **Det. type** field and the project name as the determiner, but note that ‘Annot.’ and project names should not be used for new determinations – please always use Det. or Conf. for new determinations:

> &lt;&lt;image&gt;&gt;

######## MEL 2068911

This specimen has three labels that bear names: the original collecting label bearing a taxon name written in F.M. Bailey’s hand; an old MEL label with the same name in Mueller’s handwriting; and a more recent determination on a MEL det. slip that includes extra information about the taxon concept. Even though Bailey and Mueller have given the same name to the specimen, their determinations may be of historical interest and should both be recorded.

&lt;&lt;image&gt;&gt;

&lt;&lt;image&gt;&gt;

1.  Enter ‘Bailey, F.M.’ as the determiner, and tick the **Determiner inferred** box to indicate that the determiner was inferred from the label:

> &lt;&lt;image&gt;&gt;
>
> Note that, if you didn’t recognise the handwriting on the original collecting label, and the taxon name is the same as one of the later determinations, there’s no need to enter it as a separate determination.

1.  Mueller’s determination can be entered in the same way as Bailey’s determination:

> &lt;&lt;image&gt;&gt;

1.  For Helen Aston’s determination (which is partly obscured in the image above), ‘eastern variant’ should be entered in the **Extra information** field:

> &lt;&lt;image&gt;&gt;

######## MEL 2040511

This specimen has an older, typed label that appears to have been taken from a list of exsiccata specimens, plus a name change written directly on the moss packet.

&lt;&lt;image&gt;&gt;

1.  ‘*Dicranum aciculare*’ on the typed label can be treated as the first determination. The author on the label (H. R.) differs from the author given in Tropicos (Hedw.), and a synonym is also given. *Dicranum aciculare* Hedw. should be selected from the **Taxon name** list, and both names and authors on the original label should be entered in **Det. notes**:

> &lt;&lt;image&gt;&gt;

1.  The current determination has not been attributed to a person or a project, so only the **Taxon name** field (and the **Current** box) need to be filled in:

> &lt;&lt;image&gt;&gt;

######## MEL 299373

This specimen bears two names: *Crotolaria* *pterocaule*, which was not in the **Taxon** table, and a recent MEL annotation from the Foreign Fabaceae Project.

&lt;&lt;image&gt;&gt;

1.  *Crotolaraia pterocaule* is a validly published name, so it can be added to the **Taxon** table, and the determination can be entered without a **Determiner**.

> &lt;&lt;image&gt;&gt;
>
> If you are familiar with the handwriting, you could choose to enter the determiner’s name and tick the **Determiner inferred** box.

1.  The current annotation is straightforward:

> &lt;&lt;image&gt;&gt;

######## MEL 590554

This specimen has three labels: an old MEL label with a taxon name in Mueller’s handwriting; an annotation slip with the same name as the blue MEL label, and an uncertain redetermination.

&lt;&lt;image&gt;&gt;

1.  Enter ‘Mueller, F.’ as the determiner, and tick the **Determiner inferred** box to indicate that the determiner was inferred from the label:

> &lt;&lt;image&gt;&gt;

1.  ‘Capparidaceae, revised by M. Jacobs’ should be entered in the **Det. notes** field, as it provides useful information about the determiner’s knowledge of the family:

> &lt;&lt;image&gt;&gt;

1.  Hewson’s determination has a qualifier before the taxon name. By default, the **Qualifier rank** will be set to the lowest rank to which the specimen has been determined. Because the qualifier on this det. slip appears before the genus, not the species epithet, you need to select ‘genus’ from the **Qualifier rank** pick list. ‘Flora of Australia’ should be selected from the **Flora** pick list:

> &lt;&lt;image&gt;&gt;

######## MEL 2347722

This specimen has one label in the collector’s handwriting that bears two synonyms, and a recent MEL determination slip.

&lt;&lt;image&gt;&gt;

1.  If there is more than one name on a single label, and they are written in the same handwriting, they can be treated as a single determination. In this case, it is not clear whether the name being applied to the specimen is *Lespedeza daurica* or *Trifolium dauricum*. Unless there is reason to think otherwise, assume that the first (and in this case, more prominent) name is the name the specimen is being determined to. On this label, there are two spellings of the species epithet *davurica*, both of which are incorrect. The correct spelling should be selected from the **Taxon name** drop-down list. Enter all the names in the **Det. notes** field to record exactly what appears on the label:

> &lt;&lt;image&gt;&gt;
>
> If you were familiar with the collector’s handwriting, and knew that the label was written by O.W. Borrell, you could choose to enter him as the determiner and tick the **Determiner** i**nferred** box.

1.  The current determination is straightforward:

> &lt;&lt;image&gt;&gt;

######## MEL 248757

There are three taxon names on this sheet: one written directly on the sheet in Steetz’s hand; a small, typed label reading ‘*Psoralea plicata* Del. Aeg. Sup.’; and a more recent determination on a MEL det. slip.

&lt;&lt;image&gt;&gt;

1.  A taxon name written on the sheet in Steetz’s hand can be treated as a determination. ‘Steetz, J.’ should be entered as the determiner, and the **Determiner inferred** box ticked:

> &lt;&lt;image&gt;&gt;

1.  The current determination is straightforward. Note that, if known, the determiner’s full initials should be entered in the **Determiner** field, even if only one initial is given on the det. slip:

> &lt;&lt;image&gt;&gt;
>
> The ‘*Psoralea plicata* Del. Aeg. Sup.’ label relates to one of Steetz’s collections and should not be treated as a determination. ‘Aeg. Sup.’ can be entered in the **Original collection** field:
>
> &lt;&lt;image&gt;&gt;

######## MEL 2347754

This specimen has three labels with taxon names. Although the first taxon name on the bottom two labels is the same, they should be entered as separate determinations because they contain different nomenclatural information.

&lt;&lt;image&gt;&gt;

1.  Because we treat the first name on a label as the name the specimen was determined to (unless there is reason to interpret the label differently), this determination would have *Lespedesza polystachya* in the **Taxon name** field, and both names on the label entered in **Det. notes**:

> &lt;&lt;image&gt;&gt;

1.  The second label would be entered in the same way (i.e. with the correct spelling of *L. polystachya* in the **Taxon name** field, and the full list of names in **Det. notes**):

> &lt;&lt;image&gt;&gt;

1.  The current determination would be entered as follows:

> &lt;&lt;image&gt;&gt;

######## MEL 2277834

This specimen has four separate determinations. The large, yellowish label at the bottom of the label looks like a herbarium label of sorts, so the names on that label wouldn’t be considered determinations. The oldest determination is on the label in Mueller’s hand, directly above which is a redetermination in someone else’s handwriting. To the right of the specimen is a redetermination by Bentham, and the most recent annotation is a MEL det. slip that indicates the type status of the specimen.

&lt;&lt;image&gt;&gt;

1.  Mueller’s determination should be entered with ‘Mueller, F.’ as the determiner, and the **Determiner inferred** box ticked. Mueller has written ‘*Grevillea dallachiana* Ferd. Mueller \[…\] *parviflora*’ on the label. No infraspecific taxa of *G. dallachiana* have been published, and Mueller listed *G. dallachiana* and *G. parviflora* as distinct taxa in an 1853 report. The best option in this situation is to enter *Grevillea dallachiana* in the **Taxon name** field and enter the names as they appear on the label in the **Det. notes** field:

> &lt;&lt;image&gt;&gt;

1.  ‘G. alpestris Meisn.’ is written directly above the first determination. This should be entered as a separate determination, with only the **Taxon name** field filled in:

> &lt;&lt;image&gt;&gt;

1.  The determination bearing the name *G. alpina* indicates that Bentham provided the name, so he can be entered as the determiner. The note below the name should be entered in **Det. notes**:

> &lt;&lt;image&gt;&gt;

1.  The most recent det. slip is an AVH annotation that repeats the current name and provides the type status. There is no need to include the current name from the AVH annotation as a separate determination, as it doesn’t add any information; it is better to keep Bentham’s determination as the current one, because it is more informative. The type determination needs to be added with the **Det. type** as ‘Type status’ rather than ‘AVH annot.’, and the **Type status** and **Type qualifier** fields filled in. Where the specimen is stored under the typified name, tick the **Stored under this name** field (type specimens are stored under the most recently published name of which the specimen is a type). Make sure that the **Current** box is not ticked for ‘Type status’ determinations:

> &lt;&lt;image&gt;&gt;

######## MEL 524439

There are three labels with names on this specimen. The middle label is very difficult to read, so there’s no need to add it as a determination. The top label is written in A.C. Beauglehole’s hand, and bears the same taxon name as the det. slip at the bottom of the sheet. Whether or not these should be treated as separate determinations is quite subjective. If you consider Beauglehole to be the determiner of the name on the top handwritten label then they should be entered as separate determinations, otherwise a single determination record would suffice.

&lt;&lt;image&gt;&gt;

1.  If you are interpreting the taxon name written on the top label by Beauglehole as a determination, enter it with ‘Beauglehole, A.C.’ as the determiner and tick the **Determiner inferred** box:

> &lt;&lt;image&gt;&gt;

1.  The La Trobe University Herbarium det. slip is straightforward:

> &lt;&lt;image&gt;&gt;

# <span style="font-variant:small-caps;">Index </span>

Abbreviations, 210

Adding attachments, 105

Appendices, 210

Associated taxa examples, 49

Attachment metadata workbench, 106

Downloading attachment metadata, 106

Editing attachment metadata, 107

Uploading attachment metadata, 108

Attachment tools, 143

Image viewing controls, 108

Import attachment mapping file, 111

Import attachments, 109

Show all attachments, 108

Show all images, 108

Attachments, 99

Adding attachments, 105

Attachment file format, 99

Attachment metadata, 101

Attachment storage location, 101

Collection object attachment or Collecting event attachment?, 101

Types of attachments, 100

Collection object attachment or Collecting event attachment?, 101

Batch identify, 38

Carry forward, 20

Creating and editing records, 24

Data entry forms, 24

Additional metadata, 103

Addresses, 97

Agent, 91

Agent geographies, 98

Attachment, 102

Attachments, 99

Collecting event, 44, 45

Collecting event attributes, 52

Collecting trip, 51

Collection object, 25, 58

Collection object attributes, 61

Collectors, 44

Conservator description, 66

Determinations, 30

Events, 66

General coventions, 24

Geocoordinate details, 80

Locality, 69

Locality details, 77

Other identifier, 29

Preparations, 39

Taxon, 83

Data relationships. *See* Relationships between tables

Databasing MEL duplicates, 42

**Determination examples**, 31, 212

DNA sequences

The CSV file

Adding a new marker, 148

Adding a new project, 149

Adding new data to the CSV file, 145

Uploading DNA sequence data, 145

Uploading The CSV file, 143

Upload fields

BOLDBarcodeID, 144

BOLDSampleID, 144

CatalogNumber, 143

Marker columns, 144

PreparedBy, 144

PreparedDate, 144

Project, 144

SampleNumber, 143

Sequencer, 144

Standard columns, 143

TaxonName, 144

Uploading DNA sequences, 143

Working with sequences in Specify, 149

Finding sequences, 149

The DNA sequence form, 152

Duplicates

Databasing duplicates, 42

Field types, 14

Check boxes, 18

Date fields, 18

Number box, 14

Pick lists, 17

Query combo box, 15

Read-only fields, 19

Required fields, 19

Text box, 14

Flowering and fruiting dates, 46

GEOLocate, 200

Google Earth, 207

Habitat examples, 49, 57

Help, 6

Host examples, 57

Image viewing controls, 108

Import attachment mapping file, 111

Importing attachments, 112

Import attachments, 109

Importing attachments, 110

Incoming exchange

Databasing incoming exchange, donation or shipping material, 134

Installing Specify, 1

Labels, 186

Printing labels, 186

Annotation slips, 195

Printing labels for parts, 195

Sticky labels, 30 per sheet, 195

Type of label, 188

Types of labels

Barcode label, 194

Bryophyte label, 2 per page, 190

Bryophyte label, 3 per page, 190

Carpological collection card, 193

Carpological collection card (mail area printer), 193

Duplicate label for seed collections, 2 per page, 192

Duplicate label for seed collections, 4 per page, 192

Duplicate label, 2 per page, 191

Duplicate label, 4 per page, 191

Fungi and lichen packet label, 2 per page, 189

Fungi and lichen packet label, 4 per page, 189

Long label, 2 per page, 188

Multisheet label, 194

Silica gel sample label, 193

Spirit collection card, 192

Spirit collection card (mail area printer), 193

Spirit jar label, 192

Standard herbarium sheet label, 4 per page, 188

Type folder label, 194

Vic. Ref. Set, 195

Vic. Ref. Set barcode, 197

Vic. Ref. Set label, 2 per page, 196

Vic. Ref. Set label, 4 per page, 195

Loans (MEL loans)

Adding preparations to a loan, 121

Adding shipment details to a loan, 122

Databasing loans, 120

Deleting preparations from a loan, 122

Entering a new MEL loan, 120

Printing loan paperwork, 122

Returning a databased MEL loan, 123

Returning an undatabased MEL loan (pre-1996 loans), 123

Transferring a databased MEL loan, 123

Transferring an undatabased MEL loan (pre-1996 loans), 124

MEL numbers, 27

Generating a list of MEL numbers, 197

MELISR fields

(Non-MEL loans shipment), 138, 139

Abbreviation, 94

Acknowledged (Gift), 126

Acknowledged (MEL loans), 115

Addendum, 34

Address, 97

Agent (Collectors), 44

Agent (Non-MEL loans), 137

Agent attachments, 98

Agent type, 92

Alternative name, 33

Altitude method, 75

Assessed by, 68

Associated taxa, 56

Attn:, 97

Attribution, 103

Author, 84

Basis, 35

Borrower’s comments (MEL loans preparations), 118

Botanical region, 79

Catalogue no. (Gift preparations), 128

Catalogue no. (MEL loans preparations), 117

Catalogue no. (Other identifier), 29

Catalogue number, 26

Category, 104

Category (Exchange in), 132

Category (Gift), 125

Cause of damage, 67

CITES no., 94

City, 97

Collecting event attachments, 51

Collecting event attributes, 51, 59

Collecting no., 45

Collecting notes, 48

Collecting trip, 47

Collection object attachments, 59

Collector’s uncertainty, 75

Collectors, 44

Comments, 69

Comments (Agent geographies), 98

Comments (Agent), 95

Comments (Attachments), 105

Comments (Collecting trip), 52

Comments (Collectors), 44

Comments (Geography), 83

Comments (Gift shipment), 128

Comments (MEL loans shipment), 117

Comments (Non-MEL loans shipment), 139

Comments (Non-MEL loans), 136

Comments (Taxon name), 86

Common name, 56, 62

Conditions (MEL loans), 115

Conditions (Non-MEL loans), 136

Conservator description, 59

Conservator event attachments, 69

Copyright date, 103

Copyright holder, 103

Country, 97

Created (Agent), 99

Created (Exchange in), 133

Created (Gift), 129

Created (Locality), 82

Created (MEL loans), 120

Created (Non-MEL loans), 139

Created (Taxon), 91

Created by (Agent), 99

Created by (Exchange in), 133

Created by (Gift), 129

Created by (Locality), 81

Created by (MEL loans), 120

Created by (Non-MEL loans), 139

Created by (Taxon), 91

Cultivated status, 55

Curation notes, 63

Curation sponsor, 64

Current, 32

Current due date (MEL loans), 114

Current due date (Non-MEL loans), 135

Data format, 98

Date (Cultivated status), 55

Date (Determination), 32

Date (Introduced status), 54

Date assessed, 68

Date inferred, 54

Date noticed, 68

Date received (Exchange in), 132

Date requested (MEL loans), 114

Date returned (MEL loan return preparations), 119

Date sent (Exchange in), 133

Date sent (Gift), 127

Date sent (MEL loans shipment), 116

Date sent (Non-MEL loans shipment), 138

Date type, 95

Datum, 73

Depth unit, 78

Description (Exchange in), 133

Description (Gift preparations), 128

Description (Gift), 126

Description (MEL loans), 114

Descriptive notes, 58

Destructive sampling permitted (MEL loans), 115

Det. notes, 36

Det. type, 31

Determiner, 31

Display in Google Earth, 76

Display in World Wind, 76

Duplicates at, 41

E-mail, 94

End date (Agent), 95

End date (Collecting event), 46

End date (Collecting trip), 51

Ethnobotanical info., 61

Event type, 66

Exchange, 98

Exchange number, 132

Extension (Non-MEL loans), 136

Extension granted (MEL loans), 114

Extension requested (Non-MEL loans), 136

Extra information, 35

Fascicle, 64

Fax, 97

File name, 102

File name (Exchange in), 133

File name (Gift), 126

First name, 94

Flora, 36

Full name (Child taxa), 86

Full name (Taxon), 84

Gazetteer, 79

Geocode source, 80

Geographic rank, 82

Geography, 47, 69

GEOLocate, 76

Georeference date, 80

Georeferencing notes, 80

Gift number, 125

GPI, 28

Habitat, 48

Hort. Ref. Set, 43

Host taxon, 56

Hybrid category, 85

Hybrid parent 1, 86

Hybrid parent 2, 86

Hybrid rank, 86

Illustration, 65

Image creation date, 103

Image type, 104

Imaged, 28

Incoming comments (MEL loans preparations), 118

Initials, 94

Institution, 29

Institution name, 92

Introduced status, 54

Is current (Agent address), 97

Is hybrid, 85

Is primary (Collectors), 45

Is resolved (MEL loans preparations), 118

Island, 77

Island group, 77

Jar size, 40

Job title, 94

Label code, 59

Label language, 63

Last edited (Agent), 99

Last edited (Exchange in), 134

Last edited (Gift), 129

Last edited (Locality), 82

Last edited (MEL loans), 120

Last edited (Non-MEL loans), 139

Last edited (Taxon), 91

Last edited by (Agent), 99

Last edited by (Exchange in), 134

Last edited by (Gift), 129

Last edited by (Locality), 82

Last edited by (MEL loans), 120

Last edited by (Non-MEL loans), 139

Last edited by (Taxon), 91

Last name, 92

Latitude, 73

Licence, 105

Loan closed (Non-MEL loans), 135

Loan closed(MEL loans), 115

Loan extended (Non-MEL loans), 137

Loan notice (MEL loans), 115

Loan number (MEL loans), 113

Loan number (Non-MEL loans), 135

Loan p’work, 98

Loan return preparations (MEL loans preparations), 119

Loan status (MEL loans), 113

Loan status (Non-MEL loans), 135

Loan transfer (Non-MEL loans), 136

Loan transfer no. (MEL loans), 115

Loans, 41

Locality, 47, 71

Locality attachments, 76

Longitude, 73

Magnification, 105

Map reference, 79

Max. altitude, 75

Max. depth, 78

MEL reference number (Non-MEL loans), 134

Method (Gift shipment), 127

Method (MEL loans shipment), 117

Method (Non-MEL loans shipment), 138

Migration comments (Gift preparations), 129

Min. altitude, 75

Min. depth, 78

Miscellaneous notes, 58

Mixed collection notes, 60

ms, 84

Multisheet (display field), 28

Multisheets, 41

Name (Geographical subdivisions), 83

Name (Geography), 82

Name (Gift agent), 126

Name (MEL loans agent), 116

Name (Taxon name), 83

Name on label, 83

Nomenclatural note, 85

Not geocoded because, 81

Notice sent (MEL loans), 115

Number (Collection object attributes), 65

Number (Preparations), 40

Number of parcels (Gift shipment), 128

Number of parcels (MEL loans shipment), 117

Number of parcels (Non-MEL loans shipment), 138

Old MEL ref. (Non-MEL loans), 137

On loan, 41

Orig. herb., 42

Original collection, 64

Original due date (MEL loans), 114

Original due date (Non-MEL loans), 135

Other dupl. at, 41

Outgoing comments (MEL loans preparations), 118

Parent (Geography), 82

Parent (Taxon name), 83

Part of specimen, 68

Phenology, 61

Phone, 97

Photograph, 65

Photographer, 103

Post code, 97

Postage (Gift shipment), 128

Postage (MEL loans shipment), 117

Postage (Non-MEL loans shipment), 138

Preparation, 66

Preparation type, 39

Preparation type (MEL loans preparations), 118

Preparation type. (Gift preparations), 128

Prepared by (Gift shipment), 127

Prepared by (MEL loans shipment), 116

Processed by (Exchange in), 133

Processed by (MEL loan return preparations), 119

Project (MEL loans), 114

Protocol (Geocode), 74

Protologue, 84

Provenance, 55

Purpose, 66

Qualifier, 33

Qualifier rank, 33

Quantity, 40

Quantity (Exchange in), 133

Quantity (Gift preparations), 128

Quantity (Gift), 125

Quantity (MEL loans preparations), 118

Quantity borrowed(Non-MEL loans), 135

Quantity on loan (MEL loans), 114

Quantity outstanding (Non-MEL loans), 135

Quantity resolved (MEL loan return preparations), 119

Quantity returned (MEL loan return preparations), 119

Quantity sent (Non-MEL loans shipment), 138

Quarantine (MEL loan return preparations), 120

Rank, 83

Received (Non-MEL loans), 135

Received comments (Gift), 126

Received comments (MEL loans), 115

Received from (Exchange in), 133

Reference no(s) (Gift shipment), 127

Reference no(s) (MEL loans shipment), 117

Reference no(s) (Non-MEL loans shipment), 138

Region, 98

Researcher, 66

Restrictions on use, 103

Results, 67

Returned comments (MEL loan return preparations), 119

Role (Gift agent), 126

Role (MEL loans agent), 116

Role (Non-MEL loans), 137

Sampling date, 66

Sent to (Gift), 127

Sent to (MEL loans), 116

Severity, 67

Shipment no. (Non-MEL loans), 137

Shipment number (Gift), 127

Shipment number (MEL loans), 116

Shipped to (Non-MEL loans), 137

Source (Cultivated status), 55

Source (Geocode), 74

Source (Introduced status), 54

Sponsor, 52

Spore print, 65

Start date (Agent address), 98

Start date (Agent), 95

Start date (Collecting event), 46

Start date (Collecting trip), 51

State, 97

Status (MEL loans preparations), 118

Storage, 43

Stored under this name, 35

Subject, 102

Substrate, 56

Taxa (Non-MEL loans), 136

Taxon attachments, 86

Taxon name, 32

Title (Agent), 94

Title (Attachments), 102

Toxicity, 62

Translated by, 63

Translation confidence, 63

Treatment report, 68

Trip name, 51

Type (display field), 28

Type (Other identifier), 29

Type qualifier, 35

Type status, 34

Uncertainty, 75

Unit (Altitude), 75

Usage, 62

UTM Easting, 79

UTM Grid, 78

UTM Northing, 79

UTM Zone, 79

Verbatim alt., 76

Verbatim collecting date, 53

Verbatim collectors, 52

Verbatim date noticed, 67

Verbatim end date, 51

Verbatim start date, 51

Verified status, 81

Water body, 77

Web link, 95

Weight (Gift shipment), 128

Weight (MEL loans shipment), 117

Weight (Non-MEL loans shipment), 138

Year (Taxon), 84

MELISR fieldsExchange p’work, 98

Non-MEL loans

Creating and editing non-MEL loans, 139

Entering a new non-MEL loan, 139

Processing an incoming non-MEL loan, 140

Returning a non-MEL loan with associated loan preparations, 141

Returning a non-MEL loan without associated loan preparations, 140

Numbers, 197

MEL numbers, 27

Online curation tools, 186

Outgoing exchange and donations

Databasing outgoing donations and exchange, 129

Deleting preparations from a gift record, 131

How to enter outgoing shipping material using a dummy record, 131

How to process outgoing exchange, donation or shipping material, 129

Sending silica gel samples as shipping material, 131

Plugins, 200

GEOLocate, 200

Google Earth, 207

World Wind, 205

Querying, 153

Creating queries, 165

Query builder, 165

Query results, 170

Exporting results, 175

Opening attachments in query results, 172

Opening results in a form, 174

Printing results, 174

Saving as a Record set, 171

Query template, 168

Query terms, 155

Between, 155

Contains, 156

Count, 161

Distinct, 159

Empty, 157

In, 156

Like, 156

Not, 155

Search synonyms, 158

Show, 158

Sort, 157

Querying by barcode, 162

Querying dates, 161

Querying for major storage groups, 169

Querying for type specimens, 169

Simple search, 178

Configuring simple search, 178

Examples, 182

Standard query forms, 163

Importing standard queries, 165

Tips for querying, 169

Record sets, 176

Record set creator, 198

Relationships between tables, 11

Many-to-many, 12

Many-to-one, 12

One-to-many, 12

One-to-one, 11

Show all attachments, 108

Exporting attachments, 109

Image viewing controls, 108

Viewing attachments, 109

Show all images, 108

Exporting attachments, 109

Image viewing controls, 108

Viewing attachments, 109

Specify

Help, 6

Installing Specify, 1

Logging in, 2

Set-up, 1

Substrate examples, 57

Taxon names

Field names, 37

Hybrid formulae, 88

Hybrid names, 88

Informal names, 37

Intergrades, 90

Intermediates, 90

Name usage, 36

New genus and higher taxon names, 87

Source of name, 36

Variants and forms, 36

Taxon names – what goes where?, 36

Transactions

Incoming exchange, 132

Loans, 113

Non-MEL loans, 134

Outgoing exchange and donations, 125

Transactions forms

Exchange In, 132

Gift, 125

Loan (MEL loans), 113

Loan (Non-MEL loans), 134

Loan agents, 116

Loan preparations, 117

Loan return preparations, 119

Shipments, 116

World Wind, 205
