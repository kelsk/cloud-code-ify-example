# Example Tutorial

## Introduction

This tutorial shows how to _insert what tutorial does_.

The first card in a Neos tutorial should describe the contents of the sample and the learning goals of the tutorial.

By the end of this tutorial, you will understand how to

1. _first learning point_
2. _second learning point_

Let's get started!

## Step 1: Begin

Start by making a change to the code.

1. Write a new message by replacing the text on line 14 in <walkthrough-editor-select-line filePath="./src/index.js" startLine="13" startCharacterOffset="11" endLine="13" endCharacterOffset="26">src/index.js</walkthrough-editor-select-line>.

2. Click the <walkthrough-editor-spotlight spotlightId="cloud-code-status-bar">Cloud Code status bar</walkthrough-editor-spotlight>. Look at all those commands!

Next, let's run this app.


## Step 2: The Sequel to Step 1

Let's run your app locally on **minikube**.

1. Select <walkthrough-editor-spotlight spotlightId="cloud-code-run-on-k8s">Run on Kubernetes</walkthrough-editor-spotlight>

2. Monitor your app's deployment in the <walkthrough-editor-spotlight spotlightId="output">Output</walkthrough-editor-spotlight>.
- You can manage the status of your minikube cluster using the <walkthrough-editor-spotlight spotlightId="minikube-status-bar">minikube status bar</walkthrough-editor-spotlight>

3. Once your app is deployed, click on the <walkthrough-spotlight-pointer spotlightId="devshell-web-preview-button" target="cloudshell">Web Preview button</walkthrough-spotlight-pointer> in the upper right of the editor window.


## Congratulations

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>
You did it!
<walkthrough-inline-feedback></walkthrough-inline-feedback>

**Don't forget to clean up after yourself**: If you created test projects, be sure to delete them to avoid unnecessary charges. 

Use 
```bash
gcloud projects delete {{PROJECT_ID}}
```
