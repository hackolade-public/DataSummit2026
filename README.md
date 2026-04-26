# DataSummit2026

Workshop 3: From Strategy to Structure: Accelerating Business Impact Through Hands-on Data Modeling -- instructions

Full instructions in <a href="https://hackoladestudio-my.sharepoint.com/:w:/g/personal/pascal_desmarets_hackolade_com/IQAOm_bT4B8CRoPWIv9oDiD6AaPDCFGPp1ug4hM11XTyc_0?rtime=RSQxB6mi3kg" target="_blank" rel="noopener noreferrer">this document</a> (Use Ctrl/Cmd+click to open in a new tab)



# Setup

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
2) paste the access token published in in <a href="https://hackoladestudio-my.sharepoint.com/:w:/g/personal/pascal_desmarets_hackolade_com/IQAOm_bT4B8CRoPWIv9oDiD6AaPDCFGPp1ug4hM11XTyc_0?rtime=RSQxB6mi3kg" target="_blank" rel="noopener noreferrer">this document</a> (Use Ctrl/Cmd+click to open in a new tab)
3) click the Connect button, then close the dialog.

## 3. Adjust parameter to facilitate operations with repo
1) go to Tools > Options
2) in the General tab, first line, choose GitHub from the dropdown list
    <img width="864" height="221" alt="image" src="https://github.com/user-attachments/assets/d81d4ad9-c38e-4719-83ab-d9002df0c5e8" />

3) click the OK button



# Workshop

## 1. Prompt your preferred GenAI tool
1) go to https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/prompt.md
2) copy the proposed prompt
3) paste in your preferred GenAI tool

## 2. Generate ERD in Hackolade Studio
1) copy the output from your GenAI tool, or copy from 
   1) Conceptual https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/retailco_from_reqs_doc%20-%20conceptual.dbml
   2) Logical https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/retailco_from_reqs_doc%20-%20logical.dbml
   3) Physical https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/retailco_from_reqs_doc%20-%20physical.dbml

2) go to [Studio](https://studio.hackolade.com) and create a new Polyglot model
3) go to Tools > Reverse-Engineer > Diagram > DBML...
   <img width="917" height="538" alt="image" src="https://github.com/user-attachments/assets/30f47f36-302b-4f1a-9397-6b35a2126675" />


4) choose Clipboard in the left menu
    <img width="526" height="255" alt="image" src="https://github.com/user-attachments/assets/a98ae37b-996a-4f1a-85f1-49271e7dd1e7" />


5) the copied code from the GenAI output should appear
   <img width="1167" height="730" alt="image" src="https://github.com/user-attachments/assets/99e7e472-3716-4d9b-a0e1-6d339c22060b" />


6) click the Open button at the bottom right of the dialog
7) after a few seconds, the progress dialog should give you this kind of information:
   <img width="738" height="425" alt="image" src="https://github.com/user-attachments/assets/44c5683b-1daf-43a3-a37e-2c8ccd42a6e8" />


8) after clicking the OK button, you should see the ERD result, in the Graph Diagram tab for the conceptual model for example
   <img width="937" height="822" alt="image" src="https://github.com/user-attachments/assets/3ab0974c-fa03-490b-8e87-777059817b5c" />



9. Alternatively, you can open the prepared empty models from the GitHub repository
    \- conceptual [RetailCo - conceptual.hck.json](https://studio.hackolade.com/?g=github&o=hackolade-public&r=DataSummit2026&f=models%2FRetailCo+-+conceptual.hck.json&b=main) (Use Ctrl/Cmd+click to open in a new tab)
    \- logical [RetailCo - logical.hck.json](https://studio.hackolade.com/?g=github&o=hackolade-public&r=DataSummit2026&f=models%2FRetailCo+-+logical.hck.json&b=main) (Use Ctrl/Cmd+click to open in a new tab)
    \- physical Snowflake [RetailCo - physical.hck.json](https://studio.hackolade.com/?g=github&o=hackolade-public&r=DataSummit2026&f=models%2FRetailCo+-+physical.hck.json&b=main) (Use Ctrl/Cmd+click to open in a new tab)



## **3. Make changes to your model**

1. search for the word Category in the Object Browser Find box
   <img width="362" height="345" alt="image" src="https://github.com/user-attachments/assets/59c11b7c-3e8a-4031-831c-a9411531a87c" />

2. click on the Category entity to focus the ERD on that entity
   <img width="198" height="234" alt="image" src="https://github.com/user-attachments/assets/3a27c512-1cf9-46d4-9594-7b994bbfdaa7" />

3. in the Properties Pane on the Right, click on the + sign next to Glossary terms label
    <img width="411" height="251" alt="image" src="https://github.com/user-attachments/assets/0bd6aa5b-a24b-4efe-8c7f-e2e5fb6a027f" />

4. the model was previously set up with the glossaries for this workshop.  Filter by typing the word Category and select the proper term for this attribute, then click the Apply button
    <img width="1913" height="444" alt="image" src="https://github.com/user-attachments/assets/b6e81d07-0dca-4cf0-9113-4e6bd4080d47" />

5. the binding is now performed
    <img width="409" height="280" alt="image" src="https://github.com/user-attachments/assets/0e9182fc-87ed-438b-bca5-66dbe3b486c8" />

6. you can repeat steps 3 and 4 to also assign additional terms


## 4. Save your work in a new branch on the repository

1) click the save icon in the toolbar (or go to File > Save...)
2) enter a commit message (meaningful but not too long), select to create a new branch with a name without spaces (safe set is lowercase alphanumeric characters and hyphens)
<img width="810" height="373" alt="image" src="https://github.com/user-attachments/assets/c6cdfc87-415b-42d3-929d-f21864f0d772" />

## 5. (optional) share the URL hyperlink to your model
1) click the link icon in the toolbar (or go to File > Share Data Model Link...)
<img width="800" height="283" alt="image" src="https://github.com/user-attachments/assets/d558658a-ecd6-4746-b5b0-2c95b7b1949b" />

2) click the Copy button
3) you can now send this link in Slack, Teams, email, or put it in a Confluence page, portal, etc...
**Note:** be aware of the branch in your link.  A branch is typically ephemeral, whereas the main branch is persistent.  While it is useful to share a model link in a branch as you collaborate on a new feature, in a portal, you probably want to store the link too the main branch to show always the latest approved version.











