Automated solution to help in UiPath code documentation
<br><br>
	
<b>Challenge:</b> After development, the design and architecture of the solution need to be documented in solution design document (DSD). It is a difficult and time-consuming process to get workflow (xaml files) details like file name, description, variables, and arguments. This will be more difficult if the solution contains many files.<br><br>

<b>Solution:</b> This solution will provide an Excel file that contains basic information form project.json file, folder structure and all workflow details: file name, type, annotation, variables name and type, and arguments name and type.<br><br>

<b>Use cases:</b><br>
<b>1. Documenting DSD:</b> Solution Architects or developers need to create the solution design document. This solution will provide all the code files details that have to be added in DSD.<br>
<b>2. Reviewing the code:</b> The output of this solution will help QC team have an overview about the workflows so they can check and provide their comments for each workflow.<br><br>

<b>How to use it:</b><br>
1. Download the code and unzip it.<br>
2. Execute it and provide the code folder path where project.json is placed.<br>
3. Once the process finishes, check the files in DocumentationHelper folder (C:\Users\UserName\Documents\DocumentationHelper).
<br><br>

<b>Input:</b> UiPath Code Folder Path 
<br><br>
<b>Output: Excel file withfollowing details:</b><br>
	Project details<br>
	Folder Structure<br>
	xaml files details( file name, type, annotation, variables and arguments)<br>
