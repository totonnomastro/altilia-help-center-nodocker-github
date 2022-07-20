---
layout: subpage
title: 'Creating, Configuring, Curating, and Managing Datasets '
description: 'not used'
date:   2022-06-07 11:46:41 -0300
categories: start blog
by: 'Altilia Service'
icon: 'user-check'
parent: 'Manual Index'
paragraphs:
- paragraph_content: 'Datasets are required to train the machine learning models. Using the Dataset Artifact, the users can select documents that form the dataset and then     proceed with their annotation using Altilia Labels™. It defines the labels to be recognized in the documents as attributes of semantic objects organized in taxonomies and ontologies. The user then uses the labels to annotate the documents in order to create the annotated datasets.
    <br><br>
    <ul style="margin-left: 30px;">
    <ol type="a">
        <li>You can recognize that you are in the Dataset view and in which of them you are working, by the indication provided in the header at the top left of the screen:</li>
    </ol>
    </ul>
  '
- image: "manual_index/dataset/image1.png"
- paragraph_title: 'Before you Start'
- paragraph_content: 'Make sure you:
<ul style="margin-left: 30px;">
    <ol type="1" start="2">
      <li>are logged into the platform, otherwise read chapter <a href="/altilia-help-center/manual_index/account_setup/">Account Setup with Altilia Intelligent Automation™</a> first;</li>
      <li>have created a Project as described in the chapter <a href="/altilia-help-center/manual_index/project/">Creating and Managing Project</a>;</li>
      <li>have created a Knowledge Base as described in the chapter <a href="/altilia-help-center/manual_index/knowledgebases/">Creating and Managing Knowledge Base</a>.</li>
    </ol>
  </ul>'
- paragraph_title: 'Create Dataset'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>In the Altilia Intelligent Automation™ app, click <b>“Dataset”</b> on the left navigation bar. The <b>Dataset Module</b> opens.</li>
      <li>Create a new dataset by clicking on <b>"+ New Dataset"</b>:</li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image2.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Type name, description (optional), a knowledge base previously created and then click on <b>“Create”</b>.</li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image3.png"
- paragraph_content: 'Your Dataset is now saved. At the same time a pop-up message is displayed on the screen asking you if you want immediately to be redirected to the settings page of the newly created Dataset. In this case click on <b>“Yes”</b> otherwise you can postpone it to a later time (by clicking <b>“No”</b>) and then access to the settings page as described in the paragraph <a href="/altilia-help-center/manual_index/dataset/#Access_into_Dataset">Access into Dataset</a>.'
- image: "manual_index/dataset/image4.png"
- subparagraph_title: 'Dataset Information'
- paragraph_content: 'Your Datasets are available in the <b>Dataset Artifact</b> of your Project, you can use the sorting and searching functionality to find it as described in the paragraph <a href="/altilia-help-center/manual_index/dataset/#Sorting_and_Search_Datasets">Sorting and Search Datasets</a>:'
- image: "manual_index/dataset/image5.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="1" >
      <li>Inside a Dataset panel, several information regarding the created Datasets are shown. You find here, the same information that you can find in the drawer panel as described in the paragraph <a href="/altilia-help-center/manual_index/dataset/#Dataset_Drawer_Information">Dataset Drawer Information</a>. From the top to the bottom at the left side of the panel you can find:
      </li>
        <ul style="margin-left: 30px; list-style-type: circle">
            <li><b>Dataset Name</b>: also clickable to edit it as described in <a href="/altilia-help-center/manual_index/dataset/#Edit_Dataset">Edit Dataset</a>,</li>
            <li><b>Knowledge Base</b>: name of the associated Knowledge Base,</li>
        </ul>
      <li>Also within the Dataset panel, you can also find other two features at the upper right corner side, read also more about them in the paragraph <a href="/altilia-help-center/manual_index/dataset/#Dataset_Settings">Dataset Settings</a>:
      </li>
        <ul style="margin-left: 30px; list-style-type: circle">
            <li><b>Quick button</b>: interchangeable button with other functions that you can set,</li>
            <li><b>Three dots</b>: to access, delete and archive the Dataset.</li>
        </ul>
      <li>Lastly, at the bottom right corner side is reported:</li>
        <ul style="margin-left: 30px; list-style-type: circle">
            <li>Number of <b>labels</b>, <b>documents</b> and <b>annotations</b> that compose your Dataset;</li>
            <li>Number of Dataset <b>version</b>, read more about it in the paragraph <a href="/altilia-help-center/manual_index/dataset/#Publish_Dataset">Publish Dataset</a>.</li>
        </ul>
    </ol>
  </ul>'
- image: "manual_index/dataset/image6.png"
- subparagraph_title: 'Assign Documents To Dataset'
- paragraph_content: 'In the <b>Documents Section</b> of the <b>Dataset Module</b>, assign the files of the selected Knowledge Base to the Dataset.<br><br>
<ul style="margin-left: 30px;">
  <ol type="a">
    <li>tick the checkbox corresponding to the desired documents and click <b>“Assign”</b> to add the candidate documents to the Dataset:</li>
  </ol>
</ul>'
- image: "manual_index/dataset/image7.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
  <ol type="a" start="2">
    <li>The documents are now shown on the right of the screen into <b>“DS Candidates”</b> panel when you can also find following informations:</li>
        <ul style="margin-left: 30px; list-style-type: circle">
            <li><b>Status</b> – if the document is annotated or not</li>
            <li><b>Annotations</b> – the annotations number</li>
            <li><b>Last Edit</b> – date of last annotation changes </li>
        </ul>
  </ol>
</ul>'
- image: "manual_index/dataset/image8.png"
- paragraph_content: 'Once the documents are added to the Dataset, the annotations can be added as described into <a href="/altilia-help-center/manual_index/dataset/#Altilia_Labels">Altilia Labels</a> chapter.<br><br>
For a huge number of documents, get help from the Filters panel to the right of the current view by filtering by uploaded date or filename that is automatically shown to you:'
- image: "manual_index/dataset/image9.png"
- paragraph_title: 'Altilia Labels'
- paragraph_content: 'Provide you the capability to create annotations that form the dataset. Find out how easy it is to annotate documents using point-and-click actions in order to create training sets for AI models using LabellingStudio™. This feature facilitates the transfer of the typical skills of business users and domain experts into the AI models needed for automatic document reading. This minimizes the intervention required in the creation of the datasets for machine learning experts with a consequent reduction of time and costs in the development and maintenance of AI models. The annotation can take place through manual actions supported by auto labeling and weak supervision techniques that facilitate even more the construction of training sets. Currently it allows annotation for three different types of task: classification, entity extraction, and object extraction.
<ul style="margin-left: 30px;">
  <ol type="a">
    <li>In the <b>Dataset Module</b>, open Altilia Labels by clicking on the related icon of the desired Dataset at top right of same panel:</li>
  </ol>
</ul>'
- image: "manual_index/dataset/image10.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
  <ol type="a" start="2">
    <li>It’s also reachable by clicking the <b>“Annotate”</b> button on top right of the screen of each section of the Dataset Module. </li>
  </ol>
</ul>'
- image: "manual_index/dataset/image11.png"
- subparagraph_title: 'Create Annotations'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>In <b>Altilia Labels</b> of the <b>Dataset Module</b> create your annotations for each document. The first document is automatically selected at the left navigation panel in the Documents section. By clicking on <b>“Labels”</b> in the same panel, start annotating. </li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image12.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>You can annotate at document or page level, select it from the navigation bar at right of the current view by clicking respectively <b>“Document annotations”</b> or <b>“Page annotations”</b>:</li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image13.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Create your elements by clicking on <b>“New Element”</b>:</li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image14.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="4">
      <li>Complete the entity creation by selecting the task type (Classification, Entity or Object, Page Classification, Document Classification), typing the name and clicking on <b>“Create”</b>:</li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image15.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="5">
      <li>Now create your labels contained in a specific label already created by clicking on <b>“New Label”</b></li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image16.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="6">
      <li>Add a new labels by selecting the color, typing the name and clicking on <b>“Create”</b>:</li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image17.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="7">
      <li>Create a new annotation by clicking on the new label just created in the left navigation panel and highlighting the corresponding word within the document in the box in the center of the screen:</li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image18.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="8">
      <li>Continue to create elements and labels as just described, also selecting the other documents, then click on <b>“Done”</b> when you finish. The state of the page then change from <b>“Annotation”</b> to <b>“Annotated”</b>:</li>
    </ol>
  </ul>'
- image: "manual_index/dataset/image19.png"
- paragraph_content: 'All annotations are graphically shown on the Overview Section of current module as described in the paragraph <a href="/altilia-help-center/manual_index/dataset/#Access_into_Dataset">Access into Dataset</a>.'
- subparagraph_title: 'Delete Annotation'
- paragraph_content: 'In <b>Altilia Labels</b> of the <b>Dataset Module</b> delete your annotations by clicking on the trash icon at top right of the panel that appears clicking on an annotation.'
- image: "manual_index/dataset/image20.png"
- subparagraph_title: 'Exit from Altilia Labels'
- paragraph_content: 'Make sure you saved your annotations by clicking on <b>“Done”</b> at top right of the screen and then exit from <b>Altilia Labels</b> by clicking on the arrow at top left of the screen:'
- image: "manual_index/dataset/image21.png"
- subparagraph_title: 'Altilia Reviews'
- paragraph_content: 'Altilia Reviews allows the users can review and validate data extracted by workflow in a very accurate way accessing specific documents or groups of documents where data extractions show accuracy level under a given threshold.
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>In the <b>Dataset Module</b>, open <b>Reviews™</b> by clicking on the three dots and the related icon of the desired Dataset at top right of same panel:</li>
    </ol>
</ul>'
- image: "manual_index/dataset/image22.png"
- subparagraph_title: 'Validate Labels'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>In <b>Altilia Reviews</b> of the <b>Dataset Module</b> validate your annotations for each document. The first document is automatically selected at the left navigation panel in the Documents section. By clicking on <b>“Labels”</b> in the same panel it’s possible to review the annotations for: classification, entity and object. </li>
      <li>Click on the single annotation in the central panel and give a feedback by clicking on like or unlike icons at bottom of the panel that appears clicking on the annotation:</li>
    </ol>
</ul>'
- image: "manual_index/dataset/image23.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Click on <b>“Done”</b> at top right when you end to validate. The state of the document change from <b>“Validating”</b> to <b>“Validated”</b>:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image24.png"
- paragraph_title: 'Dataset Settings'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" >
      <li>In the <b>Dataset Artifact</b>, set the <b>quick button</b> of your Dataset panel so that the most frequently used icon appears to you by clicking on the three dots icon in the upper right corner of desired Dataset panel.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image25.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>Pin the desidered icon in order to see it next to the left of the three dots icon. By default it’s set to <b>“Annotate”</b>, read more about it on the paragraph <a href="/altilia-help-center/manual_index/dataset/#Altilia_Labels">Altilia Labels</a>.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image26.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Click the pin icon to the right of <b>“Validate”</b> to set it as a quick button for each Dataset, read more about it on the paragraph <a href="/altilia-help-center/manual_index/dataset/#Altilia_Reviews">Altilia Reviews</a>.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image27.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="4">
      <li>Click the pin icon to the right of <b>“Archive”</b> to set it as a quick button for each Dataset, read more about it on the paragraph <a href="/altilia-help-center/manual_index/dataset/#Archive_and_Unarchive_Dataset">Archive and Unarchive Dataset</a>.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image28.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="5">
      <li>Click the pin icon to the right of <b>“Delete”</b> to set it as a quick button for each Dataset, read more about it on the paragraph <a href="/altilia-help-center/manual_index/dataset/#Delete_Dataset">Delete Dataset</a>.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image29.png"
- subparagraph_title: 'Edit Dataset'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" >
      <li>In the <b>Dataset Module</b>, edit your Dataset already created by clicking on its panel:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image30.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>The <b>drawer panel</b> opens at the right of the screen enabling you to change name and description of the Dataset:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image31.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Overwrite them and click anywhere on the screen outside the drawer panel to apply the changes. A pop-up message is displayed as confirmation:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image32.png"
- subparagraph_title: 'Dataset Drawer Functionality'
- paragraph_content: 'From the <b>drawer</b> it’s also possible to use some features designed to speed up the navigation in the platform. 
<ul style="margin-left: 30px;">
    <ol type="a" >
      <li>Access in a Dataset by clicking on the <b>“Details”</b> button on the bottom side of the drawer panel:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image33.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>Archive a Dataset by clicking on the <b>“Archive”</b> button on the bottom side of the drawer panel.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image34.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Remove a Dataset by clicking on the <b>“Delete”</b> button on the bottom side of the drawer panel.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image35.png"
- subparagraph_title: 'Dataset Drawer Information'
- paragraph_content: 'Inside the drawer panel on the right of the screen, is reported the name of the used Knowledge Base:
<ul style="margin-left: 30px; list-style-type: circle">
      <li><b>Knowledge Base</b> – the Knowledge Base name</li> 
</ul>'
- image: "manual_index/dataset/image36.png"
- paragraph_title: 'Access into Dataset'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" >
      <li>In the <b>Dataset Module</b>, access your Dataset by clicking on it and then on the “Details” button at the bottom of the right drawer.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image37.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>The page you are redirected to is the <b>Overview Section</b> which is described in paragraph <a href="/altilia-help-center/manual_index/dataset/#Dataset_Overview_Section">Dataset Overview Section</a>.</li>      
    </ol>
</ul>'
- paragraph_title: 'Dataset Overview Section'
- paragraph_content: 'In the <b>Overview Section</b> of <b>Dataset Artifact</b>, review the details of the created Dataset.'
- image: "manual_index/dataset/image38.png"
- subparagraph_title: 'Dataset Overview Information'
- paragraph_content: 'Below is the information of the selected Dataset:
<ul style="margin-left: 30px;">
    <ol type="a" >
      <li><b>Owner</b> - the username of the dataset creator.</li>
      <li><b>Documents</b> – number of documents of the associated Knowledge Base.</li>
      <li><b>Label</b> – total labels number assigned to your documents.</li>
      <li><b>Annotation</b> - total annotations number highlighted to your documents.</li>
      <li><b>Version</b> – number of version of your Dataset.</li>
    </ol>
</ul>'
- image: "manual_index/dataset/image39.png"
- subparagraph_title: 'Dataset Overview Pie Chart'
- paragraph_content: 'An useful interactive pie chart shows the number of documents of the selected Dataset that are annotated, annotating or not annotate, so that you have a graphical perspective: '
- image: "manual_index/dataset/image40.png"
- subparagraph_title: 'Dataset Overview Labels Chart'
- paragraph_content: 'In the bottom of the page is shown a chart where you can see annotations that have been created on Altilia Labels as described in the chapter <a href="/altilia-help-center/manual_index/dataset/#Altilia_Labels">Altilia Labels</a>.'
- image: "manual_index/dataset/image41.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" >
      <li>Select the <b>Elements</b> you want inspect by clicking on the arrow of the scroll down menù at upper left of the chart:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image42.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>The <b>Labels</b> of the selected Element are shown on the right of the chart for each one, the number of the annotations are shown on the left.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image43.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Furthermore, you can click on the Labels bars to be redirected to Altilia Labels:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image44.png"
- paragraph_title: 'Archive and Unarchive Dataset'
- paragraph_content: 'It gives the ability to archive datasets without deleting them in case you are unsure of their usability.  <br><br>
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>In the <b>Dataset Artifact</b>, archive your dataset already created by clicking on the three dots at top right of the desired dataset panel and then on <b>“Archive”</b>.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image45.png"
- paragraph_content: 'It’s also possible to archive a Dataset by <b>quick button</b> as described in paragraphs <a href="/altilia-help-center/manual_index/dataset/#Dataset_Settings">Dataset Settings</a> or from the drawer panel as shown in <a href="/altilia-help-center/manual_index/dataset/#Dataset_Drawer_Functionality">Dataset Drawer Functionality</a>.'
- subparagraph_title: 'Unarchive Dataset'
- paragraph_content: 'The number of archived Dataset are displayed at the top left of the current view as described in the paragraph <a href="/altilia-help-center/manual_index/dataset/#Dataset_Status">Dataset Status</a><br>.
<ul style="margin-left: 30px;">
    <ol type="a" >
      <li>To unarchive a Dataset click on <b>“Archived”</b> at top left of the screen,</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image46.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>From here you can activate again the desired Dataset by clicking on the unarchived icon at top right of its panel.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image47.png"
- subparagraph_title: 'Delete Dataset'
- paragraph_content: 'Note that deleted Dataset will no longer be recoverable. If you are unsure about deleting it, please archive it as described in the <a href="/altilia-help-center/manual_index/dataset/#Archive_and_Unarchive_Dataset">Archive and Unarchive Dataset</a> chapter. <br> <br> 
<ul style="margin-left: 30px;">
    <ol type="a" >
      <li>In the Datasets Module, delete your Dataset already created by clicking on the three dots at top right of its panel and then on “Delete”.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image48.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>A pop-up message appears on the screen requesting double confirmation. Click on <b>“Yes”</b> if you are sure to delete the selected Knowledge Base, otherwise click on <b>“No”</b>.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image49.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>A pop-up message appears to you to confirm the deletion:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image50.png"
- paragraph_content: '
It’s also possible to archive a Dataset by <b>quick button</b> as described in paragraphs <a href="/altilia-help-center/manual_index/dataset/#Dataset Settings">Dataset_Settings</a>  or from the <b>drawer panel</b> as shown in <a href="/altilia-help-center/manual_index/dataset/#Dataset_Drawer_Functionality">Dataset Drawer Functionality</a>, or as reported in <a href="/altilia-help-center/manual_index/dataset/#Delete_Dataset_from_Artifact">Delete Dataset from Artifact</a>. '
- subparagraph_title: 'Delete Dataset from Artifact'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>Inside the <b>Dataset Artifact</b> on any Section, you are also able to delete the Dataset by clicking on <b>“Delete”</b> button on top right of the screen:  </li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image51.png"
- paragraph_content: 'Inside the <b>Dataset Artifact</b> on any Section, you are also able to delete the Dataset by clicking on <b>“Delete”</b> button on top right of the screen:  '
- image: "manual_index/dataset/image52.png"
- paragraph_title: 'Export Dataset'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>In the <b>Dataset Artifact</b> in any section, export your Dataset by clicking the <b>“Export”</b> button on the header at top right of the current view:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image53.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>A window opens asking you to select <b>Level</b> and <b>Type</b> of the export: </li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image54.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Select the data level you want export between: </li>
        <ul style="margin-left: 30px; list-style-type: circle">
            <li><b>COMPLETE</b>: data and documents</li>
            <li><b>INTERMEDIATE</b>: data with link to documents</li>
            <li><b>MINIMAL</b>: data only</li>
        </ul>
        <li>Choose the type of file extension between ALTILIA custom format or other machine learning formats like: COCO or YOLO. </li>
        <li>Click the <b>“Export”</b> button at the end to download the Dataset locally:</li>   
    </ol>
</ul>'
- image: "manual_index/dataset/image55.png"
- paragraph_title: 'Publish Dataset'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>In the <b>Dataset Artifact</b>, inside a selected Dataset, publish a new version of your Dataset by clicking on the <b>“Publish”</b> button.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image56.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>A windows appears asking you the new name version, enter it and click on <b>“Publish”</b>:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image57.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>A pop-up message confirms that the publication worked correctly, also you can see the new version in the Dataset Overview:</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image58.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="4">
      <li>In case you want to restore the previous version, click on the three dots at right of the version and then on <b>“restore into current”</b>.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image60.png"
- paragraph_title: 'Dataset Status'
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>In the <b>Datasets Artifact</b> at the top left of the current view, a filter is available to display active and archived dataset. In parentheses is the count of datasets that are in that particular state. By default, the datasets with <b>“Active”</b> status are shown.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image61.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>Show only the archived datasets by clicking on <b>“Archived”</b></li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image62.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="3">
      <li>Show all created datasets by clicking on <b>“All”</b></li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image63.png"
- paragraph_title: 'Sorting and Search Datasets'
- paragraph_content: 'In the <b>Datasets Module</b>, sorting and search tools are available.'
- image: "manual_index/dataset/image64.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a">
      <li>By default, the <b>“Last Modified”</b> sorting is used but you can select also by <b>“Name”</b> or <b>“Author”</b></li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image65.png"
- paragraph_content: '
<ul style="margin-left: 30px;">
    <ol type="a" start="2">
      <li>Furthermore, if you want to search directly for the name of a Dataset then you can do it using the search tool.</li>      
    </ol>
</ul>'
- image: "manual_index/dataset/image66.png"

---