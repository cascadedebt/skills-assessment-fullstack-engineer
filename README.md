<p align="center">
  <img src='https://ucarecdn.com/b23cdfa3-9e8d-4799-aa9b-6c9af94f2d67/' alt="Cascade Debt" width=350px/>
  <br><br>
</p>

# Skill Assessment: Full-Stack Engineer

## Background

:clap: A sincere congratulations on progressing your candidacy for the Full-Stack Engineer role at Cascade Debt! This role is essential for building and integrating how users interact with their own data artifacts. Your duties will largely cover design, implementation, and development of Cascade's UI and API. As such, we'd love for you to show off your front-end and dev-ops skillsets to us! :sunglasses:

For this assessment, you will create a simple React app addressing the problem outlined below - your work should be offered as a zipped up solution - described in further detail at the end of this page.

---

## Problem: Word Memory

<table>
  <tr>
    <td> <img src="https://i0.wp.com/mcusercontent.com/21ab45285a43248c52473f8e6/images/da4b7c04-027b-4033-a2d3-68c372c94299.jpeg" alt="Memory Match" width=150px/></td>
    <td width=450px> 
        A popular children's game is "Memory" - in which the player needs to find matching visual cards. Your task today is an homage to this game - instead of matching pictures, you'll match words!
    </td>
  </tr>
</table>

We've been contracted to build a language training app for people learning French.

1. Name your app - give it a nice little splash page with a "GO!" button. 

2. After pressing "GO!", change the state of the button to "GRADE" (see steps below for its purpose). 

3. Also, after pressing "GO!", your app must scramble the following key-value pairs: 
  <table align='center'>
    <tr>
        <th> English Word </th><th> French Word </th>
    </tr><tr>
        <td>forest</td><td>forêt</td>
    </tr><tr>
        <td>sibling</td><td>frère et sœur</td>
    </tr><tr>
        <td>cereal</td><td>céréale</td>
    </tr><tr>
        <td>desk</td><td>bureau</td>
    </tr><tr>
        <td>camel</td><td>chameau</td>
    </tr><tr>
        <td>butter</td><td>beurre</td>
    </tr><tr>
        <td>bicycle</td><td>vélo</td>
    </tr><tr>
        <td>railroad</td><td>chemin de fer</td>
    </tr><tr>
        <td>folder</td><td>dossier</td>
    </tr><tr>
        <td>weekly</td><td>hebdomadaire</td>
    </tr><tr>
        <td>hungry</td><td>faim</td>
    </tr><tr>
        <td>limestone</td><td>calcaire</td>
    </tr>
  </table>

   Once randomized, use React components to present the key-value scramble in two separated columns - something like this: 
   <p align='center'>
<img src="assets/wordColumns.png" alt="Columns" width=350px/>
</p>

4. The goal of this app is for the user to match English words and their French counterparts. Build and implement a user-interaction component to that end - you have flexibility to implement a solution you think is appropriate. For example, the following image shows dragging lines to link up cells from one column to the next: 
<p align='center'>
<img src="assets/columnMap.gif" alt="Column Map" width=350px/>
</p>

5. Upon user clicking the "GRADE" button: 
 * display the total percentage correct
 * change "GRADE" to "GO!" (reset to initial app state)


---

## Submission

- **Ensure that your project runs fully BEFORE submission!**

- include a `README.md` file with instructions to build and run the app. Be sure to document any requirements (assume developers reading this could be running on Windows, Mac, or Linux workstations)

- Compress your files for submission - if a git repository, feel free to include history in the zip/gzip.

- Submit your project via email to `parham@cascadedebt.com`.  Alternatively, you can also upload it to Google Drive, One Drive, Dropbox, Box - any file sharing service, so long as a link is included in the email.
