Resource to learn about HTML: https://www.w3schools.com/html/
Resource to learn about CSS: https://www.w3schools.com/css/
Resource to learn about Github: https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners
How to clone from a github repository: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
How to download and use visual studio code: https://code.visualstudio.com/docs/introvideos/basics

# General description of the website structure:
The Home page of the website is in 'index.html' file. All the images and PDFs are in the assets folder. For each volumes, there are separate html pages. For example, 'VOL3.html' is the page for volume 3, 
and it links to the PDF file of volume 3. 

How to add a new volume to the website:
1. First, clone this repository, following the instruction in the fourth resource above. Open the folder in Visual studio code. 
2. Add cover image in the assets/img/ folder. 
3. Create a new file in the main folder and name it 'VOL#.html' where # is the number of the volume. 
4. Copy paste all the contents from 'VOL3.html' file to the newly created file. 
5. Upload the PDF files on OneDrive and get the embed link. In the copied file, search 'HERE1' and copy paste the embed link from one drive. This will upload the pdf in the page.
6. Upload the pdf in google drive . Give access to 'anyone with the link' and copy the link.
7. Search 'HERE2' and paste the link to the google drive. This is for the mobile view. 
8. Search 'HERE3' and copy paste from a line of code above and change the volume name. This is for the dropdown navigation bar. 
9. In index.html, search 'HERE1' and copy paste the gallery item code block (9 lines of code). Change the cover image, caption, and the file name.
10. Search 'HERE2' and copy paste from a line of code above and change the volume name. This is for the dropdown navigation bar. 

That's it! You can check the result by right clicking in the index.html file, and click 'Open with Live Server' to see the website locally. 

To publish the website, follow the instruction in this link: https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/

I recommend you to create your own git repository and save the changes there. Follow the instruction in the third link above.


