<html>
        <title>Chapters Of Me</title>
  <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding: 50px;
        }

        .card {
            background: black;
            padding: 30px;
            max-width: 400px;
            margin: auto;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        button {
            margin: 20px;
            padding: 20px 50px;
            font-size: 18px;
            cursor: pointer;
            border: none;
            border-radius: 30px;
            background-color:black;
            color: white;
        }
        button:hover {
            background-color: red;
        }
    </style>
<center>
      <h1><u style="color: black;"><b> ABOUT ME </u></h1>

<div class="card">
      <p style="color:white;">My name is M.HaaziqSohail.I am a student of Class 9 who is dedicated to personal growth and academic improvement. I take my studies seriously and strive to perform well in all subjects through discipline and consistent effort. Along with academics, I actively participate in sports, especially basketball, which has helped me develop important qualities such as teamwork, leadership, and physical fitness. Playing basketball has taught me the value of perseverance, time management, and self-confidence. I believe that balancing education with extracurricular activities is essential for overall development. My goal in life is to become a successful man who contributes positively to society and supports my family with honesty and hard work. I am determined to face challenges with courage and continue improving myself to achieve my ambitions through dedication and strong moral values.</p>
 <ul>
<li style="color:white;"> I am always eager to learn new skills that help in my overall personality development.</li>
<li style="color:white;">I try to remain positive and focused even when facing difficulties.</li>
<li style="color:white;">I understand the importance of hard work and consistency in achieving long-term success.</li>
<li style="color:white;">I aim to become a responsible citizen who contributes to the progress of the nation.</li>
</div>
</center>
<button onclick="showMessage()">About Me</button>
        <button onclick="changeColor()">Change Background</button>
        <button onclick="showHobby()">My Hobby</button>
<button onclick="showFamily()">Family</button>

<p id="output"></p>
</div>
  </body>

<script>
        function showMessage() {
            window.scrollTo(0, 0);
}

        function changeColor() {
            document.body.style.backgroundColor =
                "#" + Math.floor(Math.random()*16777215).toString(16);
        }
        function showHobby() {
            document.getElementById("output").innerText = "Sketching is a hobby that plays a significant role in my life, as it allows me to express creativity while developing important skills. Through sketching, I observe my surroundings more carefully and translate ideas, emotions, and details into visual form. This practice enhances my imagination, concentration, and attention to detail, while also encouraging patience and discipline. Sketching provides a sense of calm and relaxation, helping me manage stress and remain focused. Over time, it has strengthened my confidence and creativity, making it not only an enjoyable pastime but also a meaningful tool for personal growth and self-expression.!";
        }
function showFamily() {
            document.getElementById("output").innerText = "My family is a central source of strength and stability in my life. We are bound by mutual respect, shared values, and a strong sense of responsibility toward one another. Each member contributes uniquely to our collective growth, creating an environment that encourages learning, integrity, and perseverance. Through both challenges and achievements, my family provides consistent support and thoughtful guidance. This foundation has shaped my character, strengthened my resilience, and continues to influence the way I approach personal and professional goals.!";
        }
    </script>

</html>
