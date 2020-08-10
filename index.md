## Welcome My ePortfolio Page

### Professional self-assessment
WIP

Code Review (click thumbnail to play video):

[![Code Review](https://i.vimeocdn.com/video/932425618_330x200.jpg)](https://vimeo.com/443077415)


### Software design and engineering project
[GitHub Link NGUsageGrapher](https://github.com/haydnady/NGUsageGrapher)

This software I developed named NGUsageGrapher is a graphing software that specifically graphs your nationalgrid usage data. This idea came from using Natinalgrid’s website and the need of wanting features that help me analyses my electricity usage over the years, as the nationalgrid website was limited on that aspect. I started this project in 2020. I developed this from scratch using skills from Python courses and also using plotly (web-based data science graphing tool/library, with interactive graph for analytical applications). 
I selected this project because it will help illustrate my skills working with files in python, analytical skills and the ability to use python with web-based libraries. The python module used will hopefully show my skills in python using libraries, the code itself will show consistency and attention to details in programming, and the graph will show my understanding of analyzing data using software.
I learned a lot more about using python module pandas and I also feel more comfortable using plotly the more I use it in my projects. 
Here’s a visual workflow of the software.
![Image of process flow](https://raw.githubusercontent.com/haydnady/haydnady.github.io/master/img/Nationalgrid%20Software%20Outline.png)

Image of interactive graph generated.
![Image of graph](https://raw.githubusercontent.com/haydnady/NGUsageGrapher/master/img/graphScreenshot.png)


### Algorithms and data structure project
[GitHub Link PythonLinkedListGUI](https://github.com/haydnady/PythonLinkedListGUI)

This software I developed named PythonLinkedListGUI is a GUI that shows the linked list when data is added, removed or searched. This idea came from doing linked list projects in C++ and Java. I started this project in 2020. I developed this from scratch using skills from Python courses and also using Qt, “Qt is the faster, smarter way to create innovative devices, modern UIs & applications for multiple screens. Cross-platform software development at its best.” - [Qt](https://www.qt.io/)
![Image of application](https://github.com/haydnady/PythonLinkedListGUI/blob/master/img/uiScreenshot.JPG)


### Algorithms and data structure project
[GitHub Link PythonLinkedListGUI](https://github.com/haydnady/PythonLinkedListGUI)

This project is a MongoDB project (named MongoDBCRUD) from my CS Advanced Programming Concepts course. It was created in 2020. The software allows one to perform CRUD operation on a MongoDB database (for example: read, add, update, delete). 
Including this project in my ePortfolio will help show my ability to work with databases. I improved the project by adding error handling. I also made it so it would take user input, instead of hardcoding everything in the code. I also cleaned and formatted the code for maintainability and better readability. 


```markdown
Code example of creating and reading a document using Python and MongoDB


# ============================================== Create Docs
def insert_document(document):
    status = True

    try:
        collection.insert_one(document)
    except Exception as e:
        print("\n\t -->", e)
        status = False

    return status

# ============================================== Read Docs
def read_document(document):
    result = ""

    try:
        result = collection.find_one(document)
    except Exception as e:
        print("\n\t -->", e)

    return result

```
