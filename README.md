dmin Cert Prep Modules - Trailhead

Configuration & Setup

1) UI Interface - User Interface that consists of different areas to modify the user interface in the platform. 
	Action Link Templates: A template you can create for an action link group. An Action link is a button on a feed element that targets an API, a Web page, or a file. Use action links to integrate Salesforce and third-party systems into the feed. Every action link belongs to an action link group and action links within the group are mutually exclusive.

	Actions and Recommendations: Used to help guide end users with how to proceed in their daily work. Includes actions.

	App Menu - Area in User Interface section that lists all apps installed in the org. Can control each app's visibility settings and user's permissions. If your users reorder apps in their App Launcher, their sort order overrides yours. Also, after a user reorders the apps, the Salesforce Classic app menu displays the apps in the user’s preferred order.

	Custom Labels - Enable developes to create multilingual apps by prersenting info (i.e. help text or error messages) to users in their native language. 

	Density Settings - Default display setting for org that either shows it as Comfy (spacious view) or Compact (more info in the view)

	Global Actions - These are actions that allow users to log call details, create or update records or send an email without leaving the page they're on. This is usually in the form of a button and doesn't have to necessarily be linked to a specific object. 

	Publisher Layout - allows you to create layouts of actions on Chatter publishers for global pages such as Home, Chatter Home, and User Profile. After creating global publisher layouts, you can assign them to different user profiles.



	UI Settings

	1) UI
		- Enable Collapsible Sections: Collapsible sections let users collapse or expand sections on their record detail pages by using the arrow icon next to the section heading. When enabling collapsible sections, verify that your section headings are displayed for each page layout. Sections remain expanded or collapsed until the user changes the settings for that tab. If your org has enabled record types, Salesforce remembers a different setting for each record type.

		- Show Quick Create: The Quick Create area on a tab home page allows users to create a record quickly with minimal information. It displays by default on the tab home pages for leads, accounts, contacts, and opportunities. You can control whether the Quick Create area is displayed on all relevant tab home pages. The Show Quick Create setting also affects whether users can create records from within the lookup dialog. Creating records in the lookup dialog is available only if Quick Create is available for your chosen record type. In addition, users always need the appropriate “Create” permission to use Quick Create even though it displays for all users.

		- Enable Hover Details: Hover detail displays an interactive overlay containing record details. Details appear when users hover over a link to that record in the Recent Items list on the sidebar, or in a lookup field on a record detail page. Users can quickly view information about a record before clicking to view or edit the record. The record's mini page layout determines which fields are included in the hover details. Users can’t customize which fields appear. This option is enabled by default. To view hover details for a record, users need the appropriate sharing access, and field-level security access for the fields in the mini page layout.

		- Enable Sepaerate Loading of Related Lists: When enabled, users see primary record details immediately. As the related list data loads, users see a progress indicator. Separate loading can improve performance on record detail pages for orgs with large numbers of related lists. This option applies only to Salesforce Classic and is disabled by default. The options for separately loading related lists don’t apply to Visualforce pages, the Self-Service portal, or other pages for which you can’t control the layout.

		- Enable Separate Loading of Related Lists of External Objects: When enabled, related lists of external objects are loaded separately from primary record details and related lists of standard and custom objects. External objects behave similarly to custom objects, except that they map to data that’s stored outside your Salesforce org. It can take a while to retrieve data from an external system, depending on the network latency and availability of the external system. This option applies only to Salesforce Classic and is enabled by default. The options for separately loading related lists don’t apply to Visualforce pages, the Self-Service portal, or other pages for which you can’t control the layout.

		- Enable Inline Editing: Inline editing lets users quickly edit field values, right on a record’s detail page. This option is enabled by default and applies to all users in your org. To enable enhanced lists for profiles in particular, select Enhanced Profile List Views in User Management Settings.

		- Enable Enhanced Lists: Enhanced lists give you the ability to quickly view, customize, and edit list data to speed up your daily productivity. When enabled with the Enable Inline Editing setting, users can also edit records directly from the list, without navigating away from the page. This option is enabled by default. To enable enhanced lists for profiles in particular, Enable Enhanced Profile List Views available in User Management Settings.

		- Enable the Salesforce Classic 2010 User Interface Theme: This option isn’t related to Lightning Experience. In this case, “Salesforce Classic” refers to the newer version of Salesforce Classic, which is the interface that immediately precedes Lightning Experience. Enabling this option turns on the updated Salesforce Classic look and feel. Disabling it turns on the Salesforce Classic 2005 user interface theme —the classic, classic Salesforce interface.

		- Disable Navigation Bar Personalization in Lightning Experience: When selected, users can’t add or reorder the items included in the navigation bar for any app. However, Salesforce recommends disabling navigation personalization per app instead. From Setup in Lightning Experience, go to the App Manager. For the desired app, select App Options. Select Disable end user personalization of nav items in this app. This option applies only to Lightning Experience.

		- Clear Workspace Tabs for Each New Console Session: When selected, previously open workspace tabs aren't loaded in new console sessions. From Setup in Lightning Experience, go to the App Manager, select the console app that you want, and then select App Options. Select Clear workspace tabs for each new console session. This option applies only to Lightning Experience and is disabled by default. Workspace tabs are restored when the browser page is refreshed, even when this option is enabled. But in Safari pages, workspace tabs aren't restored upon refresh. When this option is enabled, opening a new console session clears pinned and unpinned tabs.

		- Enable Tab Bar Organizer: The Tab Bar Organizer arranges tabs in the main tab bar to prevent horizontal scrolling of the page. The Organizer dynamically determines how many tabs can display based on the width of the browser window. It puts tabs that extend beyond the browser's viewable area into a dropdown list.

		- Enable Printable List Views: Printable list views let users easily print list views. If it’s enabled, users click the Printable View link from any list view to open a new browser window, displaying the list view in a print-ready format. The link is located next to the Help for this Page link in the colored title bar of the page.

		- Enable Spell Checker on Tasks and Events: Available in all editions. Enables the Check Spelling button when users create or edit tasks or events. The spell checker analyzes the Description field on events and the Comments field on tasks.

		- Enable Customization of Chatter User Profile Pages: Enables administrators to customize the tabs on the Chatter user profile page. This includes adding custom tabs or removing default tabs. If disabled, users see the Feed and Overview tabs only.

		- Change Default Display Density Setting in Lightning Experience: This option isn’t related to Salesforce Classic, Experience Builder sites, or the Salesforce mobile apps. The display density controls field label alignment and the amount of space between page elements. Decide what the default is for your org on the Density Settings setup page. Users can choose their own display density at any time. You can’t override a user’s display density setting. Depending on which edition of Salesforce you have, your org’s default display setting varies. Two settings are available. The Comfy setting places the labels on the top of fields and has more space between page elements. Compact is a denser view with labels to the left of fields and less space between page elements.

		- Disable Lightning Experience Transition Admin Reminders: Salesforce displays a reminder every 45 days to admins (users with Modify All Data and Customize Application user permissions) working in Salesforce Classic with the countdown to the auto-activation of the Turn on Lightning Experience critical update. The reminder continues repeating until the admin turns on Lightning Experience or the update auto-activates. Salesforce also displays a series of suggested actions to admins in orgs where Lightning Experience isn’t turned on to help prepare orgs for when the Turn on Lightning Experience Critical Update is activated. When this setting is selected, the countdown reminder and the series of recommended actions don’t appear for any of the org’s admins.

		- Enable ICU formats for en_CA locale: After enabling ICU language and locale formats through a critical update, this setting also enables them for the English (Canada) locale.

		- Enable Collapsible Sidebar: The collapsible sidebar enables users to show or hide the sidebar on every page that normally includes it. When enabled, the collapsible sidebar is available to all users in your org, but each user can choose how to display the sidebar. Users can leave the sidebar visible, or they can collapse it and show it only when needed by clicking the edge of the collapsed sidebar.Call center users don't see incoming calls if they collapse the sidebar.

		- Show Custom Sidebar Components on All Pages: If you have custom home page layouts that include components in the sidebar, this option makes the sidebar components available on all pages for all org users. If you only want certain users to view sidebar components on all pages, grant those users the “Show Custom Sidebar On All Pages” permission. If the Show Custom Sidebar Components on All Pages user interface setting is selected, the Show Custom Sidebar On All Pages permission is not available.

		- Enable Home Page Hover Links for Events: This option affects only Salesforce Classic. Enables hover links in the calendar section of the Home tab. On the Home tab, users can hover the mouse over the subject of an event to see the details of the event in an interactive overlay. This option is enabled by default. This checkbox only controls the Home tab; hover links are always available on other calendar views.The fields available in the event detail and edit overlays are defined in a mini page layout.

		- Enable Drag-and-Drop Editing on Calendar Views: This option affects only Salesforce Classic. You can’t disable drag-and-drop in Lightning Experience. Enables dragging of events on single-user, daily and weekly calendar views. Dragging allows users to reschedule events without leaving the page. This option is enabled by default.Calendar views can load less quickly when this checkbox is enabled.

		- Enable Click-and-Create Events on Calendar Views: This option affects only Salesforce Classic. Lets users create events on day and weekly calendar views by double-clicking a specific time slot and entering event details in an interactive overlay. The fields available in the event detail and edit overlays are defined in a mini page layout. Recurring events and multi-person events aren’t supported for click-and-create events on calendar views.

		- Enable Drag-and-Drop Scheduling on List Views: This option affects only Salesforce Classic. Lets users create events associated with records by dragging records from list views to weekly calendar views and entering event details in an interactive overlay. This option is disabled by default. The fields available in the event detail and edit overlays are defined in a mini page layout.

		- Enable Hover Links for My Tasks List: This option affects only Salesforce Classic. Enables hover links for tasks in the My Tasks section of the Home tab and on the calendar day view. This option is enabled by default. Users can hover the mouse over the subject of a task to see the details of that task in an interactive overlay. Your administrator can configure the information presented on these overlays.

		- Enable Enhanced Page Layout Editor: When enabled, the enhanced page layout editor replaces the current interface for editing page layouts with a feature-rich WYSIWYG editor that includes several improvements

		- Enable Streaming API: Enables Streaming API, which lets you receive notifications for changes to data that match a SOQL query that you define in a secure and scalable way. This field is selected by default. If your Salesforce edition has API access and you don’t see this checkbox, contact Salesforce.

		- Enable Dynamic Streaming Channel Creation: Enables dynamic channel creation when using the generic streaming feature of Streaming API. When enabled, generic streaming channels get dynamically created when clients subscribe, if the channel hasn’t already been created. This field is selected by default. If your Salesforce edition has API access and you don’t see the checkbox, contact Salesforce.

		- Enable “Delete from Field History” and “Delete from Field History Archive” User Permissions: Enables the user permissions that allow you to delete field history and field history archive records. This field isn’t selected by default.

		- Enable Custom Object Truncate: Enables truncating custom objects, which permanently removes all the records from a custom object while keeping the object and its metadata intact for future use.

		- Enable Improved Setup User Interface: When disabled, users with Salesforce Classic access their personal settings from the Setup menu. When enabled, users with Salesforce Classic access their personal settings from the My Settings menu, accessible from the username menu. The Setup link is also moved from the username menu to the App Menu. If you change this setting, be sure to notify all users in your org.

		- Use custom address fields: When enabled, the Address custom field type is available in Object Manager. For more information, see Custom Address Fields in Salesforce Help.

		Before you enable custom address fields, review these important considerations:
			-This feature can’t be disabled.
			-This feature has limitations. For details, see Custom Address Fields Requirements and Limitations in Salesforce Help.

		-Activate Extended Mail Merge: Enables Extended Mail Merge for your org. When selected, the Mass Mail Merge link is available in the Tools area on the home pages for accounts, contacts, and leads. Also, single mail merges requested from the Activity History related list on a record are performed using Extended Mail Merge functionality. Before users create mail merge documents using Extended Mail Merge, admins must set up the feature. First, from Setup, in the Quick Find box, enter User Interface, and then select User Interface. Under the Advanced section, select Enable Extended Mail Merge. Admins can indicate whether they want all users’ mail merge documents to be saved to Salesforce Documents, or only documents over 3 MB. After the feature is enabled, admins must create mail merge templates in Microsoft® Word, and upload mail merge templates to Salesforce.

		- Always save Extended Mail Merge documents to the Documents tab: Mail merge documents generated using Extended Mail Merge are added to the user's documents folder on the Documents tab, rather than delivered as email attachments. Users are sent confirmation emails when their mail merge requests have completed. Those emails include links for retrieving generated documents from the Documents tab. These documents count against your org's storage limits.


2) Company Information
	- Located in Setup under Company Settings, this includes things such as Company Name, Address, Locale Settings, User License (Feature, User, Permission Set, Holidays, Currency Setup, Storage, Phone, Fax, Fiscal Year Start Month, Org Edition)

3) Locale Settings
	- Located in Company Informatio and consists of Default Locale, Default Language, Default Time Zone

4) Currency Management
	- Located under Company Information. You can edit current currencies and activate new ones here. You can also change the corporate currency, which is the currency of the corporate headquarters. 
	- You can enable multiple currencies which are used in opportunities, forecasts, reports, quotes and other currency fields. Only active currencies can be used in currency amount fields. You CANNOT disable them once set up. 
	- Enable advanced currency management option allows you to use dated exchange rates, which maps a conversion rate to a specific date range. 

5) Fiscal year
	- Done in setup. You can use a standard of custom fiscal year. you can also choose what year will be in the name of the fiscal year depending on the start date (i.e. April 2023 is start and ends in March 2024, so it an be either year)
	- Enabling custom fiscal years is not reversible. The best practice is to clone a standard fiscal year if you need to create a new custom one. 
	- If forecasting features ar eenabled, creating the initial custom fisal year deletes all quote and adjustments from that year forward. 
6) List views
	- You can create list views for objects/tabs and set specific filter criteria. This can be shared with groups of users including roles/roles & subordinates. Done in the app and object/tab that you select. 
7) Search Results
	- This shows what fields users see when they search for something in SF. This is modified in Setup  for each object, both custom and standard, and is done on the profile level. 
8) Default Settings

9) Homepage layouts
	- This shows what home page is available to users when they log into the org. You can assign lightning home pages to apps and also assign lightning home pages to specific profiles within apps. 

10) Sharing Settings

	Queues are used to share workload and are used in workflow.
	Groups are used to share records between random users.
	Teams are used to provide support for Accounts, Cases, and Opportunities.


11) User Management
	- User management settings section in Setup where you can enable or disable certain features like enhanced profile list view

12) Security Settings
	- 


Object Manager & Lightning App Builder

Object Architecture: SF's data resides inside objects which house the data specifically in records and fields. These are akin to tables, which have columns and rows In SF, these are known as fields and records. The objects in SF can either be standard (these normally include objects like Accounts, Opportunities, Leads, Contacts, Cases) or custom ones where the admin creates them from scratch. The standard objects usually come with the license given (i.e. Sales Cloud normally provides acccess to Accounts, Leads, Opportunity, Campaigns, Quotes, etc and Service Cloud normally provides access to Accounts, Cases, Knowldge, Entitlements, etc). Fields are similar in that they too come as either being standard, where they CANNOT be deleted and are "from the box" or custom, where the admin creates them from scratch. Standard fields can be customized, however, such as updating the values in picklists or lookup filters on relationship fields and tracking field history. 

Object Relationships: How objects relate to one another. There are several types.

	- Lookup Relationship: A loosely couple relationship essentially lonks two objects together to "lookup" one object from the rleated items on another object. 
	- Master-Detail Relationship: it is a strongly couple relationship. In this type, one object is the master and the other the detail. The master/parent controls certain behaviors of the detail/chlid object such as security settings/access. 
	-Many to Many: AKA Junction Objects, this relationship allows each record of a single object to be linked to multiple records of other objects and vice versa. They are created using a custom object and then relating two other objects via two master-detail relationships. Similar to being a "middle-man" between two objects. 
	- Hierarchical relationships: This can only be used on the User object and is designed to create a hierarchy of users. For example, it could be used to list the user's expense approver. 


Data & Analytics Management

1) Data Types
	- Types of data that include text, currency, number, auto number. 

2) Validation rule 

	- This is a rule set up in the object manager under Setup that restricts the type of data being entered into a record in order to maintain data integrity. As an example, if a user is creating a new Opportunity, a validation rule can be set up on a particular field where the user needs to enter in a certain value in order for the record or opportunity in this case to be saved. 

3) Data Import Wizard
	- Not a standalone application and is found in Setup. Prevents duplicates when importing new records and uploads up to 50000 records and can choose whether or not to trigger workflow rules and processes. 
4) Data Loader
	- Is a standalone application on both MacOS and Windows. Can import up to 5000000 records. Cannot prevent dupliates when importing new records and cannot choose whether or not ot trigger workflow rules and processes. 
5) Recycle Bin
	- Is located in the home page and is where you can work with data that has been deleted. Shows up in a list format and you can restore items, delete/hard delete items or empty the entire org recycle bin (if you or user has Modify All permission). Items are in recycle bin for 15 days until they are then removed completely if no action is taken. 

6) Merge function


7) Mass Transfer
	Mass Transfer - You can transfer things like accounts, leads, service contracts (only standard objects you can transfer) and custom objects to other owners. Need required user pemissions and read sharing access for records you don't own

8) Mass Delete - Mass deleting records based on criteria. You need the Modify All data user permission in order to do this. Best done with Data Loader and after backing up files first. 

9) Duplicate matching 
	- You can create a duplicate rule that alerts users to when they're creating a duplicate record. This is the action part of the process.  You can have the system identify whether it's a duplicate record or not by creating a matching rule, which is essentially a conditional rule. This is all done in setup under Dupliate Management. 

10) External ID
	- External ID field can be created to import external data

11) Data Export 
	- You can create a report to export records as a basic step. For exporting large amounts of data/records, you would create a report containing those records and use data loader to export.
	- The Data Export service located in Setup is a monthly export service where you can schedule it on a weekly or nmonthly basis or hit the Export Now button. You need the Weekly Export Data user permission. All data is exported in CSV file format. You can generate backup files manually once every 7 days for a weekly export and 29 days for a monthly export (Professional or Developer edition only)

12) Report Creation
	-Reports can be created and can either be standard reports, which appear in the dropdown, or custom made. Custom reports can be set up in Setup under Report Types.

	-Tabular Reports: Reports that represent just rows. If you just want to show data without the need to show totals, calculations or groups of data, then this is the report for you. It is also best to use this report type if you are planning to export data.

	-Summary Reports: Reprorts that are grouped by rows and subtotals can be viewed. For example, you want to see the number or value of opportunities per account, you would group your report by Account Name. You can also subgroup fields by dragging them under the initial group.

	- Matrix Reports: rows AND columns are grouped and compares totals. Taking the example above, you can create a report to look at the value of opportunities per account by month. 

	- Joined Reports: Allow you to create multiple reports that can be displayed using blocks where the reports are different. For example, you can use a joined report to show the ottal number of opportunities and cases per account, side by side. 

	Things to keep in mind about Reports:

		Report performance: The more blocks your report contains, the longer it will take to load. If you have more than two blocks, use report filters to keep the report view only to the data required (or have users frustrated with report load times!).  

		Export: Joined Reports are designed to be visually useful inside Salesforce, so they don’t export into a workable format. 

		Charts: You can only add one chart to Joined Reports. So, if you have more than two blocks, you have to choose one common factor (or restrict the chart to two objects).

13) Custom Reports
	- You can create custom reports using the report type feature in setup. This will allow you to create reports by joining objects together, where you can either specify that all records from object A should relate to object B or that only some of the records do.
14) Editing & Customizing Reports
	- You can edit and customize reports by going into each report and/or dashboard, respectively. You can customize reports by adding in fields and filters. Same with dashboards.

15) Dashboard components
	- Components are sections you add into a dashboard you create. You can add up to 20 of them and they can be a minimum of 1x1 block. You can add filters onto components and specify what fields you want to filter the component(s) on and how. 
16) Data Sharing
	- Reports and dashboards can be shared via providing access to the folders that the reports and dashboards reside in. Make sure they are public first before going into sharing. The reports should be the one to be modified for sharing first. 

Process Automation Section

1) Workflows
	- Workflows are a basic flow created for simple "If/Then" requests. They can Send an Outbound Message, Create a Task, Send an Email Alert, Update a Field.
	- You create the rule criteria, AKA the if part of the statment ("If the Job Application is Accepted...""), and then the workflwo action, wihich can be any of the four listed above ("then send an email saying "...." ")
	- 


2) Process Builder
	- Older version of Flow that expands up on things that workflow rules do. Used for scenarios with multiple "If/Then" statements. In addition to the standard actions that workflow rules do, they can also create a new record, update any related record, do a quick action to create a record, update a record or log a call, launch a flow, send an email, post ot chatter, submit for approval, call apex methods. The only thing is that PB does NOT support outbound messages.

	- Examples of using PB include: Send a welcome email to any contact that is identified as an internal contact, or create a record in a related custom object that tracks the asset provided to the contact. 
	- Is the only automation tool that can invoke another process

3) Flow Builder
	- The most advanced form of process automation and is used for complex business processes. Can do all that PB can do and more including deleting records and send outbound messages without code.
	- Biggest use case is for screen flows where the user is guided on the screen to capture user input. Can also be used as an autolaunched flow that is invokved automatically from a record change, a scheduled flow thatis confiugred to run on certain timings, etc.


4) Approval Process
	- A process automation that is for the approval of records by another user or group of users. You can set specific actions such as final approval actions and final rejection actions and recall actions,
	- Once an approval process has been activated, you can delete it but make sure it's inactive first. Delete pending approval requests associated with it and remove them from the recycle bin. 
	- For activating an approval process, it must have at least one step before you can activate it. You cannot go back and delete, add, or change the order of steps or even change it's reject or skip behavior. 


Sales and Marketing Applications Section

1) Sales Processes
	- A sales process is a custom set of sales stages that an opportunity must pass through during the lifecycle from open to closed. Salesforce offers various capabilities to support the sales process as an opportunity is in different stages, including forecasting, quotes splitting revenue amongst team members and orders.
	- Record types are created to work with sales processes in order to have page layouts, picklists and specific processes within the sales pipeline. 

2) Opportunities
	- These are the "deals in progress". Opportunities can be attached to an account or contact if desired. It is optionally created when a lead is converted. You can track opportunities, share them, clone them,etc.

3) Products
	- These can be created on a one off basis and stored in price books. 
	- In order to add a product to an opportunity, it needs to have a rate set against it.

4) Price Books
	- This is for setting up pricing in your store. You can configure either a standard price book or custom one for store and buyer groups. 
	- All products must have an entry in the standard price bok  beforee you can add them to other price books. 

5) Leads
	- These are prospective customers that can be converted to a contact and account (optionally an opportunity as well). These can be managed as the user progresses through the salespipeline.
	- When you delete a lead, the lead record moves to the Recycle Bin. Associated notes, attachments, and activities are deleted along with the lead. If you restore the lead, any associated notes, attachments, and activities are also restored.
	- Users without the View Converted Leads permission can delete converted leads via the public API or tools that use the public API.

6) Campaigns
	- Used for marketing. You can define campaign types, organize assets, add members, create campaign hierarchies and then track and report on campaign performance. 

	-You have many things on campaign objects. Related lists include opportunities reltaed to campaign, campaign members which include leads, contacts. Ex: person at tradshow submits a web to lead form so the tradeshow will be part of the campaign. You can add campaign members onto this campaign to build up list of who to target. 

	- Campgain influence looks at what multiple things influence a sale in terms of campaigns. Looks at the lead or contact and what they have touched in terms of campaigns during a set of time that you as an admin establish. User needs to have either CRM user or Sales User Permissio Set assignments to see this.

	- ROI is determined by lead, contact, opportunity. 

7) Content
	- Uses Salesforce CRM content which stores file sin fully searchable file respositories known as libraries. 

Document Folder & File Uploading Review

	Chatter can be one way to attach a file (Salesforce files)
	Record detail page is also another way to attach a file (page layout) or if it has chatter enabled you can do it that way too
	You can contribute content via library
	Salesforce documents is another way. You create a folder within the documents section

Service & Support Applications Section

1) Case management
	- You can manage cases which are the backbone of the service console by creating support processes (which can also include creating page layouts & record types for support processes as well), creating assignment rules, case escalation rules, auto-response rules, web to case, email to case, case teams, etc. Cases are issues brought up by customers. 
2) Support processes
	- A process for managing support cases, specifically, which can be managed by setting up a page layout for users working on cases, creating record types, adding public groups & queses for multi-tier support and escalation rules. 

3) Assignment Rules
	- Automatically assign cases to users or queues based on criteria you define. You can create multiple rules, but only one rule can be active at a time.

4) Case escaalation rules
	- Automatically determines when cases should escalate and what actions to take. After you create a rule, select if from the rules list and add rule entries.

5) Auto-response rules
	- Automatically determine which email templates to use when sending auto-response messages for new cases and what rules to use that trigger the email being sent. 

6) Web-to-case
	-Use a simple web form or a self-service customer community to make it easy for customers to submit cases directly to your customer support group.

7) Email-to-case
	- Automatically convert customer emails to cases and route them to the right user or queue.

8) Case Teams
	- A case team is a group of people that work together to solve cases. For example, a case team can include support agents, support managers, and product managers.
	- When you set up a case team, you can set up the type of access that each case team role has first (private, read only, read/write) and then you add each team to the predefined case teams

9)Knowledge
	- Knowledge base is built from knowledge articles, which are documents of information. Articles can include information on process, like how to reset your product to its defaults, or frequently asked questions, like how much storage your product supports.
	- This is enabled in Service Setup first and it can be a tab in any of the apps. 
	- You can publish the article when it's done and modify it in the page layout for the specific object for the appearance of it.

10) 
 

 Productivity & Collaboration

 1) Activities
 	- Admins can edit Activity Settings in Setup. Activities include tasks, events, log a call, email. 
 	- Specific tasks include call, email, send quote, send letter, other.
 	- Specific events include call, email, send quote/letter, meeting, other.
 	- In Activity Settings, you can tick or untick settings such as allow users to connect multiple contacts to tasks and events;
 	- Specific activity settings include:
 			Enable Group Tasks
			Roll up activities to a contact's primary account 
			Enable Sidebar Calendar Shortcut
			Enable Creation of Recurring Events in Salesforce Classic
			Enable Creation of Recurring Tasks
			Enable Activity Reminders
			Enable User Control over Task Assignment Notifications 
			Allow Flow to send delegated task notifications on records created through Apex
			Allow Process Builder to send delegated task notifications 
			Enable Email Tracking
			Exclude Email Tracking Data by IP Address (i) 
			Show simpler New Task form on mobile 
			Show Event Details on Multi-User Calendar View
			Enable Multiday Events
			Add user lists to calendar views in Lightning Experience 
			Allow Users to Relate Multiple Contacts to Tasks and Events 
			Sort past activities by the completed date 
 
 2) Chatter
 	- Chatter is a corporate network that lets your users work together, talk to each other, and share information, all in real time.
 	- Chatter can show events and tasks that were created on a record page. 
 	- If you want to talk to someone in a post, specfiically, you can @ them with their name
 	- You can create streams that show only the accts, people, contacts, etc, that you want updates on. It's their most recent activities.
 	- You can create private or public groups in order to collaborate on things like certain accts, opps, etc.
 	- Broadcast only is an option where no one can create no new main posts bu thtey can comment. 

 3) Salesforce mobile app
 	- The mobile app is a quick way for users to go through their data. 
 	- Users can modify the navigation items in the app they're currently in but need to have the permissions to do so. 
 	- Admins cannot set different menu configurations for different types of users, but users in lightning apps with correct permissions can change their navigation tabs, and those changes reflect in the lightning app's mobile navigation menu and bar
 	- If you want to include Visualforce pages, Lightning Pages, or Lightning components in your Lightning apps, you must create tabs for them.
	- Before adding a page to the Salesforce mobile app, make sure the page is enabled for mobile. Thoroughly test your Visualforce pages in the Salesforce mobile app because they don’t always work the same as they do on desktop. See the resources section for more information.
	- You can create both global and object specific actions, which are essentially just shortcuts for doing things such as launching a specific workflow in the app (i.e. creating records, logging calls, sharing files). Global actions are good for situations where the user wants to do someting quickly but not completely (i.e. a broker taking in a person's contact info without having to associate the person with other information)
	- Global publisher layout refers to the way the actions are listed in the action bar in the mobile app.  The global lahout only applies to the action bar in places like the feed or chatter groups, or only on pages that aren't related to a specific object.
	- Object specific actions are different from global in that they can update records and they can create records that are automatically associated with related information (i.e. user initiates action that simultaneously creates a contact and it is associated with an account)

4) Compact Layouts
	- This controls what fields appear in the header when a record page is opened in SF mobile app. You can assign up to 10 fields including the name field to displa in that area.
	- Unlike page layouts where you can assign a different layout to each profile, one compact layout is applied to all users. If an object has more than onem record type, you'll se a record type overrides section when you select the primary layout under the compact layout assignment. With it, you can assign specific compact layouts to different record types, 


5) AppExchange
	- This is a place where applications or solutions can be downloaded for scenarios that SF can't handle out-of-box.
	- Things that are offered are Apps, Components, Bolt Solutions, Flow SOlutions, Consultants
	- Compoenents are modular building blocks and web components are user interface elements. Components can be used to track salesforce logins and feature usage, automatically maange email opt-outs, kick of processes, find and merge duplicate records across all objects, add a calendar to a page. 
	- Users can filter the appexchange page by solutio type, ratings, languages, price, editions# salesforce-cert-pre-notes
