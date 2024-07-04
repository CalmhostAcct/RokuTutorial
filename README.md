<h1>Roku App Tutorial</h1>
<p>Step 1: create a new directory by using ``mkdir {application_name}``. Today I will be using ``mkdir rokuapplication``</p><br>
<p>Step 2: cd into it by using ``cd {application_name}`` </p><br>
<p>Step 3: download the "hello world" program by using ``wget https://github.com/CalmhostAcct/RokuTutorial/raw/main/hello-world.zip``</p><br>
<p>Step 4: unzip it by using ``unzip hello-world.zip``</p><br>
<p>Step 5 (optional): delete it by using ``rm hello-world.zip``</p><br>
<p>Step 6: edit manifest by typing ``nano manifest``. You can change the app's title, version, icon, etc.</p><br>
<p>Step 7: edit code by typing ``cd source & nano Main.brs``. You can change the how the app will behave.</p><br>
<p>Step 8: edit styling code by typing ``cd compenots & nano helloworld.xml``. You can change the how the app will look.</p><br>
<p>Step 9: download node.js and npm ``sudo apt-get install nodejs npm``. This will help install libraries. </p><br>
<p>Step 10: install brs ``npm install -g @rokucommunity/brs``. This will run BrightScript code. </p><br>
<p>Step 11: install brighterscript ``npm install brighterscript -g``. This will compile BrightScript code. </p><br>
<p>Step 12 (optional): test the code by typing ``cd source & brs Main.brs``. This will compile BrightScript code. </p><br>
<p>Step 13: compile the code by moving to root channel directory and type ``bsc``. This will compile BrightScript code. </p><br>


