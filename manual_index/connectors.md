---
layout: subpage
title: 'Exploring and Managing Connectors'
description: 'not used'
date:   2022-06-07 11:46:41 -0300
categories: start blog
by: 'Altilia Service'
icon: 'user-check'
parent: 'Manual Index'
paragraphs:
  - paragraph_content: 'The Connectors are created and managed through the Altilia Connect Module™. It allows access to  sources external to the platform to ingest documents and content. The Connectors allow you to save on the Knowledge Base within the platform itself. 
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>You can recognize that you are in the Connector view and in which of them you are working, by the indication  provided in the header at the top left of the screen:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image1_Exploring and Managing Connectors.png"
  - paragraph_title: 'Before you Start'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="1">
        <li>Create Project as described in the chapter 
          <a href="/altilia-help-center/manual_index/project/">Create Project</a>
        </li>
      </ol>
    </ul>'
  - paragraph_title: 'Create Connectors'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the Altilia Intelligent Automation™ app, click "<b>Connectors</b>" on the left navigation bar. The </b>Connectors Artifact</b> opens.</li>
        <li>Create a new connector by clicking on "<b>+ New Connector</b>":</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image2.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Type name, description (optional) and connector type (<b>FTP</b> or <b>BLOB</b> storage) and then click on “<b>Create</b>”:</li>
    </ol>
    </ul>'
    image: "manual_index/connectors/image3.png"
  - subparagraph_title: 'Connector Information'
    paragraph_content: 'Your Connectors are available in the <b>Connectors Artifact</b> of your Project, you can use the sorting and searching functionality to find it as described in the paragraph <a href="/altilia-help-center/manual_index/connectors/#Sorting_Search_and_Filter_Connector">Sorting Search and Filter Connector</a>:'
    image: "manual_index/connectors/image4.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="1">
        <li>Inside a Connector panel, several information regarding the created Connector are shown. You can also   find the same information in the drawer panel as described in the paragraph <a href="/altilia-help-center/manual_index/connectors/#Connector_Drawer_Information">Connector Drawer Information</a>. From the top to the bottom at the left side of the panel you can find:</li>      
        <ul style="margin-left: 30px; list-style-type: circle">
          <li><b>Project Name</b>: also clickable to edit it as described in <a href="/altilia-help-center/manual_index/connectors/#Edit_Connector">Edit Connector</a>,</li>
          <li><b>Source Type</b>: type of source connection (FTP or AZURE_BLOB_STARAGE),</li>
          <li><b>Connector Icon</b> for a quick visual impact</li>
        </ul>      
        <li>Also within the Connector panel, you can also find other two features at the upper right corner side, read also more about them in the paragraph <a href="/altilia-help-center/manual_index/connectors/#Settings_Connectors">Settings Connectors</a>:</li>            
        <ul style="margin-left: 30px; list-style-type: circle">
          <li><b>Quick button</b>: interchangeable button with other functions that you can set,</li>
          <li><b>Three dots</b>: to access, delete and archive the Connector</li>
        </ul> 
        <li>Lastly, at the bottom right corner side the <b>Status</b> of the Connector is reported, find out more by reading <a href="/altilia-help-center/manual_index/connectors/#Status_Connector">Status Connector</a>.</li>
      </ol>     
    </ul>'
  - paragraph_title: 'Configure FTP Connectors'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the <b>Connector Artifact</b> of the <b>Config Section</b>, after creating your FPT Connector, enter the connection settings to connect your external FTP server by providing following configurations in the <b>Connection panel</b> at left of current view: </li>
        <ul style="margin-left: 30px; list-style-type: circle">
          <li><b>Host</b> - FTP server end-point,</li>
          <li><b>Port</b> - connection port number,</li>
          <li><b>Username</b> name of the FTP server,</li>
          <li><b>Password</b> password of the FTP server.</li>
        </ul>
      </ol>
    </ul>'
    image: "manual_index/connectors/image5.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>Check your connection by clicking on “<b>Test</b>”, when the connection is successful, “<b>OK</b>” is displayed otherwise “<b>KO</b>” indicates that your FTP server is not reachable for some reason or a typing error in the configurations may have occurred</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image6.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="3">
        <li>If the connection was successful, click on “<b>Home</b>” at bottom left of the same panel to select the desired folder and then click “<b>Open Path</b>”:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image7.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="4">
        <li>The documents are now shown in the <b>Preview panel</b> at right of the Connection panel:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image8.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="5">
        <li>Click on “<b>Save</b>” at the up right corner of the screen to complete the configuration of the Connector:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image9.png"
  - paragraph_title: 'Configure Azure Blob Connectors'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the <b>Connector Artifact</b> of the <b>Config Section</b>, after creating your Azure BLOB Connector, enter the connection settings to connect your external source by providing following configurations in the Connection panel at left of current view</li>
        <ul style="margin-left: 30px; list-style-type: circle">
          <li><b>Connection string</b> - FTP server end-point;</li>
          <li><b>Container</b> - name of the associated Azure container</li>
        </ul>
      </ol>
    </ul>'
    image: "manual_index/connectors/image10.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>Check your connection by clicking on “<b>Test</b>”, when the connection is successful, “<b>OK</b>” is displayed otherwise “<b>KO</b>” indicates that your BLOB Storage is not reachable for some reason or a typing error in the configurations may have occurred</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image11.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="3">
        <li>If the connection was successful, the documents are shown in the Preview panel at right of the Connection panel.</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image12.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="4">
        <li>Click on “<b>Save</b>” to complete the configuration of the Connector.</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image13.png"
  - paragraph_title: 'Settings Connectors'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the <b>Connector Artifact</b>, set the <b>quick button</b> of your Connector panel so that the most frequently used icon appears to you by clicking the three dots icon in the upper right corner of each Connector panel.</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image14.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>Pin the desidered icon in order to see it next to the left of the three dots icon. By default it’s set to “<b>Go to Connector</b>”, read more about it on the paragraph <a href="/altilia-help-center/manual_index/connectors/#Access_into_Connector">Access into Connector</a>.</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image15.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="3">
        <li>Click the pin icon to the right of “<b>Archive</b>” to set it as a quick button for each Connector, read more about it on the paragraph <a href="/altilia-help-center/manual_index/connectors/#Archive_and_Unarchive_Connector">Archive and Unarchive Connector</a></li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image16.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="4">
        <li>Click the pin icon to the right of “<b>Delete</b>” to set it as a quick button for each Connector, read more about it on the paragraph <a href="/altilia-help-center/manual_index/connectors/#Delete_Connector">Delete Connector</a></li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image17.png"
  - paragraph_title: 'Edit Connector'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the <b>Connector Module</b>, edit your Connector already created by clicking on the name at the top left of its panel:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image18.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>The <b>drawer panel</b> opens at the right of the screen enabling you to change name and description of the Connector:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image19.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="3">
        <li>Overwrite them and click anywhere on the screen outside the drawer panel to apply the changes. A pop-up message is displayed as confirmation:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image20.png"
  - subparagraph_title: 'Connector Drawer Functionality'
    paragraph_content: 'From the following <b>drawer</b> it’s also possible to use some features designed to speed up the navigation in the platform.
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>Access in a Connector by clicking on the “<b>Details</b>” button on the bottom side of the drawer panel:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image21.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>Archive a Connector by clicking on the “<b>Archive</b>” button on the bottom side of the drawer panel</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image22.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="3">
        <li>Remove a Connector by clicking on the “<b>Delete</b>” button on the bottom side of the drawer panel:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image23.png"
  - subparagraph_title: 'Connector Drawer Information'
    paragraph_content: 'Inside the drawer panel on the right of the screen, the same information shown in each Connector panel created is also displayed, as reported in paragraph <a href="/altilia-help-center/manual_index/connectors/#Connector_Drawer_Information">Connector Drawer Information</a>:
    <ul style="margin-left: 30px; list-style-type: circle">
      <li><b>Connector Type</b> - the connector direction,</li>
      <li><b>Connection Type</b> - the name of the connection type</li>
    </ul>'
    image: "manual_index/connectors/image24.png"
  - paragraph_title: 'Access into Connector'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the <b>Connectors Artifact</b>, access your Connector already created by clicking on the three dots icon in the upper right corner of desidered Connector panel and then on “<b>Go to Connector</b>”:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image25.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>The page you are redirected to is the <b>Overview Section</b> which is described in paragraph <a href="/altilia-help-center/manual_index/connectors/#Connector_Overview_Section">Connector Overview Section</a></li>
      </ol>
    </ul>'
  - paragraph_content: 'It’s also possible to access a Connector by <b>quick button</b> as described in paragraphs <a href="/altilia-help-center/manual_index/connectors/#Settings_Connectors">Settings Connectors</a> or from the <b>drawer panel</b> as shown in <a href="/altilia-help-center/manual_index/connectors/#Connector_Drawer_Functionality">Connector Drawer Functionality</a>.'
  - paragraph_title: 'Connector Overview Section'
    paragraph_content: 'In the <b>Connector Artifact</b> to the <b>Overview Section</b>, is reported the information of the selected Connector:
    <ul style="margin-left: 30px; list-style-type: circle">
      <li><b>Owner</b> - the username of the connector creator;</li>
      <li><b>Short Description</b> - the description you entered at the time of creation. If you want to change it, read the <a href="/altilia-help-center/manual_index/connectors/#Edit_Connector">Edit Connector</a> chapter;</li>
      <li><b>Connection Type</b> - the name of the connection type;</li>
      <li><b>Connector Type</b> - the connector direction;</li>
      <li><b>Folder</b> - the folder it is in.</li>
    </ul>'
    image: "manual_index/connectors/image26.png"
  - paragraph_title: 'Archive and Unarchive Connector'
    paragraph_content: 'It gives the ability to archive connector without deleting them in case you are unsure of their usability.
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the <b>Connector Module</b>, archive your Connector already created by clicking on the three dots at top right of its panel and then on “<b>Archive</b>”:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image27.png"
  - paragraph_content: 'It’s also possible to archive a Connector by <b>quick button</b> as described in paragraphs <a href="/altilia-help-center/manual_index/connectors/#Settings_Connectors">Settings Connectors</a> or from the <b>drawer panel</b> as shown in <a href="/altilia-help-center/manual_index/connectors/#Connector_Drawer_Functionality">Connector Drawer Functionality</a>.'
  - subparagraph_title: 'Unarchive Connector'
    paragraph_content: 'The number of archived Connectors are displayed at the top left of the current view as described in the paragraph <a href="/altilia-help-center/manual_index/connectors/#Status_Connector">Status Connector</a>.
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>To unarchive a Connector click on “<b>Archived</b>” at top left of the screen,</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image28.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>From here you can activate again the desired Connector by clicking on the unarchived icon at top right of its panel:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image29.png"
  - paragraph_title: 'Delete Connector'
    paragraph_content: 'Note that deleted Connector will no longer be recoverable. If you are unsure about deleting it, please archive it as described in the <a href="/altilia-help-center/manual_index/connectors/#Archive_and_Unarchive_Connector">Archive and Unarchive Connector</a> chapter:
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the <b>Connectors Module</b>, delete your Connector already created by clicking on the three dots at top right of its panel and then on “<b>Delete</b>”:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image30.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>A pop-up message appears on the screen requesting double confirmation. Click on “<b>Yes</b>” if you are sure to delete the selected Connector, otherwise click on “<b>No</b>”:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image31.png"
  - paragraph_content: 'It’s also possible to delete a Connector by <b>quick button</b> as described in paragraphs <a href="/altilia-help-center/manual_index/connectors/#Settings_Connectors">Settings Connectors</a> or from the <b>drawer panel</b> as shown in <a href="/altilia-help-center/manual_index/connectors/#Connector_Drawer_Functionality">Connector Drawer Functionality</a>, or as reported in <a href="/altilia-help-center/manual_index/connectors/#Delete_Connector_from_Artifact">Delete Connector from Artifact</a>.'
  - subparagraph_title: 'Delete Connector from Artifact'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>Inside the <b>Connector Artifact</b> on any Section, you are also able to delete the Connector by clicking on “<b>Delete</b>” button on top right of the screen</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image32.png"
  - paragraph_title: 'Status Connector'
    paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>In the <b>Connector Module</b> at the top left of the current view, a filter is available to display active and archived knowledge bases. In parentheses is the count of Connectors that are in that particular state. By default, the Connectors with “<b>Active</b>” status are shown:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image33.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>Show only the archived Connector by clicking on “<b>Archived</b>”:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image34.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="3">
        <li>Show all created Connector by clicking on “<b>All</b>”:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image35.png"
  - paragraph_title: 'Sorting Search and Filter Connector'
    paragraph_content: 'In the <b>Connectors Module</b>, sorting and search tools are available.'
    image: "manual_index/connectors/image36.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a">
        <li>By default, the “<b>Last Modified</b>” sorting is used but you can select also by “<b>Name</b>” or “<b>Author</b>”:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image37.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="2">
        <li>If you want to search directly for the name of a Connector then you can do it using the search tool:</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image38.png"
  - paragraph_content: '
    <ul style="margin-left: 30px;">
      <ol type="a" start="3">
        <li>Furthermore, a checkbox to filter the connectors “<b>Not configured</b>” is available</li>
      </ol>
    </ul>'
    image: "manual_index/connectors/image39.png"
---

