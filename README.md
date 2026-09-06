# school-admission-website
A simple school admission website created using HTML for practice and learning.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>school-admission-website</title>
</head>
<body>
    <header>
    <div>
        <h1>TGMS SCHOOL</h1>
        <p>
          <mark>Learn Today, Build Tomorrow, Dream Big, Work Hard, Stay Curious, and Create a Bright Future Through Knowledge , Discipline, Creativity, and C ontinuous Learning.</mark>
          
        </p>
        <nav>
            <a herf="#home">home</a> 
            <a herf="#about">about</a>
            <a herf="#students">students</a>
            <a herf="#subjacts">subjacts</a>
            <a  herf="#contact">contact</a>
        </nav>
    </div>
    </header>
    <hr>
    <main>
        <div>
            <section id="home page">
                <h2>welcome to staudent portal</h2>  
                <hr>
              <h3>this is school description</h3>
              <span>
                <p><i>Our school is a place where students learn, explore, create, and develop their skills.</i>
                    <br>
                    <br><u>We provide a friendly and supportive environment where every student gets opportunities to improve their knowledge, creativity, communication, discipline, and confidence.</u> <br>
                    <br><i> Our school focuses on education as well as sports, technology, cultural activities, and practical learning.</i><br> 
                    <br><b>Teachers guide students to understand their subjects clearly and encourage them to ask questions, think creatively, and solve problems.</b> <br>
                    <br><mark>We believe that education helps students become responsible, hardworking, confident, and successful members of society.</mark><br>
                    <br><i>Our goal is to provide quality education and help every student build a bright and successful future.</i></p><br>
              </span>
              <img src= 'Staples_High_School,_Westport,_CT.jpg' width="512xp" alt="school photo">
              <hr>
            </section>
        </div> 
      <br>
      <div>
        <section id="about school">
          
            <h2>About School</h2>     
          
            <h3>school history</h3>
          <span>
            <p><i>Our school was established to provide quality education and create
    opportunities for students to learn, explore, and develop their skills.</i><br>
              
              <u>Over the years, the school has grown into a place where students are
    encouraged to work hard, think creatively, and achieve their goals.</u>
</p> 
          </span>
          <hr>
          <h1>principal's messega</h1>
          <span>
            <p>
             <u> Principal's Message Dear Students, Parents, and Visitors, It gives me great pleasure to welcome you to our school website.</u>
             <br> Our school is committed to providing quality education and creating a safe, positive, and encouraging environment for every student.
             <mark><br> 
              We believe that education is not only about academic success, but also about developing good character, discipline, creativity, confidence, and responsibility.
             </mark>
             <i> We encourage our students to discover their talents, ask questions, learn from their experiences, and work towards their goals.</i>
             <br>
              <big>Our teachers and staff work together to support every student's growth and help them become responsible and successful citizens. I wish all our students the very best in their studies and future endeavors. Principal Model School </big> 
            </p>
          </span>
          <hr>
          <big>
            <strong>my school facilitis</strong>
          </big>
          <ol>
            <li>water</li>
            <li>coding class</li>
            <li>free food</li>
            <li>special teachers</li>
          </ol>
          <hr>
        </section>
      </div>
      <div>
        <section id="student registration">
          <h2>student registration form</h2>
          
          <form>
            <label>
              name
              <input type="text" placeholder="enter student name" name="name" id="name">
            </label>
            <br><br>
            <label>
              father name
              <input type="text"  placeholder="enter the father name" name="father" id="father">
            </label>
            <br><br>
            <label>
              mother name
              <input type="text" placeholder="enter the mother name" name="mothe" id="mother">
            </label>
            <br><br>
            <label>
              date of birth
              <input type="date" placeholder="enter the student date of birth"  name="date of birth" id="birth">
              <br><br>
            </label>
            <label>
              age
              <input type="number" placeholder="enter the age" name="age" id="age">
            </label>
            <br><br>
            <label>
             email
              <input type="email" placeholder="enter the email" name=" email" id="email">
            </label>
            <br><br>
            <label>
             phone number
               <input type="tel" placeholder="enter the phone number" name="phone number" id="phone number">
             </label>
             <br><br>
             <big>address</big>
             <br>
             <textarea type="text" placeholder="enter the address" id="address" name="address">
             </textarea>
             <br><br>
             <label>
              gender
              <input type="radio" name="gender" value="male">male
              <input type="radio" name="gender" value="famale">famale         
             </label>
             <br><br>
             
            <big>class</big>
            <select for="class" id="section1">
              <option value="class">1th class</option>
              <option value="class">2th class</option>
              <option value="class">3th class</option>
              <option value="class">4th class</option>
              <option value="class">5th class</option>
            </select>
          
          <br><br>
          <big>section</big>
            <select for="section" id="section2">
              <option value="section">A section</option>
              <option value="section">B section</option>
              <option value="section">C section</option>
              <option value="section">D section</option>
              <option value="section">E section</option>
            </select>
            <br><br>
            <label>
            roll number
               <input type="number" placeholder="enter the roll number" name="roll number" id="roll number">
             </label>
             <br><br>
             <label>
              password
                 <input type="password" placeholder="enter the password" name=" password" id=" password">
               </label>
               <br><br>
               <label for="profile">profile</label>
               <input type="file" id="profile" name="profile" accopt="image/*">
               <br><br>
             <label>
               chioce favorits  subjects
              <input type="checkbox" name="subjects" value="maths">maths
              <input type="checkbox" name="subjects" value="physic">physic 
              <input type="checkbox" name="subjects" value="python">python
              <input type="checkbox" name="subjects" value="c">c
              <input type="checkbox" name="subjects" value="c++">c++      
             </label>
             <br><br>
             <button type="resit">resit</button>
          </form>
        </section>
      </div>
    </main>
</body>
</html>
