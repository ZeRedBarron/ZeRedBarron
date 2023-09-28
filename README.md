<!DOCTYPE html>
<!-- Thanks to Quinn Hardbrook for scroll through animations-->
<html>
    <head>
        <meta charset="utf-8">
        <title>My Entry: The Kitty Express: Unfinished</title>
        <link href = "https://fonts.googleapis.com/css?family=Playfair+Display|PT+Serif|Zen+Dots&display=swap" rel="stylesheet">
        <style>
            body {
                font-size: 18px;
                font-family: "Aparajita", "PT Serif", "Cambria", serif;
            }
            
            ::-webkit-scrollbar {
                width: 10px;
            }
            ::-webkit-scrollbar-track {
                background: rgb(255, 255, 255);
                border-radius: 10px;
            }
            ::-webkit-scrollbar-thumb {
                background: rgba(0, 0, 0, 50);
                border-radius: 10px;
            }
            ::-webkit-scrollbar-thumb:hover {
                background: rgba(0, 0, 0, 150);
                border-radius: 10px;
            }
            
            @keyframes fadeIn {
                from {
                    opacity : 0;
                }
                to {
                    opacity : 1;
                }
            }
            
            @keyframes slideUp {
                from {
                    margin-top : 25px;
                    margin-bottom : 5px;
                }
                to {
                    margin-top : 10px;
                    margin-bottom : 10px;
                }
            }
            
            h1 {
                text-align: center;
            }
            
            h2 {
                text-align: center;
            }
            
            p {
                line-height: 1.4;
                font-size: 18px;
                text-indent: 60px;
                margin-top : 10px;
                margin-bottom : 10px;
            }
            
            
            .animate {
                animation: 0.8s slideUp;
            }
            
            #message {
                text-align: center;
                font-family: "Zen Dots", "Trivial", "Times new Roman", "Arial";
                padding: 40px;
            }
        </style>
    </head>
    <body>
        
    </body>
    <script>
        var allP = document.getElementsByTagName("p");
        var allH = document.getElementsByTagName("h1");
        var allH2 = document.getElementsByTagName("h2");
        
        function onScroll() {
            for(var i = 0; i < allP.length; i++) {
                if(allP[i].getBoundingClientRect().top <= window.innerHeight) {
                    allP[i].classList.add("animate");
                }
            }
            for(var i = 0; i < allH.length; i++) {
                if(allH[i].getBoundingClientRect().top <= window.innerHeight) {
                    allH[i].classList.add("animate");
                }
            }
            for(var i = 0; i < allH2.length; i++) {
                if(allH2[i].getBoundingClientRect().top <= window.innerHeight) {
                    allH2[i].classList.add("animate");
                }
            }
        }
        
        window.addEventListener("scroll", onScroll);
        
        window.scrollTo(0, 0);
    </script>
</html>

<!--
**ZeRedBarron/ZeRedBarron** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
