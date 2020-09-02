<!-- WEBSITE https://codepen.io/seth-bradshaw/pen/QWNqbEB?editors=1100
Copy the questions below into the first-lastname.txt file on your github repo - answer each question and then push your changes. 
    WEBSITE https://codepen.io/seth-bradshaw/pen/QWNqbEB?editors=1100
    
    1. What is Semantic HTML? 
    It is when a tag, class name, or ID have the same function of their name. For example <p> is a tag for a paragraph, <header> is for the header, etc.
    2. What is HTML used for? 
    HTML is used for the structure of a web site.
    3. What is an attribute and where do we put it? 
    Attributes are words inside the tag that control the element.
    4. What is the h1 tag used for? How many times should I use it on a page?
    The most important header, so it should only be used once.
    5. Name two tags that have required attributes
    <input> 
    <select>
    6. What do we put in the head of our HTML document?
     <head>
    7. What is an id? 
    An id is used for us to name an element to be called later in the program
    8. What elements can I add an id to? 
    all
    9. How many times can I use the same id on a page? 
    Once
    10. What is a class? 
    It is similar to an id but can apply to multiple elements
    11. What elements can I add a class to? 
    all
    12. How many times can I use the same class on a page? 
    however much you need
    13. How do I get my link to open in a new tab?
    href
    14. What is the alt attribute in the image tag used for? 
    provides different information for a use who can't view it
    15. How do I reference an id?
    href "#idname"
    16. What is the difference between a section and a div
    A section is a container for more containers that are under a single theme, while div is container with no special meaning.
    17. What is CSS used for? 
    for styling a website
    18. How to we select an element? Example - every h2 on the page
    h2 {
        font-size: 60px;
    }
    19. What is the difference between a class and an id? - Give me an example of when I might use each one
    An id can only be used for a single element, while class can be applied to multiple. Say I wanted to make every paragraph a certain font, then I would need to have a class so it will apply to all the elements. If I just want the header or footer to change color, then you would use an ID since you only have one header and footer.
    20. How do we select classes in CSS?
    .classname
    21. How do we select a p element with a single class of “human””?
    .human p {

    }
    22. What is a parent child selector? When would this be useful? 
    it is used to select elements under the same parent element. This would be useful if you wanted to make a font change to all paragraphs under the div element.
    23. How do you select all links within a div with the class of sidebar?
    .sidebar div a {

    }
    24. What is a pseudo selector?
    a word that specifies a special state for the element
    25. What do we use the change the spacing between lines?
    Line-Height
    26. What do we use to change the spacing between letters?
    letter-spacing
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
    uppercase, lowercase, capitalize
    28. How do I add a 1px border around my div that is dotted and black?
    div {
        border: 1px dotted black;
    }
    29. How do I select everything on the page? 
    * {

    }
    30. How do I write a comment in CSS?
    /**/
    31. How do I find out what file I am in, when I am using the command line? 
    The pwd command shows you where you are, but it also says in yellow in the terminal after the second /
    32. Using the command line - how do I see a list of files/folders in my current folder?
    ls
    33. How do I remove a file via the command line? Why do I have to be careful with this? 
    rm once deleted it is more than likely unable to be retrieved.
    34. Why should I use version control? 
    If you ruin your code, then you can go back to old versions, and it makes it possible to collaborate effectively
    35. How often should I commit to github?
    every 15 minutes
    36. What is the command we would use to push our repo up to github? 
    git push -u origin seth-bradshaw
    37. Walk me through Lambda's git flow. 
    You first need to fork the project in github, then add your TL as a callaborator in settings - manage access. Then you need to clone the repository. Then go into your terminal and cd to the directory, and git clone followed by the link of the project. Then enter cd and the new name for the repository, and create your own branch name by entering git checkout -b seth-bradshaw. To prepare the repo for committing enter git add ., followed by git commit -m "Description of what you did" to commit the changes made. You then need to push the changes to github by entering git push -u seth-bradshaw. Lastly, you will need to submit a pull request for the TL to review the project.
Stretch Questions

    1. What is the difference between an inline element and a block element?
    A block element typically will appear on another line, and you cannot place a block element within a in-line element. And in-line element behaves as a container in-line
    2. What happens when an element is positioned absolutely? 
    It position is pernament, and other elements are positioned as if it doesn't exist.
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width?


