# Assingment 2

## html-ABC-college

One Home page that leads to other pages. The Home page should contain the name of the City as heading along with a logo. There should be a tab with the following links:
 Home;
 Heritage;
 Hotel Booking;
 Gallery.
There should be an appropriate description of the college on the home page.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website - Academics</title>
</head>
<body>
    <header>
        <div class="container">
            <img src="c:\Users\Lenovo\Downloads\sairam.png" alt="College Logo">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="academics.html">Academics</a></li>
                    <li><a href="admission.html">Admission</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container">
        <section>
            <h2>Academics</h2>
            <p>The Sairam Engineering College has an excellent academic coordination methodology which has evolved over a period of more than 17 years and 
                has been producing excellent results in terms of students pass percentage and university ranks.
                 
            </p>
            <ul>
                <li>Science
                    <ul>
                        <li><a href="courses/computer-science.html">Computer Science</a></li>
                        <li><a href="courses/mathematics.html">Mathematics</a></li>
                    </ul>
                </li>
                <li>Arts
                    <ul>
                        <li><a href="courses/english.html">English</a></li>
                        <li><a href="courses/sociology.html">Sociology</a></li>
                    </ul>
                </li>
                <li>Commerce
                    <ul>
                        <li><a href="courses/economics.html">Economics</a></li>
                        <li><a href="courses/business-management.html">Business Management</a></li>
                    </ul>
                </li>
            </ul>
        </section>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2024 Sairam Engineering College. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website - Admission</title>
</head>
<body>
    <header>
        <div class="container">
            <img src="c:\Users\Lenovo\Downloads\sairam.png" alt="College Logo">
            <h1>SNS Engineering College</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="academics.html">Academics</a></li>
                    <li><a href="admission.html">Admission</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container">
        <section>
            <h2>Admission</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                
                <label for="course">Select Course:</label>
                <select id="course" name="course" required>
                    <option value="">--Select Course--</option>
                    <option value="Computer Science">Computer Science</option>
                    <option value="Mathematics">Mathematics</option>
                    <option value="English">English</option>
                    <option value="Sociology">Sociology</option>
                    <option value="Economics">Economics</option>
                    <option value="Business Management">Business Management</option>
                </select><br><br>
                
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>
                
                <input type="submit" value="Submit">
            </form>
        </section>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2024 Sairam Engineering College. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Science Course</title>
</head>
<body>
    <header>
        <div class="container">
            <img src="c:\Users\Lenovo\Downloads\sairam.png" alt="College Logo">
            <nav>
                <ul>
                    <li><a href="../index.html">Home</a></li>
                    <li><a href="../academics.html">Academics</a></li>
                    <li><a href="../admission.html">Admission</a></li>
                    <li><a href="../gallery.html">Gallery</a></li>
                </ul>
            </nav>
            <h1>Computer Science</h1>
            <p>Embark on a journey of innovation and excellence with the Department of Computer Science and Engineering, a cornerstone of academic prowess of SNS Engineering College since its inception in 2001. What began with an intake of 60 students has evolved into a dynamic hub of learning, now accommodating 240 bright minds by the year 2023-24. Our commitment to growth is evident in our consistent expansion, from 120 students in 2005-2006 to 180 in 2017-18.
                At our department, we nurture talents through our esteemed B.E. and M.E. programs in Computer Science and Engineering. Guided by a team of 36 dedicated faculty members, comprising seasoned professionals with diverse expertise, we ensure a nurturing environment for academic excellence. Among them, 13 hold doctorates, while others are actively pursuing their Ph.D.s, embodying our commitment to staying at the forefront of research and knowledge.</p>
        <h2>FACULTY</h2>
        <ul>
            <label>Faulty Handling Various CS Department Subjects:</label>
            <li>Visak</li>
            <li>Ramya</li>
            <li>Ravindran</li>
            <li>Rekha</li>
        </ul>
        <html>
<head>
<title> TIME TABLE </title>   
</head>
<body>
<br>
<table align="center" width="1000" border="5" bgcolor="Lavender" cellspacing="12" cellpadding="12">
<caption><b>SLOT TIME TABLE</b></caption>

<tr bgcolor="CornflowerRed">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday </th>
</tr>
<tr align="center">
   <th bgcolor="CornflowerRed"> 8-10 </th>
   <td bgcolor="red"><b> Fundamentals Of Web Development Application</b></td>
   <td> Free Slot </td>
   <td bgcolor="lightgreen"><b>Problem sloving And Python Programming</b></td>
   <td> Free Slot </td>
   <td> Free Slot </td>
   <td> Free Slot </td>
</tr>
<tr align="center">
    <th bgcolor="CornflowerRed"> 10-12 </th>
    <td> Free Slot</td>
    <td bgcolor="yellow"><b>Parallel Computing Architecture</b></td>
    <td bgcolor="yellow"><b>Parallel Computing Architecture</b></td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td bgcolor="grey"><b>Programming in C</b></td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 12-1 </th>
    <th colspan="1">LUNCH</th>
    <th bgcolor="white" colspan="1">MENTOR MEET</th>
    <td colspan="6" align="center"><b>LUNCH</b></td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 1-3 </th>
    <td > Free SLOT </td>
    <td bgcolor="purple"><b>Intellectual Property Rights</b> </td>
    <td bgcolor="grey"><b> Programming in C</b> </td>
    <td bgcolor="red"><b> Fundamentals Of Web Development Application</b>
    <td bgcolor="red"><b> Fundamentals Of Web Development Application</b>
    <td bgcolor="pink"><b>Advanced Quantitative and Logical Reasoning</b> </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerRed"> 3-5 </th>
    <td> Free Slot </td>
    <td bgcolor="lightgreen"><b>Problem Solving and Python Programming</b></td>
    <td bgcolor="purple"><b>Intellectual Property Rights</b></td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
</tr>
</tr>
</table>
<br>
<br>
<table align="center" border="8" cellspacing="12" cellpadding="12">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td bgcolor="lightgreen"> 1. </td>
<td bgcolor="lightgreen"> 19CS301 </td>
<td bgcolor="lightgreen">  Python Programming </td>
</tr>
<tr align="center">
<td bgcolor="red"> 2. </td>
<td bgcolor="red"> 19AI414 </td>
<td bgcolor="red">  Web Application Development </td>
</tr>
<tr align="center">
<td bgcolor="grey"> 3. </td>
<td bgcolor="grey"> 19CS302 </td>
<td bgcolor="grey"> Programming in C </td>
</tr>
<tr align="center">
<td bgcolor="yellow"> 4. </td>
<td bgcolor="yellow"> 19AI407 </td>
<td bgcolor="yellow"> Parallel Computing </td>
</tr>
<tr align="center">
<td bgcolor="purple"> 5. </td>
<td bgcolor="purple"> 19ME531 </td>
<td bgcolor="purple"> Intellectual Property Rights </td>
</tr>
<tr align="center">
<td bgcolor="pink"> 6. </td>
<td bgcolor="pink"> 19EY704 </td>
<td bgcolor="pink"> Advanced Quantitative  </td>
</tr>
</html>

            </div>
    </header>
```
## OUTPUT:
![Screenshot (40)](https://github.com/DHARSHINISENTHILKUMAR/html-ABC-college/assets/113699377/d4c587b8-c6c9-4d0b-b0d1-e9e1bca54be9)
![Screenshot (41)](https://github.com/DHARSHINISENTHILKUMAR/html-ABC-college/assets/113699377/c3544a9c-a10a-4fdc-b815-fc803c0705c7)
![Screenshot (43)](https://github.com/DHARSHINISENTHILKUMAR/html-ABC-college/assets/113699377/24886c1c-ee86-4409-a0fc-9820075d61e5)
![Screenshot (44)](https://github.com/DHARSHINISENTHILKUMAR/html-ABC-college/assets/113699377/8812842c-1653-43ca-8660-66288b487a6d)
![Screenshot (45)](https://github.com/DHARSHINISENTHILKUMAR/html-ABC-college/assets/113699377/3c31177c-c146-458e-8e9d-63a2275b7092)


# Assingment 1:
```
<!DOCTYPE html>
<html>
<head>
    <title>My Day</title>
    <style>
        .container {
            width: 40%;
            margin: 0 auto;
            border-style: double;
            padding: 10px;
        }
        .header {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            padding: 0px;
        }
        table {
            width: 100%;
            border-style:none;
            padding: 0px;
        }
        td {
            border-style: double;
            padding: 20px;
            
        }
        .section-title {
            font-size: 20px;
            font-weight: bold;
        }
        .task-list {
            list-style-type: none;
            padding-left: 500px;
        }
        .task-list li {
            margin: 15px 0;
        }
        .subtask {
            margin-left: 20px;
        }
        .image-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .image-container img {
            width: 45%;
            margin: 1px 0;
            border: 1px solid #000;
        }
        .things-to-watch-title {
            border-style:double ;
            background-color: yellow;
            font-weight: bold;
            text-align: center;
            padding: 2px;
        }
        .image-container{
            border-style: double;
            padding: 1px;
        }

    </style>
</head>
<body>

<div class="container">

    <div class="header">My Day</div>
    <table>
        <tr>
            <td style="width: 50%;">
                <div class="section-title">1. Wake up early</div>
                <ul class="task-list">
                    <li><b>5AM</b></li>
                    <li class="subtask">walk</li>
                    <li class="subtask">jog</li>
                </ul>
            </td>
            <td rowspan="3" style="width: 50%;">
                <div class="things-to-watch-title">Things to watch</div>
                <div class="image-container">
                    <img src="c:\Users\Lenovo\Downloads\food img.jfif" alt="Jogging">
                    <img src="c:\Users\Lenovo\Downloads\meeting.jfif" alt="Breakfast">
                    <img src="c:\Users\Lenovo\Downloads\coffeee pic.jfif" alt="Coffee">
                    <img src="c:\Users\Lenovo\Downloads\jogging.jfif" alt="Meeting">
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="section-title">2. Breakfast</div>
                <ul class="task-list">
                    <li><b>8AM</b></li>
                    <li class="subtask">eggs</li>
                    <li class="subtask">coffee</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>
                <div class="section-title">3. Go to Saveetha</div>
                <ul class="task-list">
                    <li><b>8AM</b></li>
                    <li class="subtask">attend classes</li>
                    <li class="subtask">to be continued</li>
                </ul>
            </td>
        </tr>
    </table>
</div>

</body>
</html>
```
## OUTPUT:
![Screenshot (42)](https://github.com/DHARSHINISENTHILKUMAR/html-ABC-college/assets/113699377/c0b75e04-ef23-4261-b794-5560f6d39211)







