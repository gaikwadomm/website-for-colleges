# website-for-colleges
Builting website for first year project.
<br>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        div#lab102{
        z-index:1;
    position:absolute;
    top:15px;
    left: 5px;
    width: 150px;
    height: 120px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }  
        
    div#lab101{
    z-index:1;
    position:absolute;
    top:146px;
    left: 5px;
    width: 150px;
    height: 120px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
        
    div#stairs{
     z-index:1;
    position:absolute;
    top:277px;
    left: 5px;
    width: 100px;
    height: 75px;
    background-color: rgba(0, 0, 0, 0.497);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
        
    div#store{
        z-index:1;
    position:absolute;
    top:363px;
    left: 5px;
    width: 150px;
    height: 75px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
        
    div#exam{
        z-index:1;
    position:absolute;
    top:449px;
    left: 5px;
    width: 300px;
    height: 200px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
        
    div#pg{
        z-index:1;
    position:absolute;
    top:449px;
    left: 316px;
    width: 75px;
    height: 200px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
     writing-mode: vertical-lr;
    }
        
    div#stairs1{
        z-index:1;
    position:absolute;
    top:524px;
    left: 402px;
    width: 80px;
    height: 125px;
    background-color: rgba(0, 0, 0, 0.497);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    }
        
    div#admin{
        z-index:1;
    position:absolute;
    top:449px;
    left: 493px;
    width: 340px;
    height: 200px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    }
    
    div#estate{
        z-index:1;
    position:absolute;
    top:449px;
    left: 844px;
    width: 70px;
    height: 200px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
     writing-mode: vertical-lr;
    }
    
    div#cr12{
        z-index:1;
    position:absolute;
    top:449px;
    left: 925px;
    width: 200px;
    height: 200px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    
    }
    
    div#cr13{
        z-index:1;
    position:absolute;
    top:229px;
    left: 925px;
    width: 200px;
    height: 170px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    }
    
    div#computer{
        z-index:1;
    position:absolute;
    top:15px;
    left: 925px;
    width: 200px;
    height: 203px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    }
    
    div#toilet{
        z-index:1;
    position:absolute;
    top:15px;
    left: 844px;
    width: 70px;
    height: 100px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
    
    div#store1{
        z-index:1;
    position:absolute;
    top:126px;
    left: 804px;
    width: 110px;
    height: 70px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
    
    div#stairs2{
        z-index:1;
    position:absolute;
    top:15px;
    left: 723px;
    width: 110px;
    height: 70px;
    background-color: rgba(0, 0, 0, 0.497);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
    
    div#central{
        z-index:1;
    position:absolute;
    top:15px;
    left: 447px;
    width: 265px;
    height: 200px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
    
    div#cr11{
        z-index:1;
    position:absolute;
    top:15px;
    left: 204px;
    width: 190px;
    height: 130px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;
    }
    
    div#girls{
        z-index:1;
    position:absolute;
    top:156px;
    left: 204px;
    width: 190px;
    height: 130px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    }
    
    div#toilet1{
        z-index:1;
    position:absolute;
    top:297px;
    left: 204px;
    width: 90px;
    height: 40px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    }
    
    div#toilet2{
        z-index:1;
    position:absolute;
    top:347px;
    left: 303px;
    width: 91px;
    height: 50px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    }
    
    div#vice{
        z-index:1;
    position:absolute;
    top:292px;
    left: 405px;
    width: 60px;
    height: 105px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: small;
     border-radius: 5px; 
    }
    
    div#placement{
        z-index:1;
    position:absolute;
    top:292px;
    left: 476px;
    width: 60px;
    height: 105px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: x-small;
     border-radius: 5px; 
    }
    
    div#principle{
        z-index:1;
    position:absolute;
    top:292px;
    left: 547px;
    width: 150px;
    height: 105px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px; 
    }
    
    div#board{
        z-index:1;
    position:absolute;
    top:292px;
    left: 708px;
    width: 150px;
    height: 105px;
    background-color: rgba(0, 0, 0, 0.095);
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     border-radius: 5px;   
    }
    
    div#computer:hover,div#lab102:hover,div#lab101:hover{
    background-color: rgba(208, 255, 0, 0.237);
    text-shadow:  6px 7px 3px rgba(0, 0, 0, 0.441);
    
    
    }
    
    div#cr11:hover,div#cr12:hover,div#cr13:hover{
    background-color: rgba(73,230,73,0.489);
    text-shadow:  6px 7px 3px rgba(0, 0, 0, 0.485);
    }
    
    div#toilet:hover,div#toilet1:hover,div#toilet2:hover{
    background-color: rgba(120, 185, 242, 0.47);
    text-shadow:  6px 7px 3px rgba(0, 0, 0, 0.485);
    }
    
    div#exam:hover,div#central:hover{
    background-color: rgba(206, 89, 89, 0.486);
    text-shadow:  6px 7px 3px rgba(0, 0, 0, 0.485);
    }
    
    div#pg:hover{
    background-color: blueviolet;
    text-shadow:  6px 7px 3px rgba(0, 0, 0, 0.485);
    
    }
    
    
    div#first{
    z-index:1;
    position:absolute;
    top:745px;
    left: 200px;
    width: 5px;
    height: 5px;
    
    background-color: white;
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     text-decoration: none;
     color: black;
    
    }
    
    div#second{
    z-index:1;
    position:absolute;
    top:745px;
    left: 215px;
    width: 5px;
    height: 5px;
    
    background-color: white;
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     text-decoration: none;
     color: black;
    }
    
    div#third{
    z-index:1;
    position:absolute;
    top:745px;
    left: 230px;
    width: 5px;
    height: 5px;
    
    background-color: white;
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     text-decoration: none;
     color: black;
    }
    
    div#fourth{
    z-index:1;
    position:absolute;
    top:745px;
    left: 245px;
    width: 5px;
    height: 5px;
    
    background-color: white;
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     text-decoration: none;
     color: black;
    }
    
    div#fifth{
    z-index:1;
    position:absolute;
    top:745px;
    left: 260px;
    width: 5px;
    height: 5px;
    
    background-color: white;
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     text-decoration: none;
     color: black;
    }
    
    div#sixth{
    z-index:1;
    position:absolute;
    top:745px;
    left: 275px;
    width: 5px;
    height: 5px;
    
    background-color: white;
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     text-decoration: none;
     color: black;
    }
    
    div#seventh{
    z-index:1;
    position:absolute;
    top:745px;
    left: 290px;
    width: 5px;
    height: 5px;
    
    background-color: white;
    border: 1px solid black;
    padding: 5px;
    margin: 10px;
    
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-wrap: balance;
     font-size: large;
     text-decoration: none;
     color: black;
    }
    
    div#heading{
    position: absolute;
    top: 690px;
    left: 15px;
    text-shadow:  6px 7px 3px rgba(0, 0, 0, 0.441);

    }
    </style>
    <title>1FLOOR</title>
</head>
<body>
       <div id="heading"><h1>1<sup>st</sup></sup>FLOOR</h1></div>
    <div id="lab102">CHEMISTRY LAB-102</div>
    <div id="lab101">MECHANICS LAB-101</div>
    <div id="stairs">STAIRS</div>
    <div id="store">STORE ROOM</div>
    <div id="exam">EXAM ROOM</div>
    <div id="pg">PG  CLASS ROOM</div>
    <div id="stairs1">STAIRS</div>
    <div id="admin">ADMINISTRATIVE OFFICE</div>
    <div id="estate">ESTATE MANAGER</div>
    <div id="cr12">CR-12</div>
    <div id="cr13">CR-13</div>
    <div id="computer">COMPUTER ORGANIZATION LAB-103</div>
    <div id="toilet">TOILET</div>
    <div id="store1">STORE ROOM</div>
    <div id="stairs2">STAIRS</div>
    <div id="central">CENTRAL COMPUTING FACILITY</div>
    <div id="cr11">CR-11</div>
    <div id="girls">GIRLS COMMON ROOM</div>
    <div id="toilet1">TOILET</div>
    <div id="toilet2">TOILET</div>
    <div id="vice">VICE PRINCIPLE CABIN</div>
    <div id="placement">PLACEMENT ROOM</div>
    <div id="principle">PRINCIPLE'S ROOM</div>
    <div id="board">BOARD ROOM</div>
    <div id=""></div>
    <div id=""></div>
    <div id=""></div>
    <a href="C:\Users\Om Gaikwad\OneDrive\Desktop\CLASS AT GLANCE\1FLOOR.html"><div id="first">1</div></a>
    <a href="C:\Users\Om Gaikwad\OneDrive\Desktop\CLASS AT GLANCE\2FLOOR.html"> <div id="second">2</div></a>
    <a href="C:\Users\Om Gaikwad\OneDrive\Desktop\CLASS AT GLANCE\3FLOOR.html"> <div id="third">3</div></a>
    <a href="C:\Users\Om Gaikwad\OneDrive\Desktop\CLASS AT GLANCE\4FLOOR.html"> <div id="fourth">4</div></a>
    <a href="C:\Users\Om Gaikwad\OneDrive\Desktop\CLASS AT GLANCE\5FLOOR.html"> <div id="fifth">5</div></a>
     <a href="C:\Users\Om Gaikwad\OneDrive\Desktop\CLASS AT GLANCE\6FLOOR.html"><div id="sixth">6</div></a>
    <a href="C:\Users\Om Gaikwad\OneDrive\Desktop\CLASS AT GLANCE\7FLOOR.html"> <div id="seventh">7</div></a>
    <p></p>
    <script>
        // Check if the URL has a hash fragment
        if (window.location.hash) {
            // Get the classroom ID from the hash fragment
            var selectedRoom = window.location.hash.substring(1);
    
            // Highlight the classroom element
            var roomElement = document.getElementById(selectedRoom);
            if (roomElement) {
                roomElement.style.backgroundColor = "rgba(73,230,73,0.489)"; // Change color to indicate presence
                roomElement.innerHTML = facultyname;  // Display faculty name in the room if needed
            }
        }
    </script>

    
</body>
</html>
