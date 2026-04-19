# DataSummit2026

Workshop 3: From Strategy to Structure: Accelerating Business Impact Through Hands-on Data Modeling -- instructions

## 1. License validation
Hackolade Studio trial license key **BJRK0-N0300-GH144-182BM-2P8QF-1AH4R-4S28D-IBCJ8E53** is valid through May 21, 2026.  Follow the steps below:

1) go to <a href="https://studio.hackolade.com" target="_blank" rel="noopener noreferrer">https://studio.hackolade.com</a> (Use Ctrl/Cmd+click to open in a new tab)
2) click the Accept button for the License Agreement, then click the Close button to bypass the Overview slides
3) go to the menu option Help > License Status (or click the key icon in the bottom left of the browser tab
4) paste the license key **BJRK0-N0300-GH144-182BM-2P8QF-1AH4R-4S28D-IBCJ8E53**
5) enter some identifier that you can recognize -- **note** that, for privacy reasons, it is not required for this identifier to be your name or email address
6) click the Validate button

Getting Started videos are available on our <a href="https://community.hackolade.com/slides/hackolade-studio-tutorial-0-vision-getting-started-6" target="_blank" rel="noopener noreferrer">eLearning platform</a>  (Use Ctrl/Cmd+click to open in a new tab)

This browser-based data modeling solution is highly secure.  See more information about the security-first architecture in our <a href="https://hackolade.com/help/Security-firstbrowserdeployment.html" target="_blank" rel="noopener noreferrer">online documentation</a>  (Use Ctrl/Cmd+click to open in a new tab)

## 2. Repository connection
In order to access files prepared in our repository, you must create a connection to your repo:

1) go to the menu option Repository > Repository Connections (last option in the menu)
2) paste the access token published in <a href="https://hackoladestudio-my.sharepoint.com/:w:/g/personal/pascal_desmarets_hackolade_com/IQCLU6CwcmGGTbt-0oAJz1lSAVp1pVcWUsqimFD3lxMw4C4?e=wLVdAO" target="_blank" rel="noopener noreferrer">this document</a> (Use Ctrl/Cmd+click to open in a new tab)
3) click the Connect button, then close the dialog.

## 3. Adjust parameter to facilitate operations with repo
1) go to Tools > Options
2) in the General tab, first line, choose GitHub from the dropdown list
<img width="864" height="221" alt="image" src="https://github.com/user-attachments/assets/d81d4ad9-c38e-4719-83ab-d9002df0c5e8" />

3) click the OK button

## 4. Prompt your prefered GenAI tool
1) go to https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/prompt.md
2) copy the proposed prompt
3) paste in your prefered GenAI tool

## 5. Generate ERD in Hackolade Studio
1) copy the output from your GenAI tool, or copy from 
   1) Conceptual https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/retailco_from_reqs_doc%20-%20conceptual.dbml
   2) Logical https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/retailco_from_reqs_doc%20-%20logical.dbml
   3) Physical https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/retailco_from_reqs_doc%20-%20physical.dbml

2) open the prepared empty model DataSummit2026 Polyglot model.hck.json from the GitHub repository with this link **<u>TBA</u>**
   (Use Ctrl/Cmd+click to open in a new tab)
3) go to Tools > Reverse-Engineer > Diagram > DBML...
  <img width="678" height="356" alt="image" src="https://github.com/user-attachments/assets/94e62495-8630-4392-b346-260a093ec589" />

4) choose Clipboard in the left menu
  <img width="378" height="238" alt="image" src="https://github.com/user-attachments/assets/b0ee56df-74d7-40cd-b030-aa0b5421edc3" />

5) the copied code from the GenAI output should appear
  <img width="1905" height="1168" alt="image" src="https://github.com/user-attachments/assets/e4c24e8f-5122-458e-90bf-f4cd5f386da5" />

6) click the Open button at the bottom right of the dialog
7) after a few seconds, the progress dialog should give you this kind of information:
  <img width="741" height="592" alt="image" src="https://github.com/user-attachments/assets/39c086bb-8d05-4a3c-8cf2-b91a7d6e388e" />

8) after clicking the OK button, you should see the ERD result
  <img width="1918" height="891" alt="image" src="https://github.com/user-attachments/assets/d5ea0559-01a6-455a-bc5e-20803ae947ba" />

## 6. Save your work in a new branch on the repository
1) click the save icon in the toolbar (or go to File > Save...)
2) enter a commit message (meaningful but not too long), select to create a new branch with a name without spaces (safe set is lowercase alphanumeric characters and hyphens)
<img width="810" height="373" alt="image" src="https://github.com/user-attachments/assets/c6cdfc87-415b-42d3-929d-f21864f0d772" />

## 7. (optional) share the URL hyperlink to your model
1) click the link icon in the toolbar (or go to File > Share Data Model Link...)
<img width="793" height="287" alt="image" src="https://github.com/user-attachments/assets/d3cc67c4-e48d-4320-aa1e-e8cfa88abd1b" />

2) click the Copy button
3) you can now send this link in Slack, Teams, email, or put it in a Confluence page, portal, etc...
**Note:** be aware of the branch in your link.  A branch is typically ephemeral, whereas the main branch is persistent.  While it is useful to share a model link in a branch as you collaborate on a new feature, in a portal, you probably want to store a the lin too the main branch to show always the latest approved version.

## 8. Bind model attributes with glossary terms
1) search for the word mineral in the Object Browser Find box
<img width="359" height="396" alt="image" src="https://github.com/user-attachments/assets/d38eb77d-1d3f-4cec-bd29-00ecbfd6443c" />

2) click on the Mineral Entity to focus the ERD on that entity, and click on the mineral_id attribute
<img width="293" height="150" alt="image" src="https://github.com/user-attachments/assets/f4da0213-ebd7-4624-af88-55afefaeaf84" />

3) in the Properties Pane on the Right, click on the + sign next to Glossary terms label
<img width="438" height="301" alt="image" src="https://github.com/user-attachments/assets/106b3040-1862-4b31-afd8-1daf7978d197" />

4) the model was previously set up with the 2 glossaries for this workshop.  Filter by typing the word mineral and select the proper term for this attribute, then click the Apply button
<img width="1911" height="1101" alt="image" src="https://github.com/user-attachments/assets/9797c6b0-8bf5-4027-a8f9-2ebfba0d1091" />

5) the binding is now performed
<img width="412" height="309" alt="image" src="https://github.com/user-attachments/assets/070bc8b4-5a8e-4749-b969-15ae0698be26" />

6) you can repeat steps 3 and 4 to also assign the identifier term
<img width="421" height="354" alt="image" src="https://github.com/user-attachments/assets/bc09d465-c0d9-4b36-a4ce-d00d0639b7b6" />

7) you can now repeat these steps for another attribute, for example mineral_name
<img width="397" height="344" alt="image" src="https://github.com/user-attachments/assets/7280851a-aea2-4d8f-befc-28a3b9d7a62a" />

8) you may now save your work using instructions in section 6 above.  While you could do that to a new branch, we suggest that you do it to the same branch as used in section 6
<img width="805" height="370" alt="image" src="https://github.com/user-attachments/assets/32eecf37-cf47-4c0c-8acd-287be0078d9c" />







